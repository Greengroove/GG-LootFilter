# GREENGROOVE'S LOOT FILTER SCRIPTS - CHANGE LOG

All notable changes to this project will be documented in this file. Please note that the log is referring to the endgame filter.

In detail information about the filter can be found [here](https://www.pathofexile.com/forum/view-thread/1566921).

## 2.5.0e

- Added exclusion for Normal and Magic Coral Amulet at level >= 72. Some other bases were already excluded.
- Added ability to hide top base scepters.
- Fixed a labeling issue with Shaper's orb introduced after filter optimization.
- Fixed the Breachstones not showing properly due to game bug or wrong information from GGG's side.

## 2.5.0d

- Added a game like color theme.
- Added ability to togle wisdom scrolls and portal scrols separately.
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
- Moved the Essence blok above the Currency block.
- Renamed section "ALL 2.4 NEW BASES"

## 2.4.3b

- The racing filter is now disabled by default in the Endgame version of the filter.
- Some minor changes to the racing filter. Reworked some magic weapon progressions in the racing filter.

## 2.4.3a

- Changed highlighting for some mediocre hybrid items. These items can now be hidden with the MF block.
- Added Bone Spirit Shield as extra for the "Of animation flask" recipe. The flask is then used to make a +1 to Level of Minion Gems helmet.
- Added Hideout Doodads & Microtransactions just in case.
- Some minor changes to the 83/84+ crafting base blocks. Added normal jewlry and weapon crafting bases to the MF block.
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
- Temporary extended normal crafting items from the leveling filter to the endgame filter. Updated list of items and added ability to hide magic crafting bases.
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