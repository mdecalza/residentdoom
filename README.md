# DOOMed Resident

by Moustachio (C) 2024

## What This Is

This is a single MBF21 level built with DoomTools by MTrop.
You can build snapshots and reference/use the code within
this repo however you like. Just be sure to give some credit.
Reference the CREDITS text file for detailed sources.


## Before You Build This Project

This project may need some local properties filled in by whoever clones this project.
Make a `doommake.properties` file and look at the properties in `PROPS.txt` for the
modifiable settings for this project. The `doommake.properties` file that you create should
NOT BE CHECKED IN TO YOUR REPOSITORY!


## To Build This Project


This project requires the [DoomTools](https://github.com/MTrop/DoomTools) toolchain for
building it. Clone this project to a new folder and type:

	doommake init


...In order to ensure everything has been prepped correctly (some directories or files
may need extracting, downloading, or copying).

To clean the build folder, type:

	doommake clean


To both initialize and build this project and its distributable archive:

	doommake


To build the DeHackEd patch from DECOHack source:

	doommake patch


To convert raw assets to Doom assets:

	doommake convert


To build the assets WAD:

	doommake assets


To convert raw texture assets to Doom assets:

	doommake converttextures


To build the texture resources:

	doommake textures


To build just the maps WAD:

	doommake maps


To extract only the textures used by maps to a separate WAD file (if any):

	doommake maptextures


To run this project (after setting the correct properties):

	doommake run


To build all components:

	doommake all


To build the full release:

	doommake release

