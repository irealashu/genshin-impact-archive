# 🎮 Genshin Impact Archive

> A comprehensive Excel-based archive and tracker for **Genshin Impact** characters, weapons, artifacts, books, and world exploration progress.

This repository contains a single Excel workbook, **`Genshin Archive.xlsx`**, designed as an all-in-one reference and progression tracker for Genshin Impact players. The workbook aggregates structured game data and account-tracking tools into a portable offline format.

---

# ✨ Features

✅ Character Collection Tracking  
✅ Weapon Inventory Management  
✅ Artifact Set Reference Database  
✅ Book & Lore Collection Tracker  
✅ Regional Exploration Progress Monitoring  
✅ Offline Excel-Based Format  
✅ Version 7.0 Data Coverage

---

# 📦 Repository Snapshot

| Property | Value |
|-----------|---------|
| 📄 File | `Genshin Archive.xlsx` |
| 🎯 Game Version | 7.0 |
| 📅 Last Updated | 2026-08-31 |
| ⚖️ License | Apache License 2.0 |

---

# 📂 Workbook Structure

The workbook is organized into separate sheets dedicated to major game systems.

## 👥 Characters

Track your roster and build progress.

### Included Information

- ✅ Ownership Status
- 📈 Character Level
- ⭐ Constellation Level
- 🗡️ Equipped Weapon
- 🔧 Weapon Level
- 🎯 Talent Levels
- 🏺 Artifact Build Status
- ⚡ Endgame Readiness

Perfect for managing teams, planning builds, and tracking character progression.

---

## ⚔️ Weapons

A complete weapon collection tracker.

### Included Information

- ✅ Ownership
- ⭐ Rarity
- 🛠️ Refinement Rank
- 📦 Weapon Count
- 🎯 Weapon Type

### Weapon Categories

| Emoji | Type |
|--------|--------|
| ⚔️ | Sword |
| 🏹 | Bow |
| 🪄 | Catalyst |
| 🔱 | Polearm |
| 🪓 | Claymore |

---

## 🏺 Artifacts

Reference database for artifact sets and pieces.

### Includes

- Complete Artifact Sets
- Individual Artifact Pieces
- Set Organization
- Piece Slot Information

### Artifact Slots

| Slot | Emoji |
|--------|--------|
| Flower of Life | 🌸 |
| Plume of Death | 🪶 |
| Sands of Eon | ⏳ |
| Goblet of Eonothem | 🏆 |
| Circlet of Logos | 👑 |

Useful for farming plans and set completion tracking.

---

## 📚 Books & Lore Archive

Track collectible books obtained throughout Teyvat.

### Includes

- 📖 Book Titles
- 🌍 Locations
- 📚 Volume Numbers
- ✅ Collection Status

Designed for lore enthusiasts and completionists seeking full archive completion.

---

## 🗺️ Exploration Progress

Monitor exploration completion across every major nation and subregion.

### Supported Regions

- 🌬️ Mondstadt
- ⛰️ Liyue
- ⚡ Inazuma
- 🌿 Sumeru
- ⚖️ Fontaine
- 🔥 Natlan
- 🌙 Nod-Krai
- ❄️ Snezhnaya

### Track

- Exploration Percentage
- Subregion Completion
- Statue of the Seven Progress
- Regional Progression

---

# 🚀 How To Use

1. Download `Genshin Archive.xlsx`
2. Open it with:
   - Microsoft Excel
   - LibreOffice Calc
   - Google Sheets
3. Navigate between sheets using the workbook tabs.
4. Update ownership, levels, collection status, and exploration progress as you play.
5. Use filtering and sorting tools for deeper analysis.

---

# 📊 Included Sheets

| Sheet | Purpose |
|---------|----------|
| 👥 Characters | Character roster and builds |
| ⚔️ Weapons | Weapon inventory tracking |
| 🏺 Artifacts | Artifact database |
| 📚 Books | Book collection tracker |
| 🗺️ Regions | Exploration progress tracker |

---

# 🐍 Example: Load Data with Python

```python
import pandas as pd

df = pd.read_excel(
    "Genshin Archive.xlsx",
    sheet_name="Characters"
)

print(df.head())
print(df.columns)
```

---

# 🤝 Contributing

Contributions are welcome.

You may contribute:

- 🛠️ Data corrections
- 📈 Updated exports for newer game versions
- 📝 Documentation improvements
- 🚀 New tracking features

When submitting updates:

1. Keep the workbook filename consistent.
2. Mention the game version covered.
3. Include a short changelog describing modifications.
4. Provide attribution for any third-party data sources if required.

---

# 📜 Versioning

Recommended approaches:

### Option 1: Single File

Keep updating:

```text
Genshin Archive.xlsx
```

and track changes through Git history.

### Option 2: Versioned Releases

Use versioned exports:

```text
Genshin Archive v7.0.xlsx
Genshin Archive v7.1.xlsx
Genshin Archive v8.0.xlsx
```

This allows users to download specific historical snapshots.

---

# ⚖️ License

This project is licensed under the **Apache License 2.0**.

See the repository's `LICENSE` file for complete terms and conditions.

---

# 👤 Maintainer

**Repository Owner:** @irealashu

If you discover issues or have suggestions, please open a GitHub issue or submit a pull request.

---

# 🌟 About This Project

This archive was created to provide a convenient, offline, spreadsheet-based reference for tracking and analyzing Genshin Impact progression data.

Whether you're a collector, completionist, theory crafter, or casual player, the archive aims to keep your journey through Teyvat organized and accessible.

---

> *"The journey itself has meaning. The destination is not everything."*

💫 Ad Astra Abyssosque. Happy adventuring, Traveler.
