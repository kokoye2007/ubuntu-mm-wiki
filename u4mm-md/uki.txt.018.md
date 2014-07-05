�သည့္ clients မ်ားျဖင့္ တြဲဖက္သံုးႏိုင္သည္။ ေနာက္ဆံုးဗားရွင္းကို [RSS]( http://en.wikipedia.org/wiki/RSS ) clients သံုးကာ ၾကည့္ရႈႏိုင္သည္။ ေနာက္ဆံုး ဗားရွင္း (၁.၂) ကို တပ္ဆင္ရန္ ၀က္ဘ္ဆိုဒ္ ႏွင့္ [wiki](http://www.k5n.us/wiki/index.pmp?title=Main_Page)
ကို ၾကည့္ပါ။ ဗားရွင္းအေဟာင္း (၁.၀၅) ထည့္သြင္းရန္ 

	sudo apt-get install webcalendar

####Mail Servers

#####Postfix/Dovecot (Mail Server)

[Postfix](http://www.postfix.org/) သည္ ပြင့္လင္းရင္းျမစ္ ေမးဆာဗာျဖစ္သည္။ ၎သည္ [Dovecot](http://www.dovecot.org/) , ပြင့္လင္းရင္းျမစ္ [IMAP](http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol) [POP3](http://en.wikipedia.org/wiki/Post_Office_Protocol) ဆာဗာမ်ားျဖင့္ တိုက္ရိုက္ခ်ိတ္ဆက္သည္။ ထပ္မံသိရွိလိုပါက official [Ubuntu documentation](http://help.ubuntu.com/11.04/serverguide/C/email_services.html) တြင္ ၾကည့္ပါ။ dovecot - postfix metapackage သည္ အစိတ္အပိုင္းမ်ား တပ္ဆင္ၿပီး Maildir (mail spooling) ဖိုလ္ဒါစနစ္ကို အသံုးျပဳႏိုင္ရန္အတြက္ ခ်ိန္ညွိမႈဆိုင္ရာ ဖိုင္မ်ားကို ျပဳျပင္သည္။ Imap and Pop3 မိုဂ်ဴး၊ SMTP ႏွင့္ SASL/TLS (သက္ေသခံလက္မွတ္ပါေသာ) မ်ားကို အလိုအေလ်ာက္တပ္ဆင္သည္။

	sudo apt-get install dovecot - postfix

#####iRed Mail

[iRed Mail](http://code.google.com/p/iredmail/wiki/installation_on_Ubuntu) သည္ Dovecot, Postfix, a choice of Open LDAP (with phpLDAPAdmin) or MySQL ေဒတာေဘ့စ္၊
၀က္ဘ္အေျချပဳ ေမးလ္အတြက္  Roundcubemail or Squirrelmail ၊ phpAdmin, Postfix Admin, and A Wstats တို႔ကို ပါ၀င္ေသာ package ျဖစ္သည္။ ၎သည္ Lucid 10.04 LTS တြင္ အေကာင္းဆံုးျဖစ္ေစရန္စီမံထားၿပီး ဆာဗာအသစ္ေပၚတြင္ တပ္ဆင္ရန္ အေကာင္းဆံုးျဖစ္သည္။ (၎သည္ အီးေမးလ္ ဆိုင္ရာ ခ်ိန္ညွိမႈဖိုင္မ်ားစြာကို မူလအေနအထား ျဖစ္ေစရန္ ျပဳျပင္ေသာေၾကာင့္ျဖစ္သည္ ) ၎၏ အဖြဲ႔အစည္းပံုစံတြင္ စီးပြားျဖစ္ထုတ္လုပ္ေသာ ပံုစံ၏ အရည္အေသြးမ်ားစြာပါ၀င္သည္။

####Financial Software

For a brief introduction, see this list of 10 Linux financial tools [here](http://ubuntudoctor.com/content/news/10-linux-financial-tools).

#####KMyMoney (Personal Fiance Management)

[KMyMoney](http://kmymoney2.sourceforge.net/index-home.html) ကို ကၽြမ္းက်င္အေကာင့္ (Accountants) သမားေတြ အသံုးျပဳသလို အသံုးျပဳႏုိင္ပါသည္။ KMyMoney မွာလည္းပဲ MyMoney ႏွင့္ Intuit Quicken ကဲ့သို႔ ေငြစာရင္းေတြကို  double - accounting နဲ႔ အသံုးျပဳႏိုင္သလို၊ လုပ္ငန္းအတြက္လဲ သက္ဆိုင္ရာ အမ်ဳိးအစားအလိုက္ စီမံႏိုင္တဲ့ ေဆာ့၀ဲလ္ျဖစ္ပါသည္။ ကို KDE Kubuntu အတြက္ ျပဳလုပ္ထားတာျဖစ္ၿပီး Gnome/Ubuntu တို႕မွာလဲ သြင္းယူအသံုးျပဳႏို္င္ပါသည္။Install -

	sudo apt-get install kmymoney2

#####Gnu Cash (Personal Finance Management)

[GnuCash](http://www.gnucash.org/) ဟာ အခမဲ့ေပးထားတဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ၿပီး GPL 
လိုင္စင္နဲ႔ အသံုးျပဳႏိုင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲ ျဖစ္ပါသည္။GnuCash မွာ ေငြစာရင္းေတြကို double-accounting နဲ႔ အသံုးျပဳႏုိင္သလို ကၽြမ္းက်င္အေကာင့္ (Accountants) သမားေတြကဲ့သို႔ အသံုးျပဳႏုိင္ပါသည္။ ကို GTK - based (Gnome 2) ကို အေျခခံၿပီး ျပဳလုပ္ထားျခင္းျဖစ္ပါသည္။အခု ေနာက္ဆံုးဗားရွင္းကို source files ကေန သြင္းယူလို႔ရေနပါၿပီ။ [Gnu Cash](http://www.gnucash.org/) မွာ ထည့္သြင္းမႈပံုစံေတြနဲ႔ ရႏုိင္တဲ့ ဗားရွင္းေတြကို ေတြ႔ရမွာျဖစ္ပါသည္။ Install-

	sudo apt-get install gnucash

#####Skrooge (Personal Finance Management)

[Skrooge](http://skrooge.org/) ဟာ အခမဲ့ေပးထားတဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ၿပီး GPL လို္င္စင္နဲ႔ အသံုးျပဳႏိုင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲျဖစ္ပါသည္။ Skrooge ကို KDE ေတြမွာ အသံုးျပဳႏိုင္ေအာင္ ျပဳလုပ္ထားတာျဖစ္ၿပီး တျခား ေငြေၾကးစီမံခန္႔ခြဲမႈပရိုဂရမ္ေတြနဲ႔ တြဲၿပီး အသံုးျပဳႏုိင္ရန္အတြက္ ေဒတာေတြကို import/export လုပ္ႏုိင္တဲ့လုပ္ေဆာင္ခ်က္ ထည့္သြင္းေပးထားပါသည္။ Install -

	sudo apt-get install skrooge

#####Moneydance (Personal Finance Management)

[Moneydance](http://moneydance.com/) ဟာ ကဲ့သို႔ စီးပြားျဖစ္ေရာင္းခ်တဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ပါသည္။ Java အား အေျချပဳ ဖန္တီးထားတာျဖစ္ၿပီး Operation System အမ်ဳိးမ်ဳိးအတြက္ အသံုးျပဳႏုိင္ေအာင္ ဖန္တီးထားတာျဖစ္ပါသည္။ အသံုးခ်ခြင့္လိုင္စင္အတြက္  တစ္ခုခ်င္းကို ေဒၚလာ ၅၀ ကုန္က်မွာျဖစ္ပါသည္။

#####SQL - Ledger (Enterprise Fianance Management)

[SQL - Ledger ERP](http://www.sql-ledger.org/) က double-accounting စနစ္နဲ႔ အသံုးျပဳႏိုင္ၿပီး
Operation System မေရြးတဲ့ ၊ အခမဲ့ရရွိႏုိင္တဲ့ ပြင့္လင္းရင္းျမစ္ေဆာ့ဖ္၀ဲျဖစ္ပါသည္။ ေနာက္ၿပီး SQL database server (PostgreSQL/Oracle/Mysql databases) ေတြကို အသံုးျပဳကာ inventory ,work and purchase orders,taxes ကဲ့သို႔ေသာ လုပ္ငန္းအခ်က္အလက္ေတြကို ခန္႔ခြဲႏိုင္တဲ့ ပရိုဂရမ္တစ္ခုျဖစ္ပါသည္။ ကိုအသံုးျပဳမယ္ဆိုရင္ ၀ဘ္ဘေရာက္ဇာ (Internet exploer ,Mozilla Fox ) ကေနတစ္ဆင့္ အသံုးျပဳရမွာျဖစ္ပါသည္။ ကို က်ယ္ျပန္႔စြာ အသံုးျပဳႏုိင္ၿပီး ဘာသာစကားအမ်ားစုကိုလဲ အေထာက္အပံ့ေပးထားပါသည္။ Install -

	sudo apt-get install sql-ledger

####Wiki software

မျပင္ဆင္ရေသးပါ။ မၾကာမွီ ျပင္ဆင္မည္။

you can contribute

#####Wiki 

software allows an organization to have a manual that can be edited by a number of collaborators.Wikipedia is the best known example.

#####Media Wiki

[Media Wiki](http://www.mediawiki.org) is the free. မၾကာမီျပင္ဆင္ျဖည့္စြတ္မည္။

#####Twiki

[Twiki](http://twiki.org)
