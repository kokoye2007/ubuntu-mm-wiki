#Tips Tricks#

##Run Command##


Run Command အသုံးပြုခြင်း သင့်ရဲ့ စက်အတွင်းက  Application များကို Run Command မှတဆင့် အသုံးပြုနိုင်ပါတယ်။ `Alt + 2` ကိုသုံးပါ။

##Turn off Hot Keys##

###Hot Keys များအား ပိတ်ခြင်း####

ကျွန်တော့အမြင်မှာတော့ ဒါဟာ အလွန်အန ္တရာယ်ရှိတဲ့ လုပ်ဆောင်ချက်တစ်ခုဖြစ်ပါတယ်။။ အစက်လေးတစ်စက်ဟာ
ထင်မှတ်မထားတဲ့ ဘယ်လို အဖြစ်အပျက်မျိုးကို မဆို ဖြစ်သွားစေနိုင်ပါတယ်။ စိတ်မကောင်းစရာအဖြစ်နဲ့ပဲ ဒါဟာ ပြသနာတစ်ခုအဖြစ်နဲ့ Operation System ထဲမှာ ရှိနေပြီး  turn off လုပ်ဖို့လည်း ခက်ခဲပါတယ်။

`Menu` - `System` - `Administration` - `Advanced` - `Input Actions` - `General Settings` - `check` to`Disable KHotKeys daemon`

`Menu`- `System` - `Administration` - `Advanced` - `Input Actions` - `Gestures Settings` -
		`check` to  `Disable mouse gestures globally`

တကယ်လို့သင်က `Disable mouse gestures globally` ကို ရွေးချယ်ချင်ပါတယ်ဆိုရင်တော့  (တခါတရံမှာ အလုပ်မလုပ်ပါ) Desktop ပေါ်က မလိုအပ်တဲ့ Hotkey တွေကို disable လုပ်ပါ။

`Menu` - `System` - `Administration` - `Advanced` - `Keyboard Mouse` - `Keyboard Shortcuts`

ပြီးတော့ သင်က linking gestures to sticky and slow keys ကို deactivate လုပ်ချင်တယ်ဆိုရင်တော့

`Menu` - `System` - `Administration` - `Accessibility` - `Activation Gestures` - `uncheck` to - `Use
	gestures for activating sticky keys and slow keys`

မှတ်ချက်။     ။ သင့်အနေနဲ့ application အတော်များများကို အသုံးပြုမယ်ဆိုရင်  hotkeys တွေကို `disable` လုပ်ထားရပါမယ်။

`Synaptic Touchpad` မှ `hotkeys` များကတော့ 
[Ubuntu documentation](https://help.ubuntu.com/community/Synaptics/Touchpad#Ubuntu) ကို အသုံးပြုပြီး ရွေးချယ်
	turned off ပြုလုပ်နိုင်ပါတယ်။

##Associate default applications##

သက်ဆိုင်ရာ application များအား အလိုအလျောက်ပွင့်ရန်

-Dvd player အလိုအလျောက်ပွင့်လာရန်အတွက် DVD playback လုပ်ဆောင်နိုင်စွမ်းကို ဖွင့်ထားရန်လိုအပ်ပါသည်။ ပထမဦးစွာ
	
`Menu` - `System` - `Administration` - `Advanced` - `File` `Associations` - x - content - video - dvd - `Applications Preferance order` - `Add` တွင် မိမိနှစ်သက်ရာ media player အား ရွေးချယ်ပါ။ ၎င်းတွင် Blu - Ray နှင့် HD DVD 	အတွက် ဆင်တူသော  ရွေးချယ်မှုဇယားရှိပါသည်။ တစ်ခုချင်းစီအား ရွေးချယ်သတ်မှတ်ပေးပါ။

-`MPEG` နှင့် အခြား ရုပ်သံ `Format` များအတွက် အလိုအလျောက် player များသတ်မှတ်ရန်
	
`Menu` - `System` -`Administratio`n - `Advanced` - `File Associations` - `video` -`mpe`g -`Applications Preference order - Add` တွင် သင့်စိတ်ကြိုက်  `media player` ကို ရွေးချယ်ပါ။ .wmv) x -ms -wmv, သို့မဟုတ် Microsoft ၏ WMV format) ,.flv (x-flv, သို့မဟုတ် Flash video ), quicktime စသည် ရုပ်သံဖိုင်ပေါင်းများစွာအတွက် လက်ခံဖွင့်နိုင်မည့် player အားရွေးချယ်အသုံးပြုနိုင်ပါသည်။

