# Enigmatica 2 Tweaked

Fork of Enigmatica 2 (1.12.2)

**This pack is unofficial and is NOT affiliated with the creators of Enigmatica. I have [permission](https://github.com/EnigmaticaModpacks/Enigmatica2/issues/748) from NillerMedDild to upload this pack.**

## Description
This pack is essentially a mashup of Enigmatica 2 normal mode, Direwolf20 1.12.2, and ATM3R (plus a few other mods).
A great all-purpose pack for beginners and experienced players.
It is kitchen-sink style, however it includes Enigmatica 2's quest book to help you along.
This pack is medium-heavy, requiring about 6 GB of ram allocated to perform well.
I'd say the pack is just lighter than ATM3R.  
This pack does NOT include: refined storage, gregtech, buildcraft, projectE, avaritia, mystical agriculture, others...

### [Full mod list](/MODLIST.md)
### Latest release: 1.01

### Added mods
<details>
<summary>
click to show
</summary>

- actually computers
- animus
- armory expansion
- aroma1997s dimensional world
- bonsai trees
- born in a barn
- chicken chunks
- crossroads/essentials
- endergy
- exchangers
- furniture mod
- jeid
- letsencryptcraft
- mob grinding utils
- mod name tooltip
- morph
- morpheus
- netherportalfix
- no tema stahp
- pressure pipes
- projectred
- random things
- roguelike dungeons
- simply jetpacks 2
- storage drawers extras
- tatw (beta version)
- the one probe
- top addons
- vanillafix (override because the file needed to be renamed)
- waim
- waystones
- worley caves
- yarcf

</details>

### Removed mods
<details>
<summary>
click to show
</summary>

- betterfps (very little fps improvement, use optifine instead)
- hwyla (in favor of the one probe)
- lostcities (due to jeid incompatibility)
- neid (in favor of jeid)
- recurrent complex (due to massive server lag)
- wawla (in favor of the one probe)

</details>

### Other mod changes
<details>
<summary>
click to show
</summary>

- all mods updated except nuclearcraft, streams
- streams rolled back to 0.4.8 to fix spongeforge incompatibility
- animania addons added

If you want LagGoggles on your spongeforge server, you'll need the latest version that doesn't require TickCentral. Use `LagGoggles-THIN-1.12.2-4.11-92.jar`. Clients can still connect with the latest version of LagGoggles.
</details>

### Config changes
<details>
<summary>
click to show
</summary>

- cofh flat bedrock (not changed)
- astral sorcery - increase level limit
- draconic evolution - disable massive explosions, descrease chaos island distance
- nutrition - allow over eating
- extra utils 2 - disable deep dark dimension
- improve ore dictionary/generation/void miner output
- openblocks - increase elevator range
- embers - decrease ancient golem spawn frequency
- bug fixes
- recipes for flux sponge, creative mana pool/tablet, marble hive

</details>

### Recommended JVM arguments
From [this reddit post](https://www.reddit.com/r/feedthebeast/comments/5jhuk9/modded_mc_and_memory_usage_a_history_with_a/):
```
-Xmx6656M -Xms4G -XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
```
You'll also need Java 8 exactly, and [adoptium.net](https://adoptium.net/temurin/releases/?version=8) is the best place to get it IMO.

For the server, from [mcflags.emc.gs](https://mcflags.emc.gs):
```
java -Xmx6G -Xms5G -XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:+AlwaysPreTouch -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1 -Dusing.aikars.flags=https://mcflags.emc.gs -Daikars.new.flags=true -jar forge-1.12.2-14.23.5.2859.jar nogui
```
Note: you can usually get away with 4 GB, but 6 GB is better especially for pregen.

### Recommended user mods/resource packs
- [OptiFine - HIGHLY recommended](https://optifine.net/adloadx?f=OptiFine_1.12.2_HD_U_G5.jar)
- [Faithful32 Modded](https://github.com/F32Organization/Faithful32-1.12.2)
- [BDcraft Modded](https://bdcraft.net/community/viewtopic.php?t=6510)

### Links
- [Enigmatica 2 Tweaked Curseforge](https://curseforge.com/minecraft/modpacks/enigmatica2tweaked)
- [Enigmatica 2 Tweaked GitHub](https://github.com/BinBashBanana/Enigmatica2Tweaked)

### Links (non-affiliated)
- [Enigmatica 2 Curseforge](https://curseforge.com/minecraft/modpacks/enigmatica2)
- [Enigmatica Discord](https://discord.gg/HnWNd7X)

### Todo (for me)
<details>
<summary>
click to show
</summary>

- the list is gone lol

#### Pack files
- curseforge
  - config
  - (mods)
  - resources
  - scripts
  - options.txt
  - optionsof.txt
- client bundle
  - config
  - mods
  - resources
  - scripts
  - options.txt
  - optionsof.txt
- server bundle
  - config
  - mods
  - scripts
  - structures
  - server.properties
  - SERVER_GUIDE.txt
  - ServerStart.bat
  - ServerStartLinux.sh
  - settings.cfg

#### Ores

Good ores:
- minecraft:gold_ore
- minecraft:iron_ore
- minecraft:coal_ore
- minecraft:lapis_ore
- minecraft:diamond_ore
- minecraft:redstone_ore
- minecraft:emerald_ore
- minecraft:quartz_ore
- actuallyadditions:block_misc:3
- aroma1997sdimension:miningore:0
- appliedenergistics2:quartz_ore
- appliedenergistics2:charged_quartz_ore
- astralsorcery:blockcustomore:0
- astralsorcery:blockcustomsandore:0
- minecraft:glowstone
- thermalfoundation:ore:0
- thermalfoundation:ore:1
- thermalfoundation:ore:2
- thermalfoundation:ore:3
- thermalfoundation:ore:4
- thermalfoundation:ore:5
- thermalfoundation:ore:6
- thermalfoundation:ore:7
- thermalfoundation:ore:8
- draconicevolution:draconium_ore:0
- tconstruct:ore:0
- tconstruct:ore:1
- mekanism:oreblock:0
- nuclearcraft:ore:3
- nuclearcraft:ore:5
- nuclearcraft:ore:6
- nuclearcraft:ore:7
- ic2:resource:4
- biomesoplenty:gem_ore:0
- biomesoplenty:gem_ore:1
- biomesoplenty:gem_ore:2
- biomesoplenty:gem_ore:3
- biomesoplenty:gem_ore:4
- biomesoplenty:gem_ore:5
- biomesoplenty:gem_ore:6
- biomesoplenty:gem_ore:7
- libvulpes:ore0:0
- libvulpes:ore0:8
- forestry:resources:0
- biomesoplenty:crystal:0
- thermalfoundation:ore_fluid:0
- thermalfoundation:ore_fluid:1
- thermalfoundation:ore_fluid:2
- thermalfoundation:ore_fluid:3
- thermalfoundation:ore_fluid:4
- thaumcraft:ore_cinnabar
- thaumcraft:ore_amber
- rftools:dimensional_shard_ore:0
- projectred-exploration:ore:6

Nether variants:
- draconicevolution:draconium_ore:1
- rftools:dimensional_shard_ore:1

End variants:
- draconicevolution:draconium_ore:2
- rftools:dimensional_shard_ore:2

Ores we don't care about (duplicates):
- mysticalworld:quartz_ore
- mysticalworld:granite_quartz_ore
- bigreactors:oreyellorite
- mekanism:oreblock:1
- mekanism:oreblock:2
- thaumcraft:ore_quartz
- nuclearcraft:ore:0
- nuclearcraft:ore:1
- nuclearcraft:ore:2
- nuclearcraft:ore:4
- ic2:resource:1
- ic2:resource:2
- ic2:resource:3
- immersiveengineering:ore:0
- immersiveengineering:ore:1
- immersiveengineering:ore:2
- immersiveengineering:ore:3
- immersiveengineering:ore:4
- immersiveengineering:ore:5
- libvulpes:ore0:4
- libvulpes:ore0:5
- libvulpes:ore0:9
- libvulpes:ore0:10
- forestry:resources:1
- forestry:resources:2
- embers:ore_aluminum
- embers:ore_copper
- embers:ore_lead
- embers:ore_nickel
- embers:ore_quartz
- embers:ore_silver
- embers:ore_tin
- thermalfoundation:ore_fluid:5
- projectred-exploration:ore:0
- projectred-exploration:ore:1
- projectred-exploration:ore:2
- projectred-exploration:ore:3
- projectred-exploration:ore:4
- projectred-exploration:ore:5
- crossroads:ore_tin
- crossroads:ore_copper
- crossroads:ore_native_copper
- crossroads:ore_ruby

Ores that shouldn't count as ores:
- aroma1997sdimension:miningore:1
- astralsorcery:blockcustomore:1
- bigreactors:orebenitoite
- bigreactors:oreanglesite

</details>
