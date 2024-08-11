<p align=center>StrawChannel95 is proud to present:</p>

# <p align=center>**Apocalyptic Wonderland**</p>

<table stlyle="border: none;">
<tr>
<td><img src="https://github.com/Arkay-1248/Do-Not-Go-Gentle/blob/main/.github/WJIcon.png" width="64px" /></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

# Preamble

-   [Apocalyptic Wonderland](#apocalyptic-wonderland)
-   [Preamble](#preamble)
-   [The Why](#the-why) (This segment is completely optional to read; it just details how I made the list)
-   [What is Wabbajack](#what-is-wabbajack)                                                                                                                
-   [Requirements](#requirements)                                                                                                                                  
    - [Specifications](#specifications)                                                                                                                           
    - [Steam/GOG Requirements](#steamgog-requirements)
    - [Site Requirements](#site-requirements)                                                                                                            
    - [Extra Requirements](#extra-requirements)                                                                                                                   
-   [Installation](#installation)                                                                                                                                  
    - [File Path Setup](#file-path-setup)
    - [Generating INI Files](#generating-ini-files)                                                                                                                
    - [Clean Installation (Steam)](#clean-installation-steam)                                                                                                     
    - [INI Folders (Steam)](#ini-folders-steam)                                                                                                                   
-   [Steam Config](#steam-config)                                                                                                                                  
    - [Reinstallation](#reinstallation)                                                                                                                           
      - [Steam Library](#steam-library)                                                                                                                            
      - [Setting the Game language to English](#setting-the-game-language-to-english)                                                                              
      - [Disabling Steam Overlay](#disabling-steam-overlay)                                                                                                        
-   [GOG Installation and Config](#gog-installation-and-config)                                                                                                    
    - [Clean Installation (GOG)](#clean-installation-gog)                                                                                                         
    - [INI Folders (GOG)](#ini-folders-gog)                                                                                                                       
-   [Using Wabbajack](#using-wabbajack)                                                                                                                            
    - [Preparations](#preparations)                                                                                                                               
      - [Disabling Base Address Randomization](#disabling-base-address-randomization)
      - [Creating Exclusions](#creating-exclusions)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
-   [Installing TTW](#installing-ttw)
-   [Manually Installed Mods](#manually-installed-mods)
    -  [Cyberware 2281](#cyberware-2281)
    -  [The Golden Archive](#the-golden-archive)                                                                                                                   
    -  [Stash Organizer](#stash-organizer)                                                                                                                         
    -  [FNV 4GB Patcher](#fnv-4gb-patcher)                                                                                                                         
-   [Post-Installation](#post-installation)
    - [Capping FPS](#capping-fps)
      - [RivaTuner Statistics Server (RTTS)](#rivatuner-statistics-server-rtss)                                                                                    
      - [Special K](#special-k)                          
-   [Q&A](#qa)                                                                                                                                                     
-   [Important Info](#important-info)
    - [Where to Ask for Support](#where-to-ask-for-support)                                                                                                        
    - [How to Keep Extra Mods After Updating](#how-to-keep-extra-mods-after-updating)
    - [How to Submit Bug Reports and/or Feature Requests](#how-to-submit-bug-reports-andor-feature-requests)                                                      
    - [Adding Extra Mods](#adding-extra-mods)                                                                                                                      
-   [Updating](#updating)
-   [Credits](#credits)                                                                                                                                          
                                                                                                                                             
# The Why

> [!note]
> **This segment is entirely optional to read. These are just the events leading up to the creation of Apocalyptic Wonderland.**

I was addicted to seeing New Vegas and TTW modding videos on YouTube. I loved creators such as [Mutant Mods](https://www.youtube.com/@Mutant_Mods/), [Mortyyyy](https://www.youtube.com/@Mortyyyy01) and [DarkPopulous](https://www.youtube.com/@Darkpopulous). I saw their modded setups and admired them. I thought to myself, "Can't I make a modlist that takes all the best parts from their load orders?" 

That is when I found [Wabbajack](https://www.wabbajack.org/). I was scrolling and found a [DroppedIceCream](https://www.youtube.com/@DroppedIceCreamMods) video about Viva New Vegas. I knew it was a New Vegas guide, and then he said the magic word "Wabbajack." I was interested. An automatic mod installer that didn't make me a mod pirate. That seemed impossible to believe, yet here I am now. I dug into the rabbit hole; this was just after I had made a [Reddit post](https://www.reddit.com/r/FalloutMods/comments/1bhxmp4/fnv_my_best_modlist_for_fallout_new_vegas/) detailing my best load order for New Vegas. This post is extremely outdated. I made it before I understood a lot of the stuff I understand today. You can see it, just for the sake of laughing at my horrible choices. (Please do not follow it).

Now, one Reddit user known as [xBlue69](https://www.reddit.com/user/xblue555x/) convinced me to try Wabbajack. I joined the Wabbajack [Discord server](https://discord.com/invite/wabbajack), and I was a moron. I barely understood anything. I spoke with JanuarySnow, Althro, Luca, TDarkShadow, and Reyqune (they are all amazing) for hours. I was the most ignorant person on the planet. 

I didn't know [Stock Game](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#stock-game), [Rootbuilder](https://wiki.wabbajack.org/modlist_author_documentation/Keeping%20the%20Game%20Folder%20clean.html#rootbuilder) and so many other things. They set me on the right path, and I continued. I eventually found Salamand3r's [New Vegas Visual Renewal](https://salamand3r.fail/new-vegas-visual-renewal) guide, which then led me to the [Wasteland Survival Guide](https://wastelandsurvivalguide.github.io/). This guide is the [Viva New Vegas](https://vivanewvegas.moddinglinked.com/index.html) of TTW modding. Amazing. I love it. I used it, and then I came back for the texture guide. After that, I began browsing [Additions](https://wastelandsurvivalguide.github.io/docs/additions), adding mods as I went. I then added [STARS](https://wastelandsurvivalguide.github.io/docs/stars), downloaded a LOT of extra mods, merged like 25 ESPs using [zEdit](https://github.com/z-edit/zedit/releases), and finally generated some LOD using [xLODGen](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-114-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/). That was the last piece of the puzzle. I was ready to make a list. Of course, I still had to setup this README and my [Discord server](https://discord.gg/ez3dsBub8Q) before I published it, so I had to wait a little longer. In the meantime, I made some patches using [xEdit](https://www.nexusmods.com/newvegas/mods/34703) by following [Biggie Boss'](https://www.youtube.com/@biggie_boss) guide on patching ESPs (love you, Biggie!).

This is it: the full story. Of course, I had like 14 different modding attempts that all failed, but we don't remember those.

# What is Wabbajack?

>[!Important]
>
>From here on out, you cannot skip any segments; they're all in chronological order.

Wabbajack is an automated mod list installer that works by scanning the [META files](https://wiki.wabbajack.org/modlist_author_documentation/Meta%20Files.html) of MO2 Downloads so that it can download the mods on the user's device without redistributing any assets of said mods. This is needed because in the world of Bethesda modding, no clear permissions have been set for mods, each mod can have radically different permissions. That's why things like modpacks, or modlists, as we call them, didn't come until later down the line.

# Requirements

### Specifications

> [!Important]
>
>**Though this list was designed with performance in mind, I cannot provide support for different specifications and setups. I do not know how to improve FPS on other devices. Do not ask me about it. You can, however, ask on the support server, but no matter what you have, you need either Windows 10 or Windows 11.**

My specs are the following:

- RTX 4090.
- Intel 13900K.
- 256GB of DDR5.
- TTW running on an SSD.

If you want to increase performance, please ask in the support channel, and I personally will not be able to help you.

### Steam/GOG Requirements

A legal copy of Fallout 3 with all DLCs from either [Steam](https://store.steampowered.com/app/22370/Fallout_3_Game_of_the_Year_Edition/) or [GOG](https://www.gog.com/en/game/fallout_3_game_of_the_year_edition).

A legal copy of Fallout: New Vegas with all DLCs from either [Steam](https://store.steampowered.com/sub/13435/) or [GOG](https://www.gog.com/en/game/fallout_new_vegas_ultimate_edition).

**(I cannot provide support for any other version, the Cut German version and the Epic Games version can be used provided you install [DepotDownloader](https://github.com/SteamRE/DepotDownloader) to get the international executable for the German version, and the [Epic Games Patcher](https://www.nexusmods.com/newvegas/mods/81281) for the Epic Games version, the PCR, Microsoft Store and Gamepass versions are completely unsupported)**

### Site Requirements

A [Nexus Mods](https://nexusmods.com) account (Premium is not necessary but recommended for automated downloads).

A [ModPub](https://mod.pub/) account.

### Extra Requirements

[Every Visual C++ Redistributable Package](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one).

[DirectX Runtime Libraries](https://www.microsoft.com/en-us/download/details.aspx?id=8109).

[.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-8.0.302-windows-x64-installer).

The latest driver versions for your GPU ([NVIDIA](https://www.nvidia.com/download/index.aspx), [Intel](https://www.intel.com/content/www/us/en/search.html#sort=relevancy&f:downloadtype=[Drivers]&f:@tabfilter=[Downloads]&f:@stm_10385_en=[Graphics]), [AMD](https://www.amd.com/en/support/download/drivers.html)).

# Installation

### File Path Setup

- Navigate to the `Root Directory` (`C:\`, `D:\`, etc).
- Create a folder named `Modding`, then open it.
- Create a folder named `Wabbajack`.
- Create another folder named `Apocalyptic Wonderland` then open it.
- Create another folder named `downloads`.

### Generating INI Files

- Launch Fallout: New Vegas from Steam/GOG.
- Click `OK` when prompted with `Detecting Video Hardware`.
- Close the launcher.
- Launch Fallout 3 from Steam/GOG.
- Click `OK` when prompted with `Detecting Video Hardware`.
- Close the launcher.

### Clean Installation (Steam)

**If you use GOG, then please skip to the [GOG Installation and Config](#gog-installation-and-config) section of the README.**

In order to ensure that your Fallout: New Vegas and Fallout 3 installations are pristine and vanilla, we are going to completely re-install the game. This is especially important if you have modded the game previously, as left-over files might interfere with your installation. If you never modded Fallout: New Vegas and Fallout 3 and/or never installed other Wabbajack lists, you may skip this step. However, I still recommend you verify the game files through Steam in that case.

-   Uninstall Fallout: New Vegas and Fallout 3 through Steam.
-   Navigate to your Steam directory.
-   If there is still a Fallout: New Vegas and Fallout 3 folder there, delete it.

### INI Folders (Steam)

More Fallout-related files are located inside the so-called `INI folder`, which needs to be cleaned out as well. It contains your save games as well as the game’s INI files and, if you modded Fallout: New Vegas before, NVSE plugin logs.

-   Navigate to the INI folder; this is found under Documents/My Games.
-   If you have an ongoing vanilla playthrough, back up the Saves folder.
-   Delete everything inside the Fallout: New Vegas and Fallout 3 folders.

# Steam Config

### Reinstallation

The reinstallation also serves the purpose of relocating the game files to a better directory. Using `UAC-protected folders` for the game or any modding tools has a risk of causing issues down the line. It is best to avoid those folders to begin with. Most Wabbajack list authors, myself included, will not provide support for people who disregard this warning and use UAC-protected folders anyway. Note that this does not include the `Steam client`. Additionally, Fallout: New Vegas and Mod Organizer 2 should be installed on the same hard drive. Ideally, that hard drive would be an SSD to reduce loading times and eliminate stuttering. 

### Steam Library

In order to prevent some confusion, I will refer to the Library in Steam as the `Game Library`. It is the second of four items in the top menu in the Steam client and contains a list of all your games. A `Steam Library`, on the other hand, is a folder on your hard drive into which Steam games are installed. Since we do not want to have files inside a `UAC-protected folder`, we should not install Fallout: New Vegas in the default directory. A new `Steam Library` is required.

### Setting the Game language to English

You must do this for Wabbajack to work. If your game was previously set to non-English, make sure to verify your files on Steam after fixing it. There is no support for non-English TTW.

Open the `Steam Properties` window, navigate to the `Language` tab, and select `English` from the dropdown menu.

### Disabling Steam Overlay

- Navigate to your Steam root folder (the same folder where your steam.exe is).
- Right click `GameOverlayRenderer.dll` and open properties.
- Open the `security tab` and click `edit`.
- Click the `Deny` option under `Read & Execute` for every user.
- Click `Apply`, then `Yes`.
- In the same folder, right click `SteamOverlayVulkanLayer.dll` and open `properties`.
- Open the `security tab` and click `edit`.
- Click the `Deny` option under `Read & Execute` for every user.
- Click `Apply`, then `Yes`.

# GOG Installation and Config

### Clean Installation (GOG)

Inside the game folders of both Fallout 3 and New Vegas, there will be a file known as `unins000`. Run it, and it will activate the uninstaller; it will completely uninstall the game, and then you have to reinstall it from GOG.

### INI Folders (GOG)

More Fallout-related files are located inside the so-called `INI folder`, which needs to be cleaned out as well. It contains your save games as well as the game’s INI files and, if you modded Fallout: New Vegas before, NVSE plugin logs.

-   Navigate to the INI folder; this is found under Documents/My Games.
-   If you have an ongoing vanilla playthrough, back up the Saves folder.
-   Delete everything inside the Fallout: New Vegas and Fallout 3 folders.

> [!Note]
>
>_This section is not verifiable; I have written it from word of mouth. If someone knows the rest of the steps that GOG users have to take, please DM me at StrawChannel95 on Discord._

# Using Wabbajack

### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the Wabbajack file path that you set earlier.

#### Disabling Base Address Randomization

- Open `Windows Security` from the `Start Menu`.
- Open `App & Browser Control` in the left sidebar.
- Open `Exploit Protection Settings` under `Exploit Protection`.
- Set `Force Randomization for Images (Mandatory ASLR`) to `Use Default (Off)`.

#### Creating Exclusions

- Open `Windows Security`.
- Open `Virus & Threat Protection`.
- Click `Manage Settings` under `Virus & Threat Protection Settings`.
- Scroll down and select `Add or Remove Exclusions` under `Exclusions`.
- Select the `Apocalyptic Wonderland folder`.
- Add another exclusion for the `Wabbajack Installation` location.
- This process will also need to be done for any third-party antivirus.

### Downloading and Installing

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the number of threads it will use at the start of the installation. To have the highest number of threads and, thus, the fastest speed, it is advised to have the working folder on an SSD. You can have the Apocalyptic Wonderland and Downloads folders on separate drives without issue, aside from being limited by the slowest drive during Wabbajack installation. Click the `Play` arrow. If you have a Nexus Premium account, all of your downloads will be automated. Without Premium, you will need to manually click the Download button for each mod. Installation will be automated, regardless of your account status.

-  Open Wabbajack.
-  Load the Modlist from Disk.
-  Set Apocalyptic Wonderland to install to the `Apocalyptic Wonderland install folder` and download to the `Apocalyptic Wonderland download folder`.
-  Click the Go/Begin button.
-  Wait for Wabbajack to finish.

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. If you do not see an installation failure warning, do not worry about it. If you feel like Wabbajack is stuck or a download is hanging, just restart Wabbajack; it will pick up from exactly where you left off. Please rerun Wabbajack at least twice and try to manually download the file from Nexus first before posting about a failed download. Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Steam Config](#steam-config) section; if you own it on GOG, go back to the [GOG Installation and Config](#gog-installation-and-config) section.

# Installing TTW

-   You then want to head over to [ModPub](https://mod.pub/) and download the [TTW 3.3.2 Installer](https://mod.pub/ttw/133-tale-of-two-wastelands).
-   Extract the downloaded archive to a folder of your choosing.
-   You then want to run the installer as Administrator and set the path to both Fallout 3 and New Vegas, you then want to set the installation folder as the empty mod called `[No Delete] Tale of Two Wastelands`. You can find it by heading to where you installed MO2, going to the `mods` file, and finally going to the file named `[No Delete] Tale of Two Wastelands`, you then want to double-click while hovering the file and you want to copy the file path at the top.
-   Then you wait for the installer; this will take more time if you have other processes running in the background. It is also CPU-bound, so if you have a good CPU, it will be faster. (This will approximately take between 45 minutes and 3 hours).

# Manually Installed Mods

### Cyberware 2281

-   [Cyberware 2281 and all patches](https://mod.pub/falloutnv/15-cyberware-2281). Go on ModPub and download the mods by pressing the `MO2 Download` button for the main Cyberware 2281 mod, the TTW 3.3 patch, and the B42 Quickthrow Patch. You can then open up MO2 and click on the mods on the right. You'll then want to name all 3 files with a `[No Delete]` before them, and then once you click on `OK`, then `Replace`.

### The Golden Archive

-   [The Golden Archive](https://mod.pub/falloutnv/122/files). Go on ModPub and download the mod by pressing the `MO2 Download` button. You will then find the file on the right; you want to name it `[No Delete] The Golden Archive`, and you then want to click on `OK` then `Replace`.

### Stash Organizer

-   [Stash Organizer](https://mod.pub/falloutnv/4-stash-organizer). Go on ModPub and download the mod by pressing the `MO2 Download` button. You will then find the file on the right; you want to name it `[No Delete] Stash Organizer`, and you then want to click on `OK` then `Replace`.

### FNV 4GB Patcher

-   [FNV 4GB Patcher](https://www.nexusmods.com/newvegas/mods/62552?tab=description). You want to press the `Manual Download` button. After it's done downloading, you want to extract the archive to where your Fallout: New Vegas is located (Put it in the normal game folder and do not put it in the data folder). After that, you want to run `FNVpatch.exe` as Adminstrator. It should say "FalloutNV Patched."

# Post-Installation

### Capping FPS

> [!Important]
> RTSS is the recommended option for AMD graphics card users. Special K lacks compatibility with the combination of AMD graphics cards and DXVK. NVIDIA graphics card users will have memory related crashes if following this section instead of the [Special K section](#special-k).
>
> Special K is the recommended option for NVIDIA graphics card users. RTSS is not able to configure flip and interop appropriately, which causes a large amount of memory related crashes. AMD graphics card users will not be able to launch the game if following this section instead of the following [RTSS section](#rivatuner-statistics-server-rtss).

#### RivaTuner Statistics Server (RTSS)

- Install and launch [RTTS](https://www.guru3d.com/download/rtss-rivatuner-statistics-server-download).
- Open the `System Tray` (the triangle pointing upwards on the taskbar) and click the `RTSS icon` (an image of a computer screen) to open it.
- Press the green `Add` button and select `FalloutNV.exe` from the `Root` folder.
- Set `Application Detection Level` to `Low`.
- Set `Framerate Limit` to `59.95`.
- Enter settings using the `Setup` button.
- Scroll down and enable `Passive Waiting`.
- Set `Framerate Limiter` to `Front Edge Sync`.
- Optionally enable `On-Screen Display Support` and use the `X,Y Coordinate Buttons` at the bottom to adjust On-Screen FPS display location.
- Minimize RTSS back to the System Tray.

#### Special K

- Navigate to the NVIDIA app settings and `turn off NVIDIA overlay`, as the overlay will cause a black screen if used alongside Special K.
- Download the [Special K](https://sk-data.special-k.info/SpecialK.7z) program.
- Extract the downloaded archive into your downloads folder.
- Open the SpecialK folder.
- Rename `SpecialK32.dll` to `dinput8.dll`.
- Move the newly renamed `dinput8.dll` into the `Root` folder.
- Download the [Viva New Vegas Preconfigured Settings Archive](https://performance.moddinglinked.com/files/sk.zip).
- Extract the newly downloaded `SK.zip` into the `Root` folder.
- Launch Old Old World.
- Select `Yes` when prompted to enable DXVK support/vulkan bridge, then relaunch the game.
- Press `Ctrl + Shift + Backspace` to enter the `Special K Control Panel`.
- Under the `Framerate Limiter`, click the `Enable Framerate Limit` checkbox.
- Right click the bar next to Framerate Limit (the one that specifies FPS and says `(Limit Engaged)`, not the graph).
- Select your monitors refresh rate.
- Click `Advanced` and select `Latent Sync (VSYNC -off-) mode`.
- Double Left Click on the bar and type in 59.995, and press `enter`.
- For instructions on configuring Latent Sync, enabling V-Sync or Variable Refresh Rate, please reference the [Special K section of Wall's Performance Guide](https://performance.moddinglinked.com/falloutnv.html#RecommendedLimiters), though this is beyond the scope of Apocalyptic Wonderland's configuration.

# Q&A
<details><summary>
Expand
</summary>

Q: Wabbajack tells me I'm missing a file from the game!

A: Verify the game through Steam, then run it through the launcher and exit. The game must be a non-PCR version on Steam with all of the DLC, and the language must be English.

Q: I have missing masters when I run the game! Help!

A: The list requires you to download and install TTW separately. Reread the [Installing TTW](#installing-ttw) step.

Q: Why are the DLCs so different?

A: I felt that the mods made the DLCs better and more enjoyable while still not taking away anything from the vanilla aesthetic.

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

A: You need to make sure YUPTTW is enabled in MO2 and directly underneath the main ESMs in the plugin load order, as shown in the instructions.

Q: I am crashing; what can I do to fix it?

A: Post your crashlog in the Apocalyptic Wonderland support channel on Discord.                                                                         

Q: Why are all of my downloads so slow and eventually failing?                                                                                                     

A: You failed to connect your Nexus account to your Wabbajack. Open the settings cogwheel in Wabbajack and log into your Nexus account.                            

Q: Is the list appropriate for a person who has never played Fallout before?                                                                                       

A: Yes. This list is appropriate for anyone who wants a robust, hardcore gaming experience.                                                                        

Q: How do I find Apocalyptic Wonderland's Keybinds?                                                                                                                         
A: Press K in the pause menu.                                                                                                                                      

Q: Why do I have to manually install TTW and Stash Organizer?                                                                                                      

A: Modpub does not allow automated Wabbajack downloading.                                                                                                          

Q: Can I keep my own modded setup if I play Old Old World?                                                                                                         

A: Yes. Apocalyptic Wonderland is entirely self-contained through the use of MO2 Profiles. As long as you have the appropriate Fallout installations (Fallout 3, Fallout New Vegas, and all DLCs), the installation will still work and will not interfere with your other modded setup as long as you run the any other profiles separately.             

Q: Doesn't Ragdolls cause crashes?                                                                                                                                 

A: No. The original version of Ragdolls did cause crashes. The replacement plugin available in Death Throes is **NOT** prone to crashes.                           

Q: Can I start in the Mojave Wasteland?                                                                                                                            

A: Yes. To start in the Mojave Wasteland, select "just a memory" when prompted, "Is this now, or just a memory?" immediately after leaving the vault.              

Q: Can I install Apocalyptic Wonderland with Vortex?                                                                                                                        
A: No. Wabbajack is inherently incompatible with Vortex.                                                                                                           

Q: I get no DLC messages. Are they installed correctly?

A: Yes, the list has a mod that delays the DLCs and does not spam you with the message boxes at the beginning of the game. Just explore the game normally, and you 
will stumble on them.

Q: My saves have disappeared!

A: The list uses profile-specific saving. They are located in the directory where you installed the list under "profiles," then "Old Old World".

Q: I can't ALT-TAB? It just crashes or freezes.

A: Without going too deep into technicalities, this is intentional when not using DXVK and Flip mode as outlined in the guide. Old Old World's default mode is DX9 
and Fullscreen, with improved RAM management from the mod NVTF. One of these RAM improvements makes ALT-TABing impossible in this mode.

Q: Is "{INSERT MOD NAME HERE}" compatible with the list?

A: Short answer. If you have to ask, then no. Long answer: If you know your way around xEdit and can see what I have done in regards to patching the list for 
consistency, then absolutely.
</details>

# Important Info

## Where to Ask for Support

Don't ask on the Wabbajack server, they cannot help you; they will tell you to head over and ask the modlist author (me).

Don't DM me or anyone else regarding the list, Ask in the support channels; more people see it, and it makes my life easier.

Please ask in my Discord server, here is the [link](https://discord.gg/ez3dsBub8Q) (there is also one in [The Why](#the-why) section and another one in the [Q&A](#qa) section).

## How to Keep Extra Mods After Updating

When updating, any additional mods you have installed on top of Apocalyptic Wonderland will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

## How to Submit Bug Reports and/or Feature Requests

Head over to [this](https://github.com/StrawChannel95/Old-Old-World/tree/main/.github/ISSUE_TEMPLATE) section of the Apocalyptic Wonderland Github and you'll find a template for both feature requests and bug reports, you can also just ask on Discord.

# Adding Extra Mods

>[!Tip]
>
> Adding extra mods is completely unsupported, however, if you wish to install mods on top of this list, these are some good resources to follow.

-   [Wabbajack Wiki](https://wiki.wabbajack.org/index.html)
-   [Viva New Vegas](https://vivanewvegas.moddinglinked.com/index.html)
-   [The Best of Times](https://thebestoftimes.moddinglinked.com/index.html)
-   [Wasteland Survival Guide](https://wastelandsurvivalguide.github.io/)
-   [New Vegas Visual Renewal](https://salamand3r.fail/new-vegas-visual-renewal)
-   [The Basics of xEdit](https://moddinglinked.com/xedit.html)
-   [The Method](https://moddinglinked.com/themethod.html)

# Updating

If Apocalyptic Wonderland receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

Apocalyptic Wonderland's updates are based on a [Semantic Versioning](https://en.wikipedia.org/wiki/Software_versioning) system.

Updating is like installing. You only have to make sure that you select the same path and tick the `overwrite existing Modlist` button.

Generally speaking: 
- Full x.0 (2.0, 3.0, etc) updates require a new game.  
- Major x.x (2.1, 2.2, etc) updates require a new game.  
- Minor x.x.x (2.1.1, 2.1.2) updates can be applied to an ongoing playthrough.

Once you know and understand the depths and meanings behind these resources, you can start modding the list. Or you can ignore my advice and have a broken game because you forgot to patch something—your choice.

# Credits
- The NVSE team for NVSE and xNVSE.
- The Tale of Two Wastelands team for TTW.
- lStewieAl for the amazing lStewieAl's Tweaks mod.
- Salamand3r for NVVR.
- Vish for Viva New Vegas.
- Biggie for his amazing guides.
- NMC for his awesome texture work.
- Hitman and Rockbiter for the best animation mods on Nexus.
- Someguy2000 for the best quest mods on the Nexus.
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
- The Uranium Fever team for providing some of their own custom patches. (Thanks Kam!)
- Everyone at Scenic Route for the idea to include user comments. (I will include them once the list has actually been played by people).
- Apoapse for founding Scenic Route Games and being the lead of Librum.
- Bethesda for the engine and Fallout 3.
- Obsidian for Fallout: New Vegas.
- RoyBatty for being the best New Vegas modder to ever live.
- Axonis for Vanilla UI Plus.
- Jazzisparis for JIP NVSE.
- Halgari for Wabbajack; without him, this list and countless others wouldn't be possible.
- All the other code contributors for helping Halgari.
- Every Wabbajack staff member.
- YOU for reading this.
- And so many others that I just couldn't list even if I tried. Don't forget to endorse these mod authors; they deserve it.

I wish you all a happy nuclear wasteland.
