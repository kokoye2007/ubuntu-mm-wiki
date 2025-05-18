#﻿General Notes

Ubuntu လမ်းညွှန်သည် ပုဂ္ဂလိကဆိုင်ရာကုမ္ပ္ပဏီနှင့်သော်လည်းကောင်း အခြားစီးပွားရေး လုပ်ငန်းကြီးများနှင့်သော်လည်းကောင်း စီးပွားရေးအရသက်ဆိုင်မှုမရှိပါ။
Ubuntu သည် သုံးစွဲသူများကို Menu ရုပ်ပုံအသုံးချ Graphical User Interface  (GUI) နှင့်သော်လည်းကောင်း စာသားအသုံးချ command line ဆိုင်ရာ text-based command-line interface (CLI) သော်လည်းကောင်း အလုပ်များကို လုပ်ဆောင်နိုင်စေပါတယ်။ Ubuntu တွင်(command-line-interface)ကို Terminal လို့ခေါ်ပါတယ်။ Terminal ကိုစဖွင့်မယ်ဆိုရင် Menu- Applications-Accessories - Terminal စသည်ဖြင့် အဆင့်တိုင်းသွားရောက်နိုင်ပါသည်။ Terminal တွင် ခဲရောင်မျဉ်းအစက်များအတွင်း စာသားများကို ထည့်သွင်းအသုံးပြုနိုင်ပါသည်။

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

##Other Versions

လက်ရှိအသုံးပြုနေတဲ့ Ubuntu version ကိုကြည့်ချင်ရင် Terminal ပေါ်မှာ အောက်ပါအတိုင်းရိုက်ထည့်ပြီး Enter နှိပ်ပါ။

	lsb_release -a

လက်ရှိအသုံးပြုနေတဲ့ kernel ကိုကြည့်ချင်ရင်ရင်တော့ Terminal မှာ အောက်ပါအတိုင်းရိုက်ထည့်ပြီး Enter နှိပ်ပါ။

	uname -a

##Newer Versions  of Ubuntu 

Ubuntu ကို ၆လလျှင်တစ်ကြိမ်ထုတ်ဝေပြီး နှစ်စဉ် ဧပြီလနှင့်အောက်တိုဘာလတို့တွင် ထုတ်ဝေပါသည်။ Oneiric Ocelot (11.10) (http://ubuntuguide.org/wiki/Ubuntu:Oneiric), များမကြာမီ နောက်ဆုံးထွက်ပေါ်မည့် Oneiric ကို ၂၀၁၁ခုနှစ် အောက်တိုဘာလတွင် အခမဲ့ ရယူနိုင်မည်ဖြစ်ပါသည်။သို့ရာတွင် ၎င်းသည် ကာလရှည်ကြာ ထောက်ပံ့မှုပေးသည့် LTS Version မဟုတ်ပါ။

##Older Versions of Ubuntu

##Other Resources 

Ubuntu Forums (http://ubuntuforums.org/) တွင် အွန်လိုင်းဖြေရှင်းချက်များနှင့် အခြားသောအသေးစိတ်အချက်အလက်များကို ကူညီပေးရန် အဖွဲ့အစည်းများစွာ ရှိပါသည်။
ပြည်တွင်း အဖွဲ့အစည်းအနေဖြင့် Ubuntu for Myanmar (ubuntu-mm) (http://ubuntu-mm.net/) ရှိပြီး မြန်မာဘာသာဖြင့် Ubuntu အကြောင်းလေ့လာနိုင်ပါမည်။
####[ubuntu-mm.net](http://ubuntu-mm.net)
####[ask.ubuntu.com](http://ask.ubuntu.com)
####[FB Ubuntu-MM Group](http://fb.com/groups/ubuntu4mm)
####[FB Pages](http://fb.com/ubuntumm)
####[Ubuntu Myanmar LoCo Team](http://wiki.ubuntu.com/MyanmarTeam)
####[Ubuntu-MM LoCo](http://loco.ubuntu.com/teams/ubuntu-mm)

##Ubuntu Resources 

###Unity Desktop

[Unity](http://en.wikipedia.org/wiki/Unity_%28desktop_environment%29) ဆိုသည်မှာ Ubuntu တွင် အသုံးပြုသည့် နဂိုမူလပါသော Desktop ပုံစံဖြစ်ပါသည်။ (Gnome) ဂနုမ်းမှ အသုံးပြုသည့် GTK ပလက်ဖောင်းဖြင့် အဆင်ပြေသင့်တော်ပါသည်။ netbook များတွင် အသုံးပြုရန် ဒီဇိုင်းပြုလုပ်ထားသော်လည်း အခြားသော စက်ပစ္စည်းအမျိုးအစားများတွင်ပါ အသုံးဝင်စေရန် canonical မှ ပြင်ဆင်ပေးထားပါသည်။

###Gnome Project 

[Gnome 3](http://www.gnome.org/) သည် Ubuntu အတွက် ပုံစံအသစ်အနေဖြင့် ရယူနိုင်ပါသည်။ Gnome လုပ်ငန်းစဉ်များ (http://projects.gnome.org/) ကြည့်ရှု ရယူနိုင်ပါသည်။
