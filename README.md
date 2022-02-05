# Ruvaak

Wabbajack Modlist Installer by Styyx

**Modlist Download: [Ruvaak.wabbajack](https://drive.google.com/u/0/uc?id=1BH7_ODiZ_Fcjqc1hT8kBmPlzsECMzG7x&export=download)**

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
      - [Downloading and Installing Ruvaak](#downloading-and-installing-ruvaak)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating Ruvaak](#updating-the-modlist)
  - [FAQ](#faq)
    - [Ultrawide Options](#ultrawide-options)
    - [Controller setup](#controller-setup)
    - [Tweaking the Game Settings](#tweaking-the-game-settings)
    - [Zoomed in Display](#zoomed-in-display)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Known Issues](#known-issues)
  - [Found a bug](#I-found-a-bug)

## Preamble

> "You are not alone. Remember this the next time you wander the harsh, frozen lands of Skyrim. Many have tried --and failed-- to discover what lurks out there, in the mists, and many will after you are gone. Tell me, do you have what it takes to survive?"

Ruvaak is a list focused on making Skyrim: Anniversary Edition (AE) into a dark fantasy roleplaying game. Many new mechanics and changes are present to offer an alternate take on the game. You can view many of these changes in the [Changes to Gameplay](https://github.com/chri3i/Ruvaak-Readme/blob/main/changes%20to%20gameplay.md) article. (not yet finished)

Mods to familiarize yourself while with the downloads are running:
- [ORDII Redux](https://www.nexusmods.com/skyrimspecialedition/mods/55200) This is the perk overhaul used in Ruvaak. It takes the excellent Ordinator and combines it with the scaling of Vokrii.
- [Character Behavior Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/40417?tab=description) Yes, underwater combat is possible and necessary to explore everything
- [Rogue Like Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/23872) This mod spawns some creepy and some pretty powerful enemies alongside --or instead of-- vanilla enemies to spice up the gameplay a bit. Don't shy away from fleeing if some enemies are a bit too much. The mod does more than just spawning enemies, as well. You'll see a few powers in your character's magic menu after starting the game. One of them is trap crafting. Explore it as you might need it later on.
- [Seamless Combat Camera](https://www.nexusmods.com/skyrimspecialedition/mods/53856) This mod is responsible for the automatic change to 3rd person whenever you draw a weapon. **Ruvaak is designed for 3rd person combat as I never play in 1st person and i didn't test anything in 1st person**. If that is off-putting to you, I need to say, sadly this list probably isn't for you. *The mod can be deactivated but note that 1st person combat is as vanilla as it gets*. To help you aiming in 3rd person there are 2 mods. [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252) for the arrow prediction and [TDM](https://www.nexusmods.com/skyrimspecialedition/mods/51614) for locking onto enemies.
- Some noteworthy mods without going into more detail [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423), [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155), [Dealing with Daedra](https://www.nexusmods.com/skyrimspecialedition/mods/40494), [The Shadow of Meresis](https://www.nexusmods.com/skyrimspecialedition/mods/38167), [Blackreack Railroad](https://www.nexusmods.com/skyrimspecialedition/mods/435) and [End Times of Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/61087)

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

Ruvaak is aimed at mid tier machines so a system like the following is advised:

### 1080p (my specs)
- CPU: AMD Ryzen 7 3700X
- RAM: 16GB DDR4
- Drive: SSD
- GPU: NVIDIA GeForce RTX 3070 8GB

It will prob run good on lower specs as well but i recommend at least 6GB VRAM (GPU)

Space required: Approx 192GB (Downloads included)

## Installation

Installing Ruvaak is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

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
5. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
6. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.
	- Google Drive links sometimes fail. Download the linked files and place it in the same place as the other downloaded files: [xLodGen Output](https://drive.google.com/u/0/uc?id=1UpnxL66aVuC6KUauAp_uaZy_iaQTK6-R&export=download), [DynDOLOD Output](https://drive.google.com/u/0/uc?id=1Pz_MmmdJRe-p8w-noDLYtbtEY2kE-k3N&export=download), [Bodyslide Output](https://drive.google.com/u/0/uc?id=1tE6fNPk4YFhGCms62xmICgQvOIwQNBNC&export=download) and [TexGen Output](https://drive.google.com/u/0/uc?id=1jSOksna-G6CXQGiHWER-bVJzAHXJmHcq&export=download)

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

Ruvaak comes already set up with [Ominous ENB](https://www.nexusmods.com/skyrimspecialedition/mods/27333) for Obsidian Weathers. In the executables drop down menu in MO2, you will find an ENB Organizer that provides you with **Four** options. Depending on your PC you might want to check them out. All of them are kind of dark, fitting for the theme i was going for. One of them is pretty niche and definitely not for everyone [A Crimson Place](https://www.nexusmods.com/skyrimspecialedition/mods/61375). If you want to install your own ENB put them into a seperate folder in Ruvaak/tools/Enb Manager/Managed ENB. You need to manually add them in the ENB Manager program afterwards. Click on Skyrim --> Go to the preset Tab --> Add preset.\
Take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Play Ruvaak` and press the run button.


### In-Game MCM options

All of the MCM options are automatically configured for you already. Wait until all notifications on the top left are gone before opening the MCM. **Failing to do so will cause quite a few issues later on and will require you to start a new save.** You can tweak the MCMs to your liking:

- CGO (Leaning and Camera noise can be adjusted. I set them to 0.25)
- Combat Difficulty Customizer (again, default profile is loaded but if the game is too hard/easy you can tweak stuff there)
- Draw 2 (Goes hand in hand with the equipment styles you can set up in XPMSE MCM)
- Legacy (Race mod which lets you choose which racial power you want to use)
- Lucien (If you set a supported nickname, he will call you by that)
- NASC (Normal Attacks Stamina Consumtion, pretty straight forward. Adjust how much stamina your weapons should use)
- SkyUI
- Smart Harvest (choose whatever you want there or pause it by pressing 'O (the letter)' outside of menus)
- The Ultimate Dodge Mod (A config will get loaded upon start. You don't have to change anything there really)
- XPMSE (Adjust the equip styles for your character)
- I recommend to look at 'Breakable Equipment' to flag any lantern (one is found in the starting room) as unbreakable


### Starting the Game

After the MCM is done you'll notice that you're in a room with a weird small dragon and a few objects to loot. Take whatever you want from inside the room to gear up for an adventure. I highly suggest taking the 'stakes' with you and always keep some in your inventory as it might be the only way to reliably kill vampires. Afterwards talk to the dragon and choose your beginning. There are tons of options, so just pick what sounds best to you. Open the door once you've picked the beginning and go through it. **Please do not try to sprint and jump throught it like you're at the olympic games. All you can get out of that is possibly some weird bugs.**
**Note that Ruvaak has some very strong spawns in the wild. Choosing a start that puts you into the wilderness can result in immediate combat/death**


## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ

### BA Alchemist Arsenal

You need to be level 5 and open the crafting kit to use this. (more info once I'm done)

### Controller Setup

Controller compatibility is turned on by default as Ruvaak uses a neat SKSE plugin called [Auto Input Switch](https://www.nexusmods.com/skyrimspecialedition/mods/54309) and therefor it won't interfere for anyone using keyboard and mouse for controls.
If you use a gamepad, however, you should make yourself familiar with the changed controls. Ruvaak uses [TUCS](https://www.nexusmods.com/skyrimspecialedition/mods/29381). If you don't like the control layout you can disable the mods under *Gamepad support* at any time/
Also if you use a gamepad, activate the mod 'Gamepad MCM' in the 'Gamepad' section in MO2. This ensures to load a profile for TUDM for controller compatibility.

### Ultrawide Options

I personally do not own an Ultrawide, so I cannot offer support. And quite frankly I do not know if widescreen even works on AE yet


### Overpowered Enemies

Enemies are spawned from leveled lists which are semi-random. Ruvaak is not de-leveled but there are occasionally high level enemies in lower level areas. You can't defeat them at low levels. Try your luck later or use some strategies to overcome these hurdles. There are also some extremly powerful bosses scattered around the world. Those are meant for mid to high level characters. Avoid them as a low level character.


### OP Loot

There are some extremely powerful items in most of the dungeon boss chests. While I might make some adjustments, you can assume it's intentional. I want loot to feel rewarding. After all, there's a chance that you had some tough battles before getting to the chest.

### Survival Mode

While the list is made with Survival mode in mind, you will probably sometimes need to disable it to fully utilize the mods in the list (Underwater combat for example as most of the new underwater creatures are in the north and you'll freeze to death there when you swim)
It can be freely enabled and disabled in the settings menu whenever you want (just give it a few seconds to take effect) and don't rapid fire switch between Survival and non-Survival.

### Equipment is too weak

Make sure you meet the requirements for the equipment you want to use. By default Ruvaak restricts certain equipments to specific skill levels.

### Help, my gear broke

If your equipment got damaged or destroyed, visit a blacksmith to temper it, or temper it yourself at the right crafting station for your equipment type.

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

## Known Issues
- Before reporting any issues please refer to [Known Issues](https://github.com/chri3i/Ruvaak-Readme/blob/main/Known%20Issues.md) to see if your issue is mentioned there already. While i try to fix any issues that come up, I can't fix everything, please be patient.

## I found a bug

Go to the GitHub [Issues](https://github.com/chri3i/Ruvaak-Readme/issues) page and check if your issue was already reported. If you found no similar posts, create a new issue by clicking the green `New issues` button in the top right corner. Select `Bug report` and fill out the document.


## Credits and Thanks

- _YOU_ for reading this.
- Althro for assisting with so many things. And allowing me to fork the readme. You’re awesome.
- Chef for the help with the armors
- Spaniard for being an invaluable source of knowledge and helping me a lot with the mod choices.
- Destiny for proofreading the readme and pointing out many errors. Also for testing the list and giving helpful suggestion to improve it
- Astro for testing and giving reports, more detailed than I ever expected. Seriously, thanks a lot
- The Animonculory Dev Team.
- Noggog for Mutagen.
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
