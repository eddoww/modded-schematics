# Modded Schematics

Schematic files for modded Minecraft 1.12.2 that can be used with
[Schemetica](https://minecraft.curseforge.com/projects/schematica) and
[WorldEdit](https://minecraft.curseforge.com/projects/worldedit).

## Installing

#### Schematica

Schematica requires [LunatriusCore](https://minecraft.curseforge.com/projects/lunatriuscore) as a dependency.

It will look for schematics in your `.minecraft/schematics` folder.

**Optionally:**

Schematica can be configured to be slightly more powerful, namely, by allowing block placements directly in the air and placing as many as it can with each tick.

You can fiddle with them at `.minecraft/config/schematica.cfg`. The lines of interest are

```
	B:placeAdjacent=false
	B:placeInstantly=true
```

Or [check out](http://upaste.me/92d350009432eccab) our cfg file.


#### WorldEdit (forge)

WorldEdit loads its schematics from the `.minecraft/config/worldedit/schematics` folder

## Credits

[Lunatrius](https://github.com/Lunatrius) (Schematica)

[sk89q's Patreon](https://www.patreon.com/sk89q) (WorldEdit)

[Yarillo](https://www.reddit.com/user/Yarillo) (first schematics)

[Hiddenseek/Vevion](https://ugcraft.com) (most schematics and this GitHub repository)
