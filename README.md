# 🏏 Bangladesh Male Cricket Team's ODI Batting Analysis (2001-2020)

This project explores the batting performances of the Bangladesh male cricket team in One-Day Internationals (ODIs) from 2001 to 2020. Using Python for data cleaning, analysis, and visualization, the project highlights key player performances, team trends, and other insights.

---

## 📊 Dataset Overview

The dataset includes the following key columns:
- **player_name**: Name of the player.
- **innings_runs**: Runs scored in a single innings.
- **innings_minutes**: Time spent in the crease (in minutes).
- **innings_batted**: Indicates whether the player batted in the match.
- **balls_faced**: Number of balls faced in that particular innings.
- **fours**: Number of boundaries hit by the batsman.
- **sixes**: Number of sixes hit by the batsman.
- **strike_rate**: Player's strike rate in the innings.
- **innings_number**: Indicates the player batted in the first/second innings.
- **opposition**: The opposing team.
- **ground**: Venue where the match was played.
- **innings_date**: Date of the innings.
- **fifties**: Number of innings where the player scored 50–99 runs.
- **hundreds**: Number of innings where the player scored 100+ runs.

**Dataset Details**:
- The data covers matches from 2001 to 2020.
- Includes detailed player performance statistics, enabling in-depth analyses.

---

## 🚀 Objectives

1. Analyze batting performances based on runs, strike rates, balls faced, boundaries, and milestones.
2. Identify top-performing players and key contributors over the years.
3. Visualize trends in player performances.
4. Provide actionable insights for cricket analysts, fans, and strategists.

---

## 🛠️ Data Cleaning and Preparation

1. **Handling Missing Values**:
   - Replaced `NaN` (Not a Number) values with 0 using `numpy.nan_to_num()` for smooth analysis.
2. **Data Type Conversion**:
   - Used `pandas.to_numeric()` to convert object columns to numeric types, avoiding `ValueError: Could Not Convert String to Float`.
3. **Conditional Filtering**:
   - Selected rows based on specific conditions (e.g., innings batted, specific opposition teams).
4. **Data Aggregation**:
   - Utilized `groupby()` and `.sum()` methods to compute totals for performance metrics.

---

## 📈 Insights and Visualizations

### 1. **Top 12 Grounds with Most Matches Played**
Visualized the top grounds where Bangladesh played the most ODIs during this period.

![Top 12 Grounds](#) ![image](https://github.com/user-attachments/assets/095aa97e-0313-43df-a8e1-99f8a93ac1a3)

---

### 2. **Top 15 Run Scorers**
- Grouped data by `player_name` and summed `innings_runs` to identify the top 15 highest run-scorers during this period.
- Created a bar chart to display the results.

![Top 15 Run Scorers](#) ![image](https://github.com/user-attachments/assets/ade56641-83ca-4f2f-9a4a-815a34d40f2b)

---

### 3. **Histogram of Runs Scored**
- Plotted the distribution of runs scored by batsmen using a histogram.
- Provided insights into scoring patterns across matches.

![Runs Distribution](#) ![image](https://github.com/user-attachments/assets/345659ad-d153-4784-85df-ad9fca227a7a)

---

### 4. **Matches Played Against Each Opposition**
- Aggregated data to calculate the number of matches played against each team.
- Displayed results in a bar chart for better understanding.

![Matches Played Against Opposition](#) ![image](https://github.com/user-attachments/assets/2442edd3-bee3-4d4d-8607-2f9d57e57dc6)

---

### 5. **Batters Who Faced the Most Balls**
- Identified batters who faced the most balls and visualized the results in a bar chart.

![Most Balls Faced](#) ![image](https://github.com/user-attachments/assets/71b72faf-699c-4a1c-8452-d3b2b7257228)

---

### 6. **Top 15 Fastest Run Scorers**
- Calculated strike rates for batters with over 1,000 runs.
- Visualized the top 15 fastest run-scorers using a scatter plot.

![Top 15 Fastest Run Scorers](#) ![image](https://github.com/user-attachments/assets/07165f4e-9933-47f7-ab78-54ac00520c0c)
