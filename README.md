[custommenugif]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/custom-menu-trans.gif "Custom Menu"
[index]: #index "Back to top"

# Fr4nsson's FFXIV Config (FFC) | [**Discord**](https://discord.gg/7TJG9H8Xyf) | [**Download**](https://www.nexusmods.com/finalfantasy14/mods/1054?tab=files)
A complete config for FFXIV with a clean informational HUD layout. All jobs have their spells already assigned to hotbars. No files have been modified or created by third-party applications, all the files have been created and modified by the game. This is not against [**TOS**](https://support.na.square-enix.com/rule.php?id=5382&la=1), it is 100% safe to use.

## Index

1. [About](#about)
2. [Installation](#installation--video--picture-)
3. [What each files does](#what-each-files-does-)
4. [Custom Menu](#custom-menu--)
   1. [non-pvp](#non-pvp-areas-)
   2. [pvp](#pvp-areas-wolves-den-pier-)
5. test
6. test

## About

This is a complete config for FFXIV that I've been working on for a very long time. It is very time consuming to figure out a good hud layout and then position all the hud elements and after that is done come up with good keybinds for your jobs, and if possible, keybinds that fits logically with other similar spells between jobs and remember, ffxiv has 20 jobs as I'm writing this (31 with professions included).

When you take all that into consideration it is not something that is easily done or something that you'd manage to do right away, it would take a lot of trial and error and you would change binds over time. I've done that journey for you so you can focus on playing the game instead. If you're one that likes to fiddle around with hud and keybinds and find enjoyment in that, like I do, this is probably not for you. This is for the people that don't wanna deal with that.

Obviously not everyone might like the layout or the keybinds, there may also be some stuff that I've missed or some spells that would fit better in a different slot. This is a work in progress after all. If you have any suggestions for improvements, feel free to post it.

## Installation | [**Video**](https://www.youtube.com/watch?v=CnjSLgj-9QE) | [**Picture**](https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png) <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. Backup your current config, installing this config will overwrite almost everything you have.
3. <a href="https://www.nexusmods.com/finalfantasy14/mods/1054?tab=files">Download</a> the correct resolution config
4. Navigate to your ffxiv config location on your computer, it is usually under<br>
  <code>Documents\My Games\FINAL FANTASY XIV - A Realm Reborn</code>
5. Open the zip file you downloaded 
6. Extract <code>FFXIV.cfg</code> and <code>MACROSYS.dat</code> into <code>FINAL FANTASY XIV - A Realm Reborn</code> folder and replace when prompted.
7. Extract files INSIDE of <code>CharacterData</code> into each folder starting with <code>FFXIV_CHR</code> and replace when prompted.
8. Done

## What each files does <sup>[⮝][index]</sup>
<pre>
Fr4nsson's FFXIV Config.zip
|
|- FFXIV.cfg       : Settings in System Configuration.
|- MACROSYS.DAT    : Macros (Shared Tab).
|- CharacterData
   |
   |- ADDON.DAT    : UI Settings such as HUD and window layouts.
   |- COMMON.DAT   : Settings in Character Settings.
   |- CONTROL0.DAT : Keyboard/mouse mode settings.
   |- CONTROL1.DAT : Gamepad mode settings.
   |- HOTBAR.DAT   : Hotbar content, (spells placed on hotbars).
   |- KEYBIND.DAT  : Keybinds.
   |- LOGFLTR.DAT  : Chat log filter settings.
   |- MACRO.DAT    : Macros (Individual Tab).
</pre>

## Custom Menu <sup>[⮝][index]</sup> ![][custommenugif]
The menu works by using jobs as a database and then assigning items, macros or gearsets to a hidden hotbar you normally don't use so if you want to change what appears in the menu you'll have to unlock some jobs. You don't need to grab the jobs in order to use the menu, you only need to do that in order to edit the menu. 

*The logic behind the menu and the macros is found under <code>ALT + U -> Shared Tab</code>*

In order to change what is in the menu you need to change to the job that holds the information you're trying to change and press <code>9</code>.
A hidden hotbar (database hotbar) will appear in the top center of the screen on which you can drag other macros, items, gearsets, mounts or whatever to, when you're done with the changes press <code>9</code> again to toggle the visibility of the database hotbar.

Below is the currently used jobs, what information they contain in the database and where to get them. Switch to a job listed below and press <code>9</code> to toggle the database for that job.

### Non-PvP Areas <sup>[⮝][index]</sup>

| Job           | Information | Quest                    | Quest Giver | Location                              |
| ------------- | ----------- | ------------------------ | ----------- | ------------------------------------- |
| Botanist      | Expand      | Way of the Botanist      | Leonceault  | Old Gridania (x6.4, y8.3)             |
| Miner         | Collapse    | Way of the Miner         | Linette     | Ul'dah - Steps of Thal (x11,y14)      |
| Fisher        | Dps         | Way of the Fisher        | N'nmulika   | Limsa Lominsa Lower Decks (x7,y14)    |
| Culinarian    | Tanks       | Way of the Culinarian    | Charlys     | Limsa Lominsa Upper Decks (x9,y7)     |
| Alchemist     | Healers     | Way of the Alchemist     | Deitrich    | Ul'dah - Steps of Thal (x9, y13)      |
| Weaver        | Professions | Way of the Weaver        | Maronne     | Ul'dah - Steps of Thal (x13.9, y13.2) |
| Leatherworker | Items       | Way of the Leatherworker | Randall     | Old Gridania (x12.5, y8.2)            |
| Goldsmith     | Hunt        | Way of the Goldsmith     | Jemime      | Ul'dah - Steps of Thal (x10, y13)     |
| Armorer       | Misc2       | Way of the Armorer       | G'wahnako   | Limsa Lominsa Upper Decks (x10,y15)   |
| Blacksmith    | Misc1       | Way of the Blacksmith    | Randwulf    | Limsa Lominsa Upper Decks (x10,y15)   |

### PvP Areas *(Wolves' Den Pier)* <sup>[⮝][index]</sup>

| Job           | Information | Quest                    | Quest Giver     | Location                               |
| ------------- | ----------- | ------------------------ | --------------- | -------------------------------------- |
| Bard          | Expand      | Way of the Archer        | Athelyna        | New Gridania (x15,y12)                 |
| Machinist     | Collapse    | Savior of Skysteel       | Stephanivien    | Ishgard - Foundation (x8.1,y10.1)      |
| Dancer        | Dps         | Shall We Dance           | Eager Lominsan  | Limsa Lominsa Lower Decks (x9.8,y12.0) |
| Red Mage      | Tank        | Taking the Red           | Distraught Lass | Ul'dah - Steps of Thal (x14.1,y11.7)   |
| Black Mage    | Healer      | Way of the Thaumaturge   | Yayake          | Ul'dah - Steps of Nald (x7.3,y12.4)    |


