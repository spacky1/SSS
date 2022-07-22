# SSS
A Skyrim Together Wabbajack Modlist

## Contents
  - [Preamble](#preamble)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing SSS](#downloading-and-installing-SSS)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [Starting the Game](#starting-the-game)
    - [Important Controls](#important-controls)
  - [Updating SSS](#updating-the-modlist)
  - [FAQ](#faq)
  - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)

## Preamble
Read this.

## Installation
If you are updating the modlist, skip to the [updating section](#updating).

### Pre-Installation
Prior to installing, complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/download/dotnet/6.0/runtime).
2. Fully uninstall Skyrim by deleting the Skyrim Special Edition folder in Steam and the Skyrim Special Edition folder inside `Documents\My Games`.
3. Reinstall Skyrim.
4. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
5. Start the game once and let it do the graphics check. Do not worry about the settings as they will be replaced during installation.
6. Start the game and exit once you've reached the main menu.

### Wabbajack Installation

#### Installing Wabbajack
Download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and place it in a folder such as `C:\Wabbajack`. **Do not install it into a Windows system-managed folder. (e.g. Desktop, Downloads, etc.)** I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing SSS
Downloading and installing the modlist can take a while depending on your internet connection and specs. To install SSS, complete the following steps.

1. Grab the latest version of the modlist from [here.](https://github.com/spacky1/SSS/releases) You only need to download the .wabbajack file. 
2. Locate and open the .wabbajack file. Wabbajack should open.
3. Set the Installation Location to be somewhere like `C:\SSS`. **Do not install it into a Windows system-managed folder. (e.g. Desktop, Downloads, etc.) This may or may not break the fuck out of the list.**
4. Press the button to begin the install. Feel free to go do something else while WJ does its thing.
5. If the installation is successful, move on to [Post-Installation](#post-installation). If not, let me know.

##### Problems with Installation
It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download **x**:
	- Big files can fail to download due to connection issues. You can either run wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- Wabbajack could not find my game folder:
	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Game Folder
SSS uses a Wabbajack feature called Stock Game to keep your original Skyrim installation clean. All the files that you need to run the list are in a folder called “Game Root”.

### Installing the ENB
SSS is designed for use with Cabbage ENB. However, the author has not allowed the file to be whitelisted for Wabbajack, so it has to be downloaded and installed manually, which is simple enough.

1. Download the preset from [here](https://drive.google.com/uc?export=download&id=1Df8QfYbIhiDj6k3dLwW5yEDgEva75T4y).
2. Open the archive and copy **ONLY** the `enbseries` folder.
3. Paste this folder into `SSS\Game Root`. Windows should ask you whether you want to replace or skip the file. **Press skip–do not overwrite!**

If you wish to install your own ENB, I assume you know how to do that. The list uses [NAT.ENB's weather plugin](https://www.nexusmods.com/skyrimspecialedition/mods/27141), so choose an ENB preset that is made for its weathers, such as... NAT.ENB. Another recommendation is [Berserkyr](https://www.nexusmods.com/skyrimspecialedition/mods/62381).

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Skyrim Together Reborn` and press the `Run` button. When prompted, select `SkyrimSE.exe` **from the modlist's "Game Root" folder – NOT Steam's Skyrim Special Edition folder!**

### Starting the Game
- By default, SSS uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953). You are free to either play through the introduction or skip it.

### Important Mod Controls
- Skyrim Together GUI: Right Control
- Emotes: Right Alt
- Lock-On: Middle Mouse Button
- Toggle UI: X
- Screenshot: F1 (screenshots are saved to the Game Root folder)
- ENB Menu: F11
- Toggle DOF: F10

## Updating the modlist
Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply download the new .wabbajack file and open it. Make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## FAQ
#### I installed the ENB incorrectly, or I want better performance
- The tweaks I've made to Cabbage are contained within the `SSS\Spack's Cabbage Tweaks` folder. Simply choose either the Default or Performance files, then copy the files within that folder to the Game Root folder, overwriting when prompted.

#### Should I choose the default ENB preset or the performance ENB preset?
- Try default first. If you get frequent dips below 30fps, I would switch to the performance preset.

#### When launching Skyrim Together, I get an error about "Address Library"
- You didn't select the correct SkyrimSE executable. When launching Skyrim Together through MO2, hold down Space and select the correct .exe from `SSS\Game Root`.

#### Various character overlays (e.g. bodypaints) do not sync
- As far as I know, this is currently an issue with Skyrim Together. Idk.

#### The game crashes on startup!
- Don't tab out once the game window opens.

#### My character's hair/warpaint/skin/etc disappeared
- Open the console with tilde (\`\) type `showracemenu`, and resave your character

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
