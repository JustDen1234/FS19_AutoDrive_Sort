# FS19 AutoDrive Sort

If you are playing FS19 with a steering wheel or (as I do) with a PS4 controller, and you like to cycle thru the destinations
you might noticed that AutoDrive (now v1.1.0.5-RC5) cycles thru the destinations by create date, not alphabetically.

So I created a small console app (C#) that sorts the destinations alphabetically.

## Usage

Copy the .exe into your savegame directory. Run it, it will look for the xml file of AutoDrive, and sorts the destinations.
Next it will open the vehicles.xml file, and change the parking destination of all vehicles (and work tools) to the new sorted destination number.

It also copies the old xml files so you'll have a backup. If you want to test it, but not sure how it works, copy the autodrive and vehicles xml files
to another directory and run this program in that directory.

Note... you'll need to save your game and close the game to make it work (no need to fully quit FS19).



Program is based on [.net framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472).

---
Happy farming,

JustDen

