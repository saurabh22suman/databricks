The dataset is provided by Kaggle. Read more about the dataset and download necessary files from below link.
https://www.kaggle.com/datasets/tanishqjoshi16/ipl-2025-data-set/

I’ll provide you **20 well-crafted, tricky scenario-based questions** on this **IPL 2025 dataset** designed to test beginners to advanced users on *real-world data engineering and analysis with PySpark*. These touch upon **DataFrames, Joins, Aggregations, Window Functions, Complex Grouping, Broadcast joins, Optimization, UDFs, MLlib**, and more.

Here’s the full set:

---

## 🏏 **20 Scenario-Based PySpark Questions on IPL 2025 Dataset**

### 🔰 **Beginner to Intermediate (Data Exploration, Aggregations)**

1. **Basic Aggregation**

   > Find the **top 3 batsmen with the highest strike rate** in the 2025 season, having faced at least 100 balls.

2. **GroupBy & Aggregation**

   > Which **venue** hosted the **highest average first-innings score** in the 2025 season?

3. **Joins & Filtering**

   > Using `matches.csv` and `deliveries.csv`, **list all matches** where a player scored **a century (>=100 runs) in a single match**.

4. **Distinct & Count**

   > Count the **number of unique players** who have either won the “Player of the Match” award or featured in the **orange\_cap.csv** list.

5. **Window Functions (Ranking)**

   > For each bowler, calculate their **best bowling figure in a single match** *(most wickets, if tie -> least runs conceded)* using window functions.

6. **Handling Missing Data**

   > Some venues or player names might be missing or inconsistent. Write a query to **identify missing or null entries** across all four datasets.

7. **Multiple Aggregations**

   > For each **team**, calculate **total wins**, **total losses**, and **net run rate (NRR)** for the IPL 2025 season.

---

### ⚙️ **Intermediate to Advanced (Complex Queries, Optimization)**

8. **Exploding Data for Partnerships**

   > Generate a dataset showing the **total runs scored by every unique batting pair (partnership) per match**.

9. **Cumulative Sums**

   > Track **cumulative runs scored** by each batsman **over the tournament**, ordered by date and match\_no.

10. **Rolling Window - Form Tracking**

> For each batsman, compute their **average runs in the last 3 innings** throughout the tournament.

11. **Broadcast Joins**

> Broadcast the `orange_cap.csv` and **join** it with `deliveries.csv` to list how often **orange cap players got out in powerplay overs**.

12. **UDFs & Custom Logic**

> Create a **UDF** that tags every innings with one of: `'Slow Start'`, `'Explosive Start'`, `'Balanced'`—based on **runs scored in powerplay (0-6 overs)**.

13. **Multi-Level Aggregation**

> List bowlers who have an **economy rate below the season average economy rate**, but have **taken at least 15 wickets**.

14. **Joins + Anti-Join**

> Find all players who feature in `purple_cap.csv` **but did not bowl a single ball in the final 3 matches of the tournament**.

15. **Multiple Datasets Joins**

> Find the **correlation** between players who are in both the **orange\_cap** and **purple\_cap** lists (i.e., true all-rounders), and compute their contribution to wins.

---

### 🧩 **Advanced (Optimization, Real-World Scenarios, MLlib)**

16. **Sessionization Concept (Advanced Window Functions)**

> For every team, identify **consecutive matches won** (winning streaks) and determine the **longest winning streak** for any team in IPL 2025.

17. **Map Groups / FlatMap Groups**

> Create **inning-wise summaries**: For each innings of each match, output *runs scored*, *wickets lost*, *boundaries hit*, and *extras conceded* in a **single row**.

18. **Time-Series Analysis**

> Using match dates, find whether **teams winning toss** in matches held on **weekends (Saturday/Sunday)** have a higher win % compared to weekdays.

19. **Outlier Detection**

> Using the **total match runs distribution**, identify **matches that were statistical outliers** (using z-score or IQR method) in terms of total runs scored.

20. **MLlib Integration - Predictive Analytics**

> Use PySpark’s MLlib to build a **logistic regression model** predicting whether the **toss-winning team** will **win the match or not**, using features like venue, toss decision, team strength (from orange/purple caps), and season stats.

---

## 🏆 **Skill Coverage**

| **Skill**              | **Questions**             |
| ---------------------- | ------------------------- |
| Joins & Aggregations   | 1, 2, 3, 4, 7, 13, 14, 15 |
| Window Functions       | 5, 9, 10, 16              |
| Broadcast Joins        | 11                        |
| UDFs & Logic           | 12                        |
| Complex Aggregations   | 8, 13, 17                 |
| Time/Date Functions    | 18                        |
| Statistical Analysis   | 19                        |
| MLlib (Model Building) | 20                        |

---
