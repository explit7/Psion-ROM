Project: Psion netBook
Component: Operating System (OS) Image
Version: 1.05 (450) – English (UK) – ASCII (Release 158)

Release Information
Date: 20 August 2002

In these notes:
1.	Introduction
2.	Installation
3.	Installation of Optional Components
4.	Restoration from Backup (Note: this is important)
5.	New Features
6.	Improvements from Previous Releases
7.	Known Issues

1. Introduction

	This is an OS image for the Psion netBook.  These notes cover download
	and installation as well as improvements and new features.

2. Installation

*	Prior to installation, you should back up all data from your netBook.
	(This installation procedure will erase all data that is not
	on CompactFlash)

*	It will not be possible to restore your internet and modem connection
	details.  Make a note of these.

*	You will need a CompactFlash card with sufficent (approx 14MB) free
	space, and with no OS.IMG file in the default folder.

*	It is recommended to install the OS with a fully charged
	main battery.

*	Download the zipped OS from Teklogix website (you may have already done this.)

*	Save the file to your local hard drive.  (Psion recommends the
	My Documents folder)

*	Open the zip file (your browser may provide this option, otherwise open
	directly from your My Documents folder.)
 	If this does not work, you may not have a zip application installed.
	WinZip (a shareware program not affiliated with or endorsed by Psion)
	is available for the PC from www.winzip.com

*	Extract the OS Image file to the CompactFlash card.  This may be
	performed with PsiWin and a Psion netBook or with a separate
	CompactFlash cardreader.

*	Rename the OS Image on the CompactFlash card to OS.IMG   (The file as
	supplied is named according to language and version number.)  This must
	be performed using directly on the netBook.  (Click the Epoc logo to bring
	up the system application, click bottom left on the screen to select the
	D drive [it will probably say C initially], then select the image file
	and choose menu, file, rename...  Type OS.IMG as the new filename, and
	press return)

*	The next stages will remove all saved and unsaved data from your
	netBook.  It is essential to back up any data that you wish to preserve.
	(Note: data on CompactFlash cards is not affected.)

*	Switch off the netBook.

*	Remove the backup battery, then the main battery, and then the power supply
	from the netBook. (Note: this should be performed in the order suggested
	to reduce drain on the backup battery).

*	After waiting 15 seconds, replace the main battery and then the
	backup battery (and optionally the power supply.)
	(Note: this should be performed in the order suggested to reduce drain
	on the backup battery).

*	Switch on the netBook, and when prompted insert the CompactFlash card
	with the new OS image.  The netBook will copy the image into
	internal memory, and when this is complete the new OS is
	installed and the CompactFlash card may be removed.

*	See Restoration from Backup, below

3. Installation of Optional Components
	In some versions certain components are included separately to the OS.
	To install these optional components, connect the netBook to your PC in
	the usual manner, extract each SIS file from the zip file (for the exact
	procedure please see the instructions with your zip application).
	Open the SIS file to automatically load the application onto the netBook.
	Should you have problems with the above, verify the following:
		The netBook is turned on.
		PsiWin is installed correctly.
		The netBook is correctly connected to the PC.
	Alternatively, the SIS files may be copied directly to the netBook
	(using PsiWin) and opened from there.

4. Restoration from Backup
	This details the procedure for restoring from a backup previously made
	with PsiWin.
	This procedure may be skipped (and backup restored in the usual way)
	only if you are certain that the previous OS already had Ethernet support.
	If in doubt, please follow these instructions.
		Follow the Installation instructions above
		 (you may already have done this)
		Go to System (press the lower left icon on your netBook screen,
		 with the Epoc logo)
		Press Menu, select "Tools", then "Preferences..."
		Ensure that "Show System Folder" is ticked.
		Press Return
		Browse to System\Data:
			If C is not showing in the bottom left of the screen,
			 click there and select the C Drive.
			Double click "Close" (top left folder) as many times as
			 necessary, until Documents and System folders are showing.
			Double click "System"
			Double click "Data"
		Select commsdb.dat
		Press Menu, File, Rename...
		Type in commsdb.tmp and then press Return.
		Restore your backed up files using PsiWin in the usual way.
		Browse to System\Data (as above)
		Select commsdb.dat
		Press Delete and select "Yes".
		 (This will delete the out of date commsdb.dat from your backup)
		Select commsdb.tmp
		Press Menu, File, Rename...
		Type in commsdb.dat and then press Return.
	This stage is necessary to remove your out of date commsdb.dat settings.
	You can now restore your internet and ethernet settings from your notes,
	 using the Control Panel.


	Note: If you inadvertently failed to follow these instructions during
	 initial installation, certain internet and ethernet applications may
	 be unstable.  Should this be the case, please follow these
	 recovery instructions:
		Make a note of your internet, modem, and ethernet settings.
		Go to System (press the lower left icon on your netBook screen,
		 with the Epoc logo)
		Press Menu, select "Tools", then "Preferences"
		Ensure that "Show System Folder" is ticked.
		Press Return
		Browse to System\Data:
			If C is not showing in the bottom left of the screen,
			 click there and select the C Drive.
			Double click "Close" (top left folder) as many times as
			 necessary, until Documents and System folders are showing.
			Double click "System"
			Double click "Data"
		Select commsdb.dat, and press Delete, then "Yes".
	This will remove the incorrect settings, and you can now restore your
	 internet and ethernet settings from your notes (using Control Panel.)
	Alternatively, fully reinstall the OS as detailed above.

5. New Features

	Ethernet.
		Support is now included for LAN, rLAN, IrLan and 802.11
		 (Lucent and Cisco) PC cards.
		Ethernet settings are available in the System Control Panel.
		Enabled Ethernet settings can be used to access the internet
		 in a similar manner to other internet connections.
 
	Opera Version 5.
		Opera (www.opera.com) replaces the previous Symbian web
		 browsing application and Opera 3.16.

	nFTP
		(Either supplied with the OS or as a separate SIS file.
		 See Installation of Optional Components above.)
		nFTP (www.neuon.com) is a fully featured FTP client.

	NetStatRF
		(Either supplied with the OS or as a separate SIS file.
		 See Installation of Optional Components above.)
		NetStatRF is used to measure the signal strength of a wireless
		 LAN card.

6. Improvements from Previous Releases

*	InfraRed sending of contacts is now fully supported.
*	File copying issues are now resolved.
*	Agenda Preferences issues are now resolved.
*	Contacts labels issues are now resolved.

7. Known Issues
	If you have problems using Ethernet or any internet application, and
	 you have restored a previous backup since updating the OS, please check
	 the procedure under "Restoration from Backup" above.

	It is possible that your netBook may occasionally appear to be unresponsive
	 when using certain Modem PC Cards.  Should this happen please eject
	 and replace your Modem PC Card, and repeat the connection process.

	nFTP may very occasionally abort (with an eSock error) while initially
	 connecting to an FTP server.  This will not lose any data in the NetBook,
	 and nFTP may be safely restarted.


