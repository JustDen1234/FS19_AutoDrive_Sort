# FS19 AutoDrive Sort

If you are playing FS19 and like to cycle thru the destinations with the keyboard, a button on a steering wheel or (as I do) with a PS4 controller, 
you might noticed that AutoDrive (now v1.1.0.6) cycles thru the destinations in the order you created them, not alphabetically.

So I created a small program that sorts the destinations alphabetically. Also taking the folders in account if you use folders.

## Usage

1. Save and close your game (no need to quit FS19).
1. Copy the AutoDriveSort.exe into your savegame folder.
1. Run it.

## How does it work?

1. It will look for the AutoDrive xml file (named 'AutoDrive_config.xml').
1. Creates a backup.
1. Looks into the file if you are using folders (if in AD settings you have 'Use folders' set to Yes).
   1. If you use folders, it will take the folders into account when sorting.
   1. If you do not use folders, it will just sort all destinations.
1. Look for the 'vehicles.xml' file.
1. Create a backup of this file.
1. Change the parking destinations of all vehicles and work tools to the new sorted destination number.
1. Set the chosen destinations for every vehicle in the HUD to the new numbers.

## Download

[Latest version v1.1.0](https://github.com/JustDen1234/FS19_AutoDrive_Sort/releases/download/1.1.0/AutoDriveSort.exe)

[Version for AutoDrive v1.1.0.5-RC5 (and previous)](https://github.com/JustDen1234/FS19_AutoDrive_Sort/releases/download/1.0.6/AutoDriveSort.exe)

Program is based on [.net framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472).

---
Happy farming,

JustDen

