# How to install Rockstar and RAGEPluginHook on linux
## Pre requested

1. Lutris | For more information; https://lutris.net/downloads
2. Winetrick | For more information; https://github.com/Winetricks/winetricks?tab=readme-ov-file
3. Lutris GE-Proton | For more information; https://github.com/Vysp3r/ProtonPlus

## Step tot step guide

First we make a wine prefix, use follow commands in the command prompt **NO SUDO**;
```
WINEPREFIX=~/Games/RockstarAndRAGEPluginHook winetricks --force -q dotnet48 dotnet6 dotnet7 dotnet8 dotnet9 
```
(This process take a 10-15 mins)

## Change to GE-Proton
Open lutris go to left sidebar, hover you mouse for wine and click on gear

Change the Wine verion to GE-Proton.
And save it.

## Install Rockstar games
After the wintrick is completed than you go futher.

Then you go to top right corner where a + is.

Click on, Search the lutris website for installers

type: rockstar

Click on, Rockstar Games Launcher

Click what you prefered wine installion goes, recommanded is Standalone-1.0.36.344.

Change the installion directory to; ~/Games/RockstarAndRAGEPluginHook (where you installed you dlls with winetricks)

Click on, install 

Follow the rockstar installer, use the default what it is. BUT uncheck after the installation ```Run Rockstart Games Launcher``` Because you need to config some settings in lutris before you can use rockstar.

You get a pop up that rockstart game Launcher succesful is installed. and click op close **NOT** launch

## Configure rockstar
Right click on rockstar game launcher and select configure.

click on; Game options

Add in the Working directory you install place for Grant theft auto V, keep this things in mind;
  1. If you installed Grant theft auto V you need to add the path for installed Grant Theft Auto V
  2. If you installed GTAV selected the parent folder not GTAV folder it self. Like; ```/var/mnt/Rockstar/``` **NOT** ``` /var/mnt/Rockstar/Grand Theft Auto V Legacy/```
  3. ATM, Do not work with steam GTAV files, please use the Rockstar Games Launcher to install GTAV

Click on; Save

Go back to command promt and run this cmd:
```
WINEPREFIX=~/Games/RockstarAndRAGEPluginHook winetricks --force -q d3dcompiler_47 d3dx9 d3dx10 d3dx11_43 winhttp wininet xact corefonts
```
(This process take a x mins)

After is done, proceed futher.

Go to Wine configuration 

(That is right side of play button)

Change the Windows version to Windows 10, **NOT other version**

Click on; Play
## Cofigure Rockstar launcher 

After you log-in, the system ask; Want to auto search for installed files, click; Yes
### installed GTA V
1. If you have the installed Grant Theft Auto V, Rockstar see automatic the files and he update only the vcredits and directx.

### Did not installed GTA V
1. If you dind't installed Grant Theft Auto V, install Grant Theft Auto V LEGANCY(NOT ENCHANTED).
2. Select in the installer the path what you enter in Working directory (What you did in Confiure rockstar)

After you installed OR updated you grant theft auto V. You need to start up first time. after you have good FPS on SINGLE PLAYER. You exit game and the rockstar launcher.

## Install RPH and LSPDFR
Download next things on internet in this order and put in the main folder of GTAV:
  1. ScripthookV + (Native trainer)
  2. RAGEPluginHook
  3. LSPDFR
  (4. RAGEPluginHook persuit fix)

Right click on Rockstar game launcher, and click on duplicate

Make follow name as recommanded; RAGEPluginHook Or RPH

Right click on dublicated game, And click on configure 

Click on, Game options

Change the Executeble to the path where RAGEPluginHook.exe is.

Click on, save

Click on, Play

Follow the screen for RAGEPluginHook.

TIP: Do not load the LSPDFR plugin in first time, most of the time the game freeze. After you do you LSPDFR sync && create a character, you can turn the Plugin on.

# Troubleschoot

**(This is not real error codes)**

ERROR 1; The .asi do not work.

FIX: Install OPENIV. after that you need to download the ASI packet on openiv. (Comming soon how install OpenIV)

ERROR 2; I get missing or corrupt .dll

FIX; Check again that you paste full command from winetrick 

ERROR 3; RAGEPluginHook says launching game, but that game is not starting up or Rockstar Game Launcher

FIX; Most likely you separate the Rockstar Game Launcher wine prefix and the RAGEPluginHook wine prefix. You need to have the same wine prefix in the; Game Options

ERROR 4; My settings do not save

FIX; Go to ~/Games/RockstarAndRAGEPluginHook/drive_c/users/(you name)/Documents/Rockstar Games/GTA V/Settings.xml and change their you settings OR You have enabled auto settings in RAGEPluginHook

ERROR 5; I get in the installer follow error; winetricks verb 'arial' is already installed in '~/Games/RockstarAndRAGEPluginHook' 

FIX; You installed arial or corefront in the first winetrick command, That is not recommended. 

For other error, you make a Issue in github

And use your mind and skills. But do not repost it. I have many hours in this project, i don't wanna waste it.
```
