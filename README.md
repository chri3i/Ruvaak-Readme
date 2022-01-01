# Ruvaak very much WIP

Wabbajack Modlist Installer by Styyx

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Contents
  - [Preamble](#preamble)
  - [System Requirements](#system-requirements)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing Ruvaak](#Downloading-and-Installing-Ruvaak)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Creating your Character](#creating-your-character)
  - [Updating Ruvaak](#updating-the-modlist)
  - [FAQ](#faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Controller setup](#controller-setup)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)

## Preamble

> "You are not alone, Remember this the next time you wander the harsh, frozen lands of Skyrim. Many have tried --and failed-- to discover what lurks out there, in the mists, and many will after you are gone. Tell me, do you have what it takes to survive?"

Ruvaak is a list focused on making Skyrim: Anniversary Edition (AE) into a dark fantasy roleplaying game. Many new mechanics and changes are present to offer an alternate take on the game. You can view many of these changes in the [Changes to Gameplay](https://github.com/Althro/Tinvaak2/blob/main/Changes%20to%20Gameplay.md) article. (tbc, document not started yet)

Mods to familiarize yourself while the downloads are running:
- [Vulture Dynamic Realism 2](https://www.nexusmods.com/skyrimspecialedition/mods/56819) This mod is responsible for stamina drain in and out of combat, highly customizable.
- [Character Behavior Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/40417?tab=description) Yes, underwater combat is possible and necessary to explore everything
- [Rogue Like Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/23872) This mod spawns some creepy and some pretty powerful enemies alongside --or instead of-- vanilla enemies to spice up the gameplay a bit. Don't shy away from fleeing if some enemies are a bit too much. The mod does more than just spawning enemies, as well. You'll see a few powers in your character's magic menu after starting the game. One of them is trap crafting. Explore it as you might need it later on.

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Ruvaak is aimed at mid tier machines so a system like the following is advised: tbc

### 1080p
- 2nd Gen Ryzen (2800x)/6th Gen Intel i5 CPU 
- 16GB DDR4 Ram
- SSD
- 6GB GPU (1660 super/5600XT); 8GB GPU (1070/5700XT) recommended

Space required: Approx 146GB (Downloads included)

## Installation

Installing Ruvaak is relatively easy and, if you have nexus premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Ruvaak, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside /Documents/My Games/.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like C:\Games is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations


### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Ruvaak

Downloading and installing Ruvaak can take a while depending on your internet connection and computer. To install Ruvaak, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on Ruvaak and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Ruvaak.
4. Press the play button to begin.
5. Go and pet your nearest fluffy animal whilst Wabbajack does its thing alternatively read through this readme again.
6. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder

Ruvaak uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”. You don’t need to copy anything at all.


### ENB

Ruvaak comes already set up with Ominous ENB for Obsidian Weathers. In the executables drop down menu in MO2, you will find an ENB Manager that provides you with three  options . By default, Ruvaak uses the Full version.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Play Ruvaak` and press the run button.

### In-Game MCM options

Most of the important MCM options are automatically configured for you already. Wait until all notifications on the top left are gone before opening the MCM. **Failing to do so will cause quite a few issues later on and will require you to start a new safe.** You can tweak the following MCMs to your liking:

- Lucien (If you set a supported nickname, he will call you by that)
- SkyUI
- The Ultimate Dodge Mod (there is a profile loaded for gamepad users as I play with a gamepad myself)
- V.Dynamic Realism (there is a profile to load with my pick but you can change stuff however you like there)
- Combat Difficulty Customizer (again, default profile is loaded but if the game is too hard/easy you can tweak stuff there)


### Creating your Character

The last MCM to tweak is 'Skyrim Unbound'. You can decide yourself whether you want to play as a Dragonborn or not (some follower will refer to you as the Dragonborn no matter what you pick in Skyrim Unbound) but if you do decide against being a Dragonborn you need to know that the **main quest is NOT an option**. After you have chosen your starting gear and setup you can click on "Let's Go" or close the menu and hit 'Backspace'. Proceed with customizing your character however you want or alternatively load one of the presets provided by Shuckleberry. After that hit continue to start the game.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### BA Alchemist Arsenal

You need to be level 5 and open the crafting kit to use this.

### Controller Setup

Controller compatibility is turned on by default as Ruvaak uses a neat SKSE plugin called [Auto Input Switch](https://www.nexusmods.com/skyrimspecialedition/mods/54309) and therefor it won't interfere for anyone using keyboard and mouse for controls.
If you use a gamepad, however, you should make yourself familiar with the changed controls. Ruvaak uses [TUCS](https://www.nexusmods.com/skyrimspecialedition/mods/29381). If you don't like the control layout you can disable the mods under *Gamepad support* at any time

### Ultrawide Options

I personally do not own an Ultrawide, so I cannot offer support. And quite frankly I do not know if widescreen even works on AE yet

### Survival Mode

While the list is made with Survival mode in mind, you will probably sometimes need to disable it to fully utilize the mods in the list (Underwater combat for example as most of the new underwater creatures are in the north and you'll freeze to death there when you swim)
It can be freely enabled and disabled in the settings menu whenever you want (just give it a few seconds to take effect) and don't rapid fire switch between Survival and non-Survival

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must then you can.

#### ENB

Ruvaak ships with an ENB setup that is configured to match the look of the list. If you wish to make some changes though, here are a few common tweaks. I recommend opening the console before doing edits.

##### Removing the letterbox

1. Press [Shift+Enter] to open the ENB menu.
2. In the tab called Shader Parameters, select the `ENBPOSTPASS.FX` section. It will open once you click on it.
3. Scroll down until you see letterbox and untick it.
4. Press the save configuration button.
5. Press [Shift+Enter] to return to the game.

##### Turning off settings for FPS

If you are struggling for frames but want the colour correction and realism, turn off the following items.

- DetailedShadows
- ComplexFireLights
- ComplexParticleLights – Disable Big Range
- Reflection

If you really cannot handle the ENB, uncheck `useEffect`.

### Zoomed in Display

This is caused by Windows display scaling feature. To fix this you can do either of the following.
- Set display scaling back to 100% in Windows screen resolution settings
- Edit SSE Display Tweaks ini file under Render
	- Fullscreen: `True`
	- Borderless: `False`
    
## Removing the Modlist
Simply delete the folder and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Althro for assisting with so many things. And allowing me to fork the readme. You’re awesome.
- Mint for many edits to the readme I'm forking.
- Spaniard for being an invaluable source of knowledge and helping me a lot with the mod choices.
- Destiny for proofreading the readme and pointing out many errors
- The Animonculory Dev Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.