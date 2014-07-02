ဆိုဒ္မွ အခမဲ့သြားေရာက္ Download ျပဳလုပ္ႏိုင္ပါတယ္။

###Change Plymouth Splash Screen 

Bootup မွာျမင္ရတဲ့ဟာက ကနဦး Splash Screen ျဖစ္ၿပီး အျခားေသာ Plymouth Themes ေတြကို Package Manger မွာသြားေရာက္ ရွာေဖြႏိုင္ပါတယ္။ အသစ္တစ္ခုကို Install ျပဳလုပ္ခ်င္ရင္ေတာ့

	sudo update-alternatives --config default.plymouth
	sudo update-initramfs -u

မိမိႀကိဳက္ႏွစ္သက္ရာ Theme ကို ေရြးခ်ယ္၍ တင္ႏိုင္ပါသည္။ Plymouth ကေတာ့ Bootup ျပဳလုပ္ေနတဲ့အခ်ိန္မွာ မႀကာခဏ Blacnk Screen မ်ားေပၚေပါက္ျခင္းနဲ႕ nVidia Drivers ေတြ ခ်က္ျခင္း အလုပ္မလုပ္ေဆာင္ႏိုင္ေသးပါဘူး။

###Change USplash Boot Screen

	sudo apt-get install splashy splashy-themes

###Metacity

Metacity ဆိုတာက Gnome မွာပါတဲ့ မူလ Desktop Compositing Manager ပါ။ သူက ေပါ့ပါးျခင္း၊
ခ်က္ျခင္းေျပာင္းလြဲျခင္း (streamlined) ေတြနဲ႕အတူ မ်ားမ်ားစားစားလဲ ျပဳျပင္ေျပာင္းလြဲစရာမလိုတဲ့ Options ေတြပါ၀င္သလို Gnome Look မွာေတာ့ Multiple Themes ေတြ ခ်က္ျခင္း ေဆာင္ရြက္ႏိုင္ျပန္တယ္။

###Compiz Fusion 

Compiz Fusion က window manager နဲ႕ သီးျခားကြဲျပားပါတယ္။ သူက Desktop effects ေတြကို 
အဆင့္ျမင့္ ေျပာင္းလြဲႏိုင္တာျဖစ္ၿပီး Cube တံုးသဖြယ္မ်ိဳး Desktop ကို ေျပာင္းလဲဖန္တီးႏိုင္တာေတြလဲ
ပါ၀င္ပါတယ္။Ubuntu Users ေတာ္ေတာ္မ်ားမ်ားက Compiz ကိုေရြးခ်ယ္ အသံုးျပဳႀကပါတယ္။ဒါကို Ubuntu မွာ အခ်ိန္ခဏေလးနဲ႕ အလြယ္တကူ Install ျပဳခ်င္ရင္ေတာ့

	sudo apt-get install compiz compizconfig-settings-manager compiz-fusion-plugins-maincompiz-fusion-plugins-extra emerald librsvg2-common

Compiz ကို Window Manager အျဖစ္ထားခ်င္ရင္ေတာ့ Compiz Configuration မွာ ေအာက္ကအတိုင္း သြားေရာက္ေရြးခ်ယ္ေပးယံုပါပဲ

	Menu - System -Preferences - CompizConfig Settings Manager

မွတ္ခ်က္ ။ ေျပာင္းလြဲထားတာေတြကို အဆင္ေျပဖို႕က Process ၿပီးသြားရင္ Logout လုပ္ၿပီးေတာ့ Login ျပန္လုပ္မွသာ ေျပာင္းလြဲျခင္း effect ကို ျမင္ရမွာျဖစ္ပါတယ္။

###Virtualization

Coming Soon!!!

###Moonlight

See Moonlight plugin for Firefox

###Java

Java install လုပ္ရန္

	sudo apt-get install default-jre

###DosBox

