## 2026-10-03 | Data validation: raw/PC-tensile-raw.csv

**What was wrong:** PC-B03-S01 has T1 = 1620, while every other value is 1.32 to 2.05. Likely a kPa export instead of MPa. Nulls: HV is blank for PC-B01-S01 and PC-B03-S01 (2 of 31). Naming: columns T1, P, YM, El, d_mean are not self-explanatory; units for YM, El and d_mean are not documented in any file.

**What I did:** Wrote processed/PC-tensile-raw-cleaned.csv with 1620 divided by 1000 (1.62). The raw file is untouched. Recorded the blank HV cells as "not measured" in schema.yaml. Marked the undocumented units as "to confirm".

**Result:** T1 now 1.62, within the expected range. The two blank HV cells are documented. Three units remain unknown.
