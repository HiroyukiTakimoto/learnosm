---
layout: doc-rtl
title: OSMTracker
permalink: /fa/mobile-mapping/osmtracker/
lang: fa
category: mobile-mapping
---

OSMTracker
==============

> Reviewed 2016-02-08
  
**این متن مربوط به نرم‌افزار OSMTracker برای آندروئید است - برنامه مشابهی برای ویندوز موبایل نیز وجود دارد**  
OSMTracker اجازه میدهد تا ایجاد یک مسیر ردیابی شده GPX از یک سفر به همراه مجموعه‌ای از نقاط بین‌راهی در طول مسیر را ضبط کنید. ضبط صوت، عکس و یادداشت دیگر نیز امکانپذیر بوده و همه آنها به صورت جغرافیایی قرار می گیرند.

شروع سریع
-----------

![OSMTracker_1][]  

1. برای ایجاد مسیر جدید روی بعلاوه کلیک کنید.  
2. صفحه نمایش برای نشان دادن دکمه‌ها تغییر خواهد کرد - صبر کنید تا آنها دیگر خاکستری کمرنگ نباشند که نشاندهنده این است که موقعیت GPS پیدا شده است.  
3. مسیر خود را بروید و درست در زمانی که به ویژگی قابل نقشه‌کشی رسیدید دکمه مناسب را بزنید. همچنین با استفاده از دکمه‌ها می‌توانید صدا ضبط کنید، عکس بگیرید و یادداشت بنویسید.  
4. هنگامی که کارتان به اتمام رسید، نماد فلاپی دیسک را برای ذخیره مسیر و نقاط بین‌راهی فشار دهید.  
5. برای تبدیل مسیر به فایل gpx، انگشت خود را روی نام آن در لیست مسیرها نگه دارید، سپس گزینه مناسب را انتخاب کنید.  
6. مسیر، تصاویر و صداهای ضبط شده را به کامپیوتر منتقل کرده و برای به‌روزرسانی OSM از روی آنها بخوانید.  


نصب OSMTracker
-------------------------

