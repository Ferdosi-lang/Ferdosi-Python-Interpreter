<div dir="rtl">
  
# زبان برنامه نویسی فردوسی
یک زبان برنامه نویسی ساده؛ نوشته شده با پایتون
## این زبان در حال برنامه نویسی بوده و ممکن است دارای مشکلاتی باشد
خوشحال می شویم در حل مشکلات کمک کنید :
[خطا ها](https://github.com/Ferdowsi-lang/Ferdowsi-Python-Interpreter/issues?q=is%3Aissue+is%3Aopen+label%3Abug)
## روش استفاده
در ابتدا باید پروژه را دریافت کنید و کتابخانه های مورد نیاز را نصب کنید:
</div>

```bash
pip3 install -r requirements.txt
```

<div dir="rtl">
سپس برای تفسیر دستور زیر را در خط فرمان وارد کنید:
</div>

```
python3 ferdowsi.py <آدرس فایل>
```

<div dir="rtl">

برای مثال:
</div>

```
python3 ferdowsi.py examples/helloworld.fd
```
<div dir="rtl">

نکته: پسوند .fd برای فایل اجباری نیست

اگر در حال حاضر فایلی ندارید، می‌توانید به طور زنده در ترمینال برنامه نویسی کنید:
</div>
  
```
python3 ferdowsi.py
```
<div dir="rtl">


## مثال‌ها
### سلام دنیا

```plain
"سلام، دنیا!"
```
  
### چاپ

```plain
چاپ کن "سلام دنیا"
```
  
### شرط‌ها

```plain
اگر 12 برابر 10 + 2 باشد آنگاه "ده با دو میشود دوازده" وگرنه "ده با دو نمیشود دوازده"
```
    
### ورودی

```plain
عدد = عددگیر
نام = ورودی
```

### کامنت‌ها

```plain
# این یک کامنت است
// این هم یک کامنت است
# کامنت ها برنامه را تغییر نمیدهند
```

### شمارنده

```plain
اگر 5 شمارنده 10 باشد آنگاه "درسته" وگرنه "غلطه"
```

### تابع‌ها

```plain
زوج_فرد یعنی اگر 2 شمارنده عدد باشد آنگاه "زوج" وگرنه "فرد"

عدد = 15
زوج_فرد را اجرا کن
```
  
### عملگرها

```plain
اول = 10
دوم = 2

جمع = اول + دوم
تفریق = اول - دوم
ضرب = اول * دوم
تقسیم = اول / دوم
```
</div>

* * *
<div dir="rtl">

**این مفسر به وسیله [SLY](https://sly.readthedocs.io/en/latest/sly.html) ساخته شده است**
</div>
