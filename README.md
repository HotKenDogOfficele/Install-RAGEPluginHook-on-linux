# How to install Rockstar and RAGEPluginHook on linux
```
1.1 You need to install winetrick to performe it, Use you own distro installer to install winetrick, like "sudo apt install winetrick"
For more information; https://github.com/Winetricks/winetricks?tab=readme-ov-file

2.1 next we make a wine prefix, to other to do use follow commands in the command prompt **NO SUDO**; 
2.2; **WINEPREFIX=~/Games/RockstarAndRAGEPluginHook winetricks --force -q corefonts vcrun2015 vcrun2017 vcrun2019 win10**
2.3; **WINEPREFIX=~/Games/RockstarAndRAGEPluginHook winetricks --force -q dotnet471 dotnet472 dotnet48 dotnet6 dotnet7 dotnet8 dotnet9**

3.1 To other play RAGEPluginHook you need Lutris to play.
For more information; https://lutris.net/downloads
3.2 If you opened lutris go to left sidebar, hover you mouse for wine and click on; gear
3.3 Change the Wine verion to GE-Proton (If you haved that option you can install GE-Proton with ProtonPlus App)
For more information; https://github.com/Vysp3r/ProtonPlus

4.1 In Lutris you go to top right corner where a + is.
4.2 Click on; Search the lutris website for installers
4.3 type follow; rockstar
4.4 Click on; Rockstar Games Launcher
4.5 Click what you prefered wine installion goes, recommanded is standalone.
4.6 Change the installion directory to; ~/Games/RockstarAndRAGEPluginHook (where you installed you dlls and fronts with winetricks)
4.7 Click on; install 
4.8 Follow the rockstar installer, use the default what it is. BUT uncheck; after the installer open rockstar. (Because you need to config some settings in lutris before you can use rockstar.)

5.1 You get a pop up that rockstart game Launcher succesful is installed. and click op close NOT launch
5.2 Right click on rockstar game launcher and select configure.
5.3 click on; Game options
5.4 Add in the Working directory you install place for Grant theft auto V (Keep in mind if you installed Grant theft auto V you need to add the path for installed Grant Theft Auto V) (DO NOT WORK WITH STEAM FILES, ONLY ROCKSTAR)
5.5 Click on; Save
5.6 Click on; Play

6.1 After you log-in, the system ask; Want to auto search for installed files, click; Yes
6.1B; If you have the installed Grant Theft Auto V, Rockstar see automatic the files and he update only the vcredits and directx.
6.2 If you dind't installed Grant Theft Auto V, install Grant Theft Auto V LEGANCY(NOT ENCHANTED).
6.2 Select in the installer the path what you enter in Working directory(5.3)

7.1 After you installed / updated you grant theft auto V. You need to start up first time. after you get good FPS on SINGLE PLAYER. You exit game and the rockstar launcher.
7.2 Install what you need RAGEPluginHook for. And the RAGEPluginHook it self.

8.1 Right click on Rockstar game launcher, and click on duplicate
8.2 Make follow name as recommanded; RAGEPluginHook Or RPH
8.3 Right click on game Name what you enter on 8.2. And click on configure 
8.4 Click on; Game options
8.5 Change the Executeble to the path where RAGEPluginHook.exe is.
8.6 Click on; save
8.7 Click on; Play
8.8 Follow the screen for RAGEPluginHook.
8.9 After that you need to go automatic to Grant Theft Auto V, with everyting
```
# Troubleschoot
```
(This is not real error codes)
ERROR 1; The .asi do not work.
FIX; Install OPENIV. and you need to download the ASI packet on openiv. (Later on, i make also step tot step plan for that)

ERROR 2; I get missing or corrupt .dll
FIX; Check again that you use the good winetrick (2.2 and 2.3)

ERROR 3; RAGEPluginHook says launching game, but that game is not starting up or Rockstar Game Launcher
FIX; You separate the Rockstar Game Launcher wine prefix and the RAGEPluginHook wine prefix. You need to have the same wine prefix in the; Game Options

ERROR 4; My settings do not save
FIX; Go to ~/Games/RockstarAndRAGEPluginHook/drive_c/users/(you name)/Documents/Rockstar Games/GTA V/Settings.xml and change their you settings

For other error, you make a Issue in github
```
