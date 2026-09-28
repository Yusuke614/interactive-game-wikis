# Interactive Game Wikis & Guides Hub

A centralized collection of comprehensive, interactive video game wikis, walkthrough guides, lore chronicles, and completion trackers. Each guide is engineered as an offline-capable, single-page application (SPA) in pure HTML, CSS, and vanilla JavaScript—featuring persistent progress tracking, real-time live search, global section toggling, and game-authentic visual design.

🌐 **Live GitHub Pages Portal:** [https://yusuke614.github.io/interactive-game-wikis/](https://yusuke614.github.io/interactive-game-wikis/)

---

## 🎮 Included Game Guides & Chronicles

| Franchise | Title | Active Release | Trackable Tasks / Scope | Key Features |
| :--- | :--- | :---: | :---: | :--- |
| **Assassin's Creed** | [Assassin's Creed IV: Black Flag Resynced](games/assassins-creed/black-flag-resynced/) | `v15` | 116 Tasks | 12 IGN-grounded sections, Jackdaw naval upgrades & 5 officers, 4 Rifts, 100% sync constraints, Mayan & Templar vault armors, Caribbean pirate & Animus theme. |
| **The Legend of Zelda** | [The Legend of Zelda: Ocarina of Time 3D](games/zelda/ocarina-of-time-3d/) | `v1` | 100+ Tasks | Complete 3DS walkthrough, all 36 Heart Pieces, 100 Gold Skulltulas, songs & warp tunes, Biggoron trading sequence, Master Quest notes, Hyrule/Triforce theme. |
| **The Legend of Zelda** | [The Legend of Zelda: Echoes of Wisdom](games/zelda/echoes-of-wisdom/) | `v1` | 92 Tasks | All 15 main quests, 8 dungeons & Still Worlds, all 127 Echoes database, 6 Dampé automatons, 40 Heart Pieces, 150 Might Crystals, 25 Stamp Stands, Still World/Tri theme. |
| **The Legend of Zelda** | [The Hyrule Chronicle (English)](games/zelda/the-hyrule-chronicle/) | `v5` | 5 Canonical Eras | Nintendo's official Japanese 40th anniversary timeline translated into English. Covers the pre-creation Null void (*Echoes of Wisdom*), Dual Foundings of Hyrule, Threefold Timeline Divergence (Fallen, Child, Adult), and the distant Era of the Wild (*BotW* / *TotK*). |

---

## 🚀 Key Architectural Standards

Every wiki and chronicle in this repository is built to conform to the following engineering and UX standards:

1. **Authoritative Source Grounding**: Content sequence strictly mirrors authoritative walkthrough sources (such as official IGN Wikis and Nintendo's official Japanese timeline databases) top-to-bottom without scrambling chapter order.
2. **Dedicated Controls Bar**: Positioned at the top above navigation tabs, featuring:
   - **Real-Time Live Search (`#wikiSearch` / `#portalSearch`)**: Instant keyword filtering across all sections and cards that dynamically filters matching pages and expands matching content while typing.
   - **Global Expand All / Collapse All Toggle (`#toggleAllBtn`)**: One-click toggle between `Collapse All ▾` and `Expand All ▸` across all collapsible section bodies.
3. **Multi-Page Tab Switcher**: Single-page application architecture displaying one major chapter or era at a time to prevent cognitive overload and browser lag, with guaranteed immediate display (`style="display: block;"`) on the opening section to eliminate loading flicker.
4. **Interactive Task & Progress Tracking**: Individual quests, memory sequences, collectibles, and upgrade tiers are interactive checkboxes (`input[type="checkbox"]`) with real-time percentage fill and completion counters in the header.
5. **Safe Storage Wrapper (`safeStorage`)**: All persistence uses an in-memory fallback wrapper around `localStorage` to guarantee error-free operation on sandboxed mobile viewers, Android file providers (`content://`), and local `file://` protocols.
6. **Game-Specific World & HUD Theming**: Custom-tailored visual palettes matching each game's lore, world atmosphere, and in-game HUD rather than generic themes.
7. **Zero-Dependency Portability**: Built in 100% pure HTML5, CSS3, and vanilla JavaScript with zero external frameworks, dependencies, or network calls required for core functionality.

---

## 📁 Repository Directory Structure

```text
interactive-game-wikis/
├── README.md                                # Root repository guide (this file)
├── index.html                               # Root portal dashboard linking to all guides
└── games/
    ├── assassins-creed/
    │   └── black-flag-resynced/
    │       ├── README.md                    # AC Black Flag guide documentation
    │       ├── index.html                   # Active release (v15)
    │       └── archive/
    │           ├── ac-black-flag-resynced-wiki-v13.html
    │           └── ac-black-flag-resynced-wiki-v14.html
    │
    └── zelda/
        ├── README.md                        # Zelda franchise overview
        ├── echoes-of-wisdom/
        │   ├── README.md                    # Echoes of Wisdom guide documentation
        │   ├── index.html                   # Active release (v1)
        │   └── archive/
        │
        ├── ocarina-of-time-3d/
        │   ├── README.md                    # Ocarina of Time 3D guide documentation
        │   ├── index.html                   # Active release (v1)
        │   └── archive/
        │
        └── the-hyrule-chronicle/
            ├── README.md                    # The Hyrule Chronicle documentation
            ├── index.html                   # Active release (v5 English translation)
            └── archive/
```

---

## 🌐 GitHub Pages Deployment

* 🌐 **Live Portal URL:** [https://yusuke614.github.io/interactive-game-wikis/](https://yusuke614.github.io/interactive-game-wikis/)
* 💻 **GitHub Repository:** `https://github.com/Yusuke614/interactive-game-wikis`

To configure or re-deploy these interactive wikis on GitHub Pages:

1. Push this repository structure to your GitHub account (`Yusuke614/interactive-game-wikis`).
2. Navigate to **Repository Settings** > **Pages** (in the left sidebar).
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Set the branch to `main` and directory to `/ (root)`, then click **Save**.
5. Within 1–2 minutes, your master portal and all guides are live at:
   [https://yusuke614.github.io/interactive-game-wikis/](https://yusuke614.github.io/interactive-game-wikis/)

---

## 💾 Versioning & Maintenance Policy

* **Continuous Versioning**: Never overwrite previous revisions; strictly increment revision numbers (`_v1`, `_v2`, etc.) in the filename.
* **Archive Maintenance**: When a new revision is released, move the previous revision into the corresponding game's `archive/` folder while copying the newest release as `index.html`.
* **Personalized Instructions**: Operational guidelines for each game are maintained in the central `Gemini Spark` Google Drive folder.
