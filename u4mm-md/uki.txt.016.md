xt 3   defaults , rw  0  0

ထို႔ေနာက္ restart ျပဳလုပ္ျခင္းျဖင့္ အမွား ကင္းျခင္း ရွိမရွိ စစ္ေဆးပါ။ kolab အား download ျပဳလုပ္ထားသည့္  ေနရာတြင္  folder တစ္ခုျပဳလုပ္ပါ။ လက္ရွိ  Kolab file မ်ားအား Download ျပဳလုပ္ရန္  Folder တစ္ခု တည္ေဆာက္ပါ။

	cd /tmp
	mkdir   /kolabtmp

နာက္ဆံုးထြက္ရွိသည့္  Kolab file မ်ားအား Download ျပဳလုပ္ပါ။

	cd /tmp/kolabtmp

	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/ix 86-debian4.0
	
	wget -r -11 -nd --no-parent http://files.kolab.org/server/release/kolab-server-2.2.2/sources/

Root အေနျဖင့္ sudo-s ကို အသံုးျပဳကာ Kolab အား install ျပဳလုပ္ပါ :

	sudo-s
	sh install - kolab.sh 21  l  tee kolab - install .log

သင့္ ကြန္ပ်ဴတာအား restart ျပဳလုပ္ပါ။ Kolab service မ်ားအား ရပ္ဆိုင္း၍  Configuration utility ကို ဖြင့္ပါ။

	sudo /kolab/bin/openpky rc all stop
	sudo /kolob/sbin/kolab bootstrap -b

