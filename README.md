
# add book to obsidian

با استفاده از این اسکریپت میتونید در نرم افزار ابسیدین اطلاعات کتاب رو از سایت های مختلف استخراج کرده و در یک فایل ذخیره کنید. 

![[addbookdemo.gif]]

## ✨ متغیر‌های قابل دریافت
- 📕 عنوان کتاب
- 👤 نام نویسنده
- 📄 تعداد صفحات
- 🖼️ تصویر کتاب

<br>

## 🌐 سایت‌های پشتیبانی شده
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2ftaaghche.com%2f" width="18px" height="18px" align="center"> [طاقچه](https://taaghche.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2ffidibo.com%2f" width="18px" height="18px" align="center"> [فیدیبو](https://fidibo.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fbehkhaan.ir%2f" width="18px" height="18px" align="center"> [بهخوان](https://behkhaan.ir/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fwww.goodreads.com%2f" width="18px" height="18px" align="center"> [گودریدز](https://www.goodreads.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fwww.amazon.com%2f" width="18px" height="18px" align="center"> [آمازون](https://www.amazon.com/)

<br>

## 🛠️ روش استفاده

<video src="https://fard.storage.c2.liara.space/share/how-to-use.mp4" controls width="80%"></video>

1. یک پوشه به اسم Templates و یک پوشه به اسم my books ایجاد کنید.
2. فایل add-book.md رو از [اینجا](./Templates/add-book.md) دانلود کنید و توی پوشه Templates قرار بدید.
3. پلاگین [Templater](https://obsidian.md/plugins?id=templater-obsidian) رو نصب کنید.
4. از بخش تنظیمات پلاگین گزینه Tigger templater on new file رو فعال کنید.
5. روی گزینه add new folder template کلیک کنید.
6. در فیلد Folder پوشه my books رو انتخاب کنید.
7. در فیلد Template فایل add-book رو انتخاب کنید.
8. از تنظیمات خارج بشید. روی پوشه my book راست کلیک کنید و گزینه new note رو انتخاب کنید.
9. لینک کتاب رو وارد کنید و اینتر بزنید.

تمام! یک فایل جدید با اطلاعات کتاب براتون ساخته میشه.

<br>

## 📝 شخصی‌سازی

بعد از وارد کردن لینک چنین فایلی رو براتون میسازه:
```md
---
title: "How to Be Everything"
author: "Emilie Wapnick"
pages: 240
cover: "https://images-na.ssl-images-amazon.com/images/S/compressed.photo.goodreads.com/books/1486512765i/31307672.jpg"
tags:
  - Book
---

# خلاصه

```

متغیرهای خروجی توی بخش properties قرار گرفتند. برای شخصی سازی باید بخش "خروجی نهایی" رو توی فایل add-book.md ویرایش کنید.

<br>

## 🚀 ساخت شورتکات
از پلاگین quick add هم میتونید استفاده کنید. براتون یه دستور جدید میسازه و اجازه میده براش شورتکات مشخص کنید.

<video src="https://fard.storage.c2.liara.space/share/quick-add.mp4" controls width="80%"></video>

1. پلاگین [quick add](https://obsidian.md/plugins?id=quickadd) رو نصب کنید و وارد تنظیمات پلاگین بشید.
2. در فیلد name یک اسم انتخاب کنید، مثلا add book.
3. حالت Template رو انتخاب کنید و گزینه Add choice رو بزنید.
4. یک ردیف جدید ساخته میشه. روی آیکون تنظیمات ⚙️ بزنید.
5. از بخش Template Path تمپلیت add book رو انتخاب کنید.
6. گزینه File name Format رو فعال کنید اما فیلدش رو خالی بگذارید.
7. گزینه Create in folder رو فعال کنید و در فیلد Folder path پوشه my books رو انتخاب کنید.
8. گزینه Open رو فعال کنید که بعد از اضافه کردن فایلش رو باز کنه.
9. از تنظیمات خارج بشید، آیکون⚡رو فعال کنید.
10. حالا از بخش Hotkeys در تنظیمات ابسیدین میتونید برای دستور add book یک شورتکات مشخص کنید.

<br>

---
اگر به مطالب مرتبط با نرم‌افزار ابسیدین علاقه دارید می توانید به <img src="https://www.google.com/s2/favicons?sz=32&domain=ifard.ir" width="18px" height="18px" align="center"> [بلاگ](https://ifard.ir/) یا کانال <img src="https://www.google.com/s2/favicons?sz=32&domain=telegram.org" width="18px" height="18px" align="center"> [تلگرامم](https://t.me/ifard_ir/) مراجعه کنید. 