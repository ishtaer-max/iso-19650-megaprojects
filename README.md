# ISO 19650-governed megaprojects and their audited outcomes

The dataset behind **[The Dark Side of BIM: The Biggest ISO 19650 Failures](https://solebo.org/dark-side-of-bim/)** (Ivan Shtaer, Solebo, 2026).

It covers the 11 largest capital projects with a documented ISO 19650 or predecessor (PAS 1192) information-management mandate, across five jurisdictions and four sectors. For each one it gives the original and final budget, the overrun, the schedule slip and the source that records them.

| File | Format |
|---|---|
| `dark-side-of-bim-cases.csv` | Flat table, one row per project |
| `dark-side-of-bim-cases.json` | Same records plus dataset metadata |

## Fields

`id`, `project`, `country`, `sector`, `client`, `delivery`, `standard`, `budget_original`, `budget_final`, `overrun_pct`, `schedule_slip`, `evidence_basis`, `primary_source`, `caveat`, `source_article`, `source_url`

Every row has its own `source_url`, so the provenance stays with the data.

## Read it as a record, not a verdict

The overruns are documented, but none of these audits isolates how much the information-management mandate contributed to the outcome. What the dataset shows is that no independently audited success exists in this set. It does not prove causation.

## Methodology

The full methodology, discussion and sources are in the article: https://solebo.org/dark-side-of-bim/
The companion dataset of measured BIM *benefits* is in [The Light Side of BIM](https://solebo.org/light-side-of-bim/).

## Corrections

Counter-evidence is welcome. If you can point to a flagship project under a documented ISO 19650 mandate that an independent audit found to have finished on time and on budget, open an issue. You'll be credited.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse freely, including commercially, as long as you credit the source.

## Cite

> Shtaer, I. (2026) *ISO 19650-governed megaprojects and their audited outcomes* (v1.0) [Data set]. Solebo. https://solebo.org/dark-side-of-bim/
