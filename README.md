# DCS Game Manager

## Presentation

This project will allow you to choose between two versions of the game and automatically update saves and configuration, you'll be able to customize easily your game experience.

## Installation

The installation isn't tricky, you just have to follow those steps

### Get this repository

Download this repo by clicking on the top right button `Clone or download` and click on `Download ZIP`

Extract it where you want on your computer

### Preparation

We'll create a backup of our saves, to do that open a CMD (WINDOWS+R -> type CMD then click OK) and enter the following line code:
```powershell
Xcopy "%userprofile%\Saved Games\DCS" "%userprofile%\Saved Games\DCS_BACKUP/" /s/h/e/k/f/c
```

### Launch the script and configure it

once the backup has been made, we'll be able to launch safety the script, to do that double click on `DCS.ps1`, later you can add a desktop shortcut.

A Window'll spawn on your screen, click on the `Options` button on the bottom left corner.
We'll add our DCS game emplacement here, for my part it's:
DCS Cracked: "E:\GAMES\DCS World Crack\bin\DCS.exe"
DCS Legit: "E:\GAMES\DCS World\bin\DCS.exe"

Feel free to customize your own emplacements like:
[GAME INSTALLATION FOLDER]\bin\DCS.exe

