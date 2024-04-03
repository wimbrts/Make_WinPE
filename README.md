# Make_WinPE
**Make_WinPE - Make PE WIM File from x64 Windows ISO**
 
**Manual:**  for Windows 10/11 x64 OS
 
1. Download:  [Win10_2004_English_x64.iso](https://tb.rg-adguard.net/public.php) (best)     Or  [Win11_English_x64.iso](https://www.heidoc.net/joomla/technology-science/microsoft/67-microsoft-windows-and-office-iso-download-tool) (best Win11)  Or    [Win11_English_x64v1.iso](https://www.microsoft.com/en-us/software-download/windows11)
2. Double-click on Win10_2004_English_x64.iso Or  Win11_English_x64.iso to Mount as DVD Drive
3. Double-click Make_WinPE_Trusted.cmd to Launch Make_WinPE_x64.exe as Trusted Installer
4. In Make_WinPE_x64 Select DVD Drive e.g. sources folder with boot.wim and install.wim files
5. Option to make BCD EFI and Boot Manager Menu entries to Boot with the created PE_19041_US.wim  Or  PE_22000_US.wim file
    Select Boot Drive and WinPE drive e.g. the Drive where PE WIM file is Copied to WinPE Folder (Default)
6. Select Make PE button and Create in 1 minute PE WIM file in folder Build_PE
   For Boot Option PE WIM file is Copied from Build_PE to WinPE folder on WinPE Drive
7. Copy PE_Tools.zip and Drive.y to Root of any Drive e.g. USB Drive with Portable Tools
   Use 7-zip R-mouse Menu to Extract here to get PE_Tools folder with Portable PE Tools e.g. WinNTSetup and BOOTICE
8. Reboot and Select WinPE-WIM in Windows EFI or Boot Manager Menu
9. On Desktop click on Run_PE_Tools to get Menu with Portable PE Tools e.g. WinNTSetup and BOOTICE
10. On Desktop click on Run_System_Info for System_Info folder with Portable Tools and Option to Launch PStart Menu with Tools

**More Info:** [Make_WinPE - Make PE WIM File from x64 Windows ISO](http://reboot.pro/index.php?showtopic=22608)
 
- LARGE is Explorer Shell Version with support for Win 10/11 x64 - Better Shell, but larger Size 
- MEDIUM Version is Default - best performance for smaller size - 32-bits App + Microsoft Management Console (MMC) + WiFi Internet
- SMALL Version has Ultimate Size Reduction - Equal to MEDIUM Version, but missing 32-bits App support

All Versions have Picture + Sound + LAN Internet support and support Portable Apps - Run Apps via Desktop Icons or Launchbar
Add_Drivers folder - Add your Drivers folders e.g. for your WiFi Network card

Option to make Entry in Boot Manager Menu e.g.  Multi-Boot with your Internal Windows OS Or Multi-Boot USB - UEFI Secure + MBR BIOS Boot support
Select Boot Drive and WinPE Drive e.g. the Drive where WIM file is located in WinPE folder.

**Credits and Thanks to:**
 
- ChrisR - for making Win10XPE - LARGE Version corresponds quite well to 10XPE without Apps
  https://github.com/ChrisRfr/Win10XPE

- ericgl for giving Info on How to Extract files from install.wim by using wimlib-imagex
  http://reboot.pro/index.php?showtopic=21677&p=220611

- JFX for making WinNTSetup Program for Install of Windows from ISO File
  https://msfn.org/board/topic/149612-winntsetup-v534/
  
- alacran for testing and helpful support and for sharing Desktop Links and SendTo Links and Launchbar for support of Portable Apps
  http://reboot.pro/index.php?showtopic=22608&p=220827  and  http://reboot.pro/index.php?showtopic=22608&p=220862
  
- noel for his expertise and great help in adding Printer support
  http://reboot.pro/index.php?showtopic=22608&p=221255
