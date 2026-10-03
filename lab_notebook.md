# Lab Notebook: Jordan's PP/CaSO4 Cold-Sintering Practice Project

**Author:** Walkthrough Tester | **GitHub:** wfreinhart
**Repository:** https://github.com/wfreinhart/rdm-walkthrough-2026-10-03
**Canonical data store:** (add once established)

> **Standard:** Each entry should contain enough detail for someone
> with similar training to reproduce what you did without asking you.
> — Briney (2023), Research Data Management Workbook

---

## 2026-10-03 14:00 | Data Processing: Tensile units check (PLANNED)

| | |
|---|---|
| **Input** | raw/PC-tensile-raw.csv (specimens PC-B01-S01 to PC-B06-S0n) |
| **Output** | processed/PC-tensile-checked.csv (planned) |
| **Operator** | Walkthrough Tester (practice learner) |
| **Method** | Compare the strength column T1 against ASTM D638 expected range; flag values 1000x too large (kPa vs MPa) |
| **Software version** | Python 3.12, pandas 2.2 (planned) |
| **Timestamp + operator** | 2026-10-03 14:00, Walkthrough Tester |
| **Units + acquisition conditions** | MPa; Instron 5943, 100 N load cell, 0.5 mm/min crosshead (from README) |
| **Raw-data location** | raw/ in this repository (synthetic training data) |
| **Parent/child** | raw/PC-tensile-raw.csv -> processed/PC-tensile-checked.csv |
| **Access/sensitivity** | Internal: synthetic data, no restriction |

**Notes:** Planned entry; will be updated with actual values after the run.
