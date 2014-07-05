Tips for Ubuntu-MM
==================

###`$`
Terminal မွ　User ၏　Command Prompt ကိုဆိုလိုျခင္းျဖစ္သည္။　Online မွ　Blog မ်ား　Tutorial မ်ားတြင္　Command မ်ားကိုေဖာ္ျပရာ၌　ထည့္သြင္းေဖာ္ျပေလ့ရွိသည္။　သို႔ေသာ္　ထို　Command အား　ကူးယူ　အသုံးျပဳရာတြင္　ထည့္သြင္းအသုံးျပဳစရာမလိုပါ။　`$ sudo apt-get update` ဟုေဖာ္ျပထားပါက　`sudo apt-get update` ဆိုေသာ　command　 သာကူယူအသုံးျပဳရန္လိုအပ္သည္။ 

`$` အား　စာလုံးတစ္ခ်ိဳ႕ႏွင့္　ကပ္၍အသုံးျပဳထားပါက　shell variable အျဖစ္　သတ္မွတ္ထားသည္ကို　ျပန္လည္ေခၚယူ　အသုံးျပဳျခင္းျဖစ္သည္။　
```sh
$ var="Hello"
$ echo $var
Hello
```
အဆိုပါဥပမာရွိ　line တစ္ခုခ်င္း၏　ေရွ႕တြင္ေတြ႕ရေသာ　`$` သည္　Command Prompt ကိုဆိုလိုျခင္းျဖစ္ၿပီး　ဒုတိယ　line တြင္ျပထားေသာ　$var သည္　shell variable ကိုဆိုလိုျခင္းျဖစ္သည္။

---
###`#`
`$` ကဲသို႔ပင္　Command မ်ား၏ေရွ႕တြင္　ေဖာ္ျပေလ့ရွိသည္။　`root　user` `super user` အေနျဖင့္　အသုံးျပဳထားေသာ　Terminal ၏　Command Prompt ကိုဆိုလိုျခင္းျဖစ္သည္။　သာမန္　User Prompt `$` မွ Root User Prompt `#` သို႔ ေျပာင္းလိုပါက - `sudo -s` command ျဖင့္ေျပာင္းႏိုင္သည္။
```sh
$ sudo -s
[sudo] password for user: 
# 
```

---
###` ~/ `
သင္၏ `Home Directory` ကိုဆိုလိုျခင္းျဖစ္သည္။ တနည္းအားျဖင့္ `/home/yourname` ႏွင့္တူညီသည္။

```sh
$ cd ~/
$ cd /home/yourname
```

---
###` ./ `
Terminal တြင္ သင္ေရာက္ရွိေနေသာ လက္ရွိ Directory ကို ဆိုလိုသည္။ Executable file မ်ားကို terminal မွတဆင့္ run ေသာအခါတြင္အသုံးျပဳေလ့ရွိသည္။ ဥပမာတြင္ျပထားသည္မွာ လက္ရွိ ေရာက္ရွိေနေသာ Directory ထဲမွ script ဆိုေသာ Executable File ကို run လိုက္ျခင္းျဖစ္သည္။

```sh
$ ./script
```

---
###` . `
File သို႔မဟုတ္ Folder တို႔၏ အမည္ေရွ႕တြင္ `.` ထည့္ပါက ထို File/Folder သည္ File Manager ထဲတြင္သာမန္အားျဖင့္ ျမင္ရမည္မဟုတ္ပါ။ ထို File/Folder မ်ားအား File Manager တြင္ ျမင္ႏိုင္ေစရန္ `Control + H` Key အား ႏွိပ္၍ ေဖာ္ႏိုင္သည္။ အမ်ားအားျဖင့္ System Configuration file မ်ား folder မ်ားတြင္အသုံးျပဳေလ့ရွိသည္။ User ၏ Home Directory `~/ ` ထဲတြင္ `.local`, `.config` စသျဖင့္ေတြ႕ႏိုင္သည္။

