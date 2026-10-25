# Campaign expense ledger

All 21 rows from the verified export are included here. Campaign aliases replace source names. Spend is Meta-reported advertising delivery spend in USD, not a billing invoice or total business cost.

[Overview](../README.md) · [CSV](../data/campaigns.csv) · [JSON](../data/campaigns.json) · [Method and source scope](METHOD.md)

| Campaign | Reported end date | Spend | Primary result | Count | Cost per result |
|---|---|---:|---|---:|---:|
| Campaign 01 | 2025-12-09 | $59.32 | Link clicks | 22 | $2.70 |
| Campaign 02 | 2025-12-06 | $4.94 | Primary result unavailable | Unavailable | Unavailable |
| Campaign 03 | 2025-12-17 | $59.44 | Link clicks | 12 | $4.95 |
| Campaign 04 | 2026-01-08 | $70.62 | Link clicks | 43 | $1.64 |
| Campaign 05 | 2026-01-19 | $333.77 | Link clicks | 186 | $1.79 |
| Campaign 06 | 2026-01-20 | $181.92 | Messaging conversations started | 11 | $16.54 |
| Campaign 07 | 2026-01-20 | $221.11 | Messaging conversations started | 9 | $24.57 |
| Campaign 08 | 2026-01-23 | $349.93 | Messaging conversations started | 24 | $14.58 |
| [Campaign 09](CASES.md#campaign-09) | 2026-01-30 | $345.73 | Messaging conversations started | 49 | $7.06 |
| Campaign 10 | 2026-01-30 | $348.85 | Link clicks | 177 | $1.97 |
| Campaign 11 | 2026-02-02 | $314.68 | Messaging conversations started | 16 | $19.67 |
| Campaign 12 | 2026-08-05 | $9.26 | Primary result unavailable | Unavailable | Unavailable |
| Campaign 13 | 2026-08-03 | $6.70 | Primary result unavailable | Unavailable | Unavailable |
| Campaign 14 | 2026-08-03 | $16.04 | Primary result unavailable | Unavailable | Unavailable |
| [Campaign 15](CASES.md#campaign-15) | 2026-08-04 | $19.88 | Link clicks | 66 | $0.30 |
| Campaign 16 | 2026-08-03 | $10.65 | Messaging conversations started | 2 | $5.33 |
| Campaign 17 | 2026-08-07 | $34.92 | Landing-page views | 54 | $0.65 |
| Campaign 18 | 2026-08-05 | $24.17 | Landing-page views | 37 | $0.65 |
| [Campaign 19](CASES.md#campaign-19) | 2026-08-04 | $34.46 | Messaging conversations started | 8 | $4.31 |
| [Campaign 20](CASES.md#campaign-20) | 2026-08-07 | $30.00 | Landing-page views | 105 | $0.29 |
| Campaign 21 | 2026-08-07 | $45.00 | Messaging conversations started | 3 | $15.00 |

**Total ad spend: $2,521.39.** Four campaigns have no primary result value in the export. Their combined $36.94 remains included. Blank source values are unavailable, not converted to zero.

The end-date column is the exported campaign schedule end date. It is not a daily or monthly allocation of spend. Campaign dates, advertiser groupings and lifetime completeness cannot be inferred from this field alone.

## Spend by primary result type

| Result type | Campaigns | Spend | Primary results | Weighted cost per result |
|---|---:|---:|---:|---:|
| Link clicks | 6 | $891.88 | 506 | $1.76 |
| Landing-page views | 3 | $89.09 | 196 | $0.45 |
| Messaging conversations started | 8 | $1,503.48 | 122 | $12.32 |
| Primary result unavailable | 4 | $36.94 | Unavailable | Unavailable |

Weighted costs use the matching group spend divided by its matching primary-result count. Counts across different result types are not added into a single conversion total. Secondary link clicks and landing-page views remain in the downloadable data. Reach is available per campaign and is not summed into a unique audience total.

## What the additional spend shows

The higher-cost campaigns make the selection transparent. Messaging costs range from $4.31 to $24.57 per reported conversation in this export. Different audiences, creative, periods and campaign settings prevent treating that range as a controlled test. These records show where a manager should investigate spend efficiency, but they do not establish which changes caused the differences.
