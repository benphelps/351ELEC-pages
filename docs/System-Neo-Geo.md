# SNK Neo Geo

Because Neo Geo is both an arcade chipset and a home console system, there are two ways to set up your Neo Geo collection on 351ELEC. You can either treat it as a console system, where the roms are contained in their own folder, or you can use a dynamic collection that finds Neo Geo games in your FBNeo or MAME romsets.

If you are curating a larger arcade collection, it's easier to set up Neo Geo as an Automatic Collection. In this case you probably already have Neo Geo games as a part of your FBNeo collection, and separating them into their own folder can be annoying. It also has the advantage of being able to use roms from either the FBNeo or MAME romset as desired and running them in the correct emulator without extra configuration.

If you have no interest in keeping an arcade collection, it may be easier to use the neogeo system folder. Unfortunately, even using this route you'll end up having to deal with some of the issues of arcade ROM curation, as you'll still be using FBNeo or MAME romsets for this collection.

Neo Geo ROMs are unique in that there is no difference between arcade and home console roms. Games are treated as an arcade or home console game based on the BIOS used to run the game, and most people use a Universal BIOS that can act as either. If you're using a Universal BIOS, switching between arcade and home versions of the game is as easy as changing an option.

- [Automatic Collection Overview](#automatic-collection-overview)
- [System Overview](#system-overview)

## Automatic Collection Overview

To use the Neo Geo Automatic Collection, you'll need to have Neo Geo games as part of your FBNeo or MAME collections. These games need to be properly scraped so that the system knows that they're Neo Geo games.

Once you have scraped games as part of your FBNeo or MAME collections, you just need to enable the Automatic Collection by pressing `Start` > `Game Collection Settings` > `Automatic Game Collections`, scrolling down to the `Arcade Chipset` section, and turning on `Neo Geo`.

## System Overview

- Cores:
  - `fbneo` (default)
  - `mame2003_plus`
  - `fbalpha2012`
  - `fbalpha2019`
  - `mame2010`
  - `mame2015`
  - `mame`
- Path: `neogeo`
- Supported Extensions: `.zip .7z`

### ROM Sets

It's recommended that you use the current FBNeo romset for your Neo Geo games, although you can use any rom set supported by one of the cores listed above. Please see the [Arcade](Arcade) page for more information on creating romsets.

- [FBNeo Neo Geo XML Dat](https://raw.githubusercontent.com/libretro/FBNeo/master/dats/FinalBurn%20Neo%20(ClrMame%20Pro%20XML%2C%20Neogeo%20only).dat) - A dat file for use in clrmamepro, romcenter, or another rom compiler
