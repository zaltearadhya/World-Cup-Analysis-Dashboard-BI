# World-Cup-Analysis-Dashboard-BI

# 🏏 T20 World Cup 2022 Analysis – Power BI Dashboard

## 1. Problem Statement

The T20 World Cup 2022 generated a massive amount of match, batting, and bowling data. However, raw scorecards and tables make it difficult to quickly understand tournament trends, team dominance, player impact, and performance patterns.

The goal of this project is to convert raw cricket data into an **interactive Power BI dashboard** that provides clear insights into:

* Tournament overview
* Batting performance
* Bowling performance
* Team-wise and match-wise trends



## 2. Objectives

* To analyze **overall tournament performance** using key KPIs
* To evaluate **batting performance of players and teams**
* To analyze **bowling impact using wickets and dot balls**
* To identify **top-performing teams and players**
* To build an **interactive dashboard** with filters and match-level drilldowns
* To support **data-driven cricket analysis and storytelling**



## 3. Data Overview (from provided Power BI file & dataset)

The dataset used in this project is sourced from the **T20 World Cup 2022 match data** and includes ball-by-ball and match-level information.

### Main data fields include:

* Match details (Match name, teams)
* Player name (batsman, bowler)
* Runs scored
* Balls faced
* Fours and sixes
* Boundary runs
* Wickets
* Dot balls
* Match day / match number

This dataset enables **detailed performance analysis across players, teams, and matches**.



## 4. Data Preparation and Calculation

* Removed unnecessary columns and handled missing values
* Standardized team and player names
* Created calculated measures using **DAX**, such as:

  * Total Runs
  * Total Wickets
  * Average Strike Rate
  * Sum of Fours and Sixes
  * Boundary Runs
  * Total Balls Bowled
  * Dot Ball Count
* Built relationships between match, batting, and bowling tables
* Designed separate logic for **overview, batting, and bowling pages**



## 5. Dashboard Structure and KPIs

### 🔹 Pages in Dashboard

1. **Overview Page**

   * Total Runs
   * Total Wickets
   * Average Strike Rate
   * Match Count by Winner
   * Total Runs by Day (trend)

2. **Batting Performance Page**

   * Player-wise runs, balls, fours, sixes, boundary runs
   * Interactive player tables
   * Strike rate vs total runs scatter chart
   * Team filters and match timeline

3. **Bowling Performance Page**

   * Total wickets vs target wickets KPI
   * Total balls and wickets by team
   * Bowler-wise wickets with dot balls
   * Match-level slicers

### 🔹 Key KPIs

* 🏏 Total Runs: 11,056+
* 🎯 Total Wickets: 511
* ⚡ Average Strike Rate: ~96
* 🧢 Team-wise balls and wickets
* 🔍 Player-wise batting & bowling metrics



## 6. Observations and Key Insights

* The tournament shows **high fluctuation in daily total runs**, indicating varying pitch and match conditions
* Some teams consistently bowled **more dot balls**, contributing to higher wicket-taking pressure
* A few batsmen clearly dominate in terms of **boundary contribution and strike rate**
* Certain matches produced **exceptionally high run totals**, highlighting batting-friendly games
* Bowling analysis shows that **wickets are strongly correlated with dot ball pressure**



## 7. Business (Cricket) Recommendations

* Teams should prioritize bowlers with **high dot ball + wicket efficiency**
* Batting order optimization can be done using **strike rate vs total runs analysis**
* Match strategies can be improved by studying **team-wise bowling workloads**
* Player selection should focus not only on runs but also on **boundary impact and consistency**
* Future tournaments can use similar dashboards for **real-time performance monitoring**



## 8. Tools and Techniques

* **Power BI Desktop**
* **Power Query** for data cleaning
* **DAX** for calculated measures and KPIs
* **Data modeling** (relationships between tables)
* **Interactive visuals**:

  * KPI cards
  * Pie charts
  * Line charts
  * Scatter plots
  * Tables and slicers



## 9. Future Enhancement

* Add **player comparison pages**
* Include **venue-wise and pitch-wise analysis**
* Implement **win prediction or performance forecasting models**
* Add **powerplay, death over, and middle over analysis**
* Build a **live API-connected dashboard** for real-time tournaments



## 10. Conclusion

This project demonstrates how **Power BI can transform raw cricket data into meaningful insights**. The T20 World Cup 2022 dashboard provides a complete analytical view of the tournament, covering overview metrics, batting excellence, and bowling impact. It highlights how data visualization can support **strategic decision-making, performance evaluation, and sports analytics storytelling**.
