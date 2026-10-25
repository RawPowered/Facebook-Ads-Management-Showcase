# Data dictionary

`campaigns.csv` and `campaigns.json` contain the same 21 anonymized records. The JSON also contains report coverage and grouped summaries.

| Field | Meaning |
|---|---|
| campaign | Neutral alias for one source campaign record; not an advertiser identifier |
| result_type | Exported primary result indicator translated to a readable label |
| primary_results | Reported primary count; blank CSV / null JSON means unavailable |
| spend_usd | Meta-reported platform ad spend |
| cost_per_primary_result_usd | Spend divided by matching primary count, rounded to cents |
| impressions | Exported Ads Manager impressions |
| reach | Campaign-level reported reach; not additive across campaigns |
| link_clicks | Exported link clicks, including secondary actions on other objectives |
| landing_page_views | Exported landing-page views; missing means unavailable |
| link_ctr_percent | Link clicks / impressions × 100; expressed in percent units |
| cpc_link_usd | Spend / link clicks, rounded to cents |
| reported_end_date | Exported schedule end date, not a spend allocation date |
| featured | Whether selected for the overview |
| source_row | Original CSV row number, including header row 1 |

Source A and Source B are two reporting views of the same campaigns. Do not add their totals together. See [methodology](../docs/METHOD.md) for date, attribution, missing-value and scope details. `provenance.json` contains only raw-file fingerprints and counts. It does not expose source file contents or company identity.
