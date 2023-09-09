title: Kingdom Hearts HD 1.5 + 2.5 ReMIX
description: Gillian's mod and/or tools list for Kingdom Hearts HD 1.5 + 2.5 ReMIX.

# Kingdom Hearts HD 1.5 + 2.5 ReMIX
## Links { data-search-exclude }
- [Store Page (Epic Games Store)](https://store.epicgames.com/en-US/p/kingdom-hearts-hd-1-5-2-5-remix)
- [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Kingdom_Hearts_HD_1.5_%2B_2.5_ReMIX)
- [OpenKH](https://github.com/OpenKH/OpenKh/)
- [Kingdom Hearts Re:Fined](https://github.com/TopazTK/KH-ReFined)
- [LuaBackend](https://github.com/Sirius902/LuaBackend/)
- [KHPCPatchManager](https://github.com/AntonioDePau/KHPCPatchManager) - use OpenKH instead unless you specifically need this tool.
- [Kingdom Save Editor](https://github.com/Xeeynamo/KingdomSaveEditor)

Game definitely didn't get the best PC treatment, but thanks to Re:Fined we can have a very much bearable experience here. In some ways, even superior to the original one. Other than that, there's a bunch of HD mods, aswell as overhaul ones.

## Game Settings { data-search-exclude }
Game has a limited amount of settings - you only set up the screen/window mode, resolution, framerate lock, VSync, brightness and colorbrind options. Has hard-locked AA. See the [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Kingdom_Hearts_HD_1.5_%2B_2.5_ReMIX#Ultra-widescreen) for ultrawide or square monitor setup.
!!! note "Anisotropic Filtering"
    The game uses 4x Anisotropic by default without any way to toggle it. If you don't like that, you can increase it to 8x/16x via Nvidia Control Panel or AMD Adrenalin.

## Essentials { data-search-exclude }
### Kingdom Hearts Re:Fined { data-search-exclude }
!!! info ""
    This mod aims to fix problems, crashes, and bugs that are present within the PC Ports of all legacy-class Kingdom Hearts games, aswell as introduce quality-of-life features to the games. See the [repository](https://github.com/TopazTK/KH-ReFined) for instructions, extra information and releases. Install the v4.00 version with OpenKH.

    [:simple-discord: Re:Fined Discord Server](https://discord.gg/kh-refined){ .md-button .md-button--primary }

## Mods { data-search-exclude }
=== "Kingdom Hearts Final Mix"
    * [HD Textures](https://www.nexusmods.com/kingdomheartsfinalmix/mods/4)
    !!! info ""
        * [Critical Mix](https://www.nexusmods.com/kingdomheartsfinalmix/mods/93)

        A full overhaul with a fast KH2-style combat system. Revamps Sora's combos, keyblades, accessories, abilities, and much more.
    * [Copyright Screen Skip](https://www.nexusmods.com/kingdomheartsfinalmix/mods/70)
=== "Kingdom Hearts Re: Chain of Memories"
    * [HD Textures](https://www.nexusmods.com/kingdomheartsrechainofmemories/mods/2)
    !!! info ""
        * [Final Mix Heartless Colors](https://www.nexusmods.com/kingdomheartsrechainofmemories/mods/6)

        Replaces Heartless colors to match with the Final Mix releases the rest of the collection has.
    !!! info ""
        * [Remastered Soundtrack](https://www.nexusmods.com/kingdomheartsrechainofmemories/mods/15)

        Replaces soundtrack to match with the remastered versions the rest of the collection has.
    * [Copyright Screen Skip](https://www.nexusmods.com/kingdomheartsrechainofmemories/mods/12)
=== "Kingdom Hearts II Final Mix"
    !!! warning ""
        * [HD Textures](https://www.nexusmods.com/kingdomhearts2finalmix/mods/17)

        Not recommended on a 1080p or lower screen - the fonts get too high resolution, resulting in them looking worse instead.
    * [HD Environments](https://www.nexusmods.com/kingdomhearts2finalmix/mods/63)
    !!! warning ""
        * [HD Models](https://www.nexusmods.com/kingdomhearts2finalmix/mods/120)
        - Uses textures from the HD Textures mod.
        - May result in corrupted models in some cases.
    * [High Poly Keyblades](https://www.nexusmods.com/kingdomhearts2finalmix/mods/92)
    * [HD Maps](https://www.nexusmods.com/kingdomhearts2finalmix/mods/60)
    * [Uncensored KH2](https://www.nexusmods.com/kingdomhearts2finalmix/mods/150)
    
    !!! note ""
        [Copyright Screen Skip](https://www.nexusmods.com/kingdomhearts2finalmix/mods/128)

        [Quicker Copyright Screen](https://www.nexusmods.com/kingdomhearts2finalmix/mods/93) can be used instead.
=== "Kingdom Hearts Birth by Sleep Final Mix"
    * [HD Textures](https://www.nexusmods.com/kingdomheartsbirthbysleepfinalmix/mods/3)
    * [Improved Camera](https://www.nexusmods.com/kingdomheartsbirthbysleepfinalmix/mods/1)
    * [Aqua Uncensored](https://www.nexusmods.com/kingdomheartsbirthbysleepfinalmix/mods/5)
    !!! info ""
        * [Ultimate Mix](https://www.nexusmods.com/kingdomheartsbirthbysleepfinalmix/mods/25)

        Huge overhaul mod for Birth by Sleep.
    * [Copyright Screen Skip](https://www.nexusmods.com/kingdomheartsbirthbysleepfinalmix/mods/22)

## Tools { data-search-exclude }
### OpenKH Mod Manager { data-search-exclude }
OpenKH offers a lot of tools, but the one you'd mainly want to use as a regular user is the Mod Manager, which allows to patch a good variety of mods aswell as set up their priority. Also has a modloader which reduces build time.

???+ note "Installation"
    - Go to the latest release of [OpenKH](https://github.com/OpenKH/OpenKh/releases), download it and unpack in any desired folder (not the game folder directly).
    - Open :material-file:`OpenKh.Tools.ModsManager.exe`. Go through the instructions, install Panacea and unpack the desired game.
???+ tip "Usage"
    - To install mods, click `Mods` -> `Install a new mod...` (or press the plus to the right of the list) and from there either pick a downloaded mod or leave the name for a repository on GitHub.
    - Change priority as desired.
### LuaBackend { data-search-exclude }
LuaBackend offers to enable the game with mods scripted in lua. You may not need it.

??? note "Installation and Usage"
    - Go to the latest release of [LuaBackend](https://github.com/Sirius902/LuaBackend/releases), download it and unpack in the game folder (may not be compatible with Panacea).
    - To install mods, extract their .lua file to `%USERPROFILE%\Documents\KINGDOM HEARTS HD 1.5+2.5 ReMIX\scripts\kh1\` (or `\kh2`, `\khbbs` or `\khrecom` according to your game)
### Kingdom Save Editor { data-search-exclude }
An easy-to-use savefile editor incase you need one. Follow the link in [links](#links) to find it.