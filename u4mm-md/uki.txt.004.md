**ဥပမာ** Destop version GUI installer ကိုအသုံးပြု၍ installation ပြုလုပ်နေစဉ်အတွင်း အဆင့်တစ်ခုတွင် အောက်ပါအတိုင်းပေါ်လာမည်ဖြစ်သည်။

	Summary > Advanced > Device for boot loader installation: /dev/sda6

အထက်ပါ ဥပမာတွင် ထိုအခြေအနေအတိုင်း ထားရှိပါက GRUB2 bootloader သည် `/dev/sda6` ((K)Ubuntu OS ထည့်သွင်းထားသည့် Harddisk Partition ) အတွင်းသို့သာ ရောက်ရှိသွားမည်ဖြစ်ပြီး MBR (Master Boot Record) ကိုပြောင်းလဲမည်မဟုတ်ပါ။သို့သော် `/dev/sda` ၏ default setting တွင်ထားရှိလိုက်ပါက GRUB2
သည် `/dev/sda6` ((K)Ubuntu OS ထည့်သွင်းထားသည့် Harddisk Partition ) အတွင်းသို့
ရောက်ရှိသွားမည် ဖြစ်သည့်အပြင် MBR  (Master Boot Record) ကိုလည်း ပြုပြင်ပြောင်းလဲသွားပါမည်။ ထိုအခါ GRUB2 သည် ကွန်ပျူတာပေါ်တွင် ထည့်သွင်းထားသည့် Operation System  အားလုံး၏ master bootloader အဖြစ်ပြောင်းလဲသွားမည်ဖြစ်သည်။အခြားသော bootloader (GRUB2 မဟုတ်သည့်) များကို အသုံးပြုနေသူဖြစ်လျှင် ထိုအခြေအနေသည် အဆင်ပြေမည်မဟုတ်ပါ။

##Start Manager ကို အသုံးပြု၍ Grub ၏ setting များကို ပြောင်းလဲခြင်း

