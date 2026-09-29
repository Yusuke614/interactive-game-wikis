# The Legend of Zelda: Echoes of Wisdom — Complete Interactive Guidebook

An interactive, single-page completion guide and mechanics reference for **The Legend of Zelda: Echoes of Wisdom** on Nintendo Switch. Grounded directly on the authoritative IGN walkthrough sequence and styled with the mystical Still World, Tri Rod, and Princess Zelda aesthetic.

---

## ✦ Overview & Quick Specs

* **Game**: *The Legend of Zelda: Echoes of Wisdom* (Nintendo Switch)
* **Current Version**: `v1` (`The Legend of Zelda Echoes of Wisdom Wiki_v1.html`)
* **Trackable Tasks**: 92 interactive checkable items (Main Quests, Dungeons, Bosses, Echoes, Automatons, Heart Pieces, Upgrades)
* **Authoritative Source**: [IGN Echoes of Wisdom Wiki](https://www.ign.com/wikis/the-legend-of-zelda-echoes-of-wisdom)
* **Hosting Format**: Pure HTML5 / CSS3 / Vanilla JS single-page application (SPA)

---

## 📜 12-Section Guide Architecture (IGN Sequence)

1. **Getting Started & Tri Rod (`sec_getting_started`)**: Tri Rod summoning mechanics, Tri levels and cost reduction, Bind & Reverse Bond dual tethering, Swordfighter Form, and early milestones (bed bridges, peahat discovery, waypoints).
2. **Main Story Walkthrough (`sec_main_story`)**: All 15 major story quests from Prologue through Null's Body:
   - Prologue: The Great Escape
   - The Mysterious Rifts
   - Suthorn Ruins Dungeon
   - Searching for Everyone
   - The Jabul Waters Rift
   - Jabul Ruins Dungeon
   - A Rift in the Gerudo Desert
   - Gerudo Sanctum Dungeon
   - Still Missing: Hyrule Castle
   - Hyrule Castle Dungeon
   - Lands of the Goddesses
   - The Rift on Eldin Volcano (Eldin Temple)
   - The Faron Wetlands Rift (Faron Temple)
   - The Hebra Mountain Rift (Lanayru Temple)
   - Prime Energy & Null's Body
3. **Dungeons & Stilled Worlds (`sec_dungeons`)**: Suthorn Ruins, Jabul Ruins, Gerudo Sanctum, Hyrule Castle, Eldin Temple, Faron Temple, Lanayru Temple, and Null's Body gauntlet with puzzle mechanics and layout details.
4. **Boss Strategies & Void Battles (`sec_bosses`)**: Phase-by-phase tactics, vulnerable cores, and counter Echoes for Seismic Talus, Vocavor, Mogryph, Ganon's Shadow, Volvagia, Gohma, Skorchill, and multi-phase Null.
5. **Complete Echoes Compendium (`sec_echoes`)**: Comprehensive database of all 127 Echoes with Tri summoning costs, spawn locations, and combat synergies (Old Bed, Water Block, Flying Tile, Platboom, Peahat, Darknut Lv 3, Lynel, ReDead, Cloud, Chaser).
6. **Dampé's Mechanical Automatons (`sec_automatons`)**: All 6 mechanical companions (Techtite, Tocktorok, Gizmol, High-Teku, Roboblin, Goldfinch) with unlock side quests, required crafting parts, and wind-up combat behaviors.
7. **All 40 Pieces of Heart Guide (`sec_heart_pieces`)**: Complete regional breakdown across Suthorn, Hyrule Field, Jabul Cove, Gerudo Desert, Eldin Volcano, Faron Wetlands, and Mount Lanayru (10 full Heart Containers).
8. **Might Crystals & Upgrades (`sec_might_crystals`)**: Locations of all 150 Might Crystals and Lueburry's forge upgrades for the Sword of Might, Bow of Might, Bombs of Might, and Energy Gauge expansions.
9. **Stamp Rallies & Great Fairies (`sec_stamp_rally`)**: All 25 Stamp Stands placed by the Stamp Guy across 5 completion reward tiers (Fresh Milk, Golden Eggs, Fairy Bottle, Might Crystals, Stamp Suit), plus Lake Hylia's Great Fairy accessory slot expansions (up to 5 slots).
10. **Accessories & Equippable Outfits (`sec_accessories`)**: All 28 accessories and thematic outfits (Frog Ring, Zora Flippers, Goron Bracelet, Curious Charm, Fairy Fragrance, Cat Suit, Silk Pajamas).
11. **Smoothies & Potions Cookbook (`sec_smoothies`)**: All 69 Business Scrub blending recipes, key ingredients, and buff durations (Chilly, Piping-Hot, Tough, Quick, Golden).
12. **Hyrule Side Quests & Slumber Dojo (`sec_side_quests`)**: Regional mini-quests and all 12 Kakariko Slumber Dojo combat meditation trials.

---

## 🎨 Echoes of Wisdom Visual Palette

| UI Element | Palette Name | Hex Code | Usage |
| :--- | :--- | :---: | :--- |
| **Background** | Deep Still World Royal Navy | `#080c18` / `#060913` | Base atmospheric layer with ambient rift violet and starlight amber glows |
| **Cards & Slate** | Twilight Slate | `#0f172a` / `#162038` | Section containers and cards with rift-seam borders (`#263352` / `#384973`) |
| **Tri Gold** | Tri Rod Radiant Gold | `#f59e0b` / `#fbbf24` | Key statistics, progress fill, and active navigation buttons |
| **Rift Violet** | Still World Rift Violet | `#8b5cf6` / `#7c3aed` | Void alerts, dungeon headers, and Stilled World highlights |
| **Zelda Pink** | Princess Zelda Coral Rose | `#f43f5e` / `#fb7185` | Royal highlights and narrative callouts |
| **Echo Cyan** | Echo Energy Cyan | `#06b6d4` / `#22d3ee` | Coordinates, tags, and fairy shimmering accents |
| **Forest Green** | Hyrule Field Emerald | `#10b981` / `#34d399` | Terrain badges and tactical pro-tips |
| **Courage Blue** | Swordfighter Blue | `#3b82f6` | Swordfighter form mechanics and combat weapon upgrades |
| **Typography** | Sailcloth White & Muted Slate | `#f8fafc` / `#94a3b8` | High-contrast readable body text |
| **Header Emblem** | Glowing Tri Fairy Star Crest | `✦` | Main title header emblem |

---

## ⚡ Controls & Interactivity

* **Live Search Bar (`#wikiSearch`)**: Real-time keyword filter across all 12 sections; matching sections are automatically highlighted and expanded.
* **Global Expand/Collapse Toggle (`#toggleAllBtn`)**: Toggles all section bodies between `Collapse All ▾` and `Expand All ▸`.
* **SafeStorage Protocol**: Saves task completions (`eow_wiki_tasks`), collapsed section states, and active page selections in browser storage without throwing security exceptions.
