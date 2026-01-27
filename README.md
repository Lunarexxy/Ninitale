This is a collection of Hytale mods I've made or changed for my own use! They're split into individual packs. Each pack is standalone, and does not rely on any others. They're generally tested and ready for use.

One big exception is the WIP pack, which I use to store whatever I've been working on that I want to save. See the known issues section below for more info.

## Modpacks

Many packs override vanilla items, and may be incompatible with other mods! If anyone knows the best practices for keeping things compatible, I'd love to learn them!

Anything marked with (!) overrides vanilla items.

* **Helper Blocks:** Currently just contains a rotation gizmo viewer. At no rotation, its colored axis arrows correspond to Hytale's co-ordinates and cardinal directions.

* **Well:** Contains a well that allows you to put fluid containers in and fill them with infinite water! Very useful for farms and cooking. Currently not finished, so looks very ugly. But it works.

* **(!) Beam Blocks:** Contains crossbeam and corner variants to vanilla Hytale wooden beams, letting you connect the vertical and horizontal beams cleanly. You can craft these at the Builder's Workbench, similar to how you craft normal wooden beams. Currently only supports Softwood beams, but all wood types will be supported soon.

* **(!) Lighting Blocks:** Contains lantern variants with new colors, which can be created from regular lanterns in the Builder's Workbench. You can even turn colored lanterns back into the vanilla lantern by clicking it in the vertical Input list. You can also hold them as utility items!

* **(!) Paintings:** Contains paintings with custom artwork. Currently only has a few for the 1x1 variant. Original painting model was tweaked to allow for 20x20 pixel art to be displayed. An Aseprite file is included for easy editing!

* **(!) Vanilla Tweaks:** Modifies some vanilla items, either to re-balance them for quality of life, or to allow for more freedom in building on my own server.

* **(!) WIP:** A random assortment of stuff I saved for later use, or as reference. Probably not useful to you


## Installing

Each pack in the mod is a stand-alone modpack and can be installed separately by placing it in your server's (or world's) `mods/` folder.

**Before adding to a dedicated server:**
1. Stop the server to save everything and kick everyone.
2. Back up everything on the server except the `Server/` folder and `Assets.zip` file.
3. Fully remove the folders containing the modpacks being changed.

**Installing:**
1. Place the updated modpacks in the server's `mods/` folder, e.g. `mods/ninitale.BeamBlocks/`
2. Restart server.


## To-do and known issues

**Beam Blocks:**
 * WIP: Only fully supports Softwood at the moment. Adding the rest eventually!
 * WIP: Hitboxes were largely borrowed from stairs, which isn't ideal. Custom hitboxes are planned.
 * Bug: Textures may not line up perfectly with vanilla beams, due to block rotation mis-aligning it. I don't know if I can fix it.

**Paintings:**
 * Bug: The 1x1 painting frame might look a bit off. This seems to be a Hytale rendering bug or something, which is also present in the vanilla frame. I can't fix it.

## Editing mods

Edit modpacks on a world that you can easily restart at will. _(So ideally not a dedicated server.)_

Not everything hot-reloads cleanly at the moment, and sometimes the game can enter an odd state where your changes are not fully applied until a server restart. This especially applies to new files, like block textures or newly generated icons.

New or WIP packs should be put in their own modpack folder.

Language (.lang) files should be named after the modpack, to avoid conflicts. I'm not entirely sure if this is strictly required, but when I had a file called server.lang, it overrode all built-in language translations, rather than adding a few new ones, so this seems to be safer.


## Copyright/License

You are generally free to copy and modify any and all contents of this repository for your own personal and commercial use, unless otherwise specified.
Credit is optional but appreciated. I'm just happy if anyone can get some value out of these packs.

### Exceptions:

 * **Paintings:** Contains art assets derived from vanilla Hytale assets, with my own artworks applied, and potentially art created by others in the future. These artworks should be assumed to not be free for commercial use, and credit must be provided to the work's artist(s) in the in-game painting item's description.
 * **Well:** Contains textures modified from [Ryozu's WellWater mod](https://www.curseforge.com/hytale/mods/well-water), as well as textures created from vanilla Hytale assets. The WellWater mod assets are used under the MIT license.