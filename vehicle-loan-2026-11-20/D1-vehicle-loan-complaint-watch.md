# Vehicle loan and lease complaint watch: top 20 companies, issue changes versus the prior 90 days, three daily pulls

D1 report — final (PULL 1, PULL 2 and PULL 3 complete; submit after verification).

- Intent: d5662ca5-0f6d-498d-a6f2-40a18ceb82c1
- Escrow: esc_504a3b7d512840b99ff979f1 (funded 2026-11-20 09:30 WIB)
- Seller: morteza.ai (did:key:z6MksuuPhUAEnXhrzKZkzmce2wtqq6kL2GLz4yZyaxrLrC2T)
- Buyer: did:pkh:eip155:8453:0xAdF3Ae375A6493111d90F67B7a6c0f6b87a7ea88
- Source (only source used): Consumer Complaint Database, host www.consumerfinance.gov, endpoint /data-research/consumer-complaints/search/api/v1/
- Current window: date_received_min=2026-08-15, date_received_max=2026-11-12
- Prior window: date_received_min=2026-05-17, date_received_max=2026-08-14
- Product filter on every request: product=Vehicle loan or lease, no size parameter.

## PULL 1 — row counts and totals

PULL 1 ran 2026-11-20 03:26:59–03:27:11 UTC (right after award).

| Window | CSV row count | Total reported (no-format query) | Relation | Row count vs total |
|---|---|---|---|---|
| Current (2026-08-15 to 2026-11-12) | 6589 | 6589 | eq | equal |
| Prior (2026-05-17 to 2026-08-14) | 6045 | 6045 | eq | equal |

Both row counts equal their totals, so no difference to report. The CSV rows are used.

- Current-window rows of the 20 companies in table (a): 4720 (D2 row count).
- Prior-window row count of the 20 companies: 4241.
- Distinct companies: current window 283, prior window 316. The 20 companies of table (a) are drawn from the current window only.

## PULL 2 — row counts and totals

PULL 2 ran 2026-11-21 03:37:34–03:37:45 UTC; its progress note was filed at server time 2026-11-21 03:40:39 UTC, 24h 08m 53s after the PULL 1 progress note (server time 2026-11-20 03:31:46 UTC).

| Window | CSV row count | Total reported (no-format query) | Relation | Row count vs total |
|---|---|---|---|---|
| Current (2026-08-15 to 2026-11-12) | 6701 | 6701 | eq | equal |
| Prior (2026-05-17 to 2026-08-14) | 6045 | 6045 | eq | equal |

Both row counts equal their totals, so no difference to report. The CSV rows are used.

- Current-window rows of the 20 companies in table (a): 4807 (D3 row count).
- Prior-window row count of the 20 companies: 4241.
- Distinct companies: current window 284, prior window 316. The 20 companies of table (a) are drawn from the current window only; the same 20 companies as PULL 1, in the same order except ranks 5/6 swapped (CAPITAL ONE and HYUNDAI tied at 289, tie-break Company ascending puts CAPITAL ONE first).

## PULL 3 — row counts and totals

PULL 3 ran 2026-11-22 03:42:47–03:42:57 UTC; its progress note was filed at server time 2026-11-22 03:45:22 UTC, 24h 04m 43s after the PULL 2 progress note (server time 2026-11-21 03:40:39 UTC).

| Window | CSV row count | Total reported (no-format query) | Relation | Row count vs total |
|---|---|---|---|---|
| Current (2026-08-15 to 2026-11-12) | 6808 | 6808 | eq | equal |
| Prior (2026-05-17 to 2026-08-14) | 6045 | 6045 | eq | equal |

Both row counts equal their totals, so no difference to report. The CSV rows are used.

- Current-window rows of the 20 companies in table (a): 4888 (D4 row count).
- Prior-window row count of the 20 companies: 4241.
- Distinct companies: current window 284, prior window 316. The 20 companies of table (a) are drawn from the current window only; the same 20 companies as PULL 2, in the same order except ranks 17/18 swapped (NISSAN MOTOR ACCEPTANCE COMPANY LLC 110 before TRUIST FINANCIAL CORPORATION 109).

## Table (a) — PULL 1: top 20 companies by current-window complaints

Ranked by current count, largest first; ties by Company ascending by Unicode code point. Change = current minus prior. Percent change = change over prior, in percent, 2 decimals, no % sign, half away from zero, decimal arithmetic; n/a when the prior count is 0. Current counts sum to 4720 (D2 row count); prior counts sum to 4241 (prior-window row count of the 20 companies).

| Rank | Company | Current | Prior | Change | % change |
|---|---|---|---|---|---|
| 1 | SANTANDER HOLDINGS USA, INC. | 631 | 555 | 76 | 13.69 |
| 2 | ALLY FINANCIAL INC. | 542 | 489 | 53 | 10.84 |
| 3 | Westlake Services, LLC | 464 | 481 | -17 | -3.53 |
| 4 | CREDIT ACCEPTANCE CORPORATION | 420 | 259 | 161 | 62.16 |
| 5 | CAPITAL ONE FINANCIAL CORPORATION | 282 | 312 | -30 | -9.62 |
| 6 | HYUNDAI CAPITAL AMERICA | 277 | 244 | 33 | 13.52 |
| 7 | Bridgecrest Acceptance Corporation | 255 | 256 | -1 | -0.39 |
| 8 | TOYOTA MOTOR CREDIT CORPORATION | 231 | 226 | 5 | 2.21 |
| 9 | Exeter Finance, LLC. | 209 | 176 | 33 | 18.75 |
| 10 | WELLS FARGO & COMPANY | 203 | 158 | 45 | 28.48 |
| 11 | American Credit Acceptance, LLC | 164 | 126 | 38 | 30.16 |
| 12 | AMERICAN HONDA FINANCE CORP | 147 | 118 | 29 | 24.58 |
| 13 | NAVY FEDERAL CREDIT UNION | 140 | 103 | 37 | 35.92 |
| 14 | Global Lending Services LLC | 129 | 141 | -12 | -8.51 |
| 15 | General Motors Financial Company, Inc. | 124 | 134 | -10 | -7.46 |
| 16 | JPMORGAN CHASE & CO. | 115 | 135 | -20 | -14.81 |
| 17 | TRUIST FINANCIAL CORPORATION | 107 | 99 | 8 | 8.08 |
| 18 | NISSAN MOTOR ACCEPTANCE COMPANY LLC | 102 | 92 | 10 | 10.87 |
| 19 | TD BANK US HOLDING COMPANY | 92 | 66 | 26 | 39.39 |
| 20 | Consumer Portfolio Services, Inc. | 86 | 71 | 15 | 21.13 |

