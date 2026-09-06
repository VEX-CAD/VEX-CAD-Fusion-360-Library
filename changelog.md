# Changelog

## Version 2.0.6
#### Motion
- Added individual files for every length of low strength and high strength shaft, matching the approach already used for structure, spacers, screws, and standoffs ([#8](https://github.com/VEX-CAD/VEX-CAD-Fusion-360-Library/issues/8)).
  - `Motion/LS Shaft/` — 24 files, 0.5" to 12.0" in 0.5" increments
  - `Motion/HS Shaft/` — 48 files, 0.5" to 24.0" in 0.5" increments
- Added a named `shaft_length` user parameter to `LS Shaft.f3d` and `HS Shaft.f3d`, so a custom length can be set from **Modify > Change Parameters** without editing the timeline.
- Removed the unused off-cut body from the generated shaft files. Each length file now contains a single body.

## Version 2.0.5
#### Field Elements
- Added field elements for VRC Override

## Version 2.0.4
#### Field Elements
- Added field elements for VRC Push Back

## Version 2.0.3
#### Batch Import Script
- Updated README with steps to batch import the library into Fusion

## Version 2.0.2
#### Field Elements
- Moved Over Under field elements to an `Over Under` folder
- Added field elements for VRC High Stakes

## Version 2.0.1
#### Motion
- Added low strength and high strength shafts.
- Relocated all pneumatic folders and files to be one level higher and deleted the `need_to_finish.txt` file. 

## Version 2.0.0

In version 2.0.0 we've reorganized the folders that files are grouped into, so now we have 5 folders: Electronics, Field Elements, Hardware, Motion, and Structure. We've also stopped supporting the add-in from version 1.0.0, so motion components will come in separate files with all the different inserts, and structure as well as hardware components will come in every length possible. 
#### Electronics
- Added 5.5W motors
- Created new simple electronic models that contain only visible components instead of simplifying the entire component.
- Added the VEX V5 GPS sensor, the VEX V5 Rotational sensor, the VEX V5 5.5N bumper switch, and the V2 potentiometer. 
#### Field Elements
- Added standalone files for tiles, triballs, the match load station, the goal, as well as the barrier and high posts.
- Included a simplified full field CAD, as well as a full field CAD with the portable competition perimeter. 
#### Hardware
- Included different varieties of Robosource shoulder screws available.
- Included both lengths of 6-32 steel screws available (0.25", 0.5")
- Added Nylock Flange Nut, Nylon Flange Nut, and Low Profile Nut.
- Fixed retainer models to be flat, removing the hexagonal indent that's present on the original models. 
#### Motion
- Changed the wheel rubber on all wheel files to a gray that resembles the texture being used on the new antistatic omniwheels and traction wheels. 
- Added all unmodified varieties of VRC legal flex wheels (30A, 45A, 60A and their corresponding diameters). 
- Added 6P sprockets and v2 of the high strength gears
- Added antistatic omniwheels and traction wheels
- Changed the acetal green texture previously found on numerous plastic components in the VEX ecosystem to the new acetal red that new VEX products have been shipping with.
#### Structure
- Included new varieties of gussets introduced by VEX, grouping them into 30, 45, 60, and 90 degree folders respectively within the larger gussets folder. 
