is an open source wiki engin used by many small to medium size companies internally. မကြာမှီပြင်ဆင်ဖြည့်စွတ်မည်။

	sudo  apt-get  install   twiki

####Moin Moin

[Moin Moin](http://moinmo.in/) is free ,open source (GPL-Licensed) wiki မကြမှီပြင်ဆင်ဖြည့်စွတ်မည်။

	sudo  apt-get  install  python-moinmoin

####Tiddly  Wiki

[Tiddly Wiki](http://www.tiddlywiki.com/)is an open source personal wiki. မကြာမှီပြင်ဆင် ဖြည့်စွတ်မည်။

###Wed  Publishing

####Drupal (Web  content  publishing)

[Drupal](http://drupal.org/)သည် website များဖန်တီးခြင်းနှင့်ပူးပေါင်းဆောင်ရွက်ခြင်းတို့တွင် 
အသုံးပြုနေကြသည့်tool  များထဲတွင် ထိပ်ဆုံးမှရပ်တည်နေသည့် open-source  တစ်ခုဖြစ်သည်။ရိုးရှင်းသော  website  များမှသည်အလွန်ရှုပ်ထွေးသော website များအထိ အချိန်အနည်းငယ်ပေးလေ့လာရုံဖြင့် ဖန်တီးရေးဆွဲနိုင်သည့် module အခြေပြု wetside ဖန်တီးသည့် toolဖြစ်သည်။ စတင်သုံးစွဲနည်းတွင် သတင်းအချက်အလက်များ စုံစုံလင်လင် ရာယူနိုင်ပါသည်။ Drupal အသုံးပြုရန်အတွက် LAMP server အား 
(Install မလုပ်ရသေးပါက Install ပြုလုပ်ရန်လိုအပ်ပြီး Drupal နှင့် တပါတည်း Install  ပြုလုပ်နိုင်ပါသည်။ Drupal ကို MySQL database (LAMP ရှိ M) နှင့်အလွယ်တကူ အသုံးပြုနိုင်ပြီး PostgreSQL( Install 
ပြုလုပ်ထားပါက ) နှင့်လည်း အသုံးပြုနိုင်ပါသည်။


#####Drupal 17

Drupal 17 ၏ Debian package အား [ဤနေရာတွင်](https://packages.debian.org/sid/all/drupal7/) ရရှိနိုင်ပါသည်။ သင့် system (32 bit သို့မဟုတ် 64 bit) အတွက် package အား download ပြုလုပ်ကာ package
အား Synaptic သို့မဟုတ် Kpackage Kit စသည့် package manager များ အသုံးပြုပြီး  Install ပြုလုပ်နိုင်သည်။ (K) Ubuntu OS အသစ်တွင် တိုက်ရိုက် Install ပြုလုပ်နိုင်ရုံသာမက Debian respository ကိုပါ (Download
page တွင် ဖော်ပြထားသည့် လမ်းညွှန်ချက်အတိုင်း ) ထည့်သွင်းနိုင်ပြီး Install ပြုလုပ်နိုင်သည်။

-Drupal6 မှ Drupal7 သို့ပြောင်းလဲရန်အတွက် [ဤလမ်းညွှန်ချက်](http://drupal.org/node/570162) များအတိုင်း ပြုလုပ်နိုင်ပါသည်။


#####Drupal6 (Web content publishing)

Drupal6 အား package အဖြစ်ရယူနိုင်ပြီး  `command - line terminal` မှ လည်းရရှိနိုင်သည်။

	sudo apt-get install drupal6

install ပြုလုပ်ပြီးပါက( ဖြစ်လာနိုင်သည့်  ပြသနာအနည်းငယ်အား အောက်တွင်ဖော်ပြထားသည် ) apache2
server အား restart ပြုလုပ်ပါ။

	sudo/etc/init.d/apache2 restart

သင့် browser မှတစ်ဆင့် installation အား အပြီးသတ်ပေးပါ။

	http://localhost/drupal6/install.php

Install ပြုလုပ်ခြင်းအတွက် သင့် browser မှ တစ်ဆင့် ဤ installation tips များအားဖတ်ရှုပါ။ ပြီးနောက် Durpal site building tip များအား ကြည့်ရှုပါ။ Drupal /Ubuntu အသုံးပြုသည့် Group အား Drubuntu တွင်
တွေ့ရှိနိုင်ပါသည်။


###Installation quirks

	libgd 2- xpm

When I installed my Ubuntu server, it installed [libgd 2-noxpm
](http://package.ubuntu.com/jaunty/libgd2-noxpm). This is a graphics library without [X pixmap (XPM)](http://en.wikipedia.org/wiki/X_PixMap) or font configuration (fontconfig)
support). However, Drupal requires [libgd2-xpm](http://packages.ubuntu.com/jaunty/libgd2-xpm),which is used instead of libgd2-Xpm.Removing libgd 2-xpm doesn't appear to be trivial,
however.I could not remove it using apt,Adept,or KPackageKit.
 
However, Synaptic Package Manager does appear to remove libgd2-noxpm successfully,and
then libgd2-xpm can be installed.---

####Exim vs. Postfix

[Exim](http://www.exim.org/) နှင့် [Postfix](http://www.postfix.org/) တို့သည် mail ထိန်းချုပ်သည့် software များဖြစ်ပါသည်။ Drupal6 သည် Exim ကို အသုံးပြုထားသည့်အတွက်  Postifix အား install ပြုလုပ်ထားပါက ဖြုတ်ပစ်ပြီး Exim ကို အသုံးပြုထားသည့်အတွက် Postfix ကို အသုံးပြုထားသော 
mail server တွင် Drupal6 အား အသုံးမပြုပါက ပိုကောင်းပါသည်။

####WordPress

[WordPress](http://wordpress.org/) သည် အစပိုင်းတွင် Blog ရေးရာတွင် အသုံးပြုသည့် tool အဖြစ်မှ နောက်ပိုင်းတွင် online စာပေရေးသားထုတ်ပြန်ရာတွင် လိုအပ်သည့် လိုအပ်ချက်များကိုပါ ပေါင်းစပ်ပေးထားသော လူကြိုက်များသည့် open source web content manager တစ်ခုဖြစ်သည်။ Blogger များနှင့် website အသေးစားမှ အလယ်အလတ် အရွယ်အစားများအတွက် Wordpress မှ မြန်နှုန်းမြင့် install ပြုလုပ်ခြင်းနှင့် module များဖြင့် တန်ဆာဆင်ခြင်းများအား ထောက်ပံ့ပေးထားပါသည်။ Wordpress အတွက်
LAMP server အား ဦးစွာ install ပြုလုပ်ထားရန်လိုအပ်ပါသည်။ ထို့နောက် install လုပ်ရန်

	sudo apt-get install wordpress

-Wordpress နှင့် တွဲဖက်အသုံးပြုရန်အတွက် သင့် Apache2 ၏ www folder မှ install ပြုလုပ်မည့် 
folder သို့ သင်္ကေတ link ပြုလုပ်ရမည်ဖြစ်ပြီး  Localhost အမည်ဖြင့် MySQL database
အသစ်ဆောက်ရန် လိုအပ်မည်ဖြစ်ပါသည်။

	sudo in -s /usr/share/wordpress/var/www/wordpress
	sudo bash/usr/share/doc/wordpress/examples/setup-mysql -n wordpress local host

-မှတ်ချက်။ အကယ်၍ Wordpress အတွက် သင့် (virtual )host URL အမည်ကို သိပြီးသားဆိုပါက 
localhost အစား သင့် (virtual)host URL အမည်ကို ထည့်သွင်းပါ။

ဥပမာ သင့် URL သည် `mysite_x.homeserve.org` ဖြစ်သည်ဆိုပါစို့ ။သင်ရေးရမည့် command သည် 

	sudo bash/usr/share/doc/wordpress/examples/setup-mysql-n wordpress mysite_x.homeserve.org

-အကယ်၍ virtual host တစ်ခုမှ သင့် Wordpress server အားချိတ်ဆက်လိုပါက `/etc/apache 2/site-available folder` တွင် သင့် virtual host အတွက် configuration ဖိုင်တစ်ခု ဖန်တီးပါ။  ဖိုင်အား ဖန်တီးတည်းဖြတ်ပြီးပါက ထိုဖိုင်မှ `/etc/apache 2/sites-enabled folder` သို့ သင်္ကေတ link 
ပြုလုပ်ပေးပါ။ Apache 2 အား restart ပြုလုပ်ပါ။

	sudo/etc/init.d/apache 2 restart

Browser မှ တဆင့် Wordpress အား Install ပြုလုပ်ပါ။

	http://localhost/wordpress

သို့မဟုတ် သင့် virtual host မှ တဆင့် install

	http://mysite_x.homeserve.org/wordpress

-မှတ်ချက်။ Jaunty expositories တွင် version 2.7.1 ပါရှိပြီး Security Worm အဖြစ်သတ်မှတ် ခံထားရပါမည်။ အကယ်၍ ထို version အား install ပြုလုပ်ထားပါက Tools - Upgrade menu မှ လက်ရှိ version သို့ ချက်ချင်း Update ပြုလုပ်ပေးပါ။ (သို့မဟုတ် website မှတဆင့် လက်ရှိ version အား install ပြုလုပ်ပါ)

အလိုအလျောက် update ပြုလုပ်လိုပါက Wordpress ၏ files များနှင့် Subfolder များကို www- data(apache 2 လုပ်ဆောင်ချက်များအား ပိုင်ဆိုင်သည်) မှ update ပြုလုပ်ရန် ပိုင်ဆိုင်ရန် လိုအပ်ပါသည်။

	sudo chown-R www-data/usr/share/wordpress