Rank 21 (not in the top 20): BANK OF AMERICA, NATIONAL ASSOCIATION, 75 current-window complaints. No tie at the rank 20/21 cut.

## Table (a) — PULL 2: top 20 companies by current-window complaints

Ranked by current count, largest first; ties by Company ascending by Unicode code point. Change = current minus prior. Percent change = change over prior, in percent, 2 decimals, no % sign, half away from zero, decimal arithmetic; n/a when the prior count is 0. Current counts sum to 4807 (D3 row count); prior counts sum to 4241 (prior-window row count of the 20 companies).

| Rank | Company | Current | Prior | Change | % change |
|---|---|---|---|---|---|
| 1 | SANTANDER HOLDINGS USA, INC. | 647 | 555 | 92 | 16.58 |
| 2 | ALLY FINANCIAL INC. | 542 | 489 | 53 | 10.84 |
| 3 | Westlake Services, LLC | 465 | 481 | -16 | -3.33 |
| 4 | CREDIT ACCEPTANCE CORPORATION | 436 | 259 | 177 | 68.34 |
| 5 | CAPITAL ONE FINANCIAL CORPORATION | 289 | 312 | -23 | -7.37 |
| 6 | HYUNDAI CAPITAL AMERICA | 289 | 244 | 45 | 18.44 |
| 7 | Bridgecrest Acceptance Corporation | 256 | 256 | 0 | 0.00 |
| 8 | TOYOTA MOTOR CREDIT CORPORATION | 235 | 226 | 9 | 3.98 |
| 9 | Exeter Finance, LLC. | 215 | 176 | 39 | 22.16 |
| 10 | WELLS FARGO & COMPANY | 208 | 158 | 50 | 31.65 |
| 11 | American Credit Acceptance, LLC | 165 | 126 | 39 | 30.95 |
| 12 | AMERICAN HONDA FINANCE CORP | 151 | 118 | 33 | 27.97 |
| 13 | NAVY FEDERAL CREDIT UNION | 140 | 103 | 37 | 35.92 |
| 14 | Global Lending Services LLC | 130 | 141 | -11 | -7.80 |
| 15 | General Motors Financial Company, Inc. | 124 | 134 | -10 | -7.46 |
| 16 | JPMORGAN CHASE & CO. | 120 | 135 | -15 | -11.11 |
| 17 | TRUIST FINANCIAL CORPORATION | 108 | 99 | 9 | 9.09 |
| 18 | NISSAN MOTOR ACCEPTANCE COMPANY LLC | 106 | 92 | 14 | 15.22 |
| 19 | TD BANK US HOLDING COMPANY | 93 | 66 | 27 | 40.91 |
| 20 | Consumer Portfolio Services, Inc. | 88 | 71 | 17 | 23.94 |

Rank 21 (not in the top 20): BANK OF AMERICA, NATIONAL ASSOCIATION, 76 current-window complaints. No tie at the rank 20/21 cut. Ranks 5/6 are tied at 289 (CAPITAL ONE FINANCIAL CORPORATION before HYUNDAI CAPITAL AMERICA by Company ascending).

## Table (a) — PULL 3: top 20 companies by current-window complaints

Ranked by current count, largest first; ties by Company ascending by Unicode code point. Change = current minus prior. Percent change = change over prior, in percent, 2 decimals, no % sign, half away from zero, decimal arithmetic; n/a when the prior count is 0. Current counts sum to 4888 (D4 row count); prior counts sum to 4241 (prior-window row count of the 20 companies).

| Rank | Company | Current | Prior | Change | % change |
|---|---|---|---|---|---|
| 1 | SANTANDER HOLDINGS USA, INC. | 662 | 555 | 107 | 19.28 |
| 2 | ALLY FINANCIAL INC. | 542 | 489 | 53 | 10.84 |
| 3 | Westlake Services, LLC | 465 | 481 | -16 | -3.33 |
| 4 | CREDIT ACCEPTANCE CORPORATION | 449 | 259 | 190 | 73.36 |
| 5 | CAPITAL ONE FINANCIAL CORPORATION | 292 | 312 | -20 | -6.41 |
| 6 | HYUNDAI CAPITAL AMERICA | 291 | 244 | 47 | 19.26 |
| 7 | Bridgecrest Acceptance Corporation | 268 | 256 | 12 | 4.69 |
| 8 | TOYOTA MOTOR CREDIT CORPORATION | 237 | 226 | 11 | 4.87 |
| 9 | Exeter Finance, LLC. | 224 | 176 | 48 | 27.27 |
| 10 | WELLS FARGO & COMPANY | 215 | 158 | 57 | 36.08 |
| 11 | American Credit Acceptance, LLC | 165 | 126 | 39 | 30.95 |
| 12 | AMERICAN HONDA FINANCE CORP | 154 | 118 | 36 | 30.51 |
| 13 | NAVY FEDERAL CREDIT UNION | 140 | 103 | 37 | 35.92 |
| 14 | Global Lending Services LLC | 135 | 141 | -6 | -4.26 |
| 15 | General Motors Financial Company, Inc. | 125 | 134 | -9 | -6.72 |
| 16 | JPMORGAN CHASE & CO. | 121 | 135 | -14 | -10.37 |
| 17 | NISSAN MOTOR ACCEPTANCE COMPANY LLC | 110 | 92 | 18 | 19.57 |
| 18 | TRUIST FINANCIAL CORPORATION | 109 | 99 | 10 | 10.10 |
| 19 | TD BANK US HOLDING COMPANY | 94 | 66 | 28 | 42.42 |
| 20 | Consumer Portfolio Services, Inc. | 90 | 71 | 19 | 26.76 |

Rank 21 (not in the top 20): BANK OF AMERICA, NATIONAL ASSOCIATION, 76 current-window complaints. No tie at the rank 20/21 cut. Ranks 5/6 are no longer tied (CAPITAL ONE FINANCIAL CORPORATION 292, HYUNDAI CAPITAL AMERICA 291).

## Data files

D2, attached under Rule 25 as a data file:

- ccdb-vehicle-top20-pull1.csv — 4720 rows (plus header), the current-window complaints of the 20 companies in table (a), 15 columns in the order listed in the job, key column Complaint ID, sorted by Complaint ID as a number, no duplicate Complaint ID, cells exactly as the export prints them. 1249969 bytes.

