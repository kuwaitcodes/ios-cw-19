

# صفحة التوجيه Navigation View



## في هذا التمرين سنقوم بتخمين رقم من الظاهر بالصورة وستقوم navigation view باخبارنا ما إن كان الرقم صحيح او خاطئ في الصفحة الثانية كما هو موضح بالصورة.



<p align="center">
<img src="/number.gif" width="200" alt="alt_text" title="image_tooltip">
</p>

## لعمل كود صفحة التوجيه :

```
 NavigationView {

       NavigationLink(destination: Text(“النص المراد ظهوره بالصفحة الثانية”)) {

                            Text("النص بالصفحة الأولى")

                        }.navigationBarTitle("العنوان")

          }
```

---

## تمرين





### 1. قم بعمل fork من رابط gitHub .


### 2. قم بإنشاء تطبيق جديد في XCode


### 3. عمل مصفوفة من الأرقام ،وجعل المتغير يأخذ قيمة عشوائية باستخدام randomElement مع المصفوفة. 


### 4. يجب مقارنة الرقم الذي تم الضغط عليه مع الرقم العشوائي باستخدام if statement.


### 5. عمل forEach لعرض أرقام المصفوفة.


### 6. عمل navigation view عشان تنقلنا للصفحة الثانية وتبين النتيجة هل صحيح الرقم او غلط.


### 7. ولا ننسى نضيف عنوان حق navigation view .
