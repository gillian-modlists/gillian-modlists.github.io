title: Tools
description: Gillian's tools list and instructions to use them

# Tools { data-search-exclude }
This page lists all the tools separately away from my modlists. The reason for that is due to games sharing tools fairly often. However, don't use this page separately - other games link to the required sections already.

## General-purpose { data-search-exclude }
### [Special K](https://special-k.info/) { data-search-exclude }
A highly multi-purpose tool for debugging and solving many niche issues with PC games. Also has crucial patches for select games, such as [NieR Automata](nier_automata.md). See [this page](https://www.pcgamingwiki.com/wiki/Special_K) for more details.

???+ note "Installation and Usage"
    Follow the [official installation&usage instructions](https://wiki.special-k.info/SpecialK/Global).

### [Bethini Pie](https://www.nexusmods.com/site/mods/631) { data-search-exclude }
Universal, easy-to-use and highly flexible configuration tool for Bethesda games.

???+ note "Installation"
    - Download the [tool](https://www.nexusmods.com/site/mods/631?tab=files) and extract it to any desired folder.
    - If using [Mod Organizer 2](#mod-organizer-2), add the tool as an executable.

## Mod Managers { data-search-exclude }
### [Mod Organizer 2](https://www.nexusmods.com/skyrimspecialedition/mods/6194) { data-search-exclude }
Mod Organizer 2 is a feature rich mod manager for Bethesda games that keeps the mods away from the install folder and keeps it clean, aswell as providing environment to download mods from Nexus directly, sort the mods "correctly" and many other features.

???+ note "Installation and Usage"
    - Download the [installer](https://www.nexusmods.com/skyrimspecialedition/mods/6194?tab=files), launch it and install as desired.
    - After the first launch, you get a usage tutorial. I really don't need to explain a lot here.

### [OpenKH Mod Manager](https://github.com/OpenKH/OpenKh/) { data-search-exclude }
OpenKH offers a lot of modding tools for legacy [Kingdom Hearts](kingdom_hearts_hd_1.5_plus_2.5_remix.md) games, but the one you'd mainly want to use as a regular user is the Mod Manager, which allows to patch a good variety of mods aswell as set up their priority. Also has a modloader(Panacea) which reduces build time.

???+ note "Installation"
    - Go to the latest [release](https://github.com/OpenKH/OpenKh/releases), download it and unpack in any desired folder (not the game folder directly).
    - Open :material-file:`OpenKh.Tools.ModsManager.exe`. Go through the instructions, install Panacea and unpack the desired game.
???+ tip "Usage"
    - To install mods, click `Mods` -> `Install a new mod...` (or press the plus to the right of the list) and from there either pick a downloaded mod or leave the name for a repository on GitHub.
    - Change priority as desired.


## Mod Loaders { data-search-exclude }
### [LuaBackend](https://github.com/Sirius902/LuaBackend/) { data-search-exclude }
LuaBackend offers to enable [Kingdom Hearts](kingdom_hearts_hd_1.5_plus_2.5_remix.md) with mods scripted in Lua.

???+ note "Installation and Usage"
    - Go to the latest [release](https://github.com/Sirius902/LuaBackend/releases), download it and unpack in the game folder (may not be compatible with Panacea).
    - To install mods, extract their `.lua` file to `Documents\KINGDOM HEARTS HD 1.5+2.5 ReMIX\scripts\kh1\` (or `\kh2`, `\khbbs` or `\khrecom` according to your game)

## Save Editors { data-search-exclude }
### [Kingdom Save Editor](https://github.com/Xeeynamo/KingdomSaveEditor) { data-search-exclude }
An easy-to-use savefile editor for [Kingdom Hearts](kingdom_hearts_hd_1.5_plus_2.5_remix.md) and several other games.

???+ note "Usage"
    - Go to the latest [release](https://github.com/Xeeynamo/KingdomSaveEditor/releases), download it and unpack it in any desired folder.
    - Open `KHSave.SaveEditor.exe`. Ignore the error. Click `File` - `Open` or `Attach to PCSX2` if your game is a PS2 title.
    - For legacy Kingdom Hearts games, locate your savefiles in `Documents\Kingdom Hearts\Save Data\{userid}` - they're .png files. Encrypted unless you use Re:Fined.
    - The files that start with `BISPLS` are your savefiles. Double click to edit.