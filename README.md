# Steam Games — Market Analysis for Ubisoft
 ## Repository URL
 > 📎[https://github.com/Ibra-Ba/steam-videogames-analysis]

## Project Overview

Exploratory Data Analysis of the Steam games catalog conducted for Ubisoft,
aiming to understand the video game market and identify the key factors
that influence game popularity and sales.

**Tools:** PySpark · Databricks · Python  
**Dataset:** `s3://full-stack-bigdata-datasets/Big_Data/Project_Steam/steam_game_output.json`

---

## Notebooks

### Notebook 1 — Global Market Analysis
Covers macro-level analysis, genre analysis, and platform analysis.

> 📎 Databricks published URL: [https://dbc-dc9ab534-89e4.cloud.databricks.com/editor/notebooks/206812939310343?o=4359258060611116] 
### Notebook 2 — Popularity & Sales Factors
Identifies and quantifies the factors driving game popularity and estimated
sales using the Boxleiter method.

> 📎 Databricks published URL: [https://dbc-dc9ab534-89e4.cloud.databricks.com/editor/notebooks/2837560666121411?o=4359258060611116]



## Key Findings

### Market
- Steam catalog is dominated by a small number of prolific publishers
- Game releases peaked around 2018–2019 and stabilized through Covid
- Most paid games are priced between $5 and $20
- Discounts are a standard visibility strategy across the catalog

### Genres
- Action, Indie and RPG are the most represented genres
- Free to Play and Massively Multiplayer lead in median estimated sales
- RPG generates the highest median revenue among premium genres

### Platforms
- Windows covers nearly all games; Mac and Linux remain secondary
- Multi-platform games achieve median sales 3.8x higher than single-platform

### Popularity & Sales Drivers
| Factor | Key Insight |
|---|---|
| Genre | Strongest differentiator — RPG and MMO lead in revenue |
| Price | $30–60 sweet spot — 24x more median revenue than $10–20 |
| Platforms | 3 platforms → 3.8x more median sales than 1 platform |
| Languages | 6–10 languages is the optimal range for revenue reach |
| Release year | Older games accumulate more reviews; recent games score higher satisfaction |
| Age restriction | "Under 16" (AAA titles) dominates — age rating reflects game type, not potential |

---