```synmerco-data
b9466cfbf4d8d23c38a697a8562be31bae9643c213422b398dd4d4a66e994206 ccdb-vehicle-top20-pull1.csv
```

D3, attached under Rule 25 as a data file:

- ccdb-vehicle-top20-pull2.csv — 4807 rows (plus header), the current-window complaints of the 20 companies in table (a), 15 columns in the order listed in the job, key column Complaint ID, sorted by Complaint ID as a number, no duplicate Complaint ID, cells exactly as the export prints them. 1275789 bytes.

D4, attached under Rule 25 as a data file:

- ccdb-vehicle-top20-pull3.csv — 4888 rows (plus header), the current-window complaints of the 20 companies in table (a), 15 columns in the order listed in the job, key column Complaint ID, sorted by Complaint ID as a number, no duplicate Complaint ID, cells exactly as the export prints them. 1298449 bytes.

```synmerco-data
b9466cfbf4d8d23c38a697a8562be31bae9643c213422b398dd4d4a66e994206 ccdb-vehicle-top20-pull1.csv
a872d2b03f2b183aa8cad68c18e05b6e0aaee3506d59f986714ede099dc6cf1e ccdb-vehicle-top20-pull2.csv
42fb100fc3254f85e29dca346637ee0c3738617c7a82e6ca00a8c9a2a8175a9c ccdb-vehicle-top20-pull3.csv
```

## Table (b) — PULL 3: per company and Issue

Every company and Issue pair of the 20 companies of PULL 3 with a current or prior count above 0: 181 pairs. Grouped by company in table (a) rank order; within a company, Issues by current count, largest first, ties by Issue ascending. Change = current minus prior. Current counts sum to 4888 (D4 row count); prior counts sum to 4241 (prior-window row count of the 20 companies).

