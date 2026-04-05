# Crypto Market Response to Geopolitical Conflict
## Iran — Israel — USA (2023–2026)

## Overview
An original data analysis project examining how Bitcoin and Ethereum 
prices responded to 9 key military and political escalation events 
between Iran, Israel, and the United States from October 2023 to 
February 2026.

**Tools:** Python, SQL, SQLite, Pandas, Matplotlib, yfinance  
**Data:** Real historical price data via Yahoo Finance API  
**Period:** October 2023 – April 2026

## Research Question
Do cryptocurrency markets react consistently to geopolitical shocks,
or does the nature, timing, and anticipation of conflict events
determine the magnitude of price movements?

## Events Analyzed
| Date | Event |
|------|-------|
| Oct 7, 2023 | Hamas attacks Israel — conflict begins |
| Apr 1, 2024 | Israel strikes Iranian consulate in Damascus |
| Apr 13, 2024 | Iran launches 300+ drones and missiles at Israel |
| Apr 19, 2024 | Israel retaliates — strikes near Isfahan |
| Jul 31, 2024 | Assassination of Haniyeh in Tehran |
| Oct 1, 2024 | Iran launches 180 ballistic missiles at Israel |
| Oct 26, 2024 | Israel's largest direct strike on Iran |
| Jun 13, 2025 | Twelve-Day War begins — Israel bombs Iran |
| Feb 28, 2026 | US-Israel launch major strikes on Iran |

## Key Findings
- **Unexpected events cause more volatility than anticipated ones** —
  the Haniyeh assassination (BTC -6.1%, ETH -10.2%) caused more damage
  than the entire Twelve-Day War
- **Market desensitization over time** — 7-day BTC volatility dropped
  from $7,575 in July 2024 to $3,037 by February 2026 despite
  escalating military intensity
- **ETH carries higher geopolitical beta than BTC** — ETH consistently
  showed larger percentage moves in both directions
- **Crypto normalized conflict risk by 2025–2026** — behaving more
  like a risk asset that prices in sustained tension rather than
  reacting to each new escalation

## Files
- `crypto_analysis.ipynb` — full analysis notebook with SQL queries and charts
- `crypto_geopolitical.db` — SQLite database with price and event data
