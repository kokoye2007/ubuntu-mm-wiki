##USB Creator##

You can make a LiveCD on a USB pendrive using USB Creator and either a LiveCD or an .iso
version of the LiveCD stored on your hard drive. USB Creator is installed by default in Ubuntu.
If not,install:

	sudo apt-get install usb-creator-gtk

-Run:

`Menu` - `System` - `Startup Disk Creator`

Create a boot CD to allow booting from the USB drive

Many computers do not allow booting from a USB drive (but they do allow booting from the
CD-ROM). You can create a CD-ROM using these [Pendrivelinux instrctions](http://www.pendrivelinux.com/make-a-usb-boot-cd-for-ubuntu-9-10/)  and set your BIOS to boot from this CD-ROM. When you boot from this CD-ROOM, it will use the bootup files on the Ubuntu USB drive you previously created (in the step above).


##System Administration##

#####GRUB boot manager settings

######Grub2

Ubuntu 11.04 (Natty) တွင် boot manager အဖြစ် (customize လုပ်ရန် ရှုပ်ထွေးသော) [Grub2](http://www.gnu.org/software/grub/maunal/grub.html) ပါလာပါသည်။ (Grub2 နှင့် grub-pc သည် 
တစ်မျိုးတည်းသာ ဖြစ်သည်။) Grub2 အတွက် ညွှန်ကြားချက်များကို [Ubuntu wiki](http://wiki.ubuntu.com/Grub2) သို့မဟုတ် [Ubuntu forums](http://ubuntuforums.org/showthread.php?t=1195275) များတွင် ကြည့်ရှုနိုင်သည်။ အကြမ်းအားဖြင့်

	sudo nano /etc /default /grub
	sudo grub-mkconfig--output=/boot/grub/grub.cfg


အခြားသောနည်းလမ်းအနေဖြင့် အောက်ပါ command ကို အသုံးပြုနိုင်သည်။

	sudo update-grub


#####Turn off ACPI through GRUB

The new Linux kernel , starting with Karmic ,will attempt to throttle the CPU every few seconds
based on lm-sensors read of CPU temperature and fan speed. If your hardward is not supported
by lm-sensors (like mine), this will cause your system to show down dramatically or even freeze.
As always, this is an ACPI problems, so disabling it at boot often takes of the problem.Edit
the GRUB configuration as above and add the line:

	GRUB _ CMDLINE _ LINUX =acpi=off


Grub2 background image,colors,fonts

-Grub2 အတွက် နောက်ခံပုံရိပ်များ၊ အရောင်များ ၊ Font များ [ဤနေရာတွင်](http://ubuntuforums.org/showthread.php?p=10720685#post10720685) ကြည့်ပါ။

-Grub2 တွင် မည်သည့် နောက်ခံပုံကို သုံးသည်ဖြစ်စေ အသုံးပြုမည့်ပုံကို `/boot/grub` ဖိုင်တွဲတွင် ထည့်၍ Grub2 ကို configure လုပ်ခြင်းဖြင့် အသုံးပြုနိုင်သည်။

	sudo update grub

အသုံးပြုမည့်ပုံသည် `/etc /default /grub` တွင် ရှိသည့် Grub 2 စတင်လုပ်ဆောင်ရန် သတ်မှတ်ထားသော
ပုံအရည်အသွေးနှင့် တူညီရမည်။ (ဥပမာ 1024 x 768)

-ရွေးချယ်ထားသော splashimage များကို `/usr/share/image/grub` ဖိုင်တွဲတွင် ထည့်သွင်း၍ 
  အသုံးပြုနိုင်သည်။

	sudo apt-get install grub2-splashimages

-အသုံးပြုလိုသော ပုံရိပ်တစ်ခုကို `/boot/grub` ဖိုင်တွဲတွင် ထည့်၍ splashimage အနေဖြင့်အသုံးပြုနိုင်သည်။ ဥပမာ

	sudo in -s /usr /share /images /grub /Plasma-lamp.tga/boot/grub
	sudo update-grub

#####Grub 2 အား ချိုးဖောက်ဝင်ရောက်ခြင်း မပြုနိုင်ရန် ကာကွယ်ခြင်း

-Grub2 ကို ကာကွယ်ရန် အရေးကြီးသော အချက်များကို [Grub Manual](http://www.gnu.org/software/grub/manual/grub.html#Security ) တွင် ကြည့်ပါ။

-စကားဝှက်ထည့်သွင်းရန်အတွက် /etc/grut.d/40_custom configuration file တွင် အောက်ပါ command ကို ရိုက်ထည့်ပါ။
	set superusers=user1
	password_pbkdf2 user1 grub.pbkdf2.sha512.10000.biglongstring
	password user1 insecurecleartextpassword


စကားဝှက်နေရာတွင် insecurecleartextpassword အစား သင်၏ စကားဝှက် ထည့်သွင်းအသုံးပြုရပါမည်။
သို့မဟုတ် [ဤနေရာ](http://www.gnu.org/software/grub/manual/grub.html#Security) တွင် ပြထားသော pbkdf2-encrypted နည်းလမ်းကို အသုံးပြု၍ ကာကွယ်နိုင်သည်။ သင်၏ Ubuntu OS Grub2 လုံခြုံရေးနှင့် ပတ်သက်၍ အသေးစိတ်ကို ဤ [Blog](http://www.panoet.com/set-grub-2-password-protection-149) တွင် ဖတ်ရှုနိုင်သည်။

####GRUB Legacy

Boot partition တစ်ခုနှင့် အသုံးပြုရန် GRUB ၏ version အဟောင်းဖြစ်သည့် (Grub [Legacy](http://www.gnu.org/software/grub/manual/legacy/grub.html) ကို ရယူနိုင်သည်။ Grub Legacy ကို ထည့်သွင်းရန်အတွက်

	sudo apt-get install grub

-အကယ်၍ သင့်ကွန်ပျူတာတွင် operation system တစ်ခုထပ်ပိုရှိနေပါက multiple operation systems (OS) ဖြစ်နေပြီး သင်သည် Grub Legacy boot manager ကို သုံးစွဲဖူးပြီး ဖြစ်ကောင်းဖြစ်နိုင်သည်။ Grub Legacy ၏ option များကို menu.1st configuration file တွင် တည်းဖြတ်ပြင်ဆင်နိုင်သည်။ အသေးစိတ်ကို ကြည့်ရှုနိုင်သည်။

	sudo nano /boot /grub /menu.1st

(text editor အဖြစ် nano အစား gedit ကို အသုံးပြုနိုင်သည်။)

####Grub Legacy မှ data များ ရယူ၍ Grub2 တွင် ပြန်လည် အသုံးပြုခြင်း

Grub Legacy မှ data များရယူ၍ Grub2 တွင် အသုံးပြုရန်အတွက် Grub Legacy ၏ menu.1st configuration file တွင် ဤပုံစံဖြင့် မိမိ OS များကို ဖြည့်သွင်းပါ။ (menu.1st ဖိုင်ကို boot partition တွင် သိမ်းဆည်းထားသည်။)

	title Kubuntu Maverisk OS (chainloader)
	rootnoverity (hdo,6)
	kernel /boot /grub /core.img

သို့မဟုတ်

	title Kubuntu Maverick OS (chainloader)
	rootnoverify  (hdo,6)
	configfile/boot/grub.cfg


#####Grub Legacy ကိုချိုးဖောက်ဝင်ရောက်ခြင်းမပြုနိုင်ရန် ကာကွယ်ခြင်း

-Grub Legacy ကိုကာကွယ်ရန် အရေးကြီးသောအချက်များကို this section of [the Grub Manual](http://www.gnu.org/software/grub/manual/legacy/grub.htm#Security) တွင် ကြည့်ပါ။

-စကားဝှက်ထည့်သွင်း ကာကွယ်ရန်အတွက် `/boot/grub/menu.1st` configuration file တွင် အောက်ပါ  command line ကို uncomment လုပ်ပါ (hash သင်္ကေတကို ဖယ်ထုတ်ပါ။)

#####password topsecret

ထို့နောက် စကားဝှက်ထည့်သွင်း၍ သို့မဟုတ် [ဤနေရာ](http://www.gnu.org/software/grub/manual/legacy/grub.html1#Security ) တွင် ပြထားသော md5-
encrypted နည်းလမ်းကို အသုံးပြု၍ ကာကွယ်နိုင်သည်။ menu item များကို စကားဝှက်ဖြင့် ကာကွယ်ရန် မည်သည့် item menu ၏ ခေါင်းစဉ်အောက်တွင်မဆို ကာကွယ်ထားကြောင်း အမှတ်အသားဖြစ်သည့် lock ကို 
ထည့်သွင်းခြင်းဖြင့် လုပ်ဆောင်နိုင်သည်။
