# Ascensio



<table stlyle="border: none;">
<tr>
<td><img src="https://raw.githubusercontent.com/The-Animonculory/Animonculory-Visual-Overhaul/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	

</tr>
</table>

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
      - [Downloading and Installing Ascensio](#downloading-and-installing-ascensio)
      - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [Documentation](#documentation)
    - [BethINI](#bethini)
    - [ENB](#enb)
  - [Playing the List](#playing-the-list)
    - [Starting up the list](#starting-up-the-list)
    - [In Game MCM Options](#in-game-mcm-options)
    - [Starting the Game](#starting-the-game)
  - [Updating Ascensio](#updating-the-modlist)
  - [FAQ](#faq)
   - [Removing the modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)

# <ins>**Ascensio requires the *full* AE upgrade, which means you must *purchase* the AE edition of the game for the list to function.**<ins>

## Preamble


The full modlist can be viewed [here](https://loadorderlibrary.com/lists/project-unknown), a selection of screenshots can be viewed [here](https://imgur.com/gallery/5hQSniK).

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## System Requirements

### Minimum Specifications for ~60 fps gameplay at 1920x1080

| Spec Category | Performance Profile  | Default Profile |
|     :---:    |     :---:      |     :---:     |
| **CPU**   | i3 10100f /  i5 9600k / R5 2600 |  R7 3700x / i5 10600k |  
| **Video Card**    | GTX 1080 / RTX 2060 / RX 5600 XT | RTX 3060 Ti / RTX 2080 / RX 6700 XT       |
| **Ram**    | 16gb (2x8) DDR4 2666mhz RAM      | 32gb (2x16) DDR4 3200mhz RAM     |
| **Storage**    | SATA SSD      | M.2 SSD     |

>  I will **not** be supporting any AMD GPUs from before or from the Polaris Series (RX 500) and any NVIDIA GPUs from before or from the Maxwell Series (GTX 700/900), the only exception for this is the GTX 980 Ti, which is relateively equivelent to a 1660 Ti. These GPUs are simply not powerful enough to handle modded skyrim with an ENB on at 60 frames.

Space required: 
- Approx 210GB (Downloads included)

Size without downloads: 
- Approx 120GB

## Installation

Installing Ascensio is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating).

### Pre-Installation

Prior to installing Ascensio, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. You also need to start the games to the main menu in order to download all the creations. **DO NOT SKIP THIS STEP, IF YOU DO SO WABBAJACK WILL FAIL**
 #### __Step 3 and 4 are only necessary if you modded the game without a 'stock game' and cleaned the master files.__

 Additionally, if you have an NVIDIA GeForce Graphics Card, please do the following. 

 1. Right click on your desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings until you see **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. You may exit out of the application.

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) on this github and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing Ascensio

Downloading and installing Ascensio can take a while depending on your internet connection and computer. To install Ascensio, complete the following steps.

1. Download the Wabbajack Installer on this github,.
2. Press the download button on Ascensio and wait for it to download.
3. Set the installation folder to be somewhere like C:\Games\Ascensio. **Do not install it to your desktop, downloads folder, or Skyrim's Steam Folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

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

Ascensio uses a Wabbajack feature called Stock Game to keep your Skyrim installation clean. All the files that you need to run the list are in a folder called “Stock Game”. You don’t need to copy anything at all.

### Documentation

 - ### [Graphical Changes & Notes](https://github.com/Curly0208/Ascensio/blob/main/Graphical%20Documention.md)
 - ### [Adding Mods to Ascensio](https://github.com/Curly0208/Ascensio/blob/main/Adding%20Mods%20to%20Ascensio.md)

### ENB
Ascensio is designed for use with an ENB and comes with [Cathedral Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/24791), already activated and ready for use. The ENB has been custom tweaked for the list to match the intended look, feel and performance of the list.

If you wish to install your own ENB, however, an ENB manager is included. Simply put your new ENB into a seperate folder in `Ascensio\tools\Enb Organizer\Games\Ascensio\Preset`.

#### Using ENB Organizer

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big `Run` button next to it. Run the program named `Pick Your ENB` from Mod Organizer 2.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%201.png?raw=true)

If the image below comes up, simply press OK. It is nothing to be concerned about.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/Ignore%20Warning.png?raw=true)

Navigate to the Presets menu by pressing the symbol in the top left (the three lines). The menu should look like this:

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%203.png?raw=true)

Activate the ENB you wish to use by pressing the slider. To deactivate it, simply press the slider.

![image](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/.github/ENB%205.png)

For adding your own presets and more details, take a look at [ENB Organizer](https://www.nexusmods.com/skyrim/mods/67077) for more information or take a look at a [Video](https://www.youtube.com/watch?v=4MA5ZLcRYds&t=34s) I made.

## Playing the List

### Starting up the list
Open the installation folder and double click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `SKSE` and press the `Run` button. 

### In-Game MCM options

- This serves as a placeholder in case you want to use the Readme as some sort of template.

### Starting the Game

- Placeholder for your Readme. By default, Ascensio uses [Optional Quick Start](https://www.nexusmods.com/skyrimspecialedition/mods/63953).
	
## Adding mods to Ascensio

To safely add mods to Ascensio, please read [the guide](https://github.com/The-Animonculory/Animonculory-Visual-Overhaul/blob/main/Adding%20mods%20to%20AVO.md), which covers some of the details you need to know.

### Anniversary Edition

Ascensio is on a [downgraded](https://www.nexusmods.com/skyrimspecialedition/mods/57618) version (1.5.97) of Skyrim. As stated at the top of this document, it **does require** the paid update. 


## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. To not have mods delete, add **[NoDelete]** at the beginning of said mod. 

## FAQ

> Is there any documenation on what __Graphics__ mods were used in Ascensio?

Yes, [Click Here to See it](https://github.com/Curly0208/Ascensio/blob/main/Graphical%20Documention.md)

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 2048
- `Ambient Occlusion`: Either use this or the ENB version. The ENB version is more intensive. Do not have both turned on.
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

If you want to tweak your ENB to improve performance, consider looking at Annakin's [ENB Tips](https://github.com/The-Animonculory/Modding-Resources/blob/main/ENB%20Tips.md) guide. 

To quote her, here is a short answer to improve performance with an ENB turned on.
> #### How can I improve performance?
> - Uncheck `EnableLens`.
> - Uncheck `EnableBloom`.
> - Uncheck `EnableDepthofField`.
> - Uncheck `EnableTessellation` in `WATER`.
> - Uncheck `ComplexFireLights` and `ComplexFireLights` OR
>   - Uncheck `EnableBigRange` in these two settings.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Contact

Whilst I am available primarily on [my server](https://discord.gg/DffHKcszfg), please check the [issues](https://github.com/Curly0208/Ascensio/issues) tab on github first if you have any issues. PLEASE DO NOT DM ME ON DISCORD.

You are welcome to [contribute](https://github.com/Curly0208/Ascensio/blob/main/Contributing.md) to the list, however please check the [changelog](https://github.com/Curly0208/Ascensio/blob/main/Changelog.md) before you do.

## Credits and Thanks

- _YOU_ for reading this.
- The entire staff of the [Animonculory](https://discord.gg/DffHKcszfg). They've been unconditionally supportive of my work and I couldn't have done it without them.
  - Styyx for answering and all of my questions
  - Althro for his advice on various topics
  - Destiny for always having my back
  - Astro for coming up with the name *Ascensio*
  - Anna for always giving me a good laugh 
  - Arkay & Chef for being awesome dudes
- The cool dudes over at [Jolly Co-Operators](https://discord.gg/jolly-coop)
- JustThatKing for his endless knowledge on graphics
- iAmMe his endless support and double checking my work
- Bingus for jump starting my modding journey
- Noggog for Mutagen and the xEdit team for xEdit and their tools
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
