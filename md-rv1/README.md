##General Notes

Ubuntu လမ်းညွှန်သည် ပုဂ္ဂလိကဆိုင်ရာကုမ္ပ္ပဏီနှင့်သော်လည်းကောင်း အခြားစီးပွားရေး လုပ်ငန်းကြီးများနှင့်သော်လည်းကောင်း စီးပွားရေးအရသက်ဆိုင်မှုမရှိပါ။
Ubuntu သည် သုံးစွဲသူများကို Menu ရုပ်ပုံအသုံးချ Graphical User Interface  (GUI) နှင့်သော်လည်းကောင်း စာသားအသုံးချ command line ဆိုင်ရာ text-based command-line interface (CLI) သော်လည်းကောင်း အလုပ်များကို လုပ်ဆောင်နိုင်စေပါတယ်။ Ubuntu တွင်(command-line-interface)ကို `Terminal` လို့ခေါ်ပါတယ်။ Terminal ကိုစဖွင့်မယ်ဆိုရင် `Menu- Applications-Accessories -Terminal` စသည်ဖြင့် အဆင့်တိုင်းသွားရောက်နိုင်ပါသည်။ Terminal တွင် ခဲရောင်မျဉ်းအစက်များအတွင်း စာသားများကို ထည့်သွင်းအသုံးပြုနိုင်ပါသည်။

ကွန်ပျူတာလုပ်ဆောင်မှုစနစ်မှ ပြောင်းလဲချက်များကို ပြောင်းလဲခွင့်ရှိသူ (Admin အခွင့်ရှိတဲ့) အသုံးပြုသူကပဲဆောင်ရွက်နိုင်ပါသည်။ `sudo` Command က အသုံးပြုသူကို ပြောင်းလဲခွင့်ရှိသူ Admin အဖြစ် ယာယီသတ်မှတ်ပေးသည်(ဥပမာ - ပရိုဂရမ်တစ်ခု သွင်းစဉ် (သို့) စနစ်ပိုင်းဆိုင်ရာပြောင်းလဲစဉ်)။ နမူနာအနေဖြင့် အောက်တွင်ဖော်ပြထားသည်။

	sudo bash

`gksudo` ကို Graphical Application တွေဖွင့်ရာမှာ `sudo` အစား Run Command မှသော်လည်းကောင်း မီနူးများမှသော်လည်းကောင်း အသုံးပြုနိုင်ပါတယ်။နမူနာ အနေဖြင့် အောက်တွင်ဖော်ပြထားသည်။

	gksudo gedit /etc/apt/sources.list

ဖိုင်အများစုရဲ့ ခန့်ခွဲမှုတွေကို ရင်းမြစ်ပြင်ဆင်ခွင့်ရှိတဲ့ Admin  အခွင့် (root Administrative privileges)နှင့် Nautilus file မန်နေဂျာကဲ့သို့ အသုံးပြုကာနဲ့ ဆောင်ရွက်နိုင်ပါသည်။ Munu မှတဆင့် အသုံးပြုမယ်ဆိုရင် `gksudo` ကိုအသုံးပြုပါ။

	gksudo nautilus (သို့မဟုတ်) sudo nautilus

`man` ကတော့ ကွန်မန်းတွေအတွက် အကူအညီလိုလာပြီဆိုရင် အသုံးပြုနိုင်ပါတယ်။နမူနာအနေနဲ့ `man sudo` လို့ရိုက်ထည့်လိုက်မယ်ဆိုရင် `sudo` ကွန်မန်းနဲ့ဆိုင်တဲ့
လက်စွဲဖိုင်စာမျက်နှာတွေကိုမြင်တွေ့ရမှာဖြစ်ပါသည်။ 

	man sudo

`apt-get`  နှင့် `aptitude` တွေကို ပရိုဂရမ်တွေ ပက်ကေ့ (package) တွေ ထည့်သွင်းရာမှာအမြန်ဆုံးနည်းအနေနဲ့ အသုံးပြုပါတယ်။ GUI ထည့်သွင်းမှုအတွက် Synaptic Package Manager ကိုလဲအသုံးပြုနိုင်ပါတယ်။ ဒါပေမယ့် ပရိုဂရမ်တွေ ပက်ကေ့ (package) အများစုဟာ `apt-get install` နှင့်ရော Synaptic Package Manager နှင့်ပါ ထည့်သွင်းနိုင်ပါသည်။အခုလမ်းညွှန်မှာ မြင်တွေ့နိုင်ပါသည်။

	sudo apt-get install package 

Synaptic မှာပက်ကေ့တွေ (package) ကိုရှာဖွေပုံနဲ့ ထည့်သွင်းပုံက ဤသို့ဖြစ်ပါသည်။ အမိန့်ပေးမှုအများအပြားကို nano စာသား အယ်ဒီတာ အသုံးပြုခိုင်းစေပါတယ်။ နာနိုက
Linux တိုင်းမှာ ရရှိတဲ့ အယ်ဒီတာဖြစ်ပါသည်။ တစ်ခါတရံမှာ Ubuntu မှာပါတဲ့ gedit ထက်အသုံးပြုရတာပိုလွယ်ပါတယ်။

Menu ဆိုတာကတော့ desktop အပေါ်ဘက်မှာရှိ မီနူးဘားကို ရည်ညွှန်းပါတယ်။ မိုက်ခရိုဆော့ဖ်ဝင်းဒိုးမှာရှိတဲ့ Start menu၊ Apple Macintosh မှာရှိတဲ့ Menu bar တွေနဲ့တူတူပါပဲ။

တကယ်လို့ ၆၄ ဘစ် ဗားရှင်းစနစ်ကို အသုံးပြုမယ်ဆိုရင် i386 ကို amd64 နဲ့ အစားထိုးရမှာ ဖြစ်ပါသည်။

###Other Versions

လက်ရှိအသုံးပြုနေတဲ့ Ubuntu version ကိုကြည့်ချင်ရင် Terminal ပေါ်မှာ အောက်ပါအတိုင်းရိုက်ထည့်ပြီး Enter နှိပ်ပါ။

	lsb_release -a

လက်ရှိအသုံးပြုနေတဲ့ kernel ကိုကြည့်ချင်ရင်ရင်တော့ Terminal မှာ အောက်ပါအတိုင်းရိုက်ထည့်ပြီး Enter နှိပ်ပါ။

	uname -a

###Newer Versions  of Ubuntu 

