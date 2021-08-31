# Coffe_dispenser

PLA ABS

cup right hand

hand sensor say take cup

rotation angles can be secured physically but after prototype

flow sensor for pouring calibration

can 3d printer do it

heat sink for driver

can add nozzle sensor to detect liquid level



<h1 dir="rtl"> الوصف </h1>

<div dir="rtl">

- الملف الخاص بالمهمة الأولى في مسار الهندسة الميكانيكية  "Reception bot"

- الهدف من هذه المهمة هو تصميم روبوت الاستقبال بالشكل و المواصفات المطلوبة في المحاضرة


</div>

<h3 dir="rtl"> مميزات التصميم </h3>
<div dir="rtl">

- الروبوت بامكانه استيعاب آلة تحضير قهوة أو شاي في الجزء السفلي ثم التعديل عليها لضخ السائل للأعلى و عبر الذراع وصولا الى رأس الدلة التي ستكون مجرد اضافة جمالية، بالتالي يتم التخلص من الوزن الكبير على الذراع و تحضير المشروب سيكون بشكل آني حفاظا على درجة الحرارة
  
 </div>


<h3 dir="rtl"> ملاحظات عامة </h3>
<div dir="rtl">

- كالعادة لم يتم التركيز على الجزئيات الجمالية 
- تم اهمال مسارات البراغي في التصميم و يمكن اضافتها لاحقا
- قد يلاحظ في التصميم المبالغة في سمك بعض الاجزاء بحكم اني لم اعاين من قبل مدى صلابة خامات الطباعة ثلاثية الابعاد
- تم تغيير بعض الأبعاد المطلوبة في المحاضرة بما يوافق التصميم المقترح
- سيتم التفصيل في بعض جزئيات التصميم تاليا 
  
  </div>


<h3 dir="rtl"> ملاحظات على تصميم الرأس </h3>
<div dir="rtl">

- التصميم الأساسي مأخود من نموذج مفتوح المصدر و تم التعديل عليه (أتوقع أنه نفس التصميم الذي استخدمتموه)
- تم اختيار مصفوفة ليد "LED matrix" كوسيلة مباشرة للتفاعل مع المستخدم، بسيطة ذات لمسة جمالية و تؤدي الغرض، يتم تغطيتها بطبقة عاتمة نوعا ما مشتتة للضوء
- تم الأخذ بعين الاعتبار موقع للكاميرا و الميكروفون أعلى الرأس
- تبقى مساحة معتبرة داخل الرأس يمكن استغلالها لوضع دارة التحكم أو حتى نظام صوت
  
  </div>

<h3 dir="rtl"> ملاحظات على تصميم الذراعين </h3>
<div dir="rtl">

- تصميم كلا الذراعين تقريبا متطابق
- الذراع تحتوي على محور دوران واحد فقط على مستوى الكوع بينما تم تثبيت الكتف مباشرة بالجزء العلوي، و هذا يعد كافي جدا للوظيفة المتوقعة من الروبوت و يعطي أيضا ثبات اكبر اثناء حركة الذراع و تحمل اوزان اثقل
- التصميم يسمح بتمرير اسلاك الكهرباء و انبوب نقل المشروب مخفية بشكل تام في الداخل بدون اعاقة لحركة الذراع 
- يمكن تركيب اليد (end effector) بسهولة و كذا التبديل بين "موزع القهوة" و "حامل الصينية"

  </div>


<h3 dir="rtl"> ملاحظات على تصميم اليد الخاصة بحمل الفنجان </h3>
<div dir="rtl">

