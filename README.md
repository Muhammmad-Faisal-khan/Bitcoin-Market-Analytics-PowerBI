# Bitcoin Market Analytics Dashboard (Power BI)
### 📌 Project Overview

This project is an end-to-end Bitcoin market analytics solution built using Power BI, leveraging live cryptocurrency data from the CoinGecko API.
It combines Business Intelligence (BI), Data Analysis, and basic AI-driven insights to help understand Bitcoin price behavior, market risk, and trading activity.

## The dashboard is designed for:
* Data analysts
* BI developers
* Crypto market observers

Recruiters evaluating real-world analytics skills

## 📊 Objectives

* Analyze historical Bitcoin price trends
* Monitor market capitalization and trading volume
* Identify volatility and risk patterns
* Apply moving averages and KPIs for decision support
* Present insights through a clean, executive-level dashboard

## 🌐 Data Source

* API: CoinGecko Public API

* Endpoint Used:
https://api.coingecko.com/api/v3/coins/bitcoin/market_chart
Currency: USD
Duration: Last 365 days

## Data Includes:
* Bitcoin Prices
* Market Capitalization
* Total Trading Volume
* Timestamps (Unix Epoch)

## 🛠 Tools & Technologies

* Power BI Desktop
* Power Query (M Language) – Data transformation
* DAX – Measures & KPIs
* REST API Integration
* GitHub – Version control & portfolio hosting

## 🧱 Data Engineering Process

* Fetched live data from CoinGecko API
* Flattened nested lists (prices, market_caps, total_volumes)
* Converted Unix timestamps to Date format
* Cleaned null and misaligned values
* Created a unified analytical table
* Built DAX measures for KPIs and moving averages

## 📈 Dashboard Pages
### Page 1 — Bitcoin Price Forecast & Risk Analysis

Focuses on price behavior and volatility:
* Bitcoin price trend (USD)
* 7-day moving average
* Daily returns
* Volatility distribution
* Risk insights for short-term traders

## Page 2 — Executive Snapshot & Market KPIs
### Provides a high-level business view:
* Current price KPI
* Market capitalization KPI
* Total trading volume KPI
* Price vs volume comparison
* Date slicers for interactive analysis

## 🔍 Key Insights
* Bitcoin shows high volatility with sharp short-term movements
* Trading volume spikes often precede major price changes
* Moving averages help smooth noise and identify trend direction
* Market cap remains relatively stable compared to price swings

## Skills Demonstrated
* API-based data ingestion
* Data cleaning & transformation
* BI dashboard design
* Analytical storytelling
* KPI and metric design
* GitHub project documentation