| Company | Issue | Current | Prior | Change |
|---|---|---|---|---|
| SANTANDER HOLDINGS USA, INC. | Problems at the end of the loan or lease | 187 | 136 | 51 |
| SANTANDER HOLDINGS USA, INC. | Managing the loan or lease | 182 | 170 | 12 |
| SANTANDER HOLDINGS USA, INC. | Repossession | 137 | 111 | 26 |
| SANTANDER HOLDINGS USA, INC. | Incorrect information on your report | 51 | 51 | 0 |
| SANTANDER HOLDINGS USA, INC. | Struggling to pay your loan | 49 | 30 | 19 |
| SANTANDER HOLDINGS USA, INC. | Getting a loan or lease | 33 | 35 | -2 |
| SANTANDER HOLDINGS USA, INC. | Problem with a company's investigation into an existing problem | 15 | 15 | 0 |
| SANTANDER HOLDINGS USA, INC. | Improper use of your report | 4 | 3 | 1 |
| SANTANDER HOLDINGS USA, INC. | Problem with fraud alerts or security freezes | 2 | 0 | 2 |
| SANTANDER HOLDINGS USA, INC. | Credit monitoring or identity theft protection services | 1 | 3 | -2 |
| SANTANDER HOLDINGS USA, INC. | Unable to get your credit report or credit score | 1 | 1 | 0 |
| ALLY FINANCIAL INC. | Managing the loan or lease | 172 | 149 | 23 |
| ALLY FINANCIAL INC. | Repossession | 125 | 120 | 5 |
| ALLY FINANCIAL INC. | Problems at the end of the loan or lease | 117 | 100 | 17 |
| ALLY FINANCIAL INC. | Getting a loan or lease | 37 | 32 | 5 |
| ALLY FINANCIAL INC. | Struggling to pay your loan | 36 | 24 | 12 |
| ALLY FINANCIAL INC. | Incorrect information on your report | 33 | 40 | -7 |
| ALLY FINANCIAL INC. | Problem with a company's investigation into an existing problem | 15 | 19 | -4 |
| ALLY FINANCIAL INC. | Improper use of your report | 5 | 0 | 5 |
| ALLY FINANCIAL INC. | Credit monitoring or identity theft protection services | 2 | 3 | -1 |
| ALLY FINANCIAL INC. | Unable to get your credit report or credit score | 0 | 2 | -2 |
| Westlake Services, LLC | Repossession | 146 | 176 | -30 |
| Westlake Services, LLC | Managing the loan or lease | 138 | 140 | -2 |
| Westlake Services, LLC | Problems at the end of the loan or lease | 84 | 78 | 6 |
| Westlake Services, LLC | Getting a loan or lease | 42 | 37 | 5 |
| Westlake Services, LLC | Incorrect information on your report | 31 | 22 | 9 |
| Westlake Services, LLC | Struggling to pay your loan | 11 | 12 | -1 |
| Westlake Services, LLC | Problem with a company's investigation into an existing problem | 9 | 9 | 0 |
| Westlake Services, LLC | Improper use of your report | 3 | 6 | -3 |
| Westlake Services, LLC | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| CREDIT ACCEPTANCE CORPORATION | Managing the loan or lease | 179 | 78 | 101 |
| CREDIT ACCEPTANCE CORPORATION | Repossession | 126 | 79 | 47 |
| CREDIT ACCEPTANCE CORPORATION | Getting a loan or lease | 45 | 42 | 3 |
| CREDIT ACCEPTANCE CORPORATION | Struggling to pay your loan | 31 | 9 | 22 |
| CREDIT ACCEPTANCE CORPORATION | Problems at the end of the loan or lease | 30 | 18 | 12 |
| CREDIT ACCEPTANCE CORPORATION | Incorrect information on your report | 24 | 20 | 4 |
| CREDIT ACCEPTANCE CORPORATION | Problem with a company's investigation into an existing problem | 10 | 11 | -1 |
| CREDIT ACCEPTANCE CORPORATION | Credit monitoring or identity theft protection services | 1 | 0 | 1 |
| CREDIT ACCEPTANCE CORPORATION | Improper use of your report | 1 | 1 | 0 |
| CREDIT ACCEPTANCE CORPORATION | Problem with fraud alerts or security freezes | 1 | 0 | 1 |
| CREDIT ACCEPTANCE CORPORATION | Unable to get your credit report or credit score | 1 | 1 | 0 |
| CAPITAL ONE FINANCIAL CORPORATION | Managing the loan or lease | 82 | 93 | -11 |
| CAPITAL ONE FINANCIAL CORPORATION | Repossession | 70 | 55 | 15 |
| CAPITAL ONE FINANCIAL CORPORATION | Struggling to pay your loan | 40 | 35 | 5 |
| CAPITAL ONE FINANCIAL CORPORATION | Problems at the end of the loan or lease | 37 | 44 | -7 |
| CAPITAL ONE FINANCIAL CORPORATION | Getting a loan or lease | 31 | 42 | -11 |
| CAPITAL ONE FINANCIAL CORPORATION | Incorrect information on your report | 26 | 33 | -7 |
| CAPITAL ONE FINANCIAL CORPORATION | Problem with a company's investigation into an existing problem | 6 | 7 | -1 |
| CAPITAL ONE FINANCIAL CORPORATION | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| CAPITAL ONE FINANCIAL CORPORATION | Improper use of your report | 0 | 1 | -1 |
| CAPITAL ONE FINANCIAL CORPORATION | Unable to get your credit report or credit score | 0 | 1 | -1 |
| HYUNDAI CAPITAL AMERICA | Problems at the end of the loan or lease | 89 | 81 | 8 |
| HYUNDAI CAPITAL AMERICA | Managing the loan or lease | 72 | 67 | 5 |
| HYUNDAI CAPITAL AMERICA | Repossession | 59 | 52 | 7 |
| HYUNDAI CAPITAL AMERICA | Incorrect information on your report | 44 | 20 | 24 |
| HYUNDAI CAPITAL AMERICA | Getting a loan or lease | 12 | 12 | 0 |
| HYUNDAI CAPITAL AMERICA | Problem with a company's investigation into an existing problem | 9 | 6 | 3 |
| HYUNDAI CAPITAL AMERICA | Struggling to pay your loan | 5 | 5 | 0 |
| HYUNDAI CAPITAL AMERICA | Credit monitoring or identity theft protection services | 1 | 1 | 0 |
| Bridgecrest Acceptance Corporation | Managing the loan or lease | 95 | 69 | 26 |
| Bridgecrest Acceptance Corporation | Repossession | 74 | 90 | -16 |
| Bridgecrest Acceptance Corporation | Problems at the end of the loan or lease | 38 | 38 | 0 |
| Bridgecrest Acceptance Corporation | Incorrect information on your report | 20 | 14 | 6 |
| Bridgecrest Acceptance Corporation | Struggling to pay your loan | 17 | 14 | 3 |
| Bridgecrest Acceptance Corporation | Getting a loan or lease | 12 | 18 | -6 |
| Bridgecrest Acceptance Corporation | Problem with a company's investigation into an existing problem | 12 | 11 | 1 |
| Bridgecrest Acceptance Corporation | Improper use of your report | 0 | 2 | -2 |
| TOYOTA MOTOR CREDIT CORPORATION | Managing the loan or lease | 74 | 84 | -10 |
| TOYOTA MOTOR CREDIT CORPORATION | Repossession | 50 | 49 | 1 |
| TOYOTA MOTOR CREDIT CORPORATION | Problems at the end of the loan or lease | 42 | 34 | 8 |
| TOYOTA MOTOR CREDIT CORPORATION | Getting a loan or lease | 28 | 14 | 14 |
| TOYOTA MOTOR CREDIT CORPORATION | Struggling to pay your loan | 18 | 9 | 9 |
| TOYOTA MOTOR CREDIT CORPORATION | Incorrect information on your report | 15 | 24 | -9 |
| TOYOTA MOTOR CREDIT CORPORATION | Problem with a company's investigation into an existing problem | 4 | 11 | -7 |
| TOYOTA MOTOR CREDIT CORPORATION | Credit monitoring or identity theft protection services | 3 | 0 | 3 |
| TOYOTA MOTOR CREDIT CORPORATION | Improper use of your report | 3 | 1 | 2 |
| Exeter Finance, LLC. | Managing the loan or lease | 65 | 57 | 8 |
| Exeter Finance, LLC. | Repossession | 61 | 47 | 14 |
| Exeter Finance, LLC. | Problems at the end of the loan or lease | 29 | 14 | 15 |
| Exeter Finance, LLC. | Getting a loan or lease | 27 | 19 | 8 |
| Exeter Finance, LLC. | Struggling to pay your loan | 19 | 12 | 7 |
| Exeter Finance, LLC. | Incorrect information on your report | 17 | 17 | 0 |
| Exeter Finance, LLC. | Problem with a company's investigation into an existing problem | 5 | 7 | -2 |
| Exeter Finance, LLC. | Unable to get your credit report or credit score | 1 | 0 | 1 |
| Exeter Finance, LLC. | Improper use of your report | 0 | 2 | -2 |
| Exeter Finance, LLC. | Problem with fraud alerts or security freezes | 0 | 1 | -1 |
| WELLS FARGO & COMPANY | Managing the loan or lease | 59 | 53 | 6 |
| WELLS FARGO & COMPANY | Repossession | 54 | 31 | 23 |
| WELLS FARGO & COMPANY | Problems at the end of the loan or lease | 46 | 39 | 7 |
| WELLS FARGO & COMPANY | Incorrect information on your report | 19 | 14 | 5 |
| WELLS FARGO & COMPANY | Getting a loan or lease | 16 | 15 | 1 |
| WELLS FARGO & COMPANY | Problem with a company's investigation into an existing problem | 9 | 2 | 7 |
| WELLS FARGO & COMPANY | Struggling to pay your loan | 5 | 3 | 2 |
| WELLS FARGO & COMPANY | Credit monitoring or identity theft protection services | 4 | 1 | 3 |
| WELLS FARGO & COMPANY | Improper use of your report | 3 | 0 | 3 |
| American Credit Acceptance, LLC | Repossession | 55 | 47 | 8 |
| American Credit Acceptance, LLC | Managing the loan or lease | 48 | 32 | 16 |
| American Credit Acceptance, LLC | Struggling to pay your loan | 19 | 11 | 8 |
| American Credit Acceptance, LLC | Problems at the end of the loan or lease | 17 | 11 | 6 |
| American Credit Acceptance, LLC | Getting a loan or lease | 13 | 11 | 2 |
| American Credit Acceptance, LLC | Incorrect information on your report | 8 | 7 | 1 |
| American Credit Acceptance, LLC | Problem with a company's investigation into an existing problem | 3 | 3 | 0 |
| American Credit Acceptance, LLC | Improper use of your report | 2 | 3 | -1 |
| American Credit Acceptance, LLC | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| AMERICAN HONDA FINANCE CORP | Managing the loan or lease | 54 | 33 | 21 |
| AMERICAN HONDA FINANCE CORP | Repossession | 43 | 25 | 18 |
| AMERICAN HONDA FINANCE CORP | Problems at the end of the loan or lease | 20 | 21 | -1 |
| AMERICAN HONDA FINANCE CORP | Incorrect information on your report | 10 | 13 | -3 |
| AMERICAN HONDA FINANCE CORP | Getting a loan or lease | 8 | 15 | -7 |
| AMERICAN HONDA FINANCE CORP | Struggling to pay your loan | 7 | 3 | 4 |
| AMERICAN HONDA FINANCE CORP | Improper use of your report | 6 | 0 | 6 |
| AMERICAN HONDA FINANCE CORP | Problem with a company's investigation into an existing problem | 5 | 8 | -3 |
| AMERICAN HONDA FINANCE CORP | Unable to get your credit report or credit score | 1 | 0 | 1 |
| NAVY FEDERAL CREDIT UNION | Managing the loan or lease | 39 | 31 | 8 |
| NAVY FEDERAL CREDIT UNION | Problems at the end of the loan or lease | 39 | 31 | 8 |
| NAVY FEDERAL CREDIT UNION | Repossession | 31 | 17 | 14 |
| NAVY FEDERAL CREDIT UNION | Getting a loan or lease | 14 | 11 | 3 |
| NAVY FEDERAL CREDIT UNION | Incorrect information on your report | 8 | 6 | 2 |
| NAVY FEDERAL CREDIT UNION | Struggling to pay your loan | 8 | 4 | 4 |
| NAVY FEDERAL CREDIT UNION | Problem with a company's investigation into an existing problem | 1 | 3 | -2 |
| Global Lending Services LLC | Repossession | 58 | 47 | 11 |
| Global Lending Services LLC | Managing the loan or lease | 41 | 34 | 7 |
| Global Lending Services LLC | Getting a loan or lease | 11 | 17 | -6 |
| Global Lending Services LLC | Problems at the end of the loan or lease | 11 | 15 | -4 |
| Global Lending Services LLC | Struggling to pay your loan | 8 | 10 | -2 |
| Global Lending Services LLC | Incorrect information on your report | 4 | 10 | -6 |
| Global Lending Services LLC | Problem with a company's investigation into an existing problem | 2 | 7 | -5 |
| Global Lending Services LLC | Improper use of your report | 0 | 1 | -1 |
| General Motors Financial Company, Inc. | Managing the loan or lease | 38 | 26 | 12 |
| General Motors Financial Company, Inc. | Repossession | 35 | 46 | -11 |
| General Motors Financial Company, Inc. | Problems at the end of the loan or lease | 24 | 20 | 4 |
| General Motors Financial Company, Inc. | Struggling to pay your loan | 9 | 3 | 6 |
| General Motors Financial Company, Inc. | Incorrect information on your report | 6 | 12 | -6 |
| General Motors Financial Company, Inc. | Problem with a company's investigation into an existing problem | 6 | 10 | -4 |
| General Motors Financial Company, Inc. | Getting a loan or lease | 5 | 15 | -10 |
| General Motors Financial Company, Inc. | Improper use of your report | 2 | 0 | 2 |
| General Motors Financial Company, Inc. | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| General Motors Financial Company, Inc. | Unable to get your credit report or credit score | 0 | 1 | -1 |
| JPMORGAN CHASE & CO. | Repossession | 31 | 24 | 7 |
| JPMORGAN CHASE & CO. | Managing the loan or lease | 27 | 27 | 0 |
| JPMORGAN CHASE & CO. | Problems at the end of the loan or lease | 27 | 39 | -12 |
| JPMORGAN CHASE & CO. | Getting a loan or lease | 15 | 10 | 5 |
| JPMORGAN CHASE & CO. | Incorrect information on your report | 15 | 16 | -1 |
| JPMORGAN CHASE & CO. | Problem with a company's investigation into an existing problem | 4 | 10 | -6 |
| JPMORGAN CHASE & CO. | Improper use of your report | 1 | 1 | 0 |
| JPMORGAN CHASE & CO. | Struggling to pay your loan | 1 | 8 | -7 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Managing the loan or lease | 33 | 21 | 12 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Problems at the end of the loan or lease | 33 | 27 | 6 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Repossession | 25 | 18 | 7 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Problem with a company's investigation into an existing problem | 5 | 5 | 0 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Struggling to pay your loan | 5 | 2 | 3 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Getting a loan or lease | 4 | 6 | -2 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Incorrect information on your report | 4 | 11 | -7 |
| NISSAN MOTOR ACCEPTANCE COMPANY LLC | Improper use of your report | 1 | 2 | -1 |
| TRUIST FINANCIAL CORPORATION | Managing the loan or lease | 35 | 30 | 5 |
| TRUIST FINANCIAL CORPORATION | Repossession | 24 | 16 | 8 |
| TRUIST FINANCIAL CORPORATION | Problems at the end of the loan or lease | 21 | 26 | -5 |
| TRUIST FINANCIAL CORPORATION | Getting a loan or lease | 7 | 6 | 1 |
| TRUIST FINANCIAL CORPORATION | Incorrect information on your report | 7 | 9 | -2 |
| TRUIST FINANCIAL CORPORATION | Struggling to pay your loan | 7 | 5 | 2 |
| TRUIST FINANCIAL CORPORATION | Problem with a company's investigation into an existing problem | 6 | 5 | 1 |
| TRUIST FINANCIAL CORPORATION | Credit monitoring or identity theft protection services | 1 | 0 | 1 |
| TRUIST FINANCIAL CORPORATION | Improper use of your report | 1 | 2 | -1 |
| TD BANK US HOLDING COMPANY | Repossession | 29 | 6 | 23 |
| TD BANK US HOLDING COMPANY | Managing the loan or lease | 26 | 20 | 6 |
| TD BANK US HOLDING COMPANY | Problems at the end of the loan or lease | 18 | 24 | -6 |
| TD BANK US HOLDING COMPANY | Getting a loan or lease | 6 | 5 | 1 |
| TD BANK US HOLDING COMPANY | Incorrect information on your report | 6 | 4 | 2 |
| TD BANK US HOLDING COMPANY | Problem with a company's investigation into an existing problem | 4 | 2 | 2 |
| TD BANK US HOLDING COMPANY | Struggling to pay your loan | 4 | 4 | 0 |
| TD BANK US HOLDING COMPANY | Improper use of your report | 1 | 0 | 1 |
| TD BANK US HOLDING COMPANY | Unable to get your credit report or credit score | 0 | 1 | -1 |
| Consumer Portfolio Services, Inc. | Repossession | 29 | 18 | 11 |
| Consumer Portfolio Services, Inc. | Managing the loan or lease | 21 | 24 | -3 |
| Consumer Portfolio Services, Inc. | Getting a loan or lease | 12 | 6 | 6 |
| Consumer Portfolio Services, Inc. | Incorrect information on your report | 11 | 4 | 7 |
| Consumer Portfolio Services, Inc. | Struggling to pay your loan | 8 | 8 | 0 |
| Consumer Portfolio Services, Inc. | Problems at the end of the loan or lease | 6 | 8 | -2 |
| Consumer Portfolio Services, Inc. | Problem with a company's investigation into an existing problem | 3 | 1 | 2 |
| Consumer Portfolio Services, Inc. | Credit monitoring or identity theft protection services | 0 | 1 | -1 |
| Consumer Portfolio Services, Inc. | Improper use of your report | 0 | 1 | -1 |

