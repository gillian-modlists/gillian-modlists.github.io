title: Trainers
description: Add extra features to your GTA IV experience - for whatever reason you may need them!

# Trainers
Trainers are essentially modmenus that add a lot of fun and useful options. They're also a better alternative to the very limited amount of [cheatcodes](https://gta.fandom.com/wiki/Cheats_in_GTA_IV) the game offers. You may want one for [multiplayer](../multiplayer.md), but make sure your server allows them.
## ZMenuIV
!!! warning "Compatibility"
    This trainer is not compatible with the Complete Edition. [Downgrade](../downgrading.md) if using the Complete Edition.
The most powerful and full-fledged trainer for GTA IV. Also includes a Chaos mod for streamers and fun. And... Goldsrc physics...? Bhopping is fun, I guess.
???+ info "Installation"
    * Get the latest [Ultimate ASI Loader](../../mod-dependencies/#ultimate-asi-loader).
    * Go to [Zolika1351's Zone](https://zolika1351.pages.dev/mods/ivmenu).
    * Scroll to the bottom of the page and download the latest version.
    * Extract :material-zip-box:`ZMenuIV_vx.zip` into the game folder (excl. folders :material-folder:`asi loader if not using xliveless`, :material-folder:`for developers`, :material-folder:`old version (has VR support)`, :material-folder:`parachute support(all into game folder)`. Read the :material-file:`readme.txt` for details on these folders).
    ??? question "Addons"
        Read the :material-file:`readme.txt` for information on the addons.
???+ tip "Usage"
    - The default controls are:
        * ++f7++ to toggle menu.
        * ++num8++, ++num2++, ++num4++, ++num6++ for navigation. ++num5++ to accept, ++num0++ to go back.
        * ++right-control+num1++ to fix the car.
        * ++right-control+num2++ to flip the car.
        * ++bracket-right++ (hold) to speed the car up.
        * ++f6++ for Airbreak(noclip).
        * ++right-control++ for Special God 1.
        * ++f1++ for Special God 2.
        * ++0++ for Always God Mode.
        * ++bracket-left++ for Never Wanted.
        * ++semicolon++ for Unlimited Ammo.
        * ++equal++ for Collision.
        * ++minus++ for Resurrect.
        * ++single-quote++ for Forward Through Door.
        * ++m++ for Ragdoll.
    
    You can add your own custom keybinds that can combine multiple options together. To do so, enable `Custom Keybind Creator` in `Trainer Settings`, highlight the desired option and press ++left-control+enter++ to set the keybind up.

    Edit the `[Keybinds]` section in :material-file-cog:`ZMenuIV.ini` to change existing keybinds.
    ??? tip "Setting up Numpad-less keybinds"
        Not everyone has a Numpad, I get it, 80% (and less) keyboards are cool and comfortable. Open :material-file-cog:`ZMenuIV.ini` and locate these lines:

        ```{ .ini }
        [Keybinds]
        AirbreakUp=87
        AirbreakDn=83
        AirbreakForward=104
        AirbreakBack=98
        AirbreakLeft=100
        AirbreakRight=102
        MenuUp=104
        MenuDn=98
        MenuLeft=100
        MenuRight=102
        MenuEnter=101
        MenuBack=96
        ```

        and change them to:

        ```{ .ini }
        [Keybinds]
        AirbreakUp=32
        AirbreakDn=160
        AirbreakForward=87
        AirbreakBack=83
        AirbreakLeft=65
        AirbreakRight=68
        MenuUp=73
        MenuDn=75
        MenuLeft=74
        MenuRight=76
        MenuEnter=13
        MenuBack=220
        ```

        - Which will be:
            * ++i++++j++++k++++l++ for navigation. ++enter++ to accept, ++backslash++ to go back.
            * ++w++++a++++s++++d++ for horizontal airbreak control, ++space++ for going up and ++lshift++ for going down.

## Liberty's Legacy
!!! warning "Compatibility"
    This trainer is compatible with the Complete Edition, as well as patches 1.0.8.0 and 1.0.7.0.
This trainer is not as powerful as ZMenuIV, but still offers a lot of useful features, especially if you're playing with the Complete Edition.
???+ info "Installation"
    * Get the latest [Ultimate ASI Loader](../../mod-dependencies/#ultimate-asi-loader) and [ScriptHook](../../mod-dependencies/#scripthook).
    * Go to the [GTAForums page](https://gtaforums.com/topic/973091-gta-iv-12043-libertys-legacy-trainer/).
    * Download the latest version.
    * Extract :material-zip-box:`Liberty's Legacy Trainer xxx.zip` into the game folder.
???+ tip "Usage"
    - The default controls are: 
        * ++f11++ or RB+X/R1+Square to toggle menu.
        * Arrow keys or D-Pad for navigation. ++enter++ or A/X to accept, ++backspace++ or B/Circle to go back.
    
    Additional key bindings can be set by highlighting the desired option, pressing ++left-control+enter++ and pressing the key you want to bind.

## Simple Native Trainer
!!! warning "Compatibility"
    This trainer is compatible with all patches.
This trainer is less robust than the other two, but.. some people would want it, I guess.
???+ info "Installation"
    * Get the latest [Ultimate ASI Loader](../../mod-dependencies/#ultimate-asi-loader) and [ScriptHook](../../mod-dependencies/#scripthook).
    * Go to the [GTAForums page](https://gtaforums.com/topic/392973-ivrel-simple-trainer-for-gtaiv/).
    * Download latest version (it's somewhere in the post:material-trademark:).
    * Extract :material-file:`trainer.asi`, :material-file-cog:`trainer.ini`, :material-file:`trainertbogt.asi`, :material-file-cog:`trainertbogt.ini`, :material-file:`trainertlad.asi`, :material-file-cog:`trainertlad.ini` from :material-zip-box:`trainervxx.rar` into the game folder.
???+ tip "Usage"
    ++f3++ to open the menu, ++num8++, ++num2++, ++num4++, ++num6++ for navigation. Read the :material-file:`readme.doc` or the GTAForums page for instructions and keybinds.

[:material-page-first:Previous page <br>Multiplayer</br>](../multiplayer.md){ .md-button } [Next page:material-page-last: <br>Launcher</br>](launcher.md){ .md-button .md-button--primary }