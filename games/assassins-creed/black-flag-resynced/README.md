# Assassin's Creed IV: Black Flag Resynced — Interactive Wiki & Completion Guide

An interactive, single-page completion guide and mechanics reference for **Assassin's Creed IV: Black Flag Resynced**. Grounded directly on the official IGN walkthrough sequence and styled with the authentic aesthetic of the Caribbean Golden Age of Piracy and the Abstergo Animus interface.

---

## ⚓ Overview & Quick Specs

* **Game**: *Assassin's Creed IV: Black Flag* / *Resynced* (Remaster / Mod Overhaul)
* **Current Version**: `v16` (`Assassin's Creed Black Flag Resynced Wiki_v16.html`)
* **Trackable Tasks**: 116 persistent interactive checkable items
* **Authoritative Source**: [IGN Assassin's Creed Black Flag Resynced Wiki](https://www.ign.com/wikis/assassins-creed-black-flag-resynced)
* **Hosting Format**: Pure HTML5 / CSS3 / Vanilla JS single-page application (SPA)

---

## 🧭 12-Section Guide Architecture (IGN Sequence)

1. **Getting Started & Basics (`sec_getting_started`)**: Controls, stealth navigation, dual-swords combat, early economy, and early fort liberation (Punta Guarico).
2. **Resynced Features & Animus Enhancements (`sec_resynced_features`)**: High-framerate physics, dynamic weather cycles, overhauled ship boarding mechanics, and visual presets.
3. **Main Story Walkthrough (`sec_story`)**: Sequences 1 through 13 covering all canonical memories and optional 100% synchronization constraints.
4. **The 4 Rifts & EGO (`sec_rifts`)**: Full solutions for all 4 Animus Rifts (*Wayward Souls*, *Wayward Desires*, *Wayward Minds*, *True Purpose*) and EGO entity dialogue nodes.
5. **Jackdaw & Naval Combat (`sec_naval`)**: Complete upgrade tree for broadside cannons, heavy shot, mortars, ram, swivel guns, and cargo hold capacities.
6. **Legendary Ships (`sec_legendary_ships`)**: Tactics, firing patterns, and counter-strategies for *El Impoluto*, *HMS Prince*, *Brothers-in-Arms* (*Fearless* & *Royal Sovereign*), and *La Dama Negra*.
7. **Jackdaw Specialist Officers (`sec_officers`)**: Recruitment missions, passive ship buffs, and active boarding perks for all 5 officers:
   - **Adéwalé**: Quartermaster discipline & crew retention
   - **Anne Bonny**: Frontline boarding duelist & boarding speed
   - **Lucy Baldwin**: Master shipwright, reduced repair costs & Ram Dash
   - **Abel "Padre" Galvão**: Field surgeon, reduced crew casualties & Morale Aura
   - **Tobias "Deadman" Smith**: Master gunner, mortar reload speed & heavy shot crit
8. **A World Without Gold (`sec_world_without_gold`)**: Walkthroughs for all 8 late-game story missions (*A Bitter End*, *The Spanish Treasure Fleet*, *The King's Pardon*, *A Matter of Trust*, *The Great Inagua Siege*, *Blood and Gold*, *The Last Voyage*, *The Final Reckoning*).
9. **Naval Contracts (`sec_naval_contracts`)**: All 15 fort-issued naval contracts with vessel targets and rewards.
10. **Side Quests, Templar Hunts & Vaults (`sec_side_quests`)**: All 4 Templar Hunts (Opía Apito, Rhona Dinsmore, Antó, Vance Travers) unlocking the Templar Armor (melee resistance) and 16 Mayan Stelae puzzles unlocking the Mayan Vault Armor (bullet deflection with Yax Tun Pendant).
11. **Weapon & Outfit Crafting (`sec_crafting`)**: Hunting recipes, crafting requirements, and pistol/swords arsenal stats.
12. **Trophies & Achievements (`sec_trophies`)**: 100% achievement breakdown with unlock criteria.

---

## 🎨 Game-Authentic Visual Palette

| UI Element | Palette Name | Hex Code | Usage |
| :--- | :--- | :---: | :--- |
| **Background** | Abyssal Caribbean Midnight Sea | `#040e13` / `#05141c` | Overall atmospheric background with subtle radial glows |
| **Cards & Slate** | Weathered Naval Oak & Ship Slate | `#0b1f28` / `#102a35` | Section containers and mission cards |
| **Borders** | Copper & Weathered Seams | `#183c4b` / `#24576c` | Card borders and table dividers |
| **Primary Gold** | Spanish Doubloon Gold | `#f3a829` / `#b87a12` | Progress fill, key statistics, and active filter tabs |
| **Cyan Accent** | Caribbean Turquoise & Animus Cyan | `#00d4e6` | Coordinates, synchronization badges, and interactive links |
| **Threat Crimson**| Pirate Ensign Crimson | `#d92534` | Legendary ship encounters, combat pro-tips, and boss warnings |
| **Typography** | Sailcloth White & Sea Mist Grey | `#f0f6fa` / `#8ca5b2` | High-contrast readable body text |
| **Header Emblem** | Jackdaw Anchor Crest | `⚓` | Main title header emblem |

---

---

## 📁 Folder Structure

```text
Assassin's Creed/
├── index.html                               # AC Franchise Hub Portal
├── README.md                                # Franchise Overview Documentation
└── Black Flag Resynced/
    ├── README.md                            # AC Black Flag Guide Documentation (this file)
    ├── Assassin's Creed Black Flag Resynced Wiki_v15.html # Active interactive guide (v15)
    ├── Assassin's Creed Black Flag Resynced Wiki_v14.html # Preserved milestone archive (v14)
    └── README_archive_v1.md                 # Archived documentation copy
```

## ⚡ Controls & Interactivity

* **Live Search Bar (`#wikiSearch`)**: Real-time keyword filter across all 12 sections; matching sections are automatically highlighted and expanded.
* **Global Expand/Collapse Toggle (`#toggleAllBtn`)**: Toggles all section bodies between `Collapse All ▾` and `Expand All ▸`.
* **SafeStorage Protocol**: Saves task completions (`acbf_resynced_tasks`), collapsed section states, and active page selections in browser storage without throwing security exceptions in sandboxed viewers.
