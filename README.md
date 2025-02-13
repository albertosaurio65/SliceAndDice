[FARMERS_DELIGHT]: https://www.curseforge.com/minecraft/mc-mods/farmers-delight
[CREATE]: https://www.curseforge.com/minecraft/mc-mods/create
[OVERWEIGHT_FARMING]: https://www.curseforge.com/minecraft/mc-mods/overweight-farming
[NEAPOLITAN]: https://www.curseforge.com/minecraft/mc-mods/neapolitan
[DOWNLOAD]: https://www.curseforge.com/minecraft/mc-mods/slice-and-dice/files
[CURSEFORGE]: https://www.curseforge.com/minecraft/mc-mods/slice-and-dice
[MODRINTH]: https://modrinth.com/mod/slice-and-dice
[ISSUES]: https://github.com/PssbleTrngle/SliceAndDice/issues

<!-- modrinth_exclude.start -->
# Create Slice &  Dice
[![Release](https://img.shields.io/github/v/release/PssbleTrngle/SliceAndDice?label=Version&sort=semver)][DOWNLOAD]
[![Downloads](http://cf.way2muchnoise.eu/full_slice-and-dice_downloads.svg)][CURSEFORGE]
[![Version](http://cf.way2muchnoise.eu/versions/slice-and-dice.svg)][DOWNLOAD]
[![Issues](https://img.shields.io/github/issues/PssbleTrngle/SliceAndDice?label=Issues)][ISSUES]
[![Modrinth](https://modrinth-utils.vercel.app/api/badge/downloads?id=GmjmRQ0A&logo=true)][MODRINTH]
<!-- modrinth_exclude.end -->

### Slicer

This mod enables a variety of features to create better compatibility between mostly [Farmer's Delight][FARMERS_DELIGHT] and [Create][CREATE].
While it is designed to work with Farmer's Delight, it does work without it and also adds some compatibility features for other mods.

![](https://raw.githubusercontent.com/PssbleTrngle/SliceAndDice/1.18.x/screenshots/slicer.png)

### Automatic Cutting

The Main feature of the mod is the _Slicer_, a machine similar to the _Mechanical Mixer_ or _Mechanical Press_ from Create.
It automatically registers all cutting recipes from Farmer's Delight. In that sense, it is an automatic _Cutting Board_.  
In order to use it, the correct tool has to be placed into the machine, using `Right-Click`. 
By default, only knives and axes are allowed, but this behaviour can be overwritten by modifying the `sliceanddice:allowed_tools` item tag.

### Automatic Cooking

All recipes from Farmer's delight requiring the Cooking Pot are added as heated mixing recipes.

![](https://raw.githubusercontent.com/PssbleTrngle/SliceAndDice/1.18.x/screenshots/cooking.png)

### Sprinkler

The Sprinkler is a block which, when provided with a fluid using a pipe, will distribute it in a small are below.  
Different fluids can have different effects. For now, only lava & water do something.

- Lava applies a small amount of fire damage to entities below 
- Water makes the area below wet, making the world think it's raining there.

The latter is meant to enable growing of _Banana Fonds_ from [Neapolitan][NEAPOLITAN] without being dependent on the weather, but it could possibly have other effects on other mods too.

![](https://raw.githubusercontent.com/PssbleTrngle/SliceAndDice/1.18.x/screenshots/sprinkler.png)

### Overweight Farming

If present, some compatibility features for [Overweight Farming][OVERWEIGHT_FARMING] is added.  
This includes waxing recipes using the deployer, 
as well as showing the axe-stripping of overweight crops in JEI.

![](https://raw.githubusercontent.com/PssbleTrngle/SliceAndDice/1.18.x/screenshots/strip.png)
![](https://raw.githubusercontent.com/PssbleTrngle/SliceAndDice/1.18.x/screenshots/wax.png)
