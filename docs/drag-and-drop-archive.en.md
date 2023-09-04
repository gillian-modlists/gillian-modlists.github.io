title: Drag-and-Drop Archive
description: A complete ready-to-play drag-and-drop archive for your desired GTA IV version

# Drag-and-Drop Archive { data-search-exclude }
If you don't want to manually mod your game, you can choose an archive depending on the version you want - be it 1.2.0.59 or 1.0.8.0(a downgrader is included if you're using the [:material-steam:Steam](https://store.steampowered.com/app/12210/) or [Rockstar Games Launcher](https://store.rockstargames.com/game/buy-grand-theft-auto-iv) version). You can compare the modlist between the versions [below](#modlist) - 1.0.8.0 has a lot more notable improvements, keep that in mind.

### Notes { data-search-exclude }
!!! info ""
	1. 1.2.0.59 is the Complete Edition, also known as the latest [:material-steam:Steam](https://store.steampowered.com/app/12210/) or [Rockstar Games Launcher](https://store.rockstargames.com/game/buy-grand-theft-auto-iv) version. It removes support for multiplayer and Games for Windows - LIVE, while adding the Rockstar Games Launcher (and it's DRM) and the Social Club overlay (with it's achievements). ==The amount of supported mods is also much more limited in this version - most mods are built for 1.0.8.0 and 1.0.7.0==.
	2. 1.0.8.0 is the latest retail patch, with [ZolikaPatch](essential-modding/zolikapatch.md) support and a lot more notable mods. However, this drag-and-drop archive does NOT include any support for Games for Windows - LIVE whatsoever. See the [downgrading](downgrading.md) and [multiplayer](multiplayer.md) sections instead. ==This version is better for mod compatibility==.

!!! warning ""
	* I can't update the archive too frequently myself - check out the pages to see if the mods, especially the ones ontop, got any updates.
	* Make sure you follow the [prerequisites](index.md) (except for required space).
	* Make sure latest [drivers](../optimization/#drivers) are installed.
	* Make sure the game folder is a completely clean, fresh installation with no leftovers (:material-steam:Steam does not remove leftovers).
	* It is recommended that you start the game with a new save file after installing the archive, but you can continue to play on existing save files - you will just encounter minor issues (such as secondary objects being where they shouldn't be).

!!! warning "Performance"
	**This archive does NOT provide highest possible performance - the goal is first and foremost to provide the best vanilla-faithful experience. If you want the best performance - mod the game manually. The performance, in most cases, is still perfectly acceptable and most people shouldn't mind the slight drop in performance.**

## Installation { data-search-exclude }

=== "1.0.8.0"
	[:material-download-circle: Download](https://drive.google.com/file/d/1O1qD8ocbJ_fnERTvvVzyw6_bsw-k_evo/view){ .md-button .md-button--primary }  Last updated: **[28.08.2023](#changelog)**
	
	Download the archive and then simply extract the contents into your game folder (:material-folder:==GTAIV==, not :material-folder:==Grand Theft Auto IV==). ==After installation, go through [additional setup](additional-setup.md) (or use the [automatic setup utility](../optimization/#setup-utility)) and check [additional mods](#additional-mods)==.
	!!! warning
		The archive must be installed on top of a clean, unmodded [:material-steam:Steam](https://store.steampowered.com/app/12210/) or [Rockstar Games Launcher](https://store.rockstargames.com/game/buy-grand-theft-auto-iv) Complete Edition installation. 
		
		If you are using the [Rockstar Games Launcher](https://store.rockstargames.com/game/buy-grand-theft-auto-iv) version, do not start the game from the launcher itself, use :material-file:`PlayGTAIV.exe` instead - otherwise the game files will be replaced.

		If using Linux, add `WINEDLLOVERRIDES="xlive=n,b" %command%` to launch options.
		
		Other installation methods are not supported.
		
		In addition, I will not support any additional modifications to the files other than the instructions already listed.
	???+ info "Updating"
		If you're updating after installing the archive instead, delete :material-folder:==update== and :material-folder:==modloader== from the game folder first.
	??? warning "If the game does not start"
		Try to install :material-file-download:`vcredist_x86.exe` that's in your game folder.

		Disable your antivirus or add the GTA IV folder to exceptions. Extract :material-file:`ZolikaPatch.asi` again after doing so.

		Alternatively, your PC may not support DXVK - remove :fontawesome-solid-gears:`d3d9.dll` from the game folder or try other versions from [additional mods](#additional-mods).

		See [troubleshooting](troubleshooting.md).
	??? warning "My game is behaving strangely | My game is crashing randomly"
		Disable mods one by one to see the culprit by editing :material-file-edit:`modloader.ini` in :material-folder:==modloader== or deleting mods in :material-folder:==update==.

		See [troubleshooting](troubleshooting.md).
=== "1.2.0.59"
	[:material-download-circle: Download](https://drive.google.com/file/d/1eJ4cbVhJ4tnTGJByh_Lf4eS5SS2ShmHO/view){ .md-button .md-button--primary }  Last updated: **[28.08.2023](#changelog)**

	Download the archive and then simply extract the contents into your game folder (:material-folder:==GTAIV==, not :material-folder:==Grand Theft Auto IV==). ==After installation, go through [additional setup](additional-setup.md) (or use the [automatic setup utility](../optimization/#setup-utility)) and check [additional mods](#additional-mods)==.
	!!! warning
		The archive must be installed on top of a clean, unmodded [:material-steam:Steam](https://store.steampowered.com/app/12210/) or [Rockstar Games Launcher](https://store.rockstargames.com/game/buy-grand-theft-auto-iv) Complete Edition installation.

		If using Linux, add `WINEDLLOVERRIDES="dinput8=n,b" %command%` to launch options.
		
		Other installation methods are not supported.
		
		In addition, I will not support any additional modifications to the files other than the instructions already listed.
	???+ info "Updating"
		If you're updating after installing the archive instead, delete :material-folder:==update== from the game folder first.
	??? warning "If the game does not start"
		Your PC may not support DXVK - remove :fontawesome-solid-gears:`d3d9.dll` from the game folder or try other versions from [additional mods](#additional-mods).

		See [troubleshooting](troubleshooting.md)
	??? warning "My game is behaving strangely | My game is crashing randomly"
		Disable mods one by one to see the culprit by deleting mods in :material-folder:==update==. 
		
		See [troubleshooting](troubleshooting.md).

## Modlist { data-search-exclude }
=== "1.0.8.0"
	| Mod name | Details |
	| :------: | :-----: |
	| [Downgrader~v22~ by Zolika1351](https://zolika1351.pages.dev/mods/ivpatch/downgrading)| A simple drag&drop downgrade to 1.0.8.0 with Ultimate ASI Loader, ZolikaPatch, SteamAchievements and IV Tweaker included. |
	| [Radio Downgrader by Tomasak and others](http://downgraders.rockstarvision.com/)| A simple-to-perform radio downgrade.<br>Addon used: [Restored original TBoGT Menu Vocals](https://www.nexusmods.com/gta4/mods/234?tab=files)</br> |
	| [ZolikaPatch IV~7.62~ by Zolika1351](https://zolika1351.pages.dev/mods/ivpatch)| First main mod in the pack: adds a lot of fixes and improvements - and the game won't boot without it. |
	| [IV Tweaker~2.35~ by Zolika1351](https://zolika1351.pages.dev/mods/ivpatch)| Main modloader in the pack, also allows to increase limits for other mods. |
	| [Steam Achievements~v2~ by Zolika1351](https://gtaforums.com/topic/957432-steam-achievements-for-1070-1080/)| Allows you to get :material-steam:Steam achievements on older patches. |
	| [FusionFix~1.80~ by ThirteenAG, Tomasak and others](https://github.com/ThirteenAG/GTAIV.EFLC.FusionFix/)| Second main mod in the pack: it contains a bunch of fixes and also acts as a modloader together with [Ultimate ASI Loader](../mod-dependencies/#ultimate-asi-loader).<br>[Ported by Zolika1351](https://github.com/Zolika1351/GTAIV.EFLC.FusionFix/)</br> |
	| [Shader Fixes Collection~V109*~ by Parallellines0451 and others](https://github.com/Parallellines0451/GTAIV.ShaderFixesCollection)| A collection of numerous shader fixes, from simple scaling to restoring console files. *manually built the up-to-date files |
	| [Console Visuals~1.3~ by nastyyaboi and others](https://gtaforums.com/topic/989098-console-visuals-the-complete-edition)| Collection of ported visuals from the console version - from timecyc, to animations.<br>Used addons: Console Clothing, Console Fences, Console Trees(Console Leaves)</br> |
	| [DXVK-gplasync~2.2-4~](https://gitlab.com/Ph42oN/dxvk-gplasync/-/releases)| Translates DirectX 9 API to Vulkan - main [optimization](optimization.md) method. |
	| [Various Fixes~1.5~ by Attramet and others](https://gtaforums.com/topic/975211-various-fixes/)| A large collection of fixes of various scale - mostly broken map textures. |
	| [Trilogy Characters Fixes~2023-07-28~ by TheYoshiPunch, (Japan) GTA Love, DiZco12, JohnnyK NeverDie, and others](https://gtaforums.com/topic/927583-grand-theft-auto-iv-and-episodes-from-liberty-city-characters-fixes/page/25/#comment-1072185890)| A large collection of fixes for inconsistencies between character appearances in IV and EFLC - plus, a few fixes just for the models themselves.<br>Addon Used: Niko's Original GTAIV Hair</br> |
	| [Liberty Tweaks~1.1~ by The Westside Minions & The GTA IV Modding Community](https://gtaforums.com/topic/991160-liberty-tweaks/)| A highly configurable quality-of-life mod. ==This mod allows to quicksave using ++f9++ key. It also allows to holster weapons using the ++h++ key.== |
	| [Improved Animations Pack~1.3~ by B Dawg](https://gtaforums.com/topic/958625-improved-animations-pack/)| Fixes some weapon animation issues such as delayed fire. |
	| [IV Fixes and Improvements~3.3~ by Zolika1351 and others](https://gtaforums.com/topic/909155-iv-fixes-improvements/)| A collection of minor fixes and improvements - see the changelog on the page. |
	| [Fix Collection by iiCriminnaaL, nkjellman and me](https://drive.google.com/file/d/13OgDDm0xakbdRONPlrnN5zRfshdAgwhd/view?usp=sharing) | Several fixes from Responsive Plus and Graphics Fix, specifically - `stipple.wtd`, `coronas.wtd`, `carcols.dat`, `cargrp.dat` and files related to rain splash effects. My work in this is just bundling them separately. |
	| [Project2DFX~4.3~ by ThirteenAG](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX/releases/tag/gtaiv)| Adds nice lights in the distance at night. ==Can be disabled by deleting the `IVLodLights` files.== |
	| [Xbox Rain Droplets by ThirteenAG](https://github.com/ThirteenAG/XboxRainDroplets/releases/tag/gtaiv)| Add nice water droplets on the screen. ==Can be disabled by deleting the `GTAIV.XboxRainDroplets` files.== |
	| [Restored Pedestrians by Attramet](https://gtaforums.com/topic/981864-restored-pedestrians/) | Restores various cut/non-included pedestrians to the game world. |
	| [Various Pedestrians Actions by Attramet](https://gtaforums.com/topic/976318-various-pedestrian-actions/) | Restores various cut/non-included pedestrian actions to the game world. |
	| [Restored Trees Position by Attramet](https://gtaforums.com/topic/984591-restored-trees-position/) | Restores several trees that were only present in the beta version. |
	| [More Visible Interiors by Attramet](https://gtaforums.com/topic/974099-more-visible-interiors/) | Makes interiors more visible on the outside. |
	| [Vanilla Road Texture Enhancement by DayL](https://discord.gg/gZvZmFt2p7) | 2x AI upscaling for road textures, as well as generated normal and specular maps. ==WIP==. |
	| [Project Glass by DayL](https://discord.gg/gZvZmFt2p7) | Adds cubemap reflections to most glass in the world so it no longer looks like clear plastic. ==WIP==. |
	| [Project Thunder by ItsClockAndre](https://gtaforums.com/topic/982902-project-thunder/) | Adds a highly customizable thunder effect to the Lighting weather. |
	| [Vehicle Pack~2.0~ - 15th Anniversary Edition by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/5/#comment-1072121736)| Upscaled and ported vehicle textures from GTA V and Max Payne 3. |
	| [Improved Weapon Spec by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/4/#comment-1071652002)| Higher resolution specular maps for weapons. |
	| [Dodgy Doc - Higher Quality by donnits](https://gtaforums.com/topic/974798-donnits-bakery/) | Increases the texture resolution for the Dodgy Doc. |
	| [Resized Blista Compact by Thundersmacker](https://www.gtainside.com/en/gta4/cars/188730-resized-blista-compact/) | Fixes the model for Blista Compact, giving it the correct size and correcting modeling errors. |
	| [Fixed LCPD Buffalo by Ooboy](https://www.gtainside.com/en/gta4/cars/181342-fixed-lcpd-buffalo/) | Fixes the police Buffalo model and texture bugs. |
	| [Player Outfit Texture Fixes by B Dawg](https://gtaforums.com/topic/925011-player-outfit-texture-fixes) | Fixes green-ish textures on outfits. |
	| [Fixed Suit Display in Perseus by _ys](https://gtaforums.com/topic/984565-iv-fixed-suit-display-in-perseus/) | Fixes incorrect suit display in Perseus. |
	| [Default Pistol Iron Sight Fix by grasscid](https://www.nexusmods.com/gta4/mods/15)| Fixes the incorrect pistol iron sight. |
	| [Liberty Ferry Terminal - Waiting Room Sign Fix by donnits](https://gtaforums.com/topic/974798-donnits-bakery/)| Fixes broken UV map on "Waiting Room" sign texture. |
	| [Sugar Chomps - Separate Signs by donnits](https://gtaforums.com/topic/974798-donnits-bakery/)| Edits the UV map on the sign to include an unused texture. |
	| [Traffic Cops: Back in the Toolbooths by Olanov](https://www.gtainside.com/en/gta4/mods/187365-traffic-cops-back-in-the-tollbooths/)| Simple script mod that replaces the toll booth cop peds with traffic cops |
	| [Luis' Helmet Reflections Fix by 6135](https://www.gtainside.com/en/gta4/skins/125863-luis-s-helmet-reflections-fix/) | Fixes the reflections on Luis' helmet. |
	| [Luis' Bag Texture Fix by 6135](https://www.gtainside.com/en/gta4/skins/136118-luis-s-bag-texture-fix/) | Fixes missing normal and specular textures on Luis' bag, improves texture quality. |
	| [Johnny's Shoe Texture Fix by 6135](https://www.gtainside.com/en/gta4/skins/125196-johnny-s-shoe-texture-fix/) | Fixes missing normal and specular textures on Johnny's shoes. |
	| [GTA Online QUBE3D Background by Zolika1351](https://zolika1351.pages.dev/mods/ivqub3d)| Ported QUB3D background (without the grid) from GTA Online. |
	| [Xbox One/Series S+X Buttons by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/4/#comment-1071669058)| More modern textures for the controller buttons. |
	| [Higher Res Radio Logos In-Game](https://gtaforums.com/topic/887527-ash_735s-workshop/?do=findComment&comment=1071559765) and [Higher Res Radio Logos Menu by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/?do=findComment&comment=1071512871)| High resolution textures of radio logos. |
=== "1.2.0.59"
	| Mod name | Details |
	| :------: | :-----: |
	| [Radio Downgrader by Tomasak and others](http://downgraders.rockstarvision.com/)| A simple-to-perform radio downgrade.<br>Addon used: [Restored original TBoGT Menu Vocals](https://www.nexusmods.com/gta4/mods/234?tab=files)</br> |
	| [FusionFix~1.80~ by ThirteenAG, Tomasak and others](https://github.com/ThirteenAG/GTAIV.EFLC.FusionFix/)| The main mod of the pack, it contains a bunch of fixes and also acts as a modloader together with [Ultimate ASI Loader](../mod-dependencies/#ultimate-asi-loader). |
	| [Shader Fixes Collection~V109*~ by Parallellines0451 and others](https://github.com/Parallellines0451/GTAIV.ShaderFixesCollection)| A collection of numerous shader fixes, from simple scaling to restoring console files. *manually built the up-to-date files |
	| [Console Visuals~1.3~ by nastyyaboi and others](https://gtaforums.com/topic/989098-console-visuals-the-complete-edition)| Collection of ported visuals from the console version - from timecyc, to animations.<br>Used addons: Console Clothing, Console Fences, Console Trees(Console Leaves)</br> |
	| [DXVK-gplasync~2.2-4~](https://gitlab.com/Ph42oN/dxvk-gplasync/-/releases)| Translates DirectX 9 API to Vulkan - main [optimization](optimization.md) method. |
	| [Various Fixes~1.5~ by Attramet and others](https://gtaforums.com/topic/975211-various-fixes/)| A large collection of fixes of various scale - mostly broken map textures. |
	| [Trilogy Characters Fixes~2023-07-28~ by TheYoshiPunch, (Japan) GTA Love, DiZco12, JohnnyK NeverDie, and others](https://gtaforums.com/topic/927583-grand-theft-auto-iv-and-episodes-from-liberty-city-characters-fixes/page/25/#comment-1072185890)| A large collection of fixes for inconsistencies between character appearances in IV and EFLC - plus, a few fixes just for the models themselves.<br>Addon Used: Niko's Original GTAIV Hair</br> |
	| [Improved Animations Pack~1.3~ by B Dawg](https://gtaforums.com/topic/958625-improved-animations-pack/)| Fixes some weapon animation issues such as delayed fire. |
	| [IV Fixes and Improvements~3.3~ by Zolika1351 and others](https://gtaforums.com/topic/909155-iv-fixes-improvements/)| A collection of minor fixes and improvements - see the changelog on the page. |
	| [Fix Collection by iiCriminnaaL, nkjellman and me](https://drive.google.com/file/d/13OgDDm0xakbdRONPlrnN5zRfshdAgwhd/view?usp=sharing) | Several fixes from Responsive Plus and Graphics Fix, specifically - `stipple.wtd`, `coronas.wtd`, `carcols.dat`, `cargrp.dat` and files related to rain splash effects. My work in this is just bundling them separately. |
	| [Project2DFX~4.5~ by ThirteenAG](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX/releases/tag/gtaiv)| Adds nice lights in the distance at night. ==Can be disabled by deleting the `IVLodLights` files.== |
	| [Xbox Rain Droplets by ThirteenAG](https://github.com/ThirteenAG/XboxRainDroplets/releases/tag/gtaiv)| Add nice water droplets on the screen. ==Can be disabled by deleting the `GTAIV.XboxRainDroplets` files.== |
	| [Restored Trees Position by Attramet](https://gtaforums.com/topic/984591-restored-trees-position/) | Restores several trees that were only present in the beta version. |
	| [More Visible Interiors by Attramet](https://gtaforums.com/topic/974099-more-visible-interiors/) | Makes interiors more visible on the outside. |
	| [Vanilla Road Texture Enhancement by DayL](https://discord.gg/gZvZmFt2p7) | 2x AI upscaling for road textures, as well as generated normal and specular maps. ==WIP==. |
	| [Project Glass by DayL](https://discord.gg/gZvZmFt2p7) | Adds cubemap reflections to most glass in the world so it no longer looks like clear plastic. ==WIP==. |
	| [Vehicle Pack~2.0~ - 15th Anniversary Edition by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/5/#comment-1072121736)| Upscaled and ported vehicle textures from GTA V and Max Payne 3. |
	| [Improved Weapon Spec by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/4/#comment-1071652002)| Higher resolution specular maps for weapons. |
	| [Dodgy Doc - Higher Quality by donnits](https://gtaforums.com/topic/974798-donnits-bakery/) | Increases the texture resolution for the Dodgy Doc. |
	| [Resized Blista Compact by Thundersmacker](https://www.gtainside.com/en/gta4/cars/188730-resized-blista-compact/) | Fixes the model for Blista Compact, giving it the correct size and correcting modeling errors. |
	| [Fixed LCPD Buffalo by Ooboy](https://www.gtainside.com/en/gta4/cars/181342-fixed-lcpd-buffalo/) | Fixes the police buffalo model and texture bugs. |
	| [Player Outfit Texture Fixes by B Dawg](https://gtaforums.com/topic/925011-player-outfit-texture-fixes) | Fixes green-ish textures on outfits. |
	| [Fixed Suit Display in Perseus by _ys](https://gtaforums.com/topic/984565-iv-fixed-suit-display-in-perseus/) | Fixes incorrect suit display in Perseus. |
	| [Default Pistol Iron Sight Fix by grasscid](https://www.nexusmods.com/gta4/mods/15)| Fixes the incorrect pistol iron sight. |
	| [Liberty Ferry Terminal - Waiting Room Sign Fix by donnits](https://gtaforums.com/topic/974798-donnits-bakery/)| Fixes broken UV map on "Waiting Room" sign texture. |
	| [Sugar Chomps - Separate Signs by donnits](https://gtaforums.com/topic/974798-donnits-bakery/)| Edits the UV map on the sign to include an unused texture. |
	| [Traffic Cops: Back in the Toolbooths by Olanov](https://www.gtainside.com/en/gta4/mods/187365-traffic-cops-back-in-the-tollbooths/)| Simple script mod that replaces the toll booth cop peds with traffic cops |
	| [Luis' Helmet Reflections Fix by 6135](https://www.gtainside.com/en/gta4/skins/125863-luis-s-helmet-reflections-fix/) | Fixes the reflections on Luis' helmet. |
	| [Luis' Bag Texture Fix by 6135](https://www.gtainside.com/en/gta4/skins/136118-luis-s-bag-texture-fix/) | Fixes missing normal and specular textures on Luis' bag, improves texture quality. |
	| [Johnny's Shoe Texture Fix by 6135](https://www.gtainside.com/en/gta4/skins/125196-johnny-s-shoe-texture-fix/) | Fixes missing normal and specular textures on Johnny's shoes. |
	| [GTA Online QUBE3D Background by Zolika1351](https://zolika1351.pages.dev/mods/ivqub3d)| Ported QUB3D background (without the grid) from GTA Online. |
	| [Menu Art Fix](https://gtaforums.com/topic/887527-ash_735s-workshop/page/5/#comment-1072165611) | Fixes lower resolution backgrounds in EFLC's main menus. |
	| [Xbox One/Series S+X Buttons by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/page/4/#comment-1071669058)| More modern textures for the controller buttons. |
	| [Higher Res Radio Logos In-Game](https://gtaforums.com/topic/887527-ash_735s-workshop/?do=findComment&comment=1071559765) and [Higher Res Radio Logos Menu by Ash_735](https://gtaforums.com/topic/887527-ash_735s-workshop/?do=findComment&comment=1071512871)| High resolution textures of radio logos. |

## Additional Mods { data-search-exclude }
These mods are not included by default, but do not require any additional steps to install over the archive
=== "1.0.8.0"
	| Mod name | Details |
	| :------: | :-----: |
	| [Radio Downgrader Addons](https://www.nexusmods.com/gta4/mods/234?tab=files) | You can install following addons: `Combine Old and New Songs on Vladivostok FM` and `No EFLC Music in GTA IV Radio`. <br>Installation: Extract the downloaded addon into the game folder.</br> | 
	| Liberty Tweaks options |`Improved AI` and `Remove Weapons on Death` have been disabled - you can toggle them back in :material-file-cog:`LibertyTweaks.ini` located in :material-folder:==IVSDKDotNet\scripts\\==. You can also tweak your FOV in there, aswell as change keybinds for quicksaving and holstering weapons (++f9++ and ++h++ by default) |
	| [ColAccel by ThirteenAG](https://github.com/ThirteenAG/IV.EFLC.ColAccel/)| Speeds up loading times by several times, ==but can cause memory problems and does not cache moments from the story (like the burnt garage)==. [Can be used in combination with ZolikaPatch's FastLoading option](https://streamable.com/slqqsl). <br>Installation: download version ==1.4==, extract :material-file:`IV.EFLC.ColAccel.asi` into :material-folder:==plugins== or into the game folder</br> |
	| [Vanilla PC TLAD Noise by me](https://drive.google.com/file/d/1zxCWhWQ4qP4rJvUablTGjfqpFUp3UOS3/view?usp=sharing) | Removes console tiling from TLAD's noise introduced by Shader Fixes Collection, making it look like the vanilla on PC, incase you don't like how overexxagerated it gets.<br>Installation: Extract into game folder.</br> |
	| [Aura by catsmackaroo, Nastyyaboi, ItsClockAndre and cubabori](https://gtaforums.com/topic/989259-aura/) | A vanilla+ graphics mod, building upon the vanilla look.<br>Installation: Extract into :material-folder:==update==. ==Recommended to use with Vanilla PC TLAD Noise.==</br> | 
	| [Console Visuals Addons](https://gtaforums.com/topic/989098-console-visuals-the-complete-edition) | You can add several addons, such as Console Loading Screens and else. However, first check if the one you want is already installed.<br>Installation: Download the Complete Edition version and extract the desired ==update== folders.</br> |
	| [Better Wardrobes by Zolika1351](https://zolika1351.pages.dev/mods/ivwardrobe)| Replaces the clunky wardrobe with a faster and more intuitive one - however, it can be uncomfortable for some people and it also ==unlocks all clothing in the game from the start==.<br>Installation: Extract :material-file:`WardrobeMod.asi` into the game folder.</br> |
	| [DXVK-async 1.10.3](https://github.com/Sporif/dxvk-async/releases/tag/1.10.3)| If you have an ancient GPU (like the GTX 600 series) and DXVK from the main archive doesn't work, use this version as a replacement.<br>Installation: From the archive, extract :fontawesome-solid-gears:`d3d9.dll` from :material-folder:==x32== into the game folder.</br> |
	| [DXVK-async 1.10.1](https://github.com/Sporif/dxvk-async/releases/tag/1.10.1)| If you have an Intel iGPU, you can use this version of DXVK.<br>Installation: From the archive, extract :fontawesome-solid-gears:`d3d9.dll` from :material-folder:==x32== into the game folder.</br> |
	| [IV-Presence by ItsClockAndre](https://gtaforums.com/topic/975850-iv-presence/) | Adds a Discord Rich Presence.<br>Installation: From the archive, extract :fontawesome-solid-gears:`discord-rpc.dll` and :material-file:`IVPresence.asi` from :material-folder:==For GTA IV 1070 and 1080== into the game folder. If you have issues, also extract :material-file:`IVPresenceDependenciesChecker.exe` with it's config, launch it and see what dependencies are you lacking.</br>|
	| [Dualshock 4 button textures by tehherb](https://www.gtagaming.com/360-to-ps4-controller-icons-f30380.html)| Replaces the Xbox 360 button textures with Dualshock 4 buttons.<br>Installation: In :material-folder:==modloader== edit :material-file-edit:`modloader.ini` to change `DualshockButtons=1` to `0` at the beginning of the file, and `XboxButtons=0` to `1`.</br> |
	| [Dualsense button textures by COZlerCae](https://www.nexusmods.com/gta4/mods/286)| Replaces the Xbox 360 button textures with Dualsense buttons. <br>Installation: In :material-folder:==modloader== edit :material-file-edit:`modloader.ini` to change `DualsenseButtons=1` to `0` at the beginning of the file, and `XboxButtons=0` to `1`.</br> |

=== "1.2.0.59"
	| Mod name | Details |
	| :------: | :-----: |
	| [Radio Downgrader Addons](https://www.nexusmods.com/gta4/mods/234?tab=files) | You can install following addons: `Combine Old and New Songs on Vladivostok FM` and `No EFLC Music in GTA IV Radio`. <br>Installation: Extract the downloaded addon into the game folder.</br> | 
	| [ColAccel by ThirteenAG](https://github.com/ThirteenAG/IV.EFLC.ColAccel/)| Speeds up loading times by several times, ==but can cause memory problems and does not cache moments from the story (like the burnt garage)==.<br>Installation: download version ==1.5==, extract :material-file:`IV.EFLC.ColAccel.asi` into :material-folder:==plugins== or into the game folder.</br> |
	| [Vanilla PC TLAD noise by me](https://drive.google.com/file/d/1zxCWhWQ4qP4rJvUablTGjfqpFUp3UOS3/view?usp=sharing) | Removes console tiling from TLAD's noise introduced by Shader Fixes Collection, making it look like the vanilla on PC, incase you don't like how overexxagerated it gets.<br>Installation: Extract into game folder.</br> |
	| [Aura by catsmackaroo, Nastyyaboi, ItsClockAndre and cubabori](https://gtaforums.com/topic/989259-aura/) | A vanilla+ graphics mod, building upon the vanilla look.<br>Installation: Extract into :material-folder:==update==. Recommended to use with Vanilla PC TLAD Noise.</br> | 
	| [Console Visuals Addons](https://gtaforums.com/topic/989098-console-visuals-the-complete-edition) | You can add several addons, such as Console Loading Screens and else. However, first check if the one you want is already installed.<br>Installation: Download the Complete Edition version and extract the desired ==update== folders.</br> |
	| [DXVK-async 1.10.3](https://github.com/Sporif/dxvk-async/releases/tag/1.10.3)| If you have an ancient GPU (like the GTX 600 series) and DXVK from the main archive doesn't work, use this version as a replacement.<br>Installation: From the archive, extract :fontawesome-solid-gears:`d3d9.dll` from :material-folder:==x32== into the game folder.</br> |
	| [DXVK-async 1.10.1](https://github.com/Sporif/dxvk-async/releases/tag/1.10.1)| If you have an Intel iGPU, you can use this version of DXVK.<br>Installation: From the archive, extract :fontawesome-solid-gears:`d3d9.dll` from :material-folder:==x32== into the game folder.</br> |
	| [Dualshock 4 button textures by tehherb](https://www.gtagaming.com/360-to-ps4-controller-icons-f30380.html)| Replaces the Xbox 360 button textures with Dualshock 4 buttons.<br>Installation: in the :material-folder:==update/pc/textures==, replace :material-file:`360_buttons.wtd`.</br> |
	| [Dualsense button textures by COZlerCae](https://www.nexusmods.com/gta4/mods/286)| Replaces the Xbox 360 button textures with Dualsense buttons. <br>Installation: in the :material-folder:==update/pc/textures==, replace :material-file:`360_buttons.wtd`.</br> |

## Changelog { data-search-exclude }
=== "1.0.8.0"
	- The archive is updated frequently, below is the list of changes:
		* 28.08.2023 - Fixed the infinite loading on Three Leaf Clover mission (needs a better solution - at the moment, there's a missing NPC model in the cutscene due to this). Fixed Dodgy Doc HQ mod to actually be used. Added `dxvk.gplAsyncCache = true` to :material-file-cog:`dxvk.conf`. Removed Better Wardrobes.
		* 26.08.2023 - Updated FusionFix, Project Glass, Xbox One/Series S+X Buttons. Added Menu Art Fix. Repacked Various Fixes, aswell as adding community's fixes to it.
		* 18.08.2023 - Updated Various Fixes files. Fixed a model issue with Angels of Death's clubhouse in TLAD.
		* 17.08.2023 - Updated Project Glass. Added More Visible Interiors. Slightly tweaked configuration files.
		* 12.08.2023 - Fixed known crash and softlock issues in TLAD and TBoGT. Restored TBoGT menu soundtrack. 
		* 11.08.2023 - Fixed crash issues (IV Tweaker from up-to-date downgrader was not up-to-date). Updated FusionFix, Shader Fixes (manually built). Slightly tweaked vehicle budget. Changed Niko's hair files to fix the visual issues with it.
		* 10.08.2023 - Updated the Downgrader, ZolikaPatch and Project Glass. 
		* 07.08.2023 - Updated FusionFix.
    	* 03.08.2023 - Added Restored Trees Position. Rearranged some files to avoid incompatibility issues. Updated Console Visuals.
		* 02.08.2023 - Updated FusionFix, Trilogy Characters Fixes - also repacked it slightly.
		* 25.07.2023 - Updated Fix Collection. Minor .ini tweaks. Added Project Thunder, Restored Pedestrians, Various Pedestrian Actions.
		* 24.07.2023 - Repackage mods to reduce folder bloat. Added Road Texture Enhancement, Project Glass(+lighthing for bus stops), Dodgy Doc - Higher Quality, Rescaled Blista Compact, Player Outfit Texture Fixes, LCPD Buffalo Fix, Luis' Helmet Reflections Fix, Luis' Bag Texture Fix, Johnny's Shoe Texture Fix, Fixed Suit Display and borrowed a few fixes from Responsive Plus.
		* 20.07.2023 - Changed dxvk to dxvk-gplasync. Updated FusionFix.
		* 19.07.2023 - Updated the Downgrader, ZolikaPatch, IV Tweaker, FusionFix, Shader Fixes. Added the Radio Downgrader, GTA Online QUB3D Background, Better Wardrobes, Traffic Cops in the Toolbooths, Xbox Rain Droplets, Fixed Pistol Sights. Added Dualsense buttons to optionals. Removed Pedestrians with Unused Clothing Restored and Varied Alderney State Trooper Ped due to potential incompatibilities.
		* 15.07.2023 - Added Liberty Tweaks.
		* 13.07.2023 - Fixed disappearing assets in Roman's taxi office. Changed FPS limit in cutscenes to 32.
		* 12.07.2023 - Added the following mods: (newer) IV Fixes and Improvements, Liberty Ferry Terminal - Waiting Room Sign Fix, Sugar Chomps - Separate Signs, Pedestrians with Unused Clothes Restored, Varied Alderney State Trooper Ped, Higher Res Radio Logos, Improved Weapon Spec. Moved Various Fixes to update folder due to compatibility issues. Removed TBoGT Texture Quality Fix as Various Fixes already contains this fix fix. Removed TBoGT Vehicle Fix from modloader as FusionFix already contains the fix. Removed IVPresence. Updated ZolikaPatch.
		* 11.07.2023 - Fixed the main game crash problem.
		* 10.07.2023 - Updated the downgrader. Added FusionFix 1.60 port by Zolika. Later: Fixed TLAD crash, changed Niko's hair file, now has no visual problems.
		* 09.07.2023 - Changed the downgrader - now bundled with the archive. Removed IV Fixes and Improvements. Added Various Fixes. Added Dualshock buttons(optional).
		* 08.07.2023 - Updated Shader Fixes. Removed Simple Traffic Loader. Mods completely repacked to use modloader instead.
		* 01.07.2023 - Updated Shader Fixes, repacked some mods.
		* 30.06.2023 - Updated Shader Fixes.
		* 26.06.2023 - Created the archive.
=== "1.2.0.59"
	- The archive is updated frequently, below is the list of changes:
		* 28.08.2023 - Fixed Dodgy Doc HQ mod to actually be used. Added `dxvk.gplAsyncCache = true` to :material-file-cog:`dxvk.conf`.
		* 26.08.2023 - Updated Project Glass. Added community's fixes to Various Fixes. Returned more up-to-date Shader Fixes files, as I accidentally overwrote them last update.
		* 22.08.2023 - Updated FusionFix, Xbox One/Series S+X Buttons. Added Menu Art Fix.
    	* 18.08.2023 - Updated Various Fixes files. Fixed a model issue with Angels of Death's clubhouse in TLAD.
		* 17.08.2023 - Updated Project Glass. Added More Visible Interiors. Slightly tweaked configuration files.
		* 12.08.2023 - Fixed known crash and softlock issues in TLAD and TBoGT. Restored TBoGT menu soundtrack.  
		* 11.08.2023 - Updated Shader Fixes (manually built). Slightly tweaked vehicle budget. Changed Niko's hair files to fix the visual issues with it.
		* 10.08.2023 - Updated Project Glass.  
		* 07.08.2023 - Updated FusionFix. 
	    * 03.08.2023 - Added Restored Trees Position.
		* 02.08.2023 - Updated FusionFix, Trilogy Characters Fixes, Console Visuals.
		* 25.07.2023 - Updated Fix Collection. Minor .ini tweaks.
		* 23.07.2023 - Fixed priority for mods. Repackage mods to reduce folder bloat. Added Road Texture Enhancement, Project Glass(+lighthing for bus stops), Dodgy Doc - Higher Quality, Rescaled Blista Compact, Player Outfit Texture Fixes, LCPD Buffalo Fix, Luis' Helmet Reflections Fix, Luis' Bag Texture Fix, Johnny's Shoe Texture Fix, Fixed Suit Display and borrowed a few fixes from Responsive Plus.
		* 20.07.2023 - Changed dxvk to dxvk-gplasync. Updated FusionFix.
		* 19.07.2023 - Updated FusionFix and Shader Fixes. Added the Radio Downgrader, GTA Online QUB3D Background, Traffic Cops in the Toolbooths, Xbox Rain Droplets, Fixed Pistol Sights. Added Dualsense buttons to optionals. Removed Pedestrians with Unused Clothing Restored and Varied Alderney State Trooper Ped due to potential incompatibilities.
		* 13.07.2023 - Fixed disappearing assets in Roman's taxi office. Changed FPS limit in cutscenes to 32.
		* 12.07.2023 - Added the following mods: (newer) IV Fixes and Improvements, Liberty Ferry Terminal - Waiting Room Sign Fix, Sugar Chomps - Separate Signs, Pedestrians with Unused Clothes Restored, Varied Alderney State Trooper Ped, Higher Res Radio Logos, Improved Weapon Spec. Removed TBoGT Texture Quality Fix as Various Fixes already contains the fix.
		* 10.07.2023 - Changed Niko's hair file, now has no visual problems.
		* 09.07.2023 - Removed IV Fixes and Improvements. Added Various Fixes.
		* 08.07.2023 - Updated FusionFix, Shader Fixes, changed DXVK config, removed dxgi.dll and repacked some mods.
		* 02.07.2023 - Repacked mods in a more convenient format.
		* 01.07.2023 - Updated Shader Fixes. Ported mods from older versions.
		* 30.06.2023 - Updated mods.
		* 27.06.2023 - Updated mods.
		* 26.06.2023 - Created the archive.

[:material-page-first:Previous page <br>Introduction</br>](index.md){ .md-button } [Next page:material-page-last: <br>Additional Setup</br>](additional-setup.md){ .md-button .md-button--primary }