# FS19 AutoDrive Sort

I'm playing FS19 with a PS4 Controller, and like to cycle thru the destinations using the controller, 
but AutoDrive (now v1.1.0.5-RC5) cylces thru the destination by adding date, not alphabetically.

So I created a small console app (C#) that does the sort for me.

## Usage

Copy the .exe into your savegame directory. Run it, it will look for the xml file of AutoDrive, and sorts the destinations.
Next it will open the vehicles.xml file, and change the parking destination of all vehicles to the new sorted destination number.

It also copies the old xml files as a backup. If you want to test it, you can also copy the autodrive and vehicles xml files to another directory and try it there.

Note... you'll need to save your game and close your game to make it work (no need to fully quit FS19).



Program is based on [.net framework 4.7.2](https://dotnet.microsoft.com/download/dotnet-framework/net472).

---
Happy farming,

JustDen

