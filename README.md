# MoreBlocks
MoreBlocks is a Mod Project for SkyNations Servers with the aim to provide a greater variety of decorative Blocks and generally Blocks and Items the Players want to see in the game.

## Blocks and Items
---------------

### Implemented so far:
Sadly none, we are right at the start. Feel free to pick any block and help!

### Wishlist:
### Set 1
no texture needed:
- Doors: Steel, Wood, Titanium, Iron
- Decking: Titanium, Steel, Iron, Copper, possibly a white one to be colored (as carpet)
- Strouts: Titanium, Steel, Iron
- Platform: Titanium, Steel, Iron, Copper
- Railings: Titanium, Iron
- Step: Titanium, Steel, Iron, Copper
- Wedges: Cargo Plate, Shutter
- Wall tiles: Titanium, Steel, Iron, Copper, Wood (possibly using the sign shape)

texture needed:
- Console Block with some kind of speed-o-meter (animation)
- Console Block with different blinking lights (several frames for animation)
- Generic Motor / Machine
- Decorative Lights (possibly just the older versions of the lanterns)
- Shutters: Titanium, Iron, Copper
- Bookshelf
- Chimney / Stove (possibly with fire animation)
- Brick Block (more like classical Bricks with white grout in between the red Bricks)
- More Brick Colors

### Set 2
Blocks:
- Different Woods
- Different Stones
- Metal Table
- Red Sand
- Chairs
- Banks
- Stairs with Steps
- Stained Glass
- Flower Pot
- Bed
- Colored Ice
- Hatch door (remote controlled)
- Corner Wedges
- Sideways(?) Wedges
- Railing corners
- Turbo thrusters (generate more than two thrust)
- Dynamite Blocks
- Shield block for Ships (Deflector Shield / Shield generator)
- more ores
- a teleporter
- Soundproof Blocks
- mechanic to transport Items between chests (aka unloading the mining ship chests onto land)
- med station block
- ship repair field

Items:
- Tool to mine Steel, Copper, Iron, etc. more efficiently
- Handheld laser, Laser Gun
- Grenades

## Organizational

At the moment the goal is to provide more decorative Blocks, preferably ones that can be crafted from existing materials within the game. Blocks which require scripting to properly work because they have a mechanic, or Blocks and Items which would likely be found in a new Biome are, for now, out of the scope of this Mod, but will be listed here regardles, for future reference. 

### Set 1
- simple Blocks with a shape that already exists in the game (cube, wedges, railings, ...)
- no mechanics (scripts) needed to use them

= simple craft and place blocks, nice to look at and used for decoration
### Set 2
- all others

This are mostly blocks that either need to have a new shape/mesh made for them and/or which need a script to work properly within the game world and/or need new Biomes.

## Priority
Set 1 takes priority for now as its easy to implement and almost anyone can help with that. Its as easy as filling out a form (Tiles.xml and Blocks.xml) and drawing a picture (creating the texture).

## How do I contribute?
Pick any block you want to see in the game and provide files for it in a pull request. You don't have to provide everything needed to implement a new block, its fine if you only submit a texture, the .xml files or a script, this is an open project and maybe someone else helps providing the other parts needed.
**Do not submit a pull request that changes anything within the `_MOD\` folder**, it will not be accepted. Create a new folder for your changes within `Contributions\` and put your files in there. The folder structure therein should ideally mirror the one over in `_MOD\`. Your contribution will be reviewed, open for discussion and, if needed, subject to change (e.g. weight and cost of blocks have to be balanced in the grand scheme of the game etc.). Later it will be copied over into the `_MOD\` folder by a maintainer and released.