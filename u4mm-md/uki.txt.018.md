�သည့် clients များဖြင့် တွဲဖက်သုံးနိုင်သည်။ နောက်ဆုံးဗားရှင်းကို [RSS]( http://en.wikipedia.org/wiki/RSS ) clients သုံးကာ ကြည့်ရှုနိုင်သည်။ နောက်ဆုံး ဗားရှင်း (၁.၂) ကို တပ်ဆင်ရန် ဝက်ဘ်ဆိုဒ် နှင့် [wiki](http://www.k5n.us/wiki/index.pmp?title=Main_Page)
ကို ကြည့်ပါ။ ဗားရှင်းအဟောင်း (၁.၀၅) ထည့်သွင်းရန် 

	sudo apt-get install webcalendar

####Mail Servers

#####Postfix/Dovecot (Mail Server)

[Postfix](http://www.postfix.org/) သည် ပွင့်လင်းရင်းမြစ် မေးဆာဗာဖြစ်သည်။ ၎င်းသည် [Dovecot](http://www.dovecot.org/) , ပွင့်လင်းရင်းမြစ် [IMAP](http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol) [POP3](http://en.wikipedia.org/wiki/Post_Office_Protocol) ဆာဗာများဖြင့် တိုက်ရိုက်ချိတ်ဆက်သည်။ ထပ်မံသိရှိလိုပါက official [Ubuntu documentation](http://help.ubuntu.com/11.04/serverguide/C/email_services.html) တွင် ကြည့်ပါ။ dovecot - postfix metapackage သည် အစိတ်အပိုင်းများ တပ်ဆင်ပြီး Maildir (mail spooling) ဖိုလ်ဒါစနစ်ကို အသုံးပြုနိုင်ရန်အတွက် ချိန်ညှိမှုဆိုင်ရာ ဖိုင်များကို ပြုပြင်သည်။ Imap and Pop3 မိုဂျူး၊ SMTP နှင့် SASL/TLS (သက်သေခံလက်မှတ်ပါသော) များကို အလိုအလျောက်တပ်ဆင်သည်။

	sudo apt-get install dovecot - postfix

#####iRed Mail

[iRed Mail](http://code.google.com/p/iredmail/wiki/installation_on_Ubuntu) သည် Dovecot, Postfix, a choice of Open LDAP (with phpLDAPAdmin) or MySQL ဒေတာဘေ့စ်၊
ဝက်ဘ်အခြေပြု မေးလ်အတွက်  Roundcubemail or Squirrelmail ၊ phpAdmin, Postfix Admin, and A Wstats တို့ကို ပါဝင်သော package ဖြစ်သည်။ ၎င်းသည် Lucid 10.04 LTS တွင် အကောင်းဆုံးဖြစ်စေရန်စီမံထားပြီး ဆာဗာအသစ်ပေါ်တွင် တပ်ဆင်ရန် အကောင်းဆုံးဖြစ်သည်။ (၎င်းသည် အီးမေးလ် ဆိုင်ရာ ချိန်ညှိမှုဖိုင်များစွာကို မူလအနေအထား ဖြစ်စေရန် ပြုပြင်သောကြောင့်ဖြစ်သည် ) ၎င်း၏ အဖွဲ့အစည်းပုံစံတွင် စီးပွားဖြစ်ထုတ်လုပ်သော ပုံစံ၏ အရည်အသွေးများစွာပါဝင်သည်။

####Financial Software

For a brief introduction, see this list of 10 Linux financial tools [here](http://ubuntudoctor.com/content/news/10-linux-financial-tools).

#####KMyMoney (Personal Fiance Management)

[KMyMoney](http://kmymoney2.sourceforge.net/index-home.html) ကို ကျွမ်းကျင်အကောင့် (Accountants) သမားတွေ အသုံးပြုသလို အသုံးပြုနိုင်ပါသည်။ KMyMoney မှာလည်းပဲ MyMoney နှင့် Intuit Quicken ကဲ့သို့ ငွေစာရင်းတွေကို  double - accounting နဲ့ အသုံးပြုနိုင်သလို၊ လုပ်ငန်းအတွက်လဲ သက်ဆိုင်ရာ အမျိုးအစားအလိုက် စီမံနိုင်တဲ့ ဆော့ဝဲလ်ဖြစ်ပါသည်။ ကို KDE Kubuntu အတွက် ပြုလုပ်ထားတာဖြစ်ပြီး Gnome/Ubuntu တို့မှာလဲ သွင်းယူအသုံးပြုနိုင်ပါသည်။Install -

	sudo apt-get install kmymoney2

#####Gnu Cash (Personal Finance Management)

[GnuCash](http://www.gnucash.org/) ဟာ အခမဲ့ပေးထားတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပြီး GPL 
လိုင်စင်နဲ့ အသုံးပြုနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲ ဖြစ်ပါသည်။GnuCash မှာ ငွေစာရင်းတွေကို double-accounting နဲ့ အသုံးပြုနိုင်သလို ကျွမ်းကျင်အကောင့် (Accountants) သမားတွေကဲ့သို့ အသုံးပြုနိုင်ပါသည်။ ကို GTK - based (Gnome 2) ကို အခြေခံပြီး ပြုလုပ်ထားခြင်းဖြစ်ပါသည်။အခု နောက်ဆုံးဗားရှင်းကို source files ကနေ သွင်းယူလို့ရနေပါပြီ။ [Gnu Cash](http://www.gnucash.org/) မှာ ထည့်သွင်းမှုပုံစံတွေနဲ့ ရနိုင်တဲ့ ဗားရှင်းတွေကို တွေ့ရမှာဖြစ်ပါသည်။ Install-

	sudo apt-get install gnucash

#####Skrooge (Personal Finance Management)

[Skrooge](http://skrooge.org/) ဟာ အခမဲ့ပေးထားတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပြီး GPL လိုင်စင်နဲ့ အသုံးပြုနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲဖြစ်ပါသည်။ Skrooge ကို KDE တွေမှာ အသုံးပြုနိုင်အောင် ပြုလုပ်ထားတာဖြစ်ပြီး တခြား ငွေကြေးစီမံခန့်ခွဲမှုပရိုဂရမ်တွေနဲ့ တွဲပြီး အသုံးပြုနိုင်ရန်အတွက် ဒေတာတွေကို import/export လုပ်နိုင်တဲ့လုပ်ဆောင်ချက် ထည့်သွင်းပေးထားပါသည်။ Install -

	sudo apt-get install skrooge

#####Moneydance (Personal Finance Management)

[Moneydance](http://moneydance.com/) ဟာ ကဲ့သို့ စီးပွားဖြစ်ရောင်းချတဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပါသည်။ Java အား အခြေပြု ဖန်တီးထားတာဖြစ်ပြီး Operation System အမျိုးမျိုးအတွက် အသုံးပြုနိုင်အောင် ဖန်တီးထားတာဖြစ်ပါသည်။ အသုံးချခွင့်လိုင်စင်အတွက်  တစ်ခုချင်းကို ဒေါ်လာ ၅၀ ကုန်ကျမှာဖြစ်ပါသည်။

#####SQL - Ledger (Enterprise Fianance Management)

[SQL - Ledger ERP](http://www.sql-ledger.org/) က double-accounting စနစ်နဲ့ အသုံးပြုနိုင်ပြီး
Operation System မရွေးတဲ့ ၊ အခမဲ့ရရှိနိုင်တဲ့ ပွင့်လင်းရင်းမြစ်ဆော့ဖ်ဝဲဖြစ်ပါသည်။ နောက်ပြီး SQL database server (PostgreSQL/Oracle/Mysql databases) တွေကို အသုံးပြုကာ inventory ,work and purchase orders,taxes ကဲ့သို့သော လုပ်ငန်းအချက်အလက်တွေကို ခန့်ခွဲနိုင်တဲ့ ပရိုဂရမ်တစ်ခုဖြစ်ပါသည်။ ကိုအသုံးပြုမယ်ဆိုရင် ဝဘ်ဘရောက်ဇာ (Internet exploer ,Mozilla Fox ) ကနေတစ်ဆင့် အသုံးပြုရမှာဖြစ်ပါသည်။ ကို ကျယ်ပြန့်စွာ အသုံးပြုနိုင်ပြီး ဘာသာစကားအများစုကိုလဲ အထောက်အပံ့ပေးထားပါသည်။ Install -

	sudo apt-get install sql-ledger

####Wiki software

မပြင်ဆင်ရသေးပါ။ မကြာမှီ ပြင်ဆင်မည်။

you can contribute

#####Wiki 

software allows an organization to have a manual that can be edited by a number of collaborators.Wikipedia is the best known example.

#####Media Wiki

[Media Wiki](http://www.mediawiki.org) is the free. မကြာမီပြင်ဆင်ဖြည့်စွတ်မည်။

#####Twiki

[Twiki](http://twiki.org)
