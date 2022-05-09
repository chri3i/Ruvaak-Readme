# Ruvaak Modifications

## Disclaimer

No modifications are supported as it is impossible to track down what everyone did. So please do be honest about any modifications you've made and don't report bugs for a modified list.
Running LOOT is not advised unless you know of a way to ensure that the original load order doesn't get changed.
I tried to always match the install order with the load order. That means mod A on the right is roughly in the same spot as on the left.

### General Modifications


Move every addition you make **above** the Synthesis esps.

Things like standalone armors/weapons (craftable), texture replacers or most skse plugins won't cause any issues but there are still things to consider:
- Armors/weapons: I integrated almost everything to use [Heim's](https://www.nexusmods.com/skyrimspecialedition/mods/54207) crafting system. If you don't care about consistency then standalone armors are easy to add right in. I would advise to run Synthesis for the armors/weapons. Disable the paper maps, Dyndolod and the Synthesis plugins except the first one and run one group at a time, closing Synthesis in between.
- Texture replacers: should not cause any harm and won't require any steps other than placing them above ``Ruvaak xLodGen Output`` on the left pane in MO2
- SKSE Plugins: **You need to use plugins that are made for Skyrim version 1.6.xx**. This is mandatory and if your desired plugin does not exist for 1.6.xx (commonly refered as AE), then you can't use it.

### Enemy, Encounter and NPC Mods

Will be harder to add as I covered quite a lot already. You need to check the mod pages and search in MO2 for any mentioned conflicts. Place them under the seperator ``Difficulty & Enemies``

- standalone added enemies: will be a bit easier to add. Worldspace and Cell conflicts might need a patch. 
- Enemy Replacers: Check which ones I use in Ruvaak, untick them on the right pane in MO2 and if they are in a less modular patch, you need to remove them out of these patches. 
- NPC mods: might be fine, but mods like 3DNPCs have a lot of conflicts and are often tough to patch

### New Quest Mods, New Land Mods

Most of them are self-contained and easy to add. The reason I didn't do it, is because I like consistency. Patching that for new lands is a ton of work I'm not willing to do. Always check for conflicts and place in the seprator ``Vanilla Quests & Additional Quests``


### Combat Behavior Mods

**Straight forward: DO NOT TOUCH any of that unless you know exactly what you are doing.** Ruvaak uses a combination of something like six combat behavior mods and you will end up with weird animations and all sorts of problems if you don't do it right.
