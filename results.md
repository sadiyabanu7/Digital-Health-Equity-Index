# Analysis Results — Digital Health Equity Index

## Dataset Summary
| Parameter | Value |
|-----------|-------|
| Raw countries (World Bank API) | 180+ |
| Countries scored in index | 45 |
| Indicators used | 6 |
| Data years | 2018–2022 |
| NLP reviews analysed | 40 |
| Income groups | 4 |

---

## Digital Health Equity Index — Full Rankings

| Rank | Country | Income Group | Equity Score |
|------|---------|--------------|-------------|
| 1 | Germany | High income | 70.9 |
| 2 | Iceland | High income | 70.8 |
| 3 | Switzerland | High income | 70.5 |
| 4 | United Arab Emirates | High income | 68.5 |
| 5 | Netherlands | High income | 67.3 |
| 6 | Ireland | High income | 66.8 |
| 7 | Denmark | High income | 66.4 |
| 8 | Luxembourg | High income | 65.5 |
| 9 | Slovenia | High income | 65.1 |
| 10 | Sweden | High income | 64.8 |
| 11 | Poland | High income | 64.6 |
| 12 | France | High income | 63.1 |
| 13 | Kuwait | High income | 62.9 |
| 14 | United Kingdom | High income | 62.4 |
| 15 | Czechia | High income | 61.5 |
| … | … | … | … |
| 41 | Brazil | Upper middle income | 24.3 |
| 42 | Azerbaijan | Upper middle income | 24.4 |
| 43 | Colombia | Upper middle income | 24.8 |
| 44 | Cabo Verde | Upper middle income | 17.0 |
| 45 | Guatemala | Upper middle income | 9.1 |

---

## Correlation Matrix — Key Results

| Indicator A | Indicator B | Correlation (r) | Interpretation |
|-------------|-------------|-----------------|----------------|
| Literacy rate | Maternal mortality | -0.72 | Strong negative — higher literacy = lower mortality |
| Mobile per 100 | Maternal mortality | -0.71 | Strong negative — mobile access predicts survival |
| Internet access | Maternal mortality | -0.71 | Strong negative — digital access = better outcomes |
| Literacy rate | Mobile per 100 | +0.84 | Strong positive — literacy enables mobile use |
| Health expenditure | Internet access | -0.89 | High spend countries invest less % GDP on health |
| GDP per capita | Literacy rate | +0.57 | Moderate positive — wealth enables education |

---

## NLP Sentiment Analysis Results

| Income Group | Mean Sentiment Score | Interpretation |
|-------------|---------------------|----------------|
| High income | 0.580 | Strongly positive |
| Upper middle income | 0.280 | Moderately positive |
| Lower middle income | 0.074 | Near neutral |
| Low income | 0.034 | Near neutral / negative |

**Sentiment gap: 17.2x between high income and low income users**

### Top barrier themes in low & lower middle income reviews
| Theme | Example phrases |
|-------|----------------|
| Connectivity | "doesn't work on 2G", "need offline mode", "slow internet" |
| Cost | "too expensive", "can't afford data", "heavy data usage" |
| Device | "storage full", "crashes on old phone", "basic smartphone" |
| Language | "not in my language", "hard to understand", "local language" |
| Complexity | "too complicated", "need simpler interface", "technical knowledge" |

---

## Key Findings Summary

### Finding 1 — The equity gap is 61.8 points
Germany (70.9) vs Guatemala (9.1). Being classified as "upper middle
income" offers no guarantee of digital health equity — Brazil (24.3),
South Africa (19.3), and China (27.7) all score below 30.

### Finding 2 — Literacy is the strongest lever
Correlation of -0.72 between literacy rate and maternal mortality
is stronger than GDP (-0.43) or health expenditure (-0.15).
Literacy programmes may be the highest-leverage public health
intervention at the population level.

### Finding 3 — The sentiment gap reveals hidden inequality
A 17x gap in health app satisfaction between high and low income
users reflects real barriers: connectivity, cost, device limitations,
and language. Digital health tools are designed for the already-connected.

### Finding 4 — Mobile access is a health outcome predictor
Mobile subscriptions per 100 people correlates at -0.71 with maternal
mortality — stronger than GDP per capita (-0.43). Mobile-first health
interventions may deliver outsized impact in LMICs.

---

## Policy Recommendations

1. **Offline-first design** — health apps must function without internet
2. **2G compatibility** — minimum viable connectivity standard for LMICs
3. **Multilingual interfaces** — language barriers exclude high-burden populations
4. **Lightweight apps** — storage and data constraints are real barriers
5. **Literacy-linked interventions** — digital health must be paired with
   health literacy programmes to be effective

---

*Analysis conducted by Dr. Sadiya Banu | Data: World Bank Open Data 2018–2022*
