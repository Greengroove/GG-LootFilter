# GREENGROOVE'S LOOT FILTER SCRIPTS - CHANGE LOG

All notable changes to this project will be documented in this file. Please note that the log is referring to the endgame filter.

In detail information about the filter can be found [here](https://www.pathofexile.com/forum/view-thread/1566921).

## 3.12.x

- Moved the veiled item filter to the endgame section.

## 3.12.4b

- You can now hide Rogue's Markers in the Misc / Challenge section.
- Added filter for Heist gear in the Misc / Challenge section.
- Some changes to highlights for contracts, blueprints and alternate quality gems.
- Improved highlighting for "Prime Regrading Lens" "Secondary Regrading Lens" "Tempering Orb" "Tailoring Orb".
- Added highlighting for gems level 20 or higher or quality 20 or higher.
- Fixed Thief's Trinkets and fractured jewels not displaying correctly.

## 3.12.0

- Added a filter for Replica unique items.
- Added a filter for experimented base types.
- Added filters for alternate quality gems and a list to highlight the ones you are interested in. By default I listed the ones I'm interested in.
- Added filters for rogue equipment with the ability to hide non rares.
- Added to the new / unknown divination card list: "The Bitter Blossom" "The Cache" "The Academic" "Cursed Words"
- Added to the good divination card list: "The Gulf" "Triskaidekaphobia" "Unrequited Love" "Desecrated Virtue" "Brother's Stash"
- Added to the bad divination card list: "The Unexpected Prize" "The Journalist"

## 3.11.0e

- Changed appearance for grains and added a map icon.
- Fixed a bug because some rare gloves and boots wouldn't show when higher priority items were hidden, but lower still enabled.

## 3.11.0

- Added Harvest challenge league related items and other items specified in the [forum post](https://www.pathofexile.com/forum/view-thread/2873743).
- Added all new Divination cards to the good card list.
- "TO DO" Add editable list of bad uniques.

## 3.10.1f

- Added Explicit mod filter for Martinet's and Magister's.
- Added option to hide Blessed orbs.
- Added editable list of bad prophecies.

## 3.10.1c

- Added option to hide cluster jewels item level <= 74.
- Added filter for good veiled mods that can't be hidden.
- Changed highlights for a few Delirium challenge league items.
- Added minimum item level argument to some jewelry.
- Moved the leveling items switch to top of the block.
- Animate weapon filter is now less visible.

## 3.10.0

- Added Delirium challenge league items.
- Added "Sockets AA" with proper highlight.

## 3.9.1c (Endgame version only)

- Added Awakened Support Skill Gems.
- All normal rare items (that can't be hidden) are now affected by "Rare_items_minimum_item_level" slider and the slider can now go upt to item level 87.

## 3.9.0d

- Added MinimapIcon Blue Diamond to chisels.
- Added support for Crusader, Redeemer, Hunter and Warlord influenced map items.

## 3.9.0c

- Fixed not displaying Watchstones.

## 3.9.0b

- Updated class Warstaff to Warstaves.
- Added to the good divination card list: "Succor of the Sinless" "Etched in Blood" "The Escape" "Divine Justice" "Squandered Prosperity" "The Chosen"

## 3.9.0

- Added new map fragment types, Metamorph samples, Catalysts, new exalted orbs, "Awakener's Orb", "Ivory Watchstone" and changed sextant names.
- Just for reference - unknown card: "Underground Forest"
- First 3 essence tiers and T4 Harbinger Currency (Chaos Shard, Regal Shard, Binding Shard) moved to the endgame filter and will be hidden by default in the MF version.
- Fixed conflict with "The Wolf's Legacy" divination card.
- Improved highlighting for white Blighted maps.
- "Engineer's Shard" "Orb of Binding" "Horizon Shard" moved to the endgame filter and will be hidden by default in the MF preset.
- Changed the synthax for divination card to "==" to specify the exact name to avoid future conflicts.

## 3.8.0b

- Added special highlighting for "Black Oil" "Opalescent Oil" "Silver Oil" "Golden Oil".

## 3.8.0a

- Added option for extra highlighting for Orb of Alchemy in the Leveling Filter branch.
- Added option to highlight 4 linked rare Body Armour separate from Boots, Gloves, Helmets. 
- Removed "The Archmage's Right Hand" from the list of good divination cards.
- Changed highlighting for "Convoking Wand".
- Minimum "Racing_items_max_level" is now 60.
- Added option to display any jewelry till level 8.

## 3.8.0

- Added to the good divination card list: "Azyran's Reward" "Nook's Crown" "Remembrance" "The Bargain" "The Damned" "The Demon" "The Eye of Terror" "The Price of Loyalty" "Void of the Elements".
- Added to the bad divination card list: "The Mountain".
- Added Items related to the Blight challenge league. Some options available under ~Misc/Challenge leagues/Betrayal.
- Added veiled item filter by class with UI options in the "Special rares" tab. Disabling Veiled items is possible in the Block group browser (~ Misc/Challenge leagues/Betrayal).
- Added "Pristine Fossil" to the tier 1 fossil list.
- Added "Potent Chaotic Resonator" and "Potent Alchemical Resonator" to tier 2 resonators.
- Added ability to hide T4 "Wailing Essence".
- More blocks for rare items use the "|Disable" syntax. Affected rare items such as most weapons and some armour will be displayed with a small font when hidden.
- Moved the UI options for Fractured items below Elder and Shaper items.
- Few small adjustments to the racing and leveling filter.
- Moved "Orb of Alteration" to normal currency and "Orb of Augmentation" to low currency.
- Rare Accessories, top armour and weapons will now only use an alert sound in the leveling variation or when the "Leveling items" switch is enabled in the racing tab.

## 3.7.0a

- Updated the class for incubators and emblems as GGG changed the filter specification.
- Updated "Timeless Eternal Empire Emblem" to "Timeless Eternal Emblem", but the corresponding splinter name is still unclear, so I had to generalize. This will have to be re checked and updated after release.

## 3.7.0

- Added Incubators, Timeless Emblems and Splinters for Legion challenge league.
- Added to the good divination card list: "Alluring Bounty" "Buried Treasure" "Burning Blood" "Dark Dreams" "Pride of the First Ones" "The Archmage's Right Hand"
- Added to the bad divination card list: "Echoes of Love" "The Fool"
- Unknown cards (for reference): "The Primordial" "Thirst for Knowledge" "The Deep Ones" "Demigod's Wager"

## 3.6.3c

- Fixed: Filter was hiding Unique Shaped, Elder, Fractured and Synthesised items. Also updated the blocks that were hiding these items, not to filter unique items. 
- Chisels can no longer be hidden. When the block is disabled they only change appearance slightly and drop without sound. 

## 3.6.3

- **Parsed source code with Filterblast.**
- New slick tab with a comprehensive custom filter for Elder, Shaper and Fractured items.
- Identified fractured items receive a lesser highlight.
- Added one explicit mod for utility flasks and rearranged some blocks. Most of the explicit blocks are now grouped in a cluster. Switches moved to the Misc branch.
- Hidden currency now uses colored text for easier recognition when you press alt.
- Updated blocks for Betrayal and Delve.
- Quality flasks are now highlighted with font size 45.
- Normal skill and support gems no longer have a transparent background and are smaller and semi transparent when hidden.
- "Useful and drop only gems" and "Important currency for racing" now get a minimap icon.
- Portal scrolls get a racing override without transparency.
- Moved Breach rings to the rare items block. They are now a part of the Endgame block.
- Removed "Detonate Mines" from the useful and drop only gem list.

## 3.6.0

- Improved Shaper and Elder rare item handling. Some weapon bases and shields will receive lesser highlighting or can be hidden.
- Added Fractured and Synthesised items. They use the same filter as Elder and Shaper items.
- Any item that has a lab enchantment will be highlighted.
- Added to the good divination card list: "Alone in the Darkness" "Arrogance of the Vaal" "The Journey" "The Landing" "The Lord of Celebration" "The Mad King" "Monochrome" "Sambodhi's Vow" "The Seeker" "Seven Years' Bad Luck".
- Added to the bad divination card list: "Dark Temptation".
- Changed minimap icons for maps to white, yellow, red and brown squares.
- Divination cards are now blue squares on the minimap.
- All Breach splinters now use a blue, diamond shaped minimap icon.
- Tier 12 and 13 maps now display same as T11 maps. 
- Added minimap icons to some Harbinger related currency and updated the block.
- The custom map list now only contains one map and can no longer be disabled. Customize the list to your preference. If empty, it will automatically revert to the default setting.
- Added option to hide mediocre rare rings and amulets. These will be disabled by default in the MF version.
- Removed almost all old corrupted item filters. Kept rare jewelry, quivers and magic quivers.
- It is now possible to hide ItemLevel >= 84 "Two-Toned Boots" "Fingerless Silk Gloves" "Gripped Gloves" "Spiked Gloves" "Bone Helmet". These items are now being handled by the crafting block.
- Few other minor adjustments.

## 3.5.1c

- Removed mini map icons on rare jewelry.
- Removed "Loyalty" from the list of bad cards and added: "The Scholar" "The Gambler" "The Witch" "The King's Blade" "Struck by Lightning" "Rain of Chaos" "Doedre's Madness".
- Fixed the conflict with "The Master Artisan" Divination card.

## 3.5.1

- Fixed a small bug that showed all shaped maps as T1 items.

## 3.5.0

- Added an entry for items with veiled mod: "Veil".
- Added to the good divination card list: "The Sacrifice" "The Nurse".
- Scarabs are covered with the generic "Map Fragments" filter.
- Reworked the maps filter with the new syntax "MapTier". Thanks to Neversink for informing the community about the change.
- Added tier 2 effects on 91 items.
- Added mini map icon for lab keys and trinkets.
- A few minor fixes and changes.
- Please note that the "good map" list will have to be re evaluated at a later time.

## 3.4.2

- Added new Bestiary explicit mods.
- Added mini map icon to Chisels.
- Added switch in the leveling filter for Any 4+ link rare armour piece.
- "Work in progress" Added switch for 21+ Quality items in the branch dedicated to Delve.

## 3.4.1b

- Adjusted the highlights for Fossils.
- Low level resonators can now be hidden and have a lesser highlight.
- Unique items now use a brown circle mini map icons.
- Fixed visible mini map icons on hidden items. Only a problem with filter version 3.4.0e. Please re-download your filter.
- Changed from only showing stacks of 4 and higher of "Scroll of Wisdom" to showing stacks of any currency item.
- Changed the mini map icon for racing offhand items and added the icons to caster racing items.
- Fixed wrong border color on some linked racing wands and highlighting for normal jewels.
- Simplified the Incursion league block for better performance.

## 3.4.0e

- Added Yellow Circle minimap Icon on all maps, some currency and many other items. Currently 137 entries use the minimal icon overall.
- Added small brown square map icon for divination cards.
- Added permanent green beam on T1 items.
- Added option to show "Scroll of Wisdom" if 4 or more are stacked.
- Added Green Triangle map icon for some racing items.
- Fixed the linked racing shields not behaving as intended and a few other insignificant changes.

## 3.4.0

- **Added all items for Delve, listed in the patch notes.**
- Added map icons for items that use T1 and T2 sounds. T1 uses a big yellow star and the T2 items are displayed with a small yellow circle.
- Added to the good divination card list: "Beauty Through Death" "Boon of the First Ones" "The Endless Darkness" "The Price of Protection" "The Twilight Moon" "The Wilted Rose".
- Added to the explicit mod list: "Subterranean" "of the Underground" "of Weaponcraft" "of Spellcraft" "of Crafting".
- Changed appearance: "Divine orb" "Ancient Orb" "Orb of Annulment" "Stacked Deck" now use a black background and T2 sound instead T1.
- Changed chancing base to "Leather Belt".
- Other insignificant adjustments.

## 3.3.1c

- Added option to only show Perandus coins in stack of 4 and higher.

## 3.3.1

- **Heavily expanded the "ITEMS WITH EXPLICIT MOD" section. Most of the mod combinations are predefined, but jewels and flasks also feature a few block switches in the endgame block.**
- Maps with "Vaal" and "Zana's" explicit mod will always show.
- Changed highlighting for vials. "Vial of Awakening" "Vial of the Ghost" "Vial of Sacrifice" now look like exalted orbs.
- Adjusted the corrupted item handling to show less items.
- Added "Her Mask" to the bad divination card list.
- "Detonate Mines" gem is now hidden in the endgame filter.
- Fixed a few small bugs and some general improvements.
- Moved Abyss jewels to a new section.

## 3.3.0

- **Added all items for Incursion and a filter for Incursion explicit mods.**
- Added ability to highlight items with specific mods. An editable list is present in the "Misc" tab. This functionality is new and needs testing.
- Added to the good divination card list: "The Admirer" "The Undisputed" "The Hale Heart" "The Celestial Stone" "Perfection" "Immortal Resolve" "The Master" "The Mayor" "The Professor" "The Samurai's Eye" "The Sword King's Salute" "The Undaunted".
- Added ability to show leveled gems, with UI option in the "Misc" tab. By default gems with level 19 or higher will be displayed in the endgame filter.
- Updated the Warband filter to use "HasExplicitMod". The items will now be displayed by default.
- Added UI option for 3 linked shields for racing.
- Updated flasks progression to show more flasks as you are leveling.
- Magic wands for racing will now only show till level 9.
- Further tuning of the racing filter and many other insignificant improvements under the hood.
- The chancing items switch has been moved for easier access.

## 3.2.3

- Implemented the global "DisableDropSound" switch on Filterblast. All drop sounds are now disabled by default.
- Added new UI setting; Color for 3 linked offhand in the racing tab.
- Removed redundant magic weapons for racing and converted normal weapons to highlight any rarity instead.
- Racing Filter rework on "One Hand Mace", "Bows", "Quivers" and several smaller improvements on other weapon classes for racing.
- Reduced non top Net highlighting.
- Removed "Sorcerer Boots" from chancing bases.

## 3.2.0d

- **Updated and enhanced the racing section.** Added overrides: "Important currency for racing", "Starting weapons" and updated "Weapon with Increased Physical Damage Recipe" switch. More changes and some additions to racing accessories and a new Override section.
- Racing Filter rework on "One Hand Axe".
- Changed default background for "Racing items" to gray.
- Big utility flasks.
- Added "Siege Axe" To "Top rare weapons" and "Weapon crafting bases".
- Hidden items are now more visible.
- The default maximum level for racing items is now 67.
- Removed drop sound from low net tiers.

## 3.2.0c

- Added "Necromancy Net".
- Updated and expanded the "Bad Divination cards" list. **Removed:** "The Wolf's Shadow". **Added:** "A Mother's Parting Gift" "Cartographer's Delight" "Destined to Crumble" "Dying Anguish" "Loyalty" "Prosperity" "Rain Tempter" "The Doppelganger" "The Endurance" "The Flora's Gift" "The Hermit" "The Incantation" "The Inoculated" "The Lich" "The Lover" "The Sigil" "The Twins" "The Web".
- Better handling for nets.

## 3.2.0b

- Added "ElderMap True" (not announced in the patch notes), so the new map type will actually show on all filter versions. This is a critical update.

## 3.2.0a

- Adjusted highlighting for Nets.

## 3.2.0

- Added Bestiary and other 3.2 items (including "Elder Orb"). The drop sounds and visuals may be subject to change.
- **Added a complete filter overview PDF document to the repository.** [Reference Manual](https://github.com/Greengroove/GG-LootFilter/blob/master/GG%20Loot%20Filter%20Scripts%20-%20Complete%20overview.pdf)
- Added "The Obscured", "The Iron Bard", "The Breach", "The Dreamer" and "The World Eater" to the list of good Divination cards.
- Reverted the bad rare item list to no longer only affect items with item level lower than 84.
- Adjusted the Prismatic Jewel highlighting and some other minor fixes.
- Moved "Orb of Alteration" and "Jeweller's Orb" to "Low currency".
- Added sound for normal and magic RGB items in the leveling filter. 

## 3.1.1e

- **Redesigned the crafting filter to include items from the 2.4 expansion. The old ones were mostly removed, since they are no longer relevant.** The filter still works the same way as it did before, so any base type you wish to craft can be added to the list. As a consequence, the "2.4 AND HIGHER BASES" section has been simplified and the block switches removed. Most jewelry is kept, for the leveling process.
- Added a comprehensive list of good divination cards. Please note that it's still recommended to check all cards that drop.
- Added "The Surgeon", "The Metalsmith's Gift" and "Rain of Chaos" to the list of bad Divination cards.
- Updated the list of custom maps to include only maps up to T10, with decent layouts.
- **Added ability to set the minimum item level of rare items to be displayed.** Only affects non top rare items.
- Added an option to highlight any item level 84 and higher abyss jewels. Rare Abyssal jewels can no longer be hidden.
- Updated the list of top rare daggers.
- Added a link to PoEDB.
- Moved the chisel recipe to the leveling filter and some other minor adjustments related to this.
- Slightly reduced the sound volume for T1, T2 items and increased the Divination card sound. Renamed "Racing items" name tag to "Important items".
- Changed font size of hidden quality gems to 45.
- Updated the top flasks block.
- The bad rare item list now only affects items with item level lower than 84.
- Moved Maraketh wands to the endgame block and rare +3 bows and staves to the leveling block.
- Moved "Glassblower's Bauble" a tier higher since they are more valuable and much rarer than alterations.

## 3.1.1d

- Once again fixed the Shaped map drops. Hope this time it's for good. For extra safety measures you can keep enabled the "Low level maps in high level maps".
- Adjusted slider on the crafting filter to accommodate the new ilvl 85 and 86 mods.
- Removed link to the Pantheon Wiki page, as it is now redundant.

## 3.1.0e

- GGG has fixed the "ShapedMap True" argument, but now there's new problems. Shaped maps don't get filtered by "DropLevel". For this reason I have inserted a general filter that will show all maps until these problems are fixed for good. The custom maps list should also be fine to use.
- Reworked the "ALL 2.4 AND HIGHER BASES" block, to fix a minor problem, that caused two unwanted items to be highlighted in 3.1.0d.
- Improved highlighting for Steel and Opal rings.

## 3.1.0d

- Temporarily reverted "ShapedMap True" to the old system. It is unknown if this is temporary or permanent.
- Adjusted the minimum drop level of some items introduced in 2.4 to 70. This was causing the intended blocks to not work and could end up hiding these items in a very strict filter. The change was not documented in the patch notes.
- Removed some redundant entries and updated a few blocks for Abyss challenge league items.
- Adjusted scale for minimum rare shield drop level to 3.
- Moved "Useful and drop only gems", Vaal gems and gems with no quality to the Leveling Filter. These items can now be bought from NPCs, but the list can be useful for racing.
- Added ability to hide rare "Rustic Sash" and "Leather Belt".
- Added ability to hide "Divine Vessel". These will be hidden in the MF version by default.

## 3.1.0

- **Added support for Abyss challenge league and changes in 3.1.0, according to the official information.**
- Any Shaper and Elder items will be shown big, with green border, gray background and special sound, that is currently associated with racing drops. Subject to change in a future filter version. If these are disabled other regular filters will still apply.
- The "Custom maps" list now contains all maps up to T10. This list will be shortened at a later time when we know all the new and modified layouts.
- Removed "Leather Belt" from the chancing bases list.
- Added ability to hide Cartographer's Chisels (Hidden by default in the MF preset).
- Added ability to hide Breach splinters and rings.
- New branch in the Misc section for Challenge leagues.
- Normal and Magic endgame RGB items are now separated.
- Slightly lowered the T2 drop sound level.

## 3.0.2c

- Complete revamp of the corrupted items section and better visibility for hidden corrupted items.
- Added ability to change the background color for racing weapons in the color theme tab.
- Added filters for rare elemental thrusting swords and wands in the Endgame Filter.
- Added 10% or higher quality weapon switch in the Leveling Filter.
- Hidden superior gems are now highlighted.
- Added ability to display magic items with specific sizes till a level that is adjustable.
- Added a link to The Pantheon wiki page in the notes tab.
- FilterBlast now supports multiple values for SocketGroups. Applicable in the racing tab, example: RGB RGGB RRG.
- The Leveling filter now also shows big RGB items in maps. Added 2 new switches to enable showing large RGB items in maps.
- When Non top rare belts are disabled, they will still show normally when pressing alt.
- Added border around leveling rare boots.

## 3.0.1e

- Separated all map sounds and added a special sound set for rotations. This set is just like the default one, except that map sounds don't use any long sound effects.
- Changed and adjusted some sounds. Reverted all new sounds for Ex and Mirror to the old T1 sound. Oriath sound set, changed T2 sound.
- Added a "no no" exclusion list, for any rare item you do not want to see (ever). At least 1 item needs to listed here ("Splintered Tower Shield" is listed by default). The list starts to take effect from item level 15.
- Moved "Exalted Shard" to T1, "Harbinger's Shard" to T3 and "Horizon Shard" to T4 shards.
- Added ability to set font size for non top rare items.
- Updated crafting section and added ability to set font size.
- Separated "Alchemy Shard" from other low shards.
- Updated, to show less corrupted items by default.

## 3.0.1d

- **Introducing Sound Themes!** Two brand new themes and enhanced sound options. USE THE NEW SOUNDS AT YOUR OWN RISK!
- Added a link to the Unique items Wiki page.
- Some small adjustments, due to the addition of sound themes.

## 3.0.1

- **Introduced a new (necro) color theme named Atlantisite.**
- Slightly enhanced the map drop progression and reworked the Custom maps list.
- Silver Coin now use the T4 drop sound instead T2.
- Added ability to hide 5 socket 5 links.
- Merged the rare weapon progression blocks with the rare weapons in the leveling filter (simplification).
- Added ability to change drop sound for Exalts, Mirrors and introduced a switch to globally change the new positional drop sounds (off by default).
- Changed the slider Large font size to Maximum font size. It now affects all font sizes and will reduce them proportionally.
- Added a link to the Vendor recipe Wiki page and PoEAffix.
- Added transparent background to Perandus coins.
- Added new Filterblast option "# no title" to the racing tab armour slots.
- Updated all color themes.
- Sound volume and some other small adjustments.

## 3.0.0

- Added items for Harbinger challenge league.
- Updated entries related to rare shields and added top shield bases to the armour crafting list.
- Added a new adaptive filter with advanced UI options for rare endgame weapons.
- Added ability to select crafting jewelry, removed and adapted old options accordingly.
- Added ability to target specific classes in the linked armour slots.
- Updated the lists for top rare items.
- Enabled highlighting for "Divine Vessel".
- Added sound for leveling rare boots.
- Removed "leather belt" from chancing bases.
- The filter now uses |Disable instead of |Comment commands.
- Added transparency to background for flask progressions to distinguish drops from currency.
- Added big label for Quicksilver flasks in races.
- Removed drop sound for Perandus coins.
- Many small adjustments and few fixes.

## 2.6.2

- Added "Divine Vessel" (Shows in the previous versions of the filter as well, but can be enabled for beta users to use additional highlighting).
- Updated and added links to PoE Wiki.
- Added transparent blue background for identified magic items.
- Updated the entry for 20% quality weapons to show all weapons as it was originally intended.
- Added magic Prismatic Jewel definition, so that it can't ever be hidden.
- Adjusted the filters for corrupted items, to work with Monstrous Treasure race type. Note that these items will now be removed instead of being hidden.
- Enhanced Linked armour Slots, so that they also work with 3 links till item level 24.
- Rearranged some blocks and advanced menu options. Separated Armour and Weapons in some blocks for rare items.
- Fixed: Diamond/Topaz Flasks missing in the Flask Block (issue 9).

## 2.6.0j

- **Updated the filterblast.config file to use color themes.**
- Added the @ sign in front of blocks that are associated with custom UI options.
- Changed the Youtube link to the loot filter tutorial playlist.

## 2.6.0i

- Added tags to sounds to support the sound editor on Filterblast.
- **Added the color and sound theme tabs.**
- **Redesigned UI and added notes tab.**
- Added ability to choose up to 4 color combinations for ideal >=4 links in races, with special drop sound.
- Expanded the filtering for rare two hand items.
- Small change to chest armour for racing and many other small adjustments.
- Added option to show small or any rare item till a certain level. The level can be set in the racing tab.
- Added text area in the notes tab to write your own notes.
- Added warning "~" sign to some blocks that are more sensible.
- Added Chain belt exclusion (Rarity <= Magic) and added all exclusions to the extra block.
- Adjusted the T3 and Racing items sound volume.
- Changed Filterblast UI to use some sliders instead of switches.

## 2.6.0h

- Changed formatting of the advanced Filterblast options to use tabs and default values.
- Added all maps with nice layout to list of custom maps.
- Added filter to show any corrupted map.
- Added new file for referencing default entries in the lists.
- Added ability to set item levels for crafting weapons and armour separately.
- Moved all gem and currency entries from the On recommended to the Endgame (MF) filter branch.
- Added "Lacquered Buckler" to all top base lists.
- Added ability to change the largest font size.
- Expanded the filter for corrupted items.
- Changed highlighting for some rare wands.
- Added some notes in the Filterblast UI.
- Added a second strict adaptive filter for Body armour racing purposes. Updated filter index.
- Small adjustments to the racing filter.

## 2.6.0g

- Added a customizable list for maps and moved higher map filters to the Endgame branch. 
- Added list option for gems to be highlighted.
- Added ability to toggle all bases of magic jewels individually.
- Updated various entries in the racing filter.
- Many minor label changes.

## 2.6.0f

- Moved the endgame crafting items to a top branch, added ability to choose crafting items item level and removed redundant entries. 
- Changed to only use 2 list for top rare bases.
- Added ability to toggle max item level for racing items, removed Endgame racing branch and added a second 4 link armour entry for races in high level areas.
- Added ability to toggle sound for best in slot caster items for races.
- Added Normal chest armour progression for racing.
- Renamed some and moved most branches in the Racing filter.
- Improved the quivers for racing section.
- Some other minor spelling changes and minor adjustments.

## 2.6.0e

- Added an an adaptive filter for shaped maps with option in Filterblast UI.
- Changed animate weapon items text to be completely transparent.

## 2.6.0d

- Removed "|Comment" syntax on some useless jewelry items, that are meant to be excluded permanently. **A total of 524 entries currently use this syntax.**
- Added ability to toggle mediocre Energy shield bases.
- Added ability to choose which utility flasks to highlight. Added option for drop sound and removed some old redundant entries.
- Added ability to choose normal or magic top flask bases separately and added 3 new sections related to this.
- Added exception for wands with cast speed in the Extras branch.
- Changed the 83/84 crafting bases to 84. Even tho most weapons only need ilvl 83, I choose to use 84 to simplify the filter in endgame.
- Expanded the top rare quiver block.
- Added links to change log, Github and social channels.
- Added ranged weapons to the animate weapon block.
- Added empty lines in the advanced options for better readability.

## 2.6.0c

- Added the advanced options back in as supposed.
- Added ability to enable or disable low level currency sounds (Blacksmith's Whetstone, Orb of Transmutation, Orb of Augmentation). This is useful for races or leveling in a new league.
- Changed leaguestones to have border color represent the rarity and added unique leaguestones just in case.
- Added "Leather Belt" to the chance bases.
- Added exception for low level magic items. Any magic item will now be displayed till level 9. Smaller magic items till level 13. Both by default in the leveling filter.
- Added exception for all low level normal armour items. These will now be displayed till level 10 by default in the leveling filter.
- The smart block section is now above the advanced options in Filterblast UI.
- Added download links in the filter files.
- Added link for donations in Filterblast.

## 2.6.0b

- **THIS VERSION IS NOT COMPATIBLE WITH FILTRATION! Use [Filterblast](http://filterblast.oversoul.xyz/Greengroove/) instead.**
- **A total of 491 entries currently use the "|Comment" syntax for better performance.**
- The filter will now be automatically updated on Filterblast whenever a new release is available.
- Updated Legacy challenge league items according to GGG's informations. 
- Added anotations to top level branches.
- Added ability to hide chancing items.
- Changed the section "VENDOR RECIPE ITEMS - RGB ITEMS <= MAGIC" to "VENDOR RECIPE ITEMS - RGB ITEMS" and enhanced both RGB sections.
- Updated the "JEWELS" section.
- Added class "Amulet" to Talismans and added ability to hide them.

## 2.6.0a

- **THIS VERSION IS NOT COMPATIBLE WITH FILTRATION! Use [Filterblast](http://filterblast.oversoul.xyz/Greengroove/) instead.**
- **A total of 479 entries currently use the "|Comment" syntax for better performance.**
- The "Sai" dagger is now included in the crafting weapons list. Redundant entries have been removed.
- Added ability to hide magic items from 2.4 release (Bone Helmet, Fingerless Silk Gloves, Gripped Gloves, Spiked Gloves, Two-Toned Boots) if ItemLevel <= 83.
- Added sound for all remaining 3 linked racing caster items.
- Removed 2 redundant entries for "Imbued Wand".
- Removed the redundant old Warbands filter.
- Minor change to order of some blocks and 2 sections.
- Minor update to quivers for racing and some other improvements to the most useless part of the filter. The Endgame racing block.

## 2.6.0

- **THIS VERSION IS NOT COMPATIBLE WITH FILTRATION! Use [Filterblast](http://filterblast.oversoul.xyz/Greengroove/) instead.**
- **Added all Legacy challenge league items.**
- Removed "Chiming Spirit Shield" and "Ivory Spirit Shield" from the top caster shield list and created a new block in the endgame branch.
- Added ability to hide rare RGB items in the endgame branch.
- Added ability to hide all magic jewels.
- Made the worst rare items slightly smaller and more transparent.
- Enhanced the animate weapon block.
- Expanded the shield section in the racing filter.
- Re evaluated  and changed the order of the lists in the advanced options, for easier customization.
- Removed redundant warning sign for the caster racing items.

## 2.5.2h

- **THIS VERSION IS NOT COMPATIBLE WITH FILTRATION! Use [Filterblast](http://filterblast.oversoul.xyz/Greengroove/) instead.**
- **Added "|Comment" to many entries in the rare items progressions (leveling rares). A total of 460 entries currently use the syntax.**
- Maps up to (and including) T8 are now hidden by default in the MF filter.
- Some minor changes to descriptions and fixed a bug with endgame racing daggers.

## 2.5.2g

- **Added advanced options for Filterblast users. You can now edit some of the base type lists and socket colors for racing caster items.**
- **Added "|Comment" to many entries. A total of 403 entries currently use the syntax. This can potentially improve performance drastically.**
- Added ability to hide yellow maps up to T10 in "ON RECOMMENDED" block.
- Fixed Animate weapons entries to show up in the "Extras" smart block like intended.
- Separated Scepters, daggers and wands in the racing filter.
- Removed some redundant annotations and unused attributes.
- Sai dagger for crafting was moved back to the endgame filter.
- Separated Vaal gems from other useful and drop only gems. Added ability to hide these blocks. The switch is in the endgame block.
- Added ability to hide Gems with quality lower than 8. The switch is in the endgame block.
- Added ability to hide all non top wands in the endgame block.

## 2.5.2e

- **Added advanced option text fields for chance items.**
- Separated magic and normal corrupted items.
- Added ability to hide DropLevel >= 47 daggers. This way you only see the top base daggers. This switch is currently in the endgame block.
- Added ability to hide Gems with quality lower than 14. The switch is in the "ON RECOMMENDED" block.
- Added ability to hide alteration, chance, chromatic and Jeweller's Orb as well as some generic currency blocks. The switches are in the "ON RECOMMENDED" block.
- Added ability to hide non top base rare belts. The switches are in the "endgame" block.

## 2.5.2d

- **Added advanced syntax (|Comment) to 320 entries in the racing block.** This is only a partial implementation. Full implementation to be completed when Filtration gets updated to support the advanced syntax.
- Revamped and improved customization for top crafting bases.
- Added toggle switches and advanced syntax (|Comment) to some jewelry in the racing block.
- Added ability to toggle Transmutation, Augmentation orbs.
- **Added Animate Weapon support.**
- **Renamed some entries related to Top base items. You can now search for "Top base" in Notepad to edit the lists of top base items.**

## 2.5.1

- Separated Armourer's Scrap, Whetstones and Baubles to separate entries.
- Enhanced display of normal corrupted jewelry, to better distinguish them from the other corrupted drops.
- removed the divination cards "The Lion" and "A Mother's Parting Gift" from the bad card list.
- The crude bow for Essence crafting is now hidden by default in the endgame version.
- Added ability to hide all quality flasks and slightly improved the order of entries. Added advanced syntax for utility flasks.
- Fixed a minor error in smart blocks for Breach related items.

## 2.5.0f

- **From this version on, the "default" versions will use a fixed name for better integration with GIT.** Note that in the future releases I may release some additional non "standard" versions depending on meta and or personal preference. These versions may be specific for a challenge league and not permanent.
- Added ability to toggle low level maps in high level maps (Endgame Filter block).
- Added ability to toggle rare wands DropLevel <= 44 and moved this block to a new section (Endgame Filter block). Also fixed minor issue with this blocks where DropLevel and ItemLevel were inverted.
- Added ability to toggle lower base rare daggers (Endgame Filter block).
- Added ability to toggle rare body armour (ItemLevel <= 63) in the leveling block.
- Magic jewels can now be hidden in yellow and red maps (T6 and higher). Previously this only affected jewels in red maps.
- Improved, renamed and fixed many labels in the block group browser.
- Moved Crude bow (Essence crafting) to the leveling block.
- Slightly reworked the "Quivers for racing" block.
- Removed redundant entry for quivers and daggers in the leveling block. Note that the bases "Golden Kris" and "Copper Kris" will not show if Normal or Magic after item level 63. The switch for these is in: Racing Filter > Normal Races > Caster Items  > Dagger.

## 2.5.0e

- Added exclusion for Normal and Magic Coral Amulet at level >= 72. Some other bases were already excluded.
- Added ability to hide top base scepters.
- Fixed a labeling issue with Shaper's orb introduced after filter optimization.
- Fixed the Breachstones not showing properly due to game bug or wrong information from GGG's side.

## 2.5.0d

- Added a game like color theme.
- Added ability to toggle wisdom scrolls and portal scrolls separately.
- Removed a redundant entry in the jewelry racing block. Added Paua Amulet, Amethyst and Unset Ring to exclusions. These bases will not be displayed. Added ability to toggle other magic and normal jewelry.
- Separated Life, mana and Hybrid flask progression and added ability to toggle blocks.
- Slightly modified hierarchy in the Flask block.
- Lesser items now have slightly more transparent background.
- Added to leveling block ability to hide (non rare) large RGB items ilvl <= 67.

## 2.5.0c

- Changed "rare identified items" to "rare corrupted items".
- Added <= Magic corrupted items. Now all corrupted items are covered by the filter.
- Optimized line ordering within each entry for most blocks in the filter. Especially the Racing block is now more optimal. These improvements are of minor positive impact to performance. Please note that the versions edited with Filtration may be less optimized.
- **Warband drops (Identified items) are handled a bit better. The block will display non corrupted identified items, of any item class that can be dropped by Warbands. The top bases are handled separately so this only affects lower bases. In the Endgame filter this will be hidden by default, but can be still seen when pressing the "Alt" key, after you fight a Warband.**
- updated themes to reflect the above changes.
- Fixed Bone Spirit Shield showing as rare when magic or lower.
- Added "Spiraled Foil" to top bases.
- Changed some highlighting in the racing block.
- Added a Sockets >= 2 Special exclusion to most white and magic armour drops to reduce clutter. This can be manually adjusted across the board.
- Magic and Normal Gold ring, Paua Ring, Moonstone Ring, Coral Amulet, Gold Amulet, Studded Belt and Cloth Belt bases are now hidden while leveling.
- Reworked the caster racing block and added corresponding block group, for editing in Filtration. Removed drop sounds. **Warning: Disabling in this block will hide some daggers and scepters!**
- Improved flask progression for leveling.

## 2.5.0a

- Separated Breachstones and added corrected class "Map Fragment".

## 2.5.0

- Added extra highlighting for the new Vaal Breach gem.
- Enabled the Breach filters.

## 2.4.8

- Added announced items for Path of Exile 2.5 Breach.
- Moved the Essence block above the Currency block.
- Renamed section "ALL 2.4 NEW BASES"

## 2.4.3b

- The racing filter is now disabled by default in the Endgame version of the filter.
- Some minor changes to the racing filter. Reworked some magic weapon progressions in the racing filter.

## 2.4.3a

- Changed highlighting for some mediocre hybrid items. These items can now be hidden with the MF block.
- Added Bone Spirit Shield as extra for the "Of animation flask" recipe. The flask is then used to make a +1 to Level of Minion Gems helmet.
- Added Hideout Doodads & Microtransactions just in case.
- Some minor changes to the 83/84+ crafting base blocks. Added normal jewelry and weapon crafting bases to the MF block.
- Removed unnecessary white spaces, hash tags and 2 sections.

## 2.4.2b

- Changed the section structure for magic and normal items slightly, to better accommodate the addition of identified magic item filtration. 

## 2.4.2a

- **Added any identified magic item block. Warbands members now drop their signature items already identified. Display similar to the rare identified items but with a light blue font color.**
- Chromatic items now use a grey background. Improvement to facilitate chromatic item detection for color blind people.
- Updated all theme files.

## 2.4.2

- **The leveling versions of the filter now have a t4 sound also for Transmutation and Augmentation orbs.**
- The large font size has been changed to 45 from 60. Max font size is 45.
- Updated the list of top base rare weapons and armour. New filters have been created. The items in this lists will show without any enhancements and can be hidden with the MF filter block. The items affected by this change are: "Spike-Point Arrow Quiver", "Gemini Claw", "Eclipse Staff", "Imperial Staff", "Maelström Staff", "Fleshripper", "Exquisite Blade" and "Saintly Chainmail".
- Slightly changed the t2, identified items and Redblade Warbands drop colors to distinguish them better in the Zoisite theme. Updated the theme file.
- Converted all Tabs and indents to use spaces, so that the code will show uniform on all platforms.
- Added more blocks to the MF filter.
- Added option for a sound effect for Transmutation and Augmentation orbs. Disabled by default.
- Changed rare one hand swords in the Leveling Filter drop level >= 50 from 46. The progression remains the same.

## 2.4.1g

- Moved Settings, Notes and To do sections to top, so that Filtration won't remove them  after editing.
- Added identified items text color setting for color themes to Filtration.
- Some minor changes / fixes.

## 2.4.1f

- Moved all the blocks that are enabled by default above the “identified rare item” block.
- Changed formatting for the “identified rare item” block to have a slightly transparent background. Only lower base items can show with this formatting now. The better rares will show with their default formatting unless if this happens when leveling (outside maps). Added ability to disable this function (not recommended).

## 2.4.1e

- Moved blocks of rare items with bigger size to top and renamed them slightly.
- **Added an entry to display any identified rare item. This entry uses red font color instead of the normal yellow one. It should cover rare corrupted items, but it will also cover any rare item that you drop on the ground after id-ing.**
- Added enhanced visualization for 20% quality gems.

## 2.4.1d

- Added line breaks to separate filter entries.
- Slightly changed the sound for map drops. Maps with DropLevel >= 76 now drop with T3 sound instead of T2.
- A second entry has been added that covers maps DropLevel >= 73 to drop with T3 sounds till ItemLevel <= 78. These maps will now use the T4 sound in higher than 78 level zones.
- Removed sound from small RGB items (above ilvl 67).
- Redone the list of top base rare items.
- Added entries for weapons that used to be in the top base items to display without any enhancements.
- Slightly updated chest armour base progression. Added a block for end game items level <=67. The „Elegant Ringmail“ will no longer show in maps. 
- Added and changed some annotations.
- Changed the “uber trash” background to be slightly visible.
- Added Magic jewelry to the endgame racing block.
- Added Rares to the chisel recipe items.

## 2.4.1a

- **The filter will now use the game's version number to avoid confusion.**
- Narrowed down the list of item level 83/84+ items.
- Removed sound and border for lesser Divination cards. These cards will only show in the Leveling filter.
- Master Cartographer's Sextant and Master Cartographer's Seal now display like T11 maps and use the T2 sound (from T1 sound).
- Separated ilvl 84+ drops to normal and magic.
- Changed sound for ilvl 84+ normal jewelry and armour bases to T4 drop sound (from T3 sound) Removed sound from ilvl 84+ magic jewelry.
- Removed sound from ilvl 84+ magic jewelry and armour bases.
- Added ilvl 84+ magic jewelry and armour bases to the endgame block (mf filter).
- Magic jewels now drop with sound till item level 77 only.
- The bases "Iron Ring", "Paua Ring" and "Moonstone Ring" will no longer show at item level 84+. These bases will retain the formatting with border when you press the „alt“ key.
- Updated the list of top base rare weapons. A second list has been created. The items in this list will show without any enhancements and can be hidden with the MF filter block. The item affected by this change is "Piledriver".
- Item level 84 and higher diamond rings now drop with T3 sound and are labeled bigger.

## 2.3.6

- Moved low currency block (Scraps, Whetstones, Baubles, Wisdom, Portal Scrolls) to the (MF) endgame block.
- Moved the Extras block in their own section.
- Changed sound for Low level maps in low level maps to T3 drop sound from T4.
- Changed sound for ItemLevel >= 84 items. The Jewelry now uses T3 sound and the other items use the T4 sound.
- Moved the Divination block above the Currency block.
- Updated Stacked deck to show as intended.
- The annotations are narrowed to display better in Notepad.
- Moved Shaper's Orb to the Quest items block
- Moved Magic jewels to the endgame block (they will not show with the MF filter). Normal jewels are now displayed by default (no change, just removed the option to hide them).
- Slightly reduced volume for T2 drops.

## 2.3.4

- Updated the list of ItemLevel >= 84 items.
- Removed Harpy Rapier from highlighted items.
- Slightly lowered volume of T2 and T3 drop sounds.
- Changed sound for maps DropLevel >= 78 (T11) to T2 drop sound. The maps T13 and up retain the old T1 sound. 

## 2.3.3

- Added Crude bow with highlighting.
- Changed sound for "Master Cartographer's Sextant" and "Shaper's Orb" to the same sound as Exalts,...
- Removed highlighting and sound to top base scepters.
- Moved Normal ilvl >=75 Jewelry to Leveling block.

## 2.3.2 [Beta]

- Added 3 new color themes to use with Filtration.
- Less desired rare items have now a slightly transparent background.
- Implemented a MF filter block (optional). Hide ilvl 75+ normal jewelry (and only show ilvl83+/84+). This doesn't affect Diamond rings.
- Added ability to hide even more rare items that are not top bases. All chromatic items can also be hidden. Furthermore these are customizable with filtration blocks. This setting is to be used if MF or if you really don't want to pick up bigger items such as staves etc.
- The items that make it to the end of the filter (trash of the trash) will now barely be seen. Thus enhancing the option to view hidden items.
- Extended normal crafting items from the leveling filter to the endgame filter. Updated list of items and added ability to hide magic crafting bases.
- Removed some old useless annotations.
- Changed encoding to UTF-8 BOM.
- Updated the tittle and settings sections.
- Added the "fail safe" section on the bottom of the filter If anything slips trough (hardly). If you see this it means that the loot filter is out of date and needs to be updated.
- Some smaller changes to color and blocks labeling.
- Added ability to change background color for maps.
- Added back the currency type "Prophecy" that was previously covered by the generic Class "Currency".
- Maps are the most important item in the game. They now have a slightly lighter background than other items do. Additionally you can customize the color in Filtration. 

## 2.2.0

- Added annotations on "tricky" entries for Filtration users.
- Moved essence to a more proper location..
- Fixed a redundant entry for flasks and slightly updated their progression.
- Slightly updated <= magic weapon crafting bases.
- Done spell check.

## 2.1.5

- **Added support for themes in Filtration.**
- Added few remaining items that were unknown till 1 Sept. 2016.
- Added color info to some rare items.
- Removed some redundant entries.

## 2.1.1

- **Added support for 2.4 Atlas Of Worlds.**
- Changed sound for ilvl 83/84+ items (all but jewelry).
- Removed trinket names due to potential conflict with essence items. They still show up the same way they did before.
- All top base rares are now big.
- Added the Prophecy Wand base type to the crafting items ilvl 73+, 83+ and top base rares.
- Slightly lowered sound level for tier 2 drops.
- Updated how rare wands and scepters show.
- Added ability to show "Sharktooth Arrow Quiver" (optional) for Hyrri's Bite recipe.
- Few other minor changes.

## 2.0.7

- Update to the racing filter for casters (wands and scepters) due to recent implicit changes in 2.3.0.
- Added daggers to the racing filter for casters.
- Updated highlighting of 3 linked caster items (wands, daggers and scepters) and added a new sound to distinguish racing items from other drops.
- Updated progression for white boots, gloves and helmets for the racing filter.
- Labyrinth items now in its own category.

## 2.0.5

- Hot fix 6.6.16 removed base item "Prophecy" cause conflict with wand base type (Prophecies will still show appropriately).
- Added items for Prophecy league 2.3.x.

## 2.0.4

- Added a new sound for divination cards.
- More lower base daggers and caster shield will be shown.

## 2.0.2

- Jewels, rare wands and top tier rare items are now big.
- Added sound for "low" tier maps <= 76.
- Removed sound for elegant sword.
- Normal diamond rings now show at >= 60 and have border at >= 75.
- Some minor highlighting changes.

## 2.0 [Beta]

- **Enabled Ascendancy filter.**
- Some minor cosmetic changes.

## 1.9.9 [Beta]

- Update for Ascendancy.
- Big update to the leveling filter with Normal and Magic weapons separation.
- Updated and extended sections.

## 1.9.1 [Beta]

- Top tier items (including maps) now show with bright green background to pop out.
- Extensive rework of the racing filter that now include all weapon classes.
- Filtering starts at level 1; Items filter gradually as you level up.
- Added a lot of block groups to facilitate customization with Filtration.
- Updated flask drop progression; and more endgame customization is available.
- All utility flasks will show up with border.
- Added the blue flasks that can roll "Of Animation" mod for summoners (you need to manually turn that on).
- Sounds had a revision (volume changes).
- Almost complete revision after extensive testing.
- Some fixes.

## 1.7.5 [Beta]

- Small tune up of the racing filter.

## 1.7.4 [Beta]

- Further filter tuning.
- Some fixes.

## 1.7.3 [Beta]

- Added "settings" for easier style manipulation.
- Introduced 1 setting for easy switching between leveling and endgame filter.
- Warbands filter is now always accessible with hidden items filtration.
- Warbands filter now also used for racing purposes.
- Improvements to the leveling filter.
- Color changes.

## 1.6.9 [Beta]

- Many changes to how items show up.
- Updated how hidden items show up (Can be seen with "Alt" key pressed).
- Added Warbands filter to hidden items (Can be seen with "Alt" key pressed).
- Added full support for leveling filter.
- Some fixes.

## 1.6.8 [Beta]

- Volume changes.
- Added index.
- Many improvements.
- Some fixes.

## 1.6.7 [Beta]

- Color changes.
- Show less rare bases at 75+.
- Added filtration support.
- General improvements.

## 1.6.4 [Beta]

- 4 tiers of sounds for drops (long sounds are good).
- New pink color.
- General improvements.

## 1.6.3 [Beta]

- Ilvl 83 and 84+ items are labeled with border.
- Maps are labeled with border for mid and high tier accordingly.
- Talismans show up with the color of top tier items.
- Some labels are bigger for easier pickup.

## 1.5

- Added basic sections.
- Added chancing bases.
- Implemented basic rare item filtering.
- Added crafting items.
- Changed sounds.

## 1.0

- Original Greendude's item filter script release.