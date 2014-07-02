##USB Creator##

You can make a LiveCD on a USB pendrive using USB Creator and either a LiveCD or an .iso
version of the LiveCD stored on your hard drive. USB Creator is installed by default in Ubuntu.
If not,install:

	sudo apt - get install usb -creator-gtk

-Run:

`Menu` - `System` - `Startup Disk Creator`

Create a boot CD to allow booting from the USB drive

Many computers do not allow booting from a USB drive (but they do allow booting from the
CD-ROM). You can create a CD-ROM using these [Pendrivelinux instrctions](http://www.pendrivelinux.com/make-a-usb-boot-cd-for-ubuntu-9-10/)  and set your BIOS to boot from this CD-ROM. When you boot from this CD-ROOM, it will use the bootup files on the Ubuntu USB drive you previously created (in the step above).


##System Administration##

#####GRUB boot manager settings

######Grub2

Ubuntu 11.04 (Natty) တြင္ boot manager အျဖစ္ (customize လုပ္ရန္ ရႈပ္ေထြးေသာ) [Grub2](http://www.gnu.org/software/grub/maunal/grub.html) ပါလာပါသည္။ (Grub2 ႏွင့္ grub-pc သည္ 
တစ္မ်ဳိးတည္းသာ ျဖစ္သည္။) Grub2 အတြက္ ညႊန္ၾကားခ်က္မ်ားကို [Ubuntu wiki](http://wiki.ubuntu.com/Grub2) သို႔မဟုတ္ [Ubuntu forums](http://ubuntuforums.org/showthread.php?t=1195275) မ်ားတြင္ ၾကည့္ရႈႏုိင္သည္။ အၾကမ္းအားျဖင့္

	sudo nano /etc /default /grub
	sudo grub-mkconfig--output=/boot/grub/grub.cfg


အျခားေသာနည္းလမ္းအေနျဖင့္ ေအာက္ပါ command ကို အသံုးျပဳႏိုင္သည္။

	sudo update-grub


#####Turn off ACPI through GRUB

The new Linux kernel , starting with Karmic ,will attempt to throttle the CPU every few seconds
based on lm-sensors read of CPU temperature and fan speed. If your hardward is not supported
by lm-sensors (like mine), this will cause your system to show down dramatically or even freeze.
As always, this is an ACPI problems, so disabling it at boot often takes of the problem.Edit
the GRUB configuration as above and add the line:

	GRUB _ CMDLINE _ LINUX =acpi=off


Grub2 background image,colors,fonts

-Grub2 အတြက္ ေနာက္ခံပုံရိပ္မ်ား၊ အေရာင္မ်ား ၊ Font မ်ား [ဤေနရာတြင္](http://ubuntuforums.org/showthread.php?p=10720685#post10720685) ၾကည့္ပါ။

-Grub2 တြင္ မည္သည့္ ေနာက္ခံပံုကို သံုးသည္ျဖစ္ေစ အသံုးျပဳမည့္ပံုကို `/boot/grub` ဖိုင္တြဲတြင္ ထည့္၍ Grub2 ကို configure လုပ္ျခင္းျဖင့္ အသံုးျပဳႏုိင္သည္။

	sudo update grub

အသံုးျပဳမည့္ပံုသည္ `/etc /default /grub` တြင္ ရွိသည့္ Grub 2 စတင္လုပ္ေဆာင္ရန္ သတ္မွတ္ထားေသာ
ပံုအရည္အေသြးႏွင့္ တူညီရမည္။ (ဥပမာ 1024 x 768)

-ေရြးခ်ယ္ထားေသာ splashimage မ်ားကို `/usr/share/image/grub` ဖိုင္တြဲတြင္ ထည့္သြင္း၍ 
  အသံုးျပဳႏိုင္သည္။

	sudo apt - get install grub2-splashimages

-အသံုးျပဳလိုေသာ ပံုရိပ္တစ္ခုကို `/boot/grub` ဖို္င္တြဲတြင္ ထည့္၍ splashimage အေနျဖင့္အသံုးျပဳႏိုင္သည္။ ဥပမာ

	sudo in -s /usr /share /images /grub /Plasma-lamp.tga/boot/grub
	sudo update-grub

#####Grub 2 အား ခ်ဳိးေဖာက္၀င္ေရာက္ျခင္း မျပဳႏုိင္ရန္ ကာကြယ္ျခင္း

-Grub2 ကို ကာကြယ္ရန္ အေရးႀကီးေသာ အခ်က္မ်ားကို [Grub Manual](http://www.gnu.org/software/grub/manual/grub.html#Security ) တြင္ ၾကည့္ပါ။

-စကား၀ွက္ထည့္သြင္းရန္အတြက္ /etc/grut.d/40_custom configuration file တြင္ ေအာက္ပါ command ကို ရိုက္ထည့္ပါ။
	set superusers=user1
	password_pbkdf2 user1 grub.pbkdf2.sha512.10000.biglongstring
	password user1 insecurecleartextpassword


စကား၀ွက္ေနရာတြင္ insecurecleartextpassword အစား သင္၏ စကား၀ွက္ ထည့္သြင္းအသံုးျပဳရပါမည္။
သို႔မဟုတ္ [ဤေနရာ](http://www.gnu.org/software/grub/manual/grub.html#Security) တြင္ ျပထားေသာ pbkdf2-encrypted နည္းလမ္းကို အသံုးျပဳ၍ ကာကြယ္ႏုိင္သည္။ သင္၏ Ubuntu OS Grub2 လံုျခံဳေရးႏွင့္ ပတ္သက္၍ အေသးစိတ္ကို ဤ [Blog](http://www.panoet.com/set-grub-2-password-protection-149) တြင္ ဖတ္ရႈႏိုင္သည္။

####GRUB Legacy

Boot partition တစ္ခုႏွင့္ အသံုးျပဳရန္ GRUB ၏ version အေဟာင္းျဖစ္သည့္ (Grub [Legacy](http://www.gnu.org/software/grub/manual/legacy/grub.html) ကို ရယူႏုိင္သည္။ Grub Legacy ကို ထည့္သြင္းရန္အတြက္

	sudo apt - get install grub

-အကယ္၍ သင့္ကြန္ပ်ဴတာတြင္ operation system တစ္ခုထပ္ပိုရွိေနပါက multiple operation systems (OS) ျဖစ္ေနၿပီး သင္သည္ Grub Legacy boot manager ကို သံုးစြဲဖူးၿပီး ျဖစ္ေကာင္းျဖစ္ႏုိင္သည္။ Grub Legacy ၏ option မ်ားကို menu.1st configuration file တြင္ တည္းျဖတ္ျပင္ဆင္ႏုိင္သည္။ အေသးစိတ္ကို ၾကည့္ရႈႏိုင္သည္။

	sudo nano /boot /grub /menu.1st

(text editor အျဖစ္ nano အစား gedit ကို အသံုးျပဳႏိုင္သည္။)

####Grub Legacy မွ data မ်ား ရယူ၍ Grub2 တြင္ ျပန္လည္ အသံုးျပဳျခင္း

Grub Legacy မွ data မ်ားရယူ၍ Grub2 တြင္ အသံုးျပဳရန္အတြက္ Grub Legacy ၏ menu.1st configuration file တြင္ ဤပံုစံျဖင့္ မိမိ OS မ်ားကို ျဖည့္သြင္းပါ။ (menu.1st ဖိုင္ကို boot partition တြင္ သိမ္းဆည္းထားသည္။)

	title Kubuntu Maverisk OS (chainloader)
	rootnoverity (hdo,6)
	kernel /boot /grub /core.img

သို႔မဟုတ္

	title Kubuntu Maverick OS (chainloader)
	rootnoverify  (hdo,6)
	configfile/boot/grub.cfg


#####Grub Legacy ကိုခ်ိဳးေဖာက္၀င္ေရာက္ျခင္းမျပဳႏုိင္ရန္ ကာကြယ္ျခင္း

-Grub Legacy ကိုကာကြယ္ရန္ အေရးၾကီးေသာအခ်က္မ်ားကို this section of [the Grub Manual](http://www.gnu.org/software/grub/manual/legacy/grub.htm#Security) တြင္ ၾကည့္ပါ။

-စကား၀ွက္ထည့္သြင္း ကာကြယ္ရန္အတြက္ `/boot/grub/menu.1st` configuration file တြင္ ေအာက္ပါ  command line ကို uncomment လုပ္ပါ (hash သေကၤတကို ဖယ္ထုတ္ပါ။)

#####password topsecret

ထို႔ေနာက္ စကား၀ွက္ထည့္သြင္း၍ သို႔မဟုတ္ [ဤေနရာ](http://www.gnu.org/software/grub/manual/legacy/grub.html1#Security ) တြင္ ျပထားေသာ md5-
encrypted နည္းလမ္းကို အသံုးျပဳ၍ ကာကြယ္ႏုိင္သည္။ menu item မ်ားကို စကား၀ွက္ျဖင့္ ကာကြယ္ရန္ မည္သည့္ item menu ၏ ေခါင္းစဥ္ေအာက္တြင္မဆို ကာကြယ္ထားေၾကာင္း အမွတ္အသားျဖစ္သည့္ lock ကို 
ထည့္သြင္းျခင္းျဖင့္ လုပ္ေဆာင္ႏိုင္သည္။

