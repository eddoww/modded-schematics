# Modded Schematics

Schematic files for modded Minecraft 1.12.2 that can be used with
[Schemetica](https://minecraft.curseforge.com/projects/schematica) and
[WorldEdit](https://minecraft.curseforge.com/projects/worldedit).

## Installing

#### Schematica

Schematica requires [LunatriusCore](https://minecraft.curseforge.com/projects/lunatriuscore) as a
dependency.

Schematics looks for schematics in `schematics` in the Minecraft directory.

**Configuration (Optional)**

Schematica can be configured to be more powerful in `config/schematica.cfg` in the Minecraft
directory.

You can fiddle with them at `.minecraft/config/schematica.cfg`. The lines of interest are:

	B:placeAdjacent=false

and

	B:placeInstantly=true


Alternatively, you can check out our configuration
[here](https://github.com/eddoww/modded-schematics/releases/download/v1.2/schematica.cfg).

## Replacing Blocks

If you are using Schematica, there is a way to replace blocks of a specific type in the
projected schematic. For example, if you would like to replace the dirt in the Water Wheel, you can
use the following command:

	/schematica replace dirt grass

### TODO

* AbyssalCraft
* **~~Actually Additions~~**
* Applied Energistics 2
* **~~Astral Sorcery~~**
* **~~Better with Addons~~**
* Better with Mods
* **~~Blood Magic~~**
* Botania
* Chance Cubes
* **~~Charcoal Pit~~**
* Colossal Chests
* **~~Compact Machines~~**
* **~~Draconic Evolution~~**
* Embers
* Ender Rift
* Environmental Tech (if someone wants to)
* Evil Craft
* Forestry
* IC2
* **~~Immersive Engineering~~**
* **~~Immersive Petroleum~~**
* **~~Immersive Tech~~**
* **~~Magneticraft~~** (thx @wormzjl)
* Mekanism
* Pneumaticraft
* Soul Shards: The Old Ways
* Tech Reborn
* Terraqueous
* **~~Thaumcraft~~**
* Tinkers' Construct Smeltery (5x5 with a separate massive block/ingot cooling unit)
* **~~Vanilla~~**
* **~~Wizardry~~**
* **~~Woot~~**

## Permissions

This project is licensed under the terms of the MIT license, which means you're allowed to share,
edit and include it in any projects without express permission.

While the MIT license technically requires attribution, you don't have to mention us in your
project, although we would prefer it if you provided a link to this repository.

## Credits

[Lunatrius](https://github.com/Lunatrius) (Schematica)

[sk89q's Patreon](https://www.patreon.com/sk89q) (WorldEdit)

[Yarillo](https://www.reddit.com/user/Yarillo) (first schematics)

[Hiddenseek/Vevion](https://ugcraft.com) (most schematics and this GitHub repository)
