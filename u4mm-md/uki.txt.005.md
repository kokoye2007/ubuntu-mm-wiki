�ျပာင္းလဲႏိုင္သည္။

##Package Installation and Updates

###Apt and Package Basics 

**Add Extra Repositories ကိုဖတ္ပါ။**

Ubuntu အသံုးျပဳသူအမ်ားစုသည္ Synaptic Package Manager ကို package မ်ားထည့္သြင္းရန္ 
အသံုးျပဳႀကပါသည္။ ေအာက္ပါ ညႊန္ျပခ်က္မ်ားသည္ package မ်ားကို ကိုpackage မ်ားထည့္သြင္းရန္
အသံုးျပဳႀကပါသည္။ေအာက္ပါညႊန္ျပခ်က္မ်ားသည္ package မ်ားကို command-line Terminal အသံုးျပဳ၍ ထည့္သြင္းရန္ နည္းလမ္းမ်ားျဖစ္ပါသည္။ 

#####Terminal ကိုစတင္ရန္ 
	Menu -> Application -> Accessories -> Terminal

#####packages မ်ားထည့္သြင္းရန္ 

	sudo apt-get install *packagename* 
	ဥပမာ : sudo apt-get install mpd sbackup

#####package မ်ား ဖယ္ရွားရန္

	sudo apt-get remove *packagename*

#####package ႏွင့္တကြ ထို package ႏွင့္ သက္ဆိုင္သည္မ်ားအားလံုး ဖယ္ရွားရန္ 

	sudo apt-get autoremove 
	ဥပမာ : sudo apt-get remove mpd sbackup

#####package မ်ားရွာေဖြရန္ 

	apt-cache search < keywords> 
	ဥပမာ : apt-cache search  Music MP3 apt-cache search "Text Editor"

#####addting/removing repositories ျပဳလုပ္ၿပီး package ၏ database မ်ားကို အဆင့္ၿမႇင့္တင္ရန္ 

	sudo apt-get update

#####package မ်ားကို ugrade လုပ္ရန္ :

	sudo apt-get upgrade

#####Ubuntu စနစ္တစ္ခုလံုးကို upgrade  လုပ္ရန္ (ဥပမာ : Maverick မွ Natty)

	sudo apt-get dist-upgrade

#####deb package မ်ားထည့္သြင္းျခင္း

Debian (.deb) package မ်ားသည္ (Windows ေပၚတြင္installer .exe msi package မ်ား
အလုပ္လုပ္သကဲ့သို႕) Ubuntu ေပၚတြင္ အသံုးျပဳေသာ package မ်ားျဖစ္သည္။ Ubuntu စနစ္ေပၚတြင္ မည္သည့္ .deb package ကိုမဆို ထည့္သြင္းႏိုင္သည္။ Ubuntu စနစ္တြင္ မူလပါရွိေသာ installer ႏွင့္ .deb package မ်ားကို ဆက္သြယ္ႏိုင္ရန္ ျပဳလုပ္ထားသျဖင့္ .deb ဖိုင္မ်ားကို file manager (Nautilus) တြင္ click ျခင္းျဖင့္ လြယ္ကူစြာထည့္သြင္းႏိုင္သည္။ ေအာက္ေဖာ္ၿပပါ ညႊန္ျပခ်က္မ်ားမွာ command-line terminal (Terminal) ကိုအသံုးျပဳႇ၍ package မ်ား ထည့္သြင္းခ်င္သူမ်ားအတြက္ ျဖစ္ပါသည္။

#####အင္တာနက္မွ ဆြဲယူထားေသာ Debian (Ubuntu) package (.deb) ၁ခု ထည့္သြင္းရန္

	sudo dpkg -i packagename.deb

#####Debian (Ubuntu) package (.deb) ကိုဖယ္ရွားရန္ :

	sudo dpkg -r packagename . ဥပမာ : sudo dpkg-reconfigure mpd

##Handling (Tar/GZip) and (Tar/Bzip2) archives

