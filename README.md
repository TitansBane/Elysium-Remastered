![Logo](https://raw.githubusercontent.com/TitansBane/Elysium-Remastered/main/image/Elysium_Remastered_Banner.webp)

# Elysium Remastered

- [Elysium Remastered](#elysium-remastered)
  - [Preface](#preface)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
        - [Could not download x](#could-not-download-x)
  - [Post-Installation](#post-installation)
    - [Root Builder](#root-builder)
    - [Creation Club](#creation-club)
    - [ENB](#enb)
  - [How to start up Elysium Remastered](#how-to-start-up-elysium-remastered)
  - [Updating](#updating)
  - [Noteworthy Mods](#noteworthy-mods)
    - [Gameplay](#gameplay)
    - [Quest and Encounter Mods](#quest-and-encounter-mods)
    - [Followers](#followers)
    - [Audio and Weather](#audio-and-weather)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Other Post Installation FAQ](#other-post-installation-faq)
    - [Performance Help](#performance-help)
    - [Controlmap](#controlmap)
    - [Gamepad Support](#gamepad-support)
    - [Ultrawide Support](#ultrawide-support)
    - [Zoomed in Display](#zoomed-in-display)
    - [Removing the Modlist](#removing-the-modlist)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Changelog](#changelog)

## Preface

Elysium Remastered is a complete rebuild of the original Elysium modlist. Like the original, it focuses primarily on visuals and fully features hundreds of new additions and full Creation Club support ($20 for Anniversary Upgrade is required)—extending the base setup with Enai Siaion's full suite of gameplay overhauls and various new quests and encounters. In addition, many new mods, such as Beyond Skyrim - Bruma, Interesting NPCs, Legacy of the Dragonborn, Wyrmstooth, and a wide variety of new content, were added. You should expect a more challenging game with this list.

**Yes, this means you NEED the $20 Anniversary Edition upgrade to install this list**

## Installation

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right-click the game in your Library->Properties), navigate to the _General_ tab, and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Bethesda is still updating SSE (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. It would be best if you also disabled the Steam Cloud while you're at it.

Another problem with Steam is that if you have it installed with it's suggested paths, your first Steamlibrary will be in your Program Files folder which is a protected folder. Moving your Steamlibrary out of your Program Files folder is a key setup for a working modded experience. If you are having trouble doing so check [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting its contents.

#### Start Skyrim

After you have done everything above and got a clean SSE installation-ready, start the Launcher and let it do the initial graphics check. Do not worry about this part as the installation will replace these graphics settings, then Start Skyrim.

**Now, log in to the Creation Club and download all of the Creation Club content.**

Once that done, close Skyrim.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near your drive's root level like `C:/Wabbajack.`

#### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest amount of threads and fastest speed, it is advised to place the working folder on an SSD.

1. Open Wabbajack.
2. Click `browse modlists` (don't forget to tick show `unofficial lists`), and download Elysium Remastered from the Modlist Gallery. Wait until you are forwarded to the next window.
3. Adjust the download and installation paths. The recommended Installation Path is a blank folder at the root of a drive, such as C:\Elysium Remastered. The Download Path will update automatically. You can move it elsewhere if you want.
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off, so you lose no progress.

##### Could not download x

**The Elysium.Wabbajack from the gallery:** Please try using the [Network Workaround](https://cdn.discordapp.com/attachments/623314477151944718/880228863945343046/Discord-VPN.png) in Wabbajacks settings first. Alternatively try using a VPN service, Proton VPN is available for free if needed. If BOTH these things do not work, feel free to ask for more help in the community discord linked below.

**Anything with "Output" in the name:** These files are very large and are known to cause issues. Please try downloading them manually from the Nexus Page linked [here](https://www.nexusmods.com/skyrimspecialedition/mods/65080?tab=files). Download the missing files manually, drop them in the WJ downloads folder **WITHOUT EXTRACTING** and rerun Wabbajack.

**Anything with "Mega" or "Google Drive" in the name:** All needed files should be pinned in the #ely-remastered-support channel available in the [community discord](https://discord.gg/sxBH2c2MqF). Alternatively the links are always at the bottom of your Wabbajack log if u prefer that method. Download the missing files manually, drop them in the WJ downloads folder **WITHOUT EXTRACTING** and rerun Wabbajack.

**High Poly Head:** Mirror available [here](https://drive.google.com/drive/folders/1V_jcYzwTiKnSv8Dbv-7Z0hh9SWbkn6Bi) aswell as in the discord. Download the missing files manually, drop them in the WJ downloads folder **WITHOUT EXTRACTING** and rerun Wabbajack.

**x is not a whitelisted download:**

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

### Root Builder

Unlike regular Skyrim installation or other Wabbajack lists, Elysium Remastered uses a tool known as Root Builder. For more details regarding it, please view [the mod page](https://www.nexusmods.com/skyrimspecialedition/mods/31720)

If you wish to change ENB, please follow the steps below.

### Creation Club

Elysium Remastered utilizes all Creation Club content for Legacy of the Dragonborn and various other mods. It is fully integrated into Skyrim's world. The list requires all purchasable downloadables or the Anniversary Upgrade to start up and play.

### ENB

By default, Elysium Remastered comes configured with [Rudy ENB for NAT 3](https://www.nexusmods.com/skyrimspecialedition/mods/91675)

Suppose you want a different ENB. You can choose from a wide variety of ENBs on the Nexus that support NAT.ENB III. To replace the stock ENB, click on the `Jigsaw Puzzles` icon in MO2, select `Root Builder`, and tick the `Installer` checkbox under `Settings`. Add the ENB as a new mod in MO2. Rootbuilder should assign it correctly. Disable ENBSeries - Rudy ENB for NAT 3 and activate your new ENB.

A few other ENB suggestions are:

- [Berserkyr ENB](https://www.nexusmods.com/skyrimspecialedition/mods/62381)
- [PI-CHO ENB](https://www.nexusmods.com/skyrimspecialedition/mods/35082)

**Note:**
Please check that vsync is set to disable in enblocal.ini otherwise you will either be stuck compiling shaders or a black screen, or the menu with no options.

## How to start up Elysium Remastered

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it. Ensure it is set to Elysium [SKSE] by selecting it in the dropdown box and then hitting the run button which [will lock ModOrganizer with a similar message (DO NOT PRESS UNLOCK IT WILL MAKE YOUR SAVE FILES CORRUPTED)](https://prnt.sc/zu3NUpAPO7cN), simply wait until the game loads. You have to run Elysium [SKSE] through Mod Organizer 2 in order to play Elysium Remastered from now on.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## Noteworthy Mods

### Gameplay

Elysium Remastered uses the full suite of Enai Siaion's mods, which are:

1. [Apocalypse - Magic of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/1090)
1. [Evenstar - Minimalistic Standing Stones of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/41256)
3. [Growl - Werebeasts of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/31245)
4. [Morningstar - Minimalistic Races of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/22298)
5. [Odin - Skyrim Magic Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/46000)
6. [Sacrilege - Minimalistic Vampires of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/42408)
7. [Summermyst - Enchantments of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/6285)
8. [Thunderchild - Epic Shouts and Immersion](https://www.nexusmods.com/skyrimspecialedition/mods/1460)
9. [Triumvirate - Mage Archetypes](https://www.nexusmods.com/skyrimspecialedition/mods/39170)
10. [Vokrii - Minimalistic Perks of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/26176)
11. [Wildcat - Combat of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/1368)
12. [Wintersun - Faiths of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/22506)

Various other mods are used to flesh out all aspects of the game as well such as:

1. [Open World Loot - Encounter Zone and Loot Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/49681) for overhauling Skyrim's encounter zones and loot system.
2. [Reliquary of Myth - Artifact Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/31612) for overhauling Skyrim’s unique items.
3. [Animated Armoury - DAR Version - New Weapons with animations](https://www.nexusmods.com/skyrimspecialedition/mods/35978) which adds new weapons to Skyrim with custom attack animations, for both the Player and NPCs.
4. [Complete Crafting Overhaul Remastered](https://www.nexusmods.com/skyrimspecialedition/mods/28608) which overhauls the crafting component of the game.
5. [Weapons Armor Clothing and Clutter Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/18994) which fixes bugs and inconsistencies for Skyrim's weapons, armors, clothing, jewelry, and clutter items.
6. [Spell Perk Item Distributor](https://www.nexusmods.com/skyrimspecialedition/mods/36869) and [Enemy (R)evolution of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/37228) allows for enemies to use spells and perks from mod-added stuff.
7. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) drastically changes how pacing in the game is accomplished. Rather than only getting experience on skill level-ups, you now gain experience level for completing quests and killing monsters.
8. [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807) adds trait based weakness and resistances based on armor and enemy type.

### Quest and Encounter Mods

Elysium Remastered comes with a wide variety of new quests and encounters. A few are listed below.

[Legacy of the Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802) is an enormous mod that shapes the way how you play the game. The museum is a very robust house mod with the ability to display almost every item in the game and also has extensive mod support, which is utilized to some extent in Elysium Remastered.

[Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194) adds over 250 fully voiced NPCs, 25+ followers, 15+ marriage candidates, and 50+ quests to flesh out the world of Skyrim fully. Every hold will feel more lively, with more NPCs walking and talking with each other.

[Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576?tab=files) adds a large number of localized radiant quests found at Missive Boards of varying difficulty and with varying rewards. Missives have been extended to Solstheim, Bruma, and Wyrmstooth as well.

[Beyond Skyrim - Bruma SE](https://www.nexusmods.com/skyrimspecialedition/mods/10917) is a DLC sized new lands mod that allows you to travel beyond the borders of Skyrim and explore Bruma, the northernmost county in Cyrodiil. Delve into Ayleid ruins, meddle in local affairs or explore the wilds - the journey begins now.

[Vigilant](https://www.nexusmods.com/skyrimspecialedition/mods/11849) adds a whole new set of quests, enemies, equipment to the game revolving around the Vigilants of Stendarr and Daedra. Vigilant has been tweaked to start at level 25 and requires you to finish the House of Horrors quest to prevent easy access to high-level gear and fighting bosses that are almost impossible to beat at lower levels.

[Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/45565) adds a new quest that takes the Dragonborn to the island of Wyrmstooth situated north of Solitude across the Sea of Ghosts. Battle across new landscapes and through new dungeons in this expansion-sized mod. Wyrmstooth has been tweaked to start at level 30, and all dungeons now scale around level 30ish.

[The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168) is a medium-sized quest that expands Arniel's Endeavor to acquire Sunder and Wraithguard, completing the trifecta.

[Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179) is an excellent choice-driven quest mod with many endings surrounding the disappearance of a civilization.

[Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155) is a DLC-sized quest mod involving a castle high in the Velothi Mountains, which feature a obtainable player home.

[Immersive World Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/18330) adds a large number of roughly 100 new random events and new quests as well as modifying some of the vanilla events.

Elysium also has a lot of modified vanilla quests such as:

1. [Save the Icerunner - Lights Out Alternate Route](https://www.nexusmods.com/skyrimspecialedition/mods/34681)
2. [Finding Deerkethus](https://www.nexusmods.com/skyrimspecialedition/mods/19550)
3. [Finding Helgi and Laelette](https://www.nexusmods.com/skyrimspecialedition/mods/28973)
4. [Finding Velehk Sain](https://www.nexusmods.com/skyrimspecialedition/mods/19815)

As for the Creation Club content; most of it is **delayed** with mods such as [Rebalancing Anniversary Edition](https://www.nexusmods.com/skyrimspecialedition/mods/61004) or [CC Farming - Tweaks, Enhancement and Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/69029).

### Followers

[Inigo](https://www.nexusmods.com/skyrimspecialedition/mods/1461) is a fully voiced Khajiit adventuring companion with over 7000 lines of unique dialogue - much of it about you. He'll level alongside you and avoid most traps. If you are sneaking, he will not chatter, and he will whisper if you talk to him. He can run out of arrows. He is highly skilled in archery, one-handed, and sneak.

[Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035) is a fully voiced Imperial follower with around 3000 lines of immersive, lore-friendly dialogue. Though he arrives in Skyrim as a cowardly scholar, he will gradually gain strength and confidence by your side until he grows into a hero in his own right.

### Audio and Weather

[Audio Overhaul Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/12466), [Immersive Sounds Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/523), and [Sounds of Skyrim Complete](https://www.nexusmods.com/skyrimspecialedition/mods/8286) offer an amazing base for Skyrim's ambiance and foley.

## Creating your Character

After starting a new game, you will be dropped in the Alternate Start - Live Another Life cell where you can customise your character, then configure your mods before you actually start playing.

Stand still and wait until all messages have run through in the upper left corner (check the screenshot below). Then hit ESCAPE and create a manual save before you continue.

## In-Game MCM Options

All the required MCM options have been automated for you. Enjoy the game or tweak the following to your liking:

#### Lucien 
- (If you set a nickname that's supported he can call you by that name)

#### VIGILANT
 - No tweak here; you can manually adjust the difficulty if you find the mod too easy. Just note that this is a LATE GAME QUEST. It will make much more sense if you do it after the Dawnguard questline and the House of Horrors quest.

**Note: Dodging is provided by the Mod "The Ultimate Dodge Mod". You can head to System > Controls > Sneak and change the Keybind to whatever you want to use to dodge with. However, I recommend sticking with the default buttons else; the crouch slide animation might not function correctly.**

## Other Post Installation FAQ

### Performance Help

Elysium is a list designed for higher end PCs. But with some tweaks the list is certainly still playable on lower specs. Fortunately members of our community have put together [this guide](https://docs.google.com/document/d/12QomWYtzGeq62f6MZ-gMKf62Go1AhRFo/edit). 
These tweaks DO NOT break rule 11 unless otherwise mentioned, so please feel free to ask questions in the community discord.

### Controlmap

These are currently the custom controls added by Mods. Feel free to customize them within the Mod's MCM menus

- Quick Light : L
- Crouch Sliding - Crouch Slide : Press and hold Alt + Ctrl
- Immersive HUD - Toggle HUD : X
- Nether's Follower Framework - Horse Whistle : H
- OBody - Apply Bodyslide Preset : F10
- The Ultimate Dodge Mod - Dodge : Shift  **Note: To change this keybind you want to rebind the Sneak key in Skyrim Settings > Controls**
- The Ultimate Dodge Mod - Change Dodging Style : G (This changes between side-stepping and rolling)

### Gamepad Support

Once in-game go to The Ultimate Dodge Mod MCM and configure your Player Settings! This step is crucial for gamepad support.
- The Ultimate Dodge Mod → Player Settings :
  - Gamepad/Controller Compatibility : Enabled
  - Sneak Style : Sneak Style 2
  
### Ultrawide Support

If you have an ultrawide monitor (21:9), the UI will be off. Thankfully, widescreen support is integrated into Elysium Remastered by default, so all you need to do is enable all widescreen support mods on the left side of MO2 under the `44 WIDESCREEN SUPPORT` separator and place the widescreen_skyui_fix.esp below SkyUI_SE.esp in the load order. That's it, and you can now start the game up and play.

### Zoomed in Display

This can be caused by Window's Display Scaling feature. This usually is set to above 100% when using very large (32 inch++) sized monitors and TVs. There are two solutions to this

- Set the display scaling back to 100% in the Screen Resolution Settings for Windows
- Edit the mod SSE Display Tweaks.
  - Under `[Render]`
    - Set Fullscreen to `True`
    - Set Borderless to `False`

### Removing the Modlist

You can remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder, so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a lot!!
- Halgari and everyone in the WJ Team - Wabbajack is incredible, and so are you!

## Contact

While I am sometimes available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/TitansBane/Elysium-Remastered/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Changelog

See [Changelog](CHANGELOG.md).

***

[[Back to top]](#elysium-remastered)