## Table (c) — PULL 3: top 10 Issues by total change

Total change per Issue = sum over the 20 companies of current minus prior. Sorted by total change, largest first; ties by Issue ascending. Largest-change company = the company with the greatest signed change for that Issue among the 20 companies; ties by Company ascending. The 11th Issue, "Problem with a company's investigation into an existing problem", total change -19, is outside the top 10.

| Rank | Issue | Current | Prior | Change | Largest-change company (change) |
|---|---|---|---|---|---|
| 1 | Managing the loan or lease | 1480 | 1238 | 242 | CREDIT ACCEPTANCE CORPORATION (+101) |
| 2 | Repossession | 1262 | 1074 | 188 | CREDIT ACCEPTANCE CORPORATION (+47) |
| 3 | Problems at the end of the loan or lease | 915 | 804 | 111 | SANTANDER HOLDINGS USA, INC. (+51) |
| 4 | Struggling to pay your loan | 307 | 211 | 96 | CREDIT ACCEPTANCE CORPORATION (+22) |
| 5 | Incorrect information on your report | 359 | 347 | 12 | HYUNDAI CAPITAL AMERICA (+24) |
| 6 | Getting a loan or lease | 378 | 368 | 10 | TOYOTA MOTOR CREDIT CORPORATION (+14) |
| 7 | Improper use of your report | 33 | 26 | 7 | AMERICAN HONDA FINANCE CORP (+6) |
| 8 | Problem with fraud alerts or security freezes | 3 | 1 | 2 | SANTANDER HOLDINGS USA, INC. (+2) |
| 9 | Credit monitoring or identity theft protection services | 14 | 13 | 1 | TOYOTA MOTOR CREDIT CORPORATION (+3) |
| 10 | Unable to get your credit report or credit score | 4 | 7 | -3 | AMERICAN HONDA FINANCE CORP (+1) |

