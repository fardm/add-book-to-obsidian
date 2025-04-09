
من با کمک هوش مصنوعی یک اسکریپت نوشتم که اطلاعات کتاب رو از سایت های مختلف استخراج میکنه.

## ✨ اطلاعاتی که استخراج میکنه
- 📕 عنوان کتاب
- 👤 نام نویسنده
- 📄 تعداد صفحات
- 🖼️ تصویر کتاب


## 🌐 سایت هایی که پشتیبانی میکنه
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fwww.goodreads.com%2f" width="18px" height="18px" align="center"> [گودریدز](https://www.goodreads.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2ftaaghche.com%2f" width="18px" height="18px" align="center"> [طاقچه](https://taaghche.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2ffidibo.com%2f" width="18px" height="18px" align="center"> [فیدیبو](https://fidibo.com/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fbehkhaan.ir%2f" width="18px" height="18px" align="center"> [بهخوان](https://behkhaan.ir/)
- <img src="https://www.google.com/s2/favicons?sz=64&amp;domain=https%3a%2f%2fwww.amazon.com%2f" width="18px" height="18px" align="center"> [آمازون](https://www.amazon.com/)


## 🛠️ روش استفاده

<video src="guide/how-to-use.mp4" controls width="600">
  مرورگر شما از پخش ویدئو پشتیبانی نمی‌کند.
</video>


1. یک پوشه به اسم Templates و یک پوشه به اسم my books ایجاد کنید.
2. فایل [add-book.md](./Templates/add-book.md?raw=true) رو توی پوشه Templates قرار بدید.
3. پلاگین [Templater](https://obsidian.md/plugins?id=templater-obsidian) رو نصب کنید.
4. از بخش تنظیمات پلاگین گزینه Tigger templater on new file رو فعال کنید.
5. روی گزینه add new folder template کلیک کنید.
6. در فیلد Folder پوشه my books رو انتخاب کنید.
7. در فیلد Template فایل add-book رو انتخاب کنید.
8. از تنظیمات خارج بشید. روی پوشه my book راست کلیک کنید و گزینه new note رو انتخاب کنید.
9. لینک کتاب رو وارد کنید و اینتر بزنید.
تمام

## 📝 شخصی سازی

فایل نهایی که بهتون میده به این شکله:
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


## 🚀 ساخت شورتکات
از پلاگین quick add هم میتونید استفاده کنید. براتون یه دستور جدید میسازه و اجازه میده براش شورتکات مشخص کنید.

<video src="guide/quick-add.mp4" controls width="600">
  مرورگر شما از پخش ویدئو پشتیبانی نمی‌کند.
</video>

1. پلاگین [quick add](https://obsidian.md/plugins?id=quickadd) رو نصب کنید و وارد تنظیمات پلاگین بشید.
2. در فیلد name یک اسم انتخاب کنید، مثلا add book.
3. حالت Template رو انتخاب کنید و گزینه Add choice رو بزنید.
4. یک ردیف جدید ساخته میشه. روی آیکون تنظیمات ⚙️ بزنید.
5. از بخش Template Path تمپلیت add book رو انتخاب کنید.
6. گزینه File name Format رو فعال کنید اما فیلدش رو خالی بگذارید.
7. گزینه Create in folder رو فعال کنید و در فیلد Folder path پوشه my books رو انتخاب کنید.
8. گزینه Open رو فعال کنید که بعد از اضافه کردن فایلش رو باز کنه.
9. از تنظیمات خارج بشید، آیکون ⚡رو فعال کنید.
10. حالا از بخش Hotkeys در تنظیمات ابسیدین میتونید برای دستور add book یک شورتکات مشخص کنید.