- تم الأخد بعين الاعتبار اختيار اليد اليمنى لحمل الفنجان (من تقاليد المملكة على حد علمي ههههه)
- طريقة الحمل هي أنه بمجرد احاطة اليد بالكوب يقوم الاصبع المتحرك بدفع الكوب حتى يرتكز على القاعدة البارزة اسفل اليد، فلا تكون هناك حاجة لشد الاصبع على الكوب بل مجرد منعه من الميلان. هدا سيضمن عدم سقوط الكوب خاصة بعد ملأه و يسهل على الشخص استلامه
- اليد مزودة بحساس للمسافة بحيث يمكن برمجته مثلا لاستشعار حمل الشخص للكوب و اصدار رد صوتي مناسب. يمكن استغلاله ايضا في توجيه اليد لالتقاط الكوب بشكل دقيق لأن موقعه مناسب لذلك
- توجد قنوات داخلية لتمرير الاسلاك بشكل مخفي

  </div>


<h3 dir="rtl"> ملاحظات على تصميم اليد الخاصة بحمل الدلة </h3>
<div dir="rtl">

- تصميم الدلة مؤخود من نموذج من الأنترنت و تم التعديل عليه. هي أساسا شكل جمالي لإخفاء الانبوب الناقل للمشروب، وحجمها صغير كي لا تشكل عبئا على الاصبع المتحرك. يمكن تغييرها بتصميم آخر
- الاصبع المتحرك المربوطة به الدلة يقوم بحركة دورانية بسيطة كمحاكاة لحركة الصب في الواقع، مع أنه لاحاجة لذلك كون المشروب يتم ضخه
- يمكن اضافة حساس مسافة عند رأس الدلة بزاوية معينة حتى يقيس مستوى المشروب داخل الكوب اثناء الصب

  </div>

<h3 dir="rtl"> ملاحظات على تصميم القرص الدوار </h3>
<div dir="rtl">

- القرص يملك 7 أماكن لحمل الأكواب حاليا و يمكن تطويره مستقبلا
- قاعدة القرص بها حساسين "IR distance sensor" و "IR encoder"، الأول لمعرفة الموقع اذا به كوب أولا و الثاني لتوجيه الكوب الى المكان المناسب للالتقاط
- يمكن المزاوجة بين الحساسين و برمجتهما للمساعدة في اعادة تعبئة الأكواب بشكل سريع

  </div>

<h3 dir="rtl"> ملاحظات على تصميم الدرج </h3>
<div dir="rtl">

- فكرة الدرج مأخودة من الروبوت الخاص بشركة الأساليب الذكية
- تصميمه حاليا بسيط و يمكن تحسينه لاحقا باضافة مساعدات الانزلاق عند الأطراف
- يملك حساس مسافة لمعرفة نهاية المسار

  </div>

<h3 dir="rtl"> ملاحظات اضافية على تصميم الجزأ العلوي </h3>
<div dir="rtl">

- توجد فتحة خلفية خاصة بالصيانة و اعادة تعبئة الأكواب
- تبقى مساحة معتبرة داخل الجزأ العلوي يمكن استغلالها في اضافة آلية لتعبئة الأكواب أتوماتيكيا، و لكن لم ارد التوسع في هذا

  </div>

<h3 dir="rtl"> ملاحظات على تصميم الجزأ السفلي </h3>
<div dir="rtl">

- الجزء السفلي خاص بوضع الآلة الخاصة باعداد المشروب بعد التعديل عليها لضخ المشروب الى الأعلى
- يمكن أيضا وضع البطاريات و دوائر الطاقة في هذا الجزأ (مع عزلها طبعا) للمحافظة على مركز ثقل الروبوت منخفضا قدر الامكان
- توجد فتحة خلفية للصيانة و اعادة تعبئة المكونات

  </div>

<h3 dir="rtl"> ملاحظات على تصميم القاعدة المتحركة </h3>
<div dir="rtl">

- التصميم مستوحى أساسا من الزلاجات الكهربائية "hoverboards" و حتى المحركات المستعملة من نفس الفئة
- تم اضافة عجلتين خلفيتين لدعم التوازن
- تبقى الجزئيات الخاصة بتثبيت المحركات يمكن تصميمها عند الحاجة

  </div>