## Changes sections

- Changes PULL 2 vs PULL 1 (matched by Complaint ID: new / gone / changed counts and both row counts): see "Changes PULL 2 vs PULL 1" below.
- Changes PULL 3 vs PULL 2: see "Changes PULL 3 vs PULL 2" below.

## Changes PULL 2 vs PULL 1

Current window, matched by Complaint ID (the key column). PULL 1 current-window rows: 6589. PULL 2 current-window rows: 6701.

| | Count |
|---|---|
| New (in PULL 2, not in PULL 1) | 112 |
| Gone (in PULL 1, not in PULL 2) | 0 |
| Changed (same Complaint ID, at least one cell differs) | 60 |
| Unchanged | 6529 |

Check: 6589 − 0 + 112 = 6701. The 60 changed rows differ only in response fields: Company response to consumer changed in 60 rows, Company public response in 21 of those rows; no other column changed. The 112 new rows are complaints that reached the database after PULL 1 (all with Date received in the current window); no complaint left the window.

Biggest movers in table (a) versus PULL 1 (current count): CREDIT ACCEPTANCE CORPORATION +16 (420 → 436) and SANTANDER HOLDINGS USA, INC. +16 (631 → 647), then HYUNDAI CAPITAL AMERICA +12 (277 → 289), CAPITAL ONE FINANCIAL CORPORATION +7 (282 → 289), Exeter Finance, LLC. +6 (209 → 215). No company fell in the top 20 versus PULL 1; the top-20 set is unchanged.

## Changes PULL 3 vs PULL 2

Current window, matched by Complaint ID (the key column). PULL 2 current-window rows: 6701. PULL 3 current-window rows: 6808.

| | Count |
|---|---|
| New (in PULL 3, not in PULL 2) | 108 |
| Gone (in PULL 2, not in PULL 3) | 1 |
| Changed (same Complaint ID, at least one cell differs) | 62 |
| Unchanged | 6638 |

Check: 6701 − 1 + 108 = 6808. The 62 changed rows differ only in response fields: Company response to consumer changed in 62 rows, Company public response in 20 of those rows; no other column changed. The 108 new rows are complaints that reached the database after PULL 2 (all with Date received in the current window, 2026-09-17 to 2026-11-12); the 1 gone row is Complaint ID 31937838 (CAPITAL ONE FINANCIAL CORPORATION, Repossession, Date received 2026-11-05, Company response to consumer "In progress" in PULL 2), no longer returned for the same query in PULL 3.

Biggest movers in table (a) versus PULL 2 (current count): SANTANDER HOLDINGS USA, INC. +15 (647 → 662) and CREDIT ACCEPTANCE CORPORATION +13 (436 → 449), then Bridgecrest Acceptance Corporation +12 (256 → 268), Exeter Finance, LLC. +9 (215 → 224), WELLS FARGO & COMPANY +7 (208 → 215). No company fell in the top 20 versus PULL 2; the top-20 set is unchanged; only ranks 17/18 swapped (NISSAN MOTOR ACCEPTANCE COMPANY LLC before TRUIST FINANCIAL CORPORATION).

## PROOF — PULL 1 requests

Every request below lists host, path and parameters, its UTC time (the response Date header), and a raw excerpt: the Date header line, then the CSV header and first 3 records, or the reported total for the no-format query. Excerpts are copied exactly as the source returned them.

