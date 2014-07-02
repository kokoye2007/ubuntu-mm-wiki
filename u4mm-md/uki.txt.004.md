**ဥပမာ** Destop version GUI installer ကိုအသံုးျပဳ၍ installation ျပဳလုပ္ေနစဥ္အတြင္း အဆင့္တစ္ခုတြင္ ေအာက္ပါအတိုင္းေပၚလာမည္ျဖစ္သည္။

	Summary > Advanced > Device for boot loader installation: /dev/sda6

အထက္ပါ ဥပမာတြင္ ထိုအေျခအေနအတိုင္း ထားရွိပါက GRUB2 bootloader သည္ `/dev/sda6` ((K)Ubuntu OS ထည့္သြင္းထားသည့္ Harddisk Partition ) အတြင္းသို႕သာ ေရာက္ရွိသြားမည္ျဖစ္ၿပီး MBR (Master Boot Record) ကိုေျပာင္းလဲမည္မဟုတ္ပါ။သို႕ေသာ္ `/dev/sda` ၏ default setting တြင္ထားရွိလိုက္ပါက GRUB2
သည္ `/dev/sda6` ((K)Ubuntu OS ထည့္သြင္းထားသည့္ Harddisk Partition ) အတြင္းသို႕
ေရာက္ရွိသြားမည္ ျဖစ္သည့္အျပင္ MBR  (Master Boot Record) ကိုလည္း ျပဳျပင္ေျပာင္းလဲသြားပါမည္။ ထိုအခါ GRUB2 သည္ ကြန္ပ်ဴတာေပၚတြင္ ထည့္သြင္းထားသည့္ Operation System  အားလံုး၏ master bootloader အျဖစ္ေျပာင္းလဲသြားမည္ျဖစ္သည္။အျခားေသာ bootloader (GRUB2 မဟုတ္သည့္) မ်ားကို အသံုးျပဳေနသူျဖစ္လွ်င္ ထိုအေျခအေနသည္ အဆင္ေျပမည္မဟုတ္ပါ။

##Start Manager ကို အသံုးျပဳ၍ Grub ၏ setting မ်ားကို ေျပာင္းလဲျခင္း

