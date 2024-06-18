# Old Old World
A complete README for the Wabbajack TTW list "Old Old World."

- [The Why](#the-why)
- [What is Wabbajack](#what-is-wabbajack)
- [Old Old World Features](#old-old-world-features)
- [Installation](#installation)
  - [Clean Installation](#clean-installation)
  - [INI Folders](#ini-folders)
  - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c++-redistributable-package)
- [Steam Config](#steam-config)
  - [Reinstallation](#reinstallation)
  - [Steam Library](#steam-library)
  - [Set the Game language to English](#set-the-game-langauage-to-english)
- [Using Wabbajack](#using-wabbajack)
  - [Preparations](#preparations)
  - [Downloading and Installing](#downloading-and-installing)
  - [Problems with Wabbajack](#problems-with-wabbajack)
- [Installing TTW](#installing-ttw)
- [Manually Installed Mods](#manually-installed-mods)
 

# The Why
**This segment is entirely optional to read. These are just the events leading up to the creation of Old Old World.**

I was addicted to seeing New Vegas and TTW modding videos on YouTube. I loved creators such as [Mutant Mods](https://www.youtube.com/@Mutant_Mods/), [Mortyyyy](https://www.youtube.com/@Mortyyyy01) and [DarkPopulous](https://www.youtube.com/@Darkpopulous). I saw their modded setups and admired them. I thought to myself, "Can't I make a modlist that takes all the best parts from their load orders?" 

That is when I found [Wabbajack](https://www.wabbajack.org/). I was scrolling and found a [DroppedIceCream](https://www.youtube.com/@DroppedIceCreamMods) video about Viva New Vegas. I knew it was a New Vegas guide, and then he said the magic word "Wabbajack." I was interested. An automatic mod installer that didn't make me a mod pirate. That seemed impossible to believe, yet here I am now. I dug into the rabbit hole; this was just after I had made a [Reddit post](https://www.reddit.com/r/FalloutMods/comments/1bhxmp4/fnv_my_best_modlist_for_fallout_new_vegas/) detailing my best load order for New Vegas. This post is extremely outdated. I made it before I understood a lot of the stuff I understand today. You can see it, just for the sake of laughing at my horrible choices. (Please do not follow it).

Now, one Reddit user known as [xBlue69](https://www.reddit.com/user/xblue555x/) convinced me to try Wabbajack. I joined the Wabbajack [Discord server](https://discord.com/invite/wabbajack), and I was a moron. I barely understood anything. I spoke with JanuarySnow, Althro, Luca, TDarkShadow, and Reyqune (they are all amazing) for hours. I was the most ignorant person on the planet. 

I didn't know [Stock Game](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#stock-game), [Rootbuilder](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#rootbuilder) and so many other things. They set me on the right path, and I continued. I eventually found Salamand3r's [New Vegas Visual Renewal](https://salamand3r.fail/new-vegas-visual-renewal) guide, which then led me to the [Wasteland Survival Guide](https://wastelandsurvivalguide.github.io/). This guide is the [Viva New Vegas](https://vivanewvegas.moddinglinked.com/index.html) of TTW modding. Amazing. I love it. I used it, and then I came back for the Texture guide. After that, I began browsing [Additions](https://wastelandsurvivalguide.github.io/docs/additions), adding mods as I went. I then added [STARS](https://wastelandsurvivalguide.github.io/docs/stars), downloaded a LOT of extra mods, merged like 25 ESPs using [zEdit](https://github.com/z-edit/zedit/releases), and finally generated some LOD using [xLODGen](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-114-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/). That was the last piece of the puzzle. I was ready to make a list. Of course, I still had to setup this README and my [Discord server](https://discord.gg/ez3dsBub8Q) before I published it, so I had to wait a little longer. In the meantime, I made some patches using [xEdit](https://www.nexusmods.com/newvegas/mods/34703) by following [Biggie Boss'](https://www.youtube.com/@biggie_boss) guide on patching ESPs (love you, Biggie!).

This is it: the full story. Of course, I had like 14 different modding attempts that all failed, but we don't remember those.

**From here, you cannot skip any segments; if I see you asking about something addressed in this README, well, let's not talk about that.**

# What is Wabbajack?

Wabbajack is an automated modlist installer that works by scanning the [META files](https://wiki.wabbajack.org/modlist_author_documentation/Meta%20Files.html) of MO2 Downloads so that it can download the mods on the user's device without redistributing any assets of said mods. This is needed because in the world of Bethesda modding, no clear permissions have been set for mods, each mod can have radically different permissions. That's why things like modpacks, or modlists, as we call them, didn't come until later down the line.

# Old Old World Features

**This isn't a complete list. This list just has some of the highlights. I will leave you to find the rest of the hundreds of features that this list adds.**

-   All mods are Rootbuilded, meaning that the Root folder is completely clean. (This is what allows us to install the list and then TTW)

-   A complete UI overhaul thanks to [M.U.X. Interface Overhaul](https://www.nexusmods.com/newvegas/mods/80642) by [Anro19](https://next.nexusmods.com/profile/Anro19/).

-   A tweaks menu, featuring a full selection of engine fixes and personal tweaks, thanks to [lStewieAl's Tweaks and Engine Fixes](https://www.nexusmods.com/newvegas/mods/66347) by [lStewieAl](https://next.nexusmods.com/profile/lStewieAl/about-me?gameId=130). 

-   A full suite of graphical improvements thanks to [NVVR](https://salamand3r.fail/new-vegas-visual-renewal) by [Salamand3r](https://next.nexusmods.com/profile/5al4mand3r/about-me?gameId=130).

-   Some custom patching, though the list in general doesn't need a ton of custom patches.

-   An extraordinary amount of gameplay tweaks and improvements thanks to [Xilandro](https://next.nexusmods.com/profile/Xilandro/mods?gameId=130), [Sweet6Shooter](https://next.nexusmods.com/profile/Sweet6Shooter/about-me?gameId=130), and many more people I couldn't remember.

-   Lore-friendly, hard, and includes a cluster of new content. (I will leave you to find the new content).

-   Old Old World does all this, while having no NSFW. (This is a Fallout game, gore is everywhere).

## Installation

### Clean Installation

In order to ensure that your Fallout New Vegas and Fallout 3 installation is pristine and vanilla, we are going to completely re-install the game. This is especially important if you have modded the game previously as left-over files might interfere with your installation. If you never modded Fallout New Vegas and Fallout 3 and/or never installed other Wabbajack lists, you may skip this step. However, I still recommend you verify the game files through Steam in that case.

-   Uninstall Fallout New Vegas and Fallout 3 through Steam
-   Navigate to your Steam directory.
-   If there is still a Fallout New Vegas and Fallout 3 folder there, delete it.

### INI Folders

More Fallout-related files are located inside the so-called INI Folder which needs to be cleaned out as well. It contains your save games as well as the game’s INI files and, if you modded Fallout New Vegas before, NVSE plugin logs.

-   Navigate to the INI Folder, this is found under Documents/My Games.
-   If you have an ongoing vanilla playthrough, back up the Saves folder.
-   Delete everything inside the Fallout New Vegas and Fallout 3 folder.


### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

# Steam Config

### Reinstallation

The reinstallation also serves the purpose of relocating the game files to a better directory. Using UAC protected folders for the game or any modding tools has a risk of causing issues down the line. It is best to avoid those folders to begin with. Most Wabbajack list authors, myself included, will not provide support for people that disregard this warning and use UAC protected folders anyway. Note that this does not include the Steam client. Additionally, Fallout New Vegas and Mod Organizer 2 should be installed on the same hard drive. Ideally that hard drive would be an SSD to reduce loading times and eliminate stuttering. 

### Steam Library

In order to prevent some confusion, I will refer to the Library in Steam as the Game Library. It is the second of four items in the top menu in the Steam client and contains a list of all your games. A Steam Library on the other hand is a folder on your hard drive into which Steam games are installed. Since we do not want to have files inside a UAC protected folder we should not install Fallout New Vegas in the default directory. A new Steam Library is required.

### Set the Game language to English

You must do this for Wabbajack to work. If your game was previously set to non-English make sure to verify your files on Steam after fixing it. There is no support for non-English TTW.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

# Using Wabbajack

### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in X:\Wabbajack

### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. You can have the Old Old World and Downloads folder be on separate drives without issue, aside from being limited by the slowest drive during Wabbajack installation.

1. Open Wabbajack.
2. Load the Modlist from Disk.
3. Set Old Old World to install to X:\Old Old World and download to X:\Old Old Worlds\Downloads. Your downloads folder can be on a separate drive to save space but Wabbajack's install speed will be limited to your slowest drive. 
4. Click the Go/Begin button.
5. Wait for Wabbajack to finish.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. If you do not see an installation failed warning do not worry about it. If you feel like Wabbajack is stuck or a download is hanging just restart Wabbajack, it will pick up from exactly where you left off.  Please rerun Wabbajack at least twice and try to manually download the file from Nexus first before posting about a failed download.

# Installing TTW

-   Now, after the list is fully installed, you want to create a mod in MO2 called "[No Delete] Tale of Two Wastelands".
-   You then want to head over to [ModPub](https://mod.pub/) and download the [TTW 3.3.2 Installer](https://mod.pub/ttw/133-tale-of-two-wastelands)
-   Extract the downloaded archive to a folder of your choosing.
-   You then want to run the installer as Adminstrator and set the path to where the empty mod called "[No Delete] Tale of Two Wastelands" is.
-   Then you wait for the installer. (This will take quite some type depending on your CPU)

# Manually Installed Mods
-   [Cyberware 2281 and all patches](https://mod.pub/falloutnv/15-cyberware-2281) (Load Order Priority 302, 303 and 304 respectively. Just load the mod in 302 and then load the patches after).
-   [Stash Organizer](https://mod.pub/falloutnv/4-stash-organizer) (Load Order Priority 225).
-   [FNV 4GB Patcher](https://www.nexusmods.com/newvegas/mods/62552?tab=description) (Install the Patcher into your Root folder, let it run, and then FNV will be patched).

# Credits
- The NVSE team for NVSE and xNVSE.
- lStewieAl for the amazing lStewieAl's Tweaks mod.
- Salamand3r for NVVR.
- Vish for Viva New Vegas.
- NMC for his awesome texture work.
- Sweet6Shooter for the perks and gameplay.
- Bale for his Physically Based series.
- JanuarySnow for being an amazing, kind and helping person.
- Althro for everything that he has done.
- Luca, fucking madman maniac.
- TDarkShadow, knowledgeable as hell.
- ElminsterAU for xEdit.
- Audixas for being the lead at the Wasteland Survival Guide.
- WallSoGB for being a "crazy code monkey."
- Total, I sto--I mean borrowed some of his own README.
- SpringHeelJon, same story.
- And so many more that I just couldn't list even if I tried. Don't forget to endorse these mod authors, they deserve it.
