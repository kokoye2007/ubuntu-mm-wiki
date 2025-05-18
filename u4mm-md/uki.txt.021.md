## La TeX##

[La TeX](http://www.latex.project.org/) is a LaTeX is a free high- quality typesetting sytstem for the production of technical and scientific documention.

## LyX

[LyX](http://www.lyx.org/) is a WYSIWYG frontend and GUI interface useful in creating documents formatted for La TeX. Install:

	sudo apt-get install Lyx


####La TeX Reference Managers

-The standard La TeX bibliography (Bib TeX) tool can be manipulated with one of several
tools:

-nbibtex. Install:

	sudo apt-get install nbibtex

-jabref. Install:

	sudo apt-get install jabref



-biblatex. Install:

	sudo apt-get install biblatex



-kbibtex (for KDE) .Install:

	sudo apt-get install kbibtex


-[Zotero](http://www.zotero.org) is a Firefox plugin that allows culling references (and reference content ) from online references.

###Utilities

Utilities facilitate everyday tasks, such as keeping the clock up to date, archiving utilities , and more.

##Archiving Utilities

####ZIP####

The command - line terminal utility [ZIP](http://linux.die.net/man/1/zip) creates files that are compatible with the time - honored PKZIP and WinZip. It is included in (K) Ubuntu by default.
Extracting zip files can be done with unzip utility.using the -P option allows using a 
password for the files.

	zip - r - p mypassword desination.zip

Notes: The -r option indicates to include all subdirectories recursively.

####FileRoller (Archiving GUI)

[FileRoller](http://fileroller.sourceforge.net/features.html) is a GUI for many types of archival utilities.

####X-archiver (Archiving GUI)####

[Xarchiver](http://xarchiver.sourceforge.net/) is a GTK - based GUI front -end for many archiving

utilities. Install:

	sudo apt-get install xarchiver

#### Rar

Rar archives files into the proprietary .rar format.

	sudo apt-get install rar

Note: This application is a 40-day trial.

####Unrar

Unrar extracts files archived with the proprietary .rar format. A free version can be installed:

	sudo apt-get install unrar-free

or the proprietary version (also free for noncommercial use) can be installed with the ubuntu-restricted-extras package or with:

	sudo apt-get install unrar

####7-Zip

The open-source 7-Zip archive format was originally designed for Windows (and DOS) but is also available for Ubuntu. The GNU/Linux version of  7-Zip does not come with a GUI, but Ark 
can hook into 7-Zip to handle 7z archives.Install:

	sudo apt-get install p7zip-full

To allow the 7-Zip extension for Ark to extract .rar files ,also install:

	sudo apt-get install  p7zip-rar

####Hard Drive Utilities

K Disk Free (Hard drive properties monitor)

[K Disk Free](http://docs.kde.org/stable/en/kdeutils/kdf/using-kdf.html) is a KDE utility for 
monitoring free disk space,etc.

	sudo apt-get install kdf



##Clock Utilties

####Screensavers

A screensaver is useful as a security precaution as well as a power and screen element saver.
Using even a simple Blank Screen screensaver with a password can slow a potentially malicious passerby from gaining access to your keyboard and computer while you are away from your 
desk.

	Menu - System - Preferences - Screen Saver

-Set a security password:

	Screen Saver - Lock screen when screensaver is active (ticked)

####Partition Managers

Also see these tips for partitioning scheme suggetions, other partitioning tools and methods, and usage of multiple partitions for multiple OSs.

####G Parted Partition Manager

[Gparted](http://gparted.sourceforge.net/) သည် Hard Drive Partitions ခွဲရာတွင် အသုံးပြုနိုင်သော GTK(Gnome) အခြေပြု ဆော့လ်ဝဲ တစ်ခုဖြစ်ပါသည်။ KDE တွင်လည်း အသုံးပြုနိုင်ပါသည်။

-ဤဆော့လ်ဝဲကို LiveCD ပေါ်မှ အသုံးပြုပါက အကောင်းဆုံးဖြစ်ပါသည်။ နောက်ပိုင်းထွက်ရှိသော Ubuntu
LiveCD များတွင် GParted ဆော့လ်ဝဲကို ထည့်သွင်းထားပြီးဖြစ်သည်။ Ubuntu ကို စက်ထဲတွင် Install
မလုပ်ဘဲ၊ CD မှ တိုက်ရိုက် အသုံးပြုပြီး GParted ကို စတင်နိုင်ပါသည်။]

	Menu-System-Administration -GParted

-အခြားနည်းလမ်းတစ်ခုကား GParted .iso ဖိုင်ကို [ဤနေရာမှ](http://sourceforge.net/project/showfiles.php?group_id=115843package_id=271779) ရယူနိုင်ပါသည်။ ထို .iso ဖိုင်ကို GPartet LiveCD ပြုလုပ်ရန် ဤ [CD Burning Guide](http://help.ubuntu.com/community/BurningIsoHowto) ကို ဖတ်ပါ။ G Parted LiveCD
ကို အသုံးပြုပြီး partitions ခွဲနိုင်မည်ဖြစ်သည်။

-Ubuntu ကို Hard Drive အတွင်း  Install လုပ်ထားပါက Terminal တွင် အောက်ပါ Command ကို ရိုက်ထည့်ပြီး GParted ကို Install လုပ်နိုင်မည်ဖြစ်သည်။

	sudo apt-get install gparted


##System Backup and Recovery


####System Rescue and Cloning Utilities

#####System Rescue CD

[SystemRescueCD](http://www.sysresccd.org/Main_Page) is a LiveCD that includes important utilities such as GParted,Partimage,ddrescue, Rsync , and FSArchiver. Several of these utilities cannot be used from within a running partition, so using them from a LiveCD is often necessary.
[Download](http://www.sysresccd.org/Download) and [burn](http://help.ubuntu.com/community/BurningIsoHowto) the LiveCD from the website.


#####Clonezilla

[Clonezilla](http://clonezilla.org/)allows the backup or duplication of a partition for a single machine or for multiple machines over a network. (It is similar to North Ghost.)It includes
Partimage, [partclone](http://sourceforge.net/projects/partclone/),and other utilities.It is available [here](http://sourceforget.net/projects/clonezilla/files) as a LiveCD which can then be [burned](https://help.ubuntu.com/community/BurningIsoHowto).(A serious limitation of Clonezilla is
its inability to backup/restore split image files to/from multiple media (e.g.spanned DVDs/CDs),limiting its usefulness as an inexpensive cloning and distribution solution.Partition image
backup/restoration must be to/from a single hard drive,large capacity USB stick,or networked storage space)

####Disk Imaging software

[G4U](http://sourceforge.net/projects/g4u/) is a utility to image a disk bit by bit.

[G4L](http://sourceforge.net/projects/g4l/) is a  utility to image a disk bit by bit.It inkcludes a GUI interface.

####Ubuntu Customization Kit

[Ubuntu Customization Kit](http://sourceforge.net/projects/uck) is a utility to customize a (K) Ubuntu LiveCD.Install:

	sudo apt-get install uck

####Remastering software

Debian and (K) Ubuntu Linux operating systems can be remastered and customized (using one of a number off utilities) for re-distribution.[See this Wikipedia list](http://en.wikipedia.org/wiki/List-of-rematering) for distribution among its members,while
preserving the intrinsic architecture and function of (K)Ubuntu.The customized (K) Ubuntu OS can than be distributed on a CD or a USB flashdrive. Users are then free to futher customize
the OS,or even to revent back to the original default(K)   settings. Also see the Ubuntu [wiki](http://help.ubuntu.com/community/InstallCDCustomization).

	oem-config-gtk

	sudo apt-get install oem-comfig-gtk

[Remastersys](http://sourceforge.net/projects/remastersys/Remastersys) for [Ubuntu](http://www.geekconneection.org/remastersys/ubuntu.html) .For tips, see this page. [Reconstructor](https://www.reconstructor.org/projects/reconstuctor/wiki/UserGuide). The open source engine can be [downloaded](https://www.reconstructor.org/projects/reconstutor/files) and installed a.deb package. 


***For tips,see this page.***

Run Ubuntu LiveCD from a USB pendrive

The Ubuntu LiveCD can be installed on and run from a USB pendrive. Settings ca be 
persistently saved (but the LiveCD kerned modules can not be upgraded). Programs can be
installed and run,however ,and files saved to the USB drive. (The installed programs will remain
installed). An Ubuntu Live CD is needed to do the installation. For additional info, see the [Ubuntu Community documentation](http://help.ubuntu.com/community/Installation/FromUSBStick) or the [Pendrivelinux instructions](http://www.pendrivelinux.com/creating-an-ubuntu-live-usb-from-cd/).

The USB LiveCD can be used to install Ubuntu on computers (including netbooks) that do not
have CD-ROM/DBD drives.

USB pendrives to be used to run Ubuntu should have a minimum of 2 Gb(preferably 4 Gb).If
you wish to install a fast, fully functional Linux system on a pendrive that has less memory than
that, use [PuppyLinux](http://www.puppylinux.org/) or [Lubuntu](https://wiki.ubuntu.com/Lubuntu).
