# IPL Player Performance & Team Strategy Analysis

An exploratory data analysis of IPL matches from 2008 to 2024, using Python to uncover team strategy patterns, batting trends, bowling effectiveness, and venue characteristics.

---

## Business Questions

1. Does winning the toss give a competitive advantage?
2. How has the average match run rate evolved across IPL seasons?
3. Which bowlers are most economical in death overs (16–20)?
4. Which venues favor batsmen vs bowlers?
5. Who are the most complete batsmen in IPL history — consistency vs strike rate?

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core analysis |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis environment |

---

## Dataset

**IPL Complete Dataset (2008–2024)**  
Source: [Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

Two files used:
- `matches.csv` — match-level data (teams, toss, venue, result)
- `deliveries.csv` — ball-by-ball data (batsman, bowler, runs, extras)

---

## Key Findings

### 1. Toss Advantage — Field First to Win
Teams that won the toss and chose to **field first** won more than 50% of their matches, while teams that chose to **bat first** after winning the toss won less than 45% of the time. This suggests that in modern T20 cricket, chasing is a strategically superior approach, and captains who read conditions correctly gain a meaningful edge.

### 2. Run Rate Has Been Rising — With One Exception
The average IPL run rate has climbed steadily from **7.9 in 2008 to 9.08 in 2024**, reflecting the aggressive evolution of T20 batting over 16 seasons. The only notable dip was in **2020–2021 (8.1 → 7.7)**, when matches were played in the UAE due to COVID-19. Different pitch conditions in Dubai, Abu Dhabi, and Sharjah slowed scoring, before the tournament returned to India and run rates resumed their upward trend.

### 3. Death Over Bowling — Accuracy Beats Pace
**DE Bollinger** was the most economical death-over bowler (economy rate: **7.36**), followed by **SP Narine (7.40)** and **SL Malinga (7.80)**. The presence of both pacers and spinners in the top rankings indicates that death-over success is less about raw pace and more about **accuracy, variations, and control** under pressure.

### 4. Venue Analysis — Know Where You're Playing
The overall average first-innings score across all IPL venues is **166 runs**. Venues consistently below this average are **bowling-friendly** — teams winning the toss here should prioritize fielding first. Venues above 166 are **batting-friendly** — posting a big total becomes the preferred strategy. This analysis provides a data-backed foundation for toss decisions based on ground conditions.

### 5. Most Complete Batsmen — The Elite Quadrant
**David Warner, Chris Gayle, Jos Buttler, AB de Villiers, and Faf du Plessis** emerge as the most complete batters, combining high strike rates with strong per-innings averages. Two players stand out individually:
- **Virat Kohli** — all-time highest run scorer (8,014 runs), strike rate of 128.5, average of 32.8 — the benchmark for consistency across all seasons.
- **KL Rahul** — highest average per innings (38.4), making him the most reliable run-scorer relative to opportunities.

---

## Visualizations

### Toss Advantage
![Toss Advantage](Winning%20Toss.png)

### Run Rate Trend Across Seasons
![Run Rate Trend](Average%20Run%20Rate.png)

### Most Economical Death Over Bowlers
![Death Over Bowlers](Economical%20Bowlers.png)

### Venue Analysis
![Venue Analysis](Average%20First%20Innings%20Score.png)

### Batsman Strike Rate vs Consistency
![Batsman Scatter](Top%2020%20IPL%20Batsmen.png)

### Impact Player Score
![Impact Player Score](Impact%20Player%20Score.png)

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Valkyrie31/ipl-eda-analysis.git
cd ipl-eda-analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Download the dataset from Kaggle and place matches.csv
#    and deliveries.csv in the project folder

# 4. Launch the notebook
jupyter notebook IPL_EDA_Starter.ipynb


