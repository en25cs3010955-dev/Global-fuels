# Global Fuel Prices & Taxation Dashboard (2020–2026)

A Tableau dashboard with 9 visualisations analysing fuel prices, taxation and subsidies across **84 countries** and **7 regions** (27,468 weekly records, Jan 2020 – Apr 2026).

**Author:** Syed Imad Ali

- **Demo video (Google Drive):** https://drive.google.com/file/d/1RaTwyccMFTmnkpmScIrtc5T23haDg9AM/view?usp=sharing
**Website link:**https://en25cs3010955-dev.github.io/Global-fuels/

## Problem Statement

Analyse global petrol, diesel and LPG prices together with tax and subsidy structures, and answer the questions of three stakeholders.

| Scenario | Stakeholder | Focus |
|---|---|---|
| 1 | Dr. Sarah Mitchell, Energy Policy Consultant | Tax disparities and the effect of subsidies on prices |
| 2 | Marcus Thompson, Supply Chain Manager | Regional price variation, trends, forecasts and volatility |
| 3 | Prof. Elena Rodriguez, Energy Economics Researcher | How income level relates to taxation, subsidies and prices |

## Visualisations

| # | Sheet | Scenario |
|---|---|---|
| 1 | Average Fuel Tax Rate by Country (map) | 1 |
| 2 | Tax Rate by Region and Subsidy Level | 1 |
| 3 | Do Subsidies Lower Fuel Prices? | 1 |
| 4 | Diesel Price Trend and Forecast by Region | 2 |
| 5 | Top 10 Costliest / Cheapest Diesel Markets | 2 |
| 6 | Diesel Price Volatility by Region and Year | 2 |
| 7 | Do Wealthier Nations Tax Fuel More? | 3 |
| 8 | Subsidy Levels by Income Group | 3 |
| 9 | Average Fuel Prices by Type and Income Level | 3 |

## Dataset

`global_fuel_prices_Dataset.csv` with columns: `date, country, region, income_level, subsidy_level, petrol_usd_liter, diesel_usd_liter, lpg_usd_liter, brent_crude_usd, tax_percentage`.

## Calculated Fields

- **Subsidy Score:** converts Low / Medium / High / Very High to 1–4.
- **Avg Fuel Price:** mean of petrol, diesel and LPG prices.
- **Diesel Volatility:** standard deviation of diesel price divided by its average.

## Repository Structure

```
├── README.md
├── dashboard/        Tableau workbook (.twb / .twbx)
├── data/             Dataset (CSV)
├── video/            Demo video
├── templates/        Filled templates (PDF / Word)
└── documentation/    Project documentation
```

## Tools

Tableau Public / Tableau Desktop
