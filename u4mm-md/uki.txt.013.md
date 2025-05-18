bqt4 - core libqt4 - gui

ပြီးနောက် လက်ရှိ Skype version ၏ .deb package အား Skype website မှ download ပြုလုပ်၍ 
    install ပြုလုပ်ပါ။

    wget -O skype_ubuntu-current_amd64.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-64
    sudo dpkg -i skype-ubuntu-current_amd64.deb
    sudo rm  skype-ubuntu-current_amd64.deb

အကယ်၍ 64-bit version သည် သင့်အတွက် အလုပ်မလုပ်ပါက 32-bit version အား အသုံးပြုနိုင်သည်။

    wget -O skype_ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
    sudo dpkg -i --force -architecture  skype_ubuntu-current_i386.deb
    sudo rm  skype_ubuntu-current_i386.deb

###Installing Skype respository

Skype ၏ respository ထည့်သွင်းခြင်းအားဖြင့်လည်း Skype အား install လုပ်နိုင်ပါသည်။
ဤသို့ပြုလုပ်ခြင်းဖြင့် auto update ပြုလုပ်ပေးသည့် အကျိုးကျေးဇူးရှိပါသည်။

-Resopsitory security key အား install လုပ်ရန် (key server အတွက် သင့် firewall ၏ port 11371
    အား ဖွင့်ထားရန်လိုအပ်သည်။

    sudo apt - key adv -- keyserver pgp.mit.edu --recv -keys 0xd66b746e


###Skype repository,update ထည့်ခြင်းနှင့် Skype အား install ပြုလုပ်ခြင်း။

    echo deb http://download.skype.com/linux/repos,debian/ stable non-free l   sudo tee - a
    sudo apt-get update
    sudo apt-get install skype

##Proprietary Extras

မူပိုင်ခွင့်အရ မှတ်ပုံတင်ထားသော ထပ်ဆောင်း package များ

ူမူပိုင်ခွင့်အရ မှတ်ပုံတင်ထားသည့် software များသည် အင်တာနက် အသုံးပြုရာတွင် 
များစွာအထောက်အကူပြုပါလိမ့်မည်။ သို့သော် လွတ်လပ်စွာ ရယူသုံးစွဲခွင့်မရှိပါ ။ Multimedia Codecs များ၊
Java Runtime Environment နှင့် Firefox အတွက် plug-in များသည် ထိုကဲ့သို့သော software များဖြစ်သည်။

#Restricted Extras

##ကန့်သတ်ထားသော ထပ်ဆောင်း package များ

Ubuntu တွင် ကန့်သတ်ထားသော ထပ်ဆောင်း package များကို ထည့်သွင်းလိုလျှင် command-line Terminal 
တွင်  command တစ်ခုတည်း ရိုက်ထည့်ရုံဖြင့် လုပ်ဆောင်နိုင်ပါသည်။ ထို package များတွင် Adobe Flash 
Player, Jave Runtime Environment (JRE) (sun-java-jre) နှင့် Firefox plug-in (icedtea) များ ,
Microsoft မှ ထုတ်ဝေသော Font တချို့ (msttcorefonts) ,multimedia codecs (w32codecs or
w64codecs), mp3 compatible encoding (lame), FFMpeg, extra Gstreamer codecs, DVD
decoding အတွက် package များ (libdvdread4,သို့သော် အခြား decoder ဖြစ်သည့် libdvdcss2 ကို
ရယူလိုပါက ဤနေရာတွင်ကြည့်ပါ။) ,unrar archiver,odbc နှင့် cabextract  များပါဝင်သည်။ ထို့အပြင်
အခြားသော အကျိုးအမြတ်ရယူသည့် codecs များနှင့် avutils (libavcodec - unstripped - 52 နှင့် libavutil-
unstripped - 49) များကိုလည်း ထည့်သွင်းပေးမည်ဖြစ်သည်။

    sudo apt-get install ubuntu-restricted-extras  

မှတ်ချက် : ထည့်သွင်းခြင်း လုပ်ငန်းစဉ်အတွက် command-line Terminal တွင် လုပ်ဆောင်ချက်များ
ပြီးဆုံးမှသာ ပြည့်စုံ၍ အလုပ်လုပ်ဆောင်နိုင်မည်ဖြစ်သည်။  ယခုဖော်ပြထားသော package အားလုံးကို Package
Manager အသုံးပြု၍ ထည့်သွင်းပါက ပြည့်စုံမည်မဟုတ်ပါ။

#Photos and Graphics

သင်၏ဓာတ်ပုံများကို ပြင်ဆင်ထိန်းသိမ်းခြင်း၊ ရင်သပ်ရှုမောဖွယ် 3D ပုံများနှင့် ဂရပ်ဖစ်များကို ဖန်တီးခြင်း
သို့မဟုတ် Format ဖိုင်အမျိုးအစား ပြောင်းလဲခြင်းများ ပြုလုပ်ရန်။

##GIMP (Image Manipulator)

[Gimp](http://www.gimp.org/) သည် အစွမ်းထက်သော စွမ်းရည်ပြည့်ဝသည့် free open-source ဖြစ်ပါသည်။
ဂရစ်ဖစ်များနှင့် ဓာတ်ပုံများပြင်ဆင်သည့် Adobe Photoshop နှင့်  ဆင်တူသော ဆော့ဖ်ဝဲဖြစ်ပါသည်။

    sudo apt-get install gimp

###GIMP အတွက် သီးသန့် brushe များ palette များနှင့် gradiend များရှိပါသည်။

    sudo apt-get install gimp-data-extras
 

##Dia (Diagram editor)
 
[Dia](http://live.gnome.org/Dia) သည် Gnome အတွက် ပြုလုပ်ထားသည့် GTK အခြေခံ diagram
ဖန်တီးသည့် open source ပရိုဂရမ်ဖြစ်ပါသည်။ Visio နှင့်  ဆင်တူပါသည်။

sudo apt-get install dia


##Kivio (Diagram editor)

[Kivio](http://www.koffice.org/kivio/) သည် flow-chat များနှင့် diagram များကို ဖန်တီးသည့်  open
source ပရိုဂရမ်ဖြစ်ပြီး KDE အတွက် ပြုလုပ်ထားသည့် KOffice Suite တွင် ပါဝင်ပါသည်။ Dia ဖယောင်းမိတ္တူများ ပြုလုပ်၍ ရပါသည်။

    sudo apt-get install kivio


##Inkscape  Vector Illustrator

[Inkscape Vector Illustrator](http://www.inkscape.org/) သည် Illustrator ၊CorelDraw စသည်တို့နှင့် 
တူညီသည့် open source  ပုံဆွဲပရိုဂရမ်ဖြစ်ပါသည်။

    sudo apt-get install inkscape


##Digikam (Photo Organiser)

[Digikam](http://www.digikam.org) သည် ဒစ်ဂျစ်တယ် ဓာတ်ပုံများကို ပြင်ဆင် စုစည်းသိမ်းဆည်းဖို့
အလွန်အဆင်ပြေသော open source ဖြစ်ပါသည်။ install လုပ်လိုလျှင်

    sudo apt-get install digikam kipi-plugins digikam-doc


#F -spot (Photo Organiser)

[F -spot](http://htpp://f-spot.org/) သည် ဒစ်ဂျစ်တယ်ဓာတ်ပုံများကို ပြင်ဆင်စုစည်းသိမ်းဆည်းဖို့
အလွန်အဆင်ပြေသော Gnome Desktop အတွက် ပြုလုပ်ထားသည့် open source ဖြစ်သည်။ install
လုပ်လိုပါက:

    sudo apt-get install f-spot


##Google Picasa (Photo Organiser)


[Google Picasa](http://picasa.google.com.mm/linux/) သည် Digikam ကဲ့သို့ ပင်
ဓာတ်ပုံပြင်ဆင်သိမ်းဆည်းရန်ဖြစ်ပါသည်။ အွန်လိုင်းအသုံးပြုထားပါက Google web server သို့ 
တိုက်ရိုက်ပုံများကို upload လုပ်နိုင်ပါသည်။ အသေးစိတ်သိလိုပါက Picasa for Linux FAQ
(http://picasa.google.com/linux/faq.html) တွင် ကြည့်ပါ ။ Picasa 2.7 Download
(http://picasa.google.com/linux/download.html#picasa27) နေရာတွင် ကိုယ်တိုင် install လုပ်နိုင်သည့်
.deb ဖိုင်ရရှိနိုင်ပါသည်။

##Shotwell (Photo Organiser)

[Shotwell](http://www.yorba.org/shotwell/) အလွယ်တကူ ကြည့်ရှု ထိန်းချုပ်နိုင်မည့်
ဆော့ဝဲတစ်ခုဖြစ်ပါသည်။  ဤနေရာ (http://www.youba.org/shotwell/install/) တွင် အသေးစိတ်
ကြည\E1\80
