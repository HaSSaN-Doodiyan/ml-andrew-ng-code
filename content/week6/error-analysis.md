---
title: "تحلیل خطا"
date: 2020-10-19T17:16:27+03:30
draft: false
weight: 80
---

رویکرد پیشنهادی برای حل کردن یک مسئله یادگیری ماشین به شرح زیر است:

- با یک الگوریتم ساده شروع کنید، سریعا آن را پیاده کرده و تست کنید.

-  منحنی یادگیری را رسم کنید تا متوجه شوید که آیا داده بیشتر، ویژگی‌های بیشتر و ... مفید خواهند بود یا خیر.

- تحلیل خطا: به صورت دستی خطای موجود در نمونه‌های مجموعه cross validation را بررسی کرده و سعی کنید روند الگوریتم را تشخیص دهید.

این نکته حائز اهمیت است که نتیجه خطا را به صورت مقدار واحد و عددی بدست آورید. در غیر این صورت ارزیابی کارایی الگوریتم دشوار خواهد بود.

 ممکن است قبل ازاینکه ورودی‌های شما قابل استفاده باشند، نیاز به پردازش داشته باشند. برای مثال، اگر ورودی شما مجموعه‌ای از کلمات باشد، ممکن است بخواهید با حالت‌های مختلف همان کلمه (fail, failing, failed) مانند یک کلمه رفتار کنید. پس برای تشخیص آن‌ها به عنوان یک کلمه واحد باید از **نرم‌افزار ریشه‌یاب** استفاده کنید.