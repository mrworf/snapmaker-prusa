# Snapmaker 2.0 - Prusa Slicer Profiles

This repo contains prusa slicer profiles specifically made to be used by Snapmaker 2.0 3D printers.

A250 Contributors:
 - [@mrworf](https://github.com/mrworf)

A350 Contributors:
 - [@nivekmai](https://github.com/nivekmai)

Note: Some of these configs can be reused for the A150, but currently no contributors have that model, so the usage of these settings on A150 is completely untested.

Currently, all contributors use an enclosure as well which might impact your prints if you don't. We have not tested to see if that makes a big difference. Feel free to let us know.

# How to use

These profiles are exported as config bundles and then split into the specific parts. As such, to import them choose "File" > "Import" > "Import Config Bundle" and import each config. It will not work if you choose "Import Config".

# Contributing

To avoid having duplicates of printers/print configs, please split your configs while using "Export Config Bundle". You can tell the sections in the config bundle since they are separated by a line enclosed in square brackets (`[]`).  See e.g. [SnapMaker A350](Snapmaker%20A350/Snapmaker%20A350.ini) config as an example section extracted from a config bundle. Note how there is only one section (the `[printer:SnapMaker2 A350]` section) in that file.

Please also keep this README up to date while contributing.

# Profiles

If you add additional profiles, please add them to this section

## Complete bundles (printer/filament/print settings combined)
### A250-PETG

PETG support, not the fastest profile, but produces reliable prints.

Be careful though, the PETG will stick hard to your bed if you leave it there to cool off!

## Printers
### A350
Contains 
 - model (credits to the late [@stefix](https://forum.snapmaker.com/u/stefix))
 - print sheet texture (SVG)
 - printer settings

Note that you will have to set the model/texture in the `Bed shape` setting, unless you happen to be on Windows and saving the model/sheet to the same place

## Print Settings
### MatterHackers Build PETG
Mostly the same from the A250-PETG setup, tweaked infill and temperature.

## Filament Settings
### MatterHackers Build PETG
 - Transluscent Green
 - White

Not much configured in here other than colors (mostly the same as the A250-PETG bundle).

# Credit

Initial A250 PETG profile is based on the A350 PLA work by Edwin LIU from the snapmaker forums
- https://drive.google.com/drive/folders/1xfBgXZzwjKaeZ3iqscdpe2xosgFV03G0
- https://forum.snapmaker.com/t/prusa-slicer-profile/5657/4
