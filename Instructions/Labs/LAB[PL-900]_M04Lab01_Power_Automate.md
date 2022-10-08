---
lab:
  title: 'النشاط المعملي 4: كيفية إنشاء حل تلقائي'
  module: 'Module 4: Get Started with Power Automate'
---

# <a name="lab-4-how-to-build-an-automated-solution"></a>النشاط المعملي 4: كيفية إنشاء حل تلقائي

## <a name="scenario"></a>السيناريو

Bellows College is an educational organization with multiple buildings on campus. Campus visitors are currently recorded in paper journals. The information is not captured consistently, and there are no means to collect and analyze data about the visits across the entire campus.

ترغب إدارة الحرم الجامعي في تحديث نظام تسجيل الزوار، بحيث يتم التحكم في الوصول إلى المباني من قبل أفراد الأمن، ويجب أن تكون جميع الزيارات مسجلة مسبقًا ويتم تسجيلها من قبل مضيفيها.

خلال هذه الدورة التدريبية، ستقوم بإنشاء تطبيقات وتفعيل التشغيل الآلي لتمكين موظفي إدارة وأمن Bellows College من إدارة الوصول إلى مباني الحرم الجامعي والتحكم فيه.

في هذا التمرين المعملي، ستقوم بإنشاء تدفق Power Automate لإرسال بريد إلكتروني إلى زائر عند جدولة الزيارة.

## <a name="high-level-lab-steps"></a>خطوات معملية عالية المستوى

تم تحديد التالي كمتطلبات يجب عليك تنفيذها لإكمال المشروع:

- يجب إعلام جهات الاتصال عبر البريد الإلكتروني عند جدولة الزيارة.

## <a name="prerequisites"></a>المتطلبات الأساسية

- إكمال **الوحدة 0 المختبر 0 - التحقق من صحة بيئة المختبر**
- إكمال **الوحدة 2 النشاط المعملي 1 - نمذجة البيانات**
- إكمال **الوحدة 2 النشاط المعملي 3 - كيفية إنشاء تطبيق يستند إلى النموذج**
- تم إنشاء جهة اتصال John Doe باستخدام عنوان بريد إلكتروني شخصي

## <a name="exercise-1-create-visit-notification-flow"></a>التمرين 1: إنشاء تدفق Visit Notification

<bpt id="p1">**</bpt>Objective:<ept id="p1">**</ept> In this exercise, you will create a Power Automate flow that implements the requirement. The visitor should be sent an email that includes the unique code assigned to the visit when a visit is created.

### <a name="task-1-create-a-flow"></a>المهمة \#1: إنشاء تدفق

1.  Navigate to <ph id="ph1">&lt;https://make.powerapps.com&gt;</ph>. You may need to reauthenticate - click <bpt id="p1">**</bpt>Sign in<ept id="p1">**</ept> and follow instructions if needed.

2.  حدد بيئة **الممارسة (الأحرف الأولى من اسمي)** في أعلى اليمين، إذا لم تكن محددةً بالفعل.

3.  في شريط التنقل الأيسر، حدد **تدفقات**.

4.  إذا تمت مطالبتك، فحدد **بدء الاستخدام**.

5.  انقر فوق **تدفق جديد** وحدد **تدفق سحابي تلقائي**.

6.  أدخل "إعلام الزيارة" **لاسم التدفق**.

7.  في **اختيار مشغل التدفق لديك**، ابحث عن **Dataverse**.

8.  حدد المشغل **When a row is added, modified or deleted**، ثم انقر فوق **Create**.

9.  بادر بملء شروط المشغل للتدفق:

    1.  تحديد **Added** لـ **Change type**

    2.  حدد **الزيارات** في **اسم الجدول**

    3.  حدد **المنظمة** في **النطاق**

    4.  On the trigger step, click the ellipsis (<bpt id="p1">**</bpt>...<ept id="p1">**</ept>) and click <bpt id="p2">**</bpt>Rename<ept id="p2">**</ept>. Rename this trigger <bpt id="p1">**</bpt>"When a visit is added"<ept id="p1">**</ept>. This is a good practice, so you and other flow editors can understand the purpose of the step without having to dive into the details.

### <a name="task-2-create-a-step-to-get-the-visitor-row"></a>المهمة \#2: بادر بإنشاء خطوة صف "الوصول إلى الزائر"

1.  Bellows College مؤسسة تعليمية يضم حرمها الجامعي العديد من المباني.

2.  ابحث عن **Dataverse**.

3.  حدد إجراء **الوصول إلى صف حسب المعرّف**.

4.  حدد **جهات الاتصال** في **اسم الجدول**

5.  يتم حاليًا تسجيل زوار الحرم الجامعي في دفاتر عمل ورقية.

6.  ولا يتم جمع المعلومات بشكل متسق، ولا توجد وسيلة لجمع وتحليل البيانات المتعلقة بالزيارات عبر الحرم الجامعي بأكمله.

