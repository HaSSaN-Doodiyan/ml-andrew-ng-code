---
title: "یادگیری با نظارت چیست؟"
date: 2020-09-06T12:54:05+04:30
draft: false
weight : 20
author: Mehrdad Mohammadian
---

### تعریف یادگیری با نظارت
در <span class="top-dict" data-tipso="supervised learning">یادگیری با نظارت</span> یک مجموعه داده داریم و از قبل 
می‌دانیم که خروجی صحیح باید چطور باشد، اصطلاحا 
داده ها <span class="top-dict" data-tipso="label">برچسب</span> خورده اند! 
با این ایده که به بین خروجی و ورودی رابطه وجود دارد.

مسائل یادگیری با نظارت
به دو دسته **<span class="top-dict" data-tipso="regression">رگرسیون</span>** و
**<span class="top-dict" data-tipso="classification">طبقه بندی</span>** تقسیم می‌شوند.


### رگرسیون
![دوره یادگیری ماشین دانشگاه استنفورد به فارسی](../images/linearRegression.jpg?width=30pc)

در این مسائل سعی می‌کنیم خروجی ای با مقدار پیوسته
را پیش بینی کنیم.

در مسئله پیش بینی قیمت خانه می‌خواهیم با مجموعه
داده ای از قیمت های واقعی خانه ها بر اساس اندازه،
قیمت خانه ای جدیدی را پیش بینی کنیم.

### طبقه بندی
![دوره یادگیری ماشین دانشگاه استنفورد به فارسی](../images/classification.png?width=30pc)

در عوض اینجا سعی می‌کنیم خروجی ای با مقدار 
گسسته  پیش بینی کنیم.
مثلا در مسئله تشخیص وخیم بودن یا نبودن سرطان
می‌خواهیم بر اساس دو ویژگی سن و سایز تومور نتیجه
را در یکی از دو دسته وخیم یا غیر وخیم طبقه بندی کنیم.


### مثال های بیشتری که شما پاسخ دهید!
1. با توجه به عکسی که از یک شخص دریافت کردید
تشخیص دهید که سنش چه قدر است.
2. می‌خواهید حساب های مشتری هارا بررسی کنید
و تصمیم بگیرید که هک شده است یا نه.
3. شما انبار بزرگی از اقلام یکسان دارید و می‌ خواهید
پیش بینی کنید که طی 3 ماه آینده چه تعداد از این اقلام
به فروش می رسند.

{{%expand "برای پاسخ مثال ها کلیک کن" %}}
1. Regression
2. Classification
3. Regression
{{% /expand%}}