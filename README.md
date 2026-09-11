# 🎮 Genshin Impact Archive

> A comprehensive Excel-based archive and tracker for **Genshin Impact** characters, weapons, artifacts, books, and world exploration progress.

This repository contains a single Excel workbook, **`Genshin Archive.xlsx`**, designed as an all-in-one reference and progression tracker for Genshin Impact players. The workbook aggregates structured data and interactive tracking tools for efficient progression management.

---

## 📋 Table of Contents

- [Quick Start](#-quick-start)
- [Features](#-features)
- [Repository Snapshot](#-repository-snapshot)
- [Detailed Sheet Documentation](#-detailed-sheet-documentation)
- [How To Use](#-how-to-use)
- [Included Sheets Summary](#-included-sheets-summary)
- [Data Structure](#-data-structure)
- [Example: Load Data with Python](#-example-load-data-with-python)
- [Contributing](#-contributing)
- [Versioning & Maintenance](#-versioning--maintenance)
- [License](#-license)
- [Maintainer & Support](#-maintainer--support)
- [About This Project](#-about-this-project)
- [Quick Tips for Success](#-quick-tips-for-success)
- [Additional Resources](#-additional-resources)

---

# ✨ Features

✅ **Character Collection Tracking** — Manage roster, levels, constellations, and talent progression  
✅ **Weapon Inventory Management** — Track owned weapons, refinement ranks, and equipment status  
✅ **Artifact Set Reference Database** — Complete artifact set reference with slot information  
✅ **Book & Lore Collection Tracker** — Catalog books and lore pieces from across Teyvat  
✅ **Regional Exploration Progress Monitoring** — Track exploration percentage and statue progress in each region  
✅ **Offline Excel-Based Format** — No internet required; works on any device with Excel or compatible software  
✅ **Version 7.0 Data Coverage** — Updated with the latest game content and characters  
✅ **Sortable & Filterable** — Built-in Excel functionality for custom analysis and searches  

---

# 📦 Repository Snapshot

| Property | Value |
|-----------|---------|
| 📄 Main File | `Genshin Archive.xlsx` |
| 🎯 Game Version | 7.0 |
| 📅 Last Updated | 2026-08-31 |
| ⚖️ License | Apache License 2.0 |
| 📊 Sheet Count | 5 comprehensive sheets |
| 💾 Format | Excel (.xlsx) / Compatible spreadsheet software |

---

# 📂 Detailed Sheet Documentation

Each sheet in the workbook serves a specific purpose in tracking different aspects of your Genshin Impact progression.

---

## 👥 Characters Sheet

**Purpose:** Maintain a complete roster of your characters and track their progression, equipment, and build readiness.

### What You Can Track

| Metric | Description |
|--------|-------------|
| **Ownership Status** | Whether you own or are planning to pull the character |
| **Character Level** | Current level (1-90) |
| **Constellation Level** | Unlocked constellations (0-6) |
| **Equipped Weapon** | The weapon currently equipped on this character |
| **Weapon Level** | Weapon ascension and enhancement level |
| **Talent Levels** | Normal Attack, Elemental Skill, and Elemental Burst levels (1-15) |
| **Artifact Build Status** | Whether the character has a complete artifact set equipped |
| **Endgame Readiness** | Quick visual indicator if the character is prepared for high-level content |

### Use Cases

- 👥 Organize your full character roster alphabetically or by element
- 🎯 Plan which characters to level next based on available resources
- 🔄 Track build progression and identify characters needing investment
- 💪 Identify your strongest teams for spiral abyss and event challenges
- 📊 Compare constellation levels across your roster

### Tips

- Sort by **Character Level** to identify underleveled characters
- Filter by **Element** to find all Cryo, Electro, Pyro, etc. characters
- Use conditional formatting to highlight characters ready for endgame content

---

## ⚔️ Weapons Sheet

**Purpose:** Maintain a complete inventory of all weapons you own, including their types, rarity, and refinement status.

### Tracked Information

| Attribute | Details |
|-----------|---------|
| **Weapon Name** | Official name of the weapon |
| **Ownership Status** | Own it, Pending (planning to obtain), or Reference only |
| **Rarity** | 3-star, 4-star, or 5-star weapons |
| **Weapon Type** | Sword, Bow, Catalyst, Polearm, or Claymore |
| **Refinement Rank** | R1 to R5 (determines weapon passive strength) |
| **Weapon Count** | How many copies you own (useful for tracking duplicates) |
| **Current Equip Status** | Which character is using this weapon, if any |
| **Enhancement Level** | Weapon level and ascension status |

### Weapon Categories & Symbols

| Emoji | Type | Example Characters |
|--------|--------|--------|
| ⚔️ | Sword | Traveler, Bennett, Kazuha |
| 🏹 | Bow | Amber, Fischl, Yelan |
| 🪄 | Catalyst | Barbara, Mika, Nahida |
| 🔱 | Polearm | Zhongli, Hu Tao, Cyno |
| 🪓 | Claymore | Diluc, Alhaitham, Ganyu |

### Use Cases

- 🔍 Quickly find which weapon is best for a specific character
- 📦 Track banner weapons and identify farming priorities
- 🎯 Plan weapon enhancement based on available materials
- 💎 Identify 5-star weapons worth rolling for
- 🔄 Manage weapon transfers between characters during updates

### Tips

- Sort by **Rarity** to focus on 5-star weapons first
- Filter by **Type** to find all available options for a specific character class
- Color-code weapons by refinement rank for quick visual identification

---

## 🏺 Artifacts Sheet

**Purpose:** Reference database for all artifact sets in the game, including individual pieces and slot information.

### Artifact Data Structure

| Field | Purpose |
|--------|---------|
| **Set Name** | Official artifact set name |
| **Set Bonus (2-piece)** | Effect when 2 pieces of the set are equipped |
| **Set Bonus (4-piece)** | Enhanced effect when full 4-piece set is equipped |
| **Artifact Pieces** | The five individual pieces that compose the set |
| **Slot Information** | Which slots each piece occupies |
| **Recommended Elements/Characters** | Best champions for this set |
| **Farming Location** | Which domain or boss drops this artifact |
| **Acquisition Method** | Dungeon domain, overworld boss, etc. |

### Artifact Slots Reference

| Slot | Emoji | Stat Type | Primary Focus |
|--------|--------|-----------|---------|
| Flower of Life | 🌸 | Fixed HP | Support base stats |
| Plume of Death | 🪶 | Fixed ATK | Damage scaling |
| Sands of Eon | ⏳ | % Stat (ATK/EM/ER) | Character-specific scaling |
| Goblet of Eonothem | 🏆 | % Damage (Elemental/Physical) | Reaction or type scaling |
| Circlet of Logos | 👑 | % Stat (CRIT/Healing/ER) | Critical build optimization |

### Use Cases

- 📖 Reference guide when planning character builds
- 🎯 Identify which sets work best for specific characters
- 🔄 Plan artifact farming routes based on location and availability
- 🏆 Compare different set combinations for the same character
- 📊 Track set completion progress for your inventory

### Tips

- Use this sheet as a **lookup table** while planning new builds
- Cross-reference with the Characters sheet to identify farming priorities
- Filter by **Farming Location** to consolidate your daily farming schedule

---

## 📚 Books & Lore Archive Sheet

**Purpose:** Track all collectible books and lore materials scattered throughout Teyvat for completionists and lore enthusiasts.

### Tracked Information

| Field | Description |
|--------|-------------|
| **Book Title** | Name of the book or lore piece |
| **Book Series** | Which book series it belongs to (if applicable) |
| **Volume Number** | Volume or chapter number in the series |
| **Collection Status** | Whether you've collected it or not |
| **Location** | Region and specific area where it can be found |
| **Coordinates** | In-game coordinates (if trackable) |
| **Acquisition Method** | How to obtain (pickup, quest reward, shop, etc.) |
| **Date Collected** | When you obtained this book |
| **Relevance** | Plot significance or character connections |

### Regions Covered

- 🌬️ **Mondstadt** — Windblume region books and records
- ⛰️ **Liyue** — Ancient Chinese-inspired lore and archives
- ⚡ **Inazuma** — Samurai culture and historical records
- 🌿 **Sumeru** — Botanical knowledge and academic texts
- ⚖️ **Fontaine** — Legal records and theatrical scripts
- 🔥 **Natlan** — Cultural narratives and warrior tales
- 🌙 **Nod-Krai** — Luna related content
- ❄️ **Snezhnaya** — Historical archives and records

### Use Cases

- 📖 Systematically collect all available books for lore completionists
- 🎯 Plan book-hunting expeditions by region
- 📚 Track your collection progress toward 100% completion
- 🔍 Cross-reference books with character backstories
- 📍 Identify books you still need to collect

### Tips

- Sort by **Region** to focus on one area at a time
- Filter by **Collection Status** to see only uncollected books
- Use coordinates (if available) with map markers for efficient collection runs

---

## 🗺️ Exploration Progress Sheet

**Purpose:** Monitor your exploration completion across every major nation and subregion in Teyvat.

### Tracked Metrics

| Metric | Range | Details |
|--------|-------|---------|
| **Region Name** | — | Major nation in Teyvat |
| **Exploration %** | 0-100% | Overall exploration completion |
| **Subregions** | Multiple | Individual areas within each region |
| **Statue of the Seven** | 0-8 | Statue level |

### Supported Regions & Details

| Region | Emoji | Release | Explorer Notes |
|--------|--------|---------|---------|
| Mondstadt | 🌬️ | Launch | Starter region; German-inspired architecture |
| Liyue | ⛰️ | Launch | Asian-inspired; vast harbor and mountains |
| Inazuma | ⚡ | v2.0 | Japanese islands; high difficulty domains |
| Sumeru | 🌿 | v3.0 | Rainforest and desert; largest region |
| Fontaine | ⚖️ | v4.0 | European-inspired; underwater mechanics |
| Natlan | 🔥 | v5.0 | South American-inspired; newest major region |
| Nod-Krai | 🌙 | v6.0 | Nordic-themed region |
| Snezhnaya | ❄️ | v7.0 | Final playable region; home of The Fatui |

### Use Cases

- 🎯 Track your completion percentage in each region
- 📍 Identify underexplored areas for targeted farming
- 🗿 Monitor Statue of the Seven progress for regional damage bonuses
- 🏆 Challenge yourself to achieve 100% exploration across all regions
- 📊 Maintain a checklist for your completionist goals

### Tips

- Sort by **Exploration %** to identify regions needing attention
- Focus on raising **Statue of the Seven** for combat efficiency
- Plan region-specific farming routes based on chests and puzzles
- Cross-reference with event content that may open new areas

---

# 🚀 How To Use

### Step-by-Step Setup

1. **Download the File**
   - Clone this repository or download `Genshin Archive.xlsx` directly

2. **Open with Compatible Software**
   - Microsoft Excel (Windows/Mac) — Recommended for full compatibility
   - LibreOffice Calc (Windows/Mac/Linux) — Free, open-source alternative
   - Google Sheets — Upload for cloud-based access
   - Apple Numbers — Mac/iPad compatible

3. **Explore the Sheets**
   - Click tabs at the bottom to navigate between sheets
   - Review the existing data as reference or template

4. **Customize for Your Account**
   - Update ownership status for characters and weapons you own
   - Add your current levels and progression
   - Mark completed regions and collected books
   - Add notes specific to your build plans

5. **Use Built-in Features**
   - **Sort** columns to organize by level, rarity, or region
   - **Filter** to find specific information quickly
   - **Color-code** rows for visual organization
   - **Add formulas** to track totals and completion percentages

6. **Keep Updated**
   - Update data as you progress through the game
   - Add new characters/weapons after pulling
   - Track constellation and talent level increases
   - Mark exploration completion as you explore

---

# 📊 Included Sheets Summary

| Sheet | Icon | Primary Purpose | Key Metrics |
|---------|--------|---------|---------|
| **Characters** | 👥 | Character roster and build tracking | Level, Constellation, Talents, Equipment |
| **Weapons** | ⚔️ | Weapon inventory management | Type, Rarity, Refinement, Ownership |
| **Artifacts** | 🏺 | Artifact set reference database | Set Effects, Slots, Farming Locations |
| **Books** | 📚 | Book collection and lore tracking | Title, Location, Collection Status |
| **Regions** | 🗺️ | Exploration progress monitoring | Completion %, Statue Level |

---

# 📊 Data Structure

### Character Record Example

```
Name: Nahida
Element: Dendro
Rarity: 5-Star
Ownership: Yes
Level: 90
Constellation: C2
Weapon: A Thousand Floating Dreams (Level 90)
Normal Attack: 10
Elemental Skill: 12
Elemental Burst: 12
Artifact Build: Dendro DMG% (Gilded Dreams 4-piece)
Status: Endgame Ready
```

### Weapon Record Example

```
Name: Aqua Simulacra
Type: Bow
Rarity: 5-Star
Refinement: R1
Ownership: Yes
Equipped On: Yelan
Enhancement Level: 90
Count: 1
```

### Artifact Set Example

```
Set Name: Gilded Dreams
2-Piece Bonus: +80 Elemental Mastery
4-Piece Bonus: +14% DMG for 8s when triggering reaction (stacks up to 4)
Farming Location: Artifact Domain of Mastery (Sumeru)
Best For: Nahida, Alhaitham, Support Catalyst users
```

---

# 🐍 Example: Load Data with Python

### Basic Loading

```python
import pandas as pd

# Load Characters sheet
df_characters = pd.read_excel(
    "Genshin Archive.xlsx",
    sheet_name="Characters"
)

# Display first 10 characters
print(df_characters.head(10))
print("\nColumn Names:")
print(df_characters.columns.tolist())
```

### Intermediate: Filtered Analysis

```python
import pandas as pd

# Load all sheets
xls = pd.ExcelFile("Genshin Archive.xlsx")
df_characters = pd.read_excel(xls, "Characters")
df_weapons = pd.read_excel(xls, "Weapons")

# Find all 5-star characters you own
five_star_owned = df_characters[
    (df_characters["Rarity"] == "5-Star") & 
    (df_characters["Ownership"] == "Yes")
]
print("5-Star Characters Owned:")
print(five_star_owned[["Name", "Element", "Level", "Constellation"]])

# Count weapons by type
print("\nWeapon Count by Type:")
print(df_weapons["Type"].value_counts())
```

### Advanced: Progress Tracking

```python
import pandas as pd
import json
from datetime import datetime

# Load workbook
df_chars = pd.read_excel("Genshin Archive.xlsx", "Characters")

# Calculate team statistics
avg_level = df_chars[df_chars["Ownership"] == "Yes"]["Level"].mean()
avg_constellation = df_chars[df_chars["Ownership"] == "Yes"]["Constellation"].mean()

print(f"Average Character Level: {avg_level:.1f}")
print(f"Average Constellation: {avg_constellation:.1f}")

# Export to JSON for other applications
characters_data = df_chars.to_json(orient="records")
with open("characters_export.json", "w") as f:
    json.dump(json.loads(characters_data), f, indent=2)
```

---

# 🤝 Contributing

We welcome contributions to improve the archive! Whether you're reporting errors, adding new data, or suggesting features, your input helps maintain this resource.

### How to Contribute

1. **Report Issues**
   - Found outdated game data? Open an issue describing the discrepancy
   - Suggest missing characters, weapons, or artifacts
   - Report formatting problems or unclear descriptions

2. **Submit Updates**
   - Fork this repository
   - Make corrections or add new data
   - Ensure consistency with existing formatting
   - Submit a pull request with a clear description of changes

3. **Contribute Documentation**
   - Improve this README with better explanations
   - Add usage examples or tutorials
   - Create guides for specific use cases

4. **Add New Sheets**
   - Domain farming guides
   - Material farming calendars
   - Spiral Abyss team recommendations
   - Ley Line Overflow schedules

### Contribution Guidelines

✅ **Do**
- Keep the workbook filename consistent (`Genshin Archive.xlsx`)
- Mention the game version covered in your contribution
- Include a short changelog describing your modifications
- Provide attribution for any third-party data sources
- Test your changes thoroughly before submitting

❌ **Don't**
- Remove existing data without justification
- Change the core workbook structure without discussion
- Add copyright-restricted game artwork (text-based data only)
- Submit spreadsheets with personal/sensitive information

---

# 📜 Versioning & Maintenance

### Versioning Strategy

#### Option 1: Single File (Recommended for Simplicity)

Keep a single updated file:

```
Genshin Archive.xlsx
```

Track all changes through Git commit history. Users can:
- Access the latest data by downloading the current version
- Review historical changes via Git logs
- Rollback to specific versions if needed

**Pros:** Simple, minimal duplication
**Cons:** Historical versions not directly downloadable

#### Option 2: Versioned Releases (Recommended for Archival)

Use versioned exports aligned with game updates:

```
Genshin Archive v7.0.xlsx
Genshin Archive v7.1.xlsx
Genshin Archive v8.0.xlsx
```

**Pros:** Users can download historical snapshots, clear version tracking
**Cons:** Repository grows in size, more maintenance overhead

#### Option 3: Hybrid Approach (Recommended for Teams)

Maintain current version + major releases:

```
Genshin Archive.xlsx (Current)
releases/
├── Genshin Archive v7.0.xlsx
├── Genshin Archive v7.1.xlsx
└── Genshin Archive v8.0.xlsx
```

---

# ⚖️ License

This project is licensed under the **Apache License 2.0**.

**Summary of Rights:**
- ✅ Use commercially or privately
- ✅ Modify and distribute
- ✅ Place warranty disclaimer
- ✅ Include license and copyright notice

See the repository's `LICENSE` file for complete terms and conditions.

**Copyright © 2026 irealashu**

---

# 👤 Maintainer & Support

**Repository Owner:** [@irealashu](https://github.com/irealashu)

### Get Help or Provide Feedback

- 🐛 **Report Bugs:** Open an issue describing the problem
- 💡 **Suggest Features:** Request new tracking categories or sheets
- 📝 **Ask Questions:** Use the Discussions section for general help
- 🔄 **Submit Changes:** Fork and create a pull request with improvements

### Contact

For direct inquiries, feel free to reach out through GitHub or open an issue.

---

# 🌟 About This Project

This archive was created to provide a convenient, **offline, spreadsheet-based reference** for tracking and analyzing Genshin Impact progression data. No special software, accounts, or internet connection is required—just a spreadsheet application and this workbook.

### Who Is This For?

- 🎯 **Completionists** — Track every character, weapon, and book
- 📊 **Data Enthusiasts** — Analyze your progression metrics
- 🔄 **Team Builders** — Plan optimal character and artifact combinations
- 📱 **Casual Players** — Quick reference while playing
- 🏆 **Abyss Climbers** — Organize teams and track gear optimization
- 🧑‍💻 **Developers** — Parse data programmatically with Python/Excel APIs

### Why Use This Archive?

1. **No Cloud Required** — Fully offline operation
2. **Full Control** — Your data stays on your device
3. **Flexible** — Customize to your playstyle
4. **Free & Open** — No ads, paywalls, or tracking
5. **Shareable** — Export and collaborate easily
6. **Version-Tracked** — Full Git history of changes

---

# 🎮 Quick Tips for Success

1. **Set a Routine** — Update your archive weekly as you progress
2. **Use Filters** — Find specific data instantly with sorting/filtering
3. **Color-Code** — Use conditional formatting for visual organization
4. **Cross-Reference** — Link character builds to available weapons and artifacts
5. **Backup Regularly** — Keep copies of important versions
6. **Share & Collaborate** — Team up with friends using the same template
7. **Automate** — Use Excel formulas to calculate totals and track milestones

---

# 📚 Additional Resources

- [Genshin Impact Official Wiki](https://genshin-impact.fandom.com)
- [Artifact Farming Guide](https://genshin-impact.fandom.com/wiki/Artifact)

---

> *"Now, you who has set foot in this world. Your journey has reached its end, but one final doorway remains. Step forth, if you have understood the meaning of your journey. Defeat me, command me to stand in your way, or relinquish these divine relics to me.* 
> *My memory has all but faded completely... But I will always remember how much she too, loved these flowers."*  --Dainsleif, Teyvat Chapter Storyline Preview

✨ **Ad Astra Abyssosque.** Happy adventuring, Traveler! 🌍

---

**Last Updated:** 2026-08-31 | **Game Version:** 7.0 | **License:** Apache 2.0
