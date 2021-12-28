## NOTE: AutoDrive Sort for FS22 is out now: [FS22_AutoDrive_Sort](https://github.com/JustDen1234/FS22_AutoDrive_Sort)

# FS19 AutoDrive Sort (v1.4.0)

If you are playing FS19 and like to cycle thru the destinations with the keyboard, a button on a steering wheel or (as I do) with a PS4 controller, 
you might noticed that AutoDrive cycles thru the destinations in the order you created them, not alphabetically.

So I created a small program that sorts the destinations alphabetically. Also taking the folders in account if you use folders.

## Usage

New in v1.4.0:
---
1. Create a shortcut to AutoDriveSort.exe, and add one of more of the arguments below:  
   -dir [savegame folder]
   -backups [number of backups to keep]  

   Examples:  
     D:\AutoDriveSort.exe -dir "C:\Data\Documents\My Games\FarmingSimulator2019\savegame1"  
     D:\AutoDriveSort.exe -dir "C:\Data\Documents\My Games\FarmingSimulator2019\savegame1"  -backups 2

1. Save and close your game (no need to quit FS19).
1. Run the shortcut.


Only in v1.3.0:
---
1. Create a shortcut to AutoDriveSort.exe, and add the savegame folder as an argument.  
   Example: D:\AutoDriveSort.exe "C:\Data\Documents\My Games\FarmingSimulator2019\savegame1"  
1. Save and close your game (no need to quit FS19).
1. Run the shortcut.


OR:
---

1. Save and close your game (no need to quit FS19).
1. Copy the AutoDriveSort.exe into your savegame folder (mostly: C:\Users\[username]\Documents\My Games\FarmingSimulator2019\savegame[number]\).
1. Run it.



## How does it work?

1. It will look for the AutoDrive xml file (named 'AutoDrive_config.xml').
1. Creates a backup.
1. Looks into the file if you are using folders (if in AD settings you have 'Use folders' set to Yes).
   1. If you use folders, it will take the folders into account when sorting.
   1. If you do not use folders, it will just sort all destinations.
1. Look for the 'vehicles.xml' file.
1. Create a backup of this file.
1. Fix the parking destinations of all vehicles and work tools to the sorted destinations.
1. Fix the chosen destinations for every vehicle in the HUD to the sorted destinations.

## Download

[Latest version v1.4.0](https://github.com/JustDen1234/FS19_AutoDrive_Sort/releases/download/1.4.0/AutoDriveSort.exe)

[![Github All Releases](https://img.shields.io/github/downloads/JustDen1234/FS19_AutoDrive_Sort/total.svg)]()

Program is based on [.net framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472).

---
Happy farming,

JustDen