[DosBox](http://www.dosbox.com/) သည္ DOS-emulator (ဆက္စပ္ကိရိယာ) program တစ္ခုျဖစ္သည္။ ၄င္းသည္ `CPU:286/386 realmode/protected mode, Directory FileSystem/XMS/EMS, Tandy/Hercules/CGA/EGA/VGA/VESA grahpics` ႏွင့္ `SoundBlaster/Gravis Ultra Sound card` (ယခင္ဂိမ္းအေဟာင္းမ်ား၏ အသံျဖင့္လိုက္ေလ်ာညီေထြျဖစ္ေစရန္) အသံုးျပဳသည္။ သင္သည္ယခုေခတ္ ကြန္ပ်ဴတာမ်ားေပၚတြင္ ေဆာ့မရေတာ့ေသာ ယခင္ဂႏၶၶၶ၀င္ ဂိမ္းမ်ားအားျပန္လည္အသက္သြင္းႏိုင္ပါလိမ့္မည္။

	sudo apt-get install dosbox

###Scumm VM

[Scumm VM](http://scummvm.org/) သည္ ရုပ္ပံုမ်ားအားညႊန္ၿပျခင္း၊ Click လုပ္ျခင္းစသည့္
ဂိမ္းေဟာင္းမ်ားအား လက္ခံ၍ run ေပးပါသည္။(သင့္တြင္ ၄င္းတို႕၏ ေဒတာဖိုင္မ်ားရွိရပါမည္။) Scumm VM သည္ executables shipped မ်ားတြင္ ေနရာယူ၍ ဂိမ္းမ်ားကို Linux OSတြင္ ကစားခြင့္ေပးမွာျဖစ္ပါတယ္။

	sudo apt-get install scummvm

###Edutainment Applications 

p-26(မရိုက္ထား)

###Google Earth

[Google Earth](http://earth.google.com/) မွ သင့္အား ကၽြႏ္ုပ္တို႕ကမၻာၿဂိဳလ္ႀကီးကို အေပၚစီးက
ျမင္ေတြ႕ခြင့္ေပးမွာျဖစ္ပါတယ္။ဒီ software ဟာ အခမဲ့ package ျဖစ္ပါတယ္။ (ဒီ package ကိုအသံုးျပဳဖို႕အတြက္ License ကို accept လုပ္ရမွာျဖစ္ပါတယ္။)

	sudo apt-get install googleearth-package
	make-googleearth-package --force

ရရွိလာတဲ့ .deb file ကို click ၂ခ်က္ႏွိပ္ပါ။ (သို႕မဟုတ္) Linux အတြက္ ေနာက္ဆံုးထြက္ရွိထားတဲ့ package ကို install လုပ္ရန္အတြက္ [Google Earth downloads](http://earth.google.com/intl/en/download-earth.html) ကိုသြားၿပီး Download ဆြဲပါ။ ၿပီးရင္ ေအာက္က
command နဲ႕ install လုပ္ပါ။  

	wget http://dl.google.com/GoogleEarthLinux.bin/
	chmod  +x GoogleEarthLinux.bin ./GoogleEarthLinux.bin

####အသံုးျပဳရန္

	Menu - Application -Internet -Google Earth 3D planet viewer

သင့္အေနနဲ႕ Google Earth -View မွာရွိတဲ့ Atmosphere setting ကို turn off လုပ္ထားသင့္ပါတယ္။
ဘာေႀကာင့္လဲဆိုေတာ့ တိမ္ေတြဖံုးေနတာေႀကာင့္ ေျမျပင္ကို ျပမွာမဟုတ္လို႕ပါဘဲ။

####Troubleshooting

Troubleshooting (ျပင္ဆင္ျခင္း) အကယ္၍ Google Earth ကိုဖြင့္လိုက္တယ္။ Loading ျပဳလုပ္တယ္။ loading ျပဳလုပ္တဲ့ screen တတ္လာၿပီး error ျပမယ္။ဒါမွမဟုတ္ ဘာမွမေပၚေတာ့ဘူးဆိုရင္ေတာ့ သင္ဟာ ျဖစ္ေလ့ျဖစ္ထရွိတဲ့ error တတ္ျခင္းကိုေတြ႕ႀကံဳေနရပါၿပီ။အဲဒီလိုျဖစ္ေနခ်ိန္မွာ Google Earth ကို Terminal ကေန `~/google-earth/googleearth` လို႕ရိုက္ၿပီး run လိုက္ရင္ `./googleearth-bin: relocation error:/usr/lib/i686/cmov/libssl.so.0.9.8: symbol BIO-test-flags, version OPENSSL-0.9.8 not defined in file libcrypto.so.0.9.8 with link time reference` ဆိုတဲ့ error ကိုျပပါလိမ့္မယ္။

ဒီၿပႆနာကိုေျဖရွင္းဖို႕အတြက္သင္ Google Earth ကိုသြင္းထားတဲ့ Folder ကိုဖြင့္လိုက္ပါ။ပံုမွန္အားျဖင့္ေတာ့ Google Earth ဟာ သင့္ home folder ထဲမွာပဲ ရွိေနတတ္ပါတယ္။ ၿပီးရင္ `libcrypto.so.0.9.8` ကိုရွာၿပီး `libcrypto.so.0.9.8.bak` လို႕ေျပာင္းလိုက္ပါ။ Google Earth ဟာ ပံုမွန္အတိုင္း သံုးလို႕ရသြားပါလိ္မ့္မယ္။

	cd ~/google-earth
	sudo mv 
