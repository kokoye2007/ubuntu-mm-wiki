##Default Applications##

Ubuntu ၏ ယခင် version များတွင် သင် သတ်မှတ်ထားသော လုပ်ငန်းများအတွက် မည်သည့် program အား ပုံသေအသုံးပြုမည်ကို သင့်အနေဖြင့် ဤနေရာမှ ရွေးချယ်နိုင်သည်။

`Menu` - `System` - `Administration` - `Default Applications`

(သို့မဟုတ်) 

ဖိုင်တစ်ခုအား `right-click' နှိပ်၍  `Open with Other Application` ဖြင့်လည်း ရွေးချယ်နိုင်သည်။

Default Application munu သည် လက်ရှိ Ubuntu version တွင် မပါရှိတော့ပါ။ သို့သော် ဤ function အား ပြုလုပ်ခွင့်ပေးသော GUI နှင့် Ubuntu နှင့် Multiple similar Ubuntu system twesk များအတွက် 
[UbuntuTweak](http://ubuntu-tweak.com/) ကို install ပြုလုပ်၍ အသုံးပြုနိုင်ပါသည်။

	wget http://launchpad.net/ubuntu-tweak/0.5.x/0.5.8/+ download/ubuntu-tweak_0.5.8-1all.deb
	sudo dpkg -i ubuntu- tweak _ 0.5.8-1_all.deb
	
##Kill a process##

တစ်ခါတစ်ရံမှာ Program တစ်ခု (သို့မဟုတ်) process တစ်ခုဟာ အသုံးပြုနေစဉ်မှာပဲ ရပ်တန့် (hang)သွားတတ်ပါတယ်(ဥပမာ Firefox)။ထိုကဲ့သို့သော program (သို့မဟုတ်) process များအား kill (သို့မဟုတ်) ပိတ်ပစ်ရန်အတွက်
	
`Menu`- `System` - `Administration` - `System Monitor` - `highlight the errant process` - `Kill process`

မှပိတ်နိုင်ပါတယ်။

command line မှလည်း

		sudo killall process 

ဟုရိုက်ကာ ပိတ်နိုင်ပါတယ်။ process နေရာတွင် ရပ်တန့်နေသော program ( firefox ဆိုပါက firefox) ဟုထည့်ပေးရပါမယ်။


##Enabling NUM LOCK On Startup##

`Menu` - `System` - `Administration` -`Keyboard Mouse` - `Keyboard` - `turn on Numlock on Startup`


#Working with Menus#

##Create an encrypted folder##

သင့်အနေဖြင့် encrypted  ပြုလုပ်ထားသည့် အရာများပါဝင်သော folder တစ်ခု ဤလမ်းညွှန်ချက်များ  
(http://help.ubuntu.com/community/EncryptedPrivatedDirectory) အား ကြည့်ရှု၍ ဖန်တီးနိုင်ပါသည်။

Create a symlink from a file to another location

[symbolic link](http://en.wikipedia.org/wiki/Symbolic_link) (သို့) symlink ဟုလည်း သိကြသည့် သင်္ကေတလင့်သည် Linux ၏ file သို့မဟုတ် directory တစ်ခုအား တစ်နေရာမှ အခြားနေရာသို့ ညွှန်ပြသည့် နည်းလမ်းတစ်ခုဖြစ်သည်။ 
အသုံးပြုပုံ

	Ln -s /path /to /source/path/to/destination

အကယ်၍ `/path/to/destination` မှ `superuser` ဖြစ်ရန်လိုအပ်ပါက အောက်ပါ command အား အသုံးပြုပါ။

	sudo Ln-s /path /to/source /path/to/destination

ဤနည်းသည် ယခင် window user များ အကျွမ်းတဝင်ရှိကြမည့်  Shoutcut များဖန်တီးသည့် ပုံစံဖြင့် ဆင်တူသော်လည်း ပို၍ အဆင့်မြင့် (စွမ်းအားမြင့်) ပါသည်။

##Assign a root password##

Root သို့ တိုက်ရိုက် `log in`  ပြုလုပ်နိုင်ရန်အတွက်  root password ထည့်သွင်းပေးရန်လိုအပ်ပါသည်။ password ထည့်သွင်းရန်အတွက် 

	sudo passwd rood

ထို့နောက် သင့်အနေဖြင့် `su` ကို အသုံးပြု၍ root သို့သွားပါ။ ထို့နောက် root password အား ထည့်သွင်းပေးပါ။

##root password မရှိပဲ root permission အသုံးပြုခြင်း။##
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


#Networking#

တစ်ခုတည်းသော Network manager အား GUI interface ဖြင့် စတင်လုပ်ဆောင်စေနိုင်ပါသည်။ Network-Manager သည် ပုံမှန်အနေဖြင့် ပါဝင်ပြီးဖြစ်သည်။ သို့သော်လည်း အသုံးပြုသူများသည် [Wicd Network Manager](http://wicd.sourceforge.net/)  ကို ပို၍ နှစ်သက်ကြသည်။


###Network Manager#

Network Manager သည် ubuntu တွင် ပုံမှန်အနေဖြင့် ထည့်သွင်းထားပြီးဖြစ်သည်။ ၎င်းသည် Notification 
နေရာတွင် internet connections (wireless APs သို့မဟုတ် wired connection တို့ကို )ချိတ်ဆက်ရန် သို့မဟုတ် အသုံးမပြုရန် ရွေးချယ်နိုင်ပါသည်။


##Wicd Network Manager##

[Wicd Network Manager](http://wicd.sourceforget.net/) is a GTK -dependent networking manager written in Python that can be used in all variants of Ubuntu. Many users (including me) report it 
to be faster and more stable than Network Manager. To avoid networking conflicts, Wicd
requires the removal of Network Manager prior to installation.

	sudo apt-get remove network-manager
	sudo reboot
	sudo apt-get install wicd


##Set a static IP address##

I have never been able to ger Network Manager to accept my static IP address settings. If you 
only use only a wire interface, you do not neekd a network manager and it can be removed.

-Remove Network Manager:

	sudo apt-get remove network-manager
	sudo reboots

-Edit the /etc /network/interfaces files:


##GPPP##

GPPP သည် ယခင် Ubuntu versions တွေရဲ့  default modem dailing application ဖြစ်ခဲ့ပါသည်။

`Menu` - `Applications` - `Internet` - `GPPP Internet Dail` - 
`up Remote Access`

Remote Access နည်းလမ်းမျိုးစုံရှိပါသည်။ VNC Sharing ကို သုံးခြင်းဖြင့် ရီမုတ်လုပ်ထားသော ကွန်ပျူတာ၏ Desktop ကို ကြည့်နိုင်၊ ထိန်းချုပ်နိုင်ပါသည်။ (Windows သုံးသူများသည် အလားတူ `(remote desktop
protocol,RDP )` ဟု ခေါ်သော သီးခြားအဖွဲ့အစည်း တစ်ခုပိုင် ပရိုတိုကောကို သုံးကြသည်။) `XDMCP (X Display Manager Control Protocol)` ဖြင့် လည်း` X-windows` ကို အခြေခံသည့် ပြီးပြည့်စုံသော Remote Login ကို ပြုလုပ်နိုင်ပါသည်။ ခွင့်မပြုသင့်သော ဝင်ရောက်ခြင်းများ ၊ဒေတာအချက်အလက် ပို့ဆောင်ခြင်းများကို 
ကာကွယ်ပေးသော သင့်တော်သည့် ကြိုတင်ကာကွယ်မှုများမရှိလျှင် `Remote Connection` သည် လုံခြုံရေးအရ အန ္တရာယ်ရှိပေသည်။ 

##SSH##

`Secure Shell` သို့မဟုတ် `SSH` လို့ခေါ်သော  network protocol တစ်ခုဖြစ်ပါသည်။ ၎င်း Protocol သည် ကွန်ပျူတာ နှစ်ခုကြားတွင် `Secure channel` (သို့မဟုတ် tunnel ) မှ တဆင့် အချက်အလက်တွေကို ဖလှယ်နိုင်ရန် 
အထောက်အပံ့ပေးပါသည်။ Encryption လုပ်ခြင်းဖြင့် သတင်းအချက်အလက်များကို တိကျလုံခြုံမှု ရှိစေပါတယ်။

OpenSSH client ကိုတော့ Ubuntu တွင် default အနေနဲ့ install လုပ်ထားပြီး အခြား `SSH server run` နေသော ကွန်ပျူတာတစ်ခုနှင့် ချိတ်ဆက်ပေးနိုင်မှာဖြစ်ပါတယ်။