(Tar/GZip) ရဲ႕ extension က .tar.gz ျဖစ္ပါသည္။ (Tar/Bzip2) ရဲ႕ extension က .tar.bz2 ျဖစ္ပါသည္။ Terminal မွ အသံုးျပဳနည္းမ်ားကို ေအာက္ပါအတိုင္းေဖာ္ျပလိုက္ပါသည္။

	tar xvf  packagename . tar . gz
	-x (ျဖည္ရန္) -v ( ) -f ( )

#####.gz ကိုျဖည္ျခင္း

	gunzip filename .gz

#####.bz2 ကိုျဖည္ျခင္း

#####.gz အျဖစ္ ႏွစ္သက္ရာဖိုင္ကို compress လုပ္ျခင္း

	tar cvfs packagename  .tar.gz folder

#####.bz2 အျဖစ္ ႏွစ္သက္ရာဖိုင္ကို compress လုပ္ျခင္း

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

Package မ်ားအားလံုးသည္ Terminal (apt-get, aptitude, and Synaptic Package Manager)
မွာအဆင္သင့္ မရရွိႏိုင္ေသာ္လည္းပဲ Ubuntu Software Center မွရရွိႏိုင္ပါသည္.မည္သို႕ျဖစ္ေစ ၊ Ubuntu စတင္အသံုးျပဳသူမ်ား အေနျဖင့္ အလြယ္ကူဆံုး ျမင္ကြင္းမွ packages မ်ားအား ေအာက္ပါအတိုင္း ထည့္သြင္းႏိုင္သည္။

	Menu -Application - Ubuntu Software Center

သင္ထည့္သြင္းလိုေသာ Program အခ်ိဳ႕အား ရွာေဖြႏိုင္သည္။ဥပမာ -mp3ဟုရိုက္လွ်င္ mp3
software စာရင္းမ်ား ျမင္ရမည္။

	Installation ျပဳလုပ္လိုေသာ program အားေရြးခ်ယ္ပါ -Apply ႏွိပ္ပါ။ေရြးခ်ယ္ထားေသာ program(s) မ်ားသည္ အလိုအေလ်ာက္ install ျပဳလုပ္သြားမည္။

###Manual Updates

General Notes ကိုဖတ္ပါ။
Add Extra Repositories ကိုဖတ္ပါ။

#####Terminal မွ တဆင့္ ကိုယ္ကိုတိုင္ျပဳလုပ္ရန္အတြက္ (Command Line Interface ):

	sudo apt-get update
	sudo apt-get upgrade

	**သို႕မဟုတ္**

#####Synptic Package Manager ကို အသံုးခ်နည္း

	Menu -System -Administration - Synaptic Package Manager -Reload then Mark all upgrades

အကယ္၍ package က updating လုပ္ဖို႕ အဆင္သင့္ျဖစ္ေနမယ္ဆိုရင္ ခ်က္ျခင္း install လုပ္သင့္ပါတယ္။

###Automated Updates

#####Synaptic Package Manager ကို အသံုးခ်ျခင္း

	Menu - System - Administration - Synaptic Manager - Settings - Preferences - General - Reloading Outdated Package Information - Automatic

##Desktop Add-ons

GNOME Desktop အတြက္ အဆင္သင့္အသံုးျပဳႏိုင္တဲ့ Add-on icons ေတြ themes နဲ႕ Wallpapers မ်ား 3-D effects မ်ားႏွင့္အတူ အျခားေသာ ကိုယ္ကိုယ္တိုင္ ေရြးခ်ယ္ႏိုင္တာေတြ ရွိပါတယ္။

###Gnome Eye-Candy Resources 

[Gnome Look](http://www.gnome-look.org) တြင္ wallpapers ေတြ splash screens ေတြ icons ေတြနဲ႕အတူ  Windows Mangers အတြက္ (Metacity နဲ႕ Compiz ပါ၀င္သည့္) themes မ်ားႏွင့္
အျခားေသာ အသံုးျပဳ ေဆာ့၀ဲေတြ (appalication) မ်ားပါရွိပါသည္။

###Ubuntu Wallpaper

[Maverick Meerkat wallpaper](https://wiki.ubuntu.com/Artwork/Incoming/Maverick)