Grub သည် (Operation System ၁ခုထပ်ပို၍ ထည့်သွင်းထားသော ကွန်ပျူတာများတွင်) မည်သည့် OS ကို ပုံမှန် ဦးစားပေးအနေဖြင့် စတင်လည်ပတ်စေမည်ကို သတ်မှတ်ခြင်းနှင့် အခြားသော bootup setting များကို ထိန်းချုပ်သည့် bootup utility ၁ခုဖြစ်သည်။ [Startup Manager](http://sourceforge.net/projects/startup-manager/) ကို အသုံးပြု၍ Grub ၏ setting  များကို ပြောင်းလဲနိုင်သည်။ Startup Manager သည် Grub (Grub Legacy ), Grub 2, Usplash, and Splashy စသည့် bootloader များ၏ setting များကို ကွပ်ကဲရာတွင် အသုံးပြုသည့် software ဖြစ်သည်။ Startup Manager အသုံးပြုပုံကို [ဒီနေရာ](https://help.ubuntu.com/community/StartUpManager) တွင်ကြည့်ရှုနိုင်သည်။ Startup Manager ထည့်သွင်းရန်အတွက်

	sudo apt-get install startupmanager menu

Startup Manager လည်ပတ်စေရန်

	Menu > System > Administration > Startup Manasger

>**မှတ်ချက်** Grub setting များကို command-line interface မှလည်း ပြောင်းလဲပြင်ဆင်နိုင်သည်။

##Mac OS X နှင့် Ubuntu ကို ကွန်ပျူတာတစ်လုံးတည်းပေါ်တွင် ယှဉ်တွဲတင်ခြင်း

Mac OS X သည် Linux နှင့် တည်ဆောက်ပုံ ဆင်တူသည် (Max OS X သည် BSD Unix ကို
အခြေခံထားခြင်းဖြစ်သည်။) Mac OS X နှင့် Ubuntu ကို ယှဉ်တွဲတင်ခြင်းနှင့် ပတ်သတ်သော
အသေးစိတ်လမ်းညွှန်ချက်များကို [ဒီနေရာတွင်](http://help.ubuntu.com/community/MacBook) တွင်လေ့လာနိုင်သည်။

###Ubuntu ရှိပြီးသား ကွန်ပျူတာပေါ်တွင် Mac OS X တင်ခြင်း

Ubuntu ကို Mac OS X နှင့် ယှဉ်တွဲတင်မည်ဆိုပါက Ubuntu ကို ထည့်သွင်းမည့် Harddisk Partition ကို ext2 ကို ရွေးချယ်ပါ။ (ထိုလုပ်ငန်းစဉ်အတွက် Super Grub Disk CD သည် အသုံးဝင်သော utility ဖြစ်သည်။) Super Grub ISO ဖိုင်ကို [ဒီနေရာတွင်](http://supergrub.forjamari.linex.org) တွင် download ရယူနိုင်သည်။

Ubuntu ကို ထည့်သွင်းပြီးပါက Grub start-up list ကို ပြင်ဆင်ပြောင်းလဲပါ။

	sudo nano /boot/ grub/menu.1st

ထို့နောက် အောက်ပါစာကြောင်းများကို ထပ်ပေါင်းထည့်ပါ။

	title Mac OS X root (hd0,0) makeactive chainloader + 1

ပြီးလျှင် Mac ကို reboot လုပ်၍ Mac OS X  တွင်ပါဝင်သော Terminal ကို သွားပါ။ (boot လုပ်ရာတွင်
အခက်အခဲရှိပါက Mac OS X DVD ကိုအသုံးပြု၍ boot လုပ်ပါ။) F8 ကိုနှိပ်၍ -s ဟု ရိုက်ထည့်ပါ။ ထို့နောက် ရိုက်ထည့်ရမည့်စာကြောင်းများမှာ `fdiskn -e /dev/rdisk0 flag 2` (flag 2သည် ယခုဥပမာ၏ Harddisk Partition number 2 ဖြစ်သည်။ သင်၏ Mac တွင် အသုံးပြုထားသည့် Partition number ပေါ်တွင် လိုက်၍ပြောင်းလဲနိုင်သည်။) quity reboot ပုံမှန်အလုပ် လုပ်ဆောင်နိုင်ပြီဟု မသေချာသေးပါက Super Grub Disk CD ကို အသုံးပြု၍ Grub ကို active 
လုပ်ပါ။

###Mac OS X ရှိပြီးသား ကွန်ပျူတာပေါ်တွင် Ubuntu တင်ခြင်း

Booth လုပ်နေစဉ်အတွင်း boothloader တွင် ပုံမှန်လုပ်ဆောင်နေခြင်းမရှိဟု သတင်းပို့ချက် (ဥပမာ HFS+error) များပေါ်လာပါက Super Grub ကိုအသုံးပြု၍ Linux GRUB နှင့် MBR (Master Boot Record) ကို ပြန်လည်ပြင်ဆင်နိုင်သည်။ Ubuntu ကို ထည့်သွင်းပြီးပါက Grub start-up list ကိုပြင်ဆင်ပြောင်းလဲပါ။

	sudo nano /boot/grub/menu.1st

ထို့နောက် ထပ်ပေါင်းထည့်ရမည့် စာကြောင်းများမှာ

	title Mac OS X root (hd0,0) makeactive chainloader +1

အကယ်၍ သင်သည်GRUB တွင် Mac OS X သို့မဟုတ် Windows နှင့်ပတ်သတ်၍ အခက်အခဲဖြစ်နေပါက Mac OS X ၏ Grub ရှိ entry ကို "root (hd0,1) သို့ပြောင်းလဲပါ။ထိုသို့ပြောင်းလဲခြင်းဖြင့် သင်၏ကွန်ပျူတာသည် Partition number 1 ကို boot လုပ်ပါလိမ့်မည်။Grub
မှန်ကန်စွာအလုပ်လုပ်ဆောင်နိုင်သည်အထိ partition number ကို
