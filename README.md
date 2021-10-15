# arabic-words-list
The largest open source arabic words list 
<div dir="rtl">
*أكبر قائمة من الكلمات العربية الموجودة فعلا باللغة العربية.* 
لان هنالك قائمة مكونة آليا تحوي اكثر من 9 ملايين كلمة لكن لا تستغرب اذا وجدت كلمات غير موجودة باللغة العربية من الاساس 
على عكس هذه القائمة التي تم جمعها من الكتب من ضمنها لسان العرب و تاج العروس و ما يقارب 7 آلاف كتاب تم تحميلهم من المكتبة الشاملة بصيغة `Doc.` ثم تحويلهم لصيغة `txt.` ثم ازالة كل الحروف غير العربية والحركات وبعدها حذف الكلمات المكررة ثم تكوين الملف النهائي الذي امامكم.

القائمة تحوي حوالي 3.5 مليون كلمة بدون تكرار مطابق 
وقلت بدون تكرار مطابق لانها تحوي نوع من انواع التكرار حسب نظريتك
بمعنى ان كل من (اكتب ، كتب ، كتبت،  يكتب، تكتب)  يتم اعتبارها كلمة وقد يتفق البعض ويختلف اخرون بقول يجب حسابهم كلهم ككلمة واحدة 

مع العلم ان لم اختر هذا الترتيب بل فرض علي لان الكمبيوتر لا يعرف شيئا عن تصريف الافعال والتجذير باللغة العربية ولم اجد اداة تقوم بهذا العمل 
إن هدفي الفعلي كان صنع ملف json بهذا الترتيب 
```
  "كتب":[
    "أكتب",
    "يكتب",
    "تكتب",
    "تكتبين",
    "يكتبون",
    "تكتبان",
     ...
  ]
```
بحيث يرتب كل جذر مع مشتقاته 
لكن حدودي المعرفية سواء بالبرمجة او اللغة العربية لم تكن كافية لذا امل ان ياتي شخص اجدر مني لفعل ما لم استطع فعله 

شكري الخالص للمكتبة الشاملة مع انهم لا يعرفون اي شيء عن هذا المشروع لكن لولاهم لما كان موجودا 

#  الخطوة القادمة 

جمع كلمات اكثر من خلال 
* الويب سكرابنك مع اني لست واثقا منه فهنالك الكثير من الاخطاء الاملائية واللهجات اضافة للكلمات الاجنبية المعربة 
* ايجاد تقنية OCR تتعرف على النصوص العربية بدون اخطاء من اجل تحويل كتب `pdf` الى صيغة `txt.`

> مع انه يوجد تقنيات تدعم العربية لكن تحوي الكثير من المشاكل او لا تتدعم سوى التحويل الفردي لصفحة واحدة 

* طرق اخرى عدا الاضافة اليدوية للكلمات لانها عملية بطيئة ومستهلكة للوقت

# الاخطاء

كأي شيء يصنعه الانسان فهذا المشروع يحوي نسبة من الخطأ 
مثل ان تجد كلماتين مدموجتين مثل (عنابرمناخ) والتي يجب علي فصلها يدويا وهذا ام متعب لان القائمة كبيرة جدا 
او بعض الاخطاء الاملائية والتي اعتقد انها قليلة جدا 

حسب تقديري فنسبة الكلمات الصحيحية في القائمة هي 90% ، ربما لا تكون الافضل لكن هذا ما في استطاعتي 

# امثلة

قد يتسائل البعض عن فوائد هذا المشروع ابسط الامثلة هي 
حساب متوسط عدد الحروف في الكلمة العربية والذي اعتبر نفسي اول من قام بها ببساطة لاني بحثت بجوجل بشكل مكثف ولم اعثر على نتيجة 

الحروف الاكثر استخداما والتي قد تساهم في صنع نسخة عربية من كيبورد ديفوراك 
كبديل عن كيبورد IBM الموجود في جميع حواسيب الوندوز واللينكس و السيئ جدا من وجه نظري 

>  كيبورد الماك افضل بكثير من الوندوز لكن يمكننا صنع ما هو افضل مع هذه البيانات 

  اضافة لانهاء خرافة كون اللغة العربية تحوي 12 مليون كلمة والتي تم حسابها رياضيا
وليس لغويا 

> ابسط مثال لاثبات عدم صحة هذا الأدعاء هو : اذا قمنا بحساب عدد كلمات
> اللغة الانكليزية بنفس الطريقة سنجد ان عدد الكلمات هو اكثر من 7 ملايين
> بينما اذا ذهبت لأكبر قاموس انجليزي فهو يحتوي على 600 الف كلمة فقط

</div>
