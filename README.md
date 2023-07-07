
[index]: #index "Back to top"
[terms-of-service]: https://support.na.square-enix.com/rule.php?id=5382&la=1 "Terms of service"
[discord]: https://discord.gg/7TJG9H8Xyf "Join us on Discord"
[download]: https://www.nexusmods.com/finalfantasy14/mods/1054?tab=files "Download on nexusmods.com"

[general-idea]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/general-idea.png "General Idea"
[main-hotbar]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/main-hotbar.png "Main Hotbar"
[install-trans]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png "Installation"
[install-console-char-screen]: https://raw.githubusercontent.com/Fr4nsson/FFXIV-Config/main/images/installation_console_character_screen.png "Character Screen"

[custom-menu-gif]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/custom-menu.gif "Custom Menu"
[install-youtube]: https://www.youtube.com/watch?v=CnjSLgj-9QE "Youtube video on how to install"
[install-picture]: https://github.com/Fr4nsson/FFXIV-Config/raw/main/images/installation.png "Picture on how to install"
[comprehensive-controller-guide]: https://docs.google.com/document/d/1q_i5_X01hecbCOZOIN_71zceuSjWSuaN-OJdU6ZPV6s "Comprehensive Controller Guide"

# Fr4nsson's FFXIV Config (FFC) | [Discord][discord] | [Download][download]
A complete config for FFXIV with a clean informational HUD layout. All jobs have their spells already assigned to hotbars. No files have been modified or created by third-party applications, all the files have been created and modified by the game. This is not against [TOS][terms-of-service], it is 100% safe to use.

## Index