### P1. Current window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12, format=csv
- Retrieved (UTC): 2026-11-20 03:26:59 GMT (response Date header)
- Rows returned: 6589

```
Date: Fri, 20 Nov 2026 03:26:59 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-08-15T13:37:21.000Z,Vehicle loan or lease,Loan,Managing the loan or lease,Problem with the interest rate,Company believes it acted appropriately as authorized by contract or law,NAVY FEDERAL CREDIT UNION,PA,17112,Servicemember,Web,2026-08-15T13:45:18.000Z,Closed with explanation,Yes,25398951
2026-08-15T20:29:36.000Z,Vehicle loan or lease,Loan,Repossession,Company communicating payment assistance or payment extension options,None,CAPITAL ONE FINANCIAL CORPORATION,ID,83338,None,Web,2026-08-15T20:35:30.000Z,Closed with explanation,Yes,25405637
2026-08-16T17:25:52.000Z,Vehicle loan or lease,Loan,Managing the loan or lease,Billing problem,None,"SANTANDER HOLDINGS USA, INC.",MD,20872,None,Web,2026-08-16T17:40:36.000Z,Closed with explanation,Yes,25421176
```

### P2. Current window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12
- Retrieved (UTC): 2026-11-20 03:27:04 GMT (response Date header)
- Reported total: value 6589, relation eq

```
Date: Fri, 20 Nov 2026 03:27:04 GMT
"hits":{"total":{"value":6589,"relation":"eq"}
```

### P3. Prior window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14, format=csv
- Retrieved (UTC): 2026-11-20 03:27:06 GMT (response Date header)
- Rows returned: 6045

```
Date: Fri, 20 Nov 2026 03:27:06 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-07-07T01:24:08.000Z,Vehicle loan or lease,Loan,Getting a loan or lease,Loan opened without my consent or knowledge,None,"SANTANDER HOLDINGS USA, INC.",FL,338XX,None,Web,2026-07-07T01:43:09.000Z,Closed with explanation,Yes,23923587
2026-07-07T00:56:55.000Z,Vehicle loan or lease,Loan,Improper use of your report,Credit inquiries on your report that you don't recognize,Company has responded to the consumer and the CFPB and chooses not to provide a public response,Stellantis Financial Services US Corp.,SC,290XX,None,Web,2026-07-07T01:02:37.000Z,Closed with explanation,Yes,23922490
2026-07-07T01:21:29.000Z,Vehicle loan or lease,Lease,Problems at the end of the loan or lease,Problem while selling or giving up the vehicle,Company has responded to the consumer and the CFPB and chooses not to provide a public response,HYUNDAI CAPITAL AMERICA,CA,94070,None,Web,2026-07-07T01:47:37.000Z,Closed with explanation,Yes,23923683
```

### P4. Prior window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14
- Retrieved (UTC): 2026-11-20 03:27:11 GMT (response Date header)
- Reported total: value 6045, relation eq

```
Date: Fri, 20 Nov 2026 03:27:11 GMT
"hits":{"total":{"value":6045,"relation":"eq"}
```

## PROOF — PULL 2 requests

Every request below lists host, path and parameters, its UTC time (the response Date header), and a raw excerpt: the Date header line, then the CSV header and first 3 records, or the reported total for the no-format query. Excerpts are copied exactly as the source returned them.

### P5. Current window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12, format=csv
- Retrieved (UTC): 2026-11-21 03:37:34 GMT (response Date header)
- Rows returned: 6701

```
Date: Sat, 21 Nov 2026 03:37:34 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-08-21T09:09:07.000Z,Vehicle loan or lease,Loan,Managing the loan or lease,Billing problem,Company has responded to the consumer and the CFPB and chooses not to provide a public response,UNITED SERVICES AUTOMOBILE ASSOCIATION,GA,30060,None,Referral,2026-08-21T17:06:34.000Z,Closed with explanation,Yes,25653169
2026-08-21T19:01:45.000Z,Vehicle loan or lease,Loan,Struggling to pay your loan,Denied request to lower payments,None,"American Credit Acceptance, LLC",NY,12771,None,Web,2026-08-21T20:13:18.000Z,Closed with explanation,Yes,25662465
2026-08-22T00:50:09.000Z,Vehicle loan or lease,Loan,Struggling to pay your loan,Denied request to lower payments,Company has responded to the consumer and the CFPB and chooses not to provide a public response,HYUNDAI CAPITAL AMERICA,FL,32303,None,Web,2026-08-22T01:01:04.000Z,Closed with explanation,Yes,25674677
```

### P6. Current window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12
- Retrieved (UTC): 2026-11-21 03:37:38 GMT (response Date header)
- Reported total: value 6701, relation eq

```
Date: Sat, 21 Nov 2026 03:37:38 GMT
"hits":{"total":{"value":6701,"relation":"eq"}
```

### P7. Prior window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14, format=csv
- Retrieved (UTC): 2026-11-21 03:37:41 GMT (response Date header)
- Rows returned: 6045

```
Date: Sat, 21 Nov 2026 03:37:41 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-07-07T01:24:08.000Z,Vehicle loan or lease,Loan,Getting a loan or lease,Loan opened without my consent or knowledge,None,"SANTANDER HOLDINGS USA, INC.",FL,338XX,None,Web,2026-07-07T01:43:09.000Z,Closed with explanation,Yes,23923587
2026-07-07T00:56:55.000Z,Vehicle loan or lease,Loan,Improper use of your report,Credit inquiries on your report that you don't recognize,Company has responded to the consumer and the CFPB and chooses not to provide a public response,Stellantis Financial Services US Corp.,SC,290XX,None,Web,2026-07-07T01:02:37.000Z,Closed with explanation,Yes,23922490
2026-07-07T01:21:29.000Z,Vehicle loan or lease,Lease,Problems at the end of the loan or lease,Problem while selling or giving up the vehicle,Company has responded to the consumer and the CFPB and chooses not to provide a public response,HYUNDAI CAPITAL AMERICA,CA,94070,None,Web,2026-07-07T01:47:37.000Z,Closed with explanation,Yes,23923683
```

### P8. Prior window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14
- Retrieved (UTC): 2026-11-21 03:37:45 GMT (response Date header)
- Reported total: value 6045, relation eq

```
Date: Sat, 21 Nov 2026 03:37:45 GMT
"hits":{"total":{"value":6045,"relation":"eq"}
```

