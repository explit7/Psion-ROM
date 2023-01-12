
BUG FIX PATCHES FOR PSION NETBOOK OPERATING SYSTEM IMAGE FILE

Patches by Poke^Patisoners

Taken from
http://portal.vakoveverky.net/modules/articles/article.php?id=6

Current release of netBook OS image cumulative patch file is: c1.60a.


SUPPORTED PLATFORM
Psion netBook


SUPPORTED EPOC OPERATING SYSTEM IMAGE FILES

* NB_450UK.IMG - Version: 1.05 (450) – English (UK) – ASCII (Release 158)
* NB_453US.IMG - Version: 1.05 (453) – English (US) – ASCII (Release 158)
* NB_456FR.IMG - Version: 1.05 (456) – French (FR) – ASCII (Release 158)
* NB_457GE.IMG - Version: 1.05 (457) – German (GE) – ASCII (Release 158)
* NB_462SP.IMG - Version: 1.05 (462) – Spanish (SP) – ASCII (Release 158)
* MB_281UK.IMG - Version: 1.05 (281) – English (UK) – ASCII (Release 158) (for mBook)

KEYWORDS

Psion, Epoc, Operating System (OS) image file, patching process, bug fix, bpatch tool, PsiRom tool


ABSTRACT
Article describe about some bugs in actual Psion netBook operating system. In article is published cumulative bug fix patch and explained method how fixing this bugs against actual Psion netBook OS image file ver. 1.05 (rel.158). If someone use another language variant of image file than is in support list and needs my patches for your language variant of OS.IMG file, please contact me and I try prepare patch file for your language variant.

MOTIVATION
I was Psion 5mx owner from 2001. I upgraded to netBook at end of 2003. After some happy days with my new machine I find that last Psion netBook OS.IMG file (rel.158) have absolutely apparent bugs (wrong or greyscale icons, bad OPL toolbar and etc...). I assume that properly testing from times of Protea Bill Batchelor’s beta tester team, new Psion’s Teklogix team not done. It was sad but true. Maybe final build of OS image was made in hurry and without deep beta testing.
I begin fix this bugs especially for me. Later, I present this bug fix to other people. Omega (osg) (another member of Patisoners team) convinces me for releasing my bug fixes for all netBook users. So, I make it now.
This cumulative patch file is distributed in the hope that it will be useful, but without any warranty. Otherwise, I use patched OS image about several months without problems. Basically, I was created this cumulative patch file primary for myself, but if you want use it too.

RESULTS
Actual patch file fix this bugs and issues of original Psion netBook OS image file (Rel.158):

* Wrong OPL Toolbar main battery status icon (toolbar.opo and toolbar source). (bug fix)
* Shell stretch icons in 4 grey colour mode only. (bug fix)
* Wrong InstApp.aif icons and caption. (bug fix)
* EikConsole text selection bug. (bug fix)
* Backup battery status visible on OPL Toolbar (toolbar.opo and toolbar source). (improvement)
* Colour EikConsole support. (improvement)
* Visible Z: drive (RomDrive) in shell listbox. (improvement)

More about all netBook OS image bugs and bug fixes you can read next articles in near future.


HOW APPLY PATCH
This patch directly modified binary file of OS.IMG, so you need download this image before patching. You also need installed bpatch tool, and patch file (typically *.dif) file. If you don't know how use bpatch tool, please read bpatch tool article.

Actual Psion netBook OS.IMG file you can download here.
Actual Psion MalayBook (mBook) OS.IMG you can download here.

Actual GNU bpatch tool for many platforms (Windoze, Linux, Epoc, EpocEmx) and with sources you can download here.

Actual patch file for NB_450UK.IMG (or other os image) you can download here.

Step-by-step procedure is:
1) Download and install GNU bpatch tool file archive, for your operation system.
2) Download and unzip my cumulative patch file archive.
3) Download original Psion's OS image file archive.
4) Unzip all files from original Psion's image zip archive.
5) Apply my patch file to the original Psion netBook OS image. 

For example type:

bpatch C:NB_450UK.IMG.c160a.dif C:NB_450UK.IMG

6) If bpatch tool reports that everything was made ok, you can use new (patched) version of NB_450UK.IMG file. Otherwise, read and make procedure again and report to me.
7) Read whole text file ReadMe.txt from Psion's
8) Apply installation process described in Psion ReadMe.txt, but with your new (patched) version of OS image.
9) Enjoy new version of netBook OS.

BUG REPORTS
If you have some problem with this patch file or you find some new bug, send me email or post comments at end of this article.


Poke^Patisoners
2005-10-06
Brno, Czech Republic, Europe. 