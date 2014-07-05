
####Joomla (Web content publishing)

[Joomla](http://www.joomla.org/) သည္ website မ်ား ျပဳလုပ္ရာတြင္ ရိုးရွင္းသည့္ ပံုစံမ်ားမွ ရႈပ္ေထြးေသာ ပူးေပါင္းေဆာင္ရြက္မ်ားအထိ အသံုးျပဳႏိုင္ေသာ စြမ္းအားျမင့္ open source tool ျဖစ္သည္။ စတင္အသံုးျပဳရန္ [info for beginners](http://docs.joomla.org/Beginners) ကို ၾကည့္ရႈသင့္သည္။

####Scribus (Desktop publishing)

[Scribus](http://www.scribus.net/) သည္ desktop publishing အတြက္ professional တစ္ခုအျဖစ္ အသံုးျပဳႏိုင္ေသာ open-source package တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install scribus

#### Plone (Content Management System)

[Plone](https://plone.org/) သည္ ကမ ၻာအႏွံ႔ရွိ လုပ္ငန္းႀကီးမ်ားတြင္ အသံုးျပဳေနသည့္ content management system ျဖစ္ၿပီး platform မ်ဳိးစံုတြင္ အခမဲ့ အသံုးျပဳႏို္င္ေသာ open source (GPL - licensed ) system ျဖစ္သည္။ Installer ကို [ဒီေနရာ](http://plone.org/products/plone) တြင္ ရယူႏိုင္သည္။ Python ကို ေျပာင္းလဲထားေသာေၾကာင့္ အခ်ဳိ႕အသံုးျပဳသူမ်ားအေနျဖင့္ Jaunty တြင္ အခက္အခဲေတြ႔ႏိုင္ပါသည္။

####Gallery (Photo album website)

[Gallery](http://gallery.menalto.com/) သည္ PHP ကို အေျချပဳထားၿပီး ဓာတ္ပံု အယ္လ္ဘမ္မ်ားအား website တြင္ ျပသႏိုင္ေအာင္ ျပဳလုပ္ေပးသည့္ tool တစ္ခုျဖစ္သည္။ Drupal အတြက္ Gallery 2 Drupal interface အား ရရွိႏိုင္ပါသည္။ Install ျပဳလုပ္ရန္

[php BB (Forums) php BB](http://www.php BB.com/) သည္ Forum မ်ားတည္ေဆာက္ရန္ အသံုးျပဳသည့္ အခမဲ့ open source platform တစ္ခုျဖစ္သည္။ LAMP server (သို႔မဟုတ္) PostgreSQL database အား install ျပဳလုပ္ထားရန္ လိုအပ္သည္။ Install ျပဳလုပ္ရန္အတြက္ universe repositories အား enable ျပဳလုပ္ထားရန္ အထူးလိုအပ္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get install phpbb3

###Distance teaching

####Moodle

Moodle သည္ အြန္လိုင္း သင္ၾကားေရး cource မ်ား hosting ျပဳလုပ္ႏုိင္ရန္အတြက္ အခမဲ့ open source platform တစ္ခုျဖစ္သည္။ Webinar software ျဖင့္လည္း တြဲဖက္အသံုးျပဳႏိုင္သည္။ LAMP server အား Install ျပဳလုပ္ထားရန္ (sudo tasksel install lamp-server) လိုအပ္သည္။ Moodle ၏ အခမဲ့ theme မ်ားအား ဤေနရာတြင္ ရယူႏုိင္သည္။ Install ျပဳလုပ္ရန္

	sudo apt-get moode

Moodle အတြက္ Database server software (mysql-server-) ထည့္သြင္းလိုပါက ေဖာ္ျပပါ လမ္းညႊန္ခ်က္မ်ားအား လုပ္ေဆာင္ပါ။ Moodle အား ထည့္သြင္းထားသည့္ computer ေပၚတြင္ database အား တည္ေဆာက္၍ localhost option အား acept လုပ္ပါ။ လိုအပ္ပါက Moodle configuration အား တည္းျဖတ္ပါ။

	sudo gedit/etc/moodle/config.php

လုိအပ္ပါက `Moodle apache 2 configuration file` အား တည္းျဖတ္ပါ။

sudo gedit/etc/moodle/apache.conf

Browser မွတဆင့္ install ျပဳလုပ္ျခင္းအား အဆံုးသတ္ပါ။ (unattended install ျပဳလုပ္ျခင္းမွာ ပိုသင့္ေတာ္ပါသည္။)

`http://localhost/moodle/admin` 

စံုလင္စြာေလ့လာရန္အတြက္ အေသးစိတ္အခ်က္အလက္မ်ားတြင္ ၾကည့္ရႈပါ။

####Claroline

[Claroline](http://www.claroline.net/) သည္ e-learning course မ်ား hosting ျပဳလုပ္ရန္ႏွင့္ ေက်ာင္းသား/ေက်ာင္းသူမ်ား အြန္လိုင္းတြင္ ပူးေပါင္းလုပ္ေဆာင္ႏုိင္ရန္အတြက္ ျပဳလုပ္ထားသည့္ အခမဲ့ open-source platform တစ္ခုျဖစ္သည္။ Install ျပဳလုပ္ရန္အတြက္ LAMP server အား install ျပဳလုပ္ထားရန္လိုအပ္သည္။ installation အတြက္ source file အား ၎ website တြင္ရယူႏိုင္ၿပီး လမ္းညႊန္ခ်က္မ်ားအား [ဤေနရာတြင္](http://www.claroline.net/documentation/tutorials.html) ေတြ႔ႏုိင္သည္။

####Dokeos

[Dokeos](http://www.dokeos.com/) သည္ အခမဲ့ သင္ၾကားေရး platform တစ္ခုျဖစ္ၿပီး ေဆးပညာဆိုင္ရာ ပံုမ်ား၊ case presentation မ်ားပါ ပါ၀င္သည္။ ဥေရာပတြင္ က်ယ္က်ယ္ျပန္႔ျပန္႔ အသံုးျပဳေနၾကပါသည္။

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
