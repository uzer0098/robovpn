<p align="center">
  <a href="https://github.com/wizwizdev/wizwizxui-timebot" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/27927279/227711552-d2bc1089-5666-477b-9be7-d7e50a5286dc.png">
      <img width="200" height="200" src="https://user-images.githubusercontent.com/27927279/227711552-d2bc1089-5666-477b-9be7-d7e50a5286dc.png">
    </picture>
  </a>
</p>

<p align="center">
	<a href="./README.md">
	English
	</a>
	/
	<a href="./README-fa.md">
	فارسی
	</a>

</p>

<h1 align="center"/>ویزویز</h1>

<p align="center">
فروش آسان با <a href="https://github.com/wizwizdev/wizwizxui-timebot">ویزویز</a> نصب فقط با یک دستور
</p>

<p align="center">
ویزویز یک ربات قدرتمند و حرفه ای است که از چندین نوع پنل پشتیبانی می کند و بهترین گزینه برای فروش است، اکثر پروتکل ها را پشتیبانی می کند و نصب آسانی دارد. این ربات برای مردم عزیز ایران آماده شده است. یک جایگزین عالی برای فروش است تا بتوانید به راحتی کار خود را مدیریت کنید.
</p>


<div align=center>

[![Telegram Channel](https://img.shields.io/endpoint?label=Channel&style=flat-square&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Fwizwizch&color=blue)](https://telegram.dog/wizwizch)
[![Telegram Group](https://img.shields.io/endpoint?color=neon&label=Support%20Group&style=flat-square&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Fwizwizdev)](https://telegram.dog/wizwizdev)
<img src="https://img.shields.io/github/license/wizwizdev/wizwizxui-timebot?style=flat-square" />
<img src="https://img.shields.io/github/v/release/wizwizdev/wizwizxui-timebot.svg" />
<!-- <img src="https://visitor-badge.glitch.me/badge?page_id=wizwizdev.wizwizdev" />
 -->
</div>

<br>
<br>
    <a align="center">
        <img src="https://github.com/wizwizdev/wizwizxui-timebot/assets/27927279/f6635ea5-ab26-4c64-a7b8-952203f79763" />
    </a>     
<br>
<br>







# دستور نصب روی Ubuntu-20.4


- اگر سرور شما دسترسی روت ندارد، لطفا با دستور sudo -i دسترسی روت بدهید و سپس نصب کنید
- یک ربات در @botfather ایجاد کنید و آن را استارت کنید
- قبل از نصب حتما ip سرور را روی دامنه تنظیم کنید 
> دستور نصب را در کنسول وارد کرده و موارد مورد نیاز را برای تکمیل نصب وارد کنید.
```
bash <(curl -s https://raw.githubusercontent.com/uzer0098/robovpn/main/wizwiz.sh)
```
- در مرحله اول «sub.domain.com» یا «domain.com» را بدون https وارد کنید
- ایمیل را وارد کنید
- کلمه y را وارد کنید
- عدد 2 را وارد کنید
- نام کاربری برای دیتابیس را وارد کنید
- رمز عبور برای دیتابیس را وارد کنید
- توکن ربات را وارد کنید
- آیدی عددی ادمین را از @userinfobot بگیرید و وارد کنید
- مجدد «sub.domain.com» یا «domain.com» را بدون https وارد کنید
- بسیار خوب، پیام نصب ( ✅ ربات wizwiz با موفقیت نصب شد! ) به ربات ارسال می شود.

<br>
<br>

## دستور آپدیت ربات - آپدیت پنل - بک آپ - حذف ویزویز

- با هر به روز رسانی و بک آپ، یک اعلان برای ربات مدیر ارسال می شود


```
bash <(curl -s https://raw.githubusercontent.com/wizwizdev/wizwizxui-timebot/main/update.sh)
```

<br>
<hr>
<br>


# سوالات پرتکرار

### درگاه weswap: 
- اگر میخواین از درگاه weswap استفاده کنین اول باید تو سایت nowpayment با یه ایمیل ثبت نام کنین آدرس کیف پول ترون رو بهش بدید و یک کلید api ایجاد کنین و اون رو تو ربات قسمت درگاه  nowpayment قرار بدید ( یعنی اگه شما قرار بدید با این امکان خودکار هم برای nowpayment و هم برای weswap تنظیم میشه، اگه از weswap میخواین استفاده کنین مبلغ فروش شما باید مبلغ بالای 25 تومن باشه و برای nowpayment هم باید بالای 3.5 دلار اینا باشه وگرنه خطا مقدار میگیرد )


### قابلیت reality:
- اگر از قابلیت reality استفاده میکنید اول باید سرور رو ثبت کنید بعد به قسمت تنظیمات سرور برید و سروری که قراره این قابلیت رو داشته باشه رو انتخاب کنید و تیک گزینه reality رو فعال کنید ، بعد یه پلن ایجاد کنین و بعد برید مدیریت پلن ها روی اون پلن بزنید و پلن رو انتخاب کنین یه قسمتی هست به اسم dest - servername - flow - SpiderX حتما باید این 4 تا مورد رو تنظیم کنید و سپس خروجی کانفیگ درست رو میگیرید، اگر اطلاعات غلط یا اشتباه وارد کنید احتمال stop شدن پنل شما وجود دارد و حتما قسمت dest دامنه ای که وارد میکنید باید دارای پورت باشد مثلا 443



### ارسال ناقص کانکشن یا سفید در ربات:
- اگر به این مشکل خوردین این دوتا دستور رو توی سرورتون وارد کنید و به جای پورت پنل باید پورت پنل x-ui رو وارد کنین و فایروال هم باید روشن کنید 

- sudo ufw allow پورت پنل/tcp
- sudo ufw allow پورت پنل/udp



### مشکل stop شدن پنل x-ui:
- اگر با گرفتن کانکشن از ربات دچار stop شدن پنل شدید به خاطر این هست که تنظیمات ربات رو درست انجام ندادین برای ایجاد سرور و پلن میتونید از طریق این <a href="https://uupload.ir/view/wizwiz_6gtf.docx">لینک</a> آموزش رو دانلود کنید و انجام بدین



### افت سرعت ربات بعد از مدتی:
- دلیلش این هست که تعداد کاربر یا سرور شما بیشتر شده و باید سرور رو ارتقا بدید



### قفل اجباری کانال:
- برای قفل اجباری کانال، مطمئن شوید که ربات ادمین کانال است و تمام دسترسی ادمین را به آن بدهید (همه آنها را علامت بزنید)


### تروجان: 
- اگر از پروتکل تروجان استفاده می کنید، پنل x-ui شما باید از تروجان پشتیبانی کند، در غیر این صورت پنل شما با مشکل مواجه می شود.


### اعلان باقیمانده حجم و روز: 
- در صورتی که ترافیک باقیمانده سرویس به یک گیگابایت و زمان باقی مانده به یک روز برسد، برای کاربر اعلان ارسال می شود و اگر کاربر ظرف 48 ساعت سرویس را تمدید نکند، اعلان حذف سرویس برای کاربر ارسال می شود و سرویس حذف می شود.


### اکانت تست: 
- برای ایجاد اکانت تست باید ابتدا یک دسته و یک پلن اختصاصی فقط مربوط به اکانت تست ایجاد کنید و نباید این دسته و پلن هیچ تداخلی با قسمت فروش داشته باشد و قیمت را روی 0 قرار دهید، هر کاربر فقط یک بار می تواند اکانت تست را داشته باشد.


### رکوئست هدر:
- برای استفاده از رکوئست هدر در ربات به قسمت مدیریت سرور برید و یه سرور رو انتخاب کنید سپس باید مقدار Header Type را روی http قرار دهید و مقدار request headerهم باید  Host:domain.ir را  وارد کنید و در صورتی که چندتا هدر میخواید فعال کنید از مقدار Host:domain1.ir,domain2.ir استفاده کنید


### ثبت نشدن سرور در ربات:

- اگر هنگام خرید با خطای ( ارتباط شما با سرور برقرار نیست ) برخوردید حتما این <a href="https://t.me/wizwizch/186">ویس</a> رو گوش بدید



### ادیت سورس:

  - نرم افزار winscip یا termius نصب کن که دسترسی به فایل داشته باشی یا از طریق سایت shellngn برو وقتی رفتی وارد این مسیر شو و هر فایلی خواستی ادیت بزن

```
/var/www/html/wizwizxui-timebot
```
 





<br>
<hr>
<br>



# پنل های پشتیبانی شده


- (Niduka Akalanka)
````
bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh) 0.2.1.2
````
- (Sanaei)
````
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh) v1.6.1
````
- (Alireza)
````
bash <(curl -Ls https://raw.githubusercontent.com/alireza0/x-ui/master/install.sh) 1.4.1
````
- (Vaxilu)
````
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
````



<br>
<hr>
<br>


# حمایت

- Sepe Bank: `5892101222351344`
- Tron (TRX): `TY8j7of18gbMtneB8bbL7SZk5gcntQEemG`
- Bitcoin: `bc1qcnkjnqvs7kyxvlfrns8t4ely7x85dhvz5gqge4`
- Dogecoin: `DMyGMghEh4W55P3VeVHntCN3vYAFtshvVH`



<br>
<hr>
<br>


# امکانات

- درگاه nowpayments - zarinpal - nextpay - weswap
- پشتیبانی از - xtls - tls - reality - Grpc - ws - tcp
- پشتیبانی vless - vmess - trojan
- امکان تمدید سرویس
- اشتراک هوشمند
- وضعیت فیلتر شدن سرورها
- تغییر مکان خودکار
- افزایش حجم و زمان سرویس دهی
- قابلیت پاس کردن
- امکان سفارش طرح مورد نظر توسط کاربر
- احراز هویت شماره تماس ایرانی و خارجی
- پشتیبان گیری از پنل x-ui
- زیر مجموعه و کمیسیون
- کدهای تخفیف و هدیه ایجاد کنید
- امکان ردیابی کاربر
- ایجاد دکمه و پاسخ برای آن
- خروجی پیکربندی با IP یا دامنه های مختلف
- امکان تغییر پروتکل و نوع شبکه
- تنظیم پورت پیکربندی به صورت تصادفی یا خودکار
- کیف پول (امکان شارژ - انتقال موجودی)
- ارسال اعلان عضو جدید در ربات به (ادمین)
- نمایش اطلاعات کاربر (user-admin)
- امکان ارسال پیام خصوصی از ادمین به کاربر
- امکان مدیریت و مشاهده سرورها - دسته بندی ها - پلن ها
- قابلیت مسدود کردن و آزادسازی
- امکان اضافه کردن ادمین
- نمایش موجودی سرورها
- امکان ارسال گزارش درآمد به کانال
- ارسال پیام های عمومی
- پیکربندی های فروخته شده را دریافت کنید
- ایجاد پورت مشترک و پیکربندی پورت اختصاصی
- تست حساب برای کاربران
- قابلیت کارت به کارت
- نمایش حساب های فروخته شده هر طرح
- قابلیت نمایش (لینک نرم افزار)
- ارسال پیام های عمومی با CronJob
- اعلام پایان حجم و زمان پیکربندی (به کاربر)
- قفل اجباری کانال
- امکان دریافت جزئیات لینک
- قابلیت خاموش/روشن (همه ویژگی های ربات)
- اطلاع رسانی اطلاعات خرید + تمدید و ... به صورت کامل به ربات ادمین



<br>
<hr>
<br>


حتما به گروه و کانال بپیوندید و از ما حمایت کنید

## Contact Developer
💎 Group: https://t.me/wizwizdev
💎 Channel: https://t.me/wizwizch

<br>
<br>

## Stargazers over time

[![Stargazers over time](https://starchart.cc/wizwizdev/wizwizxui-timebot.svg)](https://starchart.cc/wizwizdev/wizwizxui-timebot)
