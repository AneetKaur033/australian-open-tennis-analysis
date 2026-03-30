#  120 Years of Australian Open Tennis — Data Visualisation

A visual analytics report on 120 years of Australian Open tennis history,
built in Tableau using historical match data covering champions, nationalities,
match durations, set scores, and performance metrics.

---

## Project Summary

The Australian Open has run since 1905. This project analyses trends across the
full tournament history - from national dominance shifts to individual player
performance - with a focus on players who have won 5 or more titles.

**Key questions explored:**
- Which countries have dominated, and how has that changed over time?
- How do top players (5+ wins) compare on win rate and games played?
- What performance differences exist between men's and women's champions?
- Who are the all-time outliers in consistency and dominance?

---

## Visualisations

### Geographic Map — Champion Countries Before & After 1970
Before 1970, Australia dominated with 37 titles. After 1970, the US led with
18 titles, and countries like Switzerland, Spain, and Serbia entered the picture.

---

### Treemap — Champions by Country & Gender
Australia leads in both men's and women's categories. Rectangle size = number
of titles. Colour = country.

---

### Scatter Plot — Games Played vs Win Rate by Gender
Most champions cluster at 40–80 games played with a 55–70% win rate.
Outliers (150+ games, high win rates) are long-term dominant champions.
Men appear further right due to best-of-five format.

---

### Parallel Coordinates — Performance Metrics (2000–2025)
Novak Djokovic stands out with 376 games played and an 88.9% win rate.
Most other champions cluster much lower, highlighting his exceptional dominance.

---

### Top Players — Win Rate Bar Chart (5+ titles)
\Margaret Court leads with 11 titles and ~67.5% win rate. Others include
Serena Williams, Novak Djokovic, Roger Federer, Roy Emerson, Nancye Wynne
Bolton, and Daphne Akhurst.

---

### Top Players — Treemap

---

## Tools & Techniques

| Tool | Purpose |
|------|---------|
| Tableau Desktop | All visualisations |
| Microsoft Excel | Data storage, calculated fields |
| Tableau Calculated Fields | Game Win Rate, Championships Won, Time Period split |

**Chart types used:** Treemap, Parallel Coordinates, Geographic Map, Scatter Plot, Bar Chart

---

##  Files in This Repo

| File | Description |
|------|-------------|
| `Australian_Open_Analysis_Report.pdf` | Full written report |
| `AneetKaur_25038579_A2.xlsx` | Dataset with calculated columns |
| `AneetKaur_25038579_A2.twbx` | Packaged Tableau workbook (open with Tableau Desktop) |
| `*.png` | Exported visualisation screenshots |

---

## Key Findings

- **Australia dominated pre-1970**, winning 37 titles. Post-1970, the sport globalised rapidly.
- **Novak Djokovic** is the biggest outlier in the parallel coordinates chart - 376 games played, 88.9% win rate.
- **Margaret Court** holds the most titles (11) with a ~67.5% win rate.
- **Men play more games per match** (best-of-five vs best-of-three), producing a systematic gender difference in total games played.
- Most champions win only once — the top 7 players with 5+ titles are a clear elite tier.
