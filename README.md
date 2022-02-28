

# <p dir="rtl">
<strong>شرح الدرس</strong></p>




1. **أنواع البيانات :** أرقام عشرية ( double ) - الأرقام ( int ) - المنطق (bool) - النصوص (string)
2. **المتغيرات :** المتغيرات هي عبارة عن عناصر يتم تخزين قيم معينة فيها،  ( مثل الذاكرة ) كتعريف بسيط. و يمكننا تغيير قيمة المتغير لاحقا بالكود. 
    * مثال: 

            ```
string characterName = "name"
```



            ```
int maxHP = 200
```



            ```
float characterSpeed = 1.50
```


3. **سلامة واستدلال أنواع البيانات : **في بعض الأحيان نريد أن ننشئ متغير بدون إعطائه  قيمة افتراضية لكي نعين قيمته لاحقا في الكود. سوف نستطيع عمل ذلك عن طريق إنشاء متغير وإعطائه نوع البيانات المراد استخدامة لاحقا.
    * مثال: 

            ```
string name;
int maxHP;
double characterSpeed;
bool isBoss;
```


4. **الطباعة Console.WriteLine : **



* 
يمكننا طباعة القيم باستعمال أمر Console.WriteLine ، مثال : 

            <p dir="rtl">
<code>Console.WriteLine("EMP activated")</code> a</p>




* 
يمكن طباعة قيم مخزنة في متغيرات من خلال كتابة الثابت مباشرة ، مثال : 

            <p dir="rtl">
<code>double pi = 3.14  \
Console.WriteLine("The value of pi is {0}", pi);</code>i)</p>




* 
يمكنك الدمج بين النصوص من خلال أمر print و الفاصلة بين كل عنصر  ، مثال :

```
string name = "ماريو";
int age = 12;
Console.WriteLine("I am" + name + "and my age is" + age);
```


<p dir="rtl">
أو</p>



```
Console.WriteLine("I am {0} and my age is {1}", name, age);
```



---

<p dir="rtl">
<strong>تمرين</strong> (this should be in github so just attach a github link)</p>


<p dir="rtl">
في هذا التمرين سوف نتعلم كيفية طباعة و استعمال المتغيرات وأنواع البيانات</p>




* 
قم بإنشاء ملف جديد اسمه gameDev 


* 
افتح visual studio و قم بإنشاء مشروع جديد 


* 
احفظ المشروع باسم CW-1-1 و احفظه بالملف


* 
عرف متغير characterName واضف اليه قيمة اسم البطل. 


* 
 عرف متغير speed , age, superPower1, superPower2 واضف اليهم المعلومات.


* 
استخدم Console.WriteLine لطباعة النص بالاسفل.
<p dir="rtl">
مثال لناتج التمرين:</p>



```
<p dir="rtl">
اسمي أحمد و قواي الخارقة هي الدرع الفولاذي و الرؤية الليلية . عمري 15 و سرعتي هي 1.65
</p>
