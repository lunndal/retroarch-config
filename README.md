# RetroArch custom config
Custom configuration files for RetroArch emulator frontend. 

Consists of two separate configuration files. 
- **Admin config** for starting RA in full access mode.
- **Penguinulator config** reset suitable for distribution to "the kids".

# Usage
The three use cases for the configurations.

## Start RA
Intended for daily use.
`.\RetroArch-Win64\retroarch.exe --menu`

## Start RA as admin
Use this when ever we need full access to everyting.

⚠️ _Does not save config automatically. Any new config need to ba saved manually._

`.\RetroArch-Win64\retroarch.exe --menu --appendconfig .\RetroArch-Win64\config\retroarch-overrides-admin.cfg`

## Reset RA to Penguinulator standard config
Use this if you need to reset the configuration with the default distribution settings for The Penguinulator.

⚠️ _Saves config automatically on exit._

`.\RetroArch-Win64\retroarch.exe --menu --appendconfig .\RetroArch-Win64\config\retroarch-resetconfig-penguinulator.cfg`
