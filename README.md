# Nursing Home Ownership Transitions Since 2016

This repository contains data analysis, notebooks, and visualizations for a story examining how nursing home ownership in the United States has changed since 2016. The project focuses on who is buying nursing homes, who is selling them, and how ownership structures are shifting over time.

---

## Research Question

How has nursing home ownership in the U.S. changed since 2016, and what types of organizations are driving acquisitions?

---

## Data Sources

This analysis uses two datasets from the Centers for Medicare & Medicaid Services (CMS):

- **SNF Change of Ownership (CHOW)**  
  Records of nursing home sales, acquisitions, mergers, and consolidations since January 1, 2016.

- **Nursing Home Provider Information File**  
  Facility-level data including ownership type, staffing levels, and quality ratings.

---

## Methodology

- Both datasets were merged using the CMS Certification Number (CCN) as the unique identifier.
- The merge successfully matched **98.9%** of buyer and seller records.
- The final dataset includes **5,141 ownership transactions** between 2016 and the present.

---

## Key Findings

### For-profit buyers dominate the market
For-profit organizations account for the vast majority of nursing home acquisitions. Out of 5,141 total transactions, 4,644 (about 90%) involved a for-profit buyer. Nonprofit organizations accounted for a small share of deals, while government entities made up an even smaller portion.

### LLCs are the most common acquirer
Among for-profit buyers, limited liability companies (LLCs) are the most frequent structure, followed by corporations. Smaller shares include individual and partnership ownership. The prevalence of LLCs makes it difficult to identify ultimate ownership due to limited disclosure requirements.

### Ownership changes rarely cross sectors
Most transactions occur within the same ownership type, such as for-profit to for-profit or nonprofit to nonprofit. Cross-sector conversions appear relatively rare, though this may be partly due to limitations in how current ownership data is recorded in CMS files, which do not fully capture historical ownership changes.

---

## Limitations

- CMS Provider Information reflects current ownership, not full historical ownership transitions.
- Some cross-sector changes may be undercounted due to data structure limitations.
- LLC ownership structures may obscure ultimate controlling entities.

---

## Contents

- `/notebooks` — Data cleaning and analysis scripts
- `/data` — Processed datasets (if included)
- `/charts` — Visualizations used in the story
- `/outputs` — Final figures and tables

---

## Author

Suiumkan Ulanbek

---

## Note

All analysis, notebooks, and visualizations used in the accompanying story are available in this repository.
