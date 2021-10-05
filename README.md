# AHK GDI+ LIBRARY EXTENDED COMPILATION

This is a compilation of user contributed functions for the GDI+ library wrapper made by Tariq Porter [tic] that never made it into.

This repository is a fork of https://github.com/mmikeww/AHKv2-Gdip/ .

The compilation comes into two flavours: AHK v1.1 and AHK v2 compatible editions. 

The Gdip_all.ahk file for AHK v1.1 should be compatible with projects already relying on the original edition. In other words, it is backwards compatible. If you find this is not the case, please report the issue[s].

The original examples From TIC are in «examples-ahk-v1-1» folder. You can find several new examples that showcase the newly supported GDI+ APIs. These are example scripts initially provided by those that coded the new functions, with minor modifications.

The examples for the AHK v2 edition I provide here in the repository were tested with AHK v2 alpha 108. In future versions of AHK v2, things might break. The library was not entirely tested on AHK v2. Therefore, bugs are likely present. Please provide feedback and/or pull requests to fix bugs.

# History
- @tic created the original [Gdip.ahk](https://github.com/tariqporter/Gdip/) library
- @Rseding91 updated it to make it compatible with unicode and x64 AHK versions and renamed the file `Gdip_All.ahk`
- @mmikeww's repository updates @Rseding91's `Gdip_All.ahk` to make it compatible with AHK v2 and also fixes some bugs
- this repository attempts to gather all the GDI+ functions contributed by various people that were missing, and further extend the coverage/support of GDI+ API functions
- MCL created an object-based GDI+ wrapper for AHK v1.1 that covers even more GDI+ functions; repository available at: https://github.com/mcl-on-github/oGdip.ahk

# FUNCTIONS LIST

- 36 GraphicsPath object functions
- 43 Pen object functions
- 29 PathGradient brush functions
- 21 LinearGradient brush functions
- 11 Texture brush functions
- 10 SolidFill and hatch brush functions
- 54 pBitmap functions
- 16 ImageAttributes and Effects functions
- 42 Fonts and StringFormat functions
- 42 pGraphics functions
- 21 Region functions
- 10 Clip functions
- 14 Transformation Matrix functions
- 35 Draw/Fill on pGraphics functions
- 14 GDI functions [selection]; the repository now includes a GDI specialized library wrapper for AHK v1.1
- 22 Other functions [selection]

Please see functions-list.txt for the actual list of functions.

# COMPARISIONS

The following list is comparing Gdip_All.ahk by Tariq Porter and Rseding91 modifications with this new version.

## ~23 MODIFIED FUNCTIONS

## ~300 NEW FUNCTIONS

See functions-list.txt for more details and credits.

## NOTES:
  - GetProperty() functions can yield incorrect results for some meta-data/properties.
  - awaiting pull requests for bug fixes

## Derniere mise à jour: mardi 5 octobre 2021 [05/10/2021], v1.88
