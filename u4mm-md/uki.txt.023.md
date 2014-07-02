##Default Applications##

Ubuntu ၏ ယခင္ version မ်ားတြင္ သင္ သတ္မွတ္ထားေသာ လုပ္ငန္းမ်ားအတြက္ မည္သည့္ program အား ပံုေသအသံုးျပဳမည္ကို သင့္အေနျဖင့္ ဤေနရာမွ ေရြးခ်ယ္ႏို္င္သည္။

`Menu` - `System` - `Administration` - `Default Applications`

(သို႔မဟုတ္) 

ဖိုင္တစ္ခုအား `right-click' ႏွိပ္၍  `Open with Other Application` ျဖင့္လည္း ေရြးခ်ယ္ႏုိင္သည္။

Default Application munu သည္ လက္ရွိ Ubuntu version တြင္ မပါရွိေတာ့ပါ။ သို႔ေသာ္ ဤ function အား ျပဳလုပ္ခြင့္ေပးေသာ GUI ႏွင့္ Ubuntu ႏွင့္ Multiple similar Ubuntu system twesk မ်ားအတြက္ 
[UbuntuTweak](http://ubuntu-tweak.com/) ကို install ျပဳလုပ္၍ အသံုးျပဳႏိုင္ပါသည္။

	wget http://launchpad.net/ubuntu-tweak/0.5.x/0.5.8/+ download/ubuntu-tweak_0.5.8-1all.deb
	sudo dpkg -i ubuntu- tweak _ 0.5.8-1_all.deb
	
##Kill a process##

တစ္ခါတစ္ရံမွာ Program တစ္ခု (သို႕မဟုတ္) process တစ္ခုဟာ အသံုးျပဳေနစဥ္မွာပဲ ရပ္တန္႔ (hang)သြားတတ္ပါတယ္(ဥပမာ Firefox)။ထိုကဲ႔သို႔ေသာ program (သို႔မဟုတ္) process မ်ားအား kill (သို႕မဟုတ္) ပိတ္ပစ္ရန္အတြက္
	
`Menu`- `System` - `Administration` - `System Monitor` - `highlight the errant process` - `Kill process`

မွပိတ္ႏိုင္ပါတယ္။

command line မွလည္း

		sudo killall process 

ဟုရိုက္ကာ ပိတ္ႏိုင္ပါတယ္။ process ေနရာတြင္ ရပ္တန္႕ေနေသာ program ( firefox ဆိုပါက firefox) ဟုထည့္ေပးရပါမယ္။


##Enabling NUM LOCK On Startup##

`Menu` - `System` - `Administration` -`Keyboard Mouse` - `Keyboard` - `turn on Numlock on Startup`


#Working with Menus#

##Create an encrypted folder##

သင့္အေနျဖင့္ encrypted  ျပဳလုပ္ထားသည့္ အရာမ်ားပါ၀င္ေသာ folder တစ္ခု ဤလမ္းညႊန္ခ်က္မ်ား  
(http://help.ubuntu.com/community/EncryptedPrivatedDirectory) အား ၾကည့္ရႈ၍ ဖန္တီးႏိုင္ပါသည္။

Create a symlink from a file to another location

[symbolic link](http://en.wikipedia.org/wiki/Symbolic_link) (သို႔) symlink ဟုလည္း သိၾကသည့္ သေကၤတလင့္သည္ Linux ၏ file သုိ႔မဟုတ္ directory တစ္ခုအား တစ္ေနရာမွ အျခားေနရာသို႔ ညႊန္ျပသည့္ နည္းလမ္းတစ္ခုျဖစ္သည္။ 
အသံုးျပဳပံု

	Ln -s /path /to /source/path/to/destination

အကယ္၍ `/path/to/destination` မွ `superuser` ျဖစ္ရန္လိုအပ္ပါက ေအာက္ပါ command အား အသံုးျပဳပါ။

	sudo Ln-s /path /to/source /path/to/destination

ဤနည္းသည္ ယခင္ window user မ်ား အကၽြမ္းတ၀င္ရွိၾကမည့္  Shoutcut မ်ားဖန္တီးသည့္ ပံုစံျဖင့္ ဆင္တူေသာ္လည္း ပို၍ အဆင့္ျမင့္ (စြမ္းအားျမင့္) ပါသည္။

##Assign a root password##

Root သုိ႔ တို္က္ရိုက္ `log in`  ျပဳလုပ္ႏိုင္ရန္အတြက္  root password ထည့္သြင္းေပးရန္လိုအပ္ပါသည္။ password ထည့္သြင္းရန္အတြက္ 

	sudo passwd rood

ထို႔ေနာက္ သင့္အေနျဖင့္ `su` ကို အသံုးျပဳ၍ root သုိ႔သြားပါ။ ထုိ႔ေနာက္ root password အား ထည့္သြင္းေပးပါ။

##root password မရွိပဲ root permission အသံုးျပဳျခင္း။##
Get a root prompt without using a root password
 
root password ကုိ မထည့္ရေသးလွ်င္ျဖစ္ေစ၊ ေမ့ေလ်ာ့သြားရင္ျဖစ္ေန ေအာက္က ကြန္မန္းေတြ သံုးျပဳျပီး root access ရယူႏုိင္ပါတယ္။

	sudo - s
	
or

	sudo su

or

	sudo bash

ဒါဆိုရင္ root password သံုးမယ့္အစား လက္ရွိသံုးေနတဲ့အေကာင့္ရဲ ့password ကုိပဲသံုးျပဳသြားပါလိမ့္မယ္။ တျခား user အေကာင့္ေတြကုိလဲ ေအာက္က ဥပမာအတုိင္း ေခၚသံုးႏုိင္ပါတယ္။

	sudo su username

File Manager ကုိေအာက္က command ေတြအသံုးျပဳျပီး root access နဲ့ဖြင့္ႏုိင္ပါတယ္။

	sudo nautilus
	
or

	gksudo nautilus


Device ေတြ ျဖဳတ္တပ္ကို maunal ျပဳလုပ္ဖုိ့အတြက္ေအာက္က ကြန္မန္းသံုးပါတယ္။

	mount /dev/hda

`hda` ေနရာမွာ ကုိယ္ mount လုပ္ခ်င္တဲ့ဟာကုိ အစားထိုးရမွာပါ။

unmount ျပဳလုပ္ဖုိ့အတြက္က ေအာက္က ကြန္မန္းသံုးျပဳပါတယ္။

	umount/dev/hda

`hda` ေနရာမွာ ကုိယ္ mount လုပ္ခ်င္တဲ့ဟာကုိ အစားထိုးရပါတယ္။။


#Networking#

တစ္ခုတည္းေသာ Network manager အား GUI interface ျဖင့္ စတင္လုပ္ေဆာင္ေစႏိုင္ပါသည္။ Network-Manager သည္ ပံုမွန္အေနျဖင့္ ပါ၀င္ၿပီးျဖစ္သည္။ သို႔ေသာ္လည္း အသံုးျပဳသူမ်ားသည္ [Wicd Network Manager](http://wicd.sourceforge.net/)  ကို ပို၍ ႏွစ္သက္ၾကသည္။


###Network Manager#

Network Manager သည္ ubuntu တြင္ ပံုမွန္အေနျဖင့္ ထည့္သြင္းထားၿပီးျဖစ္သည္။ ၎သည္ Notification 
ေနရာတြင္ internet connections (wireless APs သို႔မဟုတ္ wired connection တို႔ကို )ခ်ိတ္ဆက္ရန္ သို႔မဟုတ္ အသံုးမျပဳရန္ ေရြးခ်ယ္ႏုိင္ပါသည္။


##Wicd Network Manager##

[Wicd Network Manager](http://wicd.sourceforget.net/) is a GTK -dependent networking manager written in Python that can be used in all variants of Ubuntu. Many users (including me) report it 
to be faster and more stable than Network Manager. To avoid networking conflicts, Wicd
requires the removal of Network Manager prior to installation.

	sudo apt - get remove network-manager
	sudo reboot
	sudo apt - get install wicd


##Set a static IP address##

I have never been able to ger Network Manager to accept my static IP address settings. If you 
only use only a wire interface, you do not neekd a network manager and it can be removed.

-Remove Network Manager:

	sudo apt - get remove network-manager
	sudo reboots

-Edit the /etc /network/interfaces files:


##GPPP##

GPPP သည္ ယခင္ Ubuntu versions ေတြရဲ႕  default modem dailing application ျဖစ္ခဲ့ပါသည္။

`Menu` - `Applications` - `Internet` - `GPPP Internet Dail` - 
`up Remote Access`

Remote Access နည္းလမ္းမ်ဳိးစံုရွိပါသည္။ VNC Sharing ကို သံုးျခင္းျဖင့္ ရီမုတ္လုပ္ထားေသာ ကြန္ပ်ဴတာ၏ Desktop ကို ၾကည့္ႏိုင္၊ ထိန္းခ်ဳပ္ႏုိင္ပါသည္။ (Windows သံုးသူမ်ားသည္ အလားတူ `(remote desktop
protocol,RDP )` ဟု ေခၚေသာ သီးျခားအဖြဲ႔အစည္း တစ္ခုပိုင္ ပရိုတိုေကာကို သံုးၾကသည္။) `XDMCP (X Display Manager Control Protocol)` ျဖင့္ လည္း` X-windows` ကို အေျခခံသည့္ ၿပီးျပည့္စံုေသာ Remote Login ကို ျပဳလုပ္ႏိုင္ပါသည္။ ခြင့္မျပဳသင့္ေသာ ၀င္ေရာက္ျခင္းမ်ား ၊ေဒတာအခ်က္အလက္ ပို႔ေဆာင္ျခင္းမ်ားကို 
ကာကြယ္ေပးေသာ သင့္ေတာ္သည့္ ၾကိဳတင္ကာကြယ္မႈမ်ားမရွိလွ်င္ `Remote Connection` သည္ လံုျခံဳေရးအရ အႏ ၱရာယ္ရွိေပသည္။ 

##SSH##

`Secure Shell` သုိ႔မဟုတ္ `SSH` လို႔ေခၚေသာ  network protocol တစ္ခုျဖစ္ပါသည္။ ၎ Protocol သည္ ကြန္ပ်ဴတာ ႏွစ္ခုၾကားတြင္ `Secure channel` (သို႔မဟုတ္ tunnel ) မွ တဆင့္ အခ်က္အလက္ေတြကို ဖလွယ္ႏိုင္ရန္ 
အေထာက္အပံ့ေပးပါသည္။ Encryption လုပ္ျခင္းျဖင့္ သတင္းအခ်က္အလက္မ်ားကို တိက်လံုျခံဳမႈ ရွိေစပါတယ္။

OpenSSH client ကိုေတာ့ Ubuntu တြင္ default အေနနဲ႔ install လုပ္ထားၿပီး အျခား `SSH server run` ေနေသာ ကြန္ပ်ဴတာတစ္ခုႏွင့္ ခ်ိတ္ဆက္ေပးႏုိင္မွာျဖစ္ပါတယ္။
