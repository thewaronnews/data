# The War On News: dataset

How governments have limited journalists, from the first press laws to today. This repository is the nightly export of https://thewaronnews.com as a Frictionless Data Package under CC BY 4.0.

Every fact on the site is a claim: one dated statement with a verbatim quotation of up to 300 characters, the source address, the kind of source, the date it was checked and an archived copy. Claims are never edited; a new claim supersedes an old one and both stay in `claims`, linked by `supersedes_id` and `superseded_by`.

## Files

- `datapackage.json`: the Data Package descriptor with a Table Schema per table (types, enums, keys).
- `data/<table>.csv`: the latest rows, which the descriptor points to.
- `json/<table>.json`: the same rows as JSON.
- `snapshots/YYYY-MM-DD/`: weekly snapshots (Sundays and on schema change).

## Tables (export of 2026-09-28)

| Table | Rows |
| --- | --- |
| incidents | 226 |
| events | 13 |
| actors | 311 |
| outlets | 137 |
| journalists | 99 |
| cases | 4 |
| sources | 620 |
| claims | 986 |
| tactics | 13 |
| countries | 250 |
| incident_tactics | 333 |
| coverage_items | 47 |
| explainers | 9 |
| glossary_terms | 67 |
| incident_actors | 386 |
| incident_outlets | 191 |
| incident_journalists | 104 |
| incident_cases | 5 |
| incident_sources | 527 |
| incident_related | 3 |
| case_parties | 0 |
| case_sources | 21 |
| explainer_sources | 111 |
| glossary_sources | 51 |
| changes | 3519 |

## Licence and attribution

CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Credit: "The War On News, thewaronnews.com". Cite a single fact by its claim URL, https://thewaronnews.com/claims/<id>. Quotations and linked sources keep their owners' terms.

## Method

See https://thewaronnews.com/methodology and https://thewaronnews.com/editorial-policy.
