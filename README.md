# Arc's Name Replacer
Arc' Name Replacer Version: 1.9.1

## Mod Description: 

This mod randomly selects non unique stalkers to give a special name taken from the names.txt file.

## Requirements
MAC (Mod app creator) https://www.moddb.com/mods/stalker-anomaly/addons/mod-app-creator-mac - required for tracker

## Installation: 
### Mo2:
1. Install MAC
2. Use Mo2 to install Arc's Name Replacer.7z (Load after MAC)
3. Place names.txt in the root of your ANOMALY directory (the same place where AnomalyLauncher.exe is)
4. Run the game

### Manual:
1. Install MAC
2. Extract Arc's Name Replacer.7z and copy paste gamedata folder into root directory
3. Place names.txt in the root directory (the same place where AnomalyLauncher.exe is)
4. Run the game


## MCM settings:

Spawn Chance (float 0-100)(default: 1) - Percentage chance for a stalker to be renamed.

Enable PDA Alerts (bool)(default: true) - Turn on/off PDA alerts for when a stalker is renamed.

Enable Death Alerts (bool)(default: true) - Toggle to turn on/off notifications when you kill a renamed stalker.

Generic Message Cooldown (float 0-60)(default:2) - Time in seconds between generic PDA alerts. Special named stalkers always notify regardless of this cooldown.

Enable Debug Logging (bool)(default: false) - Prints the remaining names in the pool and the current cooldown status to the log every 10 seconds.

Enable Map Markers (bool)(default: true) - Toggle to show a map marker for renamed stalkers until you meet or kill them.

## Changelog:

v1.9.1: Changed tracker works to be on LOS instead of interacting 

v1.9: Added tracker renamed stalkers, tracks last seen pos, status, name and faction

v1.8.2: Code cleaning and bug fixes

v1.8.1: Made hostiles no longer have markers

v1.8: Added toggleable map markers for renamed stalkers

v1.7: Added debugging tools

v1.6: Added cooldown for generic messages

v1.5.1: Added some more special messages 

v1.5: Fixed issue where npc could be renamed when joining/leaving squad

v1.4: Added death alerts when the player kills a renamed npc

v1.3: Made the mod more efficient

v1.2: Added some more PDA alerts 

v1.1: Added saving so that a name can only appear once in a save file

v1: Mod created




