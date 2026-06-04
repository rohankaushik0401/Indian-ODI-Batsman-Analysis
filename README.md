# 🏏Indian ODI Batsman Performance Analytics Dashboard

## 📌 Project Overview

This project is an interactive Power BI dashboard developed to analyze and compare the performance of Indian cricket players across multiple innings. The dashboard focuses on batting performance, consistency, scoring patterns, and match-winning contributions using statistical and visual analytics.

The analysis covers players such as Virat Kohli, Rohit Sharma, KL Rahul, Rishabh Pant, and Suryakumar Yadav, providing insights into their form, strike rates, scoring consistency, and performance under different match conditions.

The dataset and analysis used in this project are strictly for study purposes and no where are mentioned to be accurate or official

---

## 🎯 Objectives

- Analyze player performance across innings.
- Compare batting consistency among players.
- Identify high-impact players through statistical metrics.
- Evaluate scoring trends and batting styles.
- Visualize player form and milestone achievements.
- Generate actionable insights using data-driven analysis.

---

## 🛠️ Tools & Technologies

- Power BI
- Microsoft Excel
- DAX (Data Analysis Expressions)
- Power Query
- Data Visualization Techniques

---

## 📊 Dashboard Features

### 1. Player Overview
- Total Runs
- Batting Average
- Strike Rate
- Highest Score
- Total Innings

### 2. Milestone Analysis
- Half Centuries (50+ Scores)
- Centuries (100+ Scores)
- Conversion Rate (50s to 100s)

### 3. Performance Trend Analysis
- Runs scored across innings
- Player form tracking
- Identification of slumps and peak performances

### 4. Comparative Analysis
- Average vs Strike Rate
- Player-to-player comparisons
- Scoring consistency analysis

### 5. Advanced Analytics
- Cluster Analysis of batting styles
- Variance and consistency evaluation
- Performance distribution

### 6. Interactive Filtering
- Player Selection
- Match Conditions
- Opponent Analysis
- Dynamic KPI Updates

---

## 📈 Key Metrics Calculated

### Batting Average

Average Runs = Total Runs / Number of Innings

### Strike Rate

Strike Rate = (Runs Scored / Balls Faced) × 100

### Half Century Count

50 ≤ Runs < 100

### Century Count

Runs ≥ 100

### Win Percentage

Win % = (Matches Won / Total Matches) × 100

---

## 🔍 Key Insights

## 📊 Summary Dashboard Matrix

| Player | Role Cluster | Consistency Index | Strike Rate | Conversion Rate | Key Context / Entry Time |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **Virat Kohli** | Statistical Outlier | **1.98** (1st) | Sub-100 | High | Context-independent / Chasing master |
| **KL Rahul** | Anchor | **1.90** (2nd) | Sub-100 | ~55% | Over 15 / Middle-overs crunch |
| **Rohit Sharma** | Volume Opener | 1.66 | Sub-100 | ~62% | Over 1–2 / Highest median score (63) |
| **Shubman Gill** | Accumulator | High | Low-to-mid 90s | ~62% | Top-order volume / Stable form |
| **Rishabh Pant** | Wildcard / Ceiling | 1.43 | Variable | ~55% | High upside against AUS/ENG |
| **Ravindra Jadeja** | Late Accumulator | 1.42 | 100+ | — | Over 35+ / High consistency for a finisher |
| **Hardik Pandya** | Finisher / Big Hitter | 1.34 | ~108 | ~28% | Over 30+ / More effective in chases |
| **Suryakumar Yadav**| Big Hitter | 1.28 | **~116** (1st) | ~67% | Over 20–25 / High volatility profile |

---

## 👤 Individual Player Profiles

### 🏏 Virat Kohli — The Statistical Outlier at the Top
* Kohli is the only player in this dataset who simultaneously leads on **batting average (68.9)**, **consistency index (1.98)**, and average score across both batting situations.
* His consistency index of **1.98** — the highest in the group — means he is nearly twice as consistent as the dataset's lower-ranked players.
* The batting-first vs chasing bar chart reinforces this: his average barely drops between the two situations, which is the hallmark of a player whose output is not context-dependent.
* The regression model further validates this — his predicted scores against Australia and England are among the highest projected figures in the entire panel.

### ⚓ KL Rahul — The Anchor the Numbers Keep Returning To
* Rahul's consistency index of **1.90** (second only to Kohli) combined with the **lowest standard deviation (30.5)** among top-order batters makes him the most statistically reliable batter in the squad from a team-building standpoint.
* His conversion rate sits at approximately **55%** — solid, not elite — but his average balls faced (skewing toward the higher end of the 32–68 range on the dashboard) tells you he's earning those runs, not manufacturing them quickly.
* Critically, his average in the last 5 innings closely tracks his overall career average, suggesting no meaningful form deterioration.
* The entry time chart shows him coming in around **over 15**, meaning he regularly faces the middle-overs crunch — and the numbers suggest he handles it better than anyone else in this group.

### 👑 Rohit Sharma — Volume, Conversion, and Situation Mastery
* Rohit's **median score of 63** is the highest in the dataset among 50+ innings batters, but the dashboard adds important texture to that.
* His conversion of starts (approximately **62%**) is the third-highest in the group, and he consistently faces more balls than the lower-order players — suggesting his runs are built on extended innings rather than explosive bursts.
* His chasing average, visible in the batting situation chart, is notably competitive with his batting-first average, which aligns with his historical record as one of the best ODI chasers.
* He enters the batting order earliest in the group (**over 1–2 consistently**), meaning his numbers are built against fresh bowling — context that makes his consistency index of **1.66** even more meaningful.

