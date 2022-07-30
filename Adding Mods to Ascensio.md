# Adding mods to Ascensio

## Disclaimer

No modifications are supported as we cannot track down what everyone has done. If you have modified your list, you void your support and bug reporting.

**However**, I am lenient with those who want to learn how to mod Skyrim properly. Do not take this as me willing to hold your hand while modifying Ascensio. Do not also ask questions and demand answers. This will get you quickly on my mental list of "Do not help x person due to y reason". I made Ascensio to give back to those who are struggling with modding. I want to help those who want to learn how to use tools use as xEdit, the Creation Kit, Nifskope, Bodyslide, Outfit Studio, and the like. I want bolster people's journey in modding skyrim, not dissuade those from trying it. Break the list, ask for some help. If it is unfixable, then reinstall the list and try again. Keep your head up and ask smart questions. If you do so, you'll begin to *actually* learn how to mod properly. 

## Things to Know Before Modifying

Ascensio uses **Skyrim version 1.5.97**. This means that **you need to use plugins that are made for Skyrim version 1.5.97**. If your desired plugin does not exist for 1.5.97 (commonly referred to as SE) then you cannot use it (E.g. [Dynamic Armor Variants](https://www.nexusmods.com/skyrimspecialedition/mods/65963)).

Ascensio is method patched which means that you can, within reason, remove or change near enough anything. The only things that are not method patches are the generated outputs. These **will need to be regenerated** depending on what you change. More details are given in the relavant sections.

## Before You Begin

You may have seen us say "the left should match the right" when it comes to modlists, but what does this actually mean?

What it essentially means is that your mod order on the left hand side of MO2 matches the plugin order on the right. For example, USMP is designed to load after USSEP and on the right hand plugin view side will load like that. Therefore, we should place the USMP mod on the left hand below USSEP in priority. Whatever loads lower in priority (higher number) will be what is loaded in the game.

### Bash & Smash

**NEVER** attempt to create a Bash or Smashed patch on AVO. You should **ONLY** use Wrye Bash to swap masters on a plugin or use the mod-checker and **NEVER** attempt to use Smash oon this list. Bash and smash patches are, for Skyrim Special/Anniversary Edition, broken and **SHOULD NOT** be used. You can do almost everything they do via a custom patch in xEdit.

Neither tool is included with the list as they are not required. If you do wish to add Bash, **you will need to reroute the managed game to your vanilla install**. If you do not, you will break the load order.

### LOOT

Do not use LOOT, plain and simple. Unless you have custom rules set with Lootifier and or know how to do that manually, then do not use LOOT by any means with Ascensio. It will break your game. I am not too knowledgeable with LOOT nor and am I willing to support it. 

### Synthesis

If you add any mod with a plugin, it's recommended to re-run Synthesis. The patchers are split into 2 groups and are as follows:

__Synthesis__
- ENBLightPatcher
- GridTransitionCrashFix
- KSHairsBaldHelmentsFixer
- AOSISCSoundPatcher
- SynOpenWorldLoot
- synOblivionInteractionIocns
- Immersive EquipmentMeshGen

__HPH Fix__
- HighPolyHead-RaceMenuPatcher 

__No custom data is used in these patches so you can just simply run them.__


## Adding Mods

Move every addition you make **above** the Synthesis and DynDOLOD esps.

Mods such as armors and weapons will not cause any issues. **However** make sure that any armors you use have bodyslide files for CBBE. 

You will need to rebuild the bodyslide data if you wish to have consistency between your newly added armors and the existing armors. Ascensio uses [OBody Standalone](https://www.nexusmods.com/skyrimspecialedition/mods/58755), thus you need to build all added CBBE armors with Outfit/Body selected with **CBBE Body Special**, and Preset selected with **-Zeroed Sliders-**. To build an armor, you need to go to the bottom left and click **Batch Build...** and make sure **Build Morphs** is checked. Select **only** the armors/clothing you added (if you select all then it will override the default list's bodyslide output). 

**Pro Tip:** If you want to search for a specific outfit instead of scrolling through tons and tons of them in the Batch Build, then use the top right and search for it by name. The naming scheme is from the `.osd` file in the mod's contents. 

[Click Here to See an Image of what it should look like.](https://cdn.discordapp.com/attachments/807279009992802364/1002715827465879562/unknown.png)

For mods that include SKSE Plugins, **you need to use plugins that are made for Skyrim version 1.5.97**. This is mandatory and if your desired plugin does not exist for 1.5.97 (commonly refered as SE), then you can't use it.

### Mesh/Texture Replacers

This is where things can get a bit complicated. What action you'll need to take depends on what your mesh/texture does. Mesh/texture replacer mods tend to fall into three categories: worldspace, non worldspace and NPC replacers. 

#### Non Worldspace Meshes/Textures

These are mods that change things relating to: 
- Armors
- Weapons
- Interiors
- Food

Simply position these in the correct section as indicated on the left hand side. If there are any esp's present, move them to the correct position and resolve any conflicts that arise in xEdit. Any new armors you add will require bodyslide files for CBBE.

**Note**: Make sure that the normal maps match for the texture/mesh you are using. If they do not, you will see some weird looking things.

#### Worldspace Mesh/Texture Replacers

These are mods that change things relating to
- Landscape
- Trees
- Architecture incl: Cities, towns and villages
- Mountains

These are more involved as you will need to regenerate the LOD files to ensure there is consistency across the worldspace. After positioning these in the correct section, please follow [this guide](https://github.com/The-Animonculory/Modding-Resources/blob/main/DynDOLOD.md) for regenerating the LOD files.

#### NPC Replacers

These are mods that change things relating to:
- NPC's
- Facedata

Ascensio uses EasyNPC to change and enhance NPC faces. To run EasyNPC please consult the EasyNPC's [Documentation](https://github.com/focustense/easymod/wiki/easynpc-%E2%80%90-Home). Long story short, if you want to rerun EasyNPC using my Profile and my current NPC setup, you need to activate all of the mods I have used and then deactivate them after running EasyNPC. For the sake of lessening the download size, I have not included the actual installations of each NPC replacer I've used. To not actually pirate the mods I've used, you have downloaded them, not actually installed them. You must install all of the following NPC replacers to get no errors rerunning EasyNPC.

[Here](https://cdn.discordapp.com/attachments/807279009992802364/1002721525343998022/unknown.png) is a list of all the NPC visual replacers I use.