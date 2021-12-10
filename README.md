
[index]: #index "Back to top"
[terms-of-service]: https://support.na.square-enix.com/rule.php?id=5382&la=1 "Terms of service"
[discord]: https://discord.gg/7TJG9H8Xyf "Join us on Discord"
[download]: https://www.nexusmods.com/finalfantasy14/mods/1054?tab=files "Download on nexusmods.com"
[custom-menu-gif]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/custom-menu-trans.gif "Custom Menu"
[install-youtube]: https://www.youtube.com/watch?v=CnjSLgj-9QE "Youtube video on how to install"
[install-picture]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png "Picture on how to install"

# Fr4nsson's FFXIV Config (FFC) | [Discord][discord] | [Download][download]
A complete config for FFXIV with a clean informational HUD layout. All jobs have their spells already assigned to hotbars. No files have been modified or created by third-party applications, all the files have been created and modified by the game. This is not against [TOS][terms-of-service], it is 100% safe to use.

## Index

1. [About](#about)
2. [Installation](#installation--youtube--picture-)
3. [What each files does](#what-each-files-does-)
4. [Custom Menu](#custom-menu--)
   1. [non-pvp](#non-pvp-areas-)
   2. [pvp](#pvp-areas-wolves-den-pier-)
5. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq-)

## About

This is a complete config for FFXIV that I've been working on for a very long time. It is very time consuming to figure out a good hud layout and then position all the hud elements and after that is done come up with good keybinds for your jobs, and if possible, keybinds that fits logically with other similar spells between jobs and remember, ffxiv has 20 jobs as I'm writing this (31 with professions included).

When you take all that into consideration it is not something that is easily done or something that you'd manage to do right away, it would take a lot of trial and error and you would change binds over time. I've done that journey for you so you can focus on playing the game instead. If you're one that likes to fiddle around with hud and keybinds and find enjoyment in that, like I do, this is probably not for you. This is for the people that don't wanna deal with that.

Obviously not everyone might like the layout or the keybinds, there may also be some stuff that I've missed or some spells that would fit better in a different slot. This is a work in progress after all. If you have any suggestions for improvements, feel free to post it.

## Installation | [Youtube][install-youtube] | [Picture][install-picture] <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. Backup your current config, installing this config will overwrite almost everything you have.
3. [Download][download] the correct resolution config
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

## Custom Menu <sup>[⮝][index]</sup> ![][custom-menu-gif]
The menu works by using jobs as a database and then assigning items, macros or gearsets to a hidden hotbar you normally don't use so if you want to change what appears in the menu you'll have to unlock some jobs. You don't need to grab the jobs in order to use the menu, you only need to do that in order to edit the menu. 

The logic behind the menu can be found under <code>ALT + U -> Shared Tab</code>

In order to change what is in the menu you need to change to the job that holds the information you're trying to change and press <code>9</code>.
A hidden hotbar (database hotbar) will appear in the top center of the screen on which you can drag other macros, items, gearsets, mounts or whatever to, when you're done with the changes press <code>9</code> again to toggle the visibility of the database hotbar.

Below is the currently used jobs, what information they contain in the database and where to get them. Switch to a job listed below and press <code>9</code> to toggle the database for that job.

#### Non-PvP Areas <sup>[⮝][index]</sup>

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

#### PvP Areas *(Wolves' Den Pier)* <sup>[⮝][index]</sup>

| Job           | Information | Quest                    | Quest Giver     | Location                               |
| ------------- | ----------- | ------------------------ | --------------- | -------------------------------------- |
| Bard          | Expand      | Way of the Archer        | Athelyna        | New Gridania (x15,y12)                 |
| Machinist     | Collapse    | Savior of Skysteel       | Stephanivien    | Ishgard - Foundation (x8.1,y10.1)      |
| Dancer        | Dps         | Shall We Dance           | Eager Lominsan  | Limsa Lominsa Lower Decks (x9.8,y12.0) |
| Red Mage      | Tank        | Taking the Red           | Distraught Lass | Ul'dah - Steps of Thal (x14.1,y11.7)   |
| Black Mage    | Healer      | Way of the Thaumaturge   | Yayake          | Ul'dah - Steps of Nald (x7.3,y12.4)    |

## Frequently Asked Questions (FAQ) <sup>[⮝][index]</sup>

> <details><br>
> <summary>What version am I using?</summary>
> You can always view your current version of the config by opening the macro menu by pressing 
> <code>ALT + U</code> go to the <code>Shared Tab</code> and in the bottom right check the macro with the <code>Bread Icon</code>. Compare it to the newest version on nexusmods to see if you have the current one.
</details>

> <details><br>
> <summary>Is this against TOS? can I get banned for using this?</summary>
> No, this is not even a mod, it's only a config so it is 100% safe to use. There is no external files added, all the files have been created by the game and modified by the game. No files have been modified or created by third-party applications.
</details>

> <details><br>
> <summary>I've added the Sage and/or Reaper to the menu but it doesn't save, every time I switch it reverts back</summary>
> If you want to include Sage in the custom menu you need to
> 
> 1. Switch to job <code>Alchemist</code> (Alchemist job holds database information regarding healer jobs in non-pvp areas)
> 2. Press <code>9</code> a new hotbar will appear in the top center of the screen
> 3. Press <code>SHIFT+G</code> to bring up your gearsets, and drag the sage gearset onto the top center hotbar
> 4. Press <code>9</code> again to toggle the visibility of the top center hotbar
> 
> For Reaper you will follow the exact steps above, just replace <code>Alchemist</code> with <code>Fisher</code>. 
> 
> To do this in pvp-areas, tp to <code>Wolves' Den Pier</code> and follow the exact steps above but replace <code>Alchemist</code> with <code>Black Mage (Healer)</code> & <code>Dancer (Dps)</code> 
> 
> For more information on how the custom menu works, see [Custom Menu](#custom-menu--).
</details>

> <details><br>
> <summary>In expandable menu, when I click on job change icon, nothing happens, whats wrong?</summary>
> Wrong gearset name, make sure at least one of each job has a gearset with default name, for example gunbreaker gearset should be <code>GNB(ilvl)</code> If this happens in PvP areas it's because you're not currently a compatible job for PvP, i.e. professions and blue mage won't work in pvp area with custom menu since they don't have pvphotbars, switch to a compatible job by bringing up gearset menu <code>SHIFT + G</code>.
</details>
