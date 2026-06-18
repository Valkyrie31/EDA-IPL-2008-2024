# IPL Player Performance & Team Strategy Analysis

An exploratory data analysis of IPL matches from 2008 to 2024, using Python to uncover team strategy patterns, batting trends, bowling effectiveness, and venue characteristics.

## Dataset

**IPL Complete Dataset (2008–2024)**  
Source: [Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

Two files used:
- `matches.csv` — match-level data (teams, toss, venue, result)
- `deliveries.csv` — ball-by-ball data (batsman, bowler, runs, extras)

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core analysis |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis environment |

## Key Findings

### 1. Toss Advantage — Field First to Win
### 2. Run Rate Has Been Rising — With One Exception
### 3. Death Over Bowling — Accuracy Beats Pace
### 4. Venue Analysis — Know Where You're Playing
### 5. Most Complete Batsmen — The Elite Quadrant

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


