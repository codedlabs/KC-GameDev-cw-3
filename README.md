<hr>
<h1><p dir="rtl">
<strong>شرح الدرس</strong></p>
</h1>


<ol>

<li><strong>أنواع البيانات :</strong> أرقام عشرية ( double ) - الأرقام ( int ) - المنطق (bool) - النصوص (string)

<li><strong>المتغيرات :</strong> المتغيرات هي عبارة عن عناصر يتم تخزين قيم معينة فيها،  ( مثل الذاكرة ) كتعريف بسيط. و يمكننا تغيير قيمة المتغير لاحقا بالكود.  
<ul>
 
<li>مثال: 

            

<pre class="prettyprint">string characterName = "name"</pre>



            

<pre class="prettyprint">int maxHP = 200</pre>


</li> 
</ul>
</li> 
</ol>



<pre class="prettyprint">float characterSpeed = 1.50</pre>


<ol>

<li><strong>سلامة واستدلال أنواع البيانات : </strong>في بعض الأحيان نريد أن ننشئ متغير بدون إعطائه  قيمة افتراضية لكي نعين قيمته لاحقا في الكود. سوف نستطيع عمل ذلك عن طريق إنشاء متغير وإعطائه نوع البيانات المراد استخدامة لاحقا. 
<ul>
 
<li>مثال: 

            

<pre class="prettyprint">string name;
int maxHP;
double characterSpeed;
bool isBoss;</pre>


<ol>

<li><strong>الطباعة Console.WriteLine : </strong>
</li>
</ol>
</li>
</ul>
</li>
</ol>

<li>يمكننا طباعة القيم باستعمال أمر Console.WriteLine ، مثال : 
<p>

            <p dir="rtl">
<code>Console.WriteLine("EMP activated")</code> a</p>

</p>
<ul>

<li>
يمكن طباعة قيم مخزنة في متغيرات من خلال كتابة الثابت مباشرة ، مثال : 
<p>

            <p dir="rtl">
<code>double pi = 3.14 <br>Console.WriteLine("The value of pi is {0}", pi);</code>i)</p>

</p>
<ul>

<li>
يمكنك الدمج بين النصوص من خلال أمر print و الفاصلة بين كل عنصر  ، مثال :



<pre class="prettyprint">string name = "ماريو";
int age = 12;
Console.WriteLine("I am" + name + "and my age is" + age);</pre>


<p>
<p dir="rtl">
أو</p>

</p>



<pre class="prettyprint">Console.WriteLine("I am {0} and my age is {1}", name, age);</pre>


<hr>
<p>
<p dir="rtl">
<strong>تمرين</strong> (this should be in github so just attach a github link)</p>

</p>
<p>
<p dir="rtl">
في هذا التمرين سوف نتعلم كيفية طباعة و استعمال المتغيرات وأنواع البيانات</p>

</p>
<ul>

<li>
قم بإنشاء ملف جديد اسمه gameDev 

<li>افتح visual studio و قم بإنشاء مشروع جديد 

<li>احفظ المشروع باسم CW-1-1 و احفظه بالملف

<li>عرف متغير characterName واضف اليه قيمة اسم البطل. 

<li> عرف متغير speed , age, superPower1, superPower2 واضف اليهم المعلومات.

<li>استخدم Console.WriteLine لطباعة النص بالاسفل.
<p>
<p dir="rtl">
مثال لناتج التمرين:</p>

</p>



<pre class="prettyprint"><p dir="rtl">
اسمي أحمد و قواي الخارقة هي الدرع الفولاذي و الرؤية الليلية . عمري 15 و سرعتي هي 1.65
</p>
