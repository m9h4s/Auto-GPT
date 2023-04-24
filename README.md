# Auto-GPT: An Autonomous GPT-4 Experiment


<hr/>

### 🔴 🔴 🔴 فوری: استفاده از "stable" نه "master" 🔴 🔴 🔴

آخرین نسخه «پایدار» را از اینجا دانلود کنید:
https://github.com/Significant-Gravitas/Auto-GPT/releases/latest

<hr/>


Auto-GPT یک برنامه آزمایشی منبع باز است که قابلیت های مدل زبان GPT-4 را به نمایش می گذارد. این برنامه که توسط GPT-4 هدایت می شود، "افکار LLM" را به هم متصل می کند تا به طور مستقل به هر هدفی که تعیین می کنید دست یابد. به‌عنوان یکی از اولین نمونه‌های GPT-4 که به‌طور کاملاً مستقل اجرا می‌شود، Auto-GPT مرزهای آنچه با هوش مصنوعی امکان‌پذیر است را تغییر می‌دهد.


<h2 align="center"> دمو یکشنبه، ۲۷ فروردین ۱۴۰۲ </h2>

https://user-images.githubusercontent.com/70048414/232352935-55c6bf7c-3958-406e-8610-0913475a0b05.mp4

Demo made by <a href=https://twitter.com/BlakeWerlinger>Blake Werlinger</a>

<h2 align="center"> 🎬 ویدیو آموزش راه اندازی به زبان فارسی 🎬</h2>
<p align="center">
نحوه ی راه اندازی به زبان فارسی
</br>
<a href="https://youtu.be/EjFrAgBaIxQ">لینک ویدیو در یوتیوب</a></p>


</br>
</br>




## 🚀 ویژگی ها

- 🌐 دسترسی به اینترنت برای جستجو و جمع آوری اطلاعات
- 💾 مدیریت حافظه بلند مدت و کوتاه مدت
- 🧠 نمونه های GPT-4 برای تولید متن
- دسترسی به وب سایت ها و سیستم عامل های محبوب
- 🗃️ ذخیره سازی و خلاصه سازی فایل با GPT-3.5
- 🔌 قابلیت توسعه با پلاگین ها

## 📋 الزامات

محیطی را برای اجرای Auto-GPT در آن انتخاب کنید (یکی را انتخاب کنید):
  - [Docker](https://docs.docker.com/get-docker/) (*recommended*)
  - Python 3.10 or later (instructions: [for Windows](https://www.tutorialspoint.com/how-to-install-python-in-windows))
  - [VSCode + devcontainer](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## شروع سریع
1. Set up your OpenAI [API Keys](https://platform.openai.com/account/api-keys)
2. Download the [latest release](https://github.com/Significant-Gravitas/Auto-GPT/releases/latest)
3. Follow the [installation instructions][docs/install]
4. Configure any additional features you want, or install some [plugins][docs/plugins]
5. [Run][docs/usage] the app

Please see the [documentation][docs] linked below for full setup instructions and configuration options.

[docs]: https://significant-gravitas.github.io/Auto-GPT/

## 📖 مستندات
* [⚙️ نصب و راه اندازی][docs/install]
* [💻 استفاده][docs/usage]
* [🔌 پلاگین ها][docs/plugins]
* پیکربندی
  * [🔍 جستجوی وب](https://significant-gravitas.github.io/Auto-GPT/configuration/search/)
  * [🧠 حافظه](https://significant-gravitas.github.io/Auto-GPT/configuration/memory/)
  * [🗣️ صدا (TTS)](https://significant-gravitas.github.io/Auto-GPT/configuration/voice/)
  * [🖼️ تولید تصویر](https://significant-gravitas.github.io/Auto-GPT/configuration/imagegen/)

[docs/install]: https://significant-gravitas.github.io/Auto-GPT/installation/
[docs/usage]: https://significant-gravitas.github.io/Auto-GPT/usage/
[docs/plugins]: https://significant-gravitas.github.io/Auto-GPT/plugins/

## ⚠️ محدودیت ها

هدف این آزمایش نشان دادن پتانسیل GPT-4 است اما با محدودیت هایی همراه است:

۱- نه یک برنامه یا محصول صیقلی، فقط یک آزمایش
۲- ممکن است در سناریوهای تجاری پیچیده و واقعی عملکرد خوبی نداشته باشد. در واقع، اگر واقعاً اینطور است، لطفاً نتایج خود را به اشتراک بگذارید!
۳- را بسیار گران است، بنابراین محدودیت های کلید API خود را با OpenAI تنظیم و نظارت کنید!


## 🛡 سلب مسئولیت

سلب مسئولیت این پروژه، Auto-GPT، یک برنامه آزمایشی است و بدون هیچ گونه ضمانت، صریح یا ضمنی، "همانطور که هست" ارائه شده است. با استفاده از این نرم‌افزار، شما موافقت می‌کنید که تمام خطرات مرتبط با استفاده از آن، از جمله از دست دادن داده‌ها، خرابی سیستم، یا هر مشکل دیگری که ممکن است ایجاد شود، به عهده بگیرید.

توسعه دهندگان و دست اندرکاران این پروژه هیچ گونه مسئولیت یا مسئولیتی در قبال هرگونه ضرر، خسارات، یا سایر عواقبی که ممکن است در نتیجه استفاده از این نرم افزار رخ دهد، نمی پذیرند. شما تنها مسئول هر تصمیم و اقدامی هستید که بر اساس اطلاعات ارائه شده توسط Auto-GPT انجام می شود.

لطفاً توجه داشته باشید که استفاده از مدل زبان GPT-4 به دلیل استفاده از توکن آن ممکن است گران باشد. با استفاده از این پروژه، تصدیق می‌کنید که مسئولیت نظارت و مدیریت استفاده از رمز خود و هزینه‌های مرتبط با آن را بر عهده دارید. به شدت توصیه می شود که استفاده از OpenAI API خود را به طور منظم بررسی کنید و هرگونه محدودیت یا هشدار لازم را برای جلوگیری از هزینه های غیرمنتظره تنظیم کنید.

به عنوان یک آزمایش مستقل، Auto-GPT ممکن است محتوا تولید کند یا اقداماتی انجام دهد که با رویه‌های تجاری واقعی یا الزامات قانونی مطابقت ندارد. این مسئولیت شماست که اطمینان حاصل کنید که هر اقدام یا تصمیمی که بر اساس خروجی این نرم افزار گرفته می شود با تمام قوانین، مقررات و استانداردهای اخلاقی قابل اجرا مطابقت دارد. توسعه دهندگان و مشارکت کنندگان این پروژه مسئولیتی در قبال عواقب ناشی از استفاده از این نرم افزار ندارند.

با استفاده از Auto-GPT، شما موافقت می‌کنید که توسعه‌دهندگان، مشارکت‌کنندگان، و طرف‌های وابسته را از هرگونه ادعا، خسارات، زیان‌ها، بدهی‌ها، هزینه‌ها و هزینه‌ها (از جمله هزینه‌های معقول وکیل) غرامت، دفاع و بی‌ضرر نگه دارید. ناشی از استفاده شما از این نرم افزار یا نقض این شرایط.
