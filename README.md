
<h1 align="center"> # شخصی سازی پنل BPB 💦 </h1>

😎 با کمک [این سایت](https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html) :   
<p align="left">https://raw.githack.com/liMilCo/BPB-ReCoder/main/recoder.html</p>
  <p align="justify">
شما می توانید کد های پلن را کاملا شخصی سازی کنید.
از انجا که کلودفلر با برسی کد ها، پروژه را شناسایی و بند میکند برای جلوگیری از ارور 1011 باید کلمات کلیدی مانند نام توابع، آدرس دسترسی به پنل و داده های متغیر و دیتابیس KV را تغییر داده شود. پروژه هایی مثل EN panel این کار را انجام داده اند اما بعد از یک مدت ممکن است این کد های جدید هم شناسایی شوند. بهترین راه حل این است که هر کاربر برای خود یک پنل با کدهای شخصی سازی شده بسازد و این برنامه این کار را برای شما انجام خواهد داد.
</p>

# اول

## کد های اصلی و خام پروژه BPB را در باکس اول وارد کنید:
![image](https://github.com/user-attachments/assets/145586fd-7520-4c44-b2b7-8f8acddbb87e)
### شما مي توانيد کد هاي خام ورژن 2.8.1 پروژه را از [اينجا ](https://raw.githubusercontent.com/liMilCo/BPB-ReCoder/main/worker.2.8.1.js)و ورژن 2.7.4 را از [اينجا ](https://github.com/bia-pain-bache/BPB-Worker-Panel/releases/download/v2.7.4/worker.js)تهيه نماييد.


# دوم


## وارد کردن اطلاعات ورود به پنل

### باکس هایی که باز هستند وارد کردن اطلاعات اجباری می باشد و باکس هایی که پیشفرض بسته هستند مثل (صفحه اصلي) یا (توابع فرعي) میتوانید خالی بگزارید

![image](https://github.com/user-attachments/assets/888f7e7e-d0c7-47ac-999d-85462e112b41)

توجه کنید وقتی پروژه شخصی سازی شده خود را در گیتهاب اجرا میکنید برای دسترسی به پنل بجای کلمه `panel `در آدرس

` BPB.SUB.workers.dev/panel`

باید از کلمه ای که در اینجا استفاده کرده اید استفاده کنید (مثلا در اینجا ما `myadmin` را انتخاب کرده ایم پس با این آدرس وارد پنل خواهیم شد:

` BPB.SUB.workers.dev/myadmin`

## انتخاب یک سایت برای صفحه اول یا روت برنامه
این سایت پیشفرض speedtest کلودفلر هست و وارد کردن آن اختیاریست و میتوانید آن را خالی بگزارید
اگر خواستید یک آدرس انتخاب کنید اول مطمعن شوید که املای کلمات را کاملا درست وارد کنید و سایتی را انتخاب کنید که سبک و ساده باشد وگرنه تعداد درخواست های زیاد به سرور کلودفلر فشار وارد میکند.

![image](https://github.com/user-attachments/assets/bbc0210f-b224-4e47-8181-bd1a7ec73153)


## وارد کردن اطلاعات مربوط به دیتابیس KV و متغیر های کلودفلر:

همان طور که در آموزش های پنل خوانده اید برای اتصال دیتابیس باید بعد از ساخت KV حتمی باید ان را با نام bpb به پنل معرفی نمایید، در اینجا شما باید این نام را تغییر دهید.

همچنین کلمات UUID و TROJAN_PASS و PROXYIP که آنها را در `Settings` بخش `Variables and Secrets`  وارد میکردید، باید تغییر دهید و آن ها را بخاطر بسپارید زیرا این کلمات با دقت باید در کلودفلر ثبت شوند.

![image](https://github.com/user-attachments/assets/f6c99917-6a5a-4c6e-8c16-aeec8bde6a52)

مطابق مثال :

![image](https://github.com/user-attachments/assets/8a38f229-5ec7-40d7-842f-1293acef5598)

### دقت کنید که حروف بزرگ و کوچک انگلیسی مهم هست و باید دقیقا همان کلمه وارد شود

**👈 این کلمات بعد از یک بار اجرای کد در مرورگر ذخیره میشوند ولی بهتر است آنها را در یک جا یاداشت کنید 👉**

## تغییر نام توابع در پروژه
از انجا که از اولین پروژه تونل پروکسی که برای کلودفلر نوشته شد نام توابع ثابت مانده است و حتی بعد از obfuscation کردن کدها هم تغییر نمیکند و کلودفلر به راحتی کد های این پروژه ها را شناسایی میکند. توابعی مانند vlessOverWSHandler و handleTCPOutBound خیلی سریع توسط کلودفلر شناسایی میشوند.

برای راحتی کار شما میتوانید با کلیک بر روی 🎁 یک نام شانسی برای این توابع انتخاب کنید.

![image](https://github.com/user-attachments/assets/8c64c378-d206-4fd1-9aa4-b028da7e34e1)


## حالت پیشرفته تغییر توابع

بخش توابع فرعی هم مثل توابع اصلی میباشد اما تغییر انها اجباری نیست اما برای اطمینان از شناسایی نشدن توسط کلودفلر میتوانید انها را نیز تغییر دهید.


![image](https://github.com/user-attachments/assets/61ae844b-0d00-4b99-9713-a1d7ff9b16bd)


# سوم

برای ایجاد تغییرات دکمه  `Generate New BPB 🌊` را فشار دهید
در باکس مربوطه کد های تغییر کرده را نمایش میدهد که میتوانید ان را دانلود کنید

![image](https://github.com/user-attachments/assets/399fa6d6-7873-42db-8b3c-371f99a79952)

# چهارم 
بعد از ایجاد تغییرات با دکمه `Obfuscator Code 💨` میتوانید در همین صفحه کد ها را Obfuscator کنید
بعد انها را کپی کرده در workers پیست کنید یا دانلود کرده و در pages آپلود کنید.

![image](https://github.com/user-attachments/assets/4b5aa91a-1998-4e11-9236-d993a8fcca42)