OSMTracker را از [فروشگاه گوگل](https://play.google.com/store/apps/details؟id=me.guillaumin.android.osmtracker) نصب کنید.  
![OSMTracker Logo][]  
در صورت نیاز [جدیدترین بسته نرم افزاری](https://drive.google.com/folderview?id=0BxxhTXmYjyeSSjg1MFhJWnJLams#list) را می‌توان خارج از فروشگاه گوگل دانلود نمود.  


پیکربندی OSMTracker
------------------------

OSMTracker را راه‌اندازی کنید و نماد منو را در دستگاه آندروییدتان بزنید، سپس **تنظیمات** را انتخاب کنید.  

- **مدت زمان ضبط صدا** - به انتخاب شما، اما توسط نویسنده ۳۰ ثانیه استفاده شده است.  
- **فعال کردن صدا** - توصیه می شود که این کادر را علامت بزنید - هنگامی که ضبط صدا شروع و پایان می‌یابد یک صدای بوق هشدار شنیده می‌شود.  
- **تنظیم مجدد احراز هویت**. این دکمه خاکستری خواهد بود تا زمانی که یک فایل GPX را آپلود کنید، و OSMTracker مجاز به آپلود مسیر به حساب کاربری OpenStreetMapتان باشد.  
- **تنظیمات GPS** دستگاه اندرویدی‌تان از کدام روش برای تعیین مکان استفاده کند. توصیه می‌شود این گزینه را روی **دقت بالا** تنظیم کنید در آن صورت دستگاه از GPS ،Wi-Fi و شبکه تلفن همراه برای تخمین موقعیت مکانی استفاده می کند.  
- **بررسی GPS هنگام راه‌اندازی** هنگامی که OSMTracker را راه‌اندازی می‌کنید، اگر GPS خاموش باشد، برنامه از شما میخواهد که آن را دوباره روشن کنید.
- **نادیده گرفتن ساعت GPS** در صورتی که تیک خورده باشد از ساعت داخلی دستگاه به جای زمان ارائه شده در سیگنال GPS استفاده می‌کند.  
- **فواصل ثبت GPS** فاصله بین ثبت موقعیت های مکانی را انتخاب کنید - برای بهترین دقت ۰ یا ۱ را انتخاب کنید، که هر کدام از اینها منجر به ضبط در هر ثانیه می‌شود.  

> با این حال هنگام استفاده از برنامه، تعداد دفعات روی استفاده از باتری تاثیر می‌گذارد. احتمالاْ صفحه نمایش در بیشتر اوقات روشن باشد، GPS کار می‌کند، و شما نیز ممکن است ضبط عکس و صدا داشته باشید - همه اینها به شدت باعث تخلیه باتری می‌شوند و در استفاده طولانی مدت توصیه می شود که دستگاه را با استفاده از منبع تفذیه اضافه تقویت کنید.  

- **پوشه ذخیره در حافظه خارجی (کارت SD)** پیش فرض /osmtracker است.  

> دستگاه‌های آندروییدی جدید اجازه ذخیره داده در کارت حافظه خارجی microSD یا کارت SD را نمیدهند. گرچه به عنوان "محل ذخیره خارجی" خوانده می شود، اما مسیرها در واقع در **/storage/emulated/0/osmtracker** ثبت می‌شوند.  

- **یک پوشه به ازای هر مسیر** از آنجاییکه همه یادداشتهای صوتی، تصویری و متنی مربوطه و مسیر GPX در یک پوشه ذخیره می‌شوند توصیه می‌شود. نام این پوشه براساس تاریخ و زمان ایجاد فایل gpx است.  
- **نام فایل مسیر** بر اساس اولویت شما گزینه‌هایی برای انتخاب وجود دارد تا نام فایل براساس آن نام‌گذاری شود.  
- **دقت در فایل GPX** توصیه می‌شود - منجر می‌شود که نام نقاط مسیریابی حاوی رقم تقریبی محدوده خطای احتمالی به متر باشد. به عنوان مثال*Footpath (4.0m)*. این اطلاعات هنگام به‌روزرسانی OSM بسیار مفید بوده می‌توان تصمیم گرفت که آیا یک ویژگی موجود را جهت تراز کردن با مسیرهای و نقاط بین‌راهی جدید جابجا کرد.  
- **استفاده از تقریب HDOP** مربوط به محاسبات اضافی برای بهبود دقت موقعیت (Horizontal Dilution of Precision).  
- **Export Compass Heading** تعریف می‌کند که آیا و چگونه داده‌های قطب نما باید به فایل GPX صادر شود.  
- **منبع عکس پیش‌فرض** به طور کلی از طریق دوربین عکس می‌گیرید، اما می‌توانید از عکس‌هایی که قبلاْ در گوشی وجود دارند استفاده کنید.  
- **صفحه نمایش همیشه روشن** این گزینه را در صورتیکه مداوم بر روی دکمه‌ها کلیک می‌کنید، عکس میگیرید، و یا صدا ضبط میکنید انتخاب کنید - در غیر اینصورت، آن را خالی بگذارید فقط باید هربار که میخواهید صفحه روشن شود دکمه پاور را بزنید البته کمتر از باتری  استفاده می‌شود.  
- **تم گرافیکی صفحه اصلی** اگر با دیدن دکمه‌ها مشکل دارید، گزینه‌هایی برای تغییر کنتراست و روشنایی صفحه نمایش ارائه می‌کند.  
- **دکمه‌های از پیش آماده** می‌توانید مجموعه دکمه‌های خودتان را طراحی و نصب کنید و با استفاده از این گزینه آنها را برای نمایش انتخاب کنید. برای شرح کامل این عملکرد، [این زیر را ببینید](/fa/mobile-mapping/osmtracker/#button-presets).   
- **نقشه پسزمینه** با فشار دادن و نگه داشتن یک مسیر ضبط شده، اگر این ویژگی انتخاب شده باشد، ضمن نمایش مسیر، برنامه داده‌های OpenStreetMap را به عنوان پس زمینه دانلود می‌کند.  

> این کار نیاز به اتصال داده دارد تا نقشه را دانلود کند. لازم نیست حتماْ از حالت استفاده کنید.  

- **ارائه دهنده کاشی نقشه** اگر انتخاب کرده‌اید که نقشه‌ای در پس‌زمینه نشان داده شود، می‌توانید انتخاب کنید کدام نسخه از نقشه به عنوان پس‌زمینه باشد.  
- **جهت** آیا می‌خواهید چرخش صفحه فعال باشد یا اینکه از حالت افقی یا عمودی صفحه استفاده می‌کنید؟  

لیست مسیرها
--------------

![OSMTracker_2][]  
پس از انجام بررسی اولیه، کلیک روی دکمه‌ها، ضبط صدا و گرفتن عکس، در پایان روی آیکن فلاپی دیسک برای تمام کردن ضبط مسیر کلیک کنید. حالا روی نام مسیر در لیست نگه داشته و گزینه‌های زیر در دسترس قرار می‌گیرد:  

- **ادامه ضبط** در صورتی که فکر می‌کنید هنوز قسمتی از مسیر مانده است به درد می‌خورد!  
- **نمایش** مسیر را نشان می‌دهد، احتمالاْ با یک نقشه پس‌زمینه در صورت وجود اتصال داده و انتخاب بودن گزینه **نقشه پس‌زمینه**.  
- **خروجی به عنوان GPX** - برای ویرایش و استفاده از مسیر و نقاط بین‌راهی در یک برنامه ویرایش لازم است.  
- **آپلود به OpenStreetMap** از این گزینه برای ارسال مسیر خود به OpenStreetMap استفاده کنید - باید یک حساب OpenStreetMap داشته باشید ([ساختن حساب اینجا توضیح داده شده است](/fa/beginner/start-osm/)) و نیاز است که مجوز تأیید این برنامه برای ارسال مسیر ردیابی شده به حساب کاربریتان داده شده باشد. برای اطلاعات بیشتر در مورد این که چرا این رکوردها برای OpenStreetMap بسیار مهم هستند، می‌توانید [مسیرهای GPX - فایلهای gpx زیر](/fa/mobile-mapping/osmtracker/#gps-traces--gpx-files) را ببینید.  

> **توجه داشته باشید، مسیر خود را هنوز حذف نکنید** شما فقط مسیر ردیابی شده اصلی را آپلود کرده‌اید و نه نقاط بین‌راهی، تصاویر و غیره را. همه چیز را تا زمانی که آنها را برای ویرایش به یک رایانه منتقل نکرده‌اید، حفظ کنید.  

-  **حذف**. واضح است.  


دکمه‌های از پیش آماده
--------------

اگر دربه دلیل خاصی در حال بررسی مسیر هستید و برچسب نقاز بین‌راهی موجود نیست، می‌توانید مجموعه نقاط بین‌راهی خود را قبل از سفر انتخاب و چینش نموده، آنها را در تلفن بارگیری کرده و در هنگام سفر در صورت نیاز آنها را انتخاب کنید - چندین قالب از پیش آماده میتوان داشت و بدون توقف در طول ضبط مسیر بین آنها سوئیچ کنید. اگر برچسبی که ایجاد می‌کنید به صورت یک یادداشت شخصی است، لازم نیست که مطابق با برچسب‌های استفاده شده در OpenStreetMap باشد و به آن آپلود نخواهد شد. به عنوان مثال، ممکن است دکمه‌هایی با برچسب‌های ذیل داشته باشید:  

- ۱ خانوار  
- ۲ خانوار  
- ۳ خانوار  
- ۴ خانوار،  
- خانه رئیس   
- ٪۲۰ آسیب‌دیده،  
- ٪۴۰ آسیب‌دیده،  
- ٪۶۰ آسیب‌دیده،  
- ٪۸۰ آسیب‌دیده،  
- مخروبه،  
- نامناسب برای کامیون،  
- ۴ دیفرانسیل مورد نیاز است،  
- و غیره..  

برای توضیحات کامل در مورد ایجاد دکمه‌های پیش‌فرض، [بخش ویکی OSMTracker](https://github.com/nguillaumin/osmtracker-android/wiki/Custom-buttons-layouts) را ببینید. این یک [فایل دانلود نمونه است.](/files/R_of_Way.xml)  

![OSMTracker button presets][]  


ضبط صدا، اندازه عکس و متن تصویر  
----------------------------------------------  

![OSMTracker recorded file sizes][]  

در مرحله بعد اگر به فکر انتقال فایل هستید، به اندازه فایلها توجه داشته باشید - همانطور که این عکس از صفحه نشان می‌دهد تصاویر نسبت به فایلهای gpx یا حتی ۱۰ ثانیه صدای ضبط شده حافظه بسیار بیشتری را می‌بلعند.  


مسیرهای GPS - فایلهای gpx
----------------------  

![OSMTracker JOSM][]  

مسیر ردیابی شده GPS در قالب فایلهای gpx از چندین عنصر تشکیل شده‌اند، که عمدتاْ "مسیر" و "نقاط بین‌راهی" هستند. تصویر بالا محتویات پوشه‌ای را نشان می‌دهد که در OSMTracker ایجاد شده و در JOSM بارگزاری شده و آماده ویرایش است، و تصاویر ماهواره‌ای نیز برای کمک بارگذاری شده است. نماد مربع در مرکز مسیر ردیابی نشان می‌دهد یک عکس در این محل گرفته شده است - به آسانی روی آیکن مربع برای نمایش عکس کلیک کنید.  

اگر در حال حرکت هستید و برای مسیریابی از GPS استفاده می‌کنید، متوجه خواهید شد که در این نقطه 'محاسبه مجدد مسیر' انجام می‌شود. این معمولاْ به این دلیل است که موقعیت GPS منطبق بر جایی که انتظار میرود جاده و یا مسیر باشد نیست - حاشیه خطا وجود دارد، اما به سادگی امکان دارد که جاده‌ها و مسیرها در مکان اشتباه قرار داده شوند و یا جاده پس از ایجاد داده‌های نقشه، جابجا شده باشد.  
داوطلبانی که OpenStreetMap را بروزرسانی می‌کنند می‌توانند تمام مسیرهای ردیابی شده‌ای که در یک منطقه آپلود شده‌اند را دانلود کرده و از آنها استفاده کنند در:  

1. ترسیم مسیرها و جاده‌هایی که توسط تصاویر ماهواره‌ای به دلیل وجود ابر، درختان، سایه‌ها، ساختمان‌ها و غیره دیده نمی‌شود.  
2. تنظیم تصاویر ماهواره‌ای تا به درستی تراز شوند - برخی تصاویر با هم اختلاف فاحشی دارند.  

اگر چه یک مسیر gpx تنها مفید است، ممکن است کاملاْ دقیق نباشد و می‌تواند تا ۳۰ متر خارج از محل باشد. هنگامی که چندین مسیر از یک محل وجود دارد، دیدن مسیر صحیح عبور جاده آسان می‌شود - به عنوان مثال تصویر زیر دانلود مسیرهای ردیابی شده gpx یک شهر را نشان می‌دهد که در آن جاده‌های اصلی را می توان توسط حجم ردیابی دید.  

![OSMTracker_gpx][] 




[OSMTracker Logo]: /images/mobile-mapping/osmtracker_logo.png
[OSMTracker_1]: /images/mobile-mapping/OSMTracker_1.png
[OSMTracker_2]: /images/mobile-mapping/OSMTracker_2.png
[OSMTracker button presets]: /images/mobile-mapping/OSMTracker_presets.png
[OSMTracker recorded file sizes]: /images/mobile-mapping/OSMTracker_files.png
[OSMTracker_gpx]: /images/mobile-mapping/OSMTracker_gpx.png
[OSMTracker JOSM]: /images/mobile-mapping/OSMTracker_JOSM.png