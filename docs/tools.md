title: Tools
description: Gillian's tools list and instructions to use them

# Tools { data-search-exclude }
This page lists all the tools separately away from my modlists. The reason for that is due to games sharing tools fairly often. However, don't use this page separately - other games link to the required sections already.

## Mod Managers { data-search-exclude }
### [OpenKH Mod Manager](https://github.com/OpenKH/OpenKh/) { data-search-exclude }
OpenKH offers a lot of modding tools for Kingdom Hearts, but the one you'd mainly want to use as a regular user is the Mod Manager, which allows to patch a good variety of mods aswell as set up their priority. Also has a modloader(Panacea) which reduces build time.

???+ note "Installation"
    - Go to the latest [release](https://github.com/OpenKH/OpenKh/releases), download it and unpack in any desired folder (not the game folder directly).
    - Open :material-file:`OpenKh.Tools.ModsManager.exe`. Go through the instructions, install Panacea and unpack the desired game.
???+ tip "Usage"
    - To install mods, click `Mods` -> `Install a new mod...` (or press the plus to the right of the list) and from there either pick a downloaded mod or leave the name for a repository on GitHub.
    - Change priority as desired.

## Mod Loaders { data-search-exclude }
### [LuaBackend](https://github.com/Sirius902/LuaBackend/) { data-search-exclude }
LuaBackend offers to enable Kingdom Hearts with mods scripted in Lua. You may not need it.

???+ note "Installation and Usage"
    - Go to the latest [release](https://github.com/Sirius902/LuaBackend/releases), download it and unpack in the game folder (may not be compatible with Panacea).
    - To install mods, extract their `.lua` file to `Documents\KINGDOM HEARTS HD 1.5+2.5 ReMIX\scripts\kh1\` (or `\kh2`, `\khbbs` or `\khrecom` according to your game)

## Save Editors { data-search-exclude }
### [Kingdom Save Editor](https://github.com/Xeeynamo/KingdomSaveEditor) { data-search-exclude }
An easy-to-use savefile editor for Kingdom Hearts and several other games.

???+ note "Usage"
    - Go to the latest [release](https://github.com/Xeeynamo/KingdomSaveEditor/releases), download it and unpack it in any desired folder.
    - Open `KHSave.SaveEditor.exe`. Ignore the error. Click `File` - `Open` or `Attach to PCSX2` if your game is a PS2 title.
    - For legacy Kingdom Hearts games, locate your savefiles in `Documents\Kingdom Hearts\Save Data\{userid}` - they're .png files. Encrypted unless you use Re:Fined.
    - The files that start with `BISPLS` are your savefiles. Double click to edit.