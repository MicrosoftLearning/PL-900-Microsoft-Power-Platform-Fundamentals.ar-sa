---
lab:
  title: 'النشاط المعملي 0: التحقق من البيئة المعملية'
  module: 'Module 0: Course introduction'
---

# <a name="lab-0-validate-lab-environment"></a>النشاط المعملي 0: التحقق من البيئة المعملية

## <a name="scenario"></a>السيناريو

Bellows College is an educational organization with multiple buildings on campus. Campus visitors are currently recorded in paper journals. The information is not captured consistently, and there are no means to collect and analyze data about the visits across the entire campus.

ترغب إدارة الحرم الجامعي في تحديث نظام تسجيل الزوار، بحيث يتم التحكم في الوصول إلى المباني من قبل أفراد الأمن، ويجب أن تكون جميع الزيارات مسجلة مسبقًا ويتم تسجيلها من قبل مضيفيها.

خلال هذه الدورة التدريبية، ستقوم بإنشاء تطبيقات وتفعيل التشغيل الآلي لتمكين موظفي إدارة وأمن Bellows College من إدارة الوصول إلى مباني الحرم الجامعي والتحكم فيه.

In this Module 0 lab, you will acquire a Power Platform trial and access the Power Platform admin center. In the admin center, you will then create a <bpt id="p1">**</bpt>Practice<ept id="p1">**</ept> environment that you will perform the majority of your lab work in.

## <a name="exercise-1--setup"></a>تمرين 1 – الإعداد

### <a name="task-1---acquire-your-microsoft-power-platform-trial-tenant"></a>المهمة \#1 - الحصول على مستأجر الإصدار التجريبي لـ Microsoft Power Platform

1. قم بنسخ **بيانات اعتماد Microsoft 365** من مضيف مختبر معتمد.

1. انتقل إلى <https://powerapps.microsoft.com> وانقر فوق **ابدأ مجانًا**.

1. ضمن **لنبدأ**، أدخل عنوان بريدك الإلكتروني من بيانات اعتماد Microsoft 365 في مربع النص الذي يشير إلى **أدخل عنوان بريد عملك الإلكتروني** وانقر فوق **التالي**.

1. If you see a prompt that you have an existing account with Microsoft. Select <bpt id="p1">**</bpt>Sign in<ept id="p1">**</ept>.

1. أدخِل كلمة المرور المُقدَّمة بواسطة "مضيف النشاط المعملي المعتمد".

1. حدد **نعم** للإبقاء على تسجيل دخولك.

1. لا تغير البلد.

1. بالنسبة إلى **رقم الهاتف**، أدخل 01234567890.

1. أكمل معلومات حسابك وحدد **Get started** في التسجيل في الإصدار التجريبي من Microsoft Power Platform.

1. في شاشة التأكيد، انقر فوق **بدء الاستخدام**.

1. إذا رأيت مطالبة بإدخال تفاصيل جهة الاتصال، فانقر فوق **X** لإغلاق النافذة المنبثقة.

### <a name="task-2--create-environment"></a>المهمة \#2 - إنشاء بيئة العمل

1. انتقل إلى <https://admin.powerplatform.microsoft.com> وسجل ل الدخول باستخدام بيانات اعتماد Microsoft 365 الخاصة بك إذا تمت مطالبتك بذلك.

1. إذا رأيت قائمة ترحيب منبثقة، فانقر فوق **بدء الاستخدام**.

1. حدد **البيئات** وانقر فوق **+جديد**.

    1. بالنسبة إلى **الاسم**، أدخل **ممارسة [الأحرف الأولية من اسمي]** (مثال: ممارسة AJ).

    1. بالنسبة إلى **النوع**، حدد **إصدار تجريبي** (لا تحدد خيار (مستند إلى اشتراك) في الإصدار التجريبي).

    1. غير التبديل عند **هل تريد إنشاء قاعدة بيانات لهذه البيئة؟** إلى **نعم**.

    1. اترك كل التحديدات الأخرى على الوضع الافتراضي وانقر فوق **التالي**.

    1. في علامة التبويب التالية، اترك جميع التحديدات على الوضع الافتراضي وانقر فوق **حفظ**.

1. يجب أن تظهر بيئة **التدريب** الآن في قائمة البيئات.

> Your environment may take a few minutes to provision. Refresh the page if needed.