### ⚡ Suryakumar Yadav — The Volatility Profile in Full
* SKY's position on the player categorisation scatter plot says everything: he sits in the top-left quadrant — **high strike rate (~116)**, average score in the 50–55 range — placing him squarely in the "Big Hitter" cluster.
* His conversion rate of approximately **67%** is the highest in the dataset, which at first appears contradictory for a volatile batter.
* The explanation lies in his role: he enters late (**around over 20–25** per the entry time chart), meaning most of his "starts" are already in accelerated phases where conversion to a larger score is structurally harder.
* The form trend line in the form analysis chart shows the widest amplitude swings of any top-six batter — peaks are sharp, troughs are deep, with limited middle ground.
* His average in the last 5 innings trails his career average slightly, flagging a possible current-form dip worth monitoring.

### 📈 Shubman Gill — The Quiet Accumulator with Upside
* Gill sits in the "Accumulator" cluster on the scatter plot — average score close to 60, moderate strike rate in the low-to-mid 90s.
* His last-5-innings average tracks very closely to his career average, making him one of the more in-form batters in the current dataset window.
* His contribution slice in the pie chart is the largest or second-largest in the group, reflecting high innings volume at consistent output.
* Conversion rate sits around **62%**, and his balls-faced profile (leaning toward the 68-ball end of the scale) confirms he builds innings the long way.
* He's the prototypical top-order accumulator — not the most explosive figure on any single metric, but reliable across all of them.

### 🃏 Rishabh Pant — The High Ceiling, High Score Wildcard
* Pant's consistency index of **1.43** places him in the middle of the group — not a concern in isolation, but the regression analysis panel is where his profile gets interesting.
* His predicted scores against Australia and England (batting first) are among the highest projected in the four-player regression panel, suggesting the model reads his upside as genuinely elite in favourable conditions.
* His conversion rate (**~55%**) and average balls faced (moderate) indicate a player who can shift gears — but the form trend chart shows pronounced volatility.
* The gap between his last-5-innings average and career average is one of the wider ones in the group, pointing to either a current form trough or a role-change impact worth investigating.

### 🚀 Hardik Pandya — Entry Time Defines Everything
* Pandya's numbers need to be read through the lens of his entry point: the entry time chart places him at **over 30+**, the second-latest entry in the group after Jadeja.
* Every metric — average score, conversion rate (**~28%**, the lowest in the dataset), consistency index (**1.34**) — has to be contextualised against the fact that he regularly faces 10 or fewer overs.
* His position on the scatter plot (Big Hitter cluster, **high strike rate ~108**, lower average score ~45) is not underperformance — it's a role-specific profile.
* The more relevant metric for a finisher is runs per ball, and his strike rate is the second-highest in the group.
* His regression predictions show the widest batting-first vs chasing gap of the players shown, suggesting he performs more effectively under chase conditions — a useful team-selection data point.

### 🪵 Ravindra Jadeja — The Late-Entry Accumulator Anomaly
* Jadeja enters latest of any player in the dataset (**over 35+**), yet his consistency index of **1.42** ranks fifth overall — which is genuinely impressive for a batter operating in the final five overs.
* His average score in the last 5 innings chart is the lowest in the group, but the career-to-recent comparison gap is relatively small, suggesting stable role-specific output rather than form decline.
* His runs-by-over chart shows activity concentrated in **overs 35–45**, confirming his late-innings cameo profile.
* The key analytical point: he's not being asked to build innings — he's being asked to add 25–40 runs at a **100+ strike rate**, and the consistency index says he delivers that reliably.

---

## 📈 Cross-Cutting Insights & Patterns

### The Consistency Index vs Strike Rate Trade-Off
The consistency index chart, ordered from **1.98 (Kohli)** to **1.28 (SKY)**, directly mirrors the inverse of the strike rate chart. 

* **The Rule:** Without exception, every player with a strike rate above 100 ranks in the bottom half of the consistency index. Every player with a strike rate below 100 ranks in the top half.
* **Analytical Takeaway:** This is not a coincidence — it is a structural relationship between intent and stability. The dataset quantifies what analysts have long argued qualitatively: aggressive batting profiles generate higher peaks but wider score distributions, while tempo-controlled batting compresses variance at the cost of ceiling. India's current lineup contains both profiles, which is by design — but the data suggests the team's floor is disproportionately dependent on Kohli and Rahul remaining in form simultaneously.

### Form Watch — Last 5 Innings vs Career Average Delta
The most actionable insight from the "average in last 5 innings" chart is the convergence between recent and career averages:

* **Stable Form:** Kohli, KL Rahul, Shubman Gill, and Suryakumar Yadav all show tight deltas, indicating stable current form.
* **Minor Warning:** Rohit Sharma shows a marginal recent dip relative to his career average.
* **Critical Flag:** Rishabh Pant shows the **largest negative delta** in the group — his last 5 innings average sits notably below his career figure, which warrants monitoring ahead of high-stakes selections.


---

## 📂 Dataset Information

The dataset contains player-wise batting records including:

- Player Name
- Innings Number
- Runs Scored
- Balls Faced
- Strike Rate
- Match Result
- Opponent

## Dashboard Preview

<img width="1353" height="730" alt="Screenshot 2026-05-23 114036" src="https://github.com/user-attachments/assets/09e41688-d429-41aa-bb97-cb69eb3d40f9" />

<img width="1348" height="741" alt="Screenshot 2026-05-23 114111" src="https://github.com/user-attachments/assets/d43cdac9-52c4-4d24-832b-94e1758fa6a4" />

<img width="1301" height="725" alt="Screenshot 2026-05-23 114127" src="https://github.com/user-attachments/assets/816285c2-6dae-474e-9464-b6272a65c548" />

<img width="1291" height="732" alt="Screenshot 2026-05-23 114220" src="https://github.com/user-attachments/assets/5a59d3dd-9730-4cd7-a24f-53c80f0d9acf" />

