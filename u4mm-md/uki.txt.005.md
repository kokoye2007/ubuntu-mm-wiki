�ပြာင်းလဲနိုင်သည်။

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

##Desktop Add-ons

GNOME Desktop အတွက် အဆင်သင့်အသုံးပြုနိုင်တဲ့ Add-on icons တွေ themes နဲ့ Wallpapers များ 3-D effects များနှင့်အတူ အခြားသော ကိုယ်ကိုယ်တိုင် ရွေးချယ်နိုင်တာတွေ ရှိပါတယ်။

###Gnome Eye-Candy Resources 

[Gnome Look](http://www.gnome-look.org) တွင် wallpapers တွေ splash screens တွေ icons တွေနဲ့အတူ  Windows Mangers အတွက် (Metacity နဲ့ Compiz ပါဝင်သည့်) themes များနှင့်
အခြားသော အသုံးပြု ဆော့ဝဲတွေ (appalication) များပါရှိပါသည်။

###Ubuntu Wallpaper
[Ubuntu wallpaper](https://www.flickr.com/groups/ubuntuwallpaper/)
[Trusty Tahr Wallpaper](https://www.flickr.com/groups/2535978@N21)
[Ubuntu Myanmar wallpaper](http://flickr.com/groups/ubuntu-mm-art)
