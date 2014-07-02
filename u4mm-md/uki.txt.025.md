ဤ password ဥပမာသည္ ssh program မွ password လိုအပ္ေသာအခါ sshpassword ကို သြားေစပါသည္။
Expect သည္ command-line terminal မွ စာလံုးအခ်ဳိ႕ကိုေစာင့္ဆိုင္း ရယူၿပီး စာမ်ားျပန္ထုတ္ေပးသည္။
ထို႔ေၾကာင့္ Menu Iten ကို terminal တြင္သာ run   ေစရမည္ျဖစ္္္္္္သည္။


###[SHC](Encrypt scripts)

[SHC](http://www.datsi.fi.upm.es/~frosal/) သည္ code ႏွင့္ password စသည္မ်ားကို မျမင္ေအာင္ ျပဳလုပ္ေပးၿပီး ထို script မ်ားကို binary အျဖစ္သို႔ ေျပာင္းလဲေပးသည့္ ရိုးရွင္းေသာ script compiler တစ္ခုျဖစ္သည္။ အသံုးျပဳပံုမ်ားအား ဤေနရာတြင္ (http://www.datsi.fi.upm.es/~frosal/sources/shc.html) ၾကည့္ရႈႏိုင္ပါသည္။ `Debian Etch respository` ကို ထည့္သြင္းျခင္းျဖင့္ install ျပဳလုပ္ႏိုင္ပါသည္။

	sudo add - apt - repository http://archive.debian.org/debian/etc main

ထို႔ေနာက္ shc package အား install ျပဳလုပ္ပါ။

	sudo apt - get install shc

#Capture a screenshot #

Screenshot ျပဳလုပ္ျခင္း ဤ [Tutorial](http://tips.webdesign10.com/how-to-take-a-screenshot-on-ubuntu-linux) တြင္ ၾကည့္ပါ။


##Desktop အား KDE  ကဲ့သို႔ ေျပာင္းလဲျခင္း##

ေနာက္ဆံုးထြက္ Ubuntu ဗားရွင္းတြင္ Gnome desktop အား ျပဳျပင္၍ cleaner KDE desktop အျဖစ္ ျပင္ဆင္ႏုိင္ပါသည္။ (ျပဳျပင္ျခင္းသည္ အလြန္ ကိုယ္ေရးကိုယ္တာက်သျဖင့္ ဤအပိုင္းသည္ လမ္းညႊန္အျဖစ္သာ ေဖာ္ျပေပးထားသည္။ )

`-Desktop Customization ျပဳျပင္ျခင္းကို ၾကည့္ပါ။`

##Ubuntu တြင္  KDE 4 Desktop အသံုးျပဳျခင္း##

Kubuntu တြင္ အလိုအေလ်ာက္ပါၿပီးျဖစ္ေသာ KDE4 အေျချပဳ Desktop အား Ubuntu တြင္ install လုပ္ႏုိင္ပါသည္။

	sudo apt - get  install kubuntu - desktop

KDE4 အား install လုပ္ရာတြင္ အသံုးမလိုေသာ feature မ်ားျပားျခင္းႏွင့္  Module  မ်ားအၾကား လိုက္ေလ်ာညီေထြမႈမရွိျခင္း ျပသနာမ်ားၾကံဳေတြ႔ရတတ္ပါသည္။ Login ျပဳလုပ္ရာ၌ KDE (Kubuntu) Desktop ျဖင့္ ျဖစ္ေစ၊ Gnome (Ubuntu) Desktop ျဖင့္ျဖစ္ေစ၊ ႀကိဳက္ႏွစ္သက္ရာျဖင့္ ျပဳလုပ္ႏုိင္သည္။ သို႔ေသာ္လည္း Desktop တစ္ခုခ်င္းစီမွ Modules ၂ခုသည္  function တစ္ခုအား လုပ္ေဆာင္မည္ဆိုပါက
အခက္အခဲ(ကြဲလြဲျခင္း)မ်ား ျဖစ္ႏိုင္ပါသည္။

##KDE 3 Desktop အား Ubuntu  တြင္ အသံုးျပဳျခင္း##

သင့္အေနျဖင့္ ယခင္ Lucid (သို႔မဟုတ္) မည္သည့္ KDE 3 application မွ KDE 3 Desktop ကို Ubuntu တြင္
install လုပ္ႏုိင္ပါသည္။	

-ေဖာ္ျပပါ KDE 3 repositories အား ထည့္ပါ။

	sudo add - apt - repository ppa:kde3 -maintainers

-KDE 3.5 desktop အား install လုပ္ပါ။

	sudo apt - get update
	sudo apt - get install kubuntu - desktop -kde 3

-မည္သည့္  KDE 3 application ကိုမဆို install ျပဳလုပ္လိုပါက package အမည္တြင္  `-kde 3` ဟူေသာ	 စာလံုးကို ထပ္ျဖည့္ေပးရပါမည္။ အခ်က္အလက္ အျပည့္အစံုအတြက္ [Pearson Computing](http://apt.pearsoncompution.net/) ကို ၾကည့္ပါ။


##Kill (end) a process ##

Process (application) အား ပိတ္ျခင္း (သို႔မဟုတ္) အဆံုးသတ္ျခင္း

-Frozen PC ကို ျပင္ဆင္ရန္ နည္းလမ္းအေတာ္မ်ားမ်ား ရွိပါသည္။ `Alt + F2` ကို ႏွိပ္ပါ။ ထို႔ေနာက္  frozen	Application ကို ပိတ္ရန္ Killall ကို အသံုးျပဳပါ။ 

ဥပမာ:

	sudo killall amarok
	sudo killall firefox

-ထစ္ေနေသာ Graphic ႏွင့္ ဆိုင္သည့္ application မ်ားကို ပိတ္ရန္အတြက္ `xkill utility` ကို သံုးပါ။`Alt+F2` ကို ႏွိပ္ပါ။ `xkill` ဟု ရိုက္ၿပီး run ကို ႏွိပ္ပါ။  သင္ပိတ္လိုေသာ  application ေပၚတြင္ Mouse ၏ ၀ဲလက္ခလုတ္ကို ႏွိပ္ပါ။ 

ဤနည္းျဖင့္  သင္ပိတ္လိုသည့္ application မ်ားကို ပိတ္ႏိုင္ပါသည္။

##skill##

-အျခားနည္းအေနျဖင့္ `AltGr+SysRq+K (Right Alt +Print Screen + K)` ကို ႏွိပ္ပါ။ ဒီနည္းက သင့္ကို logout ျဖစ္ေစမွာျဖစ္ပါတယ္။ တကယ္လို႔ ဒီနည္းက အလုပ္မျဖစ္ဘူးဆိုရင္ေတာ့  `Ctrl + Alt + F1` ကိုႏွိပ္ၿပီး login လုပ္ပါ။ ၿပီးေတာ့ သင့္ password ကို ႏွိပ္ၿပီး run ပါ။

	sudo killall gdm
	sudo startx


##View hidden files ##

Hidden File မ်ားအား ၾကည့္ရႈျခင္း  Nautilus Manager မွာ ဒါေလးကို ႏွိပ္ပါ။

	ctrl + H

##Notification (အခ်က္ျပျခင္း ) ေတြကို အသံေဖ်ာက္ရန္##

-အခ်က္ေပးသံေတြကို disable ျပဳလုပ္ဖို႔အတြက္

	Menu - System - Preferences - Sound -Sound Effects - Sound 	theme: -No sounds - Close

-GNOME အခ်က္ေပးခ်က္ေတြဟာ အသံျဖင့္ အလိုအေလ်ာက္ ဆက္စပ္ေနပါတယ္။ ဒါကို သီးျခား disable ျပဳရပါမယ္။
	
`Alt - F2 - gconf - editor -/apps/indicators - sound - volume _mute` (အမွန္ျခစ္ေပးပါ။ )

-Login အခ်က္ေပး အသံကို ပိတ္ရန္အတြက္

`Menu - System -Preferences - Startup Applications - Startup Programs - GNOME LoginSound` (အမွန္ ျခစ္ျဖဳတ္ေပးပါ။ ) 

`-Menu - System - Administration - Login Screen - Unlock - Play login sound` (အမွန္ျခစ္ျဖဳတ္ေပးပါ။)

#Random password generator#

က်ပန္း password geneartor

	-Pwgen သည္ က်ပန္း password စာလံုးစုမ်ားထုတ္ေပးရန္အတြက္  အသံုး၀င္သည့္ command line
	တစ္ခုျဖစ္သည္။ Kubuntu တြင္ Konsole မွ တဆင့္ ၊Ubuntu တြင္ Terminal မွတဆင့္
အသံုးျပဳႏိုင္သည္။ Install ျပဳလုပ္ရန္ ----

	sudo apt - get install pwgen

-Pwgen အား အသံုးျပဳရန္
	
	pwgen

-UUIDgen သည္ က်ပန္း UUID မ်ားအား ထုတ္ေပးသည့္ အသံုး၀င္ေသာ
	အလိုအေလ်ာက္ ထည့္သြင္းေပးထားသည့္ program တစ္ခုျဖစ္သည္။ အသံုးျပဳရန္ း
uuidgen


ဆႏၵရွိပါက က်ပန္း UUID အား password အေနျဖင့္လည္း အသံုးျပဳနိုင္ပါသည္။





