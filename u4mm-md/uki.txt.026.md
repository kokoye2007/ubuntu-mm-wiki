#Password chceker and enforcement#

###[John the Ripper](http://www.openwall.com/john/) Password စစ်ဆေးမှုနှင့် အတည်ပြုမှု###

John the Ripper သည် Dictionary ၏ password များအား ဖျက်ရန်အတွက် အခမဲ့အသုံးပြုနိုင်သော open source ဖြစ်ပြီး ယေဘုယျအားဖြင့် ၄သန်းခန့် ဘာသာပေါင်းစုံဖြင့် အသုံးပြုနေကြသည်။ အဘယ်ကြောင့်ဆိုသော်
ဤ program သည် ကျယ်ကျယ်ပြန့်ပြန့်နှင့် လွယ်လင့်တကူ ရနိုင်သောကြောင့် ဖြစ်ပြီး  မိမိ၏ ကွန်ပြူတာ နှင့် LAN ၏  password များအား  စစ်ဆေးခြင်း၊ လုံခြုံအောင် ပြုလုပ်ခြင်းများအတွက်လည်း ၏
အသုံးဝင်သောကြောင့်ဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install john

[Passwdqc](http://www.openwall.com/passwdqc/) သည် password များ၏ ကြံ့ခိုင်မှုအားအတည်ပြုပေးရန်အတွက် သုံးသော module တစ်ခုဖြစ်သည်။ Install ပြုလုပ်ရန်

	sudo apt-get install passwdqc


#MD5Sum#

File တစ်ခု၏ MD5 sum များအား စစ်ဆေးရန်အတွက် သုံးသော command line တစ်ခုဖြစ်သည်။

	md5sum filename

မှတ်ချက်။  ။ Filenames with spaces

###Spaces ခံ၍ အမည်ပေးထားသော File များ###

-`Spaces` ခံ၍ ရိုက်နှိပ်ထားသော File နှင့် Folder အမည်များအား မျက်တောင် အဖွင့် အပိတ်များ `( )` များ ထည့်အသုံးပြုသင့်သည်။ ဥပမာအားဖြင့် This Dir အမည်ပေးထားသော directory တစ်ခု သို့မဟုတ်
	`/home/This Dir` အမည်ရှိ directory တစ်ခုအား ပြောင်းလဲချင်ပါက အောက်ပါ command 
	အား အသုံးပြုရမည်။

	cd This Dir

သို့မဟုတ်

	cd/home/This Dir

-တစ်နည်းအားဖြင့် `backslash (/)` ကို space နေရာမှာ အစားထိုးခြင်းဖြင့်လည်း အသုံးပြုနိုင်ပါသည်။

This Dir အမည်ပေးထားသော directory တစ်ခု သို့မဟုတ် `/home/This Dir` အမည်ရှိ directory တစ်ခုအား ပြောင်းလဲချင်ပါက 

	cd This /Dir 

သို့မဟုတ်

	cd/home/This /Dir


#Alien#

[Alien](http://kitenet.net/~joey/code/alien/) သည် (Red Hat) .rpm packages များကို  (Debian).deb packages များအဖြစ်သို့ ပြောင်းလဲပေးသော ဖိုင်ပြောင်းနည်းတစ်ခုဖြစ်သည်။ ဒီနည်းဟာ စိတ်ချရတဲ့နည်းမဟုတ်သလို ပြောင်းလိုက်တဲ့ package တွေရဲ့ function တွေကို သေချာပြန်စစ်ဆေးပေးဖို့လိုအပ်ပါတယ်။ များသောအားဖြင့် စာကြောင်းတွေ ပြန်ပြောင်းပေးဖို့ လိုအပ်ပါတယ်။ Source ကနေ `(Debian).deb package` ကို ပြောင်းပေးခြင်းက ပိုပြီးစိတ်ချရပါတယ်။ Alien software ရဲ့ maintainer တွေ ကိုယ်တိုင်ကိုက important package တွေကို ဖိုင်ပြောင်းတဲ့အခါ Alien ကို အသုံးမပြုစေချင်ကြပါဘူး။ Alien ကို version နံပါတ်တွေ ပြောင်းတာကနေ ထိန်းထားချင်တယ်ဆိုရင်တော့ ဖော်ပြပါ command ကို ရိုက်ထည့်ပေးပါ။

	alien - k rpm _file _name.rpm

.rpm ကို .deb အဖြစ်ပြောင်းနည်း

	alien - d package - name .rpm

.rpm ကို .deb အဖြစ်ပြောင်းပြီး ရလာတဲ့ file ကို တစ်ခါတည်း install လုပ်ရန်

	alien - i package - name .rpm

.rpm ကို Debian အဖြစ်ပြောင်းရန်

	sudo alien - k  .rpm
	

#Software Troubleshooting#

####Program အစတွင် လုပ်ပိုင်ခွင့် Error တက်ခြင်း##

အကယ်၍  သင့်တွင် လုပ်ပိုင်ခွင့် Error တစ်ခုတက်လာပါက ဖော်ပြပါအတိုင်း လုပ်ဆောင်ပါ။

	sudo chown - R user /home/user

မှတ်ချက် ။    user ဆိုသော နေရာတွင် သင့် username အမှန်အား ထည့်ပေးပါ။ ဤ command သည် folder ၏ ပိုင်ရှင်အား ပြောင်းလဲပေးမည်ဖြစ်သည်။ `-R` အပါအဝင်  (recursively ) ကိုဆိုလိုပြီး folder အခွဲများပါ ပါဝင်ပါသည်။


##CD - ROM Troubleshooting##

###CD - ROM Error အားဖြေရှင်းခြင်း###

အကယ်၍ သင် CD burner အသုံးပြုပြီး  burn နေ့စဉ်အတွင်းမှာ `cdrecord has no permission to open the device` ဆိုတဲ့ Error တက်လာပါက terminal ကို ဖွင့်ပြီး

	sudo chmod 777 /dev /scd0

လို့ ရိုက်လိုက်ပါ။

မှတ်ချက်။ `/dev/scd0` နေရာတွင် သင့် device အားထည့်ပေးပါ။
မှတ်ချက်။ `chmod 777` သည် folder အား လုပ်ပိုင်ခွင့်အပြည့်အစုံပေးလိုက်သည့် universal option ဖြစ်သည်။ `777` ဆိုသော ဂဏန်းသည် ရေးခြင်း၊ ဖတ်ခြင်း ၊လုပ်ဆောင်ခြင်း စသည့် လုပ်ပိုင်ခွင့် တု့ိကို အသုံးပြုသူအား အပြည့်အ၀ ပေးလိုက်သည်ဟု အဓိပ္ပါယ် ရသည်။
