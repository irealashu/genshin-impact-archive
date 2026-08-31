# genshin-impact-archive

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

Genshin Impact Archive — Excel workbook export of game data (XLSX).

This repository contains a single Excel workbook, `Genshin Archive.xlsx`, which aggregates structured data for Genshin Impact entities. The export was prepared and committed by the repository owner for offline analysis, reference, or tooling.

Repository snapshot

- File: `Genshin Archive.xlsx`
- Data coverage: exported up to Genshin Impact version 7.0
- Last updated in this repository: 2026-08-31
- License: Apache License 2.0 — see the LICENSE file included in this repo

Quick links

- Download workbook (GitHub web): https://github.com/irealashu/genshin-impact-archive/blob/main/Genshin%20Archive.xlsx
- Raw download: https://raw.githubusercontent.com/irealashu/genshin-impact-archive/main/Genshin%20Archive.xlsx

Contents

The Excel workbook contains separate sheets (tabs) for the main entity types:

- Characters
- Weapons
- Artifacts
- Books (materials like talent/ascension books)
- Regions

Each sheet is structured as rows (one entity per row) and columns for attributes. Column names and exact structure may vary between exports — open the workbook to inspect headers. Below are the typical columns included per sheet to help you get started.

Typical sheet structures (example columns)

- Characters
  - id (internal id)
  - name
  - element
  - weapon_type
  - rarity
  - base_hp / base_atk / base_def
  - ascension_materials
  - talent_materials
  - description / lore
  - release_version

- Weapons
  - id
  - name
  - type
  - rarity
  - base_atk
  - secondary_stat
  - passive_description
  - how_to_obtain
  - release_version

- Artifacts
  - id
  - name
  - set_bonus
  - main_stats
  - sub_stats
  - rarity
  - sources

- Books
  - id
  - name
  - type (talent/ascension)
  - rarity
  - sources

- Regions
  - id
  - name
  - description
  - version_added

Note: The workbook may include additional sheets or slightly different column names; these examples are provided as a guide.

How to use

1. Download `Genshin Archive.xlsx` using one of the links above.
2. Open with Microsoft Excel, LibreOffice Calc, or import into Google Sheets.
3. Inspect the first row of each sheet for column headers. Use filters, sort, or pivot tables to analyze the data.
4. To consume programmatically, export the sheets to CSV (most spreadsheet applications can do this) and process with your preferred tooling.

Example: load a sheet in Python (pandas)

```python
import pandas as pd
df = pd.read_excel('Genshin Archive.xlsx', sheet_name='Characters')
print(df.columns)
```

Contributing

Contributions are welcome. If you have:

- Corrections or fixes to the existing export,
- An updated export that covers newer game versions,
- Improvements to this repository (README, LICENSE, metadata),

please open an issue describing the change, or submit a pull request with the updated `Genshin Archive.xlsx` (or the delta and an explanation). When submitting workbook updates, please:

- Keep the filename `Genshin Archive.xlsx` (or use `Genshin Archive v{version}.xlsx` for versioned exports),
- Include a short changelog entry in your PR description describing what changed and the game version covered,
- If the update is a derived dataset or includes third-party content, provide attribution in the PR and include a NOTICE file if required.

License

This repository and the files in it are licensed under the Apache License 2.0. See `LICENSE` for full terms.

Attribution and data source

This archive was exported by the repository owner (@irealashu). If you derived data from other public sources, please include attribution in a NOTICE file or the PR that adds the data.

Changelog / Versioning

If you maintain this archive over time, consider using one of these patterns:

- Keep the canonical file name `Genshin Archive.xlsx` and update it in-place; use Git commit messages to track changes (recommended for small changes).
- Provide versioned exports `Genshin Archive v7.0.xlsx`, `Genshin Archive v7.1.xlsx`, etc., so consumers can download a specific snapshot.

Support / Contact

- Repository owner: @irealashu
- Issues: https://github.com/irealashu/genshin-impact-archive/issues

Acknowledgements

This repository is a personal/exported snapshot for convenience and analysis. If you re-distribute or build upon this data, ensure you comply with the Apache-2.0 license and any terms required by original data sources.

