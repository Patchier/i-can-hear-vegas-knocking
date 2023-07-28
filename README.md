# I Can Hear Vegas Knocking

July 27th, 2023 - Full Install: ~30GB.

**Modlist Support: [WIP]**


## OVERVIEW

This ReadMe is designed to help you with installing and beginning your adventures across the ruins of Las Vegas as a courier...or, perhaps, as something else?

## GOALS

-  Install and setup I Can Hear Vegas Knocking

-  The overall goal of ICHVK is to introduce fans of New Vegas to the amazing Alternate Start mod made available by hman101, and provide a new way to play the story...or perhaps ignore it altogether. 

## NOTABLE MODS

Alternate Start with Delayed Main Quest - The centerpiece of this modlist. You no longer start by getting shot in the head. Instead, you're someone else. Someone new. The main quest is began properly later. Have a look [here](https://www.nexusmods.com/newvegas/mods/82319)

New Blood - A modified version of the excellent BLEED mod, made by SweetSixShooter. Don't expect fights to feel the same as in vanilla! 

Stewie Tweaks - My own custom take on Stewie Tweaks, forked from the default for Viva New Vegas. However, the original INI is included if you wish to use it instead! I have made several important changes, such as allowing NPCs to Sneak Crit, allowing armor that is worn to be weightless, allowing NPCs to collect casings, overhauled pickpocketing, and a ton more. I suggest checking out "Tweaks" under "Settings" to see what I've done.

Hardcore Charisma - No longer a dump stat if you care at all about what factions think of you. Take a look [here](https://www.nexusmods.com/newvegas/mods/78448) for details.

Stash Organizer - In any interior cell, or player-owned exterior cell, press the VATS key on any contained to start what is probably the best sorting mod known to man. I actually recommend reading it yourself so you can see what all it does. Check it out [here](https://eddoursul.win/mods/stash-organizer/).

I have also set JIP to separate headgear DR/DT from body armor DR/DT, and included S6S' fix to ensure enemies aren't doming you with every shot. Still, you're gonna want some head coverage if you get into a fight in the open!

## SPECIFICATIONS

- Stash Organizer:
VATS key on an interior container

## First off, you will need:

-   A clean, fresh, and LEGAL GOG or Steam installation of Fallout: New Vegas

-   30GB free to install the list itself

## Install Fallout: New Vegas

- This part is self-explanatory. You'll want to go to the installation of the game, and remove all files present in the install folder (For example, steamapps/common/Fallout New Vegas) AND the Documents folder (Documents/My Games/FalloutNV).

### Uninstalling the game

If you have the games installed under `C:\Program Files\`, `C:\Program Files (x86)\`, your Desktop, or your Documents folders, follow these steps to remove it.

#### Steam

1. Open **Steam** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage** -> **Uninstall**.
4. Navigate to `Steam\steamapps\common\` and, if present, delete the **Fallout New Vegas** folder.

#### GOG

1. Open **GOG** and go to your **Library**.
2. Find **Fallout: New Vegas** in the list.
3. Right-click on it and select **Manage Installation** -> **Uninstall**.
4. Navigate to where the game was installed (`GOG Galaxy\Games` by default) and, if present, delete the **Fallout New Vegas** folder.

### Making a new Steam Library

If you already have a Steam library set up outside of any default Windows folder, or you have the game on GOG, skip this step.

A new Steam library needs to be set up to install the game on, as the default library is in a default Windows UAC-protected folder (`C:\Program Files (x86)\Steam`).

1. Open **Steam** and select **Steam** -> **Settings** in the top left.
2. In the **Downloads** tab, select **Steam Library Folders**.
3. Select **Add Library Folder** and select a location outside of any default Windows folders.
   * For example, `C:\Games\Steam`.
4. Exit out of the settings when you are finished.

By default, Steam only allows one library per drive, but there is a workaround. If for example you already have the default Steam library at `C:\Program Files (x86)\Steam`, but still want your game on your `C:\` drive, you will need to follow [these instructions](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to do so.

- While you're here, run the games once each, and after the launcher has detected your graphics settings, make any special adjustments you need, then you may close out of it. We just needed those initial INIs to be created.

Install I Can Hear Vegas Knocking via Wabbajack: 
----------------------------------------- 

1.  Download I Can Hear Vegas Knocking from my G-Drive (you've probably already done this part, but if not, link is at the top): 

2.  After that, you will choose an installation folder (I recommend something like "D:/I Can Hear Vegas Knocking", substituting D: for any drive available.) This CANNOT be where Wabbajack.exe is located, nor your Fallout New Vegas or Fallout 3 folder.

3.  Downloads will auto-populate for you, but you can change that location if you so choose. 

4.  From there, just click the "play" button and let it do the rest. If you do not have Nexus Premium, you will have to follow along to the manual download prompts.

5. Once the list has finished installing, open the folder you installed it to, and proceed to the "Game Folder Files" folder. 

6. Copy the items inside of the Game Folder Files folder to your Fallout: New Vegas installation location.
   
7. Once the files are copied over, run the FalloutNVpatch.exe. This will patch your New Vegas exe to be Large Address Aware, letting you enjoy the list with a severely decreased risk of crashing.

8. IMPORTANT: IF YOU'RE USING GOG, DELETE THE FNV-Lang.esp PLUGIN. 

## Starting the game

Once you've finished installing, simply navigate to your installation folder for the modlist and open ModOrganizer.exe. After that, you may launch the game via the New Vegas option, which should be selected for you in the top right corner. If not, simply choose it from the drop-down and click "run". If the launcher comes up to do graphics settings again, simply set your preferred settings, then exit out of the launcher and launch the game agan.

## DXVK

I recommend looking at [DXVK](https://www.nexusmods.com/newvegas/mods/79299) to see if you can utilize it. If you can, I strongly recommend installing it. The instructions are on the mod page.

## Performance Guide

This is less of a "recommendation" and more of a "threat". Look at this page, read it, and follow any directions you can. Wall worked very hard on ensuring that you can squeeze the most out of this engine. **Note: You absolutely should, at the very least, look into capping your framerate. 111fps seems to be the maximum that I've discovered without physics completely breaking on turrets.** Instructions are [here](https://wallsogb.github.io/FalloutNV-Performance-Guide/falloutnv.html).