1. [About](#about)
2. [Main Hotbar](#main-hotbar-)
3. [General Idea](#general-idea-)
4. [Backup](#backup-)
5. [Installation (PC)](#installation-pc-)
6. [Installation (Console)](#installation-console-)
7. [What each files does](#what-each-files-does-)
8. [Custom Menu](#custom-menu-)
   1. [non-pvp](#non-pvp-areas-)
   2. [pvp](#pvp-areas-wolves-den-pier-)
9. [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq-)
10. [V2.4 Hotbar Layouts](https://github.com/Fr4nsson/FFXIV-Config/tree/main/2_4/hotbar_layouts)
11. [Keybinds](#keybinds-)
    1. [inventory](#inventory-)
    2. [mount](#mount-)
    3. [stance & weapon](#stance--weapon-)
    4. [marking targets](#marking-targets--combat-related-mostly-used-when-playing-as-tank-)
    5. [chat](#chat-)
    6. [general](#general-)
    7. [hud](#hud-)
12. [Controller](#controller--comprehensive-controller-guide-)

## About

This is a complete config for FFXIV that I've been working on for a very long time. It is very time consuming to figure out a good hud layout and then position all the hud elements and after that is done come up with good keybinds for your jobs, and if possible, keybinds that fits logically with other similar spells between jobs and remember, ffxiv has 20 jobs as I'm writing this (31 with professions included).

When you take all that into consideration it is not something that is easily done or something that you'd manage to do right away, it would take a lot of trial and error and you would change binds over time. I've done that journey for you so you can focus on playing the game instead. If you're one that likes to fiddle around with hud and keybinds and find enjoyment in that, like I do, this is probably not for you. This is for the people that don't wanna deal with that.

Obviously not everyone might like the layout or the keybinds, there may also be some stuff that I've missed or some spells that would fit better in a different slot. This is a work in progress after all. If you have any suggestions for improvements, feel free to post it on [discord][discord].

## Main Hotbar <sup>[⮝][index]</sup>
![main-hotbar][main-hotbar]

## General Idea <sup>[⮝][index]</sup>
![general-idea][general-idea]

## Backup <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. Navigate to your ffxiv config location on your computer, it is usually under<br>
   <code>Documents\My Games\FINAL FANTASY XIV - A Realm Reborn</code>
3. Make a copy of the following items and put them somewhere safe<br>
   <code>FFXIV.cfg</code><br>
   <code>FFXIV_CHR</code> folders
5. Done

## Installation (PC) <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. [Download][download] the config from nexusmods.
3. Run the installer, the installer will automatically make backups of your current characters and restore them from backup incase at some point you would uninstall the config.
4. If you don't have the runtime you will be prompted to download it first time running the installer. On [Microsoft's website](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime?cid=getdotnetcore), choose <code>Run desktop apps</code> and then choose the correct one for your system, usually <code>x64</code>. After the runtime has been installed you can run the FFC installer again.
6. Check the shortcut that was placed on your desktop.
7. Done. :tada:

## Manual Installation (PC) | [Youtube][install-youtube] | [Picture][install-picture] <sup>[⮝][index]</sup>
1. Make sure the game is not running! 
2. [Backup](#backup-) your current config, installing this config will overwrite almost everything in your current config.
3. [Download][download] the config from nexusmods.
4. Navigate to your ffxiv config location on your computer, it is usually under<br>
  <code>Documents\My Games\FINAL FANTASY XIV - A Realm Reborn</code>
5. Open the zip file you downloaded.
6. Open the <code>Manual Installation</code> folder.
7. Extract <code>FFXIV.cfg</code> into <code>FINAL FANTASY XIV - A Realm Reborn</code> folder and replace when prompted.
8. Rename one of the <code>Addon_RESOLUTION.dat</code> inside <code>CharacterData</code> to just <code>Addon.dat</code> and delete the other <code>Addon_RESOLUTION.dat</code>'s.
9. Extract files INSIDE of <code>CharacterData</code> into each folder starting with <code>FFXIV_CHR</code> and replace when prompted.
10. Read the <code>README.txt</code> which came with the zip, it contains important information you need to know.
11. Done. :tada: 

![Installation][install-trans]

## Installation (Console) <sup>[⮝][index]</sup>
You need to buy at least starter edition on pc (yes, even if you have already bought a license on console) and follow the steps below
#### What to do on pc
1. Buy at least starter edition on pc (for the same account you use for the console).
2. Install the game.
3. Completely log into the character(s) you want the config on.
4. Completely exit the game.
5. [Download][download] and install config from nexusmods.
   * See section [Installation (PC)](#installation-pc-) on how to install for PC.
7. Log back in on any character that you logged into in <code>step 3</code> and verify that the config did install correctly.
8. Log out to the character screen (Do not exit game).
9. On the character screen, click the cog wheel in the top right corner <code>Back Up CLIENT Settings</code>.
   * Choose <code>Proceed</code>, <code>Upload</code>, <code>Ok</code>.
   * You will get a message saying _Client Settings data saved to the server_.
10. On the character screen, click the cog wheel in the top right corner next to character <code>Back Up CHARACTER Settings</code>
   * Choose <code>Proceed</code>, <code>Upload</code>, <code>Ok</code>.
   * You will get a message saying _Character Settings for X successfully uploaded to the server_.
11. Repeat <code>step 9</code> on each character you want the config on.
12. PC done, go to your console and follow the rest of the steps below.

![Character Screen][install-console-char-screen]

#### What to do on console
1. On the character screen, click the cog wheel in the top right corner <code>Back Up CLIENT Settings</code>.
   * Choose <code>Proceed</code>, <code>Download</code>, <code>Ok</code>.
   * Please note that on console you choose download and not upload.
2. On the character screen, click the cog wheel in the top right corner next to character <code>Back Up CHARACTER Settings</code>.
   * Choose <code>Proceed</code>, <code>Download</code>, <code>Ok</code>.
   * Please note that on console you choose download and not upload.
3. Repeat <code>step 2</code> on each character you want the config on.
4. Restart the game.
5. Log back in on any character that you downloaded the config to in step <code>2</code> and verify that the config did install correctly.
6. Done. :tada:

## What each files does <sup>[⮝][index]</sup>
<pre>
Fr4nsson's FFXIV Config.zip
|
|- Fr4nsson's FFXIV Config Installer.exe : Automatic install/backup
   Manual Installation
   |
   |- FFXIV.cfg                          : Settings in System Configuration.
   |- CharacterData
      |
      |- ADDON.DAT                       : UI Settings such as HUD and window layouts.
      |- ADDON_1080_100.DAT              : 1920x1080, 100% Scaling, rename to ADDON.DAT if you want this resolution.
      |- ADDON_1440_100.DAT              : 2560x1440, 100% Scaling, rename to ADDON.DAT if you want this resolution.
      |- ADDON_1440_150.DAT              : 2560x1440, 150% Scaling, rename to ADDON.DAT if you want this resolution.
      |- ADDON_2160_200.DAT              : 3840x2160, 200% Scaling, rename to ADDON.DAT if you want this resolution.
      |- COMMON.DAT                      : Settings in Character Settings.
      |- CONTROL0.DAT                    : Keyboard/mouse mode settings.
      |- CONTROL1.DAT                    : Gamepad mode settings.
      |- HOTBAR.DAT                      : Hotbar content, (spells placed on hotbars).
      |- KEYBIND.DAT                     : Keybinds.
      |- LOGFLTR.DAT                     : Chat log filter settings.
      |- MACRO.DAT                       : Macros (Individual Tab).
</pre>

## Custom Menu <sup>[⮝][index]</sup>
![][custom-menu-gif]

The menu works by using jobs as a database and then assigning items, macros or gearsets to a hidden hotbar you normally don't use so if you want to change what appears in the menu you'll have to unlock some jobs. You don't need to grab the jobs in order to use the menu, you only need to do that in order to edit the menu. 

The logic behind the menu can be found under <code>ALT + M -> Individual Tab</code>

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

<details><p></p>
<summary>What version am I using?</summary>
You can always view your current version of the config by opening the macro menu 
<code>ALT + M</code> and in the bottom right check <code>Macro #99</code>. Compare the version number to the newest version on nexusmods to see if you have the most current one.
<br><br><br><br><br><br></details>

<details><p></p>
<summary>Is this against TOS? can I get banned for using this?</summary>
No, this is not even a mod, it's only a config so it is 100% safe to use. There is no external files added, all the files have been created by the game and modified by the game. No files have been modified or created by third-party applications.
<br><br><br><br><br><br></details>

<details><p></p>
<summary>Does this config work on console, PS4, PS5 etc?</summary>

Yes it does, see [Installation (Console)](#installation-console-).
<br><br><br><br><br><br></details>

<details><p></p>
<summary>I've added the Sage and/or Reaper to the menu but it doesn't save, every time I switch it reverts back</summary>
If you want to include Sage in the custom menu you need to

1. Switch to job <code>Alchemist</code> (Alchemist job holds database information regarding healer jobs in non-pvp areas)
2. Press <code>9</code> a new hotbar will appear in the top center of the screen
3. Press <code>SHIFT + G</code> to bring up your gearsets, and drag the sage gearset onto the top center hotbar
4. Press <code>9</code> again to toggle the visibility of the top center hotbar

For Reaper you will follow the exact steps above, just replace <code>Alchemist</code> with <code>Fisher</code>. 

To do this in pvp-areas, tp to <code>Wolves' Den Pier</code> and follow the exact steps above but replace <code>Alchemist</code> with <code>Black Mage (Healer)</code> & <code>Dancer (Dps)</code> 

For more information on how the custom menu works, see [Custom Menu](#custom-menu-).
<br><br><br><br><br><br></details>

<details><p></p>
<summary>In expandable menu, when I click on job change icon, nothing happens, whats wrong?</summary>
Wrong gearset name, make sure at least one of each job has a gearset with default name, gunbreaker gearset should be <code>Gunbreaker</code> for example.
<br>
<br>
With the release of patch <a href="https://na.finalfantasyxiv.com/lodestone/topics/detail/c73cd284013587066d8f9e697fab1db9f007372c#random-d49d098fa34f4ecc258f72c73b183c243f94d26e">6.1</a> there was some changes with gearset names too, before the default name was <code>GNB(ilvl)</code> but now it is just <code>Gunbreaker</code> for english language. <b>Important!</b>, if you're playing the game with a non-english language you need to make sure your gearset names all matches the names used for the autotranslation in order for the job macros to work. You can check the autotranslation by opening the macro menu <code>ALT+U</code> and then clicking on a job change macro and checking the name. For example, French players need to make their gearset names in all lowercase letters in order for the autotranslation in the job macros to work.
<br>
<br>
If this happens in PvP areas it's because you're not currently a compatible job for PvP, i.e. professions and blue mage won't work in pvp area with custom menu since they don't have pvphotbars. 
<br>
Switch to a compatible job by bringing up gearset menu <code>SHIFT + G</code>.
<br><br><br><br><br><br></details>

## Keybinds <sup>[⮝][index]</sup>

#### Inventory <sup>[⮝][index]</sup>
```
I                   = Open all bags
SHIFT + B           = Open character screen, armoury chest and all bags and sort them (I mostly use this one)
SHIFT + I           = Open Chocobo Saddlebag
CTRL  + I           = Armoury Chest
```
#### Mount <sup>[⮝][index]</sup>
```
ALT   + H           = Ridepillion
SHIFT + H           = Single Seat Mount
CTRL  + H           = Multiple Seat Mount
```
#### Stance & Weapon <sup>[⮝][index]</sup>
```
Z                   = Sheathe/Unsheathe Weapon
SHIFT + Z           = Change stance (Try it when holding a weapon, sitting or just standing with weapon sheathed)
```
#### Marking Targets / Combat Related (Mostly used when playing as Tank) <sup>[⮝][index]</sup>
```
ALT   + 1           = Mark primary target to attack
ALT   + 2           = Mark secondary target to attack
ALT   + X           = Mark target to ignore
ALT   + F           = Set Focus Target
ALT   + R           = Ready Check
ALT   + C           = Countdown
CTRL  + M           = Waymark Menu
SHIFT + M           = Signs Menu
```
#### Chat <sup>[⮝][index]</sup>
```
ALT   + S           = Switch chat mode to Say
ALT   + Y           = Switch chat mode to Yell
CTRL  + Y           = Temporarily switch chat mode to Shout
ALT   + P           = Switch chat mode to Party
ALT   + A           = Switch chat mode to Alliance / Raid
ALT   + G           = Switch chat mode to Free Company / Guild
SHIFT + ENTER       = Chat fullscreen
```
#### General <sup>[⮝][index]</sup>
```
8                   = Toggle Keybind bar
9                   = Toggle Database bar
L                   = Limit Break
Mouse5              = Confirm (Used to spam through dialog or spam it when turning in items for seals at GC) 
NUMPAD 0            = Confirm (Used to spam through dialog or spam it when turning in items for seals at GC)
Mouse4              = Cancel
Mouse3              = Auto-run
NUMPAD 1            = Toggle spell effects/names
NUMPAD 2            = Toggle spell effects/names
NUMPAD 3            = Toggle spell effects/names
NUMPAD 4            = Toggle spell effects/names
NUMPAD 5            = Toggle spell effects/names
INSERT              = Toggle spell effects/names, preset 1 (all)
DELETE              = Toggle spell effects/names, preset 3 (limited)
HOME                = Return
CTRL + HOME         = Return (Eternity Ring)
END                 = Teleport Menu
Print Screen        = Screenshot
ALT + M             = Macro Menu
ALT + NUMPAD PLUS   = Continuously increase volume until stopped by pressing NUMPAD -
NUMPAD -            = Stop volume increase (Macro cancel)
NUMPAD +            = Toggle Master Volume On/Off
NUMPAD *            = Helm Visor
NUMPAD /            = RP Walk
SHIFT + G           = Gear sets
G                   = Free Company / Guild Menu
H                   = Housing Menu
J                   = Journal / Quest Log
K                   = Key items
O                   = Friend list
SHIFT + O           = Party Members
CTRL  + O           = Party Finder
CTRL  + L           = Cross-world Linkshells
U                   = Duty Finder
P                   = Spells
SHIFT + P           = PvP Spells
, (comma)           = Currency
. (dot)             = Challenge Log
```
#### Hud <sup>[⮝][index]</sup>
```
Scroll Lock         = Toggle visibility for ALL hud elements (Nice for screenshots)
SHIFT + Scroll Lock = Toggle visibility on some hud elements (Clean Hud)
Arrow Keys          = Select a hud element in hud editor and use key to move hud element by pixel
CTRL + NUMPAD 0     = Toggle Hud Editor

Only 1080p and 2160p versions have the below hud presets!

CTRL + NUMPAD 1     = Hud Preset 1, config default (The one I play with)
CTRL + NUMPAD 2     = Hud Preset 2, larger
CTRL + NUMPAD 3     = Hud Preset 3, like Hud Preset 1, gauges and hp reversed
CTRL + NUMPAD 4     = Hud Preset 4, like Hud Preset 2, gauges and hp reversed
```
## Controller | [Comprehensive Controller Guide][comprehensive-controller-guide] <sup>[⮝][index]</sup>
```
Autorun
Left Analog Stick (Move It) then press L1

Sheathe/Unsheathe Weapon
L1 + R1 or L3

Sprint
R3 or double tap L2 then Dpad Up

Virtual Mouse
L1 + R3

Zoom In/Out
L1 + Right Analog Stick (Move It)
```