-Audacious မှတဆင့် .pls အသံ stream များကို သတ်မှတ်ပေးရန်အတွက် Audacious:

`Menu` - `Syste`m - `Administration` - `Advanced` -`File Associatons` - `audio` - `x` -`scpls` -
	`Applications Preference order` - `Audacious` အား အပေါ်ဆုံးသို့ ရွှေ့ပြောင်း၍ (သို့မဟုတ်)ထည့်ပေးခြင်းဖြင့် လုပ်ဆောင်နိုင်ပါတယ်။

Filename Patterns Section ထဲတွင်တော့ `* .pls`  ရှိနေရန်လိုအပ်သည်။

##User စကားဝှက်အသုံးပြုရန် မလိုပဲ ဝင်ရောက်သောစနစ်##

သွားရောက်ပြင်ဆင်ရန်အတွက် (မှတ်ချက် ၊ User အတွက် password လိုအပ်နေဆဲဖြစ်ပါသည်။ )

`Menu` - `System` -`System Settings` -`Login Manager` -`Convenience` - `Enable Auto` - `Login`	(အမှန်ချစ်) - `Lock session` (အမှန်ချစ်) -`Pre` - select user: `Specified :Choose primary user`

-ဒါကို ပြုလုပ်ရင်တော့ screensaver ကို Password - Portected နဲ့တွဲပြီး လုပ်သင့်ပါတယ်။


##Program များအား bootup လုပ်စဉ် အလိုအလျောက်စတင်စေခြင်း

မည်သည့် program မဆို `~/.config/autostart folder` သို့ program သင်္ကေတ
လမ်းကြောင်း ဖန်တီးပေးခြင်းအားဖြင့် `bootup` ၌ စတင်စေလိုပါက သင်္ကေတလမ်းကြောင်း ဖန်တီးပေးရပါမည်။

	sudo in -s /usr/bin/firefox ~/.config/autostart


##Bootup /Startup service များရွေးချယ်ခြင်း

System ၏ လုပ်ဆောင်ချက်များ တိုးတက်စေရန်အတွက် Startup ပြုလုပ်စဉ်တွင် မလိုအပ်သော/ 
အသုံးမပြုလိုသော service များ စတင်ခြင်းများ မဖြစ်အောင် ကာကွယ်ရပါမည်။

-GTK အား အခြေပြုထားသော Bootup - Manager အား Install ပြုလုပ်ရန်

	sudo apt-get install bum

	
##Bootup-Manager အား အသုံးပြုရန်#
	 
`Menu` - `System` - `Bootup` - `Manager` 


##Menu item မှ Script အား အသုံးပြုခြင်း##

(password စသည့် )တုံ့ပြန်မေးခွန်းများ မေးမြန်းခြင်းများအား ဖြေဆိုရန် script တိုလေးများအား Menu item ထဲတွင် ထည့်သွင်းနိုင်ပါသည်။ အောက်တွင် SSH Negotiation ပြုလုပ်စဉ် password ထည့်ပေးနိုင်သည့် ဥပမာအား ဖော်ပြပေးထားပါသည်။ ပထမဦးစွာ အသုံးဝင်  [expect](http://linux.die.net/man/1/expect) program အား install ပြုလုပ်ပါ။

	sudo apt-get install expect

Menu item တွင် shortcut (သို့) command အသုံးပြုခြင်း ဖြစ်ပါသည်။
