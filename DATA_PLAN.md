# Data Plan

## Identifiers

**Status:** Decided

**Answer, exact question, or reason:** Specimen ID (PC-Bnn-Snn) is the key. CT scans link through ids.csv: 33 of 40 links matched, 2 ambiguous, 5 unrecoverable.

**Where recorded, or who/what would settle it:** ids.csv, evidence column; raw/batch-notes.txt; raw/CT-scan-sheet.csv

## Storage

**Status:** Decided

**Answer, exact question, or reason:** Planned canonical store is an institutional cloud project folder run by the PI; two backups; restore test scheduled for 2026-11-15, not yet performed.

**Where recorded, or who/what would settle it:** README.md, section Storage & Continuity Plan

## Continuity

**Status:** Open

**Answer, exact question, or reason:** If Jordan left tomorrow, which role holds the access that survives graduation, and where are the 4.2 GB of CT stacks listed?

**Where recorded, or who/what would settle it:** The PI and the department data steward would settle it.

**Lead (Open only):** The plan names the PI as second contact, but no file lists where the CT stacks live.

## Provenance

**Status:** Open

**Answer, exact question, or reason:** Can the tensile units check be traced to the scripts that ran it? The lab notebook entry is only PLANNED.

**Where recorded, or who/what would settle it:** The notebook entry once Jordan runs the check; Jordan would settle it.

**Lead (Open only):** lab_notebook.md has a PLANNED entry, so no run is recorded yet.

## Meaning

**Status:** Open

**Answer, exact question, or reason:** What are the units of YM, El and d_mean in raw/PC-tensile-raw.csv?

**Where recorded, or who/what would settle it:** Jordan, or the Instron export settings.

**Lead (Open only):** schema.yaml marks these three units as 'to confirm'.

## Quality

**Status:** Decided

**Answer, exact question, or reason:** A manual units, nulls and naming check runs before use; corrections go to a cleaned copy in processed/ and are logged.

**Where recorded, or who/what would settle it:** validation-log.md and processed/PC-tensile-raw-cleaned.csv

## Sharing

**Status:** Open

**Answer, exact question, or reason:** Can the CT stacks be shared at publication, given the sponsor agreement?

**Where recorded, or who/what would settle it:** The sponsor agreement and the research office.

**Lead (Open only):** The project record shows no recorded sharing decision; derived porosity tables may be easier to release than raw stacks.

## Riskiest open question

### The question

The Sharing item for the CT stacks. It relates to the Sharing lesson concept of releasing data at publication. The mechanism it guards against is a late discovery that the sponsor agreement blocks release of data a paper depends on, leaving the results unverifiable.

### Following it further

Full release after sponsor review needs a review window before publication. Derived data only (porosity tables) needs a clear definition of derived and a sponsor yes. Deposit with an embargo needs a repository that supports one. First to try: ask the research office how the publication-review clause treats derived data.
