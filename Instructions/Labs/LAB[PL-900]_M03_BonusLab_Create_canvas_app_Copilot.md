<div class="Box-sc-g0xbh4-0 eoaCFS js-snippet-clipboard-copy-unpositioned undefined" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><markdown-accessiblity-table data-catalyst=""><table tabindex="0">
  <thead>
  <tr>
  <th>lab</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div dir="rtl"><table>
  <thead>
  <tr>
  <th>title</th>
  <th>module</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div dir="rtl">النشاط المعملي للمكافآت: إنشاء تطبيق لوحة باستخدام Copilot</div></td>
  <td><div dir="rtl">Module 3: Describe how to build applications with Microsoft Power Apps</div></td>
  </tr>
  </tbody>
</table>
</div></td>
  </tr>
  </tbody>
</table></markdown-accessiblity-table>

<div class="markdown-heading" dir="rtl"><h1 tabindex="-1" class="heading-element" dir="rtl">النشاط المعملي للمكافآت: إنشاء تطبيق لوحة باستخدام Copilot</h1><a id="user-content-النشاط-المعملي-للمكافآت-إنشاء-تطبيق-لوحة-باستخدام-copilot" class="anchor" aria-label="Permalink: النشاط المعملي للمكافآت: إنشاء تطبيق لوحة باستخدام Copilot" href="#النشاط-المعملي-للمكافآت-إنشاء-تطبيق-لوحة-باستخدام-copilot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl"><strong>حسابات مستأجر WWL - شروط الاستخدام</strong> إذا تم تزويدك بحساب مستأجر كجزء من تقديم تدريب بقيادة مدرب، يرجى ملاحظة أن حساب المستأجر متاح لغرض دعم الأنشطة المعملية ضمن التدريب بقيادة المدرب. يجب عدم مشاركة حسابات المستأجر أو استخدامها لأغراض خارج الأنشطة المعملية. المستأجر المستخدم في هذه الدورة التدريبية هو مستأجر تجريبي ولا يمكن استخدامه أو الوصول إليه بعد انتهاء الفصل الدراسي وهو غير مؤهل للتمديد. يجب عدم تحويل حسابات المستأجر إلى اشتراك مدفوع. تظل حسابات المستأجر التي تم الحصول عليها كجزء من هذه الدورة التدريبية ملكًا لشركة Microsoft Corporation ونحتفظ بالحق في الوصول إليها واستعادة ملكيتها في أي وقت.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">السيناريو</h2><a id="user-content-السيناريو" class="anchor" aria-label="Permalink: السيناريو" href="#السيناريو"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">Bellows College مؤسسة تعليمية يضم حرمها الجامعي العديد من المباني. يتم حاليًا تسجيل زوار الحرم الجامعي في دفاتر عمل ورقية. ولا يتم جمع المعلومات بشكل متسق، ولا توجد وسيلة لجمع وتحليل البيانات المتعلقة بالزيارات عبر الحرم الجامعي بأكمله.</p>
<p dir="rtl">ترغب إدارة الحرم الجامعي في تحديث نظام تسجيل الزوار، بحيث يتم التحكم في الوصول إلى المباني من قبل أفراد الأمن، ويجب أن تكون جميع الزيارات مسجلة مسبقًا ويتم تسجيلها من قبل مضيفيها.</p>
<p dir="rtl">في هذا التمرين المعملي، ستستخدم Copilot لإنشاء تطبيق لوحة جديد لتسجيل الزيارات.</p>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">خطوات معملية عالية المستوى</h2><a id="user-content-خطوات-معملية-عالية-المستوى" class="anchor" aria-label="Permalink: خطوات معملية عالية المستوى" href="#خطوات-معملية-عالية-المستوى"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl">سنتبع المخطط أدناه لتصميم تطبيق اللوحة:</p>
<ul dir="rtl">
<li>
<p dir="rtl">وصف التطبيق الذي تريد إنشاءه</p>
</li>
<li>
<p dir="rtl">استخدام Copilot لتعديل بنية الجدول الداعمة</p>
</li>
</ul>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">المتطلبات الأساسية</h2><a id="user-content-المتطلبات-الأساسية" class="anchor" aria-label="Permalink: المتطلبات الأساسية" href="#المتطلبات-الأساسية"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="rtl">
<li>إكمال <strong>الوحدة 1 المختبر 0 - التحقق من صحة بيئة المختبر</strong></li>
</ul>
<div class="markdown-heading" dir="rtl"><h2 tabindex="-1" class="heading-element" dir="rtl">التمرين 1: استخدم Copilot لإنشاء تطبيق زيارات الكلية.</h2><a id="user-content-التمرين-1-استخدم-copilot-لإنشاء-تطبيق-زيارات-الكلية" class="anchor" aria-label="Permalink: التمرين 1: استخدم Copilot لإنشاء تطبيق زيارات الكلية." href="#التمرين-1-استخدم-copilot-لإنشاء-تطبيق-زيارات-الكلية"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="rtl"><strong>Objective:</strong> في هذا التمرين، ستنشئ تطبيق لوحة عن طريق الاتصال بجدول زيارات الحرم الجامعي.</p>
<div class="markdown-heading" dir="rtl"><h3 tabindex="-1" class="heading-element" dir="rtl">المهمة #1: إنشاء التطبيق الأولي</h3><a id="user-content-المهمة-1-إنشاء-التطبيق-الأولي" class="anchor" aria-label="Permalink: المهمة #1: إنشاء التطبيق الأولي" href="#المهمة-1-إنشاء-التطبيق-الأولي"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="rtl">
<li>
<p dir="rtl">الانتقال إلى <code>https://make.powerapps.com</code>.</p>
</li>
<li>
<p dir="rtl">قد تحتاج إلى إعادة المصادقة - حدد <strong>تسجيل الدخول</strong> واتبع التعليمات إذا لزم الأمر.</p>
</li>
<li>
<p dir="rtl">حدد بيئة <strong>Dev One</strong> في الجزء العلوي الأيمن إذا لم تكن محددة بالفعل.</p>
</li>
<li>
<p dir="rtl">حدد <strong>+ إنشاء</strong> من شريط التنقل الأيسر من الشاشة. ضمن <strong>قسم Create your apps</strong> ، حدد <strong>Start with Copilot</strong>.</p>
</li>
<li>
<p dir="rtl">في <strong>المربع بدء استخدام Copilot</strong> ، أدخل النص التالي. <code>Create an application that logs visits to a college campus</code>.</p>
</li>
<li>
<p dir="rtl">حدد الزر <strong>إنشاء</strong>.</p>
</li>
</ol>
<p dir="rtl">سيبدأ Copilot في إنشاء بنية جدول لدعم التطبيق الخاص بك.</p>
<blockquote>
<p dir="rtl"><strong>IMPORTANT:</strong> عند استخدام الذكاء الاصطناعي التوليدي، لن تحصل دائمًا على نفس النتائج الدقيقة. من المحتمل ألا يتطابق الجدول لديك تمامًا مع الجدول الذي تم إنشاؤه لطالب آخر.</p>
</blockquote>
<ol start="7" dir="rtl">
<li>
<p dir="rtl">على الجانب الأيمن، حدد بنية الجدول في نافذة Copilot ثم حدد <strong>خيارات</strong> الجدول.</p>
</li>
<li>
<p dir="rtl">حدد <strong>خيار جدول</strong> واحد ثم حدد <strong>تطبيق</strong>.</p>
<p dir="rtl"><a target="_blank" rel="noopener noreferrer" href="https://github.com/MicrosoftLearning/PL-900-Microsoft-Power-Platform-Fundamentals.ar-sa/blob/OLPRODLOC/Instructions/Labs/media/bonus-lab-tablestr.png"><img src="https://github.com/MicrosoftLearning/PL-900-Microsoft-Power-Platform-Fundamentals.ar-sa/blob/OLPRODLOC/Instructions/Labs/media/bonus-lab-tablestr.png" alt="لقطة شاشة لبنية الجدول التي تم إنشاؤها للتو" style="max-width: 100%;"></a></p>
</li>
</ol>
<blockquote>
<p dir="rtl">لمشاهدة بنية الجدول، حدد الجدول وانقر فوق <strong>الزر عرض البيانات</strong></p>
</blockquote>
<ol start="9" dir="rtl">
<li>
<p dir="rtl"><strong>في المربع ماذا تريد أن تفعل بعد ذلك؟</strong> أدخل النص: إضافة عمودين، وقت الدخول ووقت المهلة في الجدول. يجب أن يكون كلاهما حقلي التاريخ والوقت.</p>
</li>
<li>
<p dir="rtl">حدد الزر <strong>انتقال</strong> أو اضغط على <strong>Enter</strong>.</p>
</li>
<li>
<p dir="rtl">قم بالتمرير إلى جانب الجدول وتحقق من <strong>إنشاء عمودي Time in</strong> و Time <strong>out</strong> .</p>
</li>
</ol>
<p dir="rtl">نظرًا لأننا نسجل دخول الزوار وخروجهم، لم نعد بحاجة إلى أي حقول أخرى لتاريخ الزيارة.</p>
<ol start="12" dir="rtl">
<li><strong>حدد موقع الحقل تاريخ</strong> الزيارة (أو الحقل المكافئ) وفي <strong>المربع ماذا تريد أن تفعل بعد ذلك؟</strong> أدخل النص: إزالة حقل تاريخ الزيارة (أو الحقل المكافئ).</li>
</ol>
<blockquote>
<p dir="rtl">إذا لزم الأمر، فقم بتحديث اسم الحقل المراد إزالته من اسم الجدول ذي الصلة.</p>
</blockquote>
<ol start="13" dir="rtl">
<li>
<p dir="rtl">حدد الزر <strong>انتقال</strong>.</p>
</li>
<li>
<p dir="rtl">أزل أي حقول تاريخ إضافية قد تكون موجودة بخلاف <strong>وقت الدخول</strong> و<strong>وقت الخروج</strong>.</p>
</li>
</ol>
<p dir="rtl">في البداية، تم تنسيق حقل مثل حقل <strong>الغرض</strong> مع إضافة نوع بيانات نصية. سنجعل Copilot يغيره إلى قائمة منسدلة (اختيار).</p>
<ol start="15" dir="rtl">
<li>
<p dir="rtl">في <strong>ما الذي ترغب في القيام به بعد ذلك؟</strong> أدخل النص التالي: تغيير حقل Purpose إلى قائمة اختيار مع الخيارات التالية: Campus Tour، Fair Career Fair، Meet with Professor، Student Counseling، Other.</p>
</li>
<li>
<p dir="rtl">حدد الزر <strong>انتقال</strong>.</p>
</li>
<li>
<p dir="rtl">بما أننا نريد أيضا التقاط رقم المبنى، في <strong>ما الذي ترغب في القيام به بعد ذلك؟</strong>، أدخل: إضافة عمود بناء.</p>
</li>
<li>
<p dir="rtl">حدد الزر <strong>انتقال</strong>.</p>
</li>
<li>
<p dir="rtl">بمجرد أن تصبح راضيا عن الجدول، حدد <strong>الزر حفظ التطبيق</strong> وفتحه.</p>
</li>
<li>
<p dir="rtl">إذا لزم الأمر، في الشاشة <strong>هل تم العمل؟</strong> ، حدد <strong>عدم السؤال مرة أخرى</strong>، وحدد <strong>الزر حفظ التطبيق</strong> وفتحه.</p>
</li>
</ol>
<p dir="rtl"><a target="_blank" rel="noopener noreferrer" href="https://github.com/MicrosoftLearning/PL-900-Microsoft-Power-Platform-Fundamentals.ar-sa/blob/OLPRODLOC/Instructions/Labs/media/bonus-lab-copilot-02.png"><img src="https://github.com/MicrosoftLearning/PL-900-Microsoft-Power-Platform-Fundamentals.ar-sa/blob/OLPRODLOC/Instructions/Labs/media/bonus-lab-copilot-02.png" alt="لقطة شاشة للتطبيق الذي تم إنشاؤه للتو" style="max-width: 100%;"></a></p>
<p dir="rtl">تهانينا، لقد استخدمت Copilot لإنشاء تطبيق جديد.</p>
</article></div>