7.  On this action, click the ellipsis (<bpt id="p1">**</bpt>...<ept id="p1">**</ept>) and click <bpt id="p2">**</bpt>Rename<ept id="p2">**</ept>.
        Rename this action <bpt id="p1">**</bpt>"Get the Visitor"<ept id="p1">**</ept>. This is a good practice, so you and other flow editors can understand the purpose of the step without having to dive into the details.

### <a name="task-3-create-a-step-to-send-an-email-to-the-visitor"></a>المهمة \#3: إنشاء خطوة لإرسال بريد إلكتروني إلى الزائر

1.  Click <bpt id="p1">**</bpt>+ New step<ept id="p1">**</ept>. This is the step that will send an email to the visitor.

2.  ابحث عن *mail* وحدد موصل **Office 365 Outlook** وإجراء **Send an email (V2)** .

3.  إذا طُلب منك قبول الأحكام والشروط لاستخدام هذا الإجراء، فانقر فوق **قبول**.

4.  حدد **إضافة محتوى ديناميكي** ضمن الحقل **إلى**. 
    
5.  حدد **البريد الإلكتروني** من قائمة المحتوى الديناميكي.
        > Notice that it is beneath the **Get the visitor** header. This means you
        are selecting the Email that is related to the Visitor that you looked
        up in the previous step.

6.  أدخل **زيارتك المجدولة إلى Bellows College** في حقل **الموضوع**.

7.  أدخل النص التالي في **نص البريد الإلكتروني**:

>   Dynamic content needs to be placed where fields are named in brackets. It is recommended to copy &amp; paste all text first and then add dynamic content in the correct places.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   Dear {First Name},

   You are currently scheduled to visit Bellows Campus from {Scheduled Start} until {Scheduled End}.

   Best regards,

   Campus Administration
   Bellows College
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

8.  Highlight the <bpt id="p1">**</bpt>{First Name}<ept id="p1">**</ept> text. Replace it with the <bpt id="p1">**</bpt>First Name<ept id="p1">**</ept> field from the <bpt id="p2">**</bpt>Get the Visitor<ept id="p2">**</ept> step.

9.  Highlight the <bpt id="p1">**</bpt>{Scheduled Start}<ept id="p1">**</ept> text. Replace it with the <bpt id="p1">**</bpt>Scheduled Start<ept id="p1">**</ept> field <bpt id="p2">**</bpt>When a visit is added<ept id="p2">**</ept> step.

10.  Highlight the <bpt id="p1">**</bpt>{Scheduled End}<ept id="p1">**</ept> text. Replace it with the <bpt id="p1">**</bpt>Scheduled End<ept id="p1">**</ept> field from the <bpt id="p2">**</bpt>When a visit is added<ept id="p2">**</ept> step.

11.  انقر فوق **Save**.

Leave this flow tab open for the next task. You flow should look approximately like the following:

![مثال على خطوات التدفق.](media/4-Flow.png)

### <a name="task-4-validate-and-test-the-flow"></a>المهمة \#4: التحقق من صحة التدفق واختباره

1.  افتح علامة تبويب جديدة في متصفحك وانتقل إلى <https://make.powerapps.com>.

2.  حدد بيئة **الممارسة (الأحرف الأولى من اسمي)** في أعلى اليمين، إذا لم تكن محددةً بالفعل.

3.  انقر فوق **تطبيقات** وحدد التطبيق **المستند إلى إدارة الحرم الجامعي** الذي أنشأته مسبقًا.

3.  اترك علامة تبويب المستعرض مفتوحة، وانتقل مرة أخرى إلى علامة التبويب السابقة التي بها تدفقك.

4.  On the command bar, click <bpt id="p1">**</bpt>Test<ept id="p1">**</ept>. Select <bpt id="p1">**</bpt>Manually<ept id="p1">**</ept> and then click <bpt id="p2">**</bpt>Test<ept id="p2">**</ept>.

5.  انتقل إلى علامة تبويب المستعرض باستخدام التطبيق المستند إلى النموذج. 

6.  باستخدام جزء التنقل على اليسار، حدد **الزيارات**

6. اضغط على الزر **+ جديد** لإضافة سجل **زيارة** جديد.

7. أكمل سجل "الزيارة" كما يلي:

    -   **Name:** اختبار زيارة

    -   **الزائر:** John Doe

    -   **البداية المجدولة:** غداً الساعة 8:00 صباحاً

    -   **النهاية المجدولة:** غداً الساعة 9:00 صباحاً

8. حدد زر **حفظ وإغلاق**.

9. Navigate to the browser tab with your flow test running. After a short delay, you should see the flow running. This is where you can catch any issues in the flow or confirm that it ran successfully.

After a short delay, you should see an email in your inbox, since you populated John Doe's email as your personal email. Note that it may go to your Junk Email folder.

## <a name="challenges"></a>التحديات

- Play around with the formatting on the email. How can you make it more professional looking?