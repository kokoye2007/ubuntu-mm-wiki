
####Joomla (Web content publishing)

[Joomla](http://www.joomla.org/) သည် website များ ပြုလုပ်ရာတွင် ရိုးရှင်းသည့် ပုံစံများမှ ရှုပ်ထွေးသော ပူးပေါင်းဆောင်ရွက်များအထိ အသုံးပြုနိုင်သော စွမ်းအားမြင့် open source tool ဖြစ်သည်။ စတင်အသုံးပြုရန် [info for beginners](http://docs.joomla.org/Beginners) ကို ကြည့်ရှုသင့်သည်။

####Scribus (Desktop publishing)

[Scribus](http://www.scribus.net/) သည် desktop publishing အတွက် professional တစ်ခုအဖြစ် အသုံးပြုနိုင်သော open-source package တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install scribus

#### Plone (Content Management System)

[Plone](https://plone.org/) သည် ကမ ္ဘာအနှံ့ရှိ လုပ်ငန်းကြီးများတွင် အသုံးပြုနေသည့် content management system ဖြစ်ပြီး platform မျိုးစုံတွင် အခမဲ့ အသုံးပြုနိုင်သော open source (GPL - licensed ) system ဖြစ်သည်။ Installer ကို [ဒီနေရာ](http://plone.org/products/plone) တွင် ရယူနိုင်သည်။ Python ကို ပြောင်းလဲထားသောကြောင့် အချို့အသုံးပြုသူများအနေဖြင့် Jaunty တွင် အခက်အခဲတွေ့နိုင်ပါသည်။

####Gallery (Photo album website)

[Gallery](http://gallery.menalto.com/) သည် PHP ကို အခြေပြုထားပြီး ဓာတ်ပုံ အယ်လ်ဘမ်များအား website တွင် ပြသနိုင်အောင် ပြုလုပ်ပေးသည့် tool တစ်ခုဖြစ်သည်။ Drupal အတွက် Gallery 2 Drupal interface အား ရရှိနိုင်ပါသည်။ Install ပြုလုပ်ရန်

[php BB (Forums) php BB](http://www.php BB.com/) သည် Forum များတည်ဆောက်ရန် အသုံးပြုသည့် အခမဲ့ open source platform တစ်ခုဖြစ်သည်။ LAMP server (သို့မဟုတ်) PostgreSQL database အား install ပြုလုပ်ထားရန် လိုအပ်သည်။ Install ပြုလုပ်ရန်အတွက် universe repositories အား enable ပြုလုပ်ထားရန် အထူးလိုအပ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install phpbb3

###Distance teaching

####Moodle

Moodle သည် အွန်လိုင်း သင်ကြားရေး cource များ hosting ပြုလုပ်နိုင်ရန်အတွက် အခမဲ့ open source platform တစ်ခုဖြစ်သည်။ Webinar software ဖြင့်လည်း တွဲဖက်အသုံးပြုနိုင်သည်။ LAMP server အား Install ပြုလုပ်ထားရန် (sudo tasksel install lamp-server) လိုအပ်သည်။ Moodle ၏ အခမဲ့ theme များအား ဤနေရာတွင် ရယူနိုင်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get moode

Moodle အတွက် Database server software (mysql-server-) ထည့်သွင်းလိုပါက ဖော်ပြပါ လမ်းညွှန်ချက်များအား လုပ်ဆောင်ပါ။ Moodle အား ထည့်သွင်းထားသည့် computer ပေါ်တွင် database အား တည်ဆောက်၍ localhost option အား acept လုပ်ပါ။ လိုအပ်ပါက Moodle configuration အား တည်းဖြတ်ပါ။

	sudo gedit/etc/moodle/config.php

လိုအပ်ပါက `Moodle apache 2 configuration file` အား တည်းဖြတ်ပါ။

sudo gedit/etc/moodle/apache.conf

Browser မှတဆင့် install ပြုလုပ်ခြင်းအား အဆုံးသတ်ပါ။ (unattended install ပြုလုပ်ခြင်းမှာ ပိုသင့်တော်ပါသည်။)

`http://localhost/moodle/admin` 

စုံလင်စွာလေ့လာရန်အတွက် အသေးစိတ်အချက်အလက်များတွင် ကြည့်ရှုပါ။

####Claroline

[Claroline](http://www.claroline.net/) သည် e-learning course များ hosting ပြုလုပ်ရန်နှင့် ကျောင်းသား/ကျောင်းသူများ အွန်လိုင်းတွင် ပူးပေါင်းလုပ်ဆောင်နိုင်ရန်အတွက် ပြုလုပ်ထားသည့် အခမဲ့ open-source platform တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်အတွက် LAMP server အား install ပြုလုပ်ထားရန်လိုအပ်သည်။ installation အတွက် source file အား ၎င်း website တွင်ရယူနိုင်ပြီး လမ်းညွှန်ချက်များအား [ဤနေရာတွင်](http://www.claroline.net/documentation/tutorials.html) တွေ့နိုင်သည်။

####Dokeos

[Dokeos](http://www.dokeos.com/) သည် အခမဲ့ သင်ကြားရေး platform တစ်ခုဖြစ်ပြီး ဆေးပညာဆိုင်ရာ ပုံများ၊ case presentation များပါ ပါဝင်သည်။ ဥရောပတွင် ကျယ်ကျယ်ပြန့်ပြန့် အသုံးပြုနေကြပါသည်။

###Software Development

####Kompozer Web Development Editor

[Kompozer](http://kompozer.net/) is a [Gecko](http://en.wikipedia.org/wiki/Gecko_(Layout_engine))

	sudo apt-get install kompozer

####Quanta Plus (Web IDE )

[Quanta Plus](http://quanta.kdewebdev.org/)

	sudo apt-get install quanta kompare kxsldbg cervisia

####Netbeans IDE

[Netbeans](http://www.netbeans.org/features/) is a free open-source

	sudo apt-get install netbeans

####BlueFish Web Development Editor

[BludFish](http://bluefish.openoffice.nl/) is a GTK-based (Gnome - oriented) editor to write websites,scripts and programming code. It supports perl, Python, pHp, CSS, XML , Java, Javascript, C, SQL , and other formats.

	sudo apt-get install bluefish

####Gobby ( Multi - user development)

[Gobby]( http://gobby.0x539.de/trac/) is a free, multi - platform open source collaborative editor supporting multiple documents in one session and a multi - user chat. Install:

	sudo apt-get install gobby

####Eclipse IDE

[Eclipse](http://www.eclipse.org/home/newcomers.php) is a free open - source cross - platform integrated development environment with plug in support for a large set of programming languages, e.g. Java,C/C++,Python ,PHP.

	sudo apt-get install eclipse

Science, Technology ,and Engineering Applications

What ..you thought Ubuntu was just for pay? Also see Ubuntu Science (http://help.ubuntu.com/community/OtherSoftware) . 

###Amateur Electronics

####Arduino

[Arduino](http://www.arduino.cc/) is an open - source electronics prototyping platform based on flexible, easy - to -use hardware and software. It's intended for artists, designer ,and bobbyists interested in creating interactive objects or environments.See [this tutotial](http://www.codetorment.com/2009/11/02/tutorial-getting-started-with-arduino-ide-on-linux-ubuntu-9-10/)
