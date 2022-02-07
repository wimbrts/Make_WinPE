# Make_WinPE
Make_WinPE - Make PE WIM File from x64 Windows ISO

Manual for Windows 10/11 x64 OS - February 07, 2022

1. Download:  Win10_2004_English_x64.iso      Or  Win11_English_x64v1.iso
   from https://tb.rg-adguard.net/public.php  Or  https://www.microsoft.com/en-us/software-download/windows11

2. Double-click on Win10_2004_English_x64.iso Or  Win11_English_x64v1.iso to Mount as DVD Drive

3. Double-click Make_WinPE_Trusted.cmd to Launch Make_WinPE_x64.exe as Trusted Installer

4. In Make_WinPE_x64 Select DVD Drive e.g. sources folder with boot.wim and install.wim files

5. Option to make BCD EFI and Boot Manager Menu entries to Boot with the created PE_19041_US.wim  Or  PE_22000_US.wim file

   Select Boot Drive and WinPE drive e.g. the Drive where PE WIM file is Copied to WinPE Folder (Default)

6. Select Make PE button to Create PE WIM file in folder Build_PE

   For Boot Option PE WIM file is Copied from Build_PE to WinPE folder on WinPE Drive

7. Copy PE_Tools.zip to Root of any Drive e.g. USB Drive with Portable Tools

   Use 7-zip R-mouse Menu to Extract here to get PE_Tools folder with Portable PE Tools e.g. WinNTSetup and BOOTICE

8. Reboot and Select WinPE-WIM in Windows EFI or Boot Manager Menu

9. In WinPE environment click on spacebar to Launch with UI.bat and have GUI Interface with Start Menu 

10. On Desktop click on Run_PE_Tools to get Menu with Portable PE Tools

11. WindowsKey + Z gives Additional Menu to Launch the PE programs located in X:\Program Files


Credits and Thanks to:

- spectralwhite for his design and detailed build description for Making SMALL WinPE WIM file using File_List\Add_Install_Files_SMALL.txt
  http://reboot.pro/index.php?showtopic=21677&p=220146

- ericgl for giving Info on How to Extract files from install.wim by using wimlib-imagex using his File_List\Add_Install_Files_MEDIUM.txt
  http://reboot.pro/index.php?showtopic=21677&p=220611

- JFX for making WinNTSetup Program for Install of Windows from ISO File
  https://msfn.org/board/topic/149612-winntsetup-v52/
