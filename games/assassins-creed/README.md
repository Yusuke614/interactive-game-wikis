# Assassin's Creed — Interactive Wikis, Databases & Completion Guides

A curated collection of offline-capable, interactive single-page application (SPA) game wikis, walkthrough guides, and mechanics references for the **Assassin's Creed** franchise. Grounded directly on authoritative IGN walkthrough sequences, synchronization constraints, and the Abstergo Animus database, with persistent task tracking, live search, and franchise-specific aesthetics.

🌐 **Franchise Hub Portal:** [index.html](index.html)

---

## ⚓ Included Assassin's Creed Guides & Databases

| Title | Platform / Setting | Active Release | Scope & Tasks | Folder Location |
| :--- | :---: | :---: | :---: | :--- |
| [**Black Flag Resynced**](Black%20Flag%20Resynced/) | PC Remaster / Caribbean Golden Age of Piracy | `v15` | 116 Tasks | `Black Flag Resynced/` — 12 IGN-grounded walkthrough modules, Sequences 1–13 (100% sync), 4 Animus Rifts & EGO solutions, Jackdaw upgrade trees & naval combat, 4 Legendary Ships, 5 Specialist Officers, 15 Naval Contracts, 4 Templar Hunts & 16 Mayan Stelae puzzles, crafting, and achievements. |

---

## 📁 Folder Structure

Every game and expansion is organized into its own dedicated subfolder within the franchise root:

```text
Assassin's Creed/
├── index.html                               # AC Franchise Hub Portal
├── README.md                                # Franchise overview (this file)
│
└── Black Flag Resynced/
    ├── Assassin's Creed Black Flag Resynced Wiki_v15.html # Active interactive guide (v15)
    ├── Assassin's Creed Black Flag Resynced Wiki_v14.html # Preserved milestone archive (v14)
    ├── README.md                            # Dedicated Black Flag Resynced guide documentation
    └── README_archive_v1.md                 # Archived documentation copy
```

---

## ⚡ Architectural Standards

* **Authoritative Source Grounding**: Sequenced directly from official IGN walkthroughs, memory synchronization checklists, and authentic Animus databases.
* **Dedicated Controls Bar**: Real-time live search (`#wikiSearch` / `#portalSearch`), category filtering, and global Expand All / Collapse All toggle (`#toggleAllBtn`).
* **Interactive Checklist Tracking**: Interactive checkable items using `safeStorage` wrapper compatible with desktop browsers, Android file viewers (`content://`), and local `file://` protocols.
* **Franchise-Authentic Aesthetics**: Caribbean naval warfare and Abstergo Animus visual palette (Abyssal Teal `#040e13`, Doubloon Gold `#f3a829`, and Animus Cyan `#00d4e6`).
