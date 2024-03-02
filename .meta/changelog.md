# Changelog

If you want to see more detailed changes, you can always navigate to the [commits page](https://github.com/Ceterai/Enternia/commits/main/) and click on the version you're interested in.

<details><summary>Table of Contents (Expand)</summary>

- [Changelog](#changelog)
  - [Update 2.2 - Alta Colonies](#update-22---alta-colonies)
    - [2.2.1a](#221a)
    - [2.2.1](#221)
    - [2.2.0](#220)
  - [Update 2.1 - Alta Decryption](#update-21---alta-decryption)
    - [2.1.4a](#214a)
    - [2.1.4](#214)
    - [2.1.3](#213)
    - [2.1.2](#212)
    - [2.1.1](#211)
    - [2.1.0](#210)
  - [Update 2.0 - The Alta Race](#update-20---the-alta-race)
    - [2.0.1](#201)
    - [2.0.0](#200)
  - [Update 1.7 - Imperial Arsenal](#update-17---imperial-arsenal)
    - [1.7.1](#171)
    - [1.7.0](#170)
  - [Update 1.6 - Crystal Rapture](#update-16---crystal-rapture)
    - [1.6.1](#161)
    - [1.6.0](#160)
  - [Update 1.5 - Alterash Prime](#update-15---alterash-prime)
    - [1.5.0](#150)
  - [Update 1.4 - Exploration \& Restoration](#update-14---exploration--restoration)
    - [1.4.2](#142)
    - [1.4.1](#141)
    - [1.4.0](#140)
  - [Update 1.3 - Alterash](#update-13---alterash)
    - [1.3.1](#131)
    - [1.3.0](#130)
  - [Update 1.2 - Enternia Enhanced](#update-12---enternia-enhanced)
    - [1.2.1](#121)
    - [1.2.0](#120)
  - [Update 1.1 - Enternia](#update-11---enternia)
    - [1.1.0](#110)
  - [Update 1.0 - Little Expansion](#update-10---little-expansion)
    - [1.0.1](#101)
    - [1.0.0](#100)

</details>

## Update 2.2 - Alta Colonies

### 2.2.1a

This small bugfix patch is a refinement & compatibility fix for the previous version, as well as a small clean-up of outdated and deprecated files and objects.

If you want to keep deprecated items, objects, planets, etc. - subscribe to the freshly released **My Enternia - Removed Content** mod!

![ ](/.meta/images/panels/steam_removed_content.png)

This update is also to celebrate the mod finally reaching **five stars** in Steam Workshop! **★★★★★**

![ ](/.meta/images/panels/steam_stars.png)

**Main:**

- posted a separate mod that retains any old deprecated content as a backwards-compatability feature: **My Enternia - Removed Content**:
  - [Steam Workshop Link](https://steamcommunity.com/sharedfiles/filedetails/?id=3169344640)
  - [Starbound Forums Link](https://community.playstarbound.com/resources/my-enternia-removed-content.6282/)
  
  You can use it if you want to keep years old planets or other things that were deprecated a long time ago. More details in the mod description;
- added the **Alta Scanner** to the quickbar;

**Alta:**

- made the mod compatible with **Alta Lights** placed before 2.2.1;
- the **Alta Scanner** can now be found in the quickbar around the bottom of the list *(note that just like most quickbar tools, it's meant to be used in the **admin mode** or for **creative purposes**, not an actual survival/rp, as it's still an item you'd have to craft first if you care about the progress)*:  
  ![ ](/.meta/images/panels/quickbar_scanner.png)

**Wiki:**

- added an **Alta Robotics** page with information split from the main Alta page to make it load faster and more reliably;
- moved more pages to a semi-manual state - **EDS**, **Faradea**, all modding-related pages;
- added a "cheat/creative crafting tables" section to show if an item can be accquired in admin/creative places like **Tabula Rasa**, **Spawnable Item Pack**, **Ultimate Alta Station** or **Ultimate Alta Constructor**.

**Dev:**

- added `README.md` files to some alta folders to help explain things, useful if you're using the modding wiki pages or are trying to understand where things re located in the mod;
- updated most mod support files with proper links;
- updated the main `README.md` with relevant information and some neat features;
- moved the buildscripts slightly;

**Translation:**

- moved loot items from `/items/active/unsorted/ct_alta_loot/` to `/items/active/unsorted/alta/loot/`;

**Other:**

- minor grammar fixes;
- minor bug fixes.

### 2.2.1

This time alta researchers have done a great job working on improving basic alta furniture, as well as providing support to alien (human) technology!

They have also come up with customized drone models that look just like ship drone variations! You can craft some of them, find them as loot or buy them from alta merchants.

This update is also to celebrate the **4th anniversary** of the mod, since it was first posted in Steam Workshop!

![ ](/.meta/images/panels/steam_anniversary.png)

![ ](/.meta/images/panels/steam_221a.png)

> Detailed changes for this version: [Update 2.2.1](https://github.com/Ceterai/Enternia/commit/2650b2a2ba59a67de76c6876f29821a9581d20ab)

**Main:**

- added 15 ship pet drone spawners;
- added **partial** support for the [Spawnable Item Pack](https://steamcommunity.com/sharedfiles/filedetails/?id=733665104) mod - it now contains recipes **for a lot of** items and objects of this mod. If you want to see **more** recipes, use:
  - **All recipes**: Max Tier **Alta Crafting Station**, **Alta Constructor**, **Cooking Table** and **Alta Datacenter**;
  - **Most Recipes**: **Tabula Rasa**;
  - **Majority of Recipes**: **Spawnable Item Pack**.
    - Due to how SIP works, I wasn't able to make a lot of the recipes available there as they require parameters.
- added support for [Equivalent Exchange](https://steamcommunity.com/sharedfiles/filedetails/?id=1790667104);

**Alta:**

- added extended descriptions to some vanilla items for the **Alta Scanner**;
- improved graphics for held loot crates, sets, robot spawners and the **Alta Scanner**;
- fixed **Alta Energy Source**, **Alta Lamp**, **Alta Laptop**, **Alta Light**, **Alta Monitor**, **Alta Pods**, **Alta Lamppost**, **Alta Lab Server**, **Alta Ship Monitor** - I would recommend re-placing them for changes to take place;
- fixed **Alta Mechanic** and **Alta Engineer** npcs - they no longer crash on interaction;

**Dev:**

- added a common switch/light script - `/objects/alta/switch.lua`. Will move most wired objects to used it instead of original ones;

**Translation:**

- added a file with extended item descriptions - `/items/active/unsorted/alta/scanner/items.config`;
- minor grammar fixes that **shouldn't affect translation**;
- moved spawner items from `/items/active/unsorted/ct_alta_spawner/` to `/items/active/unsorted/alta/spawner/` - **shouldn't affect translation** as these files don't need to be translated in the first place;
- planning to move loot items from `/items/active/unsorted/ct_alta_loot/` to `/items/active/unsorted/alta/loot/` in the next update;

**Tabula Rasa:**

- added all recipes to the [Tabula Rasa](https://steamcommunity.com/sharedfiles/filedetails/?id=737353165) crafting table - `/spawnitem tabularasa`;
- added `mod` category to most recipes in the mod to make them appear in **Tabula Rasa**, and added categories used by it for compatability - `materials`, `armors`, `weapons`, `consumables`, `tools`, `objects` and `other`;
- added "mod category" buttons - **My Enternia** and **Alta Species**:
  - **My Enternia** button filters by all recipes from this mod;
  - **Alta Species** button filters by all recipes from this mod that belong to altas or are considered alta technology.

**Other:**

- made simple produce items like **Ayas** stackable (up to 1000 in a stack) to make them less inconvenient;
- made it so the game knows for sure what mods to load before this one;
- possibly fixed a server-related game crash when using **Alta Scanner**;
- removed some deprecated status effects;
- minor grammar fixes;
- minor bug fixes.

### 2.2.0

You've finally received the first signal from nearby alta travelers! Seems like they're looking for a place to settle. If you'll make them feel at home, they will reward you with neat shinies, protect you, or even open up for trading!

> Keep in mind that a lot of deprecated items got removed in this version.

> Detailed changes for this version: [Update 2.2.0](https://github.com/Ceterai/Enternia/commit/2bcdc6852322c1194d21d915de53f2d56140de84)

**Main:**

- added 92 tenants and 2 outpost visitors;
- added the [Alta Scanner](https://github.com/Ceterai/Enternia/wiki/Alta-Scanner) - a lore tool that will let you know extensive information about items added by this mod (and more!);
- removed a number of deprecated items and status effects;

**Alta:**

- added recipes for additional armor and weapon variations to the Ultimate Crafting Station;
- added the Alta Scanner:
  - displays extended descriptions and certain species descriptions if the item has them;
  - displays item/colony tags of all items and objects;
  - displays additional info like breakability, species and where to find the item;
  - translation to alkey;

**Wiki:**

- added a [Tenants](https://github.com/Ceterai/Enternia/wiki/Tenants) page that lists all possible tenants added by this mod and how to spawn them;
- made crafting notes more granular, in that they now show general tier of the crafting table needed to craft them;

**Dev:**

- removed oldest deprecated items and status effects that should no longer appear in the game;

**Translation:**

- added a `/dialog/alta.config` file with all npcs lines and phrases;
- expanded the `/species/alta_namegen.config` file with new alta names;
- expanded the `/.meta/world.json` file with a couple of words in the `alkey` library;
- expanded the `/items/buildscripts/ct_texts.config` file with a couple of tooltip texts;

**Other:**

- fixed outdated IDs in the Ayaka Loot Table loot pool;
- minor grammar fixes;
- minor bug fixes.

## Update 2.1 - Alta Decryption

### 2.1.4a

A small bugfix update in preparation for 2.2, that fixes technical issues left from 2.1.4 and other older bugs.

This might be the most stable & bugless update so far, which is nice.

> Detailed changes for this version: [Update 2.1.4](https://github.com/Ceterai/Enternia/commit/c54e8bb7b6a16e6877b0ec202c659c1977f5aafe)

**Main:**

- many small bugfixes;
- perfected backwards compatability;
- another id update;
- Ultimate Crafting Station enhancements;

**Alta:**

- added recipes for additional armor and weapon variations to the Ultimate Crafting Station;
- added recipes for all weapon/armor Weapon Upgrade Anvil upgrades to the Ultimate Crafting Station;
- added more categories to the Ultimate Crafting Station (now at 34) and reworked some existing ones;
- added missing dye recipes;
- added more upgrade recipes to the Upgrade Station;
- reworked sections in the Upgrade station;
- reworked passive healing abilities and autoabilities to only heal you if you have 5 hp or more (for non-player entities);
- fixed interface in the Alta Crafting Station;
- fixed glowsticks not working properly;
- fixed coloring on the Space Helmet;

**Wiki:**

- updated some pages with fixed grammar and extended descriptions;
- updated Mod Support pages with lots of new details;

**Dev:**

- added an **Information For Translators** section to the `README.md` with information that might be relevant to translators;
- added **Translation** sections to this changelog to denote any changes that might be important for translators;
- added links to detailed commit/version changes to all version descriptions in changelog up until 2.0 (inclusive);
- added tables of content both to the changelog file and the `README.md`;
- added comments to some lua scripts and json files, including `/items/buildscripts/ct_mimics/aid.consumable` & `/items/buildscripts/alta/item.lua`;
- added handling for outdated presets in item builders;
- added handling upgrade parameters as presets in item builders;
- moved more dev files to `.meta` (`changelog.mg` and `cockpit.config.patch.init.json`);
- updated `/.meta/palettes/color_swaps.json`: removed unused palettes and reformatted existing ones, updated them accross multiple clothing items;

**Translation:**

- added translation-related comments to tier 1-5 loot crate items;
- added useful comments to the GSR Pod, the Metrocop Set and the Companion Drone spawner item;
- updated mimic items in `/items/buildscripts/ct_mimics`;
- moved english text from all item tooltips in `/interface/tooltips` and `/interface/itemdescriptions` to `/items/buildscripts/ct_texts.config` into keys `level`, `armor` and `tool` for easier translation;
- created a `world.json` file in the dev `.meta` folder. It contains color codes and descriptions of concepts, biomes and factions added by this mod;
- changed following filenames:
  - `/names/alta.namesource` to `/species/alta_namegen.config` and changed structure;
  - `/items/generic/crafting/ct_edsarmor.item` to `/items/generic/crafting/ct_eds_armor.item`;
  - `/items/generic/crafting/ctwood.item` to `/items/generic/crafting/ct_ayaka_wood.item`;
  - `/items/generic/produce/ctaya.consumable` to `/items/generic/produce/ct_aya.consumable`;
  - `/items/generic/produce/ctgil.consumable` to `/items/generic/produce/ct_gil.consumable`;
  - `/items/generic/produce/cttsay.consumable` to `/items/generic/produce/ct_tsay.consumable`;
  - `/items/generic/produce/ctwoodsap.consumable` to `/items/generic/produce/ct_ionic_sap.consumable`;
  - `/items/augments/back/ct_warpedaugment.augment` to `/items/augments/back/ct_warped_augment.augment`;
  - `/items/augments/pet/ct_warpedcollar.augment` to `/items/augments/pet/ct_warped_collar.augment`;
  - `/items/augments/pet/ct_yaaracollar.augment` to `/items/augments/pet/ct_yaara_collar.augment`;
  - `/items/armors/alta/other/eds_beret/ct_alta_eds_beret.head` to `/items/armors/alta/other/eds_beret/ct_eds_beret.head`;
  - `/items/armors/alta/other/eds_visor/ct_alta_eds_visor.head` to `/items/armors/alta/other/eds_visor/ct_eds_visor.head`;
- text/description changes/additions in following files:
  - `/items/armors/alta/tier5/combat/chest/ct_combat_chest.chest` - added `presets` with a single preset;
  - `/items/armors/alta/tier5/combat/legwear/ct_combat_legwear.legs` - added `presets` with a single preset;
  - `/items/armors/alta/other/eds_visor/ct_eds_visor.head` - added `presets` with a single preset;
  - `/interface/cockpit/cockpit.config.patch` - added a comment separating deprecated values;
  - `/items/armors/alta/tier6/elite/protector/ct_elite_protector.back` - changed `shortdescription` slightly;
  - `/radiomessages/exploration.radiomessages.patch` - slight changes to `ct_loot_crate_msg` to make it shorter;

**Other:**

- fixed koywa treasure pools;
- fixed upgrade parameters of some weapons;
- fixed categorization on Warped Fumes;
- copied Perfectly Generic Item section from Deprecation Station to the Upgrade Station;
- updated `README.md` and added navigation, as well as some useful links;
- updated color options on some clothing items to make them more aligned with the rest;
- updated deprecation scripts - now items and objects with outdated IDs will stack perfectly with relevant items;
- minor bug fixes.

### 2.1.4

At last, a data patch that fixes drone malfunctions! You can now make sure that your drone spawners are safe to use...
> Note that next version (2.2) will remove a lot of long-deprecated items and objects. Load your world and check inventories with those to update them to avoid them turning into Perfectly Generic Items. Deprecation Station will also get deprecated. It's no longer of much use, and the Perfectly Generic Item section will be moved to the Upgrade Station.

> Detailed changes for this version: [Update 2.1.4](https://github.com/Ceterai/Enternia/commit/1356eaa2d5a358e8fce42ee163f5bdee1a512cff)

**Main:**

- many big bugfixes, lore additions and wiki improvements;
- properly functional hazard objects and decorations;
- pretty big mod cleanup;

**Alta:**

- fixed scout/EDS drone spawners:
  - increased amount of drones in the Alta Drone Station from 3 to 10;
  - fixed spam in EDS Spawner;
  - fixed EDS Drones exploding on spawn in low threat environments;
- fixed defeat logic on some drones (like Frigate Drone);
- seemingly fixed errors with "liquidLineCollision" on all droids & drones (?);
- fixed Alta Lab Barrier - now it:
  - only damages when closed;
  - has according particles and looping electric sound when closed;
  - shows up in the Hazards tab in Alta Constructor;
- fixed break sounds on EDS Halters;
- fixed Staris Soup food item;
- fixed items no longer being upgradable at the Weapon Upgrade Anvil when having certain items in your inventory;
- fixed some items not being upgradable at the Weapon Upgrade Anvil due to incorrect tags (forgot the `upgradeableWeapon` tag): Bishyn Spear, Niverisk, Protospear;
- fixed tooltips on Alta City Sapling, Alta Lab Sapling and Alta Ship Sapling;

**Wiki:**

- added trivia sections;
- added extended descriptions to rifles, drones, droids, hazard objects, plants and some other things;
- added screenshots for Defensive Drone R300, Ionic Drone and Lava Drone;
- added species support;
- made Alta page semi-automated, added in-game info;
- fixed extended descriptions on monster spawner items;
- minor adjustments and formatting update;

**Dev:**

- added comments to some lua scripts;
- moved dev landscape screenshots and previews and their psd files for versioning and to keep them in one place;
- moved all dev/meta stuff like mod support scripts, palettes, mod descriptions and images to a `/.meta` folder to keep it clean;
- the `/.meta` folder is excluded from actual releases and will only be present in the GitHub repo, as well as `.gitignore`, `changelog.md` and `README.md`;
- reworked mod support scripts and added comments to make them cleaner and easier to understand;
- optimized build scripts and made them cleaner;
- made deprecation builders slightly more seamless;

**Other:**

- added particles to objects: Poison Crystals, Yaara Heart;
- fixed upgraded item icons;
- fixed upgraded calin sword;
- fixed collision on hazard objects: Alternia Crystal, Poison Crystals, Yaara Heart, Yaara Roots, Warped Roots, Alta Lab Barrier, EDS Halters;
- fixed particles on hazard objects: Alternia Crystal, Yaara Heart, Yaara Roots, Alta Lab Barrier, EDS Halters;
- fixed levels on hazard objects: Alternia Crystal, Yaara Heart, Yaara Roots, Warped Roots;
- fixed level inventory tooltips on objects;
- moved text lines from item builder scripts into a `/items/buildscripts/ct_texts.config` file to make them easier to translate/change;
- tried to fix emote issues for kaiteras (second alta gender), but wasn't successful;
- minor bug fixes.

### 2.1.3

Finally learning more about general alta traits and special abilities, you discover and learn about their strongest sides... but also about their weaknesses.

> Detailed changes for this version: [Update 2.1.3](https://github.com/Ceterai/Enternia/commit/845e5d960b0affdad90265b06b3b1d57f906da34)

**Main:**

- added full support for the [Race Traits](https://steamcommunity.com/sharedfiles/filedetails/?id=2622273194) addon;
- added partial support for [Frackin' Races](https://steamcommunity.com/sharedfiles/filedetails/?id=763259329)/[Frackin' Universe](https://steamcommunity.com/sharedfiles/filedetails/?id=729480149) - no FU BYOS support. If you need it, you can get it here: [Alta FU Patch+](https://steamcommunity.com/sharedfiles/filedetails/?id=3048977458);
- added 1 radiomessage;

**Wiki:**

- updated certain manual pages;
- fixed related resources mix-up for Ghearun & Gheatsyn codexes;
- fixed pickup radio message support;
- added "Alta Datamass" and "Empty Datamass" aliases to the Datamass;

**Other:**

- added a radio message for ebooks;
- added proper tags for augments and collars;
- minor grammar fixes and wiki enhancemens;
- fixed unlocked food recipes of food and produce;
- fixed tags on all datamasses, docs and ebooks that have wrong tags;
- minor bug fixes.

### 2.1.2

You're discovering more knowledge about alta culture and are uncovering new databases along the way, with a few things to enhance equipment you already have.

> Detailed changes for this version: [Update 2.1.2](https://github.com/Ceterai/Enternia/commit/160ebc9d589491219dfea9cb0e465c32038f6610)

**Main:**

- added 24 codexes;
- added 25 radiomessages, that now display once you pick up specific items;
- added a bit of recipes for custom items (most are only available at the ultimate crafting station);
- new cosmetic items can be found as loot in biome chests;

**Wiki:**

- updated certain manual pages;
- added pickup radio message support;

**Other:**

- added extended descriptions to most food and codex items;
- revorked perfect cooking system slightly;
- enhanced some codexes and fixed grammar & phrazing in several places;
- upgraded shields and perfect foods now have custom colors;
- all t6+ armor items now have according consistent invisible bonuses, mentioned in their descriptions;
- minor bug fixes.

### 2.1.1

Now that datacenter is full of useful and intersting information, might as well use the most of it to prepare for upcoming threats!  
Also, it seems like some melee blueprints have finished downloading... Might wanna try them out.

> Detailed changes for this version: [Update 2.1.1](https://github.com/Ceterai/Enternia/commit/8c751d4cf4ed2b2ec4217ad0f36a409348e918c9)

**Main:**

- most melee weapons are now finally usable! They's still WIP, but to a much lesser extent;
- big wiki improvements and preparations for the next version;

**Alta:**

- adjusted a lot of alta recipes;
- fixed grammatical errors in some android head items;

**Wiki:**

- updated many manual pages;
- made some manual pages non-manual: Bionid, Isoslime, Crystalline Prime, Ayaka, Phospholion;
- added aliases for proper links and references;
- added more extended descriptions;
- added more species descriptions;
- added banner support;
- added category override support;
- added parent pages support;
- added related resources support;
- added collapse blocks for big lists in loot and crafting sections;
- added manual pages: Factions, Koywa, Elin Gardens;
- added custom content support;
- added the "alkey" key to item aliases;
- added radiomessage support;
- certain color codes now translate to bold instead of links;
- enhanced tags;
- fixed codex text display;
- fixed many icons and references on manual pages;
- fixed level and other params for codexes;
- fixed whitespaces in file links;

**Other:**

- adjusted timings on a lot of recipes;
- fixed and enhanced item & colony tags on most items;
- enhanced the item builder scripts to now add race, rarity and element as tags;
- enhanced some recipes with custom params (mainly crystalline deposits);
- minor bug fixes.

### 2.1.0

Provided database has been successfully analyzed by your datacenter, unlocking access to a number of informational entry and codexes for your archive.
It seems like melee blueprints are still decrypting, so you can take your time reading through all of those waiting for it to finish.

Meanwhile, meet some experienced altas to get you accustomed to their culture and try out new equipment available at the crafting station! Trust me, you'll need it quite soon.

> Detailed changes for this version: [Update 2.1.0](https://github.com/Ceterai/Enternia/commit/58322452614ecf048629fa87cd8362b08862e886)

**Main:**

- still working on WIP weapons;
- added 34 codexes, including 6 culinary codexes and a 4-part alta history codex series;
- added more armor, augments and fixed armor coloring;
- added extended descriptions for wiki and other future uses;

**Alta:**

- added 5 t5 helmets, 3 t6 helmets, 4 t6 epps, 6 t5 augments, 6 t6 augments, 6 misc augments, 2 misc collars, 4 misc helmets;
- added 4 cosmetics;
- deprecated some old augments and collars;
- reworked visuals of all light alta objects;
- rebalanced all armor;
- made it so certain custom saplings can spawn in chests;
- custom alta saplings now contain pools of possible trees, including rare trees that cannot normally be found anywhere else;
- fixed coloring of armor items;
- increased the amount of levels in the Alta Crafting Station;

**Wiki:**

- properly updated manual pages: Alta, EDS, Ayaka, Alterash, Alterash Prime, Ceternia, Alternia, Enternia (added references to stim packs, as well as for Hevikai);
- fixed headings in many manual pages and updated their contents;
- added expanded descriptions with lore to a lot of items. These descriptions can only be seen on respective wiki pages (and in game files, obviously);
- added proper item tags to a lot of items;

**Other:**

- added rare tree variations - Warped Yaara Node, Starfield Yaara Node, Golden Yaara Node (also Elin Ayaka, which technically was added in 2.0.1);
- added missing Elite Droid and Stalker Droid recipes;
- fixed grammatical errors for some effects;
- fixed drone sorting in the crafting station;
- things like Ceter-Sphere now require an according nade and 2 according stims to craft, which require according glowsticks to craft;
- redistributed weapons and items more gradually over the planets;
- enhanced and balanced all chest loot tables;
- made names of certain items shorter to fit into tooltips;
- removed deprecated loot tables, effects, plant sprites and radio messages;
- minor bug fixes.

## Update 2.0 - The Alta Race

### 2.0.1

The database with advanced blueprints you got from those altas is still transferring into your crafting stations and datacenters. The latest blueprint pack has just dropped, let's see what it is! ..Status improvers, protective stim packs, medicine, and... Are these... saplings?

> Detailed changes for this version: [Update 2.0.1](https://github.com/Ceterai/Enternia/commit/194f6e223c60e21295a25427426d8c4b502ca031)

**Main:**

- fixed lots of bugs and crashes. See **Other** for more;
- updated the Wiki to reflect new changes and improved some of its pages too;

**Alta:**

- added Electric Stim Pack, Impulse Stim Pack, Plasma Stim Pack and Hevikai Stim Pack - both craftable at Alta Crafting Station;
- added Catalyst - a **debug item** that removes all permanent and ephemeral effects - craftable at max Alta Crafting Station;
- added 26 custom **debug saplings** that grow into certain tree types added by this mod to be able to test them easier;

**Monsters:**

- fixed drone-related behaviour - `ct_alarm_backup`;
- fixed shields on drones;
- made drone spawn animation more visible;
- fixed different monster projectiles and monster attacks;

**Wiki:**

- properly updated manual pages: Weapons, Bionid, Ceternia, Alternia, Enternia;
- added support for plants (trees, bushes and grasses);
- improved support for biomes - they now show most attributes, as well as what can spawn in them;
- improved support for everything else - if it spawns in a biome, it will now display on its page;
- improved support for chests - they now show biome loot they can have (if associated with a treasure chest);

**Other:**

- added missing effects - Plasmoblockade, Pulsoblockade, Overcharged Air, Hevikai Strike, Hevikai Block and Hevikai;
- added better descriptions to items showing where to find them;
- moved Prismantler to deprecated;
- fixed a crash when big drones try to jump;
- fixed rarities/prices/levels for almost all objects;
- fixed covers and sitting/laying offsets on all loungeable objects;
- fixed velocity jump status effect;
- reworked a lot of recipes:
  - reworked equipment and medicine recipes and united into the same tab;
  - split cosmetics into 2 tabs instead;
  - reworked some nature recipes and prepared them for the upcoming mech table;
  - reworked some crafting material recipes too;
- reworked a lot of status effect scripts:
  - moved most scripts and made them more customizeable;
  - added more proper comments and descriptions to mod scripts;
  - added proper radio messages for some effects so the player can understand what they do and how to block them - Overcharged Air, Hevikai Strike and Hevikai;
  - added proper animation files and config;
- updated mod support script stuff;
- minor bug fixes.

### 2.0.0

The Altas are finally here! What secrets do whey hold? Will they share them... with you?  
They absoultely will! Among tons of interesting information, you got new weapon blueprints, as well as more details about other already known equipment, even proper food recipes!  
It seems you have also got a hold of some weird pods labeled "GSR". I wonder what's inside...

> Detailed changes for this version: [Update 2.0.0](https://github.com/Ceterai/Enternia/commit/14420adb4e5d35f65ef1ad33f52cd8f916337fbe)

**Main:**

- created Mod Wiki. Find it here: [My Enternia: Wiki](https://github.com/Ceterai/Enternia/wiki);
- the Wiki contains in-detail info about pretty much everything in the mod, from items/objects/monsters to effects, biomes, weather and even worldbuilding concepts/lore;
- the Wiki also includes extensive info for modders wanting to create mods on top of this mod;

- added full support for the [Improved Food Descriptions](https://steamcommunity.com/sharedfiles/filedetails/?id=731354142) addon;
- added full support for the [More Planet Info](https://steamcommunity.com/sharedfiles/filedetails/?id=1117007107) addon;
- added full support for the [True Space](https://steamcommunity.com/sharedfiles/filedetails/?id=730684624) addon;

- added much more detailed GUI tooltips to many types of items:
  - weapon/shield tooltips now include more stats, element icons (shields too), full description, ability names and description, and whether it can be upgraded to anything;
  - armor/clothing/backpack/epp tooltips now have more slots for abilities and display them properly, as well as show upgrades if any;
  - drone spawners now include monster stats, resistances, ability names & descriptions and upgrades if any;
  - object tooltips now include health, list of colony tags, light color (if any) and a separate warning if the object doesn't drop itself;
  - all new tooltips include stuff like level and race;
  - all descriptions are color-coded with highlights;
  - new tooltips only apply to items added by this mod.
- added 8 ranged wrist weapons and 8 unique ranged weapons (4 WIPs);
- added 24 melee weapons (WIP): 8 light, 8 heavy and 8 spears;
- added perfectly cooked versions to all food items added by the mod;

**Alta:**

- added **Altas** as a playable race! Right now with placeholder ship and mechs, as well as no npcs/tenants and no dungeons;

- added **GSR pods** - loot crates that contain materials and rare weapons that you can't find anywhere else! (except for t6 crafting table);

- revamped [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) to encourage exploration and make progression smoother:
  - now has 9 levels instead of 6: 2 T3 levels, 2 T4, 2 T5, 2 T6 and 1 final creative level with recipes for every item in the mod;
  - only levels 3, 5 & 7 require codexes to upgrade. Levels 2, 4, 6 & 8 only require resources found on planets added by the mod;
  - levels 2, 4, 6 & 8 are "sub-tiers" - they reveal improved stuff from the previous tier, as well as cosmetics, throwables, augments, etc.;
  - levels 1 & 2 contain T3 stuff, levels 3 & 4 - T4 stuff, levels 5 & 6 - T5 stuff, levels 7 & 8 - T6 stuff.

**Other:**

- added upgrades to one of the armor sets;
- added custom **item builder** and **object builder**! They support and provide proper tooltips for:
  - item params:
    - level, price (leveled), price (fixed), race, element;
    - all damage params (leveled & fixed): damage/shot, energy/shot, firerate, dps, eps, damage/energy;
    - all shield params (leveled & fixed): health, knockback, eps, parry time, min time, cooldown time;
    - primary, secondary and passive abilities, as well as weapon upgrades (on any item, not just weapons);
    - works for almost any item type, including weapons, throwables, generics, shield, custom active items, codexes, etc.;
  - object params:
    - all mentioned above (object builder expands item builder);
    - all basic object params: health, slots, light color, colony tags, warning if the object doesn't drop itself;
    - damage params for traps, including damage element;
- added informative yet concise visuals to the mod's description;
- added custom minibiome chests to almost every biome added by the mod (see [Loot Crates](https://github.com/Ceterai/Enternia/wiki/Loot-Items#Loot-Crate-Items));
- biomes that remain without custom loot are: Poptop Valley, Snowy Ridges, Alterash Caves, Deep Alterash Caves, Electric Crystal Caves, Starforest, Antorash Plains, Obsidian Depths, Starfields, Alterash Core, Hidden Alta Labs, Alta Lab Debris, Alta Prime Labs;
- the Hive minibiome can no longer spawn on Alterash planets;
- improved other weapons and armor;
- rebalanced pricing on a lot of items;
- fixed alt abilities for some weapons;
- fixed projectiles for some weapons;
- fixed chars and pricing of some armors;
- fixed some recipes, moved them to proper places;
- moved some old weapons to deprecated and removed their recipes;
- removed some of the oldest deprecated items;
- minor bug fixes.

## Update 1.7 - Imperial Arsenal

### 1.7.1

Massive technological structures were located by your geoscanners under the surface of some alterash prime planets. The massive giants are apparently guarding some treasure among the gheatorn caves.  
The `Gheatsyn Droids` are waiting for "visitors".

**Main:**

- finished the gheatsyn droid (no longer WIP), as well as its spawner recipe. Now spawns in Gheatorn biomes on Alterash Prime planets.

**Other:**

- adjusted weapon sounds, animations and timings;
- adjusted drone spawns;
- fixed drone names;
- fixed logic of some drones as well as Alta Mini Drone spawns;
- fixed icons in the upgrader interface;
- fixed teleporter collisions;
- fixed triggers for some new objects;
- fixed wrong status effects on some shields;
- updated stim pack parameters;
- updated most crafting table interfaces;
- minor bug fixes.

### 1.7.0

Your datacenters just finished decrypting large parts of alta technology blueprints! This update adds tons of new upgradeable weapons and drone spawner items (craftable and loot ones), as well as a new tier 6 armor set!  
It also adds more throwable items and a full set of alta objects, traps, decorations and structures!

**Main:**

- added in total 72 objects: 1 sapling, 1 crafting, 64 decor, 2 spawners, 4 teleporters;
- added in total 92 items: 2 materials, 4 throwables, 8 shields, 32 weapons, 26 monster spawners, 14 loot items, 1 collar, 5 set items;
- added in total according recipes.

**Alterash:**

- updated existing biomes with new stuff.

**Alterash Prime:**

- updated existing biomes with new stuff.

**Alta:**

- added [Alta Upgrader](https://github.com/Ceterai/Enternia/wiki/Alta-Upgrader) - can be crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);

- added [Ghearun Set](https://github.com/Ceterai/Enternia/wiki/Ghearun-Set) of tier 6 armor as well as a set item;
- this set can be found in [Gheatsyn Chest](https://github.com/Ceterai/Enternia/wiki/Gheatsyn-Chest) in [Gheatsyn](https://github.com/Ceterai/Enternia/wiki/Gheatsyn) biomes or crafted at [Alta Upgrader](https://github.com/Ceterai/Enternia/wiki/Alta-Upgrader);

- added 32 ranged weapons:
  - tiers 3 (1), 4 (3), 5 (12), 6 (7), 6+1 (6), 6+2 (2), 6+3 (1);
  - press and hold can do different things (try pressing or holding LMB or RMB to see different results);
  - can shoot projectiles and apply effects;
  - projectiles can be piercing, ricosheting, guided, wobbling, exploding, sticky, liquid, etc.;
  - can have `flashlights`, `lazerpointers` and `stabilizers` (increase damage by 1.25);
  - some weapons (mostly rifles) have an alt ability that iterates between attachments above and fire modes:
    - when holding a rifle, press RMB to change attachment, or hold RMB to change firemode.
  - upgradeable to tier 6+1 (only levels 3-5).
- ranged weapons can be crafted or found in according biome chests;

- added 8 shields with unique enhanced mechanics:
  - tiers 4 (2), 5 (4), 6 (1), 6+1 (1);
  - passive status effects (apply when in hand);
  - active status effects (apply when the shield is raised);
  - press and hold can do different things (hold usually raises shield, press does something else);
  - perfect block (basic mechanic);
  - charged block (holding a raised shield will apply an effect/do something on release);
  - upgradeable to tier 6+1, just like weapons (only levels 4-5).
- shields can be crafted or found in according biome chests (Calin, Crystalline Prime, Ioncore, EDS Grounds, Evastaris);

- added 4 throwable items:
  - added a `Ceterteal Glowstick`;
  - added a `Phosphonade`;
  - added a `Vortex Nade`;
  - added an `Astera Tear`;

- added 14 basic alta objects - found in [Alta Tier 1 Pod](https://github.com/Ceterai/Enternia/wiki/Alta-Tier-1-Pod) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 12 alta city objects - found in [Alta Tier 2 Pod](https://github.com/Ceterai/Enternia/wiki/Alta-Tier-2-Pod) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 12 alta lab objects - found in [Alta Tier 3 Pod](https://github.com/Ceterai/Enternia/wiki/Alta-Tier-3-Pod) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 16 alta ship objects - found in [Alta Tier 4 Pod](https://github.com/Ceterai/Enternia/wiki/Alta-Tier-4-Pod) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 8 EDS objects - found in [EDS Pod](https://github.com/Ceterai/Enternia/wiki/EDS-Pod) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 10 special alta objects - crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- updated existing alta objects;

- added alta drones & droids and reworked old ones:
  - small alta drones:
    - `Alta Scout Drone` - Tier 1, Peaceful
      - `Alta Crystal Drone`
      - `Alta Orchid Drone`
    - `Alta Security Drone` - Tier 2, Peaceful
      - `Alta Elin Drone`
      - `Alta Companion Drone`
    - `Alta Watcher Drone` - Tier 3, Aggressive
      - `Alta EDS Drone`
      - `Alta Ionic Drone`
    - `Alta Elite Drone` - Tier 4, Aggressive
      - `Alta Defensive Drone`
      - `Alta Lava Drone`
    - `Alta Mini Drone` - Tier 0, Aggressive
  - miniboss alta drones
    - `Alta Shield Drone` - Tier 1, Peaceful
    - `Alta Sentry Drone` - Tier 2, Peaceful
    - `Alta Engineer Drone` - Tier 3, Aggressive
    - `Alta Frigate Drone` - Tier 4, Aggressive
      - `Empty Alta Frigate Drone`
  - small alta droids
    - `Alta Spider Droid` - Tier 3, Aggressive
      - `Alta EDS Droid`
    - `Alta Elite Droid` - Tier 4, Aggressive
      - `Alta Stalker Droid`
  - miniboss alta droids
    - `Alta Defensive Droid` - Tier 3, Aggressive
    - `Alta Gheatsyn Droid` - Tier 4, Aggressive (WIP)

**Other:**

- added more loot items to later create more biome chests;
- added missing recipes for some objects;
- fixed some of the broken effects;
- updated all loot tables with new objects and items;
- reduced the size of the mod and removed unnecessary files, moved more materials to the deprecated folder;
- minor bug fixes.

## Update 1.6 - Crystal Rapture

### 1.6.1

A big bugfix update that brings to life a lot of features that previously were almost or completely broken! This includes elite back armor, turrets, saplings, spawners, etc.  
The update also cleans up the mod significantly and does some restructuring to prepare it for the next version!  
Other small things like adding missing recipes, fixing objects scripts, sounds and positioning and many more.

> **Note**: planning on gradually removing deprecated resources starting from 1.8, use [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station) to exchange them if you have any.

**Main:**

- cleaned up the mod significantly by removing unused resources and reusing certain assets;
- restructured certain folders to make them easier to navigate and prepare it for 1.7 update;
- moved all deprecated resources to the deprecated folder (again);
- moved all parallaxes to the parallax folder (left old copies in their places for compatability);
- updated 5 codexes (text, formatting, price).

**Alterash Prime:**

- fixed [Phosphobulb](https://github.com/Ceterai/Enternia/wiki/Phosphobulb) sounds and effects;
- fixed [Isoslime Spawner](https://github.com/Ceterai/Enternia/wiki/Isoslime-Spawner)s - they now work as intended.

**Alta:**

- fixed [Dreamer Set](https://github.com/Ceterai/Enternia/wiki/Dreamer-Set) giving a [Perfectly Generic Item](https://github.com/Ceterai/Enternia/wiki/Perfectly-Generic-Item) instead of the helmet;
- fixed all set and loot item sounds, visuals and particles;

- added proper visuals to [Elite Protector](https://github.com/Ceterai/Enternia/wiki/Elite-Protector) and [Elite Generator](https://github.com/Ceterai/Enternia/wiki/Elite-Generator) items;
- added proper visuals to [Alta Drone Spawner](https://github.com/Ceterai/Enternia/wiki/Alta-Drone-Spawner) and finished it (no longer WIP);
- fixed turrets (no longer crash the game and now work properly, with sound etc).

**Other:**

- added fix recipes for all remaining deprecated objects and items to [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station);
- added recipes for all remaining mod objects to [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor) (enterash and stardust ones);
- marked all deprecated objects and items as "Outdated" and updated their descriptions;
- fixed positioning for all crafting tables and other objects;
- fixed [Autoeffect](https://github.com/Ceterai/Enternia/wiki/Autoeffect) and [Electric Aura](https://github.com/Ceterai/Enternia/wiki/Electric-Aura) status effects and their derivatives;
- fixed any resources that were using or linking to deprecated resources;
- removed certain recipes that no longer should exist;
- added small descriptions to every update in the changelog and fixed update descriptions before 1.2;
- minor bug fixes.

### 1.6.0

Welcome to the crystal carnaval! This update adds tons of new crystal-based decorations and items to [Alterash Prime](https://github.com/Ceterai/Enternia/wiki/Alterash-Prime) planets!
It also adds lots of throwable items, like grenades, flares, javelins, toys, etc., as well as ways to obtain them.  
Finally, the update adds a [Guide Book](https://github.com/Ceterai/Enternia/wiki/Guide-Book) that can help you get through the mod and see all of it!

**Main:**

- added in total 80 objects: 1 sapling, 1 misc, 2 crafting, 66 decor, 1 farmable, 9 natural;
- added in total 80 items: 22 throwables, 50 cooked food (8 C, 12 U, 14 R, 16 L), 4 ingredients, 2 store food, 2 material;
- added in total 1 biome: [Gheatorn](https://github.com/Ceterai/Enternia/wiki/Gheatorn);
- added in total 16 tree foliage/stem types: [Yaara](https://github.com/Ceterai/Enternia/wiki/Yaara) 2 stem 3 fol, [Tonnova](https://github.com/Ceterai/Enternia/wiki/Tonnova) 2s 1f, [Aric](https://github.com/Ceterai/Enternia/wiki/Aric) 1s 4f, [Ayaka](https://github.com/Ceterai/Enternia/wiki/Ayaka) 2s 1 roots;
- added in total 12 effects and added icons to all new and old ones;
- added in total 20 codexes;
- added in total more than 100 recipes for all the new and some old items, objects, etc (now total is 483);
- added a goalbook for those who like to have something to work towards - [My Enternia Guide](https://github.com/Ceterai/Enternia/wiki/My-Enternia-Guide).
- the [Guide](https://github.com/Ceterai/Enternia/wiki/Guide) contains a small list of things you can get/do to consider the mod played through;
- the [Guide](https://github.com/Ceterai/Enternia/wiki/Guide) can be bought at Treasured Trophies or Tabula Rasa.

**Alterash:**

- added [Aya Vine](https://github.com/Ceterai/Enternia/wiki/Aya-Vine) ceiling roots that can spawn in [Ayaka Forest](https://github.com/Ceterai/Enternia/wiki/Ayaka-Forest) and drop [Aya](https://github.com/Ceterai/Enternia/wiki/Aya) and [Aya Powder](https://github.com/Ceterai/Enternia/wiki/Aya-Powder);
- added 6 decorative yaara furniture - found in [Yaara Orb](https://github.com/Ceterai/Enternia/wiki/Yaara-Orb) in [Yaara](https://github.com/Ceterai/Enternia/wiki/Yaara) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 8 decorative warped furniture - found in [Warped Chest](https://github.com/Ceterai/Enternia/wiki/Warped-Chest) in [Warped](https://github.com/Ceterai/Enternia/wiki/Warped) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added [Warped Hive](https://github.com/Ceterai/Enternia/wiki/Warped-Hive) - a throwable item, an improved analog of a regular throwable hive;
- added [Warped Hive Seed](https://github.com/Ceterai/Enternia/wiki/Warped-Hive-Seed) - can harvest for [Warped Hive](https://github.com/Ceterai/Enternia/wiki/Warped-Hive), found in [Warped](https://github.com/Ceterai/Enternia/wiki/Warped) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added [Ceternia Core](https://github.com/Ceterai/Enternia/wiki/Ceternia-Core) - drops from [Yaara Heart](https://github.com/Ceterai/Enternia/wiki/Yaara-Heart), used for crafting tier 6 armor instead of [Yaara Root](https://github.com/Ceterai/Enternia/wiki/Yaara-Root);
- added [Yaara Node](https://github.com/Ceterai/Enternia/wiki/Yaara-Node) trees - found in [Yaara](https://github.com/Ceterai/Enternia/wiki/Yaara) biomes - can have 2 stems and 3 foliages with different drops;
- added [Yaara Eye](https://github.com/Ceterai/Enternia/wiki/Yaara-Eye) - drops from [Yaara Bulb](https://github.com/Ceterai/Enternia/wiki/Yaara-Bulb) or some [Yaara Node](https://github.com/Ceterai/Enternia/wiki/Yaara-Node) trees, used for cooking and crafting some decorations;
- updated [Yaara Root](https://github.com/Ceterai/Enternia/wiki/Yaara-Root) from produce to ingredient, now drops from all yaara objects;
- fixed planet horizon graphic freakout (wrong colors);
- updated existing biomes with new stuff.

**Alterash Prime:**

- added 12 decorative bishyn furniture - found in [Bishyn Chest](https://github.com/Ceterai/Enternia/wiki/Bishyn-Chest) in [Bishyn](https://github.com/Ceterai/Enternia/wiki/Bishyn) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 12 decorative calin furniture - found in [Calin Chest](https://github.com/Ceterai/Enternia/wiki/Calin-Chest) in [Calin](https://github.com/Ceterai/Enternia/wiki/Calin) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 12 decorative hevika furniture - found in [Hevika Chest](https://github.com/Ceterai/Enternia/wiki/Hevika-Chest) in [Hevika](https://github.com/Ceterai/Enternia/wiki/Hevika) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 16 decorative gheatsyn furniture - found in [Gheatsyn Chest](https://github.com/Ceterai/Enternia/wiki/Gheatsyn-Chest) in [Gheatsyn](https://github.com/Ceterai/Enternia/wiki/Gheatsyn) biomes or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added 8 natural gheatsyn objects - they drop [Gheatsyn Shard](https://github.com/Ceterai/Enternia/wiki/Gheatsyn-Shard) used in crafting, cooking or as a throwable;
- added [Gheatorn](https://github.com/Ceterai/Enternia/wiki/Gheatorn) biome - a [shallow underground](https://github.com/Ceterai/Enternia/wiki/shallow-underground) layer biome;
- added [Bulbonid](https://github.com/Ceterai/Enternia/wiki/Bulbonid) natural object - a very tall plant that grows in the dark, found in [Bionid](https://github.com/Ceterai/Enternia/wiki/Bionid) biomes;
- added [Isoslime Ball](https://github.com/Ceterai/Enternia/wiki/Isoslime-Ball) - throwable resource that now drops in [Isoslime](https://github.com/Ceterai/Enternia/wiki/Isoslime) biomes instead of regular slime;
- added [Tonna](https://github.com/Ceterai/Enternia/wiki/Tonna) - a throwable cooking ingredient, now drops from [Tonnova](https://github.com/Ceterai/Enternia/wiki/Tonnova) trees in [Tonnova Grove](https://github.com/Ceterai/Enternia/wiki/Tonnova-Grove) biomes;
- updated existing biomes with new stuff.

**Alta:**

- reworked all cooked food and divided it into 4 cuisines + mixed one;
- each cuisine uses specific ingredients and has shared effects specific to this cuisine;

- added [Gear Set](https://github.com/Ceterai/Enternia/wiki/Gear-Set) items - when used they give you a full set of armor and gear of certain type (useful for testing etc);
- added [Gear Set](https://github.com/Ceterai/Enternia/wiki/Gear-Set) items for all gear added by this mod;
- certain codexes are now included with some gear sets as lore of that set;

- added a number of toy items, that can be found randomly in chests;
- added 5 grenades - can be crafted at [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) in [Equipment](https://github.com/Ceterai/Enternia/wiki/Equipment) tab;
- added 2 new color glowsticks and advanced [Hevika Flare](https://github.com/Ceterai/Enternia/wiki/Hevika-Flare) items;
- added [Hevika Javelin](https://github.com/Ceterai/Enternia/wiki/Hevika-Javelin) throwable hunting spears that can be upgraded at [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station);
- new glowsticks, flares and javelins can be found in [Hevika Chest](https://github.com/Ceterai/Enternia/wiki/Hevika-Chest) in [Hevika](https://github.com/Ceterai/Enternia/wiki/Hevika) biomes;

- [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) now has a tier 6 tab for all gear/throwables that normally can only be found as loot;
- [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) now has a tab for all gear sets as items - [Gear Sets](https://github.com/Ceterai/Enternia/wiki/Gear-Sets);
- [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) now requires certain codexes to be upgraded (can be found in chests or crafted at [Alta Datacenter](https://github.com/Ceterai/Enternia/wiki/Alta-Datacenter));

- added [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor) - crafting table (6 tiers) for all objects and loot tables added by the mod and more;
- added [Alta Datacenter](https://github.com/Ceterai/Enternia/wiki/Alta-Datacenter) - crafting table (1 tier) for all codexes added by the mod;
- moved object recipes and tabs from [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) to [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- tier 6 of [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor) allows to craft naturally occuring objects and loot tables, which are unobtainable otherwise;
- both new crafting tables can be crafted at [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station);

- reworked mod saplings, they now [Uncommon](https://github.com/Ceterai/Enternia/wiki/Uncommon) and can be sold for pixels and crafted with default params ([Garden Ayaka](https://github.com/Ceterai/Enternia/wiki/Garden-Ayaka));
- ayaka saplings are now called [Alterash Sapling](https://github.com/Ceterai/Enternia/wiki/Alterash-Sapling) and are also used for [Yaara Bush Tree](https://github.com/Ceterai/Enternia/wiki/Yaara-Bush-Tree);
- added [Alta Lab Sapling](https://github.com/Ceterai/Enternia/wiki/Alta-Lab-Sapling) - [Rare](https://github.com/Ceterai/Enternia/wiki/Rare) sapling used for [Aric](https://github.com/Ceterai/Enternia/wiki/Aric) and [Tonnova](https://github.com/Ceterai/Enternia/wiki/Tonnova) trees, can be sold or crafted with default params ([Tonnova](https://github.com/Ceterai/Enternia/wiki/Tonnova));

- added [EDS Lifechamber](https://github.com/Ceterai/Enternia/wiki/EDS-Lifechamber) - an improved version of [Lifechamber](https://github.com/Ceterai/Enternia/wiki/Lifechamber). Found in [EDS Grounds](https://github.com/Ceterai/Enternia/wiki/EDS-Grounds) or crafted at [Alta Constructor](https://github.com/Ceterai/Enternia/wiki/Alta-Constructor);
- added [EDS Table](https://github.com/Ceterai/Enternia/wiki/EDS-Table) - a decorative table;
- updated [EDS Status Pod](https://github.com/Ceterai/Enternia/wiki/EDS-Status-Pod), which now has proper visuals/params and can spawn on tier 4-5 planets added by the mod;

- updated same gear sets and fixed their effects.

**Other:**

- enhanced [Ayaka](https://github.com/Ceterai/Enternia/wiki/Ayaka) stem, [Tonnova](https://github.com/Ceterai/Enternia/wiki/Tonnova) stem and [Aric](https://github.com/Ceterai/Enternia/wiki/Aric) foliage variations;
- adjusted and reworked params and descriptions for many objects;
- fixed codexes not appearing in library after discovering;
- fixed broken effects of certain sets;
- updated all loot tables with new codexes, objects and items;
- added alta shop items to all vending machines (protectorate, space station, peacekeeper, hylotl);
- added more useful recipes;
- moved all recipes that turn mod materials into standard ones to [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station);
- minor bug fixes.

## Update 1.5 - Alterash Prime

### 1.5.0

[Alterash Prime](https://github.com/Ceterai/Enternia/wiki/Alterash-Prime) is here! Explore a new planet type added by this mode - like alterash, but colder, harder to traverse, with lots of layers and new biomes!  
The update also adds tier 5 and 6 armor sets, as well as loot items and set items! Loot items contain loot from corresponding chests, and set items contain full sets of armor of a specific type.

**Main:**

- added new planet type - [Alterash Prime](https://github.com/Ceterai/Enternia/wiki/Alterash-Prime);
- added in total 48 objects, 5 items, 18 biomes;
- added in total 26 tree types, 1 bush type, over 100 recipes;
- updated [EDS Table](https://github.com/Ceterai/Enternia/wiki/EDS-Table) (now [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station)) with new interface, new recipes and categories;
- added level 6 upgrade to [Alta Crafting Station](https://github.com/Ceterai/Enternia/wiki/Alta-Crafting-Station) with recipes for every mod object and more;
- added [Loot Box](https://github.com/Ceterai/Enternia/wiki/Loot-Box) items - when used they drop loot from certain (biome) chests from the mod;
- updated some ids (use the [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station) to convert deprecated items or get rewards for lost items).

**Alterash Prime:**

- added 1 atmosphere biome ([Eva Prime](https://github.com/Ceterai/Enternia/wiki/Eva-Prime)) with clouds and bg stat effects;
- added 4 surface biomes ([Alterash Prime Gardens](https://github.com/Ceterai/Enternia/wiki/Alterash-Prime-Gardens), [Alta Prime Labs](https://github.com/Ceterai/Enternia/wiki/Alta-Prime-Labs), [EDS Grounds](https://github.com/Ceterai/Enternia/wiki/EDS-Grounds), [Tavriya](https://github.com/Ceterai/Enternia/wiki/Tavriya));
- added 4 subsurface biomes ([Calocaves](https://github.com/Ceterai/Enternia/wiki/Calocaves), [Crystalline Prime](https://github.com/Ceterai/Enternia/wiki/Crystalline-Prime), [Isoslime Plasts](https://github.com/Ceterai/Enternia/wiki/Isoslime-Plasts), [Phospholion Mines](https://github.com/Ceterai/Enternia/wiki/Phospholion-Mines));
- added 2 shallow underground biomes ([Hidden Alta Labs](https://github.com/Ceterai/Enternia/wiki/Hidden-Alta-Labs), [Tonnova Grove](https://github.com/Ceterai/Enternia/wiki/Tonnova-Grove));
- added 4 mid underground biomes ([Alta Lab Debris](https://github.com/Ceterai/Enternia/wiki/Alta-Lab-Debris), [Bishyn Halls](https://github.com/Ceterai/Enternia/wiki/Bishyn-Halls), [Hevika](https://github.com/Ceterai/Enternia/wiki/Hevika), [Shroomic Depths](https://github.com/Ceterai/Enternia/wiki/Shroomic-Depths));
- added 2 deep underground biomes ([Hevika Tunnels](https://github.com/Ceterai/Enternia/wiki/Hevika-Tunnels), [Ionic Hive](https://github.com/Ceterai/Enternia/wiki/Ionic-Hive));
- added 1 core biome ([Barren Ion Core](https://github.com/Ceterai/Enternia/wiki/Barren-Ion-Core));
- added 37 new natural objects that can be found on [alterash prime](https://github.com/Ceterai/Enternia/wiki/alterash-prime) planets.

**Alterash:**

- updated planet descriptions;
- fixed a crash because of the [Snowy Alterash Ridges](https://github.com/Ceterai/Enternia/wiki/Snowy-Alterash-Ridges) biome generation;
- rebalanced object spawns for some biomes.

**Alta:**

- added [EDS Halter](https://github.com/Ceterai/Enternia/wiki/EDS-Halter)s - 5 different types of alta tank traps;
- added [EDS Status & Defensive Pod](https://github.com/Ceterai/Enternia/wiki/EDS-Status-Pod)s (WIP), [EDS Turret](https://github.com/Ceterai/Enternia/wiki/EDS-Turret)s (WIP), [EDS Retainer](https://github.com/Ceterai/Enternia/wiki/EDS-Retainer)s (WIP);
- added 2 other alta misc objects - [Alta Energy Source](https://github.com/Ceterai/Enternia/wiki/Alta-Energy-Source) and [Alta Drone Spawner](https://github.com/Ceterai/Enternia/wiki/Alta-Drone-Spawner) (WIP);
- added alta soda recipes to more original vending machines;
- added [Combat Set](https://github.com/Ceterai/Enternia/wiki/Combat-Set) - lvl 5 alta armor set (WIP);
- added [Elite Set](https://github.com/Ceterai/Enternia/wiki/Elite-Set) - lvl 6 alta armor set (WIP);
- added [Dreamer Set](https://github.com/Ceterai/Enternia/wiki/Dreamer-Set) - lvl 6 alta armor set (WIP);
- added 3 bonus helmets to already existing alta sets;
- added [VR Headset](https://github.com/Ceterai/Enternia/wiki/VR-Headset) - lvl 1 cosmetic hat;
- fixed some codexes.

**Other:**

- added palettes folder with palettes commonly used in the mod;
- updated coloring options for all armors & clothing;
- updated icons for some effects;
- updated biome chest loot tables;
- biome chest loot tables now can also drop their according loot boxes as bonus loot, meaning loot boxes can also drop themselves;
- minor bug fixes.

## Update 1.4 - Exploration & Restoration

### 1.4.2

This is an urgent update that fixes a game-crashing bug related to biome generation on some [Alterash](https://github.com/Ceterai/Enternia/wiki/Alterash) planets.  
It also does some minor fixes related to biome spawns and treasure.

**Main:**

- updated icons for some effects;
- adjusted rarity, price, other params of more objects;
- minor bug fixes.

**Alterash:**

- adjusted biome spawns;
- adjusted chest loot tables;
- fixed a major liquid generation bug with the [Flooded Caves](https://github.com/Ceterai/Enternia/wiki/Flooded-Caves) biome that caused the game to crash.

### 1.4.1

This update does a rework of all loot found in chests across the mod, as well as focuses on updating status effects and expanding the crafting station.

**Main:**

- added icons and names to some effects;
- updated [Ionic Stroke](https://github.com/Ceterai/Enternia/wiki/Ionic-Stroke) effect;
- changed effects of some decorative clothing items;
- fixed visuals and coloring of some clothing items;
- adjsuted prices and rarity of some clothing items;
- adjusted rarity, price, other params of some objects;
- minor bug fixes.

**Alterash:**

- adjusted spawns in some biomes;
- reworked chest loot tables.

**EDS Station:**

- updated interface and descriptions;
- added tier 5 and [Envirosuit Set](https://github.com/Ceterai/Enternia/wiki/Envirosuit-Set);
- added missing recipes for some items and objects;
- fixed recipes for certain resources;
- reworked some of the recipes.

### 1.4.0

A major update that significantly expands alterash planets by adding a lot of unique biomes, weather, plants and decorative clothing items.  
It also adds the [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station) - a crafting table where you can exchange any deprecated items for new ones, or trade [Perfectly Generic Item](https://starbounder.org/Perfectly_Generic_Item)s for some gifts. Here you can also convert mod crafting materials and other items into standard Starbound resources.

**Main:**

- added in total 24 objects, 45 items, 6 biomes, 10 effects, 1 weather type;
- added the [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station) - for converting deprecated items into useful, for converting perfectly generic items into decorative clothing/objects;
- updated some ids (...again. Sorry for that. Use the [Deprecation Station](https://github.com/Ceterai/Enternia/wiki/Deprecation-Station) to convert deprecated items or get rewards for lost items).

**Alterash:**

- added 1 asteroid biome ([Moonrock Space Islands](https://github.com/Ceterai/Enternia/wiki/Moonrock-Space-Islands)) with custom objects and enemies (and rewards);
- added 1 atmosphere biome ([Evostaris](https://github.com/Ceterai/Enternia/wiki/Evostaris)) with prism ore and crystals;
- added 4 surface biomes (2 common ([Alterash Riversides](https://github.com/Ceterai/Enternia/wiki/Alterash-Riversides), [Ayaka Forest](https://github.com/Ceterai/Enternia/wiki/Ayaka-Forest)), 2 uncommon ([Snowy Alterash Ridges](https://github.com/Ceterai/Enternia/wiki/Snowy-Alterash-Ridges), [Enchanted Meadows](https://github.com/Ceterai/Enternia/wiki/Enchanted-Meadows)));
- added new objects to surface biome [Alterash Labs](https://github.com/Ceterai/Enternia/wiki/Alterash-Labs);
- added new objects to underworld biome [Underworld Forests](https://github.com/Ceterai/Enternia/wiki/Underworld-Forests);
- added new tree type for the [Alterash Riversides](https://github.com/Ceterai/Enternia/wiki/Alterash-Riversides) biome;
- added 1 object (reeds) for the [Alterash Riversides](https://github.com/Ceterai/Enternia/wiki/Alterash-Riversides) biome;
- added bg bushes (reeds) for the [Alterash Riversides](https://github.com/Ceterai/Enternia/wiki/Alterash-Riversides) biome;
- added beakseed spawns to the [Enchanted Meadows](https://github.com/Ceterai/Enternia/wiki/Enchanted-Meadows) biome;
- added snowy dungeons to surface biome [Snowy Alterash Ridges](https://github.com/Ceterai/Enternia/wiki/Snowy-Alterash-Ridges);
- added 2 more possible planet descriptions;
- added 1 weather type ([Ionic Peak](https://github.com/Ceterai/Enternia/wiki/Ionic-Peak)) - creates radiowaves that worsen player's overall condition;
- moved tsay wild crops to the [Yaara Groves](https://github.com/Ceterai/Enternia/wiki/Yaara-Groves) biome;
- rebalanced object spawns for some biomes;
- enhanced [Alterash](https://github.com/Ceterai/Enternia/wiki/Alterash) tier 1 and 2 chest loot tables with themed decorative clothing, furniture and other (music, drills);
- removed [Orbital Strike](https://github.com/Ceterai/Enternia/wiki/Orbital-Strike) from weather configs - replaced with [Ionic Peak](https://github.com/Ceterai/Enternia/wiki/Ionic-Peak).

**Other:**

- added 6 objects (2 lights, 2 hazards, 2 decor);
- added 38 clothing items (7 hats, 3 backs) - paintable;
- added 1 augment and 1 collar;
- added 10 effects ([Life Support System](https://github.com/Ceterai/Enternia/wiki/Life-Support-System), [Asirai's Potential](https://github.com/Ceterai/Enternia/wiki/Asirai's-Potential), [Asirai's Energy](https://github.com/Ceterai/Enternia/wiki/Asirai's-Energy), [Ionic Stroke](https://github.com/Ceterai/Enternia/wiki/Ionic-Stroke), [Electroblockade](https://github.com/Ceterai/Enternia/wiki/Electroblockade), [Energizer](https://github.com/Ceterai/Enternia/wiki/Energizer), etc.);
- rebalanced prices for many objects;
- rebalanced weapon damage for some weapons;
- changed abilities of the spear, renamed it and added Asirai as a separate secret weapon with slightly different abils and params.

## Update 1.3 - Alterash

### 1.3.1

A small bugfix update that focuses on recipes and biome content. Oh, and also the water on all mod planets is now electric. Enjoy!

- fixed recipes;
- changed some item colors and attributes;
- updated treasurepools;
- updated biome spawns;
- water is now electrified;
- bug fixes.

### 1.3.0

Welcome to **Alterash**! This update adds alterash planets that can be found mainly around temperate stars and replace the old planet type.

- 14 new biomes (including 4 core biomes and 8 cave biomes);
- complete rework of old 6 biomes;
- 5 new weather conditions and rework of old 3 ones;
- 4 new weather presets;
- weather will now be chosen randomly for each planet from presets;
- 15+ new objects;
- 8+ new monsters and complete rework of old 3 ones;
- technical stuff like custom terrain generators and projectiles;
- a unique horizon graphic;
- custom parallaxes for surface biomes;
- codexes that make more sense;
- recipe rework;
- crafting station (4 levels) for everything mod-related;
- major changes to ids and descriptions;
- added underworld;
- made mode file structure closer to that of the game itself;
- reworked treasure throughout the planet majorly;
- added lots of categories of custom shrubbery for different biomes;
- 4 augments and 3 pet collars;
- 1 unique upgradeable weapon;
- 10+ new materials.

## Update 1.2 - Enternia Enhanced

### 1.2.1

A small preparation update that cleans up the mod a little and fixes minor bugs.

- minor improvements;
- slight restructuring;
- major code refactor;
- preparation for 1.3.

### 1.2.0

This update finally fixes the bug where the planet appears much, much bigger than it is. This was due to allowing incorrect liquids in the main biome that don't have a celestial graphic (mainly the healing water - don't put it in the main biome).

- fixed 'large planet' bug;
- added 2 new surface biomes and 3 underground biomes;
- completely reworked and rebalanced the planet - the old biome, all recipes, item stats, etc.;
- added 3 new capturable monsters, 1 new EPP and 2 new crafting materials;
- made the planet much harder to survive - added a planet hazard - ionized air, new weather - ionized rain, added teslaspikes and other hazards to spawn;
- reworked all monster spawns;
- changed possible planet difficulty to 4-6;
- changed possible dungeons;
- minor improvements.

## Update 1.1 - Enternia

### 1.1.0

This is a general expansion that adds a planet type and some content to it.

- desided to give the mod a proper name;
- added new planet type - [Enternia](https://github.com/Ceterai/Enternia/wiki/Enternia);
- added 1 new biome with a similar name;
- added a tree type for the new biome;
- added food and crops - [Aya](https://github.com/Ceterai/Enternia/wiki/Aya), [Gil](https://github.com/Ceterai/Enternia/wiki/Gil) and [Tsay](https://github.com/Ceterai/Enternia/wiki/Tsay), as well as prepared food made from them;
- added 1 upgradeable sword.

## Update 1.0 - Little Expansion

### 1.0.1

A small correction update that balances out the guns a little bit.

- adjusted gun prices;
- added piercing shot to SMGs.

### 1.0.0

Welcome to my mod! Hope you'll enjoy it as much as I do! ^^

- added a set of armor - the [C.T. Set](https://github.com/Ceterai/Enternia/wiki/C.T.-Set), including chest, legs and 2 helmets with unique abilities;
- added 2 upgradeable one-handed guns - [Fixed Point SMG](https://github.com/Ceterai/Enternia/wiki/Fixed-Point-SMG) and [Fixed Point Hyperblaster](https://github.com/Ceterai/Enternia/wiki/Fixed-Point-Hyperblaster);
- added 2 crafting materials - [Cetereye](https://github.com/Ceterai/Enternia/wiki/Cetereye) and [Ceter-Sphere](https://github.com/Ceterai/Enternia/wiki/Ceter-Sphere), that are needed to craft most of the mod items;
- these materials can be purchased at [Treasured Trophies](https://starbounder.org/Treasured_Trophies) or in [Tabula Rasa](https://steamcommunity.com/sharedfiles/filedetails/?id=737353165) if installed.