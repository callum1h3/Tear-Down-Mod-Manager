# Tear Down Mod Manager

This mod manager allows mod developers to switch to different mods they are working on in one or two clicks. You can create mods using the UI, it will create a template file allowing you to put your lua files inside of the mod.

## Features

* Simple mod creation support.
* Allows mods you to enable multiple mods at the same time.
* It reverts all of the lua file changes done to the main games path.

## How to Use

First when installing the install file you need to set the mod path of your Tear Down root folder, this will be in your steamapps folder. 

After that you can go to the Mod Path location to add any mods you find on the internet.

If you want to create your own mod you can press the new mod button, this will create a template mod. It is important not to override any map files that are already in the game for example renaming your map to "lee". You can put code onto of the three main game files: messages, game and missions. These will put code ontop of them files not replace the files. For example if you want to add your map to the sandbox array, you will need to use table.insert to add your map to the array. You can add your own map with .vox files for the map and scripts for your map.


This mod manager should only be used until workshop support for the game comes out.
