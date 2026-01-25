This is a collection of Hytale mods I've made or changed for my own use!

They're generally tested and ready for use. One big exception is the WIP pack, which I use to store whatever I've been working on that I want to save. See the known issues section below for more info.


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
 * WIP: Rotation mechanics feel unintuitive. I saw stairs use a specific rotation setup which might help.
 * Bug: Textures may not line up perfectly with vanilla beams, due to block rotation mis-aligning it. I don't know if I can fix it.

**Paintings:**
 * Bug: The 1x1 painting frame might look a bit off. This seems to be a Hytale rendering bug or something, which is also present in the vanilla frame. I can't fix it.

**Lighting Blocks:**
 * Bug: The lanterns look weird when held in main hand, since the animation was meant for torches.

**Well:**
 * WIP: The textures and hitbox are incomplete, though the well itself works. Currently being updated to a 3x3 block version that fits Hytale's style a bit better.


## Editing mods

Edit modpacks on a world that you can easily restart at will. _(So ideally not a dedicated server.)_

Not everything hot-reloads cleanly at the moment, and sometimes the game can enter an odd state where your changes are not fully applied until a server restart. This especially applies to new files, like block textures or newly generated icons.

New or WIP packs should be put in their own modpack folder.

Language (.lang) files should be named after the modpack, to avoid conflicts. I'm not entirely sure if this is strictly required, but when I had a file called server.lang, it overrode all built-in language translations, rather than adding a few new ones, so this seems to be safer.


## Copyright/License

You are generally free to copy and modify any and all contents of this repository for your own personal and commercial use, unless otherwise specified.
Credit is optional but appreciated.

### Exceptions:

 * **Paintings:** Contains art assets derived from vanilla Hytale assets, with my own artworks applied, and potentially art created by others in the future. These artworks should be assumed to not be free for commercial use, and credit must be provided to the work's artist(s) in the in-game painting item's description.
 * **Well:** Contains textures modified from [Ryozu's WellWater mod](https://www.curseforge.com/hytale/mods/well-water), as well as textures created from vanilla Hytale assets. The WellWater mod assets are used under the MIT license.