---
###`sudo`
`root` တနည္းအားျဖင့္ `super` user အေနျဖင့္ command မ်ား executable file မ်ားအား run ေသာအခါတြင္　သုံးသည္။ Windows တြင္ Administrator အေနျဖင့္ အသုံးျပဳသည္ႏွင့္ တူညီသည္။

---
###Command, Option and Parameter
Terminal တြင္း　အသုံးျပဳေသာ　command မ်ားသည္　အမ်ားအားျဖင့္　လက္ရွိေရာက္ရွိေနေသာ　Directory ႏွင့္　အတြင္းရွိ　File/Folder မ်ားတြင္သာ　သက္ေရာက္သည္။　အထူးထပ္မံျဖည့္စြက္လိုက္ေသာ　Options မ်ား　Parameter မ်ားေပၚမူတည္၍သာ　အေျပာင္းအလဲမ်ားရွိသည္။　ဥပမာျပရလၽွင္　`ls` command သည္　လက္ရွိေရာက္ရွိေနေသာ　Directory ထဲမွ　File/Folder စာရင္းကို　ျပေပးသည္။　`ls /usr/share` ဟူ၍　parameter အေနျဖင့္　Directory Path `/usr/share` ကိုထည့္ပါက　ထို　Directory ထဲမွ　File/Folder မ်ားကိုျပေပးမည္ျဖစ္သည္။ 

Blog မ်ား　Tutorial မ်ားတြင္ေဖာ္ျပထားေသာ　Linux Command မ်ားအား　ကူးယူအသုံးျပဳရာတြင္　Error မ်ား　တက္ႏိုင္ပါသည္။　အခ်ိဳ႕ Command မ်ားမွာ မိမိ Install ျပဳလုပ္မထားျခင္းေၾကာင့္　ျဖစ္ႏိုင္သလို　ကူယူရာတြင္　text format လြဲေခ်ာ္ျခင္းေၾကာင့္လဲျဖစ္ႏိုင္ပါသည္။

Command မ်ားသည္　အမ်ားအားျဖင့္　ေအာက္ပါ　format အတိုင္းရွိတတ္ပါသည္။

```sh
$ wget -O skype-ubuntu-current_i386.deb http://www.skype.com/go/getskype-linux-beta-ubuntu-32
```
အဆိုပါစာေၾကာင္းတြင္ `wget` သည္ Internet ရွိ File မ်ားအား terminal မွတဆင့္ Download ျပဳလုပ္ရာတြင္သုံးေသာ command တစ္ခုျဖစ္သည္။　`-O` သည္　command ၏　Option ျဖစ္သည္။ Download ဆြဲလိုက္ေသာ file အား နာမည္တစ္ခုျဖင့္ ေျပာင္းလဲေစလိုလၽွင္သုံးပါသည္။ `-O` ေနာက္တြင္ရွိေသာ `skype-ubuntu-current_i386.deb` သည္ ေျပာင္းလဲလိုေသာ File နာမည္ျဖစ္ၿပီး ၄င္း၏ေနာက္ရွိ `http://www.skype.com/go/getskype-linux-beta-ubuntu-32` သည္ Download ျပဳလုပ္မည့္ File ရွိရာလမ္းေၾကာင္း (Link) ျဖစ္သည္။ ထို အစိတ္အပိုင္းတစ္ခုစီ၏ ၾကားတြင္ Space ျခားထားသည္ကို သတိျပဳရန္လိုအပ္သည္။

"wget```space```-O```space```skype-ubuntu-current_i386.deb```space```http://www.skype.com/go/getskype-linux-beta-ubuntu-32"

Command မ်ားအသုံးျပဳရာတြင္ `-`, `--`, ႏွင့္ Space တို႔ကို အထူးက႐ုျပဳရမည္ျဖစ္ၿပီး လြဲေခ်ာ္ေနပါက ထို Command အလုပ္လုပ္မည္မဟုတ္ပါ။

---
