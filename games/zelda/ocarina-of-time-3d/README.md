# The Legend of Zelda: Ocarina of Time 3D — Complete Interactive Guidebook

An interactive, single-page completion guide and mechanics reference for **The Legend of Zelda: Ocarina of Time 3D** on Nintendo 3DS. Grounded directly on the authoritative IGN walkthrough sequence and styled with the iconic forest and Triforce aesthetic of Hyrule.

---

## 🗡️ Overview & Quick Specs

* **Game**: *The Legend of Zelda: Ocarina of Time 3D* (Nintendo 3DS / Remaster)
* **Current Version**: `v1` (`The Legend of Zelda Ocarina of Time 3D Wiki_v1.html`)
* **Trackable Tasks**: 100+ interactive checkable items (Heart Pieces, Skulltulas, Songs, Dungeons)
* **Authoritative Source**: [IGN Ocarina of Time 3D Wiki](https://www.ign.com/wikis/the-legend-of-zelda-ocarina-of-time-3d)
* **Hosting Format**: Pure HTML5 / CSS3 / Vanilla JS single-page application (SPA)

---

## 📜 12-Section Guide Architecture (IGN Sequence)

1. **Getting Started & 3D Enhancements (`sec_getting_started`)**: Controls, touch-screen item equipping, gyroscopic aiming, Sheikah Hint Stone system, and Visions.
2. **Child Era Walkthrough (`sec_child_era`)**: Kokiri Forest, Great Deku Tree, Hyrule Castle & Courtyard, Kakariko Village & Graveyard, Death Mountain Trail, Goron City, Dodongo's Cavern, Zora's River, Zora's Domain, Lake Hylia, and Inside Jabu-Jabu's Belly.
3. **Adult Era Walkthrough (`sec_adult_era`)**: Temple of Time & Master Sword, Sacred Realm, Forest Temple, Fire Temple, Ice Cavern & Iron Boots, Water Temple, Bottom of the Well & Lens of Truth, Shadow Temple, Gerudo Fortress & Thieves' Hideout, Haunted Wasteland & Spirit Temple, and Ganon's Castle.
4. **Dungeon Maps & Boss Strategies (`sec_bosses`)**: Strategies for Queen Gohma, King Dodongo, Barinade, Phantom Ganon, Volvagia, Morpha, Bongo Bongo, Twinrova, Ganondorf, and Beast Ganon.
5. **Pieces of Heart Guide (`sec_heart_pieces`)**: All 36 Pieces of Heart with conditions, prerequisites, Child vs. Adult era requirements, and locations.
6. **Gold Skulltulas (`sec_gold_skulltulas`)**: All 100 Gold Skulltula tokens organized by region and day/night requirements, plus House of Skulltula reward tiers (Adult's Wallet, Shard of Agony, Giant's Wallet, Bombchus, Piece of Heart, 200 Rupees).
7. **Ocarina Songs & Warp Melodies (`sec_ocarina_songs`)**: Standard songs (Zelda's Lullaby, Epona's Song, Saria's Song, Sun's Song, Song of Time, Song of Storms, Scarecrow's Song) and Warp Melodies (Minuet of Forest, Bolero of Fire, Serenade of Water, Nocturne of Shadow, Requiem of Spirit, Prelude of Light) with 3DS button/touch notations.
8. **Equipment, Tunics & Upgrades (`sec_equipment`)**: Swords (Kokiri, Master, Giant's Knife, Biggoron's Sword 11-step trading sequence), Shields (Deku, Hylian, Mirror), Tunics (Kokiri, Goron, Zora), Boots (Kokiri, Iron, Hover), Gauntlets (Goron's Bracelet, Silver Gauntlets, Golden Gauntlets), and quiver/bomb bag/wallet upgrades.
9. **Bottles & Great Fairy Fountains (`sec_bottles_fairies`)**: All 4 Empty Bottles and all 6 Great Fairy Fountains (Magic Meter, Din's Fire, Farore's Wind, Nayru's Love, Double Magic Meter, Double Defense).
10. **Mini-Games & Side Quests (`sec_side_quests`)**: Mask of Truth trading sequence, Happy Mask Shop, Lon Lon Ranch & Epona racing, Gerudo Horseback Archery, Fishing Pond & Golden Scale, and Gerudo Training Ground (Ice Arrows).
11. **Master Quest Differences (`sec_master_quest`)**: Mirrored world layout, rearranged dungeon puzzles, altered enemy placements, and advanced puzzle solutions.
12. **Boss Challenge Mode (`sec_boss_challenge`)**: The 3DS Boss Gauntlet feature unlocked via Link's bed in Kokiri Forest.

---

## 🎨 Hyrule & Triforce Visual Palette

| UI Element | Palette Name | Hex Code | Usage |
| :--- | :--- | :---: | :--- |
| **Background** | Deep Kokiri Forest Dark | `#070e0a` / `#050a07` | Base layer with ambient radial emerald and gold glows |
| **Cards & Slate** | Sacred Grove & Temple Stone | `#0f1c16` / `#14281f` | Containers with Kokiri Vine borders (`#1d382b` / `#2d5a44`) |
| **Triforce Gold** | Triforce Radiant Gold | `#ffd700` / `#b89700` | Progress bar fill, key statistics, and active navigation buttons |
| **Forest Green** | Kokiri Forest Green | `#2ecc71` / `#10b981` | Child Era badges, forest sync, and standard tags |
| **Goron Ruby** | Goron Ruby Red | `#e74c3c` | Fire Temple, combat pro-tips, boss warnings, and danger alerts |
| **Zora Sapphire**| Zora Sapphire Blue | `#3498db` | Water Temple, bottle items, and warp tunes |
| **Sheikah Purple**| Sheikah Shadow Purple | `#9b59b6` | Shadow Temple, Lens of Truth, and Gold Skulltula tokens |
| **Light Sage** | Light Sage Amber | `#f1c40f` | Medallions and sacred stones |
| **Typography** | Sailcloth White & Forest Mist | `#f0f6fc` / `#8ea598` | High-contrast readable body text |
| **Header Emblem** | Glowing Triforce Crest | `▲` | Main title header emblem |

---

## ⚡ Controls & Interactivity

* **Live Search Bar (`#wikiSearch`)**: Real-time keyword filter across all 12 sections.
* **Global Expand/Collapse Toggle (`#toggleAllBtn`)**: Toggles all section bodies between `Collapse All ▾` and `Expand All ▸`.
* **SafeStorage Protocol**: Saves task completions (`oot3d_wiki_tasks`), collapsed section states, and active page selections in browser storage without throwing security exceptions.
