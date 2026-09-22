# The War On News: dataset

How governments have limited journalists, 1900 to today. This repository is the nightly export of https://thewaronnews.com as a Frictionless Data Package under CC BY 4.0.

Every fact on the site is a claim: one dated statement with a verbatim quotation of up to 300 characters, the source address, the kind of source, the date it was checked and an archived copy. Claims are never edited; a new claim supersedes an old one and both stay in `claims`, linked by `supersedes_id` and `superseded_by`.

## Files

- `datapackage.json`: the Data Package descriptor with a Table Schema per table (types, enums, keys).
- `data/<table>.csv`: the latest rows, which the descriptor points to.
- `json/<table>.json`: the same rows as JSON.
- `snapshots/YYYY-MM-DD/`: weekly snapshots (Sundays and on schema change).

## Tables (export of 2026-09-22)

| Table | Rows |
| --- | --- |
| incidents | 128 |
| events | 6 |
| actors | 211 |
| outlets | 58 |
| journalists | 22 |
| cases | 4 |
| sources | 326 |
| claims | 484 |
| tactics | 13 |
| countries | 250 |
| incident_tactics | 216 |
| coverage_items | 17 |
| explainers | 0 |
| glossary_terms | 67 |
| incident_actors | 266 |
| incident_outlets | 87 |
| incident_journalists | 22 |
| incident_cases | 5 |
| incident_sources | 260 |
| incident_related | 0 |
| case_parties | 0 |
| case_sources | 21 |
| explainer_sources | 0 |
| glossary_sources | 51 |
| changes | 1969 |

## Licence and attribution

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Credit: "The War On News, thewaronnews.com". Cite a single fact by its claim URL, https://thewaronnews.com/claims/<id>. Quotations and linked sources keep their owners' terms.

## Method

See https://thewaronnews.com/methodology and https://thewaronnews.com/editorial-policy.
