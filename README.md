# Gold Price Trend Analysis

A time-series analysis of historical gold prices, examining long-term growth patterns and seasonal trends — built to complement the market research behind the SmartGold AI & Unixora project.

## Overview

This project analyzes nearly 200 years of monthly gold price data (1833–present) to understand long-term price behavior, recent growth trends, and seasonal pricing patterns. It was built to add a data-driven market perspective to the Unixora gold purity analyzer project, connecting the hardware/software system to the pricing environment it operates in.

## Dataset

- **Source:** Monthly gold prices in USD per troy ounce (1833–present), compiled from historical records and World Bank Commodity Markets data
- **Fields:** Date, Price

## Process

1. **Data Loading & Cleaning** — Parsed dates, removed missing price entries
2. **Long-Term Trend Analysis** — Visualized full price history (1833–present) and a zoomed-in view from 2000 onward
3. **Recent Trend Analysis** — Calculated yearly average prices for the last 15 years and plotted the last 12 months
4. **Seasonality Analysis** — Compared average prices by calendar month (2015–present) to identify recurring seasonal patterns
5. **Growth Calculations** — Computed overall historical growth and 5-year growth rate

## Key Findings

- **Gold prices remained largely flat for over a century** under the historical gold standard, before entering a sustained upward trend after 2000
- **5-year growth: 126.5%** — gold has more than doubled in value over the last five years, reflecting strong demand as an inflation hedge and safe-haven asset
- **2026 recorded the highest yearly average price on record**, continuing a steep upward trajectory
- **Seasonal pricing patterns exist**, with certain months showing consistently higher average prices — relevant context for jewellery retailers timing purchases or sales around festival and wedding seasons

## Relevance to Unixora

This analysis reinforces the business case behind the Unixora purity analyzer: as gold prices continue to climb, the cost of inaccurate purity testing (over- or under-valuing jewellery) becomes more significant for both retailers and customers — strengthening the value proposition of an affordable, accurate testing solution for small and medium jewellery retailers.

## Tech Stack

- **Python**
- **pandas** — time-series data handling and grouping
- **matplotlib** — trend and seasonal visualization

## What I Learned

This project built my skills in time-series analysis and reinforced how quantitative market research can support and validate a product idea — connecting a hardware project to the real-world economic context it serves.
# gold-price-analysis-1