သင့္အေနျဖင့္ မိမိ၏ အခ်က္အလက္မ်ားျဖစ္သည့္ host ၏ အမည္ ၊ (၎ ကို  hostname - f ျဖင့္ သိႏိုင္သည္) domain အေသးစိတ္အခ်က္အလက္ စသည္တို႔အား ဤအဆင့္ မျပဳလုပ္မီတြင္ သိရွိထားသင့္ပါသည္။ Kolab သည္ slabd open LDAP server တို႔ကို အသံုးျပဳမည္ျဖစ္ေသာေၾကာင့္ [Open LDAP](http://www.openldap .org /) ႏွင့္ [LDAP](http://en.wikipedia.org/ wiki /LDAP) ၏ အေျခခံအခ်က္အလက္မ်ားႏွင့္ ရင္းႏွီးကၽြမ္း၀င္မႈ မရွိေသးပါက သင့္အေနျဖင့္ ေလ့လာထားသင့္ပါသည္။

Kolab ၏ service မ်ားအားလံုးအား ျပန္လည္စတင္ပါ။

	sudo / kolab /bin /openpkg rc all start

Manager အား အသံုးျပဳ ၍ bootstrap configuration တြင္ ထည့္သြင္းထားသည့္ password ျဖင့္ web
administrator interface သို႔ Login ျပဳလုပ္ပါ။

	http://yourhost.yourdomain.name/admin/

####Citadel

[Citadel](http://www.citadel.org/) သည္ အသင့္သံုး open source groupware ျဖစ္ၿပီး KDE ႏွင့္ Kolab-1 ႏွစ္မ်ဳိးလံုးျဖင့္ တြဲဖက္အသံုးျပဳႏုိင္သည္။ လြန္ခဲ့သည့္ ႏွစ္ေပါင္း ၂၀ေက်ာ္မွ Bulletin - board ပံုစံ framework အား အသံုးျပဳထားေသာေၾကာင့္  ၎သည္ KDE , Gnome ႏွစ္မ်ဳိးစလံုးျဖင့္ရ ၀က္ဘ္ အေျချပဳ ပံုစံလည္း သံုးစြဲႏို္င္သည္။ WebDAV ႏွင့္လည္း တြဲဖက္ႏို္င္ၿပီး Thunderbird ျဖင့္ လည္း အသံုးျပဳႏုိင္သည္။

#####Install the Citadel server:

	sudo apt-get install citadel-server

#####Install the Citadel client:

	sudo apt-get install citadel-client

#####Install both:

	sudo apt-get install citadel-suite

####eGroupware

[eGroupware](http://www.egroupware.org/) သည္ အေျခခံခိုင္မာ တည္ၿငိမ္ေသာ (GPL လိုင္စင္ျဖင့္) ပြင့္လင္းရင္းျမစ္ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္ၿပီး LAMP (ဦးဘႏၱဳ ဆာဗာျဖင့္ တပါတည္း ပါရွိေသာ ဆာဗာ) ႏွင့္ Postfix mail (ႏွစ္မ်ဳိးစလံုးကို ဦးတည္ထည့္သြင္းထားသင့္ပါသည္ )ေပၚတြင္ အေျခခံထားသည္။ ဗားရွင္းအသစ္ကို မၾကာေသးမီကပင္ ရရွိႏုိင္ၿပီး ဂ်ာမနီမွ ေကာ္ပိုရိတ္စပြန္စာျဖင့္ စီးပြားေရးလုပ္ငန္းသံုး ဗားရွင္းတို႔ပါ၀င္သည္။ Clients မ်ားျဖင့္ တြဲဖက္အသံုးျပဳႏိုင္မႈမွာ မ်ားစြာတိုးတက္လာပါသည္။ eGroupware သည္ အစုအဖြဲ႔ ေဆာ့၀ဲလ္မ်ားအားလံုးတြင္ အလြယ္ကူဆံုးႏွင့္ အျမန္ဆံုးေသာ တပ္ဆင္ခ်ိန္ကို ေပးစြမ္းႏုိင္ပါသည္။ အားနည္းခ်က္မွာ လက္ရွိ ဗားရွင္းအတြက္ အသံုးျပဳနည္းအမ်ားစုကို အဂၤလိပ္ဘာသာျဖင့္ မရရွိႏို္င္ေသးျခင္းပင္ျဖစ္သည္။

####Open - Xchange

[Open - Xchange](http://www.open-xchange.com/home.html) သည္ ပုဂၢလိကပိုင္ 
အသင္းအဖြဲ႔ ေဆာ့၀ဲလ္ (MS - Exchange ကို အစားထိုးရန္ ရည္ရြယ္သည္) ျဖစ္ၿပီး ၎ကို အဖြဲ႔အစည္းပံုစံသစ္ျဖင့္ ထုတ္ေ၀ျခင္းကို စီးပြားျဖစ္ ဗားရွင္းေပၚတြင္ အေျခခံထားျခင္းျဖစ္သည္။ ေနာက္ဆံုး `.deb` package သည္ Hardy Heron 8.04 အတြက္ ျဖစ္သည္။ ၎သည္ အျခားေသာ clients မ်ား ျဖစ္သည့္ Kontact,Outlook,Palm PDAs မ်ားျဖင့္လည္း တြဲဖက္အသံုးျပဳႏုိင္သည္။ ျပည့္စံုေသာ တပ္ဆင္ပံုညႊန္ၾကားခ်က္မ်ားကို ၀က္ဘ္ဆိုဒ္တြင္ ေလ့လာႏုိင္သည္။


####Open Guoupware

[OpenGroupware](http://www.opengroupware.org/) သည္ postgre SQL ေဒတာေဘ့စ္အေပၚတြင္ အေျချပဳထားေသာ အစုအဖြဲ႔ ေဆာ့၀ဲလ္ ျဖစ္သည္။ ၎တြင္ စီးပြားျဖစ္ပံုစံႏွင့္ ပြင့္လင္းရင္းျမစ္ပံုစံ (၂၀၀၈ တြင္တိုးတက္မႈ ရပ္ဆိုင္းသြားသည္ )ရွိသည္။ အသစ္မထြက္ေတာ့ေသာေၾကာင့္ တပ္ဆင္မႈကို Source မွ တိုက္ရိုက္ ထည့္သြင္းရမည္။ အေသးစိတ္ကို ၀က္ဘ္တြင္ၾကည့္ပါ။

####Zarafa

[Zarafa](http:// zarafa.com/?q=en/content/community -O) သည္ ဥေရာပ၏ ဦးေဆာင္ MS-Exchange အစားထိုး အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္သည္။  ၎သည္ ယခင္က ပုဂၢလိကပိုင္ ၊ေနာက္ပိုင္း (မွတ္ပံုတင္အမွတ္မွလြဲ၍) GPL လိုင္စင္ျဖင့္ ပြင့္လင္းရင္းျမစ္ အဖြဲ႔အစည္းပံုစံကို ၂၀၀၈တြင္ ထုတ္လုပ္ခဲ့သည္။ ေဒါင္းလုပ္ ရယူႏုိင္သည့္ အခ်က္အလက္မ်ားကို ၀က္ဘ္ဆိုက္တြင္ ေဖာ္ျပထားသည္။

####Zimbra

[Zimbra](http://www.zimbra.com/downloads/os-download.html) သည္ ပုဂၢလိကပိုင္ အုပ္စုဖြဲ႔ ေဆာ့၀ဲလ္ျဖစ္ၿပီး (ယခု VMWare မွ ပိုင္ဆိုင္သည္ ) ပြင့္လင္းရင္းျမစ္ အဖြဲ႔အစည္းပံုစံကို ထုတ္ေပးထားသည္။ လက္ရွိတြင္အခမဲ့ေပးေသာ္လည္း အဖြဲ႔အစည္းပံုစံတြင္ ကန္႔သတ္ခ်က္မ်ားရွိၿပီး GPL လို\E1\80
