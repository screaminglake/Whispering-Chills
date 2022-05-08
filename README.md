# Whispering Chills


# Preface

[Preview images](https://www.nexusmods.com/fallout4/mods/48593?tab=images)

[Trailer/video footage](https://youtu.be/Ux0z3Ul9R3g) 

[Support server](https://discord.gg/strraNQxEQ)

Whispering Chills is a horror experience unlike any other.  It is intended to be entirely standalone in that you don't need to enjoy or know very well how to play Fallout 4 to be able to enjoy it as a horror fan in general.  Perfect for anyone experiencing burnout in their other modded setups.  It is about as "lore-unfriendly" as you can get purely using the engine as a vessel to craft an entirely new experience through a unique combination of mods that enhance/rework its core mechanics and add new content that entirely change its core focus.  Unlike most other Bethesda games where the horror element feels tacked on at best even using mods, the amazing modding community around this game has afforded us the opportunity to overhaul the Fallout 4 experience into an entirely unique other experience.  The core premise revolves around an alternate vision of the Commonwealth where a door to the paranormal dimension has allowed for literal hell on earth to take over and has left very little remains in its wake.  Your ultimate goal and place in this hellscape is for you to decide.  

We've stripped away several trademarks of the base game to distinguish this as a standalone experience based in its own universe.  Almost all vanilla NPC’s have been replaced with terrifying monsters from several mods installed in the modlist.  All vanilla questlines have been replaced with more fitting, horror-based ones.  It involves a custom dynamic spawn system using SKK mods as the foundation, allowing us to breathe an unprecedented level of creature variety into the Commonwealth (including spawning GRIM creatures without having to activate the curse).  The entire soundscape from music and audio cues to ambient noises and creatures sounds have been reworked to fit the environment.  And this is just the beginning.  If you are looking for a truly unique and DIFFERENT playthrough for Fallout 4, this is it!

This modlist is adapted from the manual version of the guide that I have created and maintained over the past year and which has been enjoyed and tested by thousands, so expect a certain degree of established quality here already given that context.

[Whispering Chills manual guide](https://www.nexusmods.com/fallout4/mods/48593) 


My computer specs for reference:

CPU:  i7-9700k

GPU:  RTX 2070 8GB

Storage:  Samsung EVO 1TB SSD

RAM:  16GB DDR4

OS:  Windows 10

Resolution:  2560x1440

With this modlist, I sit above 60 FPS in every area that I can otherwise in vanilla.  Even though Fallout 4 is a 5 year old game, it can still be very intensive on CPU and GPU resources, especially when heavily modded.  Take this into account before starting to ensure your system is strong enough to handle everything being thrown at it with this setup.  Also take note of the fact that no matter what mods you use, Downtown Boston will always suffer heavy FPS drops due to poor optimization of the base game.  This occurs no matter how good your hardware is and how solid your modded setup is.  There will be performance options and a performance profile detailed later in the instructions on how to use for those on less powerful hardware.  Generally, this is not a very intensive setup when it comes to number of mods installed, visual fidelity, and overall resource loading and should run with the main profile without any adjustments just fine on most systems, but there options are there just in case.


# Before You Install

As with any modlist, it is recommended you start with a clean install.  Uninstall Fallout 4 through Steam if it's already installed (yes even if you already have a modded setup this is the safest approach) then **proceed to Documents/My Games/Fallout 4 in File Explorer and delete everything inside that folder**.  Then **navigate to wherever you have installed Fallout 4 (steam/steamapps/common/Fallout 4) and delete everything left inside that folder**.  Now you must install Fallout 4 in a non-Windows Protected folder (**NOT** within Program Files, Program Files x86, Documents, Desktop, or any other other protected folders on the OS/C Drive).  The default install location for Steam games is in a Windows-protected folder Program Files (x86) which we do NOT want as it can cause many issues with permissions and read/write access to your game files.  If you already have a Steam Library set outside this default location, you can simply install Fallout 4 there.  If you currently only have a Steam Library created with games being installed to the default Windows-protected folder on your C drive, please follow the steps below based on whether or not you have a separate hard drive from your OS drive.

**If you have another hard drive in addition to your OS drive:**

* Open Steam and click on Steam in the top left corner then click on Settings.  Go to the downloads tab listed on the left panel that opens and select the     Steam Library Folders option.  When the popup appears, click on the plus button to the right of any listed drives and then create a NEW FOLDER on any of the other drives (not your native C Drive where steam default installs to) and click select.  A new steam library folder will be created on your other drive in this new folder ([click here for reference image](https://imgur.com/KiuYDe2/)).

* Navigate to the Library section of Steam where all of your games are listed and click Fallout 4 then choose to Install Fallout 4 as per usual, but when prompted to choose an install location, specify the new SteamLibrary folder you just created on a separate hard drive instead of the default location on your OS drive and proceed to install as per usual.

**If you only have one hard drive for your computer (the OS drive) and your Steam games install to the default location in a Windows-protected folder:**

* Use [this tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to create a new Steam library in a non-protected location on the same drive as your current library.  By default, Steam only ﻿allows you to have one Steam library instance to install games to on a single drive so this is the only safe way to create a new library ﻿outside protected folders for those who only have a single hard drive.  After the new Steam library is created, install Fallout 4 from the Library section of Steam where all your games are listed and specify this new library folder as the install location.

In either case, **make sure you LAUNCH Fallout 4 through steam when installation is finished** to allow the game to set registry keys and create the initial game configuration ini's.  You should see a popup notifying you that the launcher is configuring your settings based on a preset that matches your hardware.  After clicking OK to the popup, launch the game to the main menu and exit.

Lastly, right-click on the listing for Fallout 4 in the Library tab of Steam and select Properties...  Under the opening General tab UNCHECK the box next to enabling Steam Overlay in-game.  Under the Updates tab set the first drop-down for update method from Automatic Updates to "Only update this game when I launch it" so that any potential game updates don't mess with your modded setup.

If you are not deciding to reinstall for this, be aware that any files which you have added directly to or edited within the Fallout 4 directory may interfere with the installation process.  For example, if you followed the manual version of this guide at one point and cleaned your DLC esm's in FO4Edit, you'll have to replace the esm's in the Fallout 4/Data folder with your vanilla backups or verify integrity of game files through Steam to restore them and clear out any other files you added directly to the game directory.  This Wabbajack install will include all you need.


## NVIDIA Profile Inspector

[NVIDIA Users Only to Improve game Performance] – If you do not have a NVIDIA graphics card, you will have to force vsync via your graphics settings or via ENB or High FPS Physics Fix if you notice screen tearing.  I realize this is not a traditional part of any modded setup, however it is something that I have always done in my modded setups to beneficial results and the expectation of stability predicates itself on using this profile at least in part.

Download the [nvidiaProfileInspector.zip](https://github.com/Orbmu2k/nvidiaProfileInspector/releases/tag/2.3.0.12) from the Latest Release 2.3.0.12 section. 

Using any archive extraction software such as Winrar or 7-zip, extract the nvidiaProfileInspector.zip archive anywhere.

Next, download the **FIRST** file under the last section of the Files tab for the BRB guide (Miscellaneous Files) - [NVIDIA Inspector Profile - FO4](https://www.nexusmods.com/fallout4/mods/23556?tab=files).  

Using 7-Zip, extract the 1. Nvidia Inspector Profile - FO4-23556-1-0-1559298967 archive. Double click on the extracted 1. Nvidia Inspector Profile - FO4-23556-1-0-1559298967 folder and right click on Fallout 4 Nvidia Inspector.nip file and select Copy. Now go back to where you extracted the FO4 Nvidia Profile Inspector archive, double click on FO4 Nvidia Profile Inspector folder to open it, then right click on an unused space and select Paste (Copy and Replace – if asked).

Now that you have the FO4 Nvidia Profile Inspector folder open, double click on the nvidiaProfileInspector.exe file. In the application, on the Profiles Search Bar in the top left corner, type and select Fallout 4. Between the Icons line on the Middle Top click on the icon with a green arrow pointing down, then select the Import Profile(s) option and find the inspector profile you downloaded from the BRB guide page ([reference image](https://imgur.com/hPCu1JG)). 

Now if in the Green Bar on top of the Nvidia Inspector window you see the f4se_loader.exe (as shown in the previous reference image) you can click the big green Apply Changes button in the top right corner and close the program. If it's not there, click on the Middle Top icon with a little green plus and find the f4se_launcher.exe file that should be in your fallout 4 main folder, then click Apply Changes in the top right corner and close the program.


Finally, before installing Whispering Chills, **run this AIO installer** for all versions of Visual Studio C++ to ensure Buffout and all other utilities run as intended:  https://github.com/abbodi1406/vcredist/releases (download the zip file for the latest listed release and then run the exe within the zip file and restart your computer when finished)

# Installing the Modlist

Download Wabbajack from the home page (blue download button) https://www.wabbajack.org/#/

Place Wabbjack.exe in a new root folder on one of your drives (e.g. E:/Wabbajack).  Run this exe and then once Wabbajack is fully installed select the big Browse Modlists button.  Search for Whispering Chills among the offerings here.  You can filter by Fallout 4 at the top to help your search.  Then click the download button for the Whispering Chills listing.  You’ll then have to specify 3 paths for install.

Target Modlist:  Should automatically be specified after selecting this in the UI.

Installation Location:  The location where this modlist will install to.  Create a new root folder ideally on the same drive as where you have Fallout 4 and Wabbajack installed and path to this folder here (e.g.  E:/Whispering Chills)

Download Location:  Will default to a Downloads subfolder within your installation location path.  It is fine to leave this as is unless you want the downloaded archives to go to another folder/drive where you have more space which you can specify here.

Avoid using Windows-Protected directories for all of the above (Program Files, Desktop, etc.).

Click the Play button and if you are a Nexus Premium user it will all automatically go through everything for you.  Otherwise you will have to click through and download for each mod. 

# After Installing the Modlist

Once everything is finished Wabbjack will turn green and say Installation Complete.  If you have any issues installing please ping me in the #wc-support channel on our [Discord Server](https://discord.gg/strraNQxEQ) and I will respond ASAP!  

Now go to the folder where you installed this modlist to and open the folder within called **Game Folder Files**.  Copy ALL of the contents within it to your game directory (where the game is installed; i.e. steamapps/common/Fallout 4).  Make sure you copy all the contents WITHIN this folder to the ROOT of where the game is installed (where the game’s executable is) and **not the Game Folder Files folder itself**!

To actually play Whispering Chills, launch ModOrganizer.exe from within the installation directory for this modlist.  It should default to F4SE as the executable in the top-right corner of MO2.  **Make sure the listed profile is Whispering Chills - Main Profile!**  Click the Run button to launch Whispering Chills!

Please note that this setup defaults to 1440p resolution.  If you only have a 1080p monitor, open MO2’s INI editor and switch the isizeH and isizeW values to match those of your monitor under the [Display] section of the fallout4prefs.ini tab ([reference image](https://imgur.com/f64WmSQ)).




# Updates 

Whenever the Wabbajack version of Whispering Chills updates, it is to be assumed that the update will require a new save/playthrough.  Whispering Chills is what I would consider “feature complete” in that only very minor things are likely to change with it in the months ahead following over a year of development time to get it to this point.  When an update is pushed, feel free to carry on with things as they are currently with your current version.  It is recommended you NOT update this modlist given that it WILL delete any mods I’ve decided to remove from the modlist (which happens often) thereby breaking your current playthrough most likely AND it will remove all mods you added to the build yourself including any weapon mods.  

If a version I push forth is NECESSARY in terms of updating due to some issue in the previous release that the latest release fixes I will indicate this in the release notes/changelog and will then recommend you all update.  You can protect any additional mods you’ve installed by renaming them in the left pane of MO2 to include this [NoDelete] tag at the beginning (e.g. [NoDelete] H&K MP5).  Updating is the same process as installing.  Open Wabbajack, Browse Modlists, select Whispering Chills and specify the exact same paths as where you installed this to and **be sure to check the overwrite existing modlist button.**


# Vitally Important Notes
## You must do everything and carefully read through what is written below or you will not have a very good experience at all!


## Holotapes

After exiting the vault, DO NOT MOVE!  Configure the following holotape settings as shown below by opening each holotape listed from the Misc tab of your pip-boy.  SKK Feral Nights, Replace & Respawn Manager, and Random Encounter Manager should be enabled and configured as shown before Fallout 4-76 Open World.  It is recommended you open this page and read through this on a separate device so you can configure settings while the game is open on your computer.  Do not move from where you exited the vault until you have done everything as outlined below including Holotape/MCM configuration and restarting the game!!:

#### SKK Feral Nights Holotape

You must first enable this mod by opening the holotape for it under the Misc tab.  Each option is up to your preference, however **I recommend disabling the spawn in interiors option** as it gets to be too overwhelming in my opinion.  When you are done setting options you must click Submit Changes at the bottom to fully activate the mod.

#### SKK Random Encounter Manager Holotape

Enable this mod by activating it from its holotape under the Misc tab.  You must set the line that reads Spawn Only Ferals from OFF to ON otherwise this mod will spawn in humans and other entities we don't want ([see reference image](https://imgur.com/B36HskX)).  Every other option is up to your preference.  You can leave everything at default if you want, but it is recommended you set Spawn Cooldown to more than 1 hour or lower the Spawn Chance percentage value unless you want very frequent random encounters. 

#### SKK Actor Replace & Respawn Manager Holotape

Enable this mod by activating it from its holotape under the Misc tab in the Pipboy.  Now very carefully follow the steps below to correctly configure the mod to replace vanilla actors with custom actors from mods installed in the guide.

1.  Activate the mod with the option that appears when you open the holotape.  Then set everything in the initial menu as shown in [this image](https://imgur.com/dqedtrh) and click submit changes at the bottom.

2.  Click the actor keywords menu listed at the bottom after submitting changes and set it exactly as shown in [this image](https://imgur.com/2l2iNjs) (the only change you need to make is to click on the last line in this menu for custom keyword files so it shows it as SELECTED) and then submit changes

3.  Lastly go to the replacement actors menu and scroll to the bottom to change the custom actor file line to ENABLED as shown in [this image](https://imgur.com/ZLf9BHk) and then submit changes.  You can now close the holotape.

### Fallout 4-76 Open World Holotape

Tweak all settings in this holotape [exactly as shown in this image](https://imgur.com/iZSxlSW) .  Setting everything exactly as shown here is vitally important.  You will have to click on the top replace humans with option several times to reach the CUSTOM option.  All other options in the holotape not shown in this image are entirely up to your preferences.  When finished click ENABLE Fallout 4-76 Open World [GO] at the bottom.  After you click Enable Fallout 4-76 Open World in the holotape, you will see a text popup that says "Fallout 4-76 is Preparing the Open World" in the top left corner.  This will continue to appear every few seconds until it is finished (typically takes 2-3 minutes).  Do not move while you are waiting and instead proceed to configure the settings below while you wait.  When it finishes you will see a new text popup appear that says Fallout 4-76 Open World is Ready ([reference image](https://imgur.com/a/8N0spus)).

#### Whispering Hills Holotape

Whispering Hills has a holotape where you can configure settings related to the Otherworld.  You can either craft it at a chemistry station or the Universal Workbench or open console (~ tilde key) and type help whispering 4 note and then player.additem <item ID> (using the 8 digit ID returned from the help command) to spawn it via console and have it appear in the Misc tab of your pip-boy ([see reference image](https://imgur.com/pDzUGT2)).  The otherworld is when the Hell Dimension temporarily opens and waves of creatures will attack you in complete darkness.  The only way to escape is to hide inside a building and sleep until it (hopefully) goes away or kill each wave of the attacking horde.  You can increase/decrease the frequency of this event as well as the number of spawned NPC's per wave if you feel the default settings are too intense or not intense enough.  I would recommend you not mess with anything under the tabs not related to the Otherworld as this may affect visuals or settings in ways that were not intended or optimized for the provided ENB/visual setup.

## MCM Configuration

While you wait for Fallout 4-76 Open World to finish running, open the Mod Configuration Menu (MCM) by pausing and clicking the Mod Config option at the top.  Be sure you have configured your holotapes and set up everything else you need to be ready to play because after you apply this preset FallSouls will go into effect and the game will no longer pause via the pause menu or pip-boy as it does traditionally.  Certain things like opening console (~) and message boxes will still pause the game but most traditional means of pausing will no longer work.

After opening the MCM, open the top MCM Settings Manager listing and you will see a listing in the right pane under the Presets section titled WC MCM Settings with an option next to it to apply which you should click now ([see reference image](https://imgur.com/Z1jASPs)).  You will have to disconnect your controller briefly and click the Apply button (if using one).  Click yes on the prompt to apply the preset then reload the MCM when prompted on the left and now everything will go into effect!  You can change any MCM settings per mod to your liking afterwards here but everything has already been set to provide the ideal, intended experience.

**After you see the message that Fallout 4-76 Open World is ready, you must save and then fully exit the game, relaunch, and reload that save before starting to play.**  This is to get everything set in working order and properly initialized before you really start to play.

## ENB

Whispering Chills includes its own ENB preset that you placed in your game directory from the Game Folder Files folder after installing this modlist.  If anything isn't to your liking visually, please check out my [How to Configure ENB Presets Tutorial](https://www.youtube.com/watch?v=n67F7oYvN8c) to learn how to configure any preset to your preferences.

Important Note:  This preset will lock your FPS to 60 max by default.  This is intended as the game runs into issues running above 60 FPS even with High FPS Physics Fix.  If you want to disable this, open the enblocal.ini in your game's root folderand change the line EnableFPSLimit= under the [Limiter] section from true to false. 

In order for this preset to look as intended for you and for the game to look as visually striking as possible, I highly recommend your calibrate your monitor both through the NVIDIA/AMD Control Panel (right-click Desktop and the option should appear, then for NVIDIA in the left side panel click Adjust desktop color settings under the Display header, and I'm not familiar with how to do this for AMD) and through Windows display calibration ([reference image](https://imgur.com/a/BYf4BC2); search for Calibrate Display Color in your Windows search bar or Windows settings panel).

If you want to use any other ENB preset for other modded setups you’re running, you’ll have to delete all files and folders starting with enb in your game directory before placing files from another preset.  Just copy the enbseries folder, enbseries.ini, and enblocal.ini from the Game Folder Files folder back to your game directory whenever you’re playing Whispering Chills.  There is also an alternative option that offers a more cinematic, immersive approach to this preset but is slightly more FPS intensive available on the [Whispering Chills guide page](https://www.nexusmods.com/fallout4/mods/48593?tab=files) under Optional Files titled 03. Whispering Chills Alternate Cinematic ENB Preset.  If you wish to try this version instead just for fun, simply delete the enbseries folder, enbseries.ini and enblocal.ini already in your game directory and extract the contents of the Alternate Cinematic ENB Preset to your game directory.  Easy as that!

If you are using the alternate cinematic ENB preset and want to disable any of the camera effects (vignette, grain, or letterbox/black bars at top and bottom), press the END key on your keyboard to open the ENB GUI, then click the plus icon to expand the ENBEFFECTPOSTPASS.FX menu in the right pane and click the check mark to uncheck the option next to Enable Grain, Enable Vignette or Enable Letterbox Bars ([reference image](https://imgur.com/W4kcJq9); apologies for low quality photo as it's from the New Cinematic Wasteland preset page just to use as an example because my screenshot wasn't capturing the ENB GUI).

## Performance Tips

This is not a very intensive setup and should be able to run above 60 FPS on most modern hardware.  My hardware is listed at the top of this readme for which I am able to maintain a constant 60+ FPS at almost all times without any distracting FPS drops or extended stutters.  If you are on older hardware (the kind that struggles to run any modded setup or even the game in vanilla) there is a performance profile available for you to try.  Click the Profiles drop-down in MO2 and change it to the Whispering Chills - Performance Profile.  Functionally, this profile is identical to the main profile just with some added tweaks and optimizations based around using the game’s “medium” profile.  It won’t look all that different visually but should perform much more smoothly for those struggling to maintain above 60 FPS.

General tips for saving performance on EITHER profile:

* In the INI editor, set fshadowdistance= and fdirshadowdistance= to 5000 for both (this will already be set in the performance profile so more meant for the main profile).  Shadow draw distance will be reduced, but not in a significantly noticeable way given the vision-obscuring fog

* In the ENB GUI, under the Effects tab on the left, click the checkmark next to Enable SSAO so that it is unchecked and thereby disabled.  The lack of AO is hardly noticeable in this setup, and it drains a lot of FPS having it on.

* Simply disable the ENB preset altogether while you play by pressing the scroll lock key on your keyboard.  More meant as a last resort as you will not receive the intended visual experience but FPS cap and other fixes from ENBseries will remain intact.

* Set the game resolution to 1080p instead of the default 1440p.  Open MO2’s INI editor and switch the isizeH and isizeW values to 1920 and 1080 respectively under the [Display] section of the fallout4prefs.ini tab ([reference image](https://imgur.com/f64WmSQ)).

## Buffout and Crash Logs

If at any time you crash while playing this setup, a crash log will be produced by Buffout in your Documents\My Games\Fallout4\F4SE folder and will be named something along the lines of crash-2020-12-04-23-32-30.log.  Please share these with me in #unofficial-modlist-support **(update to support channel if approved as official)** and I will attempt to troubleshoot the cause.  I haven’t come across any repeatable, avoidable crashes yet in the latest version of this modlist!

## Adding mods to the modlist (weapons)

As with the rest of the Wabbajack community, I’m generally against supporting the addition of mods to this modlist.  Please launch and set up everything exactly as instructed and verify everything is working by testing for an hour or two BEFORE you start adding your own mods.  Otherwise it is impossible to determine where your issues are stemming from.  With this setup, I will only provide support for the addition of mods to the extent of very MINOR QoL additions or weapon/equipment mods.  I left the Equipment/Weapons section of the left pane of MO2 intentionally rather empty because I don’t want to dictate how you want this modlist to play out.  If you are going for more pure survival horror, you might go with more conservative and less overpowered weapons and equipment.  If you are roleplaying as a member of Umbrella Corps dropped in with elite tactical equipment to wipe out the demon spawns that have inhabited the Commonwealth by any means necessary, then who am I to stop you from doing that?  

Any weapon/equipment mods you install should be placed within the Equipment-Weapons section in the left pane of MO2 for your own organizational purposes, and the plugins for them should be placed after the plugins for the existing equipment mods installed with the modlist (i.e. after Tactical Flashlights - Settings.esp and before _Balance_.esp in the right pane Plugins tab of MO2).  Make sure you do properly sort the plugins for any added weapons/equipments further up in the load order and don’t just leave them at the bottom.  

Quick Modification Weapon is a mod installed with the modlist which allows you to swap out weapon modifications freely on the fly.  It is such a neat feature with an awesome UI design so I included it in the modlist, but it is only the framework.  You need to install weapon mods that are compatible with it in order to use it.  Check out [the description page for QMW](https://www.nexusmods.com/fallout4/mods/44985) to get a full listing of weapon mods you can install that will be compatible with QMW.  After installing these weapon mods, press the QMW hotkey (set to G by default, but you can change this to any hotkey in its MCM menu) in-game while having one of the QMW-compatible weapons equipped and the QMW menu will appear.

For whatever mods you install over this modlist, you do so at your own risk/discretion as my support for additions will be limited and predicated on you ensuring the core modlist itself is already functional.  And I will expect you to read the description for any mods you add and ensure that you are using xEdit to determine if the mods you are adding introduce any conflicts to the modlist that must be resolved by shifting the load order or creating patches (see [this video](https://youtu.be/bEx_GcKz-BA) for details on xEdit conflict resolution).

## ECO Workbench Patcher

Equipment and Crafting Overhaul (ECO) otherwise known as the modern day alternative to AWKCR/AE includes a convenient universal workbench which can be picked up right next to the vault after you exit (situated between two shipping containers just beside the vault entrance).  After picking up the workbench, you can place it down anywhere by dropping it from your inventory and then interact with it to craft any item you wish without having to stop at an official settlement workbench.  In order to have any weapons or items added by mods you’ve installed listed in this workbench, you must create your own workbench patch.

Select ECO_WorkbenchPatcher as your executable in MO2 and click the Run button to start it ([see reference image](https://imgur.com/7Tga3No))!  A command prompt window will appear asking if you'd like to run the patcher.  Simply enter the letter Y and press enter.

When FO4Edit opens, allow it to load all plugins by simply clicking ok on the module selection popup that appears.  Once all plugins are finished loading a popup will appear asking to select options for ECO Workbench Patcher.  Leave everything checked and click the New Patch button ([see reference image](https://imgur.com/hfbOUrV)).  

In the next plugin selection window **you must uncheck the plugin for Kelly Macabre!**  If you don't do this, **you won't be able to complete the quest unless you have the universal workbench on you**.  If you have the universal workbench on you, drop it down and go to Utility Station --> Explosives --> Timed Explosive and craft it with the supplies collected as part of the quest.  If you DON'T have the universal workbench and you forgot to uncheck Kelly Macabre when running this workbench patcher, you will need to spawn the Universal Workbench into your inventory using console commands (help universal 4 misc and player.additem XXXXXXX based on the MISC item ID it returns; it will be added to the Misc tab of your inventory). 

**After unchecking Kelly Macabre,** click ok which will add all other plugins as masters to the patch.  Name the patch something appropriate like "ECO Workbench Patch" and click ok.  Then click ok again and the script will start running!  It should be done in under a minute.  Once a popup appears indicating the script has finished running you can click ok once more and close this FO4Edit window entirely. 

Now back in MO2, your newly created plugin will appear at the bottom of your load order in the Plugins tab in the right pane.  Be sure to check it on, and you'll be good to go ([see reference image](https://imgur.com/YX1sMxc))!  You can leave this patch plugin last in your load order.  In-game, you should now be able to craft any items/weapons/equipment added to the game via mods within the universal workbench.

## Nate’s Footlocker

This modlist includes a custom variant of the mod Nate’s Footlocker, now reworked to essentially be a starting supply cache that should contain everything you need to get started on your journey.  Be selective in what you grab given the carry weight of everything and remember that shipments of junk items can be stored in settlement workbenches for use in constructing items.  The footlocker can be found in the backyard of the player home (where Codsworth will be roaming in front of) along the far back fence line buried underground.  It can be difficult to locate, but just keep tracing your cursor along the back fenceline and eventually a prompt to loot the footlocker should appear with a barely visible sliver of the container surfacing above ground.

## Photo Mode

This modlist includes the Photo Mode mod.  To use photo mode, pause the game and select the Photo Mode option.  The game will then freeze, allowing you to perfectly frame a shot of an iconic moment for your playthrough.  Please feel free to share these with me and I will include them in the Nexus guide’s gallery and a special gallery to be included with this modlist when it (hopefully) goes official!

## Final Notes

-Avoid Concord at all costs!  Preston can't save you there and you certainly won't be saving him.

-Find shelter at night and get some rest.  Exploring at night is a death sentence only made more certain if you happen to receive an otherworld event while exploring outdoors at night.

-Whispering Chills is a very difficult setup.  You will have to avoid many combat encounters and sneak your away around early on.  If the early game grind feels too difficult due to lack of humans to loot and lack of quest-based XP boosts, there are a couple helpful commands you can enter into the console (~) in-game to assist you.  Player.setlevel x where x is the level you wish to be set to can be used to raise your level along with gaining all the corresponding perk points.  CGF "Game.AddPerkPoints" x (include the quotes) where x is the number of perk points you wish to add can be used to simply add perk points to use in the level up menu without actually levelling up your character.  You can also install the [Cheat Terminal](https://www.nexusmods.com/fallout4/mods/13285?tab=files) mod and place it anywhere in your load order to make for a far less difficult experience where you have the ability to adjust any aspect of the game or spawn in items freely.  Bear in mind the higher you set your level, the more difficult things will become as higher level enemies will spawn per our dynamic custom spawn system.

-FallSouls MAY break certain quests from tracking in the Data tab of the Pip-Boy (never experienced this myself).  This, however, works in my favored preference as I encourage open exploration and coming across objectives naturally.

















  
  ## Texture Overhauls (OPTIONAL)

Before starting this section, please note that it is entirely OPTIONAL and can be done at any time.  This modlist is not designed for beauty and you honestly won’t really notice much of a difference with or without retextures in this setup given the drab, desaturated color palette and visual style.  This is my preferred method of foundational texture overhaul just to offer SOMETHING, but it may not fit everyone's tastes or run suitably on everyone's hardware so proceed at your own discretion.  
  
Luxor's work overhauls textures across the entire game and uses the BRB texture process methods to repack the textures so that they can overwrite the vanilla .ba2 texture archives.  This innovative approach from the BRB guide is truly the golden standard of retexturing Fallout 4 because it does it in a way that packs the textures from several high-quality texture mods into your game's original .ba2 archives where all base game textures are stored.  Using this overhaul will retexture nearly every object in the game with a higher-quality equivalent, and by baking these textures into your .ba2's you will experience little to no performance loss as compared to installing them loose as mods individually.  Best of all, you can install all of your own texture mods over these texture packs as you please because they are now treated as the original base game .ba2's and allow for any texture mods you install to overwrite what is present in your base game texture archives without conflicts. When it comes to textures in Fallout 4, Luxor's HD overhaul should be all you need for a solid base.

Please note that the download size of all 15 textures archives from the HD overhaul is around 48 GB in total, so you will need to download them to a drive that can store that much data.  This may seem like a lot, however that's only about 30 GB more than the vanilla texture archives and very appropriate when compared to how much space would be taken up by installing/downloading hundreds of separate texture mods instead.

Manually download all 15 main file archives from Luxor's Fallout 4 HD Overhaul.  Extract the ba2 files within each anywhere on your computer and then compress all 15 of these into a SINGLE zipped file titled Fallout 4 HD Overhaul or something fitting (this may take a while to compress depending on your disk drive speed).  Then install this archive in MO2 and place it at the very TOP of the left pane just below the cleaned ESM’s.  To manually install a mod archive click on the CD icon in the top-left corner of MO2 and select the downloaded archive (reference image).  The installation process likewise may take a long time to complete.  Be patient.
  
  # Questions/Comments/Concerns?
  
Ping me in the #wc-support channel in our [Discord Server](https://discord.gg/strraNQxEQ).  You must select the Whispering Chills role in #welcome and then click [this link](https://discord.com/channels/972218144569557062/972224969499111434/972929931032014969) to be redirected to the support channel.
  
  # Changelog
  See [changelog.md](https://github.com/screaminglake/Whispering-Chills/blob/main/changelog.md)

