# FS19 AutoDrive Sort

If you are playing FS19 and like to cycle thru the destinations with the keyboard, a button on a steering wheel or (as I do) with a PS4 controller, 
you might noticed that AutoDrive (now v1.1.0.5-RC5) cycles thru the destinations in the order you created them, not alphabetically.

So I created a small program that sorts the destinations alphabetically.

## Usage

Just copy the AutoDriveSort.exe into your savegame directory and run it.

First it will look for the AutoDrive xml file (named 'AutoDrive_[mapname]_config.xml'), and sorts the destinations.
Next it will open the vehicles.xml file, and change the parking destination of all vehicles (and work tools) to the new sorted destination number.
Also the chosen destinations for every vehicle in the HUD will be set to the new numbers.

And... the original xml files will be backed up.

Note... you'll need to save and close your game before sorting (no need to fully quit FS19).

## Download

[Latest version v1.0.5](https://github.com/JustDen1234/FS19_AutoDrive_Sort/releases/download/1.0.5/AutoDriveSort.exe)

Program is based on [.net framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472).

---
Happy farming,

JustDen

