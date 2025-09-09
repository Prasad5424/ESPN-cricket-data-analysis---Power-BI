# ESPN-cricket-data-analysis---Power-BI

# Cricket Data Analysis: India ODI Team Performance

This project analyzes performances of the **India cricket team** across **Batting, Bowling, and Fielding** using **Power BI**.  
The data was sourced directly from [ESPN Cricinfo Stats](https://stats.espncricinfo.com/ci/engine/stats/index.html?class=2;type=batting).

---

## 📊 Dataset
- **Source:** ESPN Cricinfo Stats  
- **Team Analyzed:** India  
- **Data Includes:**
  - **Batting:** Matches, Innings, Runs, Average, Strike Rate, 100s/50s, Balls Faced, Fours, Sixes, Not Outs, Highest Score
  - **Bowling:** Matches, Overs, Wickets, Bowling Average, Economy, Strike Rate, Best Bowling
  - **Fielding:** Matches, Catches, Run-outs, Stumpings

---

## 🛠 Data Cleaning & Transformation
1. **Type Conversion & Null Handling**
   - Corrected data types for accurate analysis
   - Cleared null values for consistency

2. **Strike Rate Categorization (Batting)**
   - Created `Strike Rate Table`
   - Categories: `Explosive`, `Very Good`, `Good`, `Moderate`, `Low`, `Very Low`
   - Merged with batting dataset to assign strike rate categories

3. **Overall Summary Table**
   - Aggregated key metrics:
     - **Batting:** total runs, average, matches, highest score, not outs, balls faced, 4s, 6s
     - **Bowling:** total wickets, average, economy, strike rate
     - **Fielding:** total catches, run-outs, stumpings
   - Added **Slicers** in Power BI to dynamically filter data by player

4. **Power BI Visuals**
   - Interactive KPIs for top performers
   - Filters and slicers for dynamic exploration

---

## 🔍 Analysis Performed
- **Batting:** Top run-scorers, averages, strike rates, centuries, fifties, strike rate categories  
- **Bowling:** Top wicket-takers, averages, economy, strike rates, best performances  
- **Fielding:** Most catches, run-outs, stumpings, consistency comparison

---

## 💡 Key Insights
1. Top performers in batting, bowling, and fielding  
2. Strengths and weaknesses of India’s ODI team  
3. Strike rate analysis highlights batting aggression levels

---

## 🛠 Tools Used
- **Power BI Desktop** (Power Query + DAX)
- **M code** for automated data transformation
- **Interactive visuals & slicers** for dynamic analysis

