# Old Old World
A complete README for the Wabbajack TTW list "Old Old World."
 
 - [The Why](#the-why) (This segment is completely optional to read; it just details how I made the list)
 
 - [What is Wabbajack](#what-is-wabbajack)
 
 - [Old Old World Features](#old-old-world-features)

 - [Requirements](#requirements)
  
 - [Installation](#installation)
   
    - [Clean Installation](#clean-installation)

    - [INI Folders](#ini-folders)

    - [Installing Microsoft Visual C++ Redistributable Package](#installing-the-microsoft-visual-c-redistributable-package)
 
 - [Steam Config](#steam-config)
    
    - [Reinstallation](#reinstallation)

    - [Steam Library](#steam-library)
    
    - [Setting the Game language to English](#setting-the-game-language-to-english)

- [GOG Config](#gog-config)
 
- [Using Wabbajack](#using-wabbajack)
  
    - [Preparations](#preparations)
    
    - [Downloading and Installing](#downloading-and-installing)
  
    - [Problems with Wabbajack](#problems-with-wabbajack)
 
 - [Installing TTW](#installing-ttw)
 
 - [Manually Installed Mods](#manually-installed-mods)
 
 - [Post-Installation](#post-installation)

 - [Q&A](#qa)
 
 - [Where to Ask for Support](#where-to-ask-for-support)
  
   - [Don't Ask on the Wabbajack Server](#dont-ask-in-the-wabbajack-server)

   - [Don't DM Me or Anyone Regarding the List](#dont-dm-me-or-anyone-regarding-the-list)
   
   - [Ask in My Discord Server](#ask-in-my-discord-server) 
 
- [Updating](#updating)
 
- [How to Keep Extra Mods After Updating](#how-to-keep-extra-mods-after-updating)

- [Credits](#credits)

# The Why
**This segment is entirely optional to read. These are just the events leading up to the creation of Old Old World.**

I was addicted to seeing New Vegas and TTW modding videos on YouTube. I loved creators such as [Mutant Mods](https://www.youtube.com/@Mutant_Mods/), [Mortyyyy](https://www.youtube.com/@Mortyyyy01) and [DarkPopulous](https://www.youtube.com/@Darkpopulous). I saw their modded setups and admired them. I thought to myself, "Can't I make a modlist that takes all the best parts from their load orders?" 

That is when I found [Wabbajack](https://www.wabbajack.org/). I was scrolling and found a [DroppedIceCream](https://www.youtube.com/@DroppedIceCreamMods) video about Viva New Vegas. I knew it was a New Vegas guide, and then he said the magic word "Wabbajack." I was interested. An automatic mod installer that didn't make me a mod pirate. That seemed impossible to believe, yet here I am now. I dug into the rabbit hole; this was just after I had made a [Reddit post](https://www.reddit.com/r/FalloutMods/comments/1bhxmp4/fnv_my_best_modlist_for_fallout_new_vegas/) detailing my best load order for New Vegas. This post is extremely outdated. I made it before I understood a lot of the stuff I understand today. You can see it, just for the sake of laughing at my horrible choices. (Please do not follow it).

Now, one Reddit user known as [xBlue69](https://www.reddit.com/user/xblue555x/) convinced me to try Wabbajack. I joined the Wabbajack [Discord server](https://discord.com/invite/wabbajack), and I was a moron. I barely understood anything. I spoke with JanuarySnow, Althro, Luca, TDarkShadow, and Reyqune (they are all amazing) for hours. I was the most ignorant person on the planet. 

I didn't know [Stock Game](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#stock-game), [Rootbuilder](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#rootbuilder) and so many other things. They set me on the right path, and I continued. I eventually found Salamand3r's [New Vegas Visual Renewal](https://salamand3r.fail/new-vegas-visual-renewal) guide, which then led me to the [Wasteland Survival Guide](https://wastelandsurvivalguide.github.io/). This guide is the [Viva New Vegas](https://vivanewvegas.moddinglinked.com/index.html) of TTW modding. Amazing. I love it. I used it, and then I came back for the texture guide. After that, I began browsing [Additions](https://wastelandsurvivalguide.github.io/docs/additions), adding mods as I went. I then added [STARS](https://wastelandsurvivalguide.github.io/docs/stars), downloaded a LOT of extra mods, merged like 25 ESPs using [zEdit](https://github.com/z-edit/zedit/releases), and finally generated some LOD using [xLODGen](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-114-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/). That was the last piece of the puzzle. I was ready to make a list. Of course, I still had to setup this README and my [Discord server](https://discord.gg/ez3dsBub8Q) before I published it, so I had to wait a little longer. In the meantime, I made some patches using [xEdit](https://www.nexusmods.com/newvegas/mods/34703) by following [Biggie Boss'](https://www.youtube.com/@biggie_boss) guide on patching ESPs (love you, Biggie!).

This is it: the full story. Of course, I had like 14 different modding attempts that all failed, but we don't remember those.

**From here, you cannot skip any segments; if I see you asking about something addressed in this README, well, let's not talk about that.**

# What is Wabbajack?

Wabbajack is an automated modlist installer that works by scanning the [META files](https://wiki.wabbajack.org/modlist_author_documentation/Meta%20Files.html) of MO2 Downloads so that it can download the mods on the user's device without redistributing any assets of said mods. This is needed because in the world of Bethesda modding, no clear permissions have been set for mods, each mod can have radically different permissions. That's why things like modpacks, or modlists, as we call them, didn't come until later down the line.

# Old Old World Features

**This isn't a complete list. This list just has some of the highlights. I will leave it to you to find the rest of the hundreds of features that this list adds.**

-   Old Old World makes use of the Root Builder MO2 plugin, which ensures the game installation folder doesn't get modified.

-   A complete UI overhaul thanks to [Vanilla UI Plus](https://www.nexusmods.com/newvegas/mods/80642](https://www.moddb.com/mods/vanilla-ui-plus/downloads/vanilla-ui-plus-nv)) by [Axonis](https://www.moddb.com/members/axonis).

-   A tweaks menu, featuring a full selection of engine fixes and personal tweaks, thanks to [lStewieAl's Tweaks and Engine Fixes](https://www.nexusmods.com/newvegas/mods/66347) by [lStewieAl](https://next.nexusmods.com/profile/lStewieAl/about-me?gameId=130). 

-   A full suite of graphical improvements thanks to [NVVR](https://salamand3r.fail/new-vegas-visual-renewal) by [Salamand3r](https://next.nexusmods.com/profile/5al4mand3r/about-me?gameId=130).

-   Custom patching exclusive to the list.

-   An extraordinary amount of gameplay tweaks and improvements thanks to [Xilandro](https://next.nexusmods.com/profile/Xilandro/mods?gameId=130), [Sweet6Shooter](https://next.nexusmods.com/profile/Sweet6Shooter/about-me?gameId=130), and many more people I couldn't remember.

-   Lore-friendly, hard, and includes a cluster of new content. (I will leave you to find the new content).

-   Old Old World supports both `Steam` and `GOG` stores.

-   Old Old World does all this while having no NSFW. (This is a Fallout game; gore is everywhere).

# Requirements

**I cannot provide support for different specifications and setups. I do not know how to improve FPS on other devices. Do not ask me about it. You can, however, ask on the support server, but no matter what you have, you need either Windows 10 or Windows 11.**

### Specifications

My specs are the following:

- RTX 4090.

- Intel 13900K.

- 256GB of DDR5.

- TTW running on an SSD.

I capped the FPS to 60 using the [Special K](https://www.special-k.info/) program (I don't use any of its other features), and the game is very smooth with minimal crashes. Again, if you want to increase performance, please ask in the support channel, and I personally will not be able to help you.

### Steam/GOG requirements

A legal copy of Fallout 3 with all DLCs from either [Steam](https://store.steampowered.com/app/22370/Fallout_3_Game_of_the_Year_Edition/) or [GOG](https://www.gog.com/en/game/fallout_3_game_of_the_year_edition).

A legal copy of Fallout: New Vegas with all DLCs from either [Steam](https://store.steampowered.com/sub/13435/) or [GOG](https://www.gog.com/en/game/fallout_new_vegas_ultimate_edition).

**(I cannot provide support for any other version, including the PCR version)**

### Extra Requirements

A [Nexus Mods](https://nexusmods.com) account (Premium is not necessary but recommended for automated downloads).

A [ModPub](https://mod.pub/) account.

# Installation

### Clean Installation

**If you use GOG, then please skip to the [GOG Config](#gog-config) section of the README.**

In order to ensure that your Fallout: New Vegas and Fallout 3 installations are pristine and vanilla, we are going to completely re-install the game. This is especially important if you have modded the game previously, as left-over files might interfere with your installation. If you never modded Fallout: New Vegas and Fallout 3 and/or never installed other Wabbajack lists, you may skip this step. However, I still recommend you verify the game files through Steam in that case.

-   Uninstall Fallout: New Vegas and Fallout 3 through Steam.
-   Navigate to your Steam directory.
-   If there is still a Fallout: New Vegas and Fallout 3 folder there, delete it.

### INI Folders

More Fallout-related files are located inside the so-called `INI folder`, which needs to be cleaned out as well. It contains your save games as well as the game’s INI files and, if you modded Fallout: New Vegas before, NVSE plugin logs.

-   Navigate to the INI folder; this is found under Documents/My Games.
-   If you have an ongoing vanilla playthrough, back up the Saves folder.
-   Delete everything inside the Fallout: New Vegas and Fallout 3 folders.


### Installing the Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have it installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under `Visual Studio 2015, 2017, and 2019`. Here is a [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

# Steam Config

### Reinstallation

The reinstallation also serves the purpose of relocating the game files to a better directory. Using `UAC-protected folders` for the game or any modding tools has a risk of causing issues down the line. It is best to avoid those folders to begin with. Most Wabbajack list authors, myself included, will not provide support for people who disregard this warning and use UAC-protected folders anyway. Note that this does not include the `Steam client`. Additionally, Fallout: New Vegas and Mod Organizer 2 should be installed on the same hard drive. Ideally, that hard drive would be an SSD to reduce loading times and eliminate stuttering. 

### Steam Library

In order to prevent some confusion, I will refer to the Library in Steam as the `Game Library`. It is the second of four items in the top menu in the Steam client and contains a list of all your games. A `Steam Library`, on the other hand, is a folder on your hard drive into which Steam games are installed. Since we do not want to have files inside a `UAC-protected folder`, we should not install Fallout: New Vegas in the default directory. A new `Steam Library` is required.

### Setting the Game language to English

You must do this for Wabbajack to work. If your game was previously set to non-English, make sure to verify your files on Steam after fixing it. There is no support for non-English TTW.

Open the `Steam Properties` window, navigate to the `Language` tab, and select `English` from the dropdown menu.

# GOG Config

Inside the game folders of both Fallout 3 and New Vegas, there will be a file known as `unins000`. Run it, and it will activate the uninstaller, completely uninstall the game, and then reinstall it from GOG. (Make sure to delete any extra INI files in Documents:\My Games:\Fallout3 and Documents:\My Games:\FalloutNV).

I doubt you need to do this since you likely already have it installed. The package is required for MO2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under `Visual Studio 2015, 2017, and 2019`. Here is a [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

_This section is not verifiable; I have written it from word of mouth. If someone knows the rest of the steps that GOG users have to take, please DM me at StrawChannel95 on Discord._

# Using Wabbajack

### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in X:\Wabbajack.

### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest number of threads and, thus, the fastest speed, it is advised to have the working folder on an SSD. You can have the Old Old World and Downloads folders on separate drives without issue, aside from being limited by the slowest drive during Wabbajack installation. Click the `Play` arrow. If you have a Nexus Premium account, all of your downloads will be automated. Without Premium, you will need to manually click the Download button for each mod. Installation will be automated, regardless of your account status.

1. Open Wabbajack.
2. Load the Modlist from Disk.
3. Set Old Old World to install to `X:\Old Old World` and download to `X:\Old Old Worlds\Downloads`. Your downloads folder can be on a separate drive to save space, but Wabbajack's install speed will be limited to your slowest drive. 
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. If you do not see an installation failure warning, do not worry about it. If you feel like Wabbajack is stuck or a download is hanging, just restart Wabbajack; it will pick up from exactly where you left off. Please rerun Wabbajack at least twice and try to manually download the file from Nexus first before posting about a failed download. Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Installation](#installation) section, if you own it on GOG, go back to the [GOG Config](#gog-config) section.

# Installing TTW

-   Now, after the list is fully installed, you want to create a mod in MO2 called `[No Delete] Tale of Two Wastelands` by right-clicking, hovering over the `All Mods` prompt, and then press on `Create empty mod inside`, and then you should name it `[No Delete] Tale of Two Wastelands`.
-   You then want to head over to [ModPub](https://mod.pub/) and download the [TTW 3.3.2 Installer](https://mod.pub/ttw/133-tale-of-two-wastelands).
-   Extract the downloaded archive to a folder of your choosing.
-   You then want to run the installer as Adminstrator and set the path to both Fallout 3 and New Vegas, where the empty mod called `[No Delete] Tale of Two Wastelands` is. You can find it by heading to where you installed MO2, going to the `mods` file, and finally going to the file named `[No Delete] Tale of Two Wastelands`.
-   Then you wait for the installer (This will take from 30 minutes to 3 hours).

# Manually Installed Mods
-   [Cyberware 2281 and all patches](https://mod.pub/falloutnv/15-cyberware-2281). Go on ModPub and download the mods by pressing the `MO2 Download` button for the main Cyberware 2281 mod, the TTW 3.3 patch, and the B42 Quickthrow Patch. You can then open up MO2 and simply drag and drop the 3 files on the right that you just downloaded into the main mod menu that is on the left.

-   [Stash Organizer](https://mod.pub/falloutnv/4-stash-organizer). Go on ModPub and download the mod by pressing the `MO2 Download` button. You will then find the file on the right; you want to drag and drop it to the left.

-   [FNV 4GB Patcher](https://www.nexusmods.com/newvegas/mods/62552?tab=description). You want to press the `Manual Download` button. After it's done downloading, you want to extract the archive to where your Fallout: New Vegas is located (Put it in the normal game folder and do not put it in the data folder). After that, you want to run `FNVpatch.exe` as Adminstrator. It should say "FalloutNV Patched."

# Post-Installation

### Running the Game

Select the Old Old World option from the dropdown menu and launch the game. If everything works, congratulations! You can now play the list; if you can't, then head into the [Q&A](#qa) section.

# Q&A

Q: Wabbajack tells me I'm missing a file from the game!

A: Verify the game through Steam, then run it through the launcher and exit. The game must be a non-PCR version on Steam with all of the DLC, and the language must be English.

Q: I have missing masters when I run the game! Help!

A: The list requires you to download and install TTW separately. Reread the [Installing TTW](#installing-ttw) step.

Q: Why are the DLCs so different?

A: I felt that the mods made the DLCs better and more enjoyable while still not taking away anything from the vanilla aesthetic.

Q: The intro of Fallout 3 is weird!

A: I know there is minor clipping, and the cart that holds you doesn't move. I will try finding a fix. Also, TTW Quickstart is enabled, so you should not be able to see this.

Q: The white screens that say "X Years Later" are not there.

A: I know, another thing I'll have to fix. Also, TTW Quickstart is enabled by default, so you just disabled it. Yes, if you ask this question on Discord, I'll not respond.

Q: Are your DMs open?

A: For general questions not regarding the list and chatting, yes. For anything regarding the list, no.

Q: Where is your Discord server?

A: [Here](https://discord.gg/ez3dsBub8Q).

Q: I have installed TTW as shown, but the ESMs are still not there!

A: This version of MO2 can sometimes not refresh properly. Double check that you have enabled the mod by ticking it, then exit and reload MO2. Also, check that the installation of TTW totals 15.7 GB. If it's less than this, something's gone wrong somewhere.

Q: The TTW install page tells me to install a load of other mods as well; do I need these?

A: No, all of these are included in the list.

Q: I get these weird triangles with exclamation marks in the game!

A: Missing assets are caused by having an incorrect TTW setup. See the [Installing TTW](#installing-ttw) section.

Q: I get this weird message in-game about a script overwrite?

A: You need to make sure YUPTTW is enabled in MO2 and directly underneath the main ESMS in the plugin load order, as shown in the instructions.

Q: I get no DLC messages. Are they installed correctly?

A: Yes, the list has a mod that delays the DLCs and does not spam you with the message boxes at the beginning of the game. Just explore the game normally, and you will stumble on them.

Q: My saves have disappeared!

A: The list uses profile-specific saving. They are located in the directory where you installed the list under "profiles," then "Old Old World".

Q: I can't ALT-TAB? It just crashes or freezes.

A: Without going too deep into technicalities, this is intentional when not using DXVK and Flip mode as outlined in the guide. Old Old World's default mode is DX9 and Fullscreen, with improved RAM management from the mod NVTF. One of these RAM improvements makes ALT-TABbing impossible in this mode.

Q: Is "{INSERT MOD NAME HERE}" compatible with the list?

A: Short answer. If you have to ask, then no. Long answer: If you know your way around XEdit and can see what I have done in regards to patching the list for consistency, then absolutely.

# Where to Ask for Support

### Don't Ask on the Wabbajack Server

They cannot help you; they will tell you to head over and ask the modlist author (me).

### Don't DM Me or Anyone Regarding the List

Ask in the support channels; more people see it, and it makes my life easier.

### Ask in My Discord Server

Here is the [link](https://discord.gg/ez3dsBub8Q) (there is also one in [The Why](#the-why) section and another one in the [Q&A](#qa) section).

# Updating

If this Old Old World receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

Old Old World updates are based on a [Semantic Versioning](https://en.wikipedia.org/wiki/Software_versioning) system.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

Generally speaking: 
- Full x.0 (2.0, 3.0, etc) updates requires a new game.  
- Major x.x (2.1, 2.2, etc) updates requires a new game.  
- Minor x.x.x (2.1.1, 2.1.2) updates can be applied to an ongoing playthrough.

# How to Keep Extra Mods After Updating

When updating, any additional mods you have installed on top of Old Old World will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

# Credits
- The NVSE team for NVSE and xNVSE.
- lStewieAl for the amazing lStewieAl's Tweaks mod.
- Salamand3r for NVVR.
- Vish for Viva New Vegas.
- Biggie for his amazing guides.
- NMC for his awesome texture work.
- Sweet6Shooter for the perks and gameplay.
- Bale for his Physically Based series.
- JanuarySnow for being an amazing, kind, and helping person.
- Althro for everything that he has done.
- Luca, fucking madman maniac.
- TDarkShadow, knowledgeable as hell.
- Lizzy for being a modlist messiah.
- matortheeternal for zEdit.
- reyqune for having a sense of humor in these dark times.
- Lartza because he's Finnish and he is literally about to be finished by people like me asking stupid questions.
- ElminsterAU for xEdit and The Method.
- Audixas for being the lead at the Wasteland Survival Guide.
- WallSoGB for being a "crazy code monkey."
- Total because I sto---I mean borrowed some of his own README.
- SpringHeelJon, same story.
- Lively, same story as Jon and Total.
- Cangar & Kvitekvist, same story (This is getting old).
- Everyone at Scenic Route for the idea to include user comments. (I will include them once the list has actually been played by people).
- Apoapse for founding Scenic Route Games and being the lead of Librum.
- Bethesda for the engine and Fallout 3.
- Obsidian for Fallout: New Vegas.
- RoyBatty for being the best New Vegas modder to ever live.
- Axonis for Vanilla UI Plus.
- Jazzisparis for JIP NVSE.
- Halgari for Wabbajack; without him, this list and countless others wouldn't be possible.
- All the other code contributors for helping Halgari.
- YOU for reading this.
- And so many others that I just couldn't list even if I tried. Don't forget to endorse these mod authors; they deserve it.

I wish you all a happy nuclear wasteland.