Grub သည္ (Operation System ၁ခုထပ္ပို၍ ထည့္သြင္းထားေသာ ကြန္ပ်ဴတာမ်ားတြင္) မည္သည့္ OS ကို ပံုမွန္ ဦးစားေပးအေနျဖင့္ စတင္လည္ပတ္ေစမည္ကို သတ္မွတ္ျခင္းႏွင့္ အျခားေသာ bootup setting မ်ားကို ထိန္းခ်ဳပ္သည့္ bootup utility ၁ခုျဖစ္သည္။ [Startup Manager](http://sourceforge.net/projects/startup-manager/) ကို အသံုးျပဳ၍ Grub ၏ setting  မ်ားကို ေျပာင္းလဲႏိုင္သည္။ Startup Manager သည္ Grub (Grub Legacy ), Grub 2, Usplash, and Splashy စသည့္ bootloader မ်ား၏ setting မ်ားကို ကြပ္ကဲရာတြင္ အသံုးျပဳသည့္ software ျဖစ္သည္။ Startup Manager အသံုးျပဳပံုကို [ဒီေနရာ](https://help.ubuntu.com/community/StartUpManager) တြင္ႀကည့္ရွုႏိုင္သည္။ Startup Manager ထည့္သြင္းရန္အတြက္

	sudo apt-get install startupmanager menu

Startup Manager လည္ပတ္ေစရန္

	Menu > System > Administration > Startup Manasger

>**မွတ္ခ်က္** Grub setting မ်ားကို command-line interface မွလည္း ေျပာင္းလဲျပင္ဆင္ႏိုင္သည္။

##Mac OS X ႏွင့္ Ubuntu ကို ကြန္ပ်ဴတာတစ္လံုးတည္းေပၚတြင္ ယွဥ္တြဲတင္ျခင္း

Mac OS X သည္ Linux ႏွင့္ တည္ေဆာက္ပံု ဆင္တူသည္ (Max OS X သည္ BSD Unix ကို
အေျခခံထားျခင္းျဖစ္သည္။) Mac OS X ႏွင့္ Ubuntu ကို ယွဥ္တြဲတင္ျခင္းႏွင့္ ပတ္သတ္ေသာ
အေသးစိတ္လမ္းညႊန္ခ်က္မ်ားကို [ဒီေနရာတြင္](http://help.ubuntu.com/community/MacBook) တြင္ေလ့လာႏိုင္သည္။

###Ubuntu ရွိၿပီးသား ကြန္ပ်ဴတာေပၚတြင္ Mac OS X တင္ျခင္း

Ubuntu ကို Mac OS X ႏွင့္ ယွဥ္တြဲတင္မည္ဆိုပါက Ubuntu ကို ထည့္သြင္းမည့္ Harddisk Partition ကို ext2 ကို ေရြးခ်ယ္ပါ။ (ထိုလုပ္ငန္းစဥ္အတြက္ Super Grub Disk CD သည္ အသံုး၀င္ေသာ utility ျဖစ္သည္။) Super Grub ISO ဖိုင္ကို [ဒီေနရာတြင္](http://supergrub.forjamari.linex.org) တြင္ download ရယူႏိုင္သည္။

Ubuntu ကို ထည့္သြင္းၿပီးပါက Grub start-up list ကို ျပင္ဆင္ေျပာင္းလဲပါ။

	sudo nano /boot/ grub/menu.1st

ထို႕ေနာက္ ေအာက္ပါစာေႀကာင္းမ်ားကို ထပ္ေပါင္းထည့္ပါ။

	title Mac OS X root (hd0,0) makeactive chainloader + 1

ၿပီးလွ်င္ Mac ကို reboot လုပ္၍ Mac OS X  တြင္ပါ၀င္ေသာ Terminal ကို သြားပါ။ (boot လုပ္ရာတြင္
အခက္အခဲရွိပါက Mac OS X DVD ကိုအသံုးျပဳ၍ boot လုပ္ပါ။) F8 ကိုႏွိပ္၍ -s ဟု ရိုက္ထည့္ပါ။ ထို႕ေနာက္ ရိုက္ထည့္ရမည့္စာေႀကာင္းမ်ားမွာ `fdiskn -e /dev/rdisk0 flag 2` (flag 2သည္ ယခုဥပမာ၏ Harddisk Partition number 2 ျဖစ္သည္။ သင္၏ Mac တြင္ အသံုးျပဳထားသည့္ Partition number ေပၚတြင္ လိုက္၍ေျပာင္းလဲႏိုင္သည္။) quity reboot ပံုမွန္အလုပ္ လုပ္ေဆာင္ႏိုင္ၿပီဟု မေသခ်ာေသးပါက Super Grub Disk CD ကို အသံုးျပဳ၍ Grub ကို active 
လုပ္ပါ။

###Mac OS X ရွိၿပီးသား ကြန္ပ်ဴတာေပၚတြင္ Ubuntu တင္ျခင္း

Booth လုပ္ေနစဥ္အတြင္း boothloader တြင္ ပံုမွန္လုပ္ေဆာင္ေနျခင္းမရွိဟု သတင္းပို႕ခ်က္ (ဥပမာ HFS+error) မ်ားေပၚလာပါက Super Grub ကိုအသံုးျပဳ၍ Linux GRUB ႏွင့္ MBR (Master Boot Record) ကို ျပန္လည္ျပင္ဆင္ႏိုင္သည္။ Ubuntu ကို ထည့္သြင္းၿပီးပါက Grub start-up list ကိုျပင္ဆင္ေျပာင္းလဲပါ။

	sudo nano /boot/grub/menu.1st

ထို႕ေနာက္ ထပ္ေပါင္းထည့္ရမည့္ စာေႀကာင္းမ်ားမွာ

	title Mac OS X root (hd0,0) makeactive chainloader +1

အကယ္၍ သင္သည္GRUB တြင္ Mac OS X သို႕မဟုတ္ Windows ႏွင့္ပတ္သတ္၍ အခက္အခဲျဖစ္ေနပါက Mac OS X ၏ Grub ရွိ entry ကို "root (hd0,1) သို႕ေျပာင္းလဲပါ။ထိုသို႕ေျပာင္းလဲျခင္းျဖင့္ သင္၏ကြန္ပ်ဴတာသည္ Partition number 1 ကို boot လုပ္ပါလိမ့္မည္။Grub
မွန္ကန္စြာအလုပ္လုပ္ေဆာင္ႏိုင္သည္အထိ partition number ကို
