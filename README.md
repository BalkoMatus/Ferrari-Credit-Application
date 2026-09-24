# Ferrari Credit Application

A credit application for a €1.1bn term loan to Ferrari N.V., with an integrated Excel model. The loan finances a hypothetical project, the Ferrari Residential Complex Miami, a €1,425m branded residential development. The question is whether Ferrari can take on the loan without weakening its credit profile.

I wrote it for EM032 Banking at IES, Charles University (November 2025).

> **Hypothetical case study.** The Miami project, its costs, financing and loan terms were made up for an academic exercise. Ferrari N.V. has not announced such a project. The 2022-2024 financial statements are Ferrari's reported figures. This work is not affiliated with or endorsed by Ferrari N.V.

## Files

| File | Contents |
|---|---|
| [`Ferrari_Credit_Application.pdf`](Ferrari_Credit_Application.pdf) | The credit application: non-financial and financial analysis of Ferrari (2022-2024), business plan to 2030, the project and the loan, and the effect of the project on the group |
| [`Ferrari_Credit_Application_Model.xlsx`](Ferrari_Credit_Application_Model.xlsx) | Integrated three-statement model, 2022A-2030F, for Ferrari standalone and with the project |

## The loan

| Term | |
|---|---|
| Amount | €1,100m, full recourse to Ferrari N.V. |
| Interest rate | 5.0% fixed |
| Drawdown | Quarterly tranches in 2026-2028, as construction progresses |
| Repayment | Interest-only until completion, then eight equal quarterly instalments of €145.35m, Q1 2029 to Q4 2030 |
| Total interest | €154.0m |
| Equity | €325m of Ferrari's own funds, spent before the loan is drawn |

## Key results

Base case, average selling price of €20,000 per m².

| Metric | Result |
|---|---:|
| Peak net debt / EBITDA with the project | 0.72x (2028), vs. 0.25x standalone |
| Minimum EBITDA / interest | 16.1x |
| Project DSCR | 1.78x (2029), 1.18x (2030) |
| Group free cash flow / annual project debt service | 2.9x to 3.1x |
| Unlevered pre-tax project IRR | 8.5% |
| Break-even price including loan interest | €17,545 per m² |

The 2030 project DSCR is below the 1.20x a bank would usually ask of a stand-alone project. The loan is corporate with full recourse, so the relevant test is group cash flow, which covers the debt service about three times. Leverage stays below 1.0x net debt to EBITDA throughout, and the application recommends approving the loan.

## Model

| Sheet | Contents |
|---|---|
| Cover | Contents, key figures, base-case credit profile and model checks |
| Inputs | Forecast drivers and project assumptions, each with its basis and source |
| Model | Income statement, revenue build, balance sheet, cash flow, ratio analysis, working capital, fixed assets, financing, the residential project, the loan schedule, pro-forma statements with the project and credit metrics |

- All figures in € millions. Historical data for 2022-2024 come from Ferrari's Form 20-F filings (IFRS).
- Revenue is built from shipments by region and net revenue per unit, in line with Ferrari's 2025 guidance and the 2030 targets from its October 2025 Capital Markets Day.
- Cash comes from the cash flow statement, so the balance sheet balances without a plug. The Cover sheet checks that both balance sheets balance, that cash stays positive, that the instalment matches Excel's PMT and that the loan is repaid by Q4 2030.
- Project revenue is recognised on handover (IFRS 15) and development costs are held as inventory until then (IAS 2). Loan interest is expensed as incurred for simplicity. Under IAS 23 it would be capitalised into inventory, with the same total profit.

Matúš Balko, 2025
