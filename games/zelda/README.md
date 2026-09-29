# The Legend of Zelda — Interactive Wikis, Chronicles & Completion Guides

A curated collection of offline-capable, interactive single-page application (SPA) game wikis, walkthrough guides, and canon chronicles for **The Legend of Zelda** franchise. Grounded directly on authoritative IGN guides and official Nintendo publications, with persistent task tracking, live search, and franchise-specific aesthetics.

---

## 🗡️ Included Zelda Guides & Chronicles

| Title | Platform / Type | Active Release | Scope & Tasks | Folder Location |
| :--- | :---: | :---: | :---: | :--- |
| [**Echoes of Wisdom**](echoes-of-wisdom/) | Nintendo Switch | `v1` | 92 Tasks | `Echoes of Wisdom/` — All 15 main quests, 8 dungeons & Still Worlds, all 127 Echoes database, 6 Dampé automatons, 40 Heart Pieces, 150 Might Crystals, 25 Stamp Stands, Still World/Tri theme. |
| [**Ocarina of Time 3D**](ocarina-of-time-3D/) | Nintendo 3DS | `v1` | 100+ Tasks | `Ocarina of Time 3D/` — 12 IGN-grounded sections, 36 Heart Pieces, 100 Gold Skulltulas, songs & warp tunes, Biggoron trading sequence, Master Quest notes, Hyrule/Triforce theme. |
| [**The Hyrule Chronicle (English)**](the-hyrule-chronicle/) | Official Japanese Canon Timeline Translation | `v5` | 5 Canonical Eras | `The Hyrule Chronicle/` — Full translation of Nintendo's official Japanese 40th anniversary timeline. Establishes the pre-creation Null void (*Echoes of Wisdom*), the Dual Foundings of Hyrule, the Threefold Split, and the Era of the Wild (*BotW* / *TotK*). |

---

## 📁 Folder Structure

Every game and canon chronicle is organized into its own dedicated subfolder:

```text
The Legend of Zelda/
├── index.html                               # Zelda Franchise Hub Portal
├── README.md                                # Zelda franchise overview (this file)
│
├── Ocarina of Time 3D/
│   ├── The Legend of Zelda Ocarina of Time 3D Wiki_v1.html   # Active interactive guide
│   └── README.md                            # Dedicated OoT 3D guide documentation
│
├── Echoes of Wisdom/
│   ├── The Legend of Zelda Echoes of Wisdom Wiki_v1.html     # Active interactive guide
│   └── README.md                            # Dedicated Echoes of Wisdom documentation
│
└── The Hyrule Chronicle/
    ├── The_Hyrule_Chronicle_English_v5.html # Active timeline release (v5)
    ├── The_Hyrule_Chronicle_English_v1.html # Standalone HTML edition (v1)
    ├── The_Hyrule_Chronicle_English_v2.html # Standalone HTML edition (v2)
    ├── The_Hyrule_Chronicle_English_v4.html # Archive revision (v4)
    ├── The_Hyrule_Chronicle_English_v3.html # Archive revision (v3)
    ├── The_Hyrule_Chronicle_English_v2.txt  # Plain-text translation (v2)
    └── README.md                            # Dedicated Hyrule Chronicle documentation
```

---

## ⚡ Architectural Standards

* **Authoritative Source Grounding**: Sequenced directly from official IGN walkthroughs and official Nintendo Japanese archives.
* **Dedicated Controls Bar**: Real-time live search (`#wikiSearch` / `#portalSearch`) and global Expand All / Collapse All toggle (`#toggleAllBtn`).
* **Multi-Page Tab Switcher**: Single-page application architecture with default active section inline visibility guarantee (`style="display: block;"`).
* **Persistent Task Tracking**: Interactive checkable items using `safeStorage` wrapper compatible with desktop browsers, Android file viewers (`content://`), and local `file://` protocols.