Ubuntu ကို ၆လလျှင်တစ်ကြိမ်ထုတ်ဝေပြီး နှစ်စဉ် ဧပြီလနှင့်အောက်တိုဘာလတို့တွင် ထုတ်ဝေပါသည်။ Oneiric Ocelot (11.10) (http://ubuntuguide.org/wiki/Ubuntu:Oneiric), များမကြာမီ နောက်ဆုံးထွက်ပေါ်မည့် Oneiric ကို ၂၀၁၁ခုနှစ် အောက်တိုဘာလတွင် အခမဲ့ ရယူနိုင်မည်ဖြစ်ပါသည်။သို့ရာတွင် ၎င်းသည် ကာလရှည်ကြာ ထောက်ပံ့မှုပေးသည့် LTS Version မဟုတ်ပါ။

###Older Versions of Ubuntu

###Other Resources 

Ubuntu Forums (http://ubuntuforums.org/) တွင် အွန်လိုင်းဖြေရှင်းချက်များနှင့် အခြားသောအသေးစိတ်အချက်အလက်များကို ကူညီပေးရန် အဖွဲ့အစည်းများစွာ ရှိပါသည်။
ပြည်တွင်း အဖွဲ့အစည်းအနေဖြင့် Ubuntu for Myanmar (ubuntu-mm) (http://ubuntu-mm.net/) ရှိပြီး မြန်မာဘာသာဖြင့် Ubuntu အကြောင်းလေ့လာနိုင်ပါမည်။

- [ubuntu-mm.net](http://ubuntu-mm.net)
- [ask.ubuntu.com](http://ask.ubuntu.com)
- [FB Ubuntu-MM Group](http://fb.com/groups/ubuntu4mm)
- [FB Pages](http://fb.com/ubuntumm)
- [Ubuntu Myanmar LoCo Team](http://wiki.ubuntu.com/MyanmarTeam)
- [Ubuntu-MM LoCo](http://loco.ubuntu.com/teams/ubuntu-mm)

-------------------

##Ubuntu Resources 

###Unity Desktop

[Unity](http://en.wikipedia.org/wiki/Unity_%28desktop_environment%29) ဆိုသည်မှာ Ubuntu တွင် အသုံးပြုသည့် နဂိုမူလပါသော Desktop ပုံစံဖြစ်ပါသည်။ (Gnome) ဂနုမ်းမှ အသုံးပြုသည့် GTK ပလက်ဖောင်းဖြင့် အဆင်ပြေသင့်တော်ပါသည်။ netbook များတွင် အသုံးပြုရန် ဒီဇိုင်းပြုလုပ်ထားသော်လည်း အခြားသော စက်ပစ္စည်းအမျိုးအစားများတွင်ပါ အသုံးဝင်စေရန် canonical မှ ပြင်ဆင်ပေးထားပါသည်။

###Gnome Project 

[Gnome 3](http://www.gnome.org/) သည် Ubuntu အတွက် ပုံစံအသစ်အနေဖြင့် ရယူနိုင်ပါသည်။ Gnome လုပ်ငန်းစဉ်များ (http://projects.gnome.org/) ကြည့်ရှု ရယူနိုင်ပါသည်။

###Installation ပြုလုပ်ပုံ  - ၁ [(link)](https://launchpad.net/~gnome3-team/+archive/gnome3) 

	sudo add-apt-repository ppa:gnome3-team/gnome3   
	sudo apt-get update   
	sudo apt-get dist-upgrade   
	sudo apt-get install gnome-shell   

###installation ပြုလုပ်ပုံ  - ၂ [(link)](https://launchpad.net/~ubuntugnometeam)

	sudo add-apt-repository ppa:ubuntugonmeteam/gnome3   
	sudo add-apt-repository ppa:ubuntugonmeteam/ppa-gen   
	sudo apt-get update   
	sudo apt-get install ugr-desktop-g3   
	sudo apt-get dist-upgrade   

###Ubuntu Screenshots 

- [What is Ubuntu?](http://www.ubuntu.com/ubuntu)    
- [Ubuntu 11.04 Unity Desktop](http://www.youtube.com/watch/v=HMztaKt_1_E)    
- [Other YouTube videos](https://www.youtube.com/results?search_query=ubuntu+11.04)   
မကြာမီ မြန်မာဘာသာ သင်ကြားပို့ချချက်များ ထည့်သွင်းမည်။

###News Application Resources 

[GetDeb](http://www.getdeb.net) နောက်ဆုံးထွက်ရှိသော software များကိုတရားဝင် ထိန်းသိမ်းထားရာ နေရာများကဲ့သို့ ရရှိနိုင်ခြင်း (သို့) မရရှိနိုင်ခြင်း အတူတူဖြစ်သည်။ `.deb` ဖိုင်ပုံစံဖြင့်ထည့်သွင်းရန် လွယ်ကူပါသည်။ (ဤနေရာတွင် ဆက်လက်လေ့လာပါ။ Apt and Package Basics).
   
- [Top 100 Open source Applications](http://ubuntulinuxhelp.com/top-100-of-the-best-useful-opensource-applications/)
- [Linux Alternatives](http://www.linuxalt.com/)   
See our full list of add-on applications.

###Other *buntu guides and help manuals

- [Kubuntu](http://www.kubuntuguide.info) သည် နာမည်ကျော်ကြားသော KDE desktop ကို အသုံးပြုထားပါသည်။
- [Xubuntu](http://www.xubuntuguide.org) can run with as little as 256 Mb RAM.It is better for older machines with limited resources.---
- [Lubuntu](https://wiki.ubuntu.com/Lubuntu) သည် RAM 256Mb နှင့်ပင် အသုံးပြုနိုင်ပါသည်။ အိုဟောင်းနေသော စက်များနှင့်ပင် သင့်တော်ပါသည်။
- [Offical Ubuntu Server Guide](https://help.ubuntu.com/10.04/serverguide/C/index.html) Ubuntu server လမ်းညွှန် - server packages များအတွက် ကောင်းမွန်သော ကိုးကားမှုဖြစ်ပါသည်။
- [Ubuntu Doctors Guide](http://www.ubuntudoctorsguild.org/) ကျန်းမာရေးနှင့်သက်ဆိုင်သော နေရာများတွင်သုံးသော (K)ubuntu Linux များအတွက်
စုစည်းထားသော လမ်းညွှန်ချက်များ
- [SkoleLinux](http://www.slx.no/en/take-a-tour) -- Debian/Ubuntu Linux (open-source) များအတွက် ပညာရပ်ဆိုင်ရာများ စုစည်းထားမှု

--------------------- 

##Installing Ubuntu

###Ubuntu ထည့်သွင်းအသုံးပြုနိုင်ရန် Hardware လိုအပ်ချက်များ

Ubuntu Natty Narwhal သည် 384 Mb ပမာဏသည် RAM ရှိရုံမျှဖြင့် ကောင်းစွာလည်ပတ်နိုင်သည်။ (GUI installer ဖြင့်ထည့်သွင်းလျှင် အနည်းဆုံး 256 Mb ပမာဏလိုအပ်ပြီး၊စာသားဖြင့်သာဖော်ပြသော installer ကို သုံးလျှင် 192 Mb ပမာဏသာလိုအပ်သည်)။ Notebooks များတွင် Ubuntu Natty Narwhal ကိုကောင်းစွာ အသုံးပြုနိုင်သည်။

Ubuntu ထည့်သွင်းခြင်းသည် Harddisk နေရာလွတ် 3-4 Gb မျှသာ အသုံးပြုပြီး အဆင်ပြေစွာ အသုံးပြုနိုင်ရန် 8-10Gb သာ လိုအပ်သည်။ အကယ်၍ သင့်ကွန်ပျူတာ၏ memory ပမာဏသည် ယခုဖော်ပြခဲ့သည်ထက် နည်းပါးနေပါက အခြားသော
ဆင်တူ OS များဖြစ်သော အောက်ပါ OS များကို အသုံးပြုနိုင်သည်။    

- [Lubuntu](https://wiki.ubuntu.com/Lubuntu) (၁၆၀ Mb RAM ပမာဏရှိရုံဖြင့် အသုံးပြုနိုင်သည်။)   
- [PuppyLinux](http://www.puppylinux.org/) (၂၅၆ Mb RAM ပမာဏရှိရုံဖြင့် အသုံးပြုနိုင်သည်။)   
(သို့မဟုတ်) 
- DSL
(http://damnsmallinux.org) (အနည်းဆုံး RAM ပမာဏ၊Harddisk နေရာလွတ် အနည်းငယ်သာရှိရုံ၊ USB drive မှ အသုံးပြုရန်၊ သို့မဟုတ် အခြား Operation System များ အတွင်းမှ softwareတစ်ခုကဲ့သို့အသုံးပြုရန်)။

###Fresh Installation

####Ubuntu တစ်ခုတည်း သီးသန့်ထည့်သွင်းခြင်း

[ဒီနေရာမှ](http://www.ubuntu.com/download/ubuntu/download) မှ Ubuntu ၏
နောက်ဆုံးထွက်ရှိထားသော IOS အား download ဆွဲယူပါ။ ထို IOS အား CD ပေါ်သို့ Ubuntu installation CD (LiveCD) အဖြစ် အသုံးပြုနိုင်ရန် မည်သို့ပြုလုပ်ရမည်ကို
[How To](https://help.ubuntu.com/community/BurningIsoHowto) တွင် လမ်းညွှန်ထားသည်။ ထိုလမ်းညွှန်ချက်အတိုင်း ပြုလုပ်ထားသည့် Live CD ကို Ubuntu ထည့်သွင်းရန်အတွက် အသုံးပြုသည်။

အခြားနည်းလမ်းတစ်ခုအနေဖြင့် Server version ကို အရင်ထည့်သွင်းပြီးမှ Ubuntu desktop version ကို ထည့်သွင်း၍ အသုံးပြုနိုင်သည်။

Server version ကဲ့သို့ ပိုမိုမြန်ဆန်သည့် စာသားဖြင့်သာဖော်ပြသော installer ကို အသုံးပြုထားသည့် ISO file ကို [Alternative Download](http://www.ubuntu.com/download/ubuntu/alternative-download) တွင် ရယူနိုင်သည်။ ထို ISO တွင်Desktop CD(Regular Download) ထက်ရွေးချယ်နိုင်သော installation လုပ်ငန်းစဉ်များ ပိုမိုပါဝင်သည်။

LiveCD ကို USB flashdrive ပေါ်သို့ (usb-creater-gtk) အသုံးပြု၍ ထည့်သွင်းပြီး ထို flashdrive ကို CD drive မပါဝင်သည့် ကွန်ပျူတာများပေါ်တွင် Ubuntu ထည့်သွင်းရန် အသုံးပြုနိုင်သည်။ [ဒီနေရာတွင်ကြည့်ပါ။](https://help.ubuntu.com/community/Installation/FromUSBStick)

####Windows နှင့် Ubuntu ကို ကွန်ပျူတာတစ်လုံးထဲပေါ်တွင် ယှဉ်တွဲတင်ခြင်း

ကွန်ပျူတာတစ်လုံးထဲပေါ်တွင် Windows နှင့် Ubuntu ယှဉ်တွဲတင်ရာတွင် အခက်အခဲများ ကြုံတွေ့ရနိုင်ပါသည်။ Windows ၏ bootloader သည် Windows သီးသန့်ကိုသာ ထောက်ပံ့သည့်အတွက် ကွန်ပျူတာပေါ်တွင် Windows ကို ဦးစွာထည့်သွင်းရပါမည်။ ပုံမှန် Windows ထည့်သွင်းသည့်လုပ်ငန်းစဉ်တွင် Hard drive ၏
နေရာရှိသမျှကို အသုံးပြုသည့်အတွက် Ubuntu ထည့်သွင်းရန် နေရာလွတ်ရရှိရန်ဆိုပါက Windows မှအသုံးပြုထားသည့် Hard drive ကိုချုံ့ပေးရန် လိုအပ်ပါသည်။(Hard drive ပမာဏကိုမပြောင်းလဲခင် ဦးစွာမလိုအပ်သော ဖိုင်များကို ရှင်းလင်း၍ ဖိုင်ပြန်စီသော လုပ်ငန်းစဉ်ကို လုပ်ဆောင်ထားပါ။)

Windows ၏ Hard drive partition ကိုချုံ့ပြီးပါက  Ubuntu ကို ထည့်သွင်းရန်သို့မဟုတ် Hard disk 
partition များကို ထပ်မံပြုပြင်ပြောင်းလဲနိုင်ရန်အတွက် ကွန်ပျူတာကို reboot ပြန်လုပ်ပေးရပါမည်။
ဤသို့ပြုလုပ်ခြင်းအားဖြင့် Windows စနစ်မှ အသစ်ပြုပြင်လုပ်ဆောင်ထားသော    Hard drive ကို သိရှိစေပြီး (Windows XP တွင် `chkdsk` ကိုအသုံးပြုပြီး နောက်ပိုင်းထွက်ရှိလာသော Windows စနစ်များတွင် အခြားသော Hard drive ကိုစစ်ဆေးသည့် utilities များကို အသုံးပြုသည်။)ထို့အပြင် bootup ဖိုင်များကို ပြောင်းလဲရေးသားစေသည်။ (ထိုကဲ့သို့ reboot မပြုလုပ်ခဲ့ပါက Windows အသုံးပြုသော Hard drive partition ၏ bootup ဖိုင်များကို Windows Recovery Console အသုံးပြု၍ ကိုယ်တိုင် ပြင်ဆင်ပေးရမည်ဖြစ်သည်။

Windows စနစ်ထည့်သွင်းခြင်းနည်းသစ်များတွင် Hard drive primary partition ၂ခုအသုံးပြုသည်
(Windows စနစ်စတင်ရန partition  အသေး၁ခုနှင့် Windows စနစ်တစ်ခုလုံးအတွက် partition အကြီးတစ်ခု)။ Ubuntu Linux စနစ်ထည့်သွင်းရာတွင်လည်း Hard drive partition ၂ခုလိုအပ်ပါသည် (`linux-swap` partitionနှင့် စနစ်တစ်ခုလုံးအတွက် partition)။ Linux အတွက် Hard drive partition များခွဲရာတွင် primary partition သို့မဟုတ် primary partition ပေါ်မှ ပြန်ခွဲဝေထားသော logical partition  ၂ခု အသုံးပြုရမည်။အချို့ကွန်ပျူတာရောင်းချသူများသည် Hard drive ၏ primary partition ၄ခုလုံးကို အသုံးပြုထားတတ်သည့်အတွက် Ubuntu  ထည့်သွင်းရန်အတွက် partition နေရာလွတ်မရှိကြောင်း ဖော်ပြနေတတ်သည်။ Hard drive ၏ primary partition ၁ခုရှိလျှင် ထို primary partition  ပေါ်တွင် logical partition များထပ်မံခွဲ၍ Ubuntu  ကိုထည့်သွင်းနိုင်သည်။(Ubuntu အတွက် primary  partition ဖြစ်စေ logical partition ဖြစ်စေ အသုံးပြုနိုင်သည်။)

အကယ်၍ Hard drive ပေါ်တွင် primary partition ၂ခုသာရှိပါက(ထို၂ခုတွင် နေရာလွတ်များစွာရှိနေလျှင်) Ubuntu ကို ဒုတိယ operation system အဖြစ်ထည့်သွင်းရာတွင် အခက်အခဲရှိမည်မဟုတ်ပါ။ Ubuntu LiveCD ကို `largest available free space` တွင် ထည့်သွင်းရန်ခွင့်ပြုလိုက်ရုံဖြင့် အလိုအလျှောက် ပြုလုပ်သွားနိုင်သည်။ အခြား Partition ၁ခုတွင် နေရာလွတ် အများအပြားရှိနေပါက Ubuntu LiveCD သည် Ubuntu ကို `largest available free space` တွင် ထည့်သွင်းပေးလိမ့်မည်ဖြစ်သည်။

မူလ Windows စနစ်၏ partition သည် အနည်းဆုံး 20GB  (Vista နှင့် Windows 7 ဆိုလျှင် 30GB)
ရှိရမည်ဖြစ်ပြီး Ubuntu အတွက် partition သည် အနည်းဆုံး 10G (20GB ပေးနိုင်ရင်ပိုကောင်းပါသည်။) ရှိရမည်ဖြစ်သည်။သင့်တွင် Hard drive  နေရာလွတ်များစွာရှိနေလျှင် သင်ကြိုက်သည့် operation system ကို နေရာကြိုက်သလောက် ပိုပေးနိုင်ပါသည်။

အပြန်အလှန်အားဖြင့် သင့်ကွန်ပျူတာတွင် Ubuntu ကို အရင်ထည့်သွင်းပြီးမှ GParted ဖြင့် primary `NTFS` partition တစ်ခု ဖန်တီး၍ Windows စနစ်ကို ထည့်သွင်းနိုင်ပါသည်။ (GParted ကို LiveCD/USB တစ်ခုမှနေ၍ အသုံးပြု၇ပါမည်။) ထို primary NTFS partition ကိုဖန်တီးပြီးပါက သင်၏ Windows CD/DVD မှ boot လုပ်၍ Windows စနစ်ကိုထို NTFS partition တွင်ထည့်သွင်းရန် ရွေးချယ်ရမည်။ထည့်သွင်းခြင်း လုပ်ငန်းစဉ် ပြီးဆုံးပါက ကွန်ပျူတာပုံမှန် အလုပ်လုပ်ဆောင်နိုင်စေရန် reboot ပြန်လုပ်ပါ။ထိုလုပ်ငန်းစဉ်အားလုံး ပြီးဆုံးသွားလျှင် Ubuntu LiveCD/USB ကိုသုံး၍ `GRUB` ကို `MBR` တွင်ပြန်လည်ထည့်သွင်းပါ။ (အဘယ်ကြောင့်ဆိုသော် Windows သည် `MBR` ကိုပြုပြင်၍ သူ၏ကိုယ်ပိုင် bootloader ကို master bootloader အဖြစ်ပြောင်းလဲသွား၍ဖြစ်ပါသည်။) `GRUB` ကိုထည့်သွင်းပြီးပါက သင်နှစ်သက်ရာ OS ဖြင့် boot
လုပ်နိုင်မည်ဖြစ်သည်။

###အခြားသော Windows နှင့် Ubuntu ယှဉ်တွဲ ထည့်သွင်းခြင်း နည်းလမ်းများ

[Wubi](http://www.ubuntu.com/getubuntu/download-wubi) (Windows-based Ubuntu
Installer), Ubuntu ကို Windows စနစ်ပေါ်တွင်  Hard drive အတုတစ်ခုဖန်တီး၍ အသုံးပြုနိုင်ရန်
လုပ်ဆောင်ပေးသော dual-boot installer ၁ခုဖြစ်သည် (သို့သော်Ubuntu ၏စွမ်းဆောင်ရည်
ကျဆင်းနိုင်ပါသည်။ Windows စနစ်ပေါ်တွင် အသုံးပြုရသည့်အတွက် ဤနည်းလမ်းကို Ubuntu ကို
ယာယီ အသုံးပြုရန်အတွက်သာ သုံးရန်သင့်တော်ပါသည်။ Ubuntu ကိုအမြဲတမ်း အသုံးပြုမည်ဆိုပါက
သီးသန့် partition, သီးသန်ု့ filesystem ပေါ်တွင် ထည့်သွင်းခြင်းသာ အကောင်းဆုံးနည်းလမ်း
ဖြစ်ပါသည်။

[Easy BCD](http://neosmart.net/dl.php?id=1), Windows စနစ်ပေါ်တွင် အသုံးပြုရသည့် အခမဲ့
Program တစ်ခုဖြစ်သည်။ Windows 7/Vista ၏ bootloader ကို ပြုပြင်ပြောင်းလဲခြင်းဖြင့် Windows 
7/Vista နှင့် Ubuntu (တခြား operation systems များအတွက်လည်း အသုံးပြုနိုင်သည်။) ကွန်ပျူတာ ၁ လုံးတည်းပေါ်တွင် အသုံးပြုနိုင်စေသည်။

###Installing multiple OS on a single computer

ကွန်ပျူတာတစ်လုံးတည်းပေါ်တွင် Operation System များ ၁ခုထက်ပို၍ အသုံးပြုခြင်း

>**သတိပြုရန်** Ubuntu ထည့်သွင်းသောလုပ်ငန်းစဉ်အတွင်း ရွေးချယ်စရာအဆင့်တစ်ခုရှိပါသည် (Ready to install > Advanced)။ ၎င်းမှာ GRUBF2 bootloader ကို MBR (Master Boot Record) အားပြောင်းလဲခြင်းမပြုလုပ်ပဲ (K)Ubuntu OS ထည့်သွင်းထားသော Harddisk Partition အတွင်း ထည့်သွင်းရန် ရွေးချယ်ခြင်းဖြစ်သည်။ ထိုအဆင့်ကိုလုပ်ဆောင်ရာတွင် အထူးသတိပြုရန်လိုအပ်သောအချက်မှာ သင်၏ကွန်ပျူတာစနစ်တွင် boot လုပ်ရန်အတွက် သီးခြား Harddisk Partition တစ်ခု(သို့) Operation System ၂ ခုထပ်ပို၍ အသုံးပြုထားခြင်း (သို့) chainloads bootloaders များ အသုံးပြုထားခြင်းရှိမရှိပင် ဖြစ်သည်။ ထိုသို့သောစနစ်များတွင် MBR ကိုပြုပြင်ပြောင်းလဲခြင်းမလုပ်သည်မှာ အကောင်းဆုံးပင်ဖြစ်သည်။
﻿**ဥပမာ** Destop version GUI installer ကိုအသုံးပြု၍ installation ပြုလုပ်နေစဉ်အတွင်း အဆင့်တစ်ခုတွင် အောက်ပါအတိုင်းပေါ်လာမည်ဖြစ်သည်။

	Summary > Advanced > Device for boot loader installation: /dev/sda6

အထက်ပါ ဥပမာတွင် ထိုအခြေအနေအတိုင်း ထားရှိပါက GRUB2 bootloader သည် `/dev/sda6` ((K)Ubuntu OS ထည့်သွင်းထားသည့် Harddisk Partition ) အတွင်းသို့သာ ရောက်ရှိသွားမည်ဖြစ်ပြီး MBR (Master Boot Record) ကိုပြောင်းလဲမည်မဟုတ်ပါ။သို့သော် `/dev/sda` ၏ default setting တွင်ထားရှိလိုက်ပါက GRUB2
သည် `/dev/sda6` ((K)Ubuntu OS ထည့်သွင်းထားသည့် Harddisk Partition ) အတွင်းသို့
ရောက်ရှိသွားမည် ဖြစ်သည့်အပြင် MBR  (Master Boot Record) ကိုလည်း ပြုပြင်ပြောင်းလဲသွားပါမည်။ ထိုအခါ GRUB2 သည် ကွန်ပျူတာပေါ်တွင် ထည့်သွင်းထားသည့် Operation System  အားလုံး၏ master bootloader အဖြစ်ပြောင်းလဲသွားမည်ဖြစ်သည်။အခြားသော bootloader (GRUB2 မဟုတ်သည့်) များကို အသုံးပြုနေသူဖြစ်လျှင် ထိုအခြေအနေသည် အဆင်ပြေမည်မဟုတ်ပါ။

###Start Manager ကို အသုံးပြု၍ Grub ၏ setting များကို ပြောင်းလဲခြင်း

Grub သည် (Operation System ၁ခုထပ်ပို၍ ထည့်သွင်းထားသော ကွန်ပျူတာများတွင်) မည်သည့် OS ကို ပုံမှန် ဦးစားပေးအနေဖြင့် စတင်လည်ပတ်စေမည်ကို သတ်မှတ်ခြင်းနှင့် အခြားသော bootup setting များကို ထိန်းချုပ်သည့် bootup utility ၁ခုဖြစ်သည်။ [Startup Manager](http://sourceforge.net/projects/startup-manager/) ကို အသုံးပြု၍ Grub ၏ setting  များကို ပြောင်းလဲနိုင်သည်။ Startup Manager သည် Grub (Grub Legacy ), Grub 2, Usplash, and Splashy စသည့် bootloader များ၏ setting များကို ကွပ်ကဲရာတွင် အသုံးပြုသည့် software ဖြစ်သည်။ Startup Manager အသုံးပြုပုံကို [ဒီနေရာ](https://help.ubuntu.com/community/StartUpManager) တွင်ကြည့်ရှုနိုင်သည်။ Startup Manager ထည့်သွင်းရန်အတွက်

	sudo apt-get install startupmanager menu

Startup Manager လည်ပတ်စေရန်

	Menu > System > Administration > Startup Manasger

>**မှတ်ချက်** Grub setting များကို command-line interface မှလည်း ပြောင်းလဲပြင်ဆင်နိုင်သည်။

###Mac OS X နှင့် Ubuntu ကို ကွန်ပျူတာတစ်လုံးတည်းပေါ်တွင် ယှဉ်တွဲတင်ခြင်း

Mac OS X သည် Linux နှင့် တည်ဆောက်ပုံ ဆင်တူသည် (Max OS X သည် BSD Unix ကို
အခြေခံထားခြင်းဖြစ်သည်။) Mac OS X နှင့် Ubuntu ကို ယှဉ်တွဲတင်ခြင်းနှင့် ပတ်သတ်သော
အသေးစိတ်လမ်းညွှန်ချက်များကို [ဒီနေရာတွင်](http://help.ubuntu.com/community/MacBook) တွင်လေ့လာနိုင်သည်။

####Ubuntu ရှိပြီးသား ကွန်ပျူတာပေါ်တွင် Mac OS X တင်ခြင်း

Ubuntu ကို Mac OS X နှင့် ယှဉ်တွဲတင်မည်ဆိုပါက Ubuntu ကို ထည့်သွင်းမည့် Harddisk Partition ကို ext2 ကို ရွေးချယ်ပါ။ (ထိုလုပ်ငန်းစဉ်အတွက် Super Grub Disk CD သည် အသုံးဝင်သော utility ဖြစ်သည်။) Super Grub ISO ဖိုင်ကို [ဒီနေရာတွင်](http://supergrub.forjamari.linex.org) တွင် download ရယူနိုင်သည်။

Ubuntu ကို ထည့်သွင်းပြီးပါက Grub start-up list ကို ပြင်ဆင်ပြောင်းလဲပါ။

	sudo nano /boot/ grub/menu.1st

ထို့နောက် အောက်ပါစာကြောင်းများကို ထပ်ပေါင်းထည့်ပါ။

	title Mac OS X root (hd0,0) makeactive chainloader + 1

ပြီးလျှင် Mac ကို reboot လုပ်၍ Mac OS X  တွင်ပါဝင်သော Terminal ကို သွားပါ။ (boot လုပ်ရာတွင်
အခက်အခဲရှိပါက Mac OS X DVD ကိုအသုံးပြု၍ boot လုပ်ပါ။) F8 ကိုနှိပ်၍ -s ဟု ရိုက်ထည့်ပါ။ ထို့နောက် ရိုက်ထည့်ရမည့်စာကြောင်းများမှာ `fdiskn -e /dev/rdisk0 flag 2` (flag 2သည် ယခုဥပမာ၏ Harddisk Partition number 2 ဖြစ်သည်။ သင်၏ Mac တွင် အသုံးပြုထားသည့် Partition number ပေါ်တွင် လိုက်၍ပြောင်းလဲနိုင်သည်။) quity reboot ပုံမှန်အလုပ် လုပ်ဆောင်နိုင်ပြီဟု မသေချာသေးပါက Super Grub Disk CD ကို အသုံးပြု၍ Grub ကို active 
လုပ်ပါ။

####Mac OS X ရှိပြီးသား ကွန်ပျူတာပေါ်တွင် Ubuntu တင်ခြင်း

Booth လုပ်နေစဉ်အတွင်း boothloader တွင် ပုံမှန်လုပ်ဆောင်နေခြင်းမရှိဟု သတင်းပို့ချက် (ဥပမာ HFS+error) များပေါ်လာပါက Super Grub ကိုအသုံးပြု၍ Linux GRUB နှင့် MBR (Master Boot Record) ကို ပြန်လည်ပြင်ဆင်နိုင်သည်။ Ubuntu ကို ထည့်သွင်းပြီးပါက Grub start-up list ကိုပြင်ဆင်ပြောင်းလဲပါ။

	sudo nano /boot/grub/menu.1st

ထို့နောက် ထပ်ပေါင်းထည့်ရမည့် စာကြောင်းများမှာ

	title Mac OS X root (hd0,0) makeactive chainloader +1

အကယ်၍ သင်သည်GRUB တွင် Mac OS X သို့မဟုတ် Windows နှင့်ပတ်သတ်၍ အခက်အခဲဖြစ်နေပါက Mac OS X ၏ Grub ရှိ entry ကို "root (hd0,1) သို့ပြောင်းလဲပါ။ထိုသို့ပြောင်းလဲခြင်းဖြင့် သင်၏ကွန်ပျူတာသည် Partition number 1 ကို boot လုပ်ပါလိမ့်မည်။Grub
မှန်ကန်စွာအလုပ်လုပ်ဆောင်နိုင်သည်အထိ partition number ကို﻿ပြောင်းလဲနိုင်သည်။

-------------------

##Package Installation and Updates

###Apt and Package Basics 

**Add Extra Repositories ကိုဖတ်ပါ။**

Ubuntu အသုံးပြုသူအများစုသည် Synaptic Package Manager ကို package များထည့်သွင်းရန် 
အသုံးပြုကြပါသည်။ အောက်ပါ ညွှန်ပြချက်များသည် package များကို ကိုpackage များထည့်သွင်းရန်
အသုံးပြုကြပါသည်။အောက်ပါညွှန်ပြချက်များသည် package များကို command-line Terminal အသုံးပြု၍ ထည့်သွင်းရန် နည်းလမ်းများဖြစ်ပါသည်။ 

#####Terminal ကိုစတင်ရန် 
	Menu -> Application -> Accessories -> Terminal

#####packages များထည့်သွင်းရန် 

	sudo apt-get install *packagename* 
	ဥပမာ : sudo apt-get install mpd sbackup

#####package များ ဖယ်ရှားရန်

	sudo apt-get remove *packagename*

#####package နှင့်တကွ ထို package နှင့် သက်ဆိုင်သည်များအားလုံး ဖယ်ရှားရန် 

	sudo apt-get autoremove 
	ဥပမာ : sudo apt-get remove mpd sbackup

#####package များရှာဖွေရန် 

	apt-cache search < keywords> 
	ဥပမာ : apt-cache search  Music MP3 apt-cache search "Text Editor"

#####addting/removing repositories ပြုလုပ်ပြီး package ၏ database များကို အဆင့်မြှင့်တင်ရန် 

	sudo apt-get update

#####package များကို ugrade လုပ်ရန် :

	sudo apt-get upgrade

#####Ubuntu စနစ်တစ်ခုလုံးကို upgrade  လုပ်ရန် (ဥပမာ : Maverick မှ Natty)

	sudo apt-get dist-upgrade

#####deb package များထည့်သွင်းခြင်း

Debian (.deb) package များသည် (Windows ပေါ်တွင်installer .exe msi package များ
အလုပ်လုပ်သကဲ့သို့) Ubuntu ပေါ်တွင် အသုံးပြုသော package များဖြစ်သည်။ Ubuntu စနစ်ပေါ်တွင် မည်သည့် .deb package ကိုမဆို ထည့်သွင်းနိုင်သည်။ Ubuntu စနစ်တွင် မူလပါရှိသော installer နှင့် .deb package များကို ဆက်သွယ်နိုင်ရန် ပြုလုပ်ထားသဖြင့် .deb ဖိုင်များကို file manager (Nautilus) တွင် click ခြင်းဖြင့် လွယ်ကူစွာထည့်သွင်းနိုင်သည်။ အောက်ဖော်ပြပါ ညွှန်ပြချက်များမှာ command-line terminal (Terminal) ကိုအသုံးပြုှ၍ package များ ထည့်သွင်းချင်သူများအတွက် ဖြစ်ပါသည်။

#####အင်တာနက်မှ ဆွဲယူထားသော Debian (Ubuntu) package (.deb) ၁ခု ထည့်သွင်းရန်

	sudo dpkg -i packagename.deb

#####Debian (Ubuntu) package (.deb) ကိုဖယ်ရှားရန် :

	sudo dpkg -r packagename . ဥပမာ : sudo dpkg-reconfigure mpd

------------------

##Handling (Tar/GZip) and (Tar/Bzip2) archives

(Tar/GZip) ရဲ့ extension က .tar.gz ဖြစ်ပါသည်။ (Tar/Bzip2) ရဲ့ extension က .tar.bz2 ဖြစ်ပါသည်။ Terminal မှ အသုံးပြုနည်းများကို အောက်ပါအတိုင်းဖော်ပြလိုက်ပါသည်။

	tar xvf  packagename . tar . gz
	-x (ဖြည်ရန်) -v ( ) -f ( )

#####.gz ကိုဖြည်ခြင်း

	gunzip filename .gz

#####.bz2 ကိုဖြည်ခြင်း

#####.gz အဖြစ် နှစ်သက်ရာဖိုင်ကို compress လုပ်ခြင်း

	tar cvfs packagename  .tar.gz folder

#####.bz2 အဖြစ် နှစ်သက်ရာဖိုင်ကို compress လုပ်ခြင်း

	tar cvfj packagename.tar.bz2 folder

-------------------------

##Installing a package from source 

Coming Soon !      
your can contribute

###Aptitude

Aptitude is a terminal-based package manager that can be used instead of apt-get. Aptitude marks package that are automatically installed and removes them when no packages depend on them. This makes it easy to remove application completely. To use Aptitude, replace apt-get with aptitude in the command line.Example

	sudo aptitude install packagename
	sudo aptitude remove packagename 
	sudo aptitude update
	sudo aptitude upgrade

For an ncurses-based graphical user interface, type

	sudo aptitude

For more information, see the aptitude documentation 
(http://people.debian.org/~dburrows/aptitude-doc/en/) .

###Synaptic Package Manager

While apt-get and aptitude are fast ways of installing programs/packages, you can also use the Synaptic Package Manager (Menu - System - Administration - Synaptic Manager ), a GUI method for installing programs/packages.Most (but not all) programs/packages available with apt-get install will also be available from the Synaptic Package Manager.This is the preferred method for most desktop users.In this guide, when you see

	sudo apt-get install package

you can simply search for package in Synaptic and install it that way.

	Menu-System - Administration - Synaptic Package Manager

Search for the name of the program/package. You can also search for a word in its
description.

Mark for Installation -Apply

The selected programs(s) will be automatically installed, along with its dependencies.

###Ubuntu Software Center (Add/Remove Programs)

Package များအားလုံးသည် Terminal (apt-get, aptitude, and Synaptic Package Manager)
မှာအဆင်သင့် မရရှိနိုင်သော်လည်းပဲ Ubuntu Software Center မှရရှိနိုင်ပါသည်.မည်သို့ဖြစ်စေ ၊ Ubuntu စတင်အသုံးပြုသူများ အနေဖြင့် အလွယ်ကူဆုံး မြင်ကွင်းမှ packages များအား အောက်ပါအတိုင်း ထည့်သွင်းနိုင်သည်။

	Menu -Application - Ubuntu Software Center

သင်ထည့်သွင်းလိုသော Program အချို့အား ရှာဖွေနိုင်သည်။ဥပမာ -mp3ဟုရိုက်လျှင် mp3
software စာရင်းများ မြင်ရမည်။

	Installation ပြုလုပ်လိုသော program အားရွေးချယ်ပါ -Apply နှိပ်ပါ။ရွေးချယ်ထားသော program(s) များသည် အလိုအလျောက် install ပြုလုပ်သွားမည်။

###Manual Updates

General Notes ကိုဖတ်ပါ။
Add Extra Repositories ကိုဖတ်ပါ။

#####Terminal မှ တဆင့် ကိုယ်ကိုတိုင်ပြုလုပ်ရန်အတွက် (Command Line Interface ):

	sudo apt-get update
	sudo apt-get upgrade

	**သို့မဟုတ်**

#####Synptic Package Manager ကို အသုံးချနည်း

	Menu -System -Administration - Synaptic Package Manager -Reload then Mark all upgrades

အကယ်၍ package က updating လုပ်ဖို့ အဆင်သင့်ဖြစ်နေမယ်ဆိုရင် ချက်ခြင်း install လုပ်သင့်ပါတယ်။

###Automated Updates

#####Synaptic Package Manager ကို အသုံးချခြင်း

	Menu - System - Administration - Synaptic Manager - Settings - Preferences - General - Reloading Outdated Package Information - Automatic

------------------------------

##Desktop Add-ons

GNOME Desktop အတွက် အဆင်သင့်အသုံးပြုနိုင်တဲ့ Add-on icons တွေ themes နဲ့ Wallpapers များ 3-D effects များနှင့်အတူ အခြားသော ကိုယ်ကိုယ်တိုင် ရွေးချယ်နိုင်တာတွေ ရှိပါတယ်။

###Gnome Eye-Candy Resources 

[Gnome Look](http://www.gnome-look.org) တွင် wallpapers တွေ splash screens တွေ icons တွေနဲ့အတူ  Windows Mangers အတွက် (Metacity နဲ့ Compiz ပါဝင်သည့်) themes များနှင့်အခြားသော အသုံးပြု ဆော့ဝဲတွေ (appalication) များပါရှိပါသည်။

###Ubuntu Wallpaper
[Ubuntu wallpaper](https://www.flickr.com/groups/ubuntuwallpaper/)
[Trusty Tahr Wallpaper](https://www.flickr.com/groups/2535978@N21)
[Ubuntu Myanmar wallpaper](http://flickr.com/groups/ubuntu-mm-art)
ဆိုဒ်မှ အခမဲ့သွားရောက် Download ပြုလုပ်နိုင်ပါတယ်။

###Change Plymouth Splash Screen 

Bootup မှာမြင်ရတဲ့ဟာက ကနဦး Splash Screen ဖြစ်ပြီး အခြားသော Plymouth Themes တွေကို Package Manger မှာသွားရောက် ရှာဖွေနိုင်ပါတယ်။ အသစ်တစ်ခုကို Install ပြုလုပ်ချင်ရင်တော့

	sudo update-alternatives --config default.plymouth
	sudo update-initramfs -u

မိမိကြိုက်နှစ်သက်ရာ Theme ကို ရွေးချယ်၍ တင်နိုင်ပါသည်။ Plymouth ကတော့ Bootup ပြုလုပ်နေတဲ့အချိန်မှာ မကြာခဏ Blacnk Screen များပေါ်ပေါက်ခြင်းနဲ့ nVidia Drivers တွေ ချက်ခြင်း အလုပ်မလုပ်ဆောင်နိုင်သေးပါဘူး။

###Change USplash Boot Screen

	sudo apt-get install splashy splashy-themes

###Metacity

Metacity ဆိုတာက Gnome မှာပါတဲ့ မူလ Desktop Compositing Manager ပါ။ သူက ပေါ့ပါးခြင်း၊
ချက်ခြင်းပြောင်းလွဲခြင်း (streamlined) တွေနဲ့အတူ များများစားစားလဲ ပြုပြင်ပြောင်းလွဲစရာမလိုတဲ့ Options တွေပါဝင်သလို Gnome Look မှာတော့ Multiple Themes တွေ ချက်ခြင်း ဆောင်ရွက်နိုင်ပြန်တယ်။

###Compiz Fusion 

Compiz Fusion က window manager နဲ့ သီးခြားကွဲပြားပါတယ်။ သူက Desktop effects တွေကို 
အဆင့်မြင့် ပြောင်းလွဲနိုင်တာဖြစ်ပြီး Cube တုံးသဖွယ်မျိုး Desktop ကို ပြောင်းလဲဖန်တီးနိုင်တာတွေလဲ
ပါဝင်ပါတယ်။Ubuntu Users တော်တော်များများက Compiz ကိုရွေးချယ် အသုံးပြုကြပါတယ်။ဒါကို Ubuntu မှာ အချိန်ခဏလေးနဲ့ အလွယ်တကူ Install ပြုချင်ရင်တော့

	sudo apt-get install compiz compizconfig-settings-manager compiz-fusion-plugins-maincompiz-fusion-plugins-extra emerald librsvg2-common

Compiz ကို Window Manager အဖြစ်ထားချင်ရင်တော့ Compiz Configuration မှာ အောက်ကအတိုင်း သွားရောက်ရွေးချယ်ပေးယုံပါပဲ

	Menu - System -Preferences - CompizConfig Settings Manager

မှတ်ချက် ။ ပြောင်းလွဲထားတာတွေကို အဆင်ပြေဖို့က Process ပြီးသွားရင် Logout လုပ်ပြီးတော့ Login ပြန်လုပ်မှသာ ပြောင်းလွဲခြင်း effect ကို မြင်ရမှာဖြစ်ပါတယ်။

###Virtualization

Coming Soon!!!

###Moonlight

See Moonlight plugin for Firefox

###Java

Java install လုပ်ရန်

	sudo apt-get install default-jre

###DosBox

[DosBox](http://www.dosbox.com/) သည် DOS-emulator (ဆက်စပ်ကိရိယာ) program တစ်ခုဖြစ်သည်။ ၎င်းသည် `CPU:286/386 realmode/protected mode, Directory FileSystem/XMS/EMS, Tandy/Hercules/CGA/EGA/VGA/VESA grahpics` နှင့် `SoundBlaster/Gravis Ultra Sound card` (ယခင်ဂိမ်းအဟောင်းများ၏ အသံဖြင့်လိုက်လျောညီထွေဖြစ်စေရန်) အသုံးပြုသည်။ သင်သည်ယခုခေတ် ကွန်ပျူတာများပေါ်တွင် ဆော့မရတော့သော ယခင်ဂန္ဓ္ဓ္ဓဝင် ဂိမ်းများအားပြန်လည်အသက်သွင်းနိုင်ပါလိမ့်မည်။

	sudo apt-get install dosbox

###Scumm VM

[Scumm VM](http://scummvm.org/) သည် ရုပ်ပုံများအားညွှန်ပြခြင်း၊ Click လုပ်ခြင်းစသည့်
ဂိမ်းဟောင်းများအား လက်ခံ၍ run ပေးပါသည်။(သင့်တွင် ၎င်းတို့၏ ဒေတာဖိုင်များရှိရပါမည်။) Scumm VM သည် executables shipped များတွင် နေရာယူ၍ ဂိမ်းများကို Linux OSတွင် ကစားခွင့်ပေးမှာဖြစ်ပါတယ်။

	sudo apt-get install scummvm

###Edutainment Applications 

p-26(မရိုက်ထား)

###Google Earth

[Google Earth](http://earth.google.com/) မှ သင့်အား ကျွန်ုပ်တို့ကမ္ဘာဂြိုလ်ကြီးကို အပေါ်စီးက
မြင်တွေ့ခွင့်ပေးမှာဖြစ်ပါတယ်။ဒီ software ဟာ အခမဲ့ package ဖြစ်ပါတယ်။ (ဒီ package ကိုအသုံးပြုဖို့အတွက် License ကို accept လုပ်ရမှာဖြစ်ပါတယ်။)

	sudo apt-get install googleearth-package
	make-googleearth-package --force

ရရှိလာတဲ့ .deb file ကို click ၂ချက်နှိပ်ပါ။ (သို့မဟုတ်) Linux အတွက် နောက်ဆုံးထွက်ရှိထားတဲ့ package ကို install လုပ်ရန်အတွက် [Google Earth downloads](http://earth.google.com/intl/en/download-earth.html) ကိုသွားပြီး Download ဆွဲပါ။ ပြီးရင် အောက်က
command နဲ့ install လုပ်ပါ။  

	wget http://dl.google.com/GoogleEarthLinux.bin/
	chmod  +x GoogleEarthLinux.bin ./GoogleEarthLinux.bin

#####အသုံးပြုရန်

	Menu - Application -Internet -Google Earth 3D planet viewer

သင့်အနေနဲ့ Google Earth -View မှာရှိတဲ့ Atmosphere setting ကို turn off လုပ်ထားသင့်ပါတယ်။
ဘာကြောင့်လဲဆိုတော့ တိမ်တွေဖုံးနေတာကြောင့် မြေပြင်ကို ပြမှာမဟုတ်လို့ပါဘဲ။

#####Troubleshooting

Troubleshooting (ပြင်ဆင်ခြင်း) အကယ်၍ Google Earth ကိုဖွင့်လိုက်တယ်။ Loading ပြုလုပ်တယ်။ loading ပြုလုပ်တဲ့ screen တတ်လာပြီး error ပြမယ်။ဒါမှမဟုတ် ဘာမှမပေါ်တော့ဘူးဆိုရင်တော့ သင်ဟာ ဖြစ်လေ့ဖြစ်ထရှိတဲ့ error တတ်ခြင်းကိုတွေ့ကြုံနေရပါပြီ။အဲဒီလိုဖြစ်နေချိန်မှာ Google Earth ကို Terminal ကနေ `~/google-earth/googleearth` လို့ရိုက်ပြီး run လိုက်ရင် `./googleearth-bin: relocation error:/usr/lib/i686/cmov/libssl.so.0.9.8: symbol BIO-test-flags, version OPENSSL-0.9.8 not defined in file libcrypto.so.0.9.8 with link time reference` ဆိုတဲ့ error ကိုပြပါလိမ့်မယ်။

ဒီပြဿနာကိုဖြေရှင်းဖို့အတွက်သင် Google Earth ကိုသွင်းထားတဲ့ Folder ကိုဖွင့်လိုက်ပါ။ပုံမှန်အားဖြင့်တော့ Google Earth ဟာ သင့် home folder ထဲမှာပဲ ရှိနေတတ်ပါတယ်။ ပြီးရင် `libcrypto.so.0.9.8` ကိုရှာပြီး `libcrypto.so.0.9.8.bak` လို့ပြောင်းလိုက်ပါ။ Google Earth ဟာ ပုံမှန်အတိုင်း သုံးလို့ရသွားပါလိမ့်မယ်။

	cd ~/google-earth
	sudo mv 
	libcrypto.so.0.9.8 libcrypto.so.0.9.8.bak
	sudo In -s /usr/lib/libcrypto.so.0.9.8~/google-earth/libcrypto.so.0.9.8

>**သတိပြုရန်** သင့်အနေနဲ့ `~/google-earth` လို့ရိုက်မယ့်အစား `/home/user/google-earth` လို့လဲရိုက်နိုင်ပါတယ်)

အခြား ပြဿနာတွေအတွက်ကိုတော့ [Ubuntu help pages on Google Earth](https://help.ubuntu.com/community/GoogleEarth) မှာကြည့်ရှုနိုင်ပါတယ်။

#####Google Earth အား Uninstall ပြုလုပ်ရန်

Uninstall ပြုလုပ်ဖို့အတွက် `/home/user/google-earth Folder` (သင် Google-earth ကို install ထားတဲ့ folder) မှာရှိတဲ့ uninstall shell script ကို run ပါ။

###FBReader (e-book reader)

[FBReader](http://www.fbreader.org/) သည် GTK platform ကို အခြေခံထားပြီး အခြား platform များတွင်ပါ အသုံးပြုနိုင်သည့် အခမဲ့ e-book reader တစ်ခုဖြစ်သည်။ install ပြုလုပ်ရန်:

	sudo apt-get install fbreader

###Calibre (e-book reader)

[Calibre](http://calibre-ebook.com) သည် e-book reader ဖြစ်ပြီး library manager အဖြစ်လည်း
အသုံးပြုနိုင်သည်။ Install ပြုလုပ်ပုံကို [ဤနေရာတွင်](http://calibre-ebook.com/download-linux)
ကြည့်ပါ။

----------------------

##Games 

ဂိမ်းများ (K)Ubuntu Linux အတွက် သဘာဝကျတဲ့ ဂိမ်းတွေရှိပါတယ်။   

- Ubuntu Community Wiki -- [Games](http://help.ubuntu.com/community/Games).
- [Best Linux Games for 2008](http://whdb.com/2008/top-25-linux-games-for-2008/).
- [Best 25 Linux Games of 2007](http://rangit.com/software/top-8-linux-games-of-2007/).

(K)Ubuntu မှာ ရာပေါင်းများစွာသော အခမဲ့, open-source ဂိမ်းတွေရှိပါတယ်။

- [KDE Games collection](http://www.kde.org/application/games/) နဲ့ 
- [Gnome Games](http://live.gnome.org/GnomeGames/) collection အပါအဝင် အတော်များများကို သင့်ရဲ့ Package Manager ထဲက Games Section မှတဆင့် ရယူနိုင်ပါတယ်။

ဥပမာတစ်ချို့ပေးရမယ်ဆိုရင် 

#####PouetChess
[PouetChess](http://pouetchess.sourceforge.net/) ဟာပြီးပြည့်စုံတဲ့ 3-D ချက်ထိုးတဲ့ Game တစ်ခုပါ။ Install ပြုလုပ်ရန်      

	sudo apt-get install pouetchess

#####PokerTH
[PokerTH](http://www.pokerth.net/) ဟာအလွန်ကစားရကောင်းတဲ့ Texas Hold 'Em Poker ပိုကာ Game ပါ။ [PPA repository](https://launchpad.net/~pkg-games/+archive/ppa) အသုံးပြုပြီး install လုပ်နိုင်ပါတယ်။

#####Kajongg
[Kajongg](http://packages.ubuntu.com/maverick/kajongg) ဟာလူတွေနဲ့ပဲဖြစ်ဖြစ်၊
စက်ရုပ်တွေနဲ့ပဲဖြစ်ဖြစ် တွဲဖက်/ယှဉ်ပြိုင်ကစားရမယ့် MahJongg (မာကျောက်)ကစားနည်းစစ်စစ်ပါပဲ။
Install ပြုလုပ်ရန် -

	sudo apt-get install kajongg

#####Planet Penguin Racer
[Planet Penguin Racer](http://en.wikipedia.org/wiki/Tux-Racer) ဟာပင်ဂွင်းငှက်ကလေးဟာ
သုံးဖက်မြင် (3-D) အနေအထားနဲ့ နှင်းလျှောစီးသွားမယ်။ ငါးတွေကို ဖမ်းရမှာဖြစ်ပါတယ်။ 

#####Extreme Tux Racer
[Extreme Tux Racer](http://extremetuxracer.com/) ကတော့ နောက်ပေါ် ဗားရှင်းဖြစ်ပေမယ့် 32-bit မှာပဲအလုပ်လုပ်ပါတယ်။

#####KsirK
[KsirK](http://games.kde.org/game.php?game=ksirk) ဟာကွန်ပျူတာနဲ့ပဲဖြစ်ဖြစ်
သူငယ်ချင်းနဲ့ချိတ်ဆက်ပြီးပဲဖြစ်ဖြစ် သဲထိတ်ရင်ဖိုဆော့ကစားရမဲ့ ဂိမ်းပါ။ Install ပြုလုပ်ရန် -

	sudo apt-get install kdegames

#####Racer
[Racer](http://www.racer.nl/) ဟာတကယ့်ကို စိန်ခေါ်ယှဉ်ပြိုင်နိုင်တဲ့ 3-D ပြိုင်ကားဂိမ်းပါ။ Binary
install ကို [ဒီမှာ](http://www.racer.nl/dl_beta_linux.htm) တွေ့နိုင်ပါတယ်။ ပြေးလမ်းအသစ်နဲ့
[extra add-ons](http://www.racer.nl/dl_content.htm) တွေလည်းရှိပါတယ်။

#####TORCS
[TORCS](http://torcs.sourceforge.net/) ဟာ 3-D ပြိုင်ကားဂိမ်းဖြစ်ပါတယ်။ Install လုပ်ရန် -

	sudo apt-get install torcs

#####Supertuxkart
[Supertuxkart](http://supertuxkart.sourceforge.net/) ဟာပြိုင်ကား အသေးစားလေးများကို မောင်းနှင်ရတဲ့ ဂိမ်းဖြစ်ပါတယ်။ Install ပြုလုပ်ရန် - 

	sudo apt-get install supertuxkart

#####Pingus
[Pingus](http://pingus.seul.org/) ရဲ့ညီအစ်ကိုဖြစ်တဲ့ Lemming (လီမင်) အစား
ပင်ဂွင်းငှက်ကလေးတွေကို အသုံးပြုထားတာပါ။ Install ပြုလုပ်ရန် - 

	sudo apt-get install pingus

#####Frozen Bubble
[Frozen Bubble](http://www.frozen-bubble.org/)--ပူပေါင်းဖောက် ကစားနည်းတစ်ခုပါ။ Install
ပြုလုပ်ရန် - 

	sudo apt-get install frozen-bubble

#####Frets on Fire
[Frets on Fire](http://fretsonfire.sourceforge.net/) ဟာ Guitar Hero  နဲ့ ဆင်တူပါတယ်သင့်အနေနဲ့ Community Site တွေကနေတဆင့် [Guitar Hero](http://www.geetarfreaks.webs.com/Viva%20La%20Music.html) ထဲက သီချင်းတွေကို
သွင်းယူနိုင်ပါတယ်။ [community sites](http://fretsonfire.wikidot.com/custom-songs) မှာလဲ
အသေးစိတ်ဖတ်နိုင်ပါတယ်။ Install ပြုလုပ်ရန် - 

	sudo apt-get install fretsonfire

#####Scorched3d
[Scorched3d](http://www.scorched3d.co.uk/) ဟာနှစ်ဘက်မြင်ကို သုံးဖက်မြင် (3-
D) အဖြစ် ကစားနိုင်မယ့် အမြောက်ပစ်ဂိမ်းပါ။ Install လုပ်ရန် - 

	sudo apt-get install scorched3d

#####Pyscrabble
[Pyscrabble](http://pyscrabble.sourceforge.net/) နှင့် pyscrabble-server -- Online Scrabble(
စကားလုံးမိတ်ဆက်) ဂိမ်းနဲ့ server ဖြစ်ပါတယ်။ Install ပြုလုပ်ရန် -

	sudo apt-get install pyscrabble pyscrabble-server

Lexulou နဲ့ Internet Scrabble Club တို့မှာလည်း Scrabble နဲ့ပုံစံတူ browser-based online
ဂိမ်းတွေရှိပါတယ်။Internet Scrabble Club ကတော့ Java ကို install လုပ်ထားဖို့လိုအပ်ပါတယ်။Java install လုပ်ရန်

	sudo apt-get install default-jre

#####Wing Commander Linux
[Wing Commander Linux](http://priv.solsector.net/) ရဲ့ အခမဲ့ဗားရှင်းကို Binary ဖိုင်အဖြစ်
ဒီမှာ [Download](http://sourceforge.net/projects/privateer/)ယူနိုင်ပါပြီ။

[Vdrift](http://vdrift.net/) သည် အခမဲ့ open source ဖြစ်ပြီး Need For Speed ကဲ့သို့သော realistic, physics, multiple drift tracks, and multiplayer များပါဝင်သော 3-D ပြိုင်ကားဂိမ်းတစ်ခုဖြစ်သည်။ Joysticks များဖြင့်သော်လည်းကောင်း Mice နှင့် keyboard ဖြင့်သော်လည်းကောင်း အသုံးပြုနိုင်သည်။ Linux အတွက် Binary package အား ထို website မှ download လုပ်၍ ရယူနိုင်ပါသည်။

###Action Games

အံ့အားသင့်ဖွယ်ရာ အက်ရှင်ဂိမ်းတွေကို (Top 25 မှ ဂိမ်းများအပါအဝင်) Ubuntu မှာ ရရှိနိုင်ပါတယ်။
အတော်များများကို `Menu - Application - Ubuntu Software Center - Games` ကနေပြီး install လုပ်နိုင်ပါတယ်။ Example အချို့ကတော့-

#####Alien Arena
[Alien Arena](http://icculus.org/alienarena/rpa/about.html) --multi-player first person
shooter အက်ရှင်ဂိမ်းဖြစ်ပြီးအခမဲ့ server များနဲ့ ဆော့ကစားနိုင်ပါတယ်။ 

- (Package : alien- arena)
- (Server : alien-arena-server)


	sudo apt-get install alien-arena
	sudo apt-get install alien-arena-server

#####OpenArena
[OpenArena](http://www.openarena.ws/) -- Open-Source multi-player first person shooter အက်ရှင်ဂိမ်းဖြစ်ပြီး အခမဲ့ server များနဲ့ ဆော့ကစားနိုင်ပါတယ်။

	sudo apt-get install openaren
	sudo apt-get install openarena-server

#####Tremulous
[Tremulous](http://www.tremulous.net) -- Halo နဲ့ဆင်တူပြီး multiplayer first person shooter action ဂိမ်းဖြစ်ပါတယ်။ နောက်ဆုံးထွက် ဗားရှင်းအတွက် Repositories ရှိပါတယ်။

	sudo apt-get install tremulous
	sudo apt-get install tremulous-server

#####Sauerbraten
[Sauerbraten](http://sauerbraten.org/) - Cuber မှဖြစ်ပြီး Graphic ကောင်းကောင်းနဲ့ multiplayer ဆော့နိုင်တဲ့ First person shooter game ဖြစ်ပါတယ်။

	sudo apt-get install sauerbraten
	sudo apt-get install sauerbraten-server

#####Nexuiz
[Nexuiz](http://www.alientrap.org/nexuiz/) -- (ပြိုင်ပွဲများ) ပါဝင်တဲ့ open-source multi-player
First person shooter game ဖြစ်ပြီး free servers များနဲ့ဆော့ကစားနိုင်ပါတယ်။

	sudo apt-get install nexuiz
	sudo apt-get install nexuiz-server

မြေပုံ ၃၅ခုပါတဲ့ add-on community pack ကိုတော့ [ဒီနေရာမှာ](http://www.alientrap.org/nexuiz/downloads.php) ရရှိနိုင်ပါတယ်။ အဲတာကို install လုပ်ချင်ရင်တော့
map pack ကို `/home/username/.nexuiz/data` (ဒါမှမဟုတ်~ /.nexuiz/data)မှာ ဖြည်ချပေးပါ။ 
> **မှတ်ချက်** ဒီထဲက ဂိမ်းတော်တော်များများဟာ graphics လိုအပ်ချက်တွေရှိပါတယ်။ ဒါတွေကို ဆော့မယ်ဆိုရင်တော့သင့်အနေနဲ့ hardware driver တွေကို လုံလုံလောက်လောက် activate လုပ်ထားရပါမယ်။

#####Urban Terror

[Urban Terror](http://www.urbanterror.net) သည် multiplayer first person shooter အက်ရှင်ဂိမ်း (ဆာဗာထည့်သွင်းပြီး) ဖြစ်သည်။ ၎င်းသည် open-source quake 3 engine ကိုအသုံးပြုထားပြီး တကယ့်လက်နက်များ၏ အသုံးပြုနိုင်မှုများအား ထည့်သွင်းပေးထားသည်။အခမဲ့ server များဖြင့် multi-player ဆော့နိုင်စေရန် ပြုလုပ်ပေးထားသည်။ဂျာမနီနိုင်ငံတွင် လူငယ်များဆော့ကစားခွင့်အား ပိတ်ပင်ထားပါသည်။ Download ပြုလုပ်ပြီး [ဤအညွှန်း](http://www.urbanterror.info/docs/texts/110) ကိုအသုံးပြုကာ install လုပ်နိုင်ပါသည်။

#####Domm

Skulltag ရဲ့[ZDoom](http://zdoom.org/wiki/Compile_ZDoom_on_Linux) နဲ့ ProBoom (Freedoom) တို့ဟာ Doom2 ရဲ့ ဗားရှင်းခွဲတွေဖြစ်ပါတယ်။ Doom3 အတွက်ကိုတော့ Ubuntu ပေါ်က [Doom3](http://help.ubuntu.com/community/Doom3) မှာ ကြည့်ရှုနိုင်ပါတယ်။

#####Skulltag

[Skulltag](http://skulltag.net/wiki/Installation_for_Ubuntu) သည် [ZDoom](http://zdoom.org/wiki/Compile_ZDoom_on_Linux) ကို အဆင့်မြှင့်တင်ထားသော  ဗားရှင်းဖြစ်ပြီး
network play ကစားနိုင်ပါသည်။ (K)Ubuntu တွင် install လုပ်နည်းအား [website](http://skulltage.net/wiki/Installation_for_Ubuntu)တွင် ကြည့်ရှုနိုင်ပါသည်။(အကယ်၍သင့်တွင် မူလ
`Doom2.wad` မရှိပါက အောက်တွင် ဖော်ပြထားသော Freedom Iwad ကို အသုံးပြုနိုင်ပါသည်။) 

> **မှတ်ချက်** Modules အတော်များများသည် Universe repositories မှ သီးခြားလိုအပ်ပါသည်။သင့်အနေဖြင့် Universe repositories ကို enable ပြုလုပ်ထားရန်လိုအပ်သည်။ `Synaptic Package Manager - Settings - Repositories - Edit Software Sources - Community-maintained Open Source software (universe)` - (အမှန်ခြစ်ပေးပါ။))

Install ပြုလုပ်ရန် ကြိုတင်ပြင်ဆင်မှု

	sudo apt-get install timidity timidity-interfaces-extra

ထို့နောက် skulltage ၏ repositories များ update များထည့်၍ skulltage နှင့် DoomSeeker(Skulltag online server) အား install ပြုလုပ်ပါ။

	echo deb http://skulltag.net/download/files/release/deb/jaunty multiverse/ sudo tee /etc/apt/sour
	sudo apt-get update
	sudo apt-get install skulltage doomseeker-skulltag

အကယ်၍ သင့်တွင် `doom2.wad,tnt.wad` သို့မဟုတ် `plutonia.wad` မရှိပါက `freedoom.wad` ကိုသင့် `~/.skulltag` folder သို့ copy လုပ်နိုင်ပါသည်။

	cd ~/.skulltag
	wget http:/mirror.cinquix.com/pub/savannah/freedoom/freedoom-iwad/freedoom-iwad-0.6.4.zip/
	unzip freedoom-iwad-0.6.4.zip
	cp freedoom+/doom2.wad.
	rm freedoom-iwad-0.6.4.zip

အကယ်၍ သင့်တွင် (skulltag-server,firewalls နှင့် skulltag ဖြင့် port forwarding
ပြုလုပ်ခြင်းတို့အတွက်)အကူအညီများလိုအပ်ပါက ဤထပ်တိုး လမ်းညွှန်ချက်များအား ကြည့်ပါ။

Skulltag ကို မည်သည့် platform, မည်သည့် graphics, မည်သည့် စက်တွင်မဆိုအသုံးပြုနိုင်ပါသည်။
၎င်းတွင် ထောင်ပေါင်းများစွာသော add-on များ၊မြေပုံများ၊ gameplay mode များအား
ရွေးချယ်မကုန်နိုင်အောင် အသုံးပြုကစားနိုင်ပါသည်။

#####PrBoom

[PrBoom](http://prboom.sourceforge.net/) သည် မူလ first person shooter action game ဖြစ်သည့် [Doom2](http://en.wikipedia.org/wiki/Doom_II) သည် အခမဲ့ open source port ဖြစ်သည်။၎င်းတွင် ZDoom ၏ advanced option  များပါဝင်ခြင်းမရှိပါ။ Freedoom သည်မူလ `Doom2,wad` ကိုနေရာယူမည့် အခမဲ့ Iwad (မြေပုံစု)ဖြစ်ပါသည်။

	sudo apt-get install prboom freedoom timidity timidity-interfaces-extra

ဤဂိမ်းအတွက် ထောင်ပေါင်းများစွာသော [ မြေပုံ (Wads)](http://www.doomword.com/10years/bestwads/) ရှိပါသည်။သင့် home directory သည် သင့်
မြေပုံ (wads) များ သိမ်းဆည်းရန် အလွယ်ကူဆုံးနေရာဖြစ်ပါသည်။

	mkdir /home/user/wads

သို့မဟုတ် အပြောင်းအလဲအနေဖြင့် `/user/share/games/doom folder` ကိုအသုံးပြု၍ folder
အားမည်သူမဆို အသုံးပြုနိုင်ကြောင်း ပြောင်းလဲသတ်မှတ်ပေးနိုင်ပါသည်။

	chmod -R 777/usr/share/games/doom

သင့်မူလဂိမ်းထဲမှ `doom2.wad,tnt.wad` နှင့် `plutonia.wad` တို့အား ဤ folder ထဲတွင်ထည့်ပါ။
အကယ်ဤသင့်တွင်မရှိပါက `usr/share/games/freedoom version` မှ `doom2.wad` ကို ဤ 
folder သို့ copy လုပ်နိုင်ပါသည်။သင် internet မှ Download လုပ်ထားသော `.wad` ဖိုင်အသစ်များကိုလည်း ဤ folder ထဲတွင်ပင် ထည့်သွင်းပါ။ ပြီးနောက် ဂိမ်းအား မူလ မြေပုံဖြင့်ဖြစ်စေ၊သင့် .wad မြေပုံသစ်ဖြင့်ဖြစ်စေကစားနိုင်ပါသည်။

	prboom -iwad /home/user/wads/doom2.wad-file /home/user/wads/new_wad.wad

>**မှတ်ချက်** `doom2,wad,tnt.wad` သို့မဟုတ် `plutonia.wad` တို့ကိုသာလျှင် `iwad` အဖြစ်အသုံးပြု၍ ရပါသည်။ သင့်အနေဖြင့် `wad` အသစ်ထည့်သွင်းအသုံးပြုလိုပါက အထက်ပါ၃ခုမှ တစ်ခုရှိရပါမည်။ပြဿနာရှိလာပါက `doom2.wad` ကိုသုံးပါ။   


>**မှတ်ချက်** ဤဂိမ်းအား `Menu -Applications - Ubuntu Software Center -Games` ရှိ Freedom မှ install လုပ်ယူနိုင်ပါသည်။ သို့သော် `timidity` နှင့် `timidity-interfaces-extra` ကို install ပြုလုပ်ရန်လိုအပ်ပါသည်။

####MMORPG

#####Spring

The Spring Project  (http://spring, clan-sy.com) သည် [Star Wars Imperial Winter](http://www.imperialwinter.com/) နှင့် [Complete Annihilation](http://springrts.com/wiki/Complete_Annihilation#Introduction) တို့ကဲ့သို့ အခမဲ့ multiplayer ဂိမ်းများအား
ရေးဆွဲခြင်း၊ကစားခြင်းတို့အတွက် scripting engine platform ဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install spring

#####Regnum Online

[Regnum Online MMPORG](http://www.regnumonline.com.ar/index.php?sec=61=1) အတွက် အကူအညီလိုအပ်ပါက အခြေခံ [installation](http://ubuntuforums.org/showthread.php?t=615246) ဲပြုလုပ်နည်းနှင့် [help forum](http://www.regnumonline.com.ar/forum/forumdisplay.php?f=15) တွင်ကြည့်ပါ။

#####PlaneShift 

[PlaneShift](http://www.planeshift.it/) သည် စိတ်ကူးယဉ်မှုတွေ ပြည့်သိပ်နှစ်မြုပ်နေသည့် online fantasy ဂိမ်းတစ်ခုဖြစ်သည်။ Client နှင့် patches များအား [ဒီနေရာတွင်](http://www.planeshift.it/download.html) download လုပ်နိုင်ပါသည်။

Download လုပ်ထားသော Binary Installation ဖိုင်အား executable ဖြစ်အောင်ပြုလုပ်ပါ။

	cd /directory_where_downloaded
	chmod +x PlaneShift-v0.5.4-x64.bin

root အနေဖြင့် executable လုပ်ထားသောဖိုင်အား run ပါ။

	sudo  ./PlaneShift-v0.5.4-x64.bin

Install လုပ်ရမည့်လမ်းညွှန်ချက်များအား လိုက်နာပါ။Whether to manually set permissions
ဟုမေးလာပါက no ဟုဖြေပေးပါ။ Install ပြုလုပ်နေစဉ်တွင် အသုံးပြုသူတော်တော်များများသည် ဂိမ်းအား User အားလုံးအသုံးပြုနိုင်ရန် `/opt` တွင် install လုပ်ခြင်းထက် user တစ်ဦးတည်း အသုံးပြုနိုင်မည့် `/home directory` တွင်  install ပြုလုပ်ခြင်းကို ပိုအလေးပေးကြသည်။ `/opt` တွင်install လုပ်ခြင်းသည် အလုပ်ပိုခြင်းကြောင့်ဖြစ်သည်။ သင့် user account အား Games Group တွင်ထည့်သွင်းပါ။

	Menu - System - Administration - Users and Groups - user- Manager Groups -games - Properties - Group Members -user (အမှန်ခြစ်ပါ)-OK

Download the updater patch psupdaterlinux64.zip and unzip it to your download directory. Run the updater as root:

	chmod +x psupdater
	chmod +x psupdater.bin
	sudo ./psupdater---

[PlaneShift Registration](http://www.planeshift.it/register.html)တွင် စာရင်းသွင်း၍ အခမဲ့
အကောင့်တစ်ခုလုပ်ပါ။ အကယ်၍ သင်သည် game ကို menu တွင်ထည့်သွင်းထားပါက `Menu - Applications - Lost Found - Client and Setup` တွင်ရှိပါလိမ့်မည်။

Menu မှ run ချင်ပါက Run in terminal ကို အမှန်ခြစ်လုပ်ပေးရပါမည်။ Command-line Terminal မှ run ချင်ပါက

	sudo /opt/PlaneShift/pssetup
	sudo /opt/PlaneShift/psclient

>**မှတ်ချက်** DSL connection ဖြင့် 32-bit ဗားရှင်း အသုံးပြုပါက လေးပါသည်။

----------------------------

##Internet Applications

သင့်ရဲ့ Internet connection အား Internet applications များဖြင့် အပြည့်အဝအသုံးပြုနိုင်သည်။Web
browsers,Email clients, Instant Messengers, နှင့် အမျိုးအစားအများပါဝင်သည်။

###Web Browsers

####Mozilla Firefox 

[Mozilla Firefox](http://www.mozilla.com/en-US/) သည်နေရာအများတွင် တွေ့ရသည့် web browser ဖြစ်သည်။ open source components တွင် အခြေခံထားသော်လည်း သင်၏ အမည် သို့မဟုတ် ကုန်အမှတ်တံဆိပ် ပါဝင်ထားပြီး တခုခုပြောင်းလဲထားခြင်းဖြင့် ထပ်မံ ဖြန့်ဖြူးနိုင်မည်မဟုတ်ပါ။ လက်ရှိသုံးနေသော version အားတင်ရန် -

	sudo apt-get install firefox

#####Firefox Plug-ins

######Adblock Plus plug-in (block ads in a web page)

[Adblock Plus](http://adblockplus.org/en/ ဖြင့် web pages များတွင် Blocks ads လုပ်နိုင်သည်။
သင့်အနေနဲ့ subscribe လုပ်ခြင်းဖြင့် အခမဲ့ Filter Service နှင့် ကြော်ငြာများကို တစ်ချက်တည်းနှင့်ပိတ်ရန် အတွက်ထပ်ပေါင်းနိုင်ပါသည်။

	sudo apt-get install xul-ext-adblock-plus

သင့်အနေနဲ့ ၎င်း extension အား add ရန် Firefox `Tools - Add -on -Get Add -ons -Search All` Add-ons-AdBlock Plus. (ထိုကဲ့သို့ လုပ်ဆောင်လျှင် firefox အနေဖြင့် automatic updates
လုပ်ဆောင်ပေးလိမ့်မည်။)

[Noscript](http://noscript.net/) သည် Internet ပေါ်တွင် browsing လုပ်ရာတွင် Sercuriy တိုင်းတာချက်အရ အရေးကြီးပါဝင်မှု တစ်ခုဖြစ်သည်။Scripts များဖြင့် Internet မှတဆင့် Viruses များနှင့် Trojans တို့သည် computers သို့ရောက်ရှိသည်။၎င်း plugin ဖြင့် မည်သည့် scripts အား Allow နှင့် blocks the rest လုပ်မည်ကို ရွေးချယ်နိုင်သည်။ ၎င်း extension အား add ရန် Firefox - `Tools - Add -ons -Get Add-ons -Search All Add -ons-Noscript.` (ထိုကဲ့သို့လုပ်ဆောင်လျင် firefox အနေဖြင့် automatic updates လုပ်ဆောင်ပေးလိမ့်မည်။)

######RefreshBlocker plug-in (prevents redirects)

[RefreshBlocker](https://addons.mozilla.org/en-US/firefox/addon/refreshblocker/) သည် မည်သည့် website(and pages)အား redirect(based on  META tags within the webpage ပြုလုပ်ရန်အတွက် user များအား ဆုံးဖြတ်ပေးသည်။သို့ပေသော်လည်း Firefox (as of version 3.5) တွင် အားလုံး directs လုပ်ခြင်းကို blocks လုပ်သည်မှာ default ဖြစ်သည်။ စိတ်ကြိုက်မဟုတ်သည့်အတွက်ကြောင့် firefox redirect control အား  turnoff လုပ်ပြီး ၎င်းအစား RefreshBlocker သုံးသည်။ သင့်အနေနဲ့ ၎င်း extension အား add ရန် Firefox - `Tool -Add-ons-Get Add-ons -Search All Add-ons-RefreshBlocker.`(ထိုကဲ့သို့လုပ်ဆောင်လျင် firefox အနေဖြင့် automatic updates လုပ်ဆောင်ပေးလိမ့်မည်။

######Turn off the Firefox  automatic redirect bloker  

Firefox - Enter about : config in the browser location bar-right-click on
accessibility:blockautorefresh - Toggle to change the value from true to false


######User Agent Switcher plug-in for Firefox

[User Agent Switcher](http://chrispederick.com/work/user-agent-switcher/) သည် အခြားသော browser  ကဲ့သို့ အယောင်ဆောင်ခြင်းကို ပြုလုပ်သည်ခွင့်ပြုခြင်း (အချိန်လွန်) broser-specific ပါရှိသောအကြောင်းအရာများကို displayed ပြုလုပ်ရန်။

သင့်အနေနဲက ၎င်း extension အား add ရန် Firefox - `Tool -Add-ons-GetAdd-ons- Search All Auto-ons-User Agent Switcher.`(ထိုကဲ့သို့လုပ်ဆောင်လျင် firefox  အနေဖြင့် automatic updates လုပ်ဆောင်ပေးလိမ့်မည်။

######Video DownloadHelper plug-in for Firefox

[Video DownloadHelper](http://addons.mozilla.org/en-US/firefox/addon3006) သည် youtube ကဲ့သို့သော site များမှ videos (Flash Videos အပါအဝင်) ကို download ရယူရန်ဖြစ်သည်။

သင့်အနေနဲ့ ၎င်းextension အား add ရန် Fierfox - `Tools -Add -ons- Get Add -ons-Search All Add-ons-Video DownloadHelper.` (ထိုကဲ့သို့ လုပ်ဆောင်လျင် firefox အနေဖြင့် automatic 
updates လုပ်ဆောင်ပေးလိမ့်မည်။) 

######Unplug Download Management

[UnPlug](https://addons.mozilla.org/en.US/firefox/addon/2254) add-on သည် webpag ပေါ်တွင် embedded လုပ်ထားသော video နှင့် Audio များကို Save လုပ်ယူနိုင်သည်။

သင့်အနေဖြင့် ၎င်း extension အား add ရန် Firefox - `Tool- Add-ons-Get Add-ons-Browse All Add-ons.` (ထိုကဲ့သို့လုပ်ဆောင်လျင် firefox အနေဖြင့် automatic updates
လုပ်ဆောင်ပေးလိမ့်မည်။)

######Lucifox (eBook reader  extension)

[Lucifox](https://addons.mozilla.org/en-US/firefox/addon/lucifox/) (Lucidor for Firefox) သည် e-book များကို ဖတ်ရန်နှင့် Firefox window မှနေ catalogs များကို browsed လုပ်ပေးနိုင်ရန်ဖြစ်သည်။ Install ပြုလုပ်ရန်ယ website သို့သွားပြီး နောက် Download Now နေရာတွင်ရယူနိုင်သည်။

######Java Runtime Environment (JRE) for Firefox plug-in

ယခု package သည် Java Runtime Enviroment install နှင့်တူညီသည်။ (OpenOffice Installed သောအခါ or ubuntu-restricted -extras installed သောအခါ JRE  ပါဝင်သည်။)

	sudo apt-get install sun-java6-jre sun-java6-plugin

>**မှတ်ချက်** သင့်အနေဖြင့် product ကိုအသုံးပြုရန် product license အား မလွဲမသွေ လက်ခံရမည်။

######Adobe Acrobat Reader for Firefox Plug-in

၎င်း pluging သည် Adobe Acrobat(pdf) files များကို firefox browser တွင် ကြည့်ရန်ဖြစ်သည်။
Read Add Extra Kubuntu Repositories and enable the Natty partner repository :

	deb http://archive.canonical.com/ubuntu natty partner/	

ပြီးပါက Adobe Reader ထည့်သွင်းရန် :

	sudo apt-get install acroread

သို့မဟုတ်ပါက ၎င်း plugin အား the Medibuntu repository list တွင်လည်း ရရှိနိုင်သည်။
Medibuntu repository အား သင့်ရဲ့ repository list တွင်ထည့်ရန် :

	deb http://packages.medibuntu.org// natty free non-free

ပြီးပါက Adober Reader ထည့်သွင်းရန် :

	sudo apt-get install acroread mozilla-acroread acroread-plugins acroread-fonts

######Adobe Flash Player for Firefox Plug-in

Firefox အတွက် offical Adobe Flash Plugin 10 အား တင်ရန် :

	sudo apt-get install adobe-flashplugin

######Gnash Plug-in (Open source Flash Player replacement)

[Gnash](http://www.gnashdev.org/) သည် 32-bit version ကဲ့သို့ 64-version အတွက်လည်း
ရယူနိုင်သည်။ ၎င်းသည် Adobe Flashplayer အတွက် source အား ပြောင်းလဲနိုင်သည်။

	sudo apt-get install gnash

installing ပြီးနောက်, သင့် web browser ရဲ့ Preference - Application ထဲရှိ `SWF and SPL files` မှားကို `Gnash` ဖြင့်သုံးမည်ဟု ကြေငြာရမည်။

######VLC plug-in for Firefox

၎င်း package သည် ယခုလက်ရှိ အသုံးများသော VIC player အား Firefox browser ရှိ play media 
တွင် အသုံးပြုသည်။

	sudo apt-get install mozilla-plugin-vlc

######Gecko MediaPlayer Plug-in for Firefox

[Gecko MediaPlayer](http://kdekorte.googlepages.com/gecko-mediaplayer) သည် Gecko-based broswers (Firefox,SeaMonkey,IceApe,Opera) များတွင် Mplayer မှ multimedia သို့ သုံးပြုသည်။

	sudo apt-get install gecko-mediaplayer

နောက်တစ်ခုအနေဖြင့် Firefox အတွက် mplayer အားသုံးပြုနိုင်သည်။

	sudo apt-get install mozilla-mplayer

######Kaffeine Plug-in for Firefox

၎င်း package ဖြစ်သည့် the Kaffeine media player (often used in KDE-based desktops) သည် Firefox browser တွင် multimedia အဖြစ်လုပ်ဆောင်သည ်။

	sudo apt-get install kaffeine-mozilla

######Helix player plug-in for Firefox

၎င်း package ဖြစ်သည့် [Helix player](https://helixcommunity.org/) (the open source player that plays Real Player content in Linux) သည် Firefox browser တွင် RealMedia အဖြစ်လုပ်ဆောင်သည်။

	sudo apt-get install mozilla-helix-player

######Moonlight plugin for Firefox

[Moonlight](http://www.go-mono.com/moonlight) သည် Silverlight (the Microsoft multimedia presentation platform) အား open source အဖြစ်လုပ်ဆောင်ရန် ကြိုးစားနေသော the Novell Mono ၏ project ဖြစ်သည်။၎င်းသည် FFMpeg အမျိုးအစားဖြစ်သည်။ Firefox 3 web browser တွင် ကောင်းကောင်းသုံးနိုင်ရန်ပြုလုပ်ထားပြီး, plugin ကဲ့သို့(အခြားသော mozilla browsers ကောင်းကောင်းသုံးနိုင်ရန်ပြုလုပ်ထားပြီး, plugin ကဲ့သို့(အခြားသော mozilla browsers
များတွင်လည်းလုပ်နိုင်သည်။)mozilla-based browsers ဖြစ်သော Version 2.3 တွင်လည်း plugin အဖြစ် လုပ်ဆောင်နိုင်သည်။

	sudo apt-get install moonlight-plugin-mozilla

stable version 2.4 အား [ဒီနေရာတွင်](http://www.go=mono.com/moonlight/stable.aspx)
ရနိုင်သည်။ The Moonlight 3.99 plugin (compatible with most Silverlight 3/4 content) အား
[ဒီနေရာတွင်](http://www.go--mono.com/moonlight/prerelease.aspx) ရနိုင်သည်။

######Netflix under Moonlight

Netflix streaming အတွက်လိုအပ်ချက်နှစ်ခုမှာ the capabilities of Silverlight 2.0 နှင့် Digital Rights Management modules ဖြစ်သည်။သို့ပေသော်လည်း လက်ရှိအမျိုးအစားဖြစ်သော Moonlight 2.0 တွင်လည်း Silverlight content (including Netflix content) သုံးနိုင်သည် ,linux အတွက် Digital Rights Management modules အား Netfilix မှ အဆင်သင့်မဖြစ်သေးပါ။ ကျေးဇူးပြုပြီး [Netflix](http://www.netflix.com/ContactUs) သို့တိုက်ရိုက်ဆက်သွယ်ပြီး သတင်းရယူနိုင်ပါသည်။သို့မဟုတ် [ဤနေရာတွင်](http://www.petitiononline.com/Linflix)  မှတ်ပုံတင်ပြီး တောင်းဆိုနိုင်ပါသည်။ (Chrome browser အတွက်Google မှပြုလုပ်နေသော)An HTML5 Netflix plugin မကြာမီ သုံးစွဲနိုင်တော့မည်။အခြားသော နည်းလမ်းတစ်ခုအနေနဲ့ Netflix Android app အား virtual Android environment တွင်လည်း သုံးစွဲနိုင်သည်။

######FireFTP for Firefox

FireFTP (http://fireftp.mozdev.org/) သည် Firefox extension တွင် FTP transfers အတွက်ဖြစ်သည်။

#####Firefox Widgets

Turn off browser bar drop-down list in Firefox

Firefox တွင် drop-down list ရှိ browser bar အားပိတ်ထားရန်။

၎င်းသည် Firefox တွင် တစ်ခါတစ်ရံမှသာ ဖြစ်ပေါ်တတ်သော ပြဿနာဖြစ်သည်။ drop-down list ရှိ location browser bar အား ပိတ်ထားရန် (http://kb.mozillazine.org/Browser.urlbar.maxRichResults) (ထိုသို့ပြုလုပ်ခြင်းဖြင့် သင့် browsing history အားပြသတော့မည်မဟုတ်ပါ။)

Firefox -  about:config (in the location browser bar) - browser.urlbar.maxRichResults-right-click-Modify-set value to 0

######IceCat

IceCat (http://en.wikipedia.org/wiki/GNU_IceCat) သည် Mozilla ၏ ကုန်အမှတ်တံဆိပ် မူပိုင်ခွင့်၊ တားမြစ်ချက်များမရှိသော Firefox အခြေပြု Browser တစ်ခုဖြစ်သည်။Debian project မှထောက်ပံ့ပေးသည်။ ယခင်က IceWeasel နာမည်နှင့်ဖြစ်ပြီး၊ယခု IceApe Browser နာမည်သို့ ပြောင်းလိုက်သည်။နောက်ဆုံး version ကို Install လုပ်ဆောင်ရန် Terminal တွင် အောက်ပါအတိုင်းရိုက်ထည့်ပါ။

    sudo apt-get install iceape-browser

######SeaMonkey

[SeaMonkey](http://www.seamonkey-project.org/) သည် web browser, IM (IRC) client, Email client,RSS/News reader နှင့် အခြား web development tools များပါဝင်သော အင်တာနက် application တစ်ခုဖြစ်ပါသည်။Mozilla ၏ ထုတ်ကုန်များကို အခြေခံထားပြီး၊ Mozilla ၏ မူပိုင်ခွင့်၊ ဖြန့်ဝေသုံးစွဲခွင့်များနှင့် ဆက်စပ်နေသည်။ Thunderbird နှင့် Firefox ကဲ့သို့ Seamonkey အတွက် Plugins အမြောက်အများရှိသည်။ Seamonkey ကို Install လုပ်ဆောင်ရန် Terminal တွင် အောက်ပါအတိုင်းရိုက်ထည့်ပါ။

    sudo apt-get install seamonkey

######IceApe

[IceApe](http://en.wikipedia.org/wiki/Naming_conflict_between_Debian_and_Mozilla) သည် web browser, IM (IRC) client, Email client, RSS/News reader နှင့် web development tools များပါဝင်သော open-source အင်တာနက် application တစ်ခုဖြစ်သည်။ Seamonkey ကို အခြေခံထားပြီး၊ မူပိုင်ခွင့် ကန့်သတ်ထားခြင်းများမရှိပေ။ Debian project မှထောက်ပံ့ပေးထားသော application ဖြစ်သည်။ နောက်ဆုံး version ကို Install လုပ်ဆောင်ရန် Terminal တွင် အောက်ပါအတိုင်းရိုက်ထည့်ပါ။

    sudo apt-get install iceape

####Opera

[Opera](http://www.opera.com/) သည် မူပိုင်ခွင့်ကန့်သတ်ချက်ရှိသော proprietary browser, internet suite တစ်ခုဖြစ်သည်။ Mobile devices အချို့နှင့် game consoles များတွင်လဲ အသုံးပြုနိုင်သည်။ Email, address book, IRC chat, integrated BitTorrent နှင့် webfeeds များပါဝင်သည်။ Plugins အနည်းငယ်လဲရှိသည်။ Install လုပ်ဆောင်ရန် Opera ၏ website မှ Download (http://www.opera.com/browser/download/) လုပ်ပြီး၊ လမ်းညွှန်ချက်များ ဆက်လုပ်ပါ။ သို့မဟုတ် အောက်ပါ command များကို အသုံးပြုပြီး Opera repository မှတဆင့် Install လုပ်နိုင်သည်။

	echo "deb http://deb.opera.com/opera/ stable non-free" | sudo tee /etc/apt/sources.list.d/opera.list
	wget -O - http://deb.opera.com/archive.key | sudo apt-key add -
	sudo apt-get install opera

####Chromium

[Chromium](http://dev.chromium.org/) သည် Google Chrome browser ကို အခြေခံထားသော open- source browser တစ်ခုဖြစ်သည်။ Chromium ကို Install လုပ်ရန် Terminal တွင် အောက်ပါအတိုင်း ရိုက်ထည့်ပါ။

    sudo apt-get install chromium-browser

Chromium ကို အသုံးပြုရန် အောက်ပါအတိုင်းသွားပါ။

Menu - Applications - Internet - Chromium Web Browser

####Google Chrome

[Google Chrome](http://www.google.com/chrome) သည် Google မှထုတ်သော browser တစ်ခုဖြစ်သည်။ Chromium browser ကိုအခြေခံထားပြီး၊ Google ၏ နာမည်၊ လိုဂိုအမှတ်တံဆိပ်၊ GoogleUpdate ဟုခေါ်သည့် အလိုအလျောက် Update စနစ်၊RZL နှင့် အခြား Google add-ons များပါဝင်သည်။ Google Chrome ကို ဤနေရာမှ (http://www.google.com/chrome/eula.html) ဒေါင်းလုတ်လုပ်ပြီး၊ install လုပ်ပါ။

###Download Managers

Browsers များထက် ဒေါင်းလုတ်လုပ်ငန်းစဉ် လွယ်ကူပြီး၊ပိုမိုမြန်ဆန်စေရန်၊ အမှားနည်းစေရန် ပြုလုပ်ထားသော ဆော့လ်ဝဲများဖြစ်သည်။အချို့ Download Managers များတွင် အင်တာနက် ကွန်နက်ရှင်မကောင်းပါက ခဏရပ်တန့်ထားပြီး၊ နောင် ကွန်နက်ရှင်ပြန်ကောင်းမှ ဆက်လက်ဒေါင်းလုတ်နိုင်သော Resuming Downloads Option လဲပါဝင်သည်။

####MultiGet

[MultiGet](http://multiget.sourceforge.net/) သည် ဒေါင်းလုတ်လုပ်ငန်းစဉ်များ လွယ်ကူစေရန် အသုံးပြုနိုင်သည့် Download Manager တစ်ခုဖြစ်သည်။ GTK ကို အခြေခံထားပြီး GUI (Graphical User Interface) နှင့်ဖြစ်သည်။ HTTP/FTP စနစ်တို့ကို ထောက်ပံ့ပြီး၊ Resuming Downloads ကိုလဲ လုပ်ဆောင်နိုင်သည်။ SOCKS 4,4a,5 proxy, ftp proxy, http proxy တို့နှင့်လဲ အသုံးပြုနိုင်သည်။ MultiGet ကို Install လုပ်ဆောင်ရန် Terminal တွင် အောက်ပါ command ကိုရိုက်ထည့်ပါ။

    sudo apt-get install multiget

####Usenet Clients

Usenet Clients ဆိုသည်မှာ ယခင်တုန်းက အသုံးပြုကြသော အင်တာနက်ပေါ်ရှိ Discussions Group တစ်ခုဖြစ်သည်။ယခုခေတ် အသုံးများကြသော ဖိုရမ်များ၏ ရှေ့ဆောင်လမ်းပြတစ်ခုဖြစ်သည်။ ဖိုရမ်များကဲ့သို့ပင် ပို့စ်များတင်ခြင်း၊ အခြားသူများတင်ထားသော ပို့စ်များကိုဖတ်ရှုခြင်းများ ပြုလုပ်နိုင်သည်။ဆွေးနွေးချက်များ၊ ပို့စ်များကိုသက်ဆိုင်ရာ ကဏ္ဍအသီးသီးအလိုက် စုစည်းထားပြီး newsgroupဟုခေါ်သည်။ ဆွေးနွေးချက်များကိုလည်း Threads များခွဲထားသည်။ Usenet Discussion Group မှ ဆွေးနွေးချက်များကို ဖတ်ရှုရန် Usenet Clients ဟုခေါ်သော ဆော့လ်ဝဲများသုံးရန် လိုအပ်သည်။

####Pan
[Pan](http://pan.rebelbase.com/) Pan သည် Usenet မှ ဆွေးနွေးချက်များကို ဖတ်ရှုရန် အသုံးပြုနိုင်သည့် Gnome-based ဆော့လ်ဝဲလ်တစ်ခုဖြစ်သည်။ nzb (http://en.wikipedia.org/wiki/Nzb) binary downloader တစ်ခုလဲ ဖြစ်သည်။ Pan ကို Install လုပ်ရန် Terminal တွင် အောက်ပါ Command ကိုရိုက်ထည့်ပါ။

    sudo apt-get install pan 

####Kwooty

[Kwooty](http://kwooty.sourceforge.net/) သည် Usenet မှ ဆွေးနွေးချက်များ ဖတ်ရှုရန်အတွက် KDE4 တွင်အသုံးပြုနိုင်သည့် ဆော့လ်ဝဲတစ်ခုဖြစ်သည်။ nzb (http://en.wikipedia.org/wiki/Nzb) binary downloader တစ်ခုလဲဖြစ်သည်။ Kwooty ကို Install လုပ်ဆောင်ရန်အတွက် လိုအပ်သော Files များ၊ PPA repositories များ၊လမ်းညွှန်ချက်များကို Kwooty website တွင် ကြည့်ရှုနိုင်ပါသည်။

###Instant Messengers

mIRC, Gtalk ကဲ့သို့ ချက်တင်လုပ်ခြင်း၊ စကားပြောခြင်း၊video calling များလုပ်ဆောင်နိုင်သော
ဆော့လ်ဝဲတစ်မျိုးဖြစ်သည်။

####Empathy

[Empathy](http://live.gnome.org/Empathy) ဆိုသည်မှာ Open Source IM ဆော့လ်ဝဲလ်တစ်ခုဖြစ်ပါသည်။ ဤဆော့လ်ဝဲသည် Ubuntu (Gnome) အသုံးပြုသော desktop များတွင် ပုံမှန်ပါဝင်သော ဆော့လ်ဝဲတစ်ခုလည်းဖြစ်သည်။

    sudo apt-get install empathy

####Pidgin

[Pidgin](http://www.pidgin.im/) ဆော့လ်ဝဲလ်သည် Open Source IM ဆော့လ်ဝဲလ်တစ်ခု ဖြစ်သည်။ ဤဆော့လ်ဝဲလ်သည် Ubuntu (Gnome) အသုံးပြုသော desktop များတွင် ပုံမှန်ပါဝင်သော ဆော့လ်ဝဲလ်တစ်ခုလည်းဖြစ်သည်။ ယခုလက်ရှိ Empathy ကိုသာ ပုံမှန် အစားထိုးသုံးလျက်ရှိသော်လည်း မြန်မာပြည်၏ MPT လိုင်းနှင့် အခြားသော Proxy ထည့်သွင်းရသော လိုင်းများအတွက်သင့်တော်သည်။

    sudo apt-get install pidgin

#####အသုံးပြုပုံ

- Add Account လုပ်ပါ။
- Basic Tab ထဲမှာ အောက်ပါအတိုင်းဖြည့်ပါ။

```
**Login Options**
protocol    : XMPP
username    : gmailaccount (@gmail ဖြည့်ရန်မလိုပါ)
Domain      : gmail.com
```

- Advanced Tab တွင် ```Force old (port 5223) SSL``` ကိုအမှန်ခြစ်ပေးပါ။
- ```Connect port``` တွင် ```443``` ဖြည့်ပါ။
- ```Connect server``` တွင် ```talk.google.com``` ဖြည့်ပါ။
- အားလုံးပြီးလျှင် Add ကိုနှိပ်ပါ။

ပြီးလျှင် ချိတ်ဆက် အသုံးပြုနိုင်ပါသည်။

####Kopete

[Kopete](http://kopete.kde.org/) ဆိုသည်မှာ Kubuntu Os (KDE) အတွက် default ပါဝင်သော ချက်တင်ဆော့လ်ဝဲဖြစ်သည်။

    sudo apt-get install kopete

#####Kopete Styles

Kopete အတွက် [ပုံစံ](http://www.kde-look.org/index.php?xcontentmode=24x26) ကို ထည့်သွင်းပြီး Kopete တွင် မိမိနှစ်သက်ရာ ပုံစံများကို အောက်ဖော်ပြပါနေရာတွင် ပြောင်းလဲနိုင်ပါသည်။

    Kopete > Settings > Configure > Chat Windows > Style > Get New...

#####GoogleTalk on Kopete

Kopete ကိုအသုံးပြုပြီး [GoogleTalk](http://www.google.com/talk/about.html) Instant Messaging အသုံးပြုနိုင်သော်လည်း VOIP ကို အသုံးမပြုနိုင်သဖြင့် အသံဆက်သွယ်ခြင်း ရမည်မဟုတ်ပါ။ Jabber Protocol ကိုသုံးထားသည်။ ဤနေရာတွင်လေ့လာပါ [GoogleTalk instructions](http://www.google.com/support/talk/bin/answer.py?answer=57557).

####Konversation (IRC client)

Konversation (http://konversation.kde.org/) သည် kubuntu တွင် default ပါဝင်သော IRC ချက် ဆော့လ်ဝဲလ်ဖြစ်သည်။ mIRC အလားတူဆော့လ်ဝဲလ် တစ်ခုဖြစ်သည်။

    sudo apt-get install konversation

####aMSN

aMSN သည် MSN ရဲ့ client ဆော့ဝဲကဲ့သို့   အသုံးပြုနိုင်သော ဆော့ဝဲတစ်ခုဖြစ်သည်။ Pidgin တွင်လည်း အလားတူသုံးနိုင်သည်။

    sudo apt-get install amsn

သင့်အင်တာနက်လိုင်းအနေဖြင့် အဆင်ပြေနိုင်မပြေနိုင် မသိသော်လည်း ဖိုင်များ လွယ်ကူစွာ
ဆွဲယူကူးပြောင်းနိုင်မှုကို Ubuntu Geek (http://www.ubuntugeek.com/how-to-enable-drag-and-drop-capabilities-to-amsn.html) တွင် ဖတ်ရှုနိုင်သည်။

####Emesence

[Emesence](http://www.emesene.org/) သည် ရိုးရှင်းသောပုံစံဖြင့် ပြုလုပ်ထားသော MSN messager တစ်ခုဖြစ်သည်။ အလားတူပင် [#Pidgin l Pidgin] တွင်လည်း အသုံးပြုနိုင်ပါသည်။

    sudo apt-get install emesene

####Videoconferencing and VOIP

ယခုအခါ Videoconferencing နှင့် Voice Over Internet (VOIP) တို့တို Application တစ်ခုတည်းအဖြစ်  ပေါင်းစပ်လာပြီဖြစ်သည်။ တချို့ဆိုလျှင် internet ချိတ်စပ်မထားသော ဖုန်းများကိုပင် အသက်သာဆုံး နှုန်းထားဖြင့် ခေါ်ဆိုနိုင်နေပြီဖြစ်သည်။ 

####Ekiga

ယခင် Gnomemeeting ဟုသိခဲ့ကြသည့် [Ekiga](http://www.gnomemeeting.org/) သည် SIP အား အပြည့်အဝလိုက်နာသည့် function အပြည့်အစုံပါ VOIP နှင့် Video စနစ်ပါ အသုံးပြုနိုင်သော ပရိုဂရမ်ဖြစ်သည်။

    sudo apt-get install ekiga


####Skype

[Skype](http://www.skype.com/) သည် Ekiga ကဲ့သို့ VOIP နှင့် Video စနစ်သုံး ဆက်သွယ်ရေး
ပရိုဂရမ်ဖြစ်သော်လည်း Open-Source မဟုတ်ပါ။ Skype ဆက်သွယ်မှုများအား [guide](http://help.ubuntu.com/community.SkypeRecordingHowto)

Install ပြုလုပ်နိုင်ရန် package တချို့ လိုအပ်ပါသည်။

    sudo apt-get install libqt4-dbus libqt4-network libqt4-xml

နောက်ဆုံးထွက် ဗားရှင်းအား ရယူရန်နှင့် 32 -bit ဗားရှင်းအား download နှင့် install ပြုလုပ်ရန်

```
wget -O skype-ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
sudo dpkg -i skype-ubuntu-current_i386.deb
sudo rm skype-ubuntu-current_i386.deb
```

ယခင်က အချို့ သုံးစွဲသူများသည် ၎င်းတို့၏ မိုက်ခရိုဖုန်းများအား 2.1.0.47 နောက်ပိုင်း ဗားရှင်းများတွင် 	သုံးစွဲ၍ မရသောကြောင့် အောက်ဖော်ပြပါ command များ သုံးခဲ့ကြသည်။

```
wget -O skype-ubuntu-current_i386.deb http://download.skype.com/linux/skype-debian_2,1.0.47-1
sudo dpkg -i skype-ubuntu-current_i386.deb
sudo rm skype-ubuntu-current_i386.deb
```

######နောက်တစ်နည်း

```
wget -O skype-ubuntu-current_amd64.deb http://download.skype.com/linux/skype-ubuntu-intrepid
sudo dpkg -i skype-ubuntu-current_amd64.deb
sudo rm skype-ubuntu-current_amd64.deb
```

#####How to install Skype on a 64-bit system

Skype အား 64-bit system များတွင် install ပြုလုပ်နည်း 64-bit system အတွက် Skype ၏ လက်ရှိ version သည် 32 bit module အား 64 အတွက် အသုံးပြုထားခြင်းဖြစ်သည်။ 64 bit system တွင် install ပြုလုပ်ရန်အတွက် အခြား package များအား ဦးစွာ install ပြုလုပ်ရန် လိုအပ်သည်။

```
sudo apt-get install ia32-libs lib32asound2 libqt4-core libqt4-gui bqt4 - core libqt4 - gui
```

ပြီးနောက် လက်ရှိ Skype version ၏ .deb package အား Skype website မှ download ပြုလုပ်၍ 
	install ပြုလုပ်ပါ။

    wget -O skype_ubuntu-current_amd64.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-64
    sudo dpkg -i skype-ubuntu-current_amd64.deb
    sudo rm  skype-ubuntu-current_amd64.deb

အကယ်၍ 64-bit version သည် သင့်အတွက် အလုပ်မလုပ်ပါက 32-bit version အား အသုံးပြုနိုင်သည်။

    wget -O skype_ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
    sudo dpkg -i --force -architecture  skype_ubuntu-current_i386.deb
    sudo rm  skype_ubuntu-current_i386.deb


#####Installing Skype respository

Skype ၏ respository ထည့်သွင်းခြင်းအားဖြင့်လည်း Skype အား install လုပ်နိုင်ပါသည်။
ဤသို့ပြုလုပ်ခြင်းဖြင့် auto update ပြုလုပ်ပေးသည့် အကျိုးကျေးဇူးရှိပါသည်။

-Resopsitory security key အား install လုပ်ရန် (key server အတွက် သင့် firewall ၏ port 11371
	အား ဖွင့်ထားရန်လိုအပ်သည်။

    sudo apt - key adv -- keyserver pgp.mit.edu --recv -keys 0xd66b746e


#####Skype repository,update ထည့်ခြင်းနှင့် Skype အား install ပြုလုပ်ခြင်း။

    echo deb http://download.skype.com/linux/repos,debian/ stable non-free l   sudo tee - a
    sudo apt-get update
    sudo apt-get install skype

------------------------

##Proprietary Extras
မူပိုင်ခွင့်အရ မှတ်ပုံတင်ထားသော ထပ်ဆောင်း package များ မူပိုင်ခွင့်အရ မှတ်ပုံတင်ထားသည့် software များသည် အင်တာနက် အသုံးပြုရာတွင် များစွာအထောက်အကူပြုပါလိမ့်မည်။ သို့သော် လွတ်လပ်စွာ ရယူသုံးစွဲခွင့်မရှိပါ ။ Multimedia Codecs များ၊ Java Runtime Environment နှင့် Firefox အတွက် plug-in များသည် ထိုကဲ့သို့သော software များဖြစ်သည်။

--------------------------

##Restricted Extras
###ကန့်သတ်ထားသော ထပ်ဆောင်း package များ

Ubuntu တွင် ကန့်သတ်ထားသော ထပ်ဆောင်း package များကို ထည့်သွင်းလိုလျှင် command-line Terminal တွင်  command တစ်ခုတည်း ရိုက်ထည့်ရုံဖြင့် လုပ်ဆောင်နိုင်ပါသည်။ ထို package များတွင် `Adobe Flash Player`, `Jave Runtime Environment (JRE) (sun-java-jre)` နှင့် `Firefox plug-in (icedtea)` များ, Microsoft မှ ထုတ်ဝေသော `Font` တချို့ `(msttcorefonts)`, `multimedia codecs (w32codecs or w64codecs)`, `mp3 compatible encoding (lame)`, `FFMpeg`, `extra Gstreamer codecs`, DVD decoding အတွက် package များ (`libdvdread4`, သို့သော် အခြား decoder ဖြစ်သည့် `libdvdcss2` ကို
ရယူလိုပါက ဤနေရာတွင်ကြည့်ပါ။), `unrar archiver`, `odbc` နှင့် `cabextract`များပါဝင်သည်။ ထို့အပြင် အခြားသော အကျိုးအမြတ်ရယူသည့် codecs များနှင့် `avutils (libavcodec - unstripped - 52` နှင့် `libavutil-unstripped - 49`) များကိုလည်း ထည့်သွင်းပေးမည်ဖြစ်သည်။

    sudo apt-get install ubuntu-restricted-extras  

>**မှတ်ချက်** ထည့်သွင်းခြင်း လုပ်ငန်းစဉ်အတွက် command-line Terminal တွင် လုပ်ဆောင်ချက်များပြီးဆုံးမှသာ ပြည့်စုံ၍ အလုပ်လုပ်ဆောင်နိုင်မည်ဖြစ်သည်။  ယခုဖော်ပြထားသော package အားလုံးကို Package Manager အသုံးပြု၍ ထည့်သွင်းပါက ပြည့်စုံမည်မဟုတ်ပါ။

--------------------------------

##Photos and Graphics

သင်၏ဓာတ်ပုံများကို ပြင်ဆင်ထိန်းသိမ်းခြင်း၊ ရင်သပ်ရှုမောဖွယ် 3D ပုံများနှင့် ဂရပ်ဖစ်များကို ဖန်တီးခြင်း
သို့မဟုတ် Format ဖိုင်အမျိုးအစား ပြောင်းလဲခြင်းများ ပြုလုပ်ရန်။

###GIMP (Image Manipulator)

[Gimp](http://www.gimp.org/) သည် အစွမ်းထက်သော စွမ်းရည်ပြည့်ဝသည့် free open-source ဖြစ်ပါသည်။
ဂရစ်ဖစ်များနှင့် ဓာတ်ပုံများပြင်ဆင်သည့် Adobe Photoshop နှင့်  ဆင်တူသော ဆော့ဖ်ဝဲဖြစ်ပါသည်။

    sudo apt-get install gimp

####GIMP အတွက် သီးသန့် brushe များ palette များနှင့် gradiend များရှိပါသည်။

    sudo apt-get install gimp-data-extras
 

###Dia (Diagram editor)
 
[Dia](http://live.gnome.org/Dia) သည် Gnome အတွက် ပြုလုပ်ထားသည့် GTK အခြေခံ diagram
ဖန်တီးသည့် open source ပရိုဂရမ်ဖြစ်ပါသည်။ Visio နှင့်  ဆင်တူပါသည်။

sudo apt-get install dia

###Kivio (Diagram editor)

[Kivio](http://www.koffice.org/kivio/) သည် flow-chat များနှင့် diagram များကို ဖန်တီးသည့်  open source ပရိုဂရမ်ဖြစ်ပြီး KDE အတွက် ပြုလုပ်ထားသည့် KOffice Suite တွင် ပါဝင်ပါသည်။ Dia ဖယောင်းမိတ္တူများ ပြုလုပ်၍ ရပါသည်။

    sudo apt-get install kivio

###Inkscape  Vector Illustrator

[Inkscape Vector Illustrator](http://www.inkscape.org/) သည် Illustrator ၊CorelDraw စသည်တို့နှင့် 
တူညီသည့် open source  ပုံဆွဲပရိုဂရမ်ဖြစ်ပါသည်။

    sudo apt-get install inkscape

###Digikam (Photo Organiser)

[Digikam](http://www.digikam.org) သည် ဒစ်ဂျစ်တယ် ဓာတ်ပုံများကို ပြင်ဆင် စုစည်းသိမ်းဆည်းဖို့
အလွန်အဆင်ပြေသော open source ဖြစ်ပါသည်။ install လုပ်လိုလျှင်

    sudo apt-get install digikam kipi-plugins digikam-doc

###F -spot (Photo Organiser)

[F -spot](http://htpp://f-spot.org/) သည် ဒစ်ဂျစ်တယ်ဓာတ်ပုံများကို ပြင်ဆင်စုစည်းသိမ်းဆည်းဖို့
အလွန်အဆင်ပြေသော Gnome Desktop အတွက် ပြုလုပ်ထားသည့် open source ဖြစ်သည်။ install
လုပ်လိုပါက:

    sudo apt-get install f-spot


###Google Picasa (Photo Organiser)

[Google Picasa](http://picasa.google.com.mm/linux/) သည် Digikam ကဲ့သို့ ပင်
ဓာတ်ပုံပြင်ဆင်သိမ်းဆည်းရန်ဖြစ်ပါသည်။ အွန်လိုင်းအသုံးပြုထားပါက Google web server သို့ 
တိုက်ရိုက်ပုံများကို upload လုပ်နိုင်ပါသည်။ အသေးစိတ်သိလိုပါက Picasa for Linux FAQ
(http://picasa.google.com/linux/faq.html) တွင် ကြည့်ပါ ။ Picasa 2.7 Download
(http://picasa.google.com/linux/download.html#picasa27) နေရာတွင် ကိုယ်တိုင် install လုပ်နိုင်သည့်
.deb ဖိုင်ရရှိနိုင်ပါသည်။

###Shotwell (Photo Organiser)

[Shotwell](http://www.yorba.org/shotwell/) အလွယ်တကူ ကြည့်ရှု ထိန်းချုပ်နိုင်မည့် ဆော့ဝဲတစ်ခုဖြစ်ပါသည်။  ဤနေရာ (http://www.youba.org/shotwell/install/) တွင် အသေးစိတ် ကြည့်ရှုပါ။

#####Terminal မှ သွင်းရန်

    sudo add-apt-repository ppa:yorba/ppa
    sudo apt-get update
    sudo apt-get install shotwell

###Tesseract (Optical Character Reader)

Tesseract (http://code.google.com/p/tesseract-ocr/) သည် command-line ဖြင့် အသုံးပြုနိုင်သည့် optical character reader တစ်ခုဖြစ်ပါသည်။ Install  ပြုလုပ်ရန်:

    sudo apt-get install tesseract -ocr

[Ocropus](http://code.google.com/p/ocropus/) သည် Tesseract ကို အသုံးပြုထားသည့် document - analysis engine တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်:

    sudo apt-get install ocropus

###Xsane (Scanning utility)

[Xsane](http://www.xsane.org/) သည် Scan ဖတ်ရန် အသုံးပြုနိုင်သည့် ဆော့ဝဲလ်တစ်မျိုးဖြစ်ပါသည်။ Xsane ကို  Install လုပ်ရန် Terminal တွင် အောက်ပါ Command ကို ရိုက်ထည့်ပေးပါ။

    sudo apt-get install xsane


###Gnome - Scan (Scanning Utility)

[Gnome - Scan](http://projects.gnome.org/gnome-scan/) သည် Scan ဖတ်ရန် အသုံးပြုနိုင်သည့်
ဆော့ဝဲလ်တစ်မျိုးဖြစ်ပါသည်။ Gnome - Scan ကို Install လုပ်ရန် Terminal တွင် အောက်ပါ Command
ကို ရိုက်ထည့်ပါ။

    sudo apt-get install gnomescan 


###Gwenview (Image Manipulator)

Gwenview (http://gwenview.sourceforget.net/) သည် KDE တွင် ဓာတ်ပုံများကြည့်ရန် အသုံးပြုနိုင်သောဆော့လ်ဝဲ တစ်မျိုးဖြစ်သည်။ ပုံများကို rotate လုပ်ခြင်း၊ crop လုပ်ခြင်း၊ resize လုပ်ခြင်း စသည့်အခြေခံတည်းဖြတ်မှုများလည်း ပြုလုပ်နိုင်သည်။ Gwenview ကို Kubuntu တွင် defaultအနေနှင့် ထည့်သွင်းထားသည်။ (K menu - Graphics - Gwenview Image Viewer) Gwenview ကို Installလုပ်လိုပါက Terminal တွင် အောက်ပါ Command ကို ရိုက်ထည့်ပါ။

    sudo apt-get install openclipart

##Screencasts and Desktop Recording

Coming Soon!!!

------------------------

##Video Applications

###Webcam Applications

ဤဆော့ဝဲများသည် Webcam အသုံးပြုသောဆော့ဝဲများဖြစ်ပါသည်။မိမိတို့ပုံများကို Effect များ ထည့်သုံး၍ 
အလွယ်တကူအသုံးပြုနိုင်သော ဆော့ဝဲများဖြစ်သည်။

####Cheese
[Cheese](http://projects.gnome.org/cheese/) သည် Gnome-based webcam
 ဆော့ဝဲတစ်ခုဖြစ်ပြီး ဆော့ဝဲ ၍ window size ကိုလဲ လိုအပ်သလို ပြုလုပ်အသုံးပြုနိုင်ပါသည်။

Terminal မှ သွင်းရန်

    sudo apt-get install cheese

####Kamoso
 
[Kamoso](https://kde-apps.org/content/show.php/Kamoso?content=111750) သည်
KDE-base webcam ဆော့ဝဲတစ်ခုဖြစ်သည်။

    sudo apt-get install kamoso

####Camorama
[Camorama](http://camorama.fixedgear.org/index.php) သည် Cheese ကဲ့သို့သော webcam 
ဆော့ဝဲတစ်ခုဖြစ်ပြီး Gtk based ဆော့ဝဲတစ်ခုဖြစ်သည်။

    sudo apt-get install camorama

####Xawtv

[Xawtv](http://git.linuxtv.org/xawtv4.git) သည် Cheese ကဲ့သို့သော webcam
ဆော့ဝဲတစ်ခုဖြစ်ပြီး Gtk based ဆော့ဝဲတစ်ခုဖြစ်သည်။ ScreenCasts ပြုလုပ်ရန် အသုံးတည့်သော 
အမျိုးအစားဖြစ်သည်။

Click on X in the window bar-Advanced -No Border(ticked)

    sudo apt-get-install xawtv

ဤဆော့ဝဲများကို Gnome/KDE Ubuntu နှင့် Kubuntu များတွင် အသုံးပြုနိုင်ပါသည်။

-----------------------------------------

##Office Suites

###Open Office

[Open Office](http://www.openoffice.org) ကို Ubuntu တွင် ပုံမှန်အနေဖြင့် ထည့်သွင်းပြီးဖြစ်သည်။ ပါဝင်သော ဆော့ဝဲများနှင့် နှိုင်းယှဉ်ပြရလျှင် --Writer (Word ကဲ့သို့ သုံးနိုင်သည်),Presentation (PowerPoint ကဲ့သို့  သုံးနိုင်သည်),Calc spreadsheet (Excel ကဲ့သို့ သုံးနိုင်သည်) , နှင့် Base relational database (Access ကဲ့သို့ သုံးနိုင်သည်)

####Word 2007 အား Open Office တွင်အသုံးပြုခြင်း

နောက်ဆုံးထွက် Open Office  သည် .docx ဖိုင် (Word 2007) ဖိုင်များအား ပုံမှန်အတိုင်း အသုံးပြုနိုင်ပြီ ဖြစ်သည်။

###Libre Office

[Libre Office](https://www.libreoffice.org/) သည် free and open source (GPL-licensed) office suite တစ်ခုဖြစ်ပြီး ယခင်က OpenOffice နှင့် အတူတူပင်ဖြစ်သည်။ Install ပြုလုပ်ရန်:

    sudo add-apt-repository ppa:libreoffice/ppa
    sudo apt-get update
    sudo apt-get install libreoffice libreoffice-gnoma

###KOffice

[KOffice](http://www.koffice.org/) သည် KDE project ၏ တစိတ်တဒေသဖြစ်ပြီး OpenOffice suite ၏ လုပ်ဆောင်ချက်များအား OpenOffice လိုင်စင်အောက်မှ မဟုတ်ဘဲ အသုံးပြုနိုင်ရန်ဖြစ်သည်။ ဤ program အား မည်သည့် ubuntu ဗားရှင်းတွင်မဆို အသုံးပြုနိုင်သည်။ Install ပြုလုပ်ရန်

    sudo apt-get install koffice

###Abi Word

[Abi Word](http://www.abisource.com/) သည် လျှင်မြန်ပြီး စုပေါင်းလုပ်ဆောင်နိုင်သော စာစီစာရိုက်စနစ်ဖြစ်သည်။ နောက်ဆုံးထွက် ဗားရှင်းအား ကြည့်ရန် [Abi Word website](http://abisource.com/com/wiki/Install-on-Ubuntu) ကို သွားပါ။ Repositories မှ install လုပ်ရန်

    sudo apt-get install abiword

###Xournal

[Xournal](http://xournal.sourceforge.net/) သည် အခမဲ့ (GPL-licensed) ဖြစ်ပြီး မှတ်စု ရေးသားခြင်း။ ပုံကြမ်းဆွဲခြင်း (သို့မဟုတ်) stylus အသုံးပြု၍ ဂျာနယ်များ သိမ်းဆည်းခြင်းများအတွက် GTK/Gnome အား အခြေခံထားသည့် အသုံးချ software ဖြစ်သည်။ Install ပြုလုပ်ရန် universe repositories အား enable ပြုလုပ်ထားရမည်။

    sudo apt-get install xournal

###PDF Files

[PDF](https://en.wikipedia.org/wiki/Portable-Document-Format) ဖိုင်သည် Adobe Acrobat (အခြားe-book readers များတွင် ဖတ်ရှုနိုင်သော) Format တစ်ခုဖြစ်သည်။ Ubuntu တွင် PDF ကဲ့သို့ ဖိုင်များအတွက် အသုံးဝင်သည့် program အများအပြားရှိပါသည်။ Synaptic Package Manager တွင် pdf ကို ရိုက်၍ ရှာဖွေကြည့်ပါ။

####Print to a PDF File

(K) Ubuntu သည် မည်သည့် Document (စာရွက်စာတမ်း) ကိုမဆို PDF Format သို့ အလိုအလျောက် ထုတ်ခွင့်ပြုပါသည်။ မည်သည့် application မှမဆို File- Print -Print to File - Output:PDF

####View a PDF document

[Evince](http://projects.gnome.org/evince/) သည် PDF ဖိုင်များ ကြည့်ရှုရန်အတွက်
အလိုအလျောက် ထ﻿ည့်သွင်းပြီးသားဖြစ်သည်။ PDF ဖိုင်များသည် Evince နှင့် အလိုအလျောက်ဖွင့်နိုင်သည်။ ထို့ကြောင့် PDF ကို click  လုပ်လိုက်ပါက (Nautilus ကဲ့သို့သော File manager မှ ဖွင့်ပါက) Evince နှင့် အလိုအလျောက်ပွင့်မည်ဖြစ်သည်။ Evince ကို ဤသို့လည်း စတင်အသုံးပြုနိုင်သည်။


####Menu- Office - Evince

???

####Print PDF documents

The CUPS Print manager has a plugin to seamlessly print PDF documents. Install:

	sudo apt-get install cups-pdf

???

####Scan to a PDF file

[Gscan2pdf](http:// gscan2pdf.sourceforge.net/) is a utility to do exactly that: scan to a PDF file. Multiple options for scanning can be set.Install:

	sudo apt-get install gscan2pdf

####PDF -Shuffler (PDF file management)

[PDF - Shuffler](http://sourceforge.net/projects/pdfshuffler/files/) is a free GTK-based utility to manipulate multiple PDF files,allowing individual pages or entire PDF documents to be re-arranged, rotated, merged, or deleted. This is an essential tool for working with PDF files.Install:

	sudo apt-get install pdf-shuffler

Run:

	Menu - Office - PDF - Shuffler

####Max View (PDF File management)

[Max View](http://sourceforge.net/projects/maxview/) is utility to capture , manipulate and rearrange,and print `.pdf` and `.max` files. Written in Qt, it is similar in some respects to Paperport. [Download](http://sourceforge.net/projects/max view 0.7-2/) and install the `.deb` package (use i386 instead of amd64 if using a 32-bit OS):

	wget - O maxview current.deb http://sourceforge.net/projects/maxview/files/maxviewo.7-2/maxvie
	sudo dpkg- i  maxview current .deb

Start Max View in a GUI by creating a menu item with the Command: maxview
/home/user, where /home/user is the directory in which you wish Max View to start.

####PDF edit (PDF File editor)

[PDF edit](http://pdfedit.petricek.net/en/index.html) is a free (GPL - licensed), Qt - based PDF  file editing and manipulation program that uses a GUI for editing.Install:

	sudo apt-get install pdfedit

####Import PDF files into a word processor

####Import PDF files into Open Office Writer

[PDF files can be imported](htt://extensions.services.openoffice.org/project/pdfimport) into the OpenOffice Writer word processor as a hybrid document ( not a scanned character document ) by installing:

	sudo apt-get install openoffice.org-pdf import

####Import PDF files into K Word

Kword is the Word Processor package in K Office.It allows the importing of PDF files by 
default.

####PDF- X Change (PDF file editor)

[PDF-X Change](http://www.tracker-software.com/product/pdf-xchange-viewer) is a free
Windows-based application to view,modify,or perform simple editing of PDF files.It works under Wine.

-------------------------------

##Personal Information Managers

Coming Soon !!!

you can contribute.

###Groupware

Groupware တွင်  ဝေမျှသုံးသော ပြက္ခဒိန်များ၊ Email server စုစည်းထားမှုများ၊ အစုအသင်းများ၏ လိပ်စာ စာရင်းများ၊ အသင်းအဖွဲ့များ၏ စီမံကိန်းများ နှင့် အသင်းအဖွဲ့များအတွင်း message ပို့ခြင်းများ ပါဝင်သည်။ ၎င်းတို့သည် LAMP (သို့) အလားတူ ဆာဗာများ တစ်ခု (သို့) တစ်ခုထက်ပို၍ လိုအပ်သည်။

####Groupware Servers

Groupware servers များမှာ Server platform ပေါ်တွင် အသုံးပြုရန် ရည်ရွယ်ထားခြင်းဖြစ်သည်။
သင့်အနေဖြင့် သီးသန့် အုပ်စုဖွဲ့ ဆော့ဝဲလ်ဆာဗာတစ်ခုအတွက် (အမြန်နှုန်းကောင်းစေရန်အတွက်) Ubuntu server version အား တပ်ဆင်ထားသင့်သည်။

###Kolab

[Kolab](http://www.kolab.org/) သည်အပြည့်စုံဆုံးသော  Open- source groupware ဖြစ်ပြီး platform မျိုးစုံအတွက် ဖြန့်ချီထားသည်။ ၎င်းတို့သည် Ubuntu (Evolution အပါအဝင်) KDE/Kunbuntu (Kcontact အပါအဝင်) တို့နှင့် ကောင်းစွာ ပေါင်းစပ်အလုပ်လုပ်နိုင်သည်။   ၎င်းသည် အခမဲ့၊ GPL လိုင်စင်ဖြင့် ပွင့်လင်းရင်းမြစ်ဖြစ်သော်လည်း (အခြားအုပ်စုဖွဲ့ ဆော့ဝဲများနှင့် မတူသည့်အချက်မှာ) စီးပွားရေးလုပ်ငန်းသုံးအတွက် အကူအညီရခြင်းပင်ဖြစ်သည်။  ၎င်းသည် ကြီးမားသော အဖွဲ့အစည်းများအတွက် အသုံးပြုနိုင်သည့်အပြင် Outlook (MS -Exchange) နှင့် Mozilla တို့နှင့်လည်း တွဲဖက်နိုင်သည်။ သို့သော်ဂျာမန်ထုတ်ဖြစ်သည့်အတွက် အင်္ဂလိပ်ဘာသာဖြင့် အသုံးပြုနည်းတွင် အကန့်အသတ်များ ရံဖန်ရံခါ ရှိတတ်သည်။ 

Kolab ဝက်ဘ်ဆိုက်တွင် ရင်းမြစ်မှ တပ်ဆင်ပုံ (ယခုလက်ရှိ ဗ.၂.၂) အတွက် ညွှန်ကြားချက်များ ပေးထားသည်။ ဗားရှင်း ၂.၂ တွင် Horde ဝက်ဘ်ပုံစံပါဝင်သည်။ လက်ရှိ ဘီတာအဆင့် ဒီဘီရန်းအတွက် ညွှန်ကြားချက်များမှာ [HERE](http://wiki.kolab.org/index.php/Debian) - Administrators - Kolab-Installation (သို့) OpenPkg အတွက် ညွန်ကြားချက်များမှာ [HERE](http://files.kolab.org/server/release/kolab-server-2.2.4/ix86-debian5.0/1st.README)

>**မှတ်ချက်**  Kolab သည်   ၎င်းကိုယ်ပိုင် ဆာဗာအစိတ်အပိုင်းများကို အသုံးပြုခြင်းဖြင့် 
Kolab ကို သီးသန့်ဆာဗာပေါ်တွင် အသုံးပြုခြင်းသည် အကောင်းဆုံးဖြစ်သည်။ သို့သော်လည်း မတူညီသော port များကို ရွေးချယ်ပေးခြင်းဖြင့် အခြားသော ဆာဗာမိုဂျူးများဖြင့် ပဋိပက္ခ ဖြစ်ခြင်းကို ရှောင်လွှဲကာစက်တစ်လုံးတည်းပေါ်တွင် အခြားသော ဆာဗာများကိုပါ တပ်ဆင်အသုံးပြုနိုင်သည်။  

compiler နှင့်အခြားသော လိုအပ်သည့် အရာများကို တပ်ဆင်ရန်

	sudo apt-get install build-essential

####Kolab Ubuntu package

အသုံးပြုနည်း မပါဝင်သေးသော Kolab version အသစ် (v.2.2) Ubuntu/ Kubuntu အတွက်လည်း ရှိပါသည်။ တပ်ဆင်ရန်မှာ

	sudo apt-get install kolabd

####Manual Kolab installation

Kolab တပ်ဆင်ရန်အတွက် ဖိုလ်ဒါတစ်ခုဆောက်ပါ။ ၎င်းကို အားလုံး အသုံးပြုခွင့်ပေးပါ။

	sudo mkdir/ kolab
	sudo chmod 777 / kolab

**Optional**: kolab ကို   ၎င်း အတွက် ကိုယ်ပိုင် အပိုင်းတွင် တပ်ဆင်လိုပါက ဦးစွာ အပိုင်းသစ် အရင်ပြုလုပ်ပါ။ (ဥပမာ - Gparted ကို သုံး ၍ ) ထို့နောက်  ၎င်းအပိုင်းအတွက် နာမည်ပေးပါ။

	sudo rdisk - 1

၎င်းသည် `/dev/sda3` ကဲ့သို့ ဖြစ်ရမည်။ အဆိုပါ `/deb/sda3` (သင်ပြုလုပ်သောအပိုင်း ) ကို `/etc/fstab` ပြုလုပ်ခြင်းအားဖြင့်  `/kolab` အဖြစ်တင်ပါ။

	sudo nano / etc /fstab 

ထို့နောက် နောက်တစ်ကြောင်း ထပ်ပေါင်းပါ။

	/dev/sda3/kolab  ext3   defaults , rw  0  0

ထို့နောက် restart ပြုလုပ်ခြင်းဖြင့် အမှား ကင်းခြင်း ရှိမရှိ စစ်ဆေးပါ။ kolab အား download ပြုလုပ်ထားသည့်  နေရာတွင်  folder တစ်ခုပြုလုပ်ပါ။ လက်ရှိ  Kolab file များအား Download ပြုလုပ်ရန်  Folder တစ်ခု တည်ဆောက်ပါ။

	cd /tmp
	mkdir   /kolabtmp

နာက်ဆုံးထွက်ရှိသည့်  Kolab file များအား Download ပြုလုပ်ပါ။

	cd /tmp/kolabtmp

	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/ix 86-debian4.0
	
	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/sources/

Root အနေဖြင့် sudo-s ကို အသုံးပြုကာ Kolab အား install ပြုလုပ်ပါ :

	sudo-s
	sh install - kolab.sh 21  l  tee kolab - install .log

သင့် ကွန်ပျူတာအား restart ပြုလုပ်ပါ။ Kolab service များအား ရပ်ဆိုင်း၍  Configuration utility ကို ဖွင့်ပါ။

	sudo /kolab/bin/openpky rc all stop
	sudo /kolob/sbin/kolab bootstrap -b

သင့်အနေဖြင့် မိမိ၏ အချက်အလက်များဖြစ်သည့် host ၏ အမည် ၊ (၎င်း ကို  hostname - f ဖြင့် သိနိုင်သည်) domain အသေးစိတ်အချက်အလက် စသည်တို့အား ဤအဆင့် မပြုလုပ်မီတွင် သိရှိထားသင့်ပါသည်။ Kolab သည် slabd open LDAP server တို့ကို အသုံးပြုမည်ဖြစ်သောကြောင့် [Open LDAP](http://www.openldap .org /) နှင့် [LDAP](http://en.wikipedia.org/ wiki /LDAP) ၏ အခြေခံအချက်အလက်များနှင့် ရင်းနှီးကျွမ်းဝင်မှု မရှိသေးပါက သင့်အနေဖြင့် လေ့လာထားသင့်ပါသည်။

Kolab ၏ service များအားလုံးအား ပြန်လည်စတင်ပါ။

	sudo / kolab /bin /openpkg rc all start

Manager အား အသုံးပြု ၍ bootstrap configuration တွင် ထည့်သွင်းထားသည့် password ဖြင့် web
administrator interface သို့ Login ပြုလုပ်ပါ။

	http://yourhost.yourdomain.name/admin/

###Citadel

[Citadel](http://www.citadel.org/) သည် အသင့်သုံး open source groupware ဖြစ်ပြီး KDE နှင့် Kolab-1 နှစ်မျိုးလုံးဖြင့် တွဲဖက်အသုံးပြုနိုင်သည်။ လွန်ခဲ့သည့် နှစ်ပေါင်း ၂၀ကျော်မှ Bulletin - board ပုံစံ framework အား အသုံးပြုထားသောကြောင့်  ၎င်းသည် KDE , Gnome နှစ်မျိုးစလုံးဖြင့်ရ ဝက်ဘ် အခြေပြု ပုံစံလည်း သုံးစွဲနိုင်သည်။ WebDAV နှင့်လည်း တွဲဖက်နိုင်ပြီး Thunderbird ဖြင့် လည်း အသုံးပြုနိုင်သည်။

####Install the Citadel server:

	sudo apt-get install citadel-server

####Install the Citadel client:

	sudo apt-get install citadel-client

####Install both:

	sudo apt-get install citadel-suite

####eGroupware

[eGroupware](http://www.egroupware.org/) သည် အခြေခံခိုင်မာ တည်ငြိမ်သော (GPL လိုင်စင်ဖြင့်) ပွင့်လင်းရင်းမြစ် အုပ်စုဖွဲ့ ဆော့ဝဲလ်ဖြစ်ပြီး LAMP (ဦးဘန္တု ဆာဗာဖြင့် တပါတည်း ပါရှိသော ဆာဗာ) နှင့် Postfix mail (နှစ်မျိုးစလုံးကို ဦးတည်ထည့်သွင်းထားသင့်ပါသည် )ပေါ်တွင် အခြေခံထားသည်။ ဗားရှင်းအသစ်ကို မကြာသေးမီကပင် ရရှိနိုင်ပြီး ဂျာမနီမှ ကော်ပိုရိတ်စပွန်စာဖြင့် စီးပွားရေးလုပ်ငန်းသုံး ဗားရှင်းတို့ပါဝင်သည်။ Clients များဖြင့် တွဲဖက်အသုံးပြုနိုင်မှုမှာ များစွာတိုးတက်လာပါသည်။ eGroupware သည် အစုအဖွဲ့ ဆော့ဝဲလ်များအားလုံးတွင် အလွယ်ကူဆုံးနှင့် အမြန်ဆုံးသော တပ်ဆင်ချိန်ကို ပေးစွမ်းနိုင်ပါသည်။ အားနည်းချက်မှာ လက်ရှိ ဗားရှင်းအတွက် အသုံးပြုနည်းအများစုကို အင်္ဂလိပ်ဘာသာဖြင့် မရရှိနိုင်သေးခြင်းပင်ဖြစ်သည်။

####Open - Xchange

[Open - Xchange](http://www.open-xchange.com/home.html) သည် ပုဂ္ဂလိကပိုင် 
အသင်းအဖွဲ့ ဆော့ဝဲလ် (MS - Exchange ကို အစားထိုးရန် ရည်ရွယ်သည်) ဖြစ်ပြီး ၎င်းကို အဖွဲ့အစည်းပုံစံသစ်ဖြင့် ထုတ်ဝေခြင်းကို စီးပွားဖြစ် ဗားရှင်းပေါ်တွင် အခြေခံထားခြင်းဖြစ်သည်။ နောက်ဆုံး `.deb` package သည် Hardy Heron 8.04 အတွက် ဖြစ်သည်။ ၎င်းသည် အခြားသော clients များ ဖြစ်သည့် Kontact,Outlook,Palm PDAs များဖြင့်လည်း တွဲဖက်အသုံးပြုနိုင်သည်။ ပြည့်စုံသော တပ်ဆင်ပုံညွှန်ကြားချက်များကို ဝက်ဘ်ဆိုဒ်တွင် လေ့လာနိုင်သည်။

####Open Guoupware

[OpenGroupware](http://www.opengroupware.org/) သည် postgre SQL ဒေတာဘေ့စ်အပေါ်တွင် အခြေပြုထားသော အစုအဖွဲ့ ဆော့ဝဲလ် ဖြစ်သည်။ ၎င်းတွင် စီးပွားဖြစ်ပုံစံနှင့် ပွင့်လင်းရင်းမြစ်ပုံစံ (၂၀၀၈ တွင်တိုးတက်မှု ရပ်ဆိုင်းသွားသည် )ရှိသည်။ အသစ်မထွက်တော့သောကြောင့် တပ်ဆင်မှုကို Source မှ တိုက်ရိုက် ထည့်သွင်းရမည်။ အသေးစိတ်ကို ဝက်ဘ်တွင်ကြည့်ပါ။

####Zarafa

[Zarafa](http:// zarafa.com/?q=en/content/community -O) သည် ဥရောပ၏ ဦးဆောင် MS-Exchange အစားထိုး အုပ်စုဖွဲ့ ဆော့ဝဲလ်ဖြစ်သည်။  ၎င်းသည် ယခင်က ပုဂ္ဂလိကပိုင် ၊နောက်ပိုင်း (မှတ်ပုံတင်အမှတ်မှလွဲ၍) GPL လိုင်စင်ဖြင့် ပွင့်လင်းရင်းမြစ် အဖွဲ့အစည်းပုံစံကို ၂၀၀၈တွင် ထုတ်လုပ်ခဲ့သည်။ ဒေါင်းလုပ် ရယူနိုင်သည့် အချက်အလက်များကို ဝက်ဘ်ဆိုက်တွင် ဖော်ပြထားသည်။

####Zimbra

[Zimbra](http://www.zimbra.com/downloads/os-download.html) သည် ပုဂ္ဂလိကပိုင် အုပ်စုဖွဲ့ ဆော့ဝဲလ်ဖြစ်ပြီး (ယခု VMWare မှ ပိုင်ဆိုင်သည် ) ပွင့်လင်းရင်းမြစ် အဖွဲ့အစည်းပုံစံကို ထုတ်ပေးထားသည်။ လက်ရှိတွင်အခမဲ့ပေးသော်လည်း အဖွဲ့အစည်းပုံစံတွင် ကန့်သတ်ချက်များရှိပြီး GPL လိုင်စင်မပေးပေ။ တင်သွင်းလိုက်သော ပြောင်းလဲမှုများ၊ပါဝင်ရေးသားမှုများသည် VMWare ၏ ပိုင်ဆိုင်မှုများဖြစ်သွားသည်။  [Zimbra wiki](http://wiki.zimbra.com/wiki/Main-Page) ကိုကြည့်ပါ။ Lucid Lynx 10.04 LTS အတွက် ဘီတာဗားရှင်းကို ၆၄ဘစ် အသုံးပြုသူများအတွက် ရရှိနိုင်ပြီး အဟောင်း Hardy 8.04 ကိုလည်းအသုံးပြုနိုင်ပါသည်။

####School Tool

[School Tool](http://www.schooltool.org/) သည် အခြေခံနှင့် အလယ်တန်းအဆင့် ကျောင်းများအတွက် ပြက္ခဒိန်၊ ပညာရည်မှတ်တမ်း ၊ကျောင်းခေါ်ချိန် ၊ကျောင်းသား အချက်အလက် သိမ်းဆည်းရာများအတွက် ပွင့်လင်းရင်းမြစ် အုပ်စုဖွဲ့ဆော့ဝဲလ် ဖြစ်သည်။ ၎င်းကို ဦးဘန္တု မှ စပွန်ဆာပေးထားသော Shuttleworth ဖောင်ဒေးရှင်း၏ အကူအညီဖြင့် ဖန်တီးခဲ့ခြင်းဖြစ်သည်။တပ်ဆင်ရန်အတွက် ညွှန်ကြားချက်များကို ကြည့်ပါ။ 

	[installation instructions](http://book.schooltool.org/htmlhelp/install.html)

####Sugar CRM Community Editon

[Sugar CRM](http://www.sugarcrm.com/crm/download) သည် ဖောက်သည်ဆိုင်ရာ စီမံခန့်ခွဲမှုစနစ်ဖြစ်ပြီးအရောင်းအင်အားစုများ (အရောင်း ၊ဈေးကွက်မြှင့်တင်ရေး၊ ထောက်ပံ့ရေး၊ စီမံခန့်ခွဲမှု ၊ အချိန်ခွဲဝေမှုများ) အကြားတွင် ပေါင်းစပ်ညှိနှိုင်းရာတွင် သုံးလေ့ရှိသည်။ Sugar CRM အဖွဲ့အစည်းပုံစံကို ကျယ်ကျယ်ပြန့်ပြန်သုံးစွဲကြသည်။ LAMP ဆာဗာကို ဦးစွာတပ်ဆင်သင့်သည်။ 

	sudo tasksel install lamp-server 

Sugar CRM ကို `/var/www` သို့ ဖြည်ထုတ်ပါ။ ထို့နောက် http://localhost/SUGAR-FOLDER/ သို့ Login ဝင်ပါ။ အခြားရွေးချယ်စရာအဖြစ် SugarCRM ဆာဗာအသစ်ကို LAMP နှင့် 
ှSugarCRM အဖွဲ့အစည်းပုံစံ အသင့်ပါပြီး တပ်ဆင်ရန် (ဘိုင်နာရီ) [instrallation](http://www.sugarcrm.com/crm/download#installers) ပုံစံဖြင့်လည်း ရနိုင်ပါသည်။


####Guoupware Clients

အုပ်စုဖွဲ့ ဆော့ဝဲလ်များသည် Kontact/KMail/, Mozilla Thunderbird (သို့) SeaMonkey တို့ဖြင့် ဆက်သွယ်မှုများ ဆောင်ရွက်နိုင်ကြသည်။

####Evolution Exchange 

Evolution Exchange သည် MS  Exchange 2000 2003 သို့ (Outlook Web Access ) ကို အသုံးပြု၍ ဆက်သွယ်နိုင်သည်။ Install -

	sudo apt-get install evolution-exchange

####Kontact Personal Information Manager

Kontact Personal Information Manager တကိုယ်ရည်သုံး အချက်အလက်မန်နေဂျာသည် ဦးဘန္တု တွင်တပါတည်းပါဝင်ပြီးဖြစ်ပြီး အခြားသော အစုဖွဲ့ ဆော့ဝဲလ်များဖြင့် ကောင်းစွာအလုပ်လုပ်နိုင်သည်။ interfaces with many [groupware servers](http://kontact.kde.org/groupwareservers.php).

####KDE Groupware Wizard

KDE အုပ်စုဖွဲ့ဆော့ဝဲလ် အလိုအလျောက်ဆောင်ရွက်မှု  Kubuntu သည် အလိုအလျောက်ဆောင်ရွက်မှု (Script) ဖြင့် အုပ်စုဖွဲ့ ဆော့ဝဲလ်ဆာဗာနှင့် clients (Kontact/Kmail စသည်များ ) ကို ဆက်သွယ်နိုင်စေရန် ကူညီပေးသည်။ ယခုလက်ရှိ ထောက်ပံ့နိုင်သော အုပ်စုဖွဲ့ ဆော့ဝဲလ်များမှာ Kolab, eGroupware, SUSE Linux Openexchange နှင့် Novell Groupwise တို့ဖြစ်ကြသည်။

####Zimbra Desktop 

[Zimbra Desktop](http://www.zimbra.com/products/desktop.html) သည် Zimbra ဆာဗာအတွက်အသုံးပြုနိုင်သည်။ Zimbra Desktop FQA များ ကို ကြည့်ပါ။ ပိုမိုသိရှိလိုပါက Ubuntu Forums Zimbra Desktop Installation [thread [1]](http://ubuntuforums.org/showthread.pmp?p=10634207)

####Oracle Calendar Desktop Client

[Oracle Calendar Desktop Client](http://www.oracle.com/technology/products/cs/user_info/ocalendar/desktop_index.html) သည် oracle အုပ်စုဖွဲ့ ဆော့ဝဲလ် နှင့် ဒေတာဘေ့စ် နှင့် အသုံးပြုရန်အတွက် ပုဂ္ဂလိကပိုင် ပြက္ခဒိန်ဆော့ဝဲလ် ဖြစ်သည်။ Oracle Calendar Desktop Client ကို ဒေါင်းလုပ်ဆွဲရန် 

	wget  http://ww.k_state.edu/infotech/calendar/oracle_10_clients/DesktopClients/Linux/callinu

ဖြည်ထုတ်ရန် 

	tar_xvf cal_linux_1011.tar.gz

ဖြည်ထုတ်ပြီးသော ဖိုင်များကို ဖိုလ်ဒါထဲသို့ နေရာပြောင်းပါ။

	cd Cracle Calendar_inst/

ဖိုင်များကို ပြင်ဆင်ပါ။

	mv cal_linux cal_linux.bak; cat cal_linux.bak l seds/export LD_ASSUME-KERNEL/ #Xport LD_ASSUME_KERN

ခွင့်ပြုမှုကို ပြင်ဆင်ပါ။

	chmod +x gui_install.sh cal_linux

GUI ဖြင့် ထည့်သွင်းမှုကို စတင်ပါ။

	sudo sh gui_install.sh

--------------------------------

##အစုအဖွဲ့ ပြက္ခဒိန်များ

###DAViCal Calendar Server

[DA Vi Cal](http://wiki. davical. org/ w/ Main_ Page) သည် [CalDAV](http://en.wikipedia.org/wiki/CalDAV), postgre SQL, Apache php တို့ကို အခြေခံထားပြီး MozillaThunderbird/Lightning/Sunbird,Evolution နှင့် အခြားသော ပြက္ခဒိန် client များဖြင့် ကောင်းစွာအလုပ်လုပ်နိုင်သည်။ install-

	sudo apt-get install davical

[အသေးစိတ်အချက်အလက်များ](http://wiki.davical.org/w/Ubunty_Maverick)

###Darwin Calendar Server

[Darwin Calendar Server](http://trac.calendarserver.org/) ပြက္ခဒိန် ဆာဗာသည် Apple ၏ [CalDAV](http://en.wikipedia.org/wiki/CalDAV ) ပွင့်လင်းရင်းမြစ် port ကို အခြေခံထားသော ပြက္ခဒိန်ဆာဗာ ဖြစ်ပြီး  Mozilla Thunderbird/ Lightening/ Sunbird/ Evolution နှင့် အခြားသော ပြက္ခဒိန် client များဖြင့် ကောင်းစွာအလုပ်လုပ်နိုင်သည်။ ရှင်း ၁.၂ ကို သိမ်းဆည်းထားသော နေရာများမှ တပ်ဆင်ရန်မှာ (အသေးစိတ်ညွှန်ကြားချက်များကို ဝက်ဘ်ဆိုက်တွင် ကြည့်ရှုပါ။ )

	sudo apt-get install calendarserver


###WebCalaendar

[WebCalaendar](http://www.k5n.us/webcalaendar.php?topic=About) သည် [ICS](http://en.wikipedia.org/wiki/I Calendar) ကို အခြေခံထားသော အုပ်စုဖွဲ့ ပြက္ခဒိန်များအတွက် ဆာဗာဖြစ်ပြီး အမျိုးမျိုးသော ဒေတာဘေ့များဖြင့် တွဲဖက်သုံးနိုင်သည်။  PHP ဖြင့် ရေးသားထားပြီး Sunbird/Thunderbird
(Lightning) , Apple iCal, and Evolution ﻿စသည့် clients များဖြင့် တွဲဖက်သုံးနိုင်သည်။ နောက်ဆုံးဗားရှင်းကို [RSS]( http://en.wikipedia.org/wiki/RSS ) clients သုံးကာ ကြည့်ရှုနိုင်သည်။ နောက်ဆုံး ဗားရှင်း (၁.၂) ကို တပ်ဆင်ရန် ဝက်ဘ်ဆိုဒ် နှင့် [wiki](http://www.k5n.us/wiki/index.pmp?title=Main_Page)
ကို ကြည့်ပါ။ ဗားရှင်းအဟောင်း (၁.၀၅) ထည့်သွင်းရန် 

	sudo apt-get install webcalendar

-------------------------------------

##Mail Servers

###Postfix/Dovecot (Mail Server)

[Postfix](http://www.postfix.org/) သည် ပွင့်လင်းရင်းမြစ် မေးဆာဗာဖြစ်သည်။ ၎င်းသည် [Dovecot](http://www.dovecot.org/) , ပွင့်လင်းရင်းမြစ် [IMAP](http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol) [POP3](http://en.wikipedia.org/wiki/Post_Office_Protocol) ဆာဗာများဖြင့် တိုက်ရိုက်ချိတ်ဆက်သည်။ ထပ်မံသိရှိလိုပါက official [Ubuntu documentation](http://help.ubuntu.com/11.04/serverguide/C/email_services.html) တွင် ကြည့်ပါ။ dovecot - postfix metapackage သည် အစိတ်အပိုင်းများ တပ်ဆင်ပြီး Maildir (mail spooling) ဖိုလ်ဒါစနစ်ကို အသုံးပြုနိုင်ရန်အတွက် ချိန်ညှိမှုဆိုင်ရာ ဖိုင်များကို ပြုပြင်သည်။ Imap and Pop3 မိုဂျူး၊ SMTP နှင့် SASL/TLS (သက်သေခံလက်မှတ်ပါသော) များကို အလိုအလျောက်တပ်ဆင်သည်။

	sudo apt-get install dovecot - postfix

###iRed Mail

[iRed Mail](http://code.google.com/p/iredmail/wiki/installation_on_Ubuntu) သည် Dovecot, Postfix, a choice of Open LDAP (with phpLDAPAdmin) or MySQL ဒေတာဘေ့စ်၊
ဝက်ဘ်အခြေပြု မေးလ်အတွက်  Roundcubemail or Squirrelmail ၊ phpAdmin, Postfix Admin, and A Wstats တို့ကို ပါဝင်သော package ဖြစ်သည်။ ၎င်းသည် Lucid 10.04 LTS တွင် အကောင်းဆုံးဖြစ်စေရန်စီမံထားပြီး ဆာဗာအသစ်ပေါ်တွင် တပ်ဆင်ရန် အကောင်းဆုံးဖြစ်သည်။ (၎င်းသည် အီးမေးလ် ဆိုင်ရာ ချိန်ညှိမှုဖိုင်များစွာကို မူလအနေအထား ဖြစ်စေရန် ပြုပြင်သောကြောင့်ဖြစ်သည် ) ၎င်း၏ အဖွဲ့အစည်းပုံစံတွင် စီးပွားဖြစ်ထုတ်လုပ်သော ပုံစံ၏ အရည်အသွေးများစွာပါဝင်သည်။

-----------------------------

##Financial Software

For a brief introduction, see this list of 10 Linux financial tools [here](http://ubuntudoctor.com/content/news/10-linux-financial-tools).

###KMyMoney (Personal Fiance Management)

[KMyMoney](http://kmymoney2.sourceforge.net/index-home.html) ကို ကျွမ်းကျင်အကောင့် (Accountants) သမားတွေ အသုံးပြုသလို အသုံးပြုနိုင်ပါသည်။ KMyMoney မှာလည်းပဲ MyMoney နှင့် Intuit Quicken ကဲ့သို့ ငွေစာရင်းတွေကို  double - accounting နဲ့ အသုံးပြုနိုင်သလို၊ လုပ်ငန်းအတွက်လဲ သက်ဆိုင်ရာ အမျိုးအစားအလိုက် စီမံနိုင်တဲ့ ဆော့ဝဲလ်ဖြစ်ပါသည်။ ကို KDE Kubuntu အတွက် ပြုလုပ်ထားတာဖြစ်ပြီး Gnome/Ubuntu တို့မှာလဲ သွင်းယူအသုံးပြုနိုင်ပါသည်။Install -

	sudo apt-get install kmymoney2

###Gnu Cash (Personal Finance Management)

[GnuCash](http://www.gnucash.org/) ဟာ အခမဲ့ပေးထားတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပြီး GPL 
လိုင်စင်နဲ့ အသုံးပြုနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲ ဖြစ်ပါသည်။GnuCash မှာ ငွေစာရင်းတွေကို double-accounting နဲ့ အသုံးပြုနိုင်သလို ကျွမ်းကျင်အကောင့် (Accountants) သမားတွေကဲ့သို့ အသုံးပြုနိုင်ပါသည်။ ကို GTK - based (Gnome 2) ကို အခြေခံပြီး ပြုလုပ်ထားခြင်းဖြစ်ပါသည်။အခု နောက်ဆုံးဗားရှင်းကို source files ကနေ သွင်းယူလို့ရနေပါပြီ။ [Gnu Cash](http://www.gnucash.org/) မှာ ထည့်သွင်းမှုပုံစံတွေနဲ့ ရနိုင်တဲ့ ဗားရှင်းတွေကို တွေ့ရမှာဖြစ်ပါသည်။ Install-

	sudo apt-get install gnucash

###Skrooge (Personal Finance Management)

[Skrooge](http://skrooge.org/) ဟာ အခမဲ့ပေးထားတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပြီး GPL လိုင်စင်နဲ့ အသုံးပြုနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲဖြစ်ပါသည်။ Skrooge ကို KDE တွေမှာ အသုံးပြုနိုင်အောင် ပြုလုပ်ထားတာဖြစ်ပြီး တခြား ငွေကြေးစီမံခန့်ခွဲမှုပရိုဂရမ်တွေနဲ့ တွဲပြီး အသုံးပြုနိုင်ရန်အတွက် ဒေတာတွေကို import/export လုပ်နိုင်တဲ့လုပ်ဆောင်ချက် ထည့်သွင်းပေးထားပါသည်။ Install -

	sudo apt-get install skrooge

###Moneydance (Personal Finance Management)

[Moneydance](http://moneydance.com/) ဟာ ကဲ့သို့ စီးပွားဖြစ်ရောင်းချတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပါသည်။ Java အား အခြေပြု ဖန်တီးထားတာဖြစ်ပြီး Operation System အမျိုးမျိုးအတွက် အသုံးပြုနိုင်အောင် ဖန်တီးထားတာဖြစ်ပါသည်။ အသုံးချခွင့်လိုင်စင်အတွက်  တစ်ခုချင်းကို ဒေါ်လာ ၅၀ ကုန်ကျမှာဖြစ်ပါသည်။

###SQL - Ledger (Enterprise Fianance Management)

[SQL - Ledger ERP](http://www.sql-ledger.org/) က double-accounting စနစ်နဲ့ အသုံးပြုနိုင်ပြီး
Operation System မရွေးတဲ့ ၊ အခမဲ့ရရှိနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲဖြစ်ပါသည်။ နောက်ပြီး SQL database server (PostgreSQL/Oracle/Mysql databases) တွေကို အသုံးပြုကာ inventory ,work and purchase orders,taxes ကဲ့သို့သော လုပ်ငန်းအချက်အလက်တွေကို ခန့်ခွဲနိုင်တဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပါသည်။ ကိုအသုံးပြုမယ်ဆိုရင် ဝဘ်ဘရောက်ဇာ (Internet exploer ,Mozilla Fox ) ကနေတစ်ဆင့် အသုံးပြုရမှာဖြစ်ပါသည်။ ကို ကျယ်ပြန့်စွာ အသုံးပြုနိုင်ပြီး ဘာသာစကားအများစုကိုလဲ အထောက်အပံ့ပေးထားပါသည်။ Install -

	sudo apt-get install sql-ledger

--------------------------------------

##Wiki software

မပြင်ဆင်ရသေးပါ။ မကြာမှီ ပြင်ဆင်မည်။

you can contribute

###Wiki 

software allows an organization to have a manual that can be edited by a number of collaborators.Wikipedia is the best known example.

###Media Wiki

[Media Wiki](http://www.mediawiki.org) is the free. မကြာမီပြင်ဆင်ဖြည့်စွတ်မည်။

###Twiki

[Twiki](http://twiki.org) is an open source wiki engin used by many small to medium size companies internally. မကြာမှီပြင်ဆင်ဖြည့်စွတ်မည်။

	sudo  apt-get  install   twiki


###Moin Moin

[Moin Moin](http://moinmo.in/) is free ,open source (GPL-Licensed) wiki မကြမှီပြင်ဆင်ဖြည့်စွတ်မည်။

	sudo  apt-get  install  python-moinmoin

###Tiddly  Wiki

[Tiddly Wiki](http://www.tiddlywiki.com/)is an open source personal wiki. မကြာမှီပြင်ဆင် ဖြည့်စွတ်မည်။

-------------------------------

##Wed  Publishing

###Drupal (Web  content  publishing)

[Drupal](http://drupal.org/)သည် website များဖန်တီးခြင်းနှင့်ပူးပေါင်းဆောင်ရွက်ခြင်းတို့တွင် 
အသုံးပြုနေကြသည့်tool  များထဲတွင် ထိပ်ဆုံးမှရပ်တည်နေသည့် open-source  တစ်ခုဖြစ်သည်။ရိုးရှင်းသော  website  များမှသည်အလွန်ရှုပ်ထွေးသော website များအထိ အချိန်အနည်းငယ်ပေးလေ့လာရုံဖြင့် ဖန်တီးရေးဆွဲနိုင်သည့် module အခြေပြု wetside ဖန်တီးသည့် toolဖြစ်သည်။ စတင်သုံးစွဲနည်းတွင် သတင်းအချက်အလက်များ စုံစုံလင်လင် ရာယူနိုင်ပါသည်။ Drupal အသုံးပြုရန်အတွက် LAMP server အား 
(Install မလုပ်ရသေးပါက Install ပြုလုပ်ရန်လိုအပ်ပြီး Drupal နှင့် တပါတည်း Install  ပြုလုပ်နိုင်ပါသည်။ Drupal ကို MySQL database (LAMP ရှိ M) နှင့်အလွယ်တကူ အသုံးပြုနိုင်ပြီး PostgreSQL( Install 
ပြုလုပ်ထားပါက ) နှင့်လည်း အသုံးပြုနိုင်ပါသည်။


####Drupal 17

Drupal 17 ၏ Debian package အား [ဤနေရာတွင်](https://packages.debian.org/sid/all/drupal7/) ရရှိနိုင်ပါသည်။ သင့် system (32 bit သို့မဟုတ် 64 bit) အတွက် package အား download ပြုလုပ်ကာ package
အား Synaptic သို့မဟုတ် Kpackage Kit စသည့် package manager များ အသုံးပြုပြီး  Install ပြုလုပ်နိုင်သည်။ (K) Ubuntu OS အသစ်တွင် တိုက်ရိုက် Install ပြုလုပ်နိုင်ရုံသာမက Debian respository ကိုပါ (Download
page တွင် ဖော်ပြထားသည့် လမ်းညွှန်ချက်အတိုင်း ) ထည့်သွင်းနိုင်ပြီး Install ပြုလုပ်နိုင်သည်။

-Drupal6 မှ Drupal7 သို့ပြောင်းလဲရန်အတွက် [ဤလမ်းညွှန်ချက်](http://drupal.org/node/570162) များအတိုင်း ပြုလုပ်နိုင်ပါသည်။


####Drupal6 (Web content publishing)

Drupal6 အား package အဖြစ်ရယူနိုင်ပြီး  `command - line terminal` မှ လည်းရရှိနိုင်သည်။

	sudo apt-get install drupal6

install ပြုလုပ်ပြီးပါက( ဖြစ်လာနိုင်သည့်  ပြသနာအနည်းငယ်အား အောက်တွင်ဖော်ပြထားသည် ) apache2
server အား restart ပြုလုပ်ပါ။

	sudo/etc/init.d/apache2 restart

သင့် browser မှတစ်ဆင့် installation အား အပြီးသတ်ပေးပါ။

	http://localhost/drupal6/install.php

Install ပြုလုပ်ခြင်းအတွက် သင့် browser မှ တစ်ဆင့် ဤ installation tips များအားဖတ်ရှုပါ။ ပြီးနောက် Durpal site building tip များအား ကြည့်ရှုပါ။ Drupal /Ubuntu အသုံးပြုသည့် Group အား Drubuntu တွင်
တွေ့ရှိနိုင်ပါသည်။

####Installation quirks

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

###WordPress

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


###Joomla (Web content publishing)

[Joomla](http://www.joomla.org/) သည် website များ ပြုလုပ်ရာတွင် ရိုးရှင်းသည့် ပုံစံများမှ ရှုပ်ထွေးသော ပူးပေါင်းဆောင်ရွက်များအထိ အသုံးပြုနိုင်သော စွမ်းအားမြင့် open source tool ဖြစ်သည်။ စတင်အသုံးပြုရန် [info for beginners](http://docs.joomla.org/Beginners) ကို ကြည့်ရှုသင့်သည်။

---------------------------------

##Scribus (Desktop publishing)

[Scribus](http://www.scribus.net/) သည် desktop publishing အတွက် professional တစ်ခုအဖြစ် အသုံးပြုနိုင်သော open-source package တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install scribus

## Plone (Content Management System)

[Plone](https://plone.org/) သည် ကမ ္ဘာအနှံ့ရှိ လုပ်ငန်းကြီးများတွင် အသုံးပြုနေသည့် content management system ဖြစ်ပြီး platform မျိုးစုံတွင် အခမဲ့ အသုံးပြုနိုင်သော open source (GPL - licensed ) system ဖြစ်သည်။ Installer ကို [ဒီနေရာ](http://plone.org/products/plone) တွင် ရယူနိုင်သည်။ Python ကို ပြောင်းလဲထားသောကြောင့် အချို့အသုံးပြုသူများအနေဖြင့် Jaunty တွင် အခက်အခဲတွေ့နိုင်ပါသည်။

##Gallery (Photo album website)

[Gallery](http://gallery.menalto.com/) သည် PHP ကို အခြေပြုထားပြီး ဓာတ်ပုံ အယ်လ်ဘမ်များအား website တွင် ပြသနိုင်အောင် ပြုလုပ်ပေးသည့် tool တစ်ခုဖြစ်သည်။ Drupal အတွက် Gallery 2 Drupal interface အား ရရှိနိုင်ပါသည်။ Install ပြုလုပ်ရန်

[php BB (Forums) php BB](http://www.php BB.com/) သည် Forum များတည်ဆောက်ရန် အသုံးပြုသည့် အခမဲ့ open source platform တစ်ခုဖြစ်သည်။ LAMP server (သို့မဟုတ်) PostgreSQL database အား install ပြုလုပ်ထားရန် လိုအပ်သည်။ Install ပြုလုပ်ရန်အတွက် universe repositories အား enable ပြုလုပ်ထားရန် အထူးလိုအပ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install phpbb3

##Distance teaching

###Moodle

Moodle သည် အွန်လိုင်း သင်ကြားရေး cource များ hosting ပြုလုပ်နိုင်ရန်အတွက် အခမဲ့ open source platform တစ်ခုဖြစ်သည်။ Webinar software ဖြင့်လည်း တွဲဖက်အသုံးပြုနိုင်သည်။ LAMP server အား Install ပြုလုပ်ထားရန် (sudo tasksel install lamp-server) လိုအပ်သည်။ Moodle ၏ အခမဲ့ theme များအား ဤနေရာတွင် ရယူနိုင်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get moode

Moodle အတွက် Database server software (mysql-server-) ထည့်သွင်းလိုပါက ဖော်ပြပါ လမ်းညွှန်ချက်များအား လုပ်ဆောင်ပါ။ Moodle အား ထည့်သွင်းထားသည့် computer ပေါ်တွင် database အား တည်ဆောက်၍ localhost option အား acept လုပ်ပါ။ လိုအပ်ပါက Moodle configuration အား တည်းဖြတ်ပါ။

	sudo gedit/etc/moodle/config.php

လိုအပ်ပါက `Moodle apache 2 configuration file` အား တည်းဖြတ်ပါ။

sudo gedit/etc/moodle/apache.conf

Browser မှတဆင့် install ပြုလုပ်ခြင်းအား အဆုံးသတ်ပါ။ (unattended install ပြုလုပ်ခြင်းမှာ ပိုသင့်တော်ပါသည်။)

`http://localhost/moodle/admin` 

စုံလင်စွာလေ့လာရန်အတွက် အသေးစိတ်အချက်အလက်များတွင် ကြည့်ရှုပါ။

###Claroline

[Claroline](http://www.claroline.net/) သည် e-learning course များ hosting ပြုလုပ်ရန်နှင့် ကျောင်းသား/ကျောင်းသူများ အွန်လိုင်းတွင် ပူးပေါင်းလုပ်ဆောင်နိုင်ရန်အတွက် ပြုလုပ်ထားသည့် အခမဲ့ open-source platform တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်အတွက် LAMP server အား install ပြုလုပ်ထားရန်လိုအပ်သည်။ installation အတွက် source file အား ၎င်း website တွင်ရယူနိုင်ပြီး လမ်းညွှန်ချက်များအား [ဤနေရာတွင်](http://www.claroline.net/documentation/tutorials.html) တွေ့နိုင်သည်။

###Dokeos

[Dokeos](http://www.dokeos.com/) သည် အခမဲ့ သင်ကြားရေး platform တစ်ခုဖြစ်ပြီး ဆေးပညာဆိုင်ရာ ပုံများ၊ case presentation များပါ ပါဝင်သည်။ ဥရောပတွင် ကျယ်ကျယ်ပြန့်ပြန့် အသုံးပြုနေကြပါသည်။

--------------------------------

##Software Development

###Kompozer Web Development Editor

[Kompozer](http://kompozer.net/) is a [Gecko](http://en.wikipedia.org/wiki/Gecko_(Layout_engine))

	sudo apt-get install kompozer

###Quanta Plus (Web IDE )

[Quanta Plus](http://quanta.kdewebdev.org/)

	sudo apt-get install quanta kompare kxsldbg cervisia

###Netbeans IDE

[Netbeans](http://www.netbeans.org/features/) is a free open-source

	sudo apt-get install netbeans

###BlueFish Web Development Editor

[BludFish](http://bluefish.openoffice.nl/) is a GTK-based (Gnome - oriented) editor to write websites,scripts and programming code. It supports perl, Python, pHp, CSS, XML , Java, Javascript, C, SQL , and other formats.

	sudo apt-get install bluefish

###Gobby ( Multi - user development)

[Gobby]( http://gobby.0x539.de/trac/) is a free, multi - platform open source collaborative editor supporting multiple documents in one session and a multi - user chat. Install:

	sudo apt-get install gobby

###Eclipse IDE

[Eclipse](http://www.eclipse.org/home/newcomers.php) is a free open - source cross - platform integrated development environment with plug in support for a large set of programming languages, e.g. Java,C/C++,Python ,PHP.

	sudo apt-get install eclipse

Science, Technology ,and Engineering Applications

What ..you thought Ubuntu was just for pay? Also see Ubuntu Science (http://help.ubuntu.com/community/OtherSoftware) . 

-----------------------------------

##Amateur Electronics

###Arduino

[Arduino](http://www.arduino.cc/) is an open - source electronics prototyping platform based on flexible, easy - to -use hardware and software. It's intended for artists, designer ,and bobbyists interested in creating interactive objects or environments.See [this tutotial](http://www.codetorment.com/2009/11/02/tutorial-getting-started-with-arduino-ide-on-linux-ubuntu-9-10/)

### La TeX

[La TeX](http://www.latex.project.org/) is a LaTeX is a free high- quality typesetting sytstem for the production of technical and scientific documention.

#### LyX

[LyX](http://www.lyx.org/) is a WYSIWYG frontend and GUI interface useful in creating documents formatted for La TeX. Install:

	sudo apt-get install Lyx


####La TeX Reference Managers

-The standard La TeX bibliography (Bib TeX) tool can be manipulated with one of several
tools:

-nbibtex. Install:

	sudo apt-get install nbibtex

-jabref. Install:

	sudo apt-get install jabref



-biblatex. Install:

	sudo apt-get install biblatex



-kbibtex (for KDE) .Install:

	sudo apt-get install kbibtex


-[Zotero](http://www.zotero.org) is a Firefox plugin that allows culling references (and reference content ) from online references.

--------------------------------------

##Utilities

Utilities facilitate everyday tasks, such as keeping the clock up to date, archiving utilities , and more.

###Archiving Utilities

####ZIP####

The command - line terminal utility [ZIP](http://linux.die.net/man/1/zip) creates files that are compatible with the time - honored PKZIP and WinZip. It is included in (K) Ubuntu by default.
Extracting zip files can be done with unzip utility.using the -P option allows using a 
password for the files.

	zip - r - p mypassword desination.zip

Notes: The -r option indicates to include all subdirectories recursively.

####FileRoller (Archiving GUI)

[FileRoller](http://fileroller.sourceforge.net/features.html) is a GUI for many types of archival utilities.

####X-archiver (Archiving GUI)####

[Xarchiver](http://xarchiver.sourceforge.net/) is a GTK - based GUI front -end for many archiving

utilities. Install:

	sudo apt-get install xarchiver

#### Rar

Rar archives files into the proprietary .rar format.

	sudo apt-get install rar

Note: This application is a 40-day trial.

####Unrar

Unrar extracts files archived with the proprietary .rar format. A free version can be installed:

	sudo apt-get install unrar-free

or the proprietary version (also free for noncommercial use) can be installed with the ubuntu-restricted-extras package or with:

	sudo apt-get install unrar

####7-Zip

The open-source 7-Zip archive format was originally designed for Windows (and DOS) but is also available for Ubuntu. The GNU/Linux version of  7-Zip does not come with a GUI, but Ark 
can hook into 7-Zip to handle 7z archives.Install:

	sudo apt-get install p7zip-full

To allow the 7-Zip extension for Ark to extract .rar files ,also install:

	sudo apt-get install  p7zip-rar

####Hard Drive Utilities

K Disk Free (Hard drive properties monitor)

[K Disk Free](http://docs.kde.org/stable/en/kdeutils/kdf/using-kdf.html) is a KDE utility for 
monitoring free disk space,etc.

	sudo apt-get install kdf



###Clock Utilties

####Screensavers

A screensaver is useful as a security precaution as well as a power and screen element saver.
Using even a simple Blank Screen screensaver with a password can slow a potentially malicious passerby from gaining access to your keyboard and computer while you are away from your 
desk.

	Menu - System - Preferences - Screen Saver

-Set a security password:

	Screen Saver - Lock screen when screensaver is active (ticked)

###Partition Managers

Also see these tips for partitioning scheme suggetions, other partitioning tools and methods, and usage of multiple partitions for multiple OSs.

####G Parted Partition Manager

[Gparted](http://gparted.sourceforge.net/) သည် Hard Drive Partitions ခွဲရာတွင် အသုံးပြုနိုင်သော GTK(Gnome) အခြေပြု ဆော့လ်ဝဲ တစ်ခုဖြစ်ပါသည်။ KDE တွင်လည်း အသုံးပြုနိုင်ပါသည်။

-ဤဆော့လ်ဝဲကို LiveCD ပေါ်မှ အသုံးပြုပါက အကောင်းဆုံးဖြစ်ပါသည်။ နောက်ပိုင်းထွက်ရှိသော Ubuntu
LiveCD များတွင် GParted ဆော့လ်ဝဲကို ထည့်သွင်းထားပြီးဖြစ်သည်။ Ubuntu ကို စက်ထဲတွင် Install
မလုပ်ဘဲ၊ CD မှ တိုက်ရိုက် အသုံးပြုပြီး GParted ကို စတင်နိုင်ပါသည်။]

	Menu-System-Administration -GParted

-အခြားနည်းလမ်းတစ်ခုကား GParted .iso ဖိုင်ကို [ဤနေရာမှ](http://sourceforge.net/project/showfiles.php?group_id=115843package_id=271779) ရယူနိုင်ပါသည်။ ထို .iso ဖိုင်ကို GPartet LiveCD ပြုလုပ်ရန် ဤ [CD Burning Guide](http://help.ubuntu.com/community/BurningIsoHowto) ကို ဖတ်ပါ။ G Parted LiveCD
ကို အသုံးပြုပြီး partitions ခွဲနိုင်မည်ဖြစ်သည်။

-Ubuntu ကို Hard Drive အတွင်း  Install လုပ်ထားပါက Terminal တွင် အောက်ပါ Command ကို ရိုက်ထည့်ပြီး GParted ကို Install လုပ်နိုင်မည်ဖြစ်သည်။

	sudo apt-get install gparted


###System Backup and Recovery

####System Rescue and Cloning Utilities

#####System Rescue CD

[SystemRescueCD](http://www.sysresccd.org/Main_Page) is a LiveCD that includes important utilities such as GParted,Partimage,ddrescue, Rsync , and FSArchiver. Several of these utilities cannot be used from within a running partition, so using them from a LiveCD is often necessary.
[Download](http://www.sysresccd.org/Download) and [burn](http://help.ubuntu.com/community/BurningIsoHowto) the LiveCD from the website.


#####Clonezilla

[Clonezilla](http://clonezilla.org/)allows the backup or duplication of a partition for a single machine or for multiple machines over a network. (It is similar to North Ghost.)It includes
Partimage, [partclone](http://sourceforge.net/projects/partclone/),and other utilities.It is available [here](http://sourceforget.net/projects/clonezilla/files) as a LiveCD which can then be [burned](https://help.ubuntu.com/community/BurningIsoHowto).(A serious limitation of Clonezilla is
its inability to backup/restore split image files to/from multiple media (e.g.spanned DVDs/CDs),limiting its usefulness as an inexpensive cloning and distribution solution.Partition image
backup/restoration must be to/from a single hard drive,large capacity USB stick,or networked storage space)

####Disk Imaging software

[G4U](http://sourceforge.net/projects/g4u/) is a utility to image a disk bit by bit.

[G4L](http://sourceforge.net/projects/g4l/) is a  utility to image a disk bit by bit.It inkcludes a GUI interface.

#####Ubuntu Customization Kit

[Ubuntu Customization Kit](http://sourceforge.net/projects/uck) is a utility to customize a (K) Ubuntu LiveCD.Install:

	sudo apt-get install uck

####Remastering software

Debian and (K) Ubuntu Linux operating systems can be remastered and customized (using one of a number off utilities) for re-distribution.[See this Wikipedia list](http://en.wikipedia.org/wiki/List-of-rematering) for distribution among its members,while
preserving the intrinsic architecture and function of (K)Ubuntu.The customized (K) Ubuntu OS can than be distributed on a CD or a USB flashdrive. Users are then free to futher customize
the OS,or even to revent back to the original default(K)   settings. Also see the Ubuntu [wiki](http://help.ubuntu.com/community/InstallCDCustomization).

	oem-config-gtk

	sudo apt-get install oem-comfig-gtk

[Remastersys](http://sourceforge.net/projects/remastersys/Remastersys) for [Ubuntu](http://www.geekconneection.org/remastersys/ubuntu.html) .For tips, see this page. [Reconstructor](https://www.reconstructor.org/projects/reconstuctor/wiki/UserGuide). The open source engine can be [downloaded](https://www.reconstructor.org/projects/reconstutor/files) and installed a.deb package. 


***For tips,see this page.***

Run Ubuntu LiveCD from a USB pendrive

The Ubuntu LiveCD can be installed on and run from a USB pendrive. Settings ca be 
persistently saved (but the LiveCD kerned modules can not be upgraded). Programs can be
installed and run,however ,and files saved to the USB drive. (The installed programs will remain
installed). An Ubuntu Live CD is needed to do the installation. For additional info, see the [Ubuntu Community documentation](http://help.ubuntu.com/community/Installation/FromUSBStick) or the [Pendrivelinux instructions](http://www.pendrivelinux.com/creating-an-ubuntu-live-usb-from-cd/).

The USB LiveCD can be used to install Ubuntu on computers (including netbooks) that do not
have CD-ROM/DBD drives.

USB pendrives to be used to run Ubuntu should have a minimum of 2 Gb(preferably 4 Gb).If
you wish to install a fast, fully functional Linux system on a pendrive that has less memory than
that, use [PuppyLinux](http://www.puppylinux.org/) or [Lubuntu](https://wiki.ubuntu.com/Lubuntu).

###USB Creator##

You can make a LiveCD on a USB pendrive using USB Creator and either a LiveCD or an .iso
version of the LiveCD stored on your hard drive. USB Creator is installed by default in Ubuntu.
If not,install:

	sudo apt-get install usb-creator-gtk

-Run:

	Menu-System-Startup Disk Creator

Create a boot CD to allow booting from the USB drive

Many computers do not allow booting from a USB drive (but they do allow booting from the CD-ROM). You can create a CD-ROM using these [Pendrivelinux instrctions](http://www.pendrivelinux.com/make-a-usb-boot-cd-for-ubuntu-9-10/)  and set your BIOS to boot from this CD-ROM. When you boot from this CD-ROOM, it will use the bootup files on the Ubuntu USB drive you previously created (in the step above).

--------------------------------------

##System Administration##

###GRUB boot manager settings

####Grub2

Ubuntu 11.04 (Natty) တွင် boot manager အဖြစ် (customize လုပ်ရန် ရှုပ်ထွေးသော) [Grub2](http://www.gnu.org/software/grub/maunal/grub.html) ပါလာပါသည်။ (Grub2 နှင့် grub-pc သည် 
တစ်မျိုးတည်းသာ ဖြစ်သည်။) Grub2 အတွက် ညွှန်ကြားချက်များကို [Ubuntu wiki](http://wiki.ubuntu.com/Grub2) သို့မဟုတ် [Ubuntu forums](http://ubuntuforums.org/showthread.php?t=1195275) များတွင် ကြည့်ရှုနိုင်သည်။ အကြမ်းအားဖြင့်

	sudo nano /etc /default /grub
	sudo grub-mkconfig--output=/boot/grub/grub.cfg


အခြားသောနည်းလမ်းအနေဖြင့် အောက်ပါ command ကို အသုံးပြုနိုင်သည်။

	sudo update-grub


####Turn off ACPI through GRUB

The new Linux kernel , starting with Karmic ,will attempt to throttle the CPU every few seconds
based on lm-sensors read of CPU temperature and fan speed. If your hardward is not supported
by lm-sensors (like mine), this will cause your system to show down dramatically or even freeze.
As always, this is an ACPI problems, so disabling it at boot often takes of the problem.Edit
the GRUB configuration as above and add the line:

	GRUB _ CMDLINE _ LINUX =acpi=off


Grub2 background image,colors,fonts

-Grub2 အတွက် နောက်ခံပုံရိပ်များ၊ အရောင်များ ၊ Font များ [ဤနေရာတွင်](http://ubuntuforums.org/showthread.php?p=10720685#post10720685) ကြည့်ပါ။

-Grub2 တွင် မည်သည့် နောက်ခံပုံကို သုံးသည်ဖြစ်စေ အသုံးပြုမည့်ပုံကို `/boot/grub` ဖိုင်တွဲတွင် ထည့်၍ Grub2 ကို configure လုပ်ခြင်းဖြင့် အသုံးပြုနိုင်သည်။

	sudo update grub

အသုံးပြုမည့်ပုံသည် `/etc /default /grub` တွင် ရှိသည့် Grub 2 စတင်လုပ်ဆောင်ရန် သတ်မှတ်ထားသော
ပုံအရည်အသွေးနှင့် တူညီရမည်။ (ဥပမာ 1024 x 768)

-ရွေးချယ်ထားသော splashimage များကို `/usr/share/image/grub` ဖိုင်တွဲတွင် ထည့်သွင်း၍ 
  အသုံးပြုနိုင်သည်။

	sudo apt-get install grub2-splashimages

-အသုံးပြုလိုသော ပုံရိပ်တစ်ခုကို `/boot/grub` ဖိုင်တွဲတွင် ထည့်၍ splashimage အနေဖြင့်အသုံးပြုနိုင်သည်။ ဥပမာ

	sudo in -s /usr /share /images /grub /Plasma-lamp.tga/boot/grub
	sudo update-grub

####Grub 2 အား ချိုးဖောက်ဝင်ရောက်ခြင်း မပြုနိုင်ရန် ကာကွယ်ခြင်း

-Grub2 ကို ကာကွယ်ရန် အရေးကြီးသော အချက်များကို [Grub Manual](http://www.gnu.org/software/grub/manual/grub.html#Security ) တွင် ကြည့်ပါ။

-စကားဝှက်ထည့်သွင်းရန်အတွက် /etc/grut.d/40_custom configuration file တွင် အောက်ပါ command ကို ရိုက်ထည့်ပါ။
	set superusers=user1
	password_pbkdf2 user1 grub.pbkdf2.sha512.10000.biglongstring
	password user1 insecurecleartextpassword


စကားဝှက်နေရာတွင် insecurecleartextpassword အစား သင်၏ စကားဝှက် ထည့်သွင်းအသုံးပြုရပါမည်။
သို့မဟုတ် [ဤနေရာ](http://www.gnu.org/software/grub/manual/grub.html#Security) တွင် ပြထားသော pbkdf2-encrypted နည်းလမ်းကို အသုံးပြု၍ ကာကွယ်နိုင်သည်။ သင်၏ Ubuntu OS Grub2 လုံခြုံရေးနှင့် ပတ်သက်၍ အသေးစိတ်ကို ဤ [Blog](http://www.panoet.com/set-grub-2-password-protection-149) တွင် ဖတ်ရှုနိုင်သည်။

####GRUB Legacy

Boot partition တစ်ခုနှင့် အသုံးပြုရန် GRUB ၏ version အဟောင်းဖြစ်သည့် (Grub [Legacy](http://www.gnu.org/software/grub/manual/legacy/grub.html) ကို ရယူနိုင်သည်။ Grub Legacy ကို ထည့်သွင်းရန်အတွက်

	sudo apt-get install grub

-အကယ်၍ သင့်ကွန်ပျူတာတွင် operation system တစ်ခုထပ်ပိုရှိနေပါက multiple operation systems (OS) ဖြစ်နေပြီး သင်သည် Grub Legacy boot manager ကို သုံးစွဲဖူးပြီး ဖြစ်ကောင်းဖြစ်နိုင်သည်။ Grub Legacy ၏ option များကို menu.1st configuration file တွင် တည်းဖြတ်ပြင်ဆင်နိုင်သည်။ အသေးစိတ်ကို ကြည့်ရှုနိုင်သည်။

	sudo nano /boot /grub /menu.1st

(text editor အဖြစ် nano အစား gedit ကို အသုံးပြုနိုင်သည်။)

####Grub Legacy မှ data များ ရယူ၍ Grub2 တွင် ပြန်လည် အသုံးပြုခြင်း

Grub Legacy မှ data များရယူ၍ Grub2 တွင် အသုံးပြုရန်အတွက် Grub Legacy ၏ menu.1st configuration file တွင် ဤပုံစံဖြင့် မိမိ OS များကို ဖြည့်သွင်းပါ။ (menu.1st ဖိုင်ကို boot partition တွင် သိမ်းဆည်းထားသည်။)

	title Kubuntu Maverisk OS (chainloader)
	rootnoverity (hdo,6)
	kernel /boot /grub /core.img

သို့မဟုတ်

	title Kubuntu Maverick OS (chainloader)
	rootnoverify  (hdo,6)
	configfile/boot/grub.cfg


####Grub Legacy ကိုချိုးဖောက်ဝင်ရောက်ခြင်းမပြုနိုင်ရန် ကာကွယ်ခြင်း

-Grub Legacy ကိုကာကွယ်ရန် အရေးကြီးသောအချက်များကို this section of [the Grub Manual](http://www.gnu.org/software/grub/manual/legacy/grub.htm#Security) တွင် ကြည့်ပါ။

-စကားဝှက်ထည့်သွင်း ကာကွယ်ရန်အတွက် `/boot/grub/menu.1st` configuration file တွင် အောက်ပါ  command line ကို uncomment လုပ်ပါ (hash သင်္ကေတကို ဖယ်ထုတ်ပါ။)

####password topsecret

ထို့နောက် စကားဝှက်ထည့်သွင်း၍ သို့မဟုတ် [ဤနေရာ](http://www.gnu.org/software/grub/manual/legacy/grub.html1#Security ) တွင် ပြထားသော md5-
encrypted နည်းလမ်းကို အသုံးပြု၍ ကာကွယ်နိုင်သည်။ menu item များကို စကားဝှက်ဖြင့် ကာကွယ်ရန် မည်သည့် item menu ၏ ခေါင်းစဉ်အောက်တွင်မဆို ကာကွယ်ထားကြောင်း အမှတ်အသားဖြစ်သည့် lock ကို 
ထည့်သွင်းခြင်းဖြင့် လုပ်ဆောင်နိုင်သည်။

###Default Applications###

Ubuntu ၏ ယခင် version များတွင် သင် သတ်မှတ်ထားသော လုပ်ငန်းများအတွက် မည်သည့် program အား ပုံသေအသုံးပြုမည်ကို သင့်အနေဖြင့် ဤနေရာမှ ရွေးချယ်နိုင်သည်။

	Menu-System-Administration-Default Applications

(သို့မဟုတ်) 

ဖိုင်တစ်ခုအား right-click' နှိပ်၍  `Open with Other Application` ဖြင့်လည်း ရွေးချယ်နိုင်သည်။

Default Application menu သည် လက်ရှိ Ubuntu version တွင် မပါရှိတော့ပါ။ သို့သော် ဤ function အား ပြုလုပ်ခွင့်ပေးသော GUI နှင့် Ubuntu နှင့် Multiple similar Ubuntu system twesk များအတွက် 
[UbuntuTweak](http://ubuntu-tweak.com/) ကို install ပြုလုပ်၍ အသုံးပြုနိုင်ပါသည်။

	wget http://launchpad.net/ubuntu-tweak/0.5.x/0.5.8/+ download/ubuntu-tweak_0.5.8-1all.deb
	sudo dpkg -i ubuntu- tweak _ 0.5.8-1_all.deb


###Kill a process###

တစ်ခါတစ်ရံမှာ Program တစ်ခု (သို့မဟုတ်) process တစ်ခုဟာ အသုံးပြုနေစဉ်မှာပဲ ရပ်တန့် (hang)သွားတတ်ပါတယ်(ဥပမာ Firefox)။ထိုကဲ့သို့သော program (သို့မဟုတ်) process များအား kill (သို့မဟုတ်) ပိတ်ပစ်ရန်အတွက်
	
Menu-System-Administration-System Monitor-highlight the errant process-Kill process

မှပိတ်နိုင်ပါတယ်။

command line မှလည်း

	sudo killall process 

ဟုရိုက်ကာ ပိတ်နိုင်ပါတယ်။ process နေရာတွင် ရပ်တန့်နေသော program ( firefox ဆိုပါက firefox) ဟုထည့်ပေးရပါမယ်။

-------------------------

###Enabling NUM LOCK On Startup###

Menu-System-Administration-Keyboard Mouse-Keyboard-turn on Numlock on Startup


###Working with Menus#


###Create an encrypted folder###

သင့်အနေဖြင့် encrypted  ပြုလုပ်ထားသည့် အရာများပါဝင်သော folder တစ်ခု ဤလမ်းညွှန်ချက်များ 
(http://help.ubuntu.com/community/EncryptedPrivatedDirectory) အား ကြည့်ရှု၍ ဖန်တီးနိုင်ပါသည်။

Create a symlink from a file to another location

[symbolic link](http://en.wikipedia.org/wiki/Symbolic_link) (သို့) symlink ဟုလည်း သိကြသည့် သင်္ကေတလင့်သည် Linux ၏ file သို့မဟုတ် directory တစ်ခုအား တစ်နေရာမှ အခြားနေရာသို့ ညွှန်ပြသည့် နည်းလမ်းတစ်ခုဖြစ်သည်။ 
အသုံးပြုပုံ

	Ln -s /path /to /source/path/to/destination

အကယ်၍ `/path/to/destination` မှ `superuser` ဖြစ်ရန်လိုအပ်ပါက အောက်ပါ command အား အသုံးပြုပါ။

	sudo Ln-s /path /to/source /path/to/destination

ဤနည်းသည် ယခင် window user များ အကျွမ်းတဝင်ရှိကြမည့်  Shoutcut များဖန်တီးသည့် ပုံစံဖြင့် ဆင်တူသော်လည်း ပို၍ အဆင့်မြင့် (စွမ်းအားမြင့်) ပါသည်။


###Assign a root password###

Root သို့ တိုက်ရိုက် `log in`  ပြုလုပ်နိုင်ရန်အတွက်  root password ထည့်သွင်းပေးရန်လိုအပ်ပါသည်။ password ထည့်သွင်းရန်အတွက် 

	sudo passwd rood

ထို့နောက် သင့်အနေဖြင့် `su` ကို အသုံးပြု၍ root သို့သွားပါ။ ထို့နောက် root password အား ထည့်သွင်းပေးပါ။


###root password မရှိပဲ root permission အသုံးပြုခြင်း။###
Get a root prompt without using a root password
 
root password ကို မထည့်ရသေးလျှင်ဖြစ်စေ၊ မေ့လျော့သွားရင်ဖြစ်နေ အောက်က ကွန်မန်းတွေ သုံးပြုပြီး root access ရယူနိုင်ပါတယ်။

	sudo - s
	
or

	sudo su

or

	sudo bash

ဒါဆိုရင် root password သုံးမယ့်အစား လက်ရှိသုံးနေတဲ့အကောင့်ရဲ့password ကိုပဲသုံးပြုသွားပါလိမ့်မယ်။ တခြား user အကောင့်တွေကိုလဲ အောက်က ဥပမာအတိုင်း ခေါ်သုံးနိုင်ပါတယ်။

	sudo su username

File Manager ကိုအောက်က command တွေအသုံးပြုပြီး root access နဲ့ဖွင့်နိုင်ပါတယ်။

	sudo nautilus
	
or

	gksudo nautilus


Device တွေ ဖြုတ်တပ်ကို maunal ပြုလုပ်ဖို့အတွက်အောက်က ကွန်မန်းသုံးပါတယ်။

	mount /dev/hda

`hda` နေရာမှာ ကိုယ် mount လုပ်ချင်တဲ့ဟာကို အစားထိုးရမှာပါ။

unmount ပြုလုပ်ဖို့အတွက်က အောက်က ကွန်မန်းသုံးပြုပါတယ်။

	umount/dev/hda

`hda` နေရာမှာ ကိုယ် mount လုပ်ချင်တဲ့ဟာကို အစားထိုးရပါတယ်။။

-------------------------------------------------

##Networking##

တစ်ခုတည်းသော Network manager အား GUI interface ဖြင့် စတင်လုပ်ဆောင်စေနိုင်ပါသည်။ Network-Manager သည် ပုံမှန်အနေဖြင့် ပါဝင်ပြီးဖြစ်သည်။ သို့သော်လည်း အသုံးပြုသူများသည် [Wicd Network Manager](http://wicd.sourceforge.net/)  ကို ပို၍ နှစ်သက်ကြသည်။


###Network Manager

Network Manager သည် ubuntu တွင် ပုံမှန်အနေဖြင့် ထည့်သွင်းထားပြီးဖြစ်သည်။ ၎င်းသည် Notification 
နေရာတွင် internet connections (wireless APs သို့မဟုတ် wired connection တို့ကို )ချိတ်ဆက်ရန် သို့မဟုတ် အသုံးမပြုရန် ရွေးချယ်နိုင်ပါသည်။


###Wicd Network Manager###

[Wicd Network Manager](http://wicd.sourceforget.net/) is a GTK -dependent networking manager written in Python that can be used in all variants of Ubuntu. Many users (including me) report it 
to be faster and more stable than Network Manager. To avoid networking conflicts, Wicd
requires the removal of Network Manager prior to installation.

	sudo apt-get remove network-manager
	sudo reboot
	sudo apt-get install wicd


###Set a static IP address###

I have never been able to ger Network Manager to accept my static IP address settings. If you 
only use only a wire interface, you do not neekd a network manager and it can be removed.

-Remove Network Manager:

	sudo apt-get remove network-manager
	sudo reboots

-Edit the /etc /network/interfaces files:


###GPPP###

GPPP သည် ယခင် Ubuntu versions တွေရဲ့  default modem dailing application ဖြစ်ခဲ့ပါသည်။

`Menu` - `Applications` - `Internet` - `GPPP Internet Dail` - 
`up Remote Access`

Remote Access နည်းလမ်းမျိုးစုံရှိပါသည်။ VNC Sharing ကို သုံးခြင်းဖြင့် ရီမုတ်လုပ်ထားသော ကွန်ပျူတာ၏ Desktop ကို ကြည့်နိုင်၊ ထိန်းချုပ်နိုင်ပါသည်။ (Windows သုံးသူများသည် အလားတူ `(remote desktop
protocol,RDP )` ဟု ခေါ်သော သီးခြားအဖွဲ့အစည်း တစ်ခုပိုင် ပရိုတိုကောကို သုံးကြသည်။) `XDMCP (X Display Manager Control Protocol)` ဖြင့် လည်း` X-windows` ကို အခြေခံသည့် ပြီးပြည့်စုံသော Remote Login ကို ပြုလုပ်နိုင်ပါသည်။ ခွင့်မပြုသင့်သော ဝင်ရောက်ခြင်းများ ၊ဒေတာအချက်အလက် ပို့ဆောင်ခြင်းများကို 
ကာကွယ်ပေးသော သင့်တော်သည့် ကြိုတင်ကာကွယ်မှုများမရှိလျှင် `Remote Connection` သည် လုံခြုံရေးအရ အန ္တရာယ်ရှိပေသည်။ 

###SSH###

`Secure Shell` သို့မဟုတ် `SSH` လို့ခေါ်သော  network protocol တစ်ခုဖြစ်ပါသည်။ ၎င်း Protocol သည် ကွန်ပျူတာ နှစ်ခုကြားတွင် `Secure channel` (သို့မဟုတ် tunnel ) မှ တဆင့် အချက်အလက်တွေကို ဖလှယ်နိုင်ရန် 
အထောက်အပံ့ပေးပါသည်။ Encryption လုပ်ခြင်းဖြင့် သတင်းအချက်အလက်များကို တိကျလုံခြုံမှု ရှိစေပါတယ်။

OpenSSH client ကိုတော့ Ubuntu တွင် default အနေနဲ့ install လုပ်ထားပြီး အခြား `SSH server run` နေသော ကွန်ပျူတာတစ်ခုနှင့် ချိတ်ဆက်ပေးနိုင်မှာဖြစ်ပါတယ်။

------------------------------------------

##Tips Tricks##

###Run Command###

Run Command အသုံးပြုခြင်း သင့်ရဲ့ စက်အတွင်းက  Application များကို Run Command မှတဆင့် အသုံးပြုနိုင်ပါတယ်။ `Alt + 2` ကိုသုံးပါ။

###Hot Keys များအား ပိတ်ခြင်း###

ကျွန်တော့အမြင်မှာတော့ ဒါဟာ အလွန်အန ္တရာယ်ရှိတဲ့ လုပ်ဆောင်ချက်တစ်ခုဖြစ်ပါတယ်။။ အစက်လေးတစ်စက်ဟာ
ထင်မှတ်မထားတဲ့ ဘယ်လို အဖြစ်အပျက်မျိုးကို မဆို ဖြစ်သွားစေနိုင်ပါတယ်။ စိတ်မကောင်းစရာအဖြစ်နဲ့ပဲ ဒါဟာ ပြသနာတစ်ခုအဖြစ်နဲ့ Operation System ထဲမှာ ရှိနေပြီး  turn off လုပ်ဖို့လည်း ခက်ခဲပါတယ်။

`Menu` - `System` - `Administration` - `Advanced` - `Input Actions` - `General Settings` - `check` to`Disable KHotKeys daemon`

`Menu`- `System` - `Administration` - `Advanced` - `Input Actions` - `Gestures Settings` -
		`check` to  `Disable mouse gestures globally`

တကယ်လို့သင်က `Disable mouse gestures globally` ကို ရွေးချယ်ချင်ပါတယ်ဆိုရင်တော့  (တခါတရံမှာ အလုပ်မလုပ်ပါ) Desktop ပေါ်က မလိုအပ်တဲ့ Hotkey တွေကို disable လုပ်ပါ။

`Menu` - `System` - `Administration` - `Advanced` - `Keyboard Mouse` - `Keyboard Shortcuts`

ပြီးတော့ သင်က linking gestures to sticky and slow keys ကို deactivate လုပ်ချင်တယ်ဆိုရင်တော့

`Menu` - `System` - `Administration` - `Accessibility` - `Activation Gestures` - `uncheck` to - `Use
	gestures for activating sticky keys and slow keys`

မှတ်ချက်။     ။ သင့်အနေနဲ့ application အတော်များများကို အသုံးပြုမယ်ဆိုရင်  hotkeys တွေကို `disable` လုပ်ထားရပါမယ်။

`Synaptic Touchpad` မှ `hotkeys` များကတော့ 
[Ubuntu documentation](https://help.ubuntu.com/community/Synaptics/Touchpad#Ubuntu) ကို အသုံးပြုပြီး ရွေးချယ်
	turned off ပြုလုပ်နိုင်ပါတယ်။

###Associate default applications###

သက်ဆိုင်ရာ application များအား အလိုအလျောက်ပွင့်ရန်

-Dvd player အလိုအလျောက်ပွင့်လာရန်အတွက် DVD playback လုပ်ဆောင်နိုင်စွမ်းကို ဖွင့်ထားရန်လိုအပ်ပါသည်။ ပထမဦးစွာ
	
`Menu` - `System` - `Administration` - `Advanced` - `File` `Associations` - x - content - video - dvd - `Applications Preferance order` - `Add` တွင် မိမိနှစ်သက်ရာ media player အား ရွေးချယ်ပါ။ ၎င်းတွင် Blu - Ray နှင့် HD DVD 	အတွက် ဆင်တူသော  ရွေးချယ်မှုဇယားရှိပါသည်။ တစ်ခုချင်းစီအား ရွေးချယ်သတ်မှတ်ပေးပါ။

-`MPEG` နှင့် အခြား ရုပ်သံ `Format` များအတွက် အလိုအလျောက် player များသတ်မှတ်ရန်
	
`Menu` - `System` -`Administratio`n - `Advanced` - `File Associations` - `video` -`mpe`g -`Applications Preference order - Add` တွင် သင့်စိတ်ကြိုက်  `media player` ကို ရွေးချယ်ပါ။ .wmv) x -ms -wmv, သို့မဟုတ် Microsoft ၏ WMV format) ,.flv (x-flv, သို့မဟုတ် Flash video ), quicktime စသည် ရုပ်သံဖိုင်ပေါင်းများစွာအတွက် လက်ခံဖွင့်နိုင်မည့် player အားရွေးချယ်အသုံးပြုနိုင်ပါသည်။

-Audacious မှတဆင့် .pls အသံ stream များကို သတ်မှတ်ပေးရန်အတွက် Audacious:

`Menu` - `Syste`m - `Administration` - `Advanced` -`File Associatons` - `audio` - `x` -`scpls` -
	`Applications Preference order` - `Audacious` အား အပေါ်ဆုံးသို့ ရွှေ့ပြောင်း၍ (သို့မဟုတ်)ထည့်ပေးခြင်းဖြင့် လုပ်ဆောင်နိုင်ပါတယ်။

Filename Patterns Section ထဲတွင်တော့ `* .pls`  ရှိနေရန်လိုအပ်သည်။

###User စကားဝှက်အသုံးပြုရန် မလိုပဲ ဝင်ရောက်သောစနစ်###

သွားရောက်ပြင်ဆင်ရန်အတွက် (မှတ်ချက် ၊ User အတွက် password လိုအပ်နေဆဲဖြစ်ပါသည်။ )

`Menu` - `System` -`System Settings` -`Login Manager` -`Convenience` - `Enable Auto` - `Login`	(အမှန်ချစ်) - `Lock session` (အမှန်ချစ်) -`Pre` - select user: `Specified :Choose primary user`

-ဒါကို ပြုလုပ်ရင်တော့ screensaver ကို Password - Portected နဲ့တွဲပြီး လုပ်သင့်ပါတယ်။


###Program များအား bootup လုပ်စဉ် အလိုအလျောက်စတင်စေခြင်း

မည်သည့် program မဆို `~/.config/autostart folder` သို့ program သင်္ကေတ
လမ်းကြောင်း ဖန်တီးပေးခြင်းအားဖြင့် `bootup` ၌ စတင်စေလိုပါက သင်္ကေတလမ်းကြောင်း ဖန်တီးပေးရပါမည်။

	sudo in -s /usr/bin/firefox ~/.config/autostart


###Bootup /Startup service များရွေးချယ်ခြင်း

System ၏ လုပ်ဆောင်ချက်များ တိုးတက်စေရန်အတွက် Startup ပြုလုပ်စဉ်တွင် မလိုအပ်သော/ 
အသုံးမပြုလိုသော service များ စတင်ခြင်းများ မဖြစ်အောင် ကာကွယ်ရပါမည်။

-GTK အား အခြေပြုထားသော Bootup - Manager အား Install ပြုလုပ်ရန်

	sudo apt-get install bum

	
###Bootup-Manager အား အသုံးပြုရန်#
	 
`Menu` - `System` - `Bootup` - `Manager` 


###Menu item မှ Script အား အသုံးပြုခြင်း##

(password စသည့် )တုံ့ပြန်မေးခွန်းများ မေးမြန်းခြင်းများအား ဖြေဆိုရန် script တိုလေးများအား Menu item ထဲတွင် ထည့်သွင်းနိုင်ပါသည်။ အောက်တွင် SSH Negotiation ပြုလုပ်စဉ် password ထည့်ပေးနိုင်သည့် ဥပမာအား ဖော်ပြပေးထားပါသည်။ ပထမဦးစွာ အသုံးဝင်  [expect](http://linux.die.net/man/1/expect) program အား install ပြုလုပ်ပါ။

	sudo apt-get install expect

Menu item တွင် shortcut (သို့) command အသုံးပြုခြင်း ဖြစ်ပါသည်။ 

ဤ password ဥပမာသည် ssh program မှ password လိုအပ်သောအခါ sshpassword ကို သွားစေပါသည်။
Expect သည် command-line terminal မှ စာလုံးအချို့ကိုစောင့်ဆိုင်း ရယူပြီး စာများပြန်ထုတ်ပေးသည်။
ထို့ကြောင့် Menu Iten ကို terminal တွင်သာ run   စေရမည်ဖြစ်သည်။


###[SHC](Encrypt scripts)

[SHC](http://www.datsi.fi.upm.es/~frosal/) သည် code နှင့် password စသည်များကို မမြင်အောင် ပြုလုပ်ပေးပြီး ထို script များကို binary အဖြစ်သို့ ပြောင်းလဲပေးသည့် ရိုးရှင်းသော script compiler တစ်ခုဖြစ်သည်။ အသုံးပြုပုံများအား ဤနေရာတွင် (http://www.datsi.fi.upm.es/~frosal/sources/shc.html) ကြည့်ရှုနိုင်ပါသည်။ `Debian Etch respository` ကို ထည့်သွင်းခြင်းဖြင့် install ပြုလုပ်နိုင်ပါသည်။

	sudo add-apt-repository http://archive.debian.org/debian/etc main

ထို့နောက် shc package အား install ပြုလုပ်ပါ။

	sudo apt-get install shc

###Capture a screenshot 

Screenshot ပြုလုပ်ခြင်း ဤ [Tutorial](http://tips.webdesign10.com/how-to-take-a-screenshot-on-ubuntu-linux) တွင် ကြည့်ပါ။


###Desktop အား KDE  ကဲ့သို့ ပြောင်းလဲခြင်း

နောက်ဆုံးထွက် Ubuntu ဗားရှင်းတွင် Gnome desktop အား ပြုပြင်၍ cleaner KDE desktop အဖြစ် ပြင်ဆင်နိုင်ပါသည်။ (ပြုပြင်ခြင်းသည် အလွန် ကိုယ်ရေးကိုယ်တာကျသဖြင့် ဤအပိုင်းသည် လမ်းညွှန်အဖြစ်သာ ဖော်ပြပေးထားသည်။ )

`-Desktop Customization ပြုပြင်ခြင်းကို ကြည့်ပါ။`

###Ubuntu တွင်  KDE 4 Desktop အသုံးပြုခြင်း

Kubuntu တွင် အလိုအလျောက်ပါပြီးဖြစ်သော KDE4 အခြေပြု Desktop အား Ubuntu တွင် install လုပ်နိုင်ပါသည်။

	sudo apt-get  install kubuntu-desktop

KDE4 အား install လုပ်ရာတွင် အသုံးမလိုသော feature များပြားခြင်းနှင့်  Module  များအကြား လိုက်လျောညီထွေမှုမရှိခြင်း ပြသနာများကြုံတွေ့ရတတ်ပါသည်။ Login ပြုလုပ်ရာ၌ KDE (Kubuntu) Desktop ဖြင့် ဖြစ်စေ၊ Gnome (Ubuntu) Desktop ဖြင့်ဖြစ်စေ၊ ကြိုက်နှစ်သက်ရာဖြင့် ပြုလုပ်နိုင်သည်။ သို့သော်လည်း Desktop တစ်ခုချင်းစီမှ Modules ၂ခုသည်  function တစ်ခုအား လုပ်ဆောင်မည်ဆိုပါက
အခက်အခဲ(ကွဲလွဲခြင်း)များ ဖြစ်နိုင်ပါသည်။

###KDE 3 Desktop အား Ubuntu  တွင် အသုံးပြုခြင်း

သင့်အနေဖြင့် ယခင် Lucid (သို့မဟုတ်) မည်သည့် KDE 3 application မှ KDE 3 Desktop ကို Ubuntu တွင်
install လုပ်နိုင်ပါသည်။	

-ဖော်ပြပါ KDE 3 repositories အား ထည့်ပါ။

	sudo add-apt-repository ppa:kde3-maintainers

-KDE 3.5 desktop အား install လုပ်ပါ။

	sudo apt-get update
	sudo apt-get install kubuntu-desktop-kde3

-မည်သည့်  KDE 3 application ကိုမဆို install ပြုလုပ်လိုပါက package အမည်တွင်  `-kde3` ဟူသော	 စာလုံးကို ထပ်ဖြည့်ပေးရပါမည်။ အချက်အလက် အပြည့်အစုံအတွက် [Pearson Computing](http://apt.pearsoncompution.net/) ကို ကြည့်ပါ။


###Kill (end) a process 

Process (application) အား ပိတ်ခြင်း (သို့မဟုတ်) အဆုံးသတ်ခြင်း

-Frozen PC ကို ပြင်ဆင်ရန် နည်းလမ်းအတော်များများ ရှိပါသည်။ `Alt + F2` ကို နှိပ်ပါ။ ထို့နောက်  frozen Application ကို ပိတ်ရန် Killall ကို အသုံးပြုပါ။ 

ဥပမာ:

	sudo killall amarok
	sudo killall firefox

-ထစ်နေသော Graphic နှင့် ဆိုင်သည့် application များကို ပိတ်ရန်အတွက် `xkill utility` ကို သုံးပါ။`Alt+F2` ကို နှိပ်ပါ။ `xkill` ဟု ရိုက်ပြီး run ကို နှိပ်ပါ။  သင်ပိတ်လိုသော  application ပေါ်တွင် Mouse ၏ ဝဲလက်ခလုတ်ကို နှိပ်ပါ။ 

ဤနည်းဖြင့်  သင်ပိတ်လိုသည့် application များကို ပိတ်နိုင်ပါသည်။

###skill

-အခြားနည်းအနေဖြင့် `AltGr+SysRq+K (Right Alt +Print Screen + K)` ကို နှိပ်ပါ။ ဒီနည်းက သင့်ကို logout ဖြစ်စေမှာဖြစ်ပါတယ်။ တကယ်လို့ ဒီနည်းက အလုပ်မဖြစ်ဘူးဆိုရင်တော့  `Ctrl + Alt + F1` ကိုနှိပ်ပြီး login လုပ်ပါ။ ပြီးတော့ သင့် password ကို နှိပ်ပြီး run ပါ။

	sudo killall gdm
	sudo startx


###View hidden files 

Hidden File များအား ကြည့်ရှုခြင်း  Nautilus Manager မှာ ဒါလေးကို နှိပ်ပါ။

	ctrl + H

###Notification (အချက်ပြခြင်း ) တွေကို အသံဖျောက်ရန်

-အချက်ပေးသံတွေကို disable ပြုလုပ်ဖို့အတွက်

	Menu - System - Preferences - Sound -Sound Effects - Sound 	theme: -No sounds - Close

-GNOME အချက်ပေးချက်တွေဟာ အသံဖြင့် အလိုအလျောက် ဆက်စပ်နေပါတယ်။ ဒါကို သီးခြား disable ပြုရပါမယ်။
	
`Alt - F2 - gconf - editor -/apps/indicators - sound - volume _mute` (အမှန်ခြစ်ပေးပါ။ )

-Login အချက်ပေး အသံကို ပိတ်ရန်အတွက်

`Menu - System -Preferences - Startup Applications - Startup Programs - GNOME LoginSound` (အမှန် ခြစ်ဖြုတ်ပေးပါ။ ) 

`-Menu - System - Administration - Login Screen - Unlock - Play login sound` (အမှန်ခြစ်ဖြုတ်ပေးပါ။)

###Random password generator

ကျပန်း password geneartor

	-Pwgen သည် ကျပန်း password စာလုံးစုများထုတ်ပေးရန်အတွက်  အသုံးဝင်သည့် command line
	တစ်ခုဖြစ်သည်။ Kubuntu တွင် Konsole မှ တဆင့် ၊Ubuntu တွင် Terminal မှတဆင့်
အသုံးပြုနိုင်သည်။ Install ပြုလုပ်ရန် ----

	sudo apt-get install pwgen

-Pwgen အား အသုံးပြုရန်
	
	pwgen

-UUIDgen သည် ကျပန်း UUID များအား ထုတ်ပေးသည့် အသုံးဝင်သော
	အလိုအလျောက် ထည့်သွင်းပေးထားသည့် program တစ်ခုဖြစ်သည်။ အသုံးပြုရန် း
uuidgen


ဆန္ဒရှိပါက ကျပန်း UUID အား password အနေဖြင့်လည်း အသုံးပြုနိုင်ပါသည်။


###Password chceker and enforcement

[John the Ripper](http://www.openwall.com/john/) Password စစ်ဆေးမှုနှင့် အတည်ပြုမှု

John the Ripper သည် Dictionary ၏ password များအား ဖျက်ရန်အတွက် အခမဲ့အသုံးပြုနိုင်သော open source ဖြစ်ပြီး ယေဘုယျအားဖြင့် ၄သန်းခန့် ဘာသာပေါင်းစုံဖြင့် အသုံးပြုနေကြသည်။ အဘယ်ကြောင့်ဆိုသော်
ဤ program သည် ကျယ်ကျယ်ပြန့်ပြန့်နှင့် လွယ်လင့်တကူ ရနိုင်သောကြောင့် ဖြစ်ပြီး  မိမိ၏ ကွန်ပြူတာ နှင့် LAN ၏  password များအား  စစ်ဆေးခြင်း၊ လုံခြုံအောင် ပြုလုပ်ခြင်းများအတွက်လည်း ၏
အသုံးဝင်သောကြောင့်ဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install john

[Passwdqc](http://www.openwall.com/passwdqc/) သည် password များ၏ ကြံ့ခိုင်မှုအားအတည်ပြုပေးရန်အတွက် သုံးသော module တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install passwdqc


###MD5Sum###

File တစ်ခု၏ MD5 sum များအား စစ်ဆေးရန်အတွက် သုံးသော command line တစ်ခုဖြစ်သည်။

	md5sum filename

မှတ်ချက်။  ။ Filenames with spaces

###Spaces ခံ၍ အမည်ပေးထားသော File များ###

-`Spaces` ခံ၍ ရိုက်နှိပ်ထားသော File နှင့် Folder အမည်များအား မျက်တောင် အဖွင့် အပိတ်များ `( )` များ ထည့်အသုံးပြုသင့်သည်။ ဥပမာအားဖြင့် This Dir အမည်ပေးထားသော directory တစ်ခု သို့မဟုတ်
	`/home/This Dir` အမည်ရှိ directory တစ်ခုအား ပြောင်းလဲချင်ပါက အောက်ပါ command 
	အား အသုံးပြုရမည်။

	cd This Dir

သို့မဟုတ်

	cd/home/This Dir

-တစ်နည်းအားဖြင့် `backslash (/)` ကို space နေရာမှာ အစားထိုးခြင်းဖြင့်လည်း အသုံးပြုနိုင်ပါသည်။

This Dir အမည်ပေးထားသော directory တစ်ခု သို့မဟုတ် `/home/This Dir` အမည်ရှိ directory တစ်ခုအား ပြောင်းလဲချင်ပါက 

	cd This /Dir 

သို့မဟုတ်

	cd/home/This /Dir


###Alien###

[Alien](http://kitenet.net/~joey/code/alien/) သည် (Red Hat) .rpm packages များကို  (Debian).deb packages များအဖြစ်သို့ ပြောင်းလဲပေးသော ဖိုင်ပြောင်းနည်းတစ်ခုဖြစ်သည်။ ဒီနည်းဟာ စိတ်ချရတဲ့နည်းမဟုတ်သလို ပြောင်းလိုက်တဲ့ package တွေရဲ့ function တွေကို သေချာပြန်စစ်ဆေးပေးဖို့လိုအပ်ပါတယ်။ များသောအားဖြင့် စာကြောင်းတွေ ပြန်ပြောင်းပေးဖို့ လိုအပ်ပါတယ်။ Source ကနေ `(Debian).deb package` ကို ပြောင်းပေးခြင်းက ပိုပြီးစိတ်ချရပါတယ်။ Alien software ရဲ့ maintainer တွေ ကိုယ်တိုင်ကိုက important package တွေကို ဖိုင်ပြောင်းတဲ့အခါ Alien ကို အသုံးမပြုစေချင်ကြပါဘူး။ Alien ကို version နံပါတ်တွေ ပြောင်းတာကနေ ထိန်းထားချင်တယ်ဆိုရင်တော့ ဖော်ပြပါ command ကို ရိုက်ထည့်ပေးပါ။

	alien - k rpm _file _name.rpm

.rpm ကို .deb အဖြစ်ပြောင်းနည်း

	alien - d package - name .rpm

.rpm ကို .deb အဖြစ်ပြောင်းပြီး ရလာတဲ့ file ကို တစ်ခါတည်း install လုပ်ရန်

	alien - i package - name .rpm

.rpm ကို Debian အဖြစ်ပြောင်းရန်

	sudo alien - k  .rpm
	
--------------------------------

##Software Troubleshooting##

###Program အစတွင် လုပ်ပိုင်ခွင့် Error တက်ခြင်း

အကယ်၍  သင့်တွင် လုပ်ပိုင်ခွင့် Error တစ်ခုတက်လာပါက ဖော်ပြပါအတိုင်း လုပ်ဆောင်ပါ။

	sudo chown - R user /home/user

မှတ်ချက် ။    user ဆိုသော နေရာတွင် သင့် username အမှန်အား ထည့်ပေးပါ။ ဤ command သည် folder ၏ ပိုင်ရှင်အား ပြောင်းလဲပေးမည်ဖြစ်သည်။ `-R` အပါအဝင်  (recursively ) ကိုဆိုလိုပြီး folder အခွဲများပါ ပါဝင်ပါသည်။


##CD - ROM Troubleshooting##

###CD - ROM Error အားဖြေရှင်းခြင်း###

အကယ်၍ သင် CD burner အသုံးပြုပြီး  burn နေ့စဉ်အတွင်းမှာ `cdrecord has no permission to open the device` ဆိုတဲ့ Error တက်လာပါက terminal ကို ဖွင့်ပြီး

	sudo chmod 777 /dev /scd0

လို့ ရိုက်လိုက်ပါ။

မှတ်ချက်။ `/dev/scd0` နေရာတွင် သင့် device အားထည့်ပေးပါ။
မှတ်ချက်။ `chmod 777` သည် folder အား လုပ်ပိုင်ခွင့်အပြည့်အစုံပေးလိုက်သည့် universal option ဖြစ်သည်။ `777` ဆိုသော ဂဏန်းသည် ရေးခြင်း၊ ဖတ်ခြင်း ၊လုပ်ဆောင်ခြင်း စသည့် လုပ်ပိုင်ခွင့် တု့ိကို အသုံးပြုသူအား အပြည့်အ၀ ပေးလိုက်သည်ဟု အဓိပ္ပါယ် ရသည်။