## PROOF — PULL 3 requests

Every request below lists host, path and parameters, its UTC time (the response Date header), and a raw excerpt: the Date header line, then the CSV header and first 3 records, or the reported total for the no-format query. Excerpts are copied exactly as the source returned them.

### P9. Current window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12, format=csv
- Retrieved (UTC): 2026-11-22 03:42:47 GMT (response Date header)
- Rows returned: 6808

```
Date: Sun, 22 Nov 2026 03:42:47 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-08-15T13:37:21.000Z,Vehicle loan or lease,Loan,Managing the loan or lease,Problem with the interest rate,Company believes it acted appropriately as authorized by contract or law,NAVY FEDERAL CREDIT UNION,PA,17112,Servicemember,Web,2026-08-15T13:45:18.000Z,Closed with explanation,Yes,25398951
2026-08-15T20:29:36.000Z,Vehicle loan or lease,Loan,Repossession,Company communicating payment assistance or payment extension options,None,CAPITAL ONE FINANCIAL CORPORATION,ID,83338,None,Web,2026-08-15T20:35:30.000Z,Closed with explanation,Yes,25405637
2026-08-16T17:25:52.000Z,Vehicle loan or lease,Loan,Managing the loan or lease,Billing problem,None,"SANTANDER HOLDINGS USA, INC.",MD,20872,None,Web,2026-08-16T17:40:36.000Z,Closed with explanation,Yes,25421176
```

### P10. Current window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-08-15, date_received_max=2026-11-12
- Retrieved (UTC): 2026-11-22 03:42:51 GMT (response Date header)
- Reported total: value 6808, relation eq

```
Date: Sun, 22 Nov 2026 03:42:51 GMT
"hits":{"total":{"value":6808,"relation":"eq"}
```

### P11. Prior window, format=csv

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14, format=csv
- Retrieved (UTC): 2026-11-22 03:42:53 GMT (response Date header)
- Rows returned: 6045

```
Date: Sun, 22 Nov 2026 03:42:53 GMT
Date received,Product,Sub-product,Issue,Sub-issue,Company public response,Company,State,ZIP code,Tags,Submitted via,Date sent to company,Company response to consumer,Timely response?,Complaint ID
2026-06-17T14:02:23.000Z,Vehicle loan or lease,Loan,Problems at the end of the loan or lease,Unable to receive car title or other problem after the loan is paid off,None,"Westlake Services, LLC",WI,53213,None,Web,2026-06-17T14:15:36.000Z,Closed with explanation,Yes,23296439
2026-07-31T09:40:41.000Z,Vehicle loan or lease,Loan,Getting a loan or lease,Confusing or misleading advertising or marketing,None,"AC AutoPay LLC, Denver, CO Branch",FL,326XX,None,Web,2026-07-31T09:48:20.000Z,Closed with explanation,Yes,24806242
2026-07-31T16:54:21.000Z,Vehicle loan or lease,Loan,Repossession,Account reinstatement or redemption after repossession,None,Premier Auto Credit,CA,90003,None,Web,2026-07-31T17:30:21.000Z,Closed with explanation,Yes,24819952
```

### P12. Prior window, no format (total)

- Host: www.consumerfinance.gov
- Path: /data-research/consumer-complaints/search/api/v1/
- Parameters: product=Vehicle loan or lease, date_received_min=2026-05-17, date_received_max=2026-08-14
- Retrieved (UTC): 2026-11-22 03:42:57 GMT (response Date header)
- Reported total: value 6045, relation eq

```
Date: Sun, 22 Nov 2026 03:42:57 GMT
"hits":{"total":{"value":6045,"relation":"eq"}
```

## Acceptance self-check (final — PULL 3 status)

1. The three CSV files attached with exactly the listed columns, each holding the current-window rows of that pull's 20 companies, no duplicate Complaint ID — met: D2 (4720 rows), D3 (4807 rows) and D4 (4888 rows), each 15 columns, no duplicate Complaint ID; see "Data files" and the D2/D3/D4 descriptions above.
2. Each table (a) lists exactly 20 companies by exact string, ranked by current count with the tie-break, current counts summing to that pull's CSV row count and prior counts to the stated prior-window row count — met for all three pulls; PULL 3: current sum 4888 = D4 rows, prior sum 4241 = stated prior-window row count of the 20 companies (see "Table (a) — PULL 3" above).
3. Table (b) covers every company and Issue pair of the 20 companies of pull 3 (or the last pull that did not fail), and table (c) has 10 Issues sorted by change with the tie-breaks, each with its largest-change company — met: table (b) has all 181 pairs of the PULL 3 top 20 (current sum 4888, prior sum 4241), table (c) has the top 10 Issues by total change with each largest-change company (see "Table (b) — PULL 3" and "Table (c) — PULL 3" above).
4. The report states both windows' CSV row counts and totals for every pull, and the PROOF shows each request with its UTC time, Date header line and the CSV header with first records or the total — met for all three pulls; PULL 3: current 6808 = total 6808 (eq), prior 6045 = total 6045 (eq) (see "PULL 3 — row counts and totals" and "PROOF — PULL 3 requests", P9–P12, above).
5. The PLATFORM RECORD shows a PULL 1: note and each later PULL note at least its wait after the one before, each with its CSV's row count and SHA-256; each pull's source time later than the previous pull's; change counts agree with the CSV files — met: PULL 1 note filed (row count 4720, SHA-256 b9466cfbf4d8d23c38a697a8562be31bae9643c213422b398dd4d4a66e994206); PULL 2 note filed 2026-11-21 03:40:39 UTC (row count 4807, SHA-256 a872d2b03f2b183aa8cad68c18e05b6e0aaee3506d59f986714ede099dc6cf1e), 24h 08m 53s after the PULL 1 note; PULL 3 note filed 2026-11-22 03:45:22 UTC (row count 4888, SHA-256 42fb100fc3254f85e29dca346637ee0c3738617c7a82e6ca00a8c9a2a8175a9c), 24h 04m 43s after the PULL 2 note. Each pull's source time is later than the previous pull's (PULL 1 03:26:59–03:27:11 UTC 20 Nov; PULL 2 03:37:34–03:37:45 UTC 21 Nov; PULL 3 03:42:47–03:42:57 UTC 22 Nov). Change counts agree with the CSV files (PULL 3 vs PULL 2: 6701 − 1 + 108 = 6808; see "Changes PULL 3 vs PULL 2" above).
