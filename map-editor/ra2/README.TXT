Command & Conquer - Red Alert 2 (c): FinalAlert 2 Editor
------------------------------------------------------------
 Copyright 2001 Electronic Arts Inc. All rights reserved.
 Westwood Studios [TM] is an Electronic Arts [TM] brand.

 Microsoft, DirectX, and DirectDraw are registered trademarks or trademarks of Microsoft
 Corporation in the USA and/or other countries.

------------------------------------------------------------
Welcome Commander,

Thanks for reviewing our new & improved C&C: Red Alert 2 mission editor.  Here at Westwood 
we've been working hard with the original FinalAlert developer for a few months now. By 
teaming up with Mr. Wagner, we've been able to add many more items into FinalAlert
that should make it more user friendly and powerful.


Regards,

President M. Dugan



TECH SUPPORT DISCLAIMER
----------
In order to ask questions about FinalAlert 2, please visit www.westwood.com. 
We will review the message board and reply to questions as often as we can. Tech support 
is limited.  FinalAlert 2 is distributed free of charge for the benefit of Red Alert 2 
fans. 


MINIMUM SPECS
----------
FinalAlert 2:
- Win9x or Win2k
- DirectX 6
- 64 MB physical, 150 MB free space on your page file harddisk
- Red Alert 2 installed
- Direct X 8.0 recomendend

Command & Conquer: Red Alert 2
- see system requirements on box



KNOWN ISSUES/BUGS
----------
- If FinalAlert 2 crashes while loading pictures, switch into another color mode 
  by right clicking on your desktop and selecting properties. Select the correct 
  tab and switch to another color mode. Then try again. If it doesn´t work, try a 
  lower resolution. And if even this doesn´t help, check the end of this file that 
  has additional notes
  Work Around:  First you should try switching to 16 bit color depth and probably a 
  lower resolution. If this doesn´t work, you should make sure that c:\ (or where you 
  have your swap file) has enough free space (300-400 MB are perfect). If this also 
  doesn´t help, you can try to increase your swap file size manually (but please only do 
  this if you are experienced!)

- In Windows true color 32 bit when the user right clicks Iso View it may be corrupted.
  Try different color settings in Windows if any unexpected video behavior is occurring.

- Problems may occur if you have one or more mods installed. If you experience problems,
  please try first to remove these mods.
  



HOW TO START
----------
After FinalAlert 2 has finished loading, press F1 to show the manual and
some tutorials.



PLEASE!!! Read the manual by pressing F1 in FinalAlert 2.  You should also begin with
the tutorials included.



FAQ
----------
Q: How can I create a zoom trigger?
A: If you want to zoom on a particular place, you must first use the 'move camera 
   and scroll to waypoint' action (#48) and then zoom in.  The zoom rate is controlled 
   by an undocumented keyword which must be placed in the [General] section of RULES.INI 
   or your map file: ZoomInFactor=N    } It works to use Edit->Ini to create a [General] 
   section inside the map file and insert the key.

Q: Can I play the maps online? And use the new unit types online?
A: Yes, Patch 1.005 will increase the synchronization limit to 3 minutes (180 seconds).
   40 seconds is enough for about a 500-550kb transfer (so 130-150 kb for a map for 4 
   players online). You can use the unit types online.

Q: How can I keep the map file small so that I´m able to play with 4 players online?
A: One possibility is to "hide" the preview. Just select the appropiate options when you 
   save the map. Since Patch 1.005 will allow longer synch times, this problem should be
   less of an issue..

Q: Ok I´ve made a multiplayer map. How can I play it?
A: In the Red Alert 2 map settings dialog, choose "multiplayer maps" and click on 
   your's (usually near the bottom). Note that you cannot load the map in the random 
   map editor.

Q: What is that drag & drop feature? How can I copy units/buildings or move them?
A: Instead of deleting a building and placing it somewhere else, you can simply click 
   with the left mouse button on the building and move your mouse while holding down the
   mouse button. You can now see a line that shows where the building/unit will be placed. 
   If you stop holding down the button, the unit/building will be moved there. If you hold 
   down the shift key also, it will be "copied" there. That means you can  create a big 
   army without having to create every unit yourself. Note: if you move/copy a building 
   and it is to big to be placed at the new position, no warning appears! That means you 
   will probably have problems if you don´t make sure that there is enough space!


FEATURE					BUILT-IN
Basic					Yes
Special Flags				Yes
Lighting				Yes
General editor for sections		Yes
Inserting of other INI files		Yes
Version of rules.ini included in EXE	Not anymore included. Uses directly Red Alert 2´s 
					rules.ini 
Graphical editor			Iso-view included (terrain is shown and EDITABLE!)
Inserting Trees				Yes
Inserting Units				Yes
Inserting Buildings			Yes
Inserting Infantry			Yes
Inserting Aircraft			Yes
Inserting waypoints			Yes
Inserting base nodes			Yes
Object settings				Yes
General map settings			Yes
Triggers etc				Yes
Scripts					Yes
AITriggerTypes etc			Yes
Minimap					Yes
Placing cliffs, water, roads, etc.	Yes


Note: We have not listed every feature missing/built in.


***********
DLLS NEEDED
***********

ADVAPI32.DLL
COMCTL32.DLL 
DDRAW.DLL 
GDI32.DLL 
KERNEL32.DLL
MFC42.DLL   
MSVCP60.DLL 
MSVCRT.DLL  
NTDLL.DLL   
SHELL32.DLL  
SHLWAPI.DLL  
USER32.DLL  
VERSION.DLL

Now DLLs, that are loaded delayed:
COMDLG32.DLL
CRYPT32.DLL 
MPR.DLL    
MSOSS.DLL  
MSVCRT20.DLL 
ODBC32.DLL  
OLE32.DLL  
OLEAUT32.DLL 
OLEDLG.DLL  
OLEPRO32.DLL
RPCRT4.DLL
URLMON.DLL  
WININET.DLL  
WINSPOOL.DRV 
WSOCK32.DLL  








