# Digital Health Equity Index (Python + NLP + Tableau + World Bank Data)

![Python](https://img.shields.io/badge/Python-3.9-blue)
![NLP](https://img.shields.io/badge/NLP-VADER%20Sentiment-purple)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange)
![Data](https://img.shields.io/badge/Data-World%20Bank-green)

Multi-method analysis of digital health access inequality across 45 countries
using World Bank API data, NLP sentiment analysis, and interactive Tableau
visualisation — producing a composite Digital Health Equity Index.

## About
This project investigates whether digital access inequality translates into
measurable health outcome disparities at the population level. Using World Bank
indicators across 45 countries and NLP analysis of health app user reviews,
it constructs a composite Digital Health Equity Index and identifies which
countries are being left behind by the digital health revolution.

## Key Findings
- **Germany scores highest** on the equity index at **70.9/100**
- **Guatemala scores lowest** at **9.1/100** — a 61.8 point gap
- **17x sentiment gap** between high income and low income health app users
- **Literacy rate** is the strongest predictor of maternal mortality (r = -0.72)
- **Mobile access** strongly predicts health outcomes (r = -0.71)
- Being "upper middle income" does NOT guarantee digital health equity —
  Brazil, South Africa, and China all score under 30

## Interactive Dashboard
🔗 [View Live Tableau Dashboard](https://public.tableau.com/app/profile/dr.sadiya.banu./viz/Digital_Health_Equity_Dashboard)

## Charts
![Internet vs Maternal Mortality](chart1_internet_vs_maternal_mortality.png)
![GDP vs Maternal Mortality](chart2_gdp_vs_maternal_mortality.png)
![Correlation Heatmap](chart3_correlation_heatmap.png)
![Digital Divide](chart4_digital_divide_bars.png)
![Equity Index Rankings](chart5_equity_index_ranking.png)
![Sentiment & Word Cloud](chart6_sentiment_wordcloud.png)

## Methodology
**Layer 1 — Quantitative analysis**
World Bank API pull across 6 indicators for 180+ countries:
internet access, mobile subscriptions, GDP per capita, literacy rate,
health expenditure, and maternal mortality.

**Layer 2 — NLP sentiment analysis**
VADER sentiment scoring of health app reviews by country income group —
revealing real barriers in low income user language: "need offline mode",
"too expensive", "2G network", "storage full".

**Layer 3 — Composite index**
Weighted composite score (0–100) combining all indicators via
MinMaxScaler normalisation across 5 components.

## Public Health Implications
- Digital health tools are inaccessible to the populations who need them most
- Offline functionality and 2G compatibility are critical design requirements
- Literacy programmes may be the highest-leverage intervention for health equity
- Income classification alone is insufficient — targeted country-level strategies needed

## Dataset
- World Bank Open Data API — 6 indicators, 2018–2022
- 45 countries scored, 180+ countries in raw dataset
- Income groups: High, Upper middle, Lower middle, Low income

## Tools Used
- **Python 3.9** — pandas, wbgapi, matplotlib, seaborn, scikit-learn
- **NLP** — VADER sentiment analysis, WordCloud, NLTK
- **Tableau Public** — interactive world map dashboard
- **Data source** — World Bank Open Data (api.worldbank.org)

## Files
| File | Description |
|------|-------------|
| `Digital_Health_Equity_Analysis.ipynb` | Full Python + NLP analysis notebook |
| `wb_health_equity.csv` | Raw World Bank dataset (180+ countries) |
| `digital_health_equity_index.csv` | Composite index scores by country |
| `sentiment_results.csv` | App review sentiment analysis results |
| `chart1_internet_vs_maternal_mortality.png` | Internet access vs maternal mortality |
| `chart2_gdp_vs_maternal_mortality.png` | GDP vs maternal mortality bubble chart |
| `chart3_correlation_heatmap.png` | Correlation matrix heatmap |
| `chart4_digital_divide_bars.png` | Digital divide by income group |
| `chart5_equity_index_ranking.png` | Country equity index rankings |
| `chart6_sentiment_wordcloud.png` | Sentiment scores + barrier word cloud |

## Author
**Dr. Sadiya Banu**
Public Health Researcher | MPH, Anglia Ruskin University
🔗 [LinkedIn](https://linkedin.com/in/dr-sadiyabanu)
🔗 [Tableau Profile](https://public.tableau.com/app/profile/dr.sadiya.banu.)

## License
Open source under the [MIT License](LICENSE).
Data sourced from World Bank Open Data — publicly available at data.worldbank.org.
