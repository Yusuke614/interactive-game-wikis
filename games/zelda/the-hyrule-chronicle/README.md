# The Hyrule Chronicle (English Translation) — Interactive Official Canon Timeline

An interactive, single-page application (SPA) recreation and English translation of **Nintendo's official Japanese 40th anniversary chronicle** for *The Legend of Zelda* franchise. Grounded directly in official Nintendo archives and expanded with newly canonized revelations from *The Legend of Zelda: Echoes of Wisdom*, *Breath of the Wild*, and *Tears of the Kingdom*.

---

## ⚜️ Overview & Quick Specs

* **Title**: *The Hyrule Chronicle (English Translation)* (ゼルダの伝説 総合年表)
* **Current Version**: `v5` (`The_Hyrule_Chronicle_English_v5.html`)
* **Source Basis**: Nintendo Official Japanese Zelda 40th Anniversary Portal
* **Scope**: Complete history from pre-creation myth to the distant Era of the Wild
* **Hosting Format**: Pure HTML5 / CSS3 / Vanilla JS single-page application (SPA)

---

## 📜 Key Canon Architecture & Revelations

1. **Pre-Creation Void (Null / Echoes of Wisdom)**:
   - Officially formalizes the primordial *World of Nothingness* (無の世界) predating heaven and earth.
   - Explains that the devourer entity **Null** consumed nascent forms before the three Golden Goddesses (Din, Nayru, Farore) descended to cultivate the earth, establish immutable laws, and seal Null.
2. **The Dual Foundings of Hyrule**:
   - **First Founding**: Established in antiquity by the mortal descendants of Goddess Hylia and the first mortal Zelda after the Era of Chaos and the construction of the Temple of Time by Sage Rauru.
   - **Second Founding**: Established in the distant Era of the Wild by King Rauru (Zonai) and Queen Sonia, distinct from the ancient first kingdom.
3. **The Great Divergence of Destinies (Threefold Split)**:
   - **Branch I: The Decline of Hyrule & The Last Hero (Hero Defeated)**: The Hero of Time falls; Ganon gains the complete Triforce; Sages seal Ganon in the Sacred Realm which decays into the Dark World (*A Link to the Past*, *Link's Awakening*, *Oracle of Seasons/Ages*, *A Link Between Worlds*, *Tri Force Heroes*, *The Legend of Zelda*, *The Adventure of Link*).
   - **Branch II: The Twilight Realm & The Shadow (Child Era)**: Link is returned to his youth to warn Princess Zelda; Ganondorf is exposed and banished to the Twilight Realm (*Majora's Mask*, *Twilight Princess*, *Four Swords Adventures*).
   - **Branch III: The Great Sea & The New World (Adult Era)**: The Hero departs across time; Ganon returns to a hero-less land; the Gods flood Hyrule to seal the demon king beneath the waves (*The Wind Waker*, *Phantom Hourglass*, *Spirit Tracks*).
4. **The Distant Era of the Wild**:
   - The ancient Cataclysm, the Sheikah technology awakening, the Great Calamity, and the Upheaval (*Breath of the Wild*, *Tears of the Kingdom*).

---

## 🎨 Visual Palette & Aesthetic Styling

| UI Element | Palette Name | Hex Code | Usage |
| :--- | :--- | :---: | :--- |
| **Background** | Imperial Obsidian & Dark Slate | `#0c0a08` / `#080706` | Deep atmospheric background with subtle radial gold glows |
| **Cards & Containers** | Ancient Royal Relic Slate | `rgba(22, 18, 14, 0.88)` | Interactive chronicle event cards |
| **Primary Gold** | Master Triforce Gold | `#d4af37` / `#f3e5ab` | Hero typography, headers, and golden relic accents |
| **Unified Era** | Sacred Creation Gold | `#d4af37` | Primeval era, Skyward Sword, and founding badges |
| **Fallen Branch** | Decline & Demon King Crimson | `#c84b31` | Hero Defeated timeline markers and Dark World alerts |
| **Child Branch** | Twilight Shadow Violet | `#795290` | Majora's Mask, Twilight Princess, and Shadow Realm markers |
| **Adult Branch** | Great Sea Azure | `#2d82b7` | Wind Waker and flooded ocean eras |
| **Wild Era** | Zonai Radiant Teal | `#0fa389` | Breath of the Wild & Tears of the Kingdom markers |
| **Typography** | Royal Cinzel & Cormorant Garamond | `'Cinzel', serif` | Formal imperial classical font styling |

---

## ⚡ Interactive Features

* **Interactive Branch Filter Tabs**: Switch between *All Eras*, *Creation & Unified*, *The Decline of Hyrule*, *The Twilight Realm*, *The Great Sea*, and *The Era of the Wild*.
* **Era Search & Filter**: Real-time search across all canonical events, historical outcomes, and game release dates.
* **SafeStorage Protocol**: Remembers active timeline selections across reloads without throwing security exceptions in sandboxed viewers.
