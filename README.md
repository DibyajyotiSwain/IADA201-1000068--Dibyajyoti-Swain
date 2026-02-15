# IADA201-1000068--Dibyajyoti-Swain

# IPL Match-Winning Factors Analysis

**Course:** Artificial Intelligence
**Course Name:** The Art of Storytelling with Data
**Student Name:** Dibyajyoti Swain


## 📊 Project Overview

This project analyzes IPL cricket data to identify key match-winning factors using interactive Tableau dashboards. The objective is to evaluate player performance, team rivalries, toss influence, and venue impact on match outcomes.

The dashboard is designed for cricket analysts, franchises, coaches, and stakeholders seeking data-driven strategic insights.

---

## 📁 Data Summary

Two datasets were used:

* **matches.csv** → Match-level data
* **deliveries.csv** → Ball-by-ball data

### 🔗 Data Integration

The datasets were joined inside Tableau using:

`matches.id = deliveries.match_id`

An inner join was applied to ensure consistency between match-level and ball-level records.

---

## 🔄 Data Preparation & Transformation

Data cleaning and structuring were performed inside Tableau:

* Standardized team names (e.g., Delhi Daredevils → Delhi Capitals)
* Unified franchise rebranding (e.g., Kings XI Punjab → Punjab Kings)
* Created calculated fields including:

  * Strike Rate
  * Economy Rate
  * Valid Wickets (excluding run-outs)
  * Win Type (Batting First vs Chasing)
* Removed unnecessary fields for better performance and clarity

---

## 📈 Dashboard Components

The final dashboard consists of the following analytical sections:

### 1️⃣ Top Batsmen — Runs & Strike Efficiency

Highlights high-impact batters based on total runs and strike rates.

### 2️⃣ Top Bowlers — Wickets & Economy

Identifies dominant bowlers balancing wicket-taking ability and run control.

### 3️⃣ Team Rivalries — Head-to-Head Patterns

Visualizes match-level rivalry dynamics showing dominance trends between franchises.

### 4️⃣ Toss Impact — Strategic Influence

Analyzes how toss decisions influence match outcomes.

### 5️⃣ Venue-Based Analysis

Examines how different stadiums affect win patterns and match dynamics.

All components are interactive with dynamic filters for season, team, and venue.

---

## 📖 Story Narrative Structure

The Tableau Storyboard presents six structured insights:

1. Batting dominance and scoring efficiency
2. Bowling control and wicket impact
3. Head-to-head rivalry patterns
4. Overall win percentage comparison
5. Toss decision influence
6. Venue-based variations in match outcomes

The story flows logically from player-level impact to team strategy and environmental influence.

---

## 🔍 Key Insights

* High run accumulation combined with strong strike rates defines modern batting dominance.
* Teams with disciplined bowling units and effective wicket-taking outperform in critical phases.
* Certain franchises show sustained superiority in specific rivalries.
* Toss decisions influence strategic match flow.
* Venue conditions significantly impact scoring patterns and winning probability.

---

## 🎛 Interactive Features

* Season filter
* Team selection filter
* Venue-based filtering
* Dynamic tooltips with match-level details
* Multi-page story navigation

---

## 🔗 Tableau Public Dashboard Link:

https://public.tableau.com/app/profile/dibyajyoti.swain6968/viz/IPL_Match_Winning_Factors_Dibyajyoti_Swain_Dashboard/DecodingIPLMatch-WinningFactors?publish=yes


**Storyboard: **

https://public.tableau.com/app/profile/dibyajyoti.swain6968/viz/IPL_Match_Winning_Factors_Dibyajyoti_Swain_Dashboard/Storyboard?publish=yes 

---
## Screenshots of the Tableau Dashboard
<img width="1016" height="414" alt="Screenshot 2026-02-15 121523" src="https://github.com/user-attachments/assets/1b3ee3ef-e87a-443b-b798-a3343dac2bd6" />
<img width="1594" height="808" alt="Screenshot 2026-02-15 121450" src="https://github.com/user-attachments/assets/8932cd56-89e3-4705-aecd-91a947ca1b0f" />
<img width="1094" height="544" alt="Screenshot 2026-02-15 121423" src="https://github.com/user-attachments/assets/dc3e48e3-a887-4129-9943-1608cf0d5f99" />
<img width="1087" height="497" alt="Screenshot 2026-02-15 121358" src="https://github.com/user-attachments/assets/e707e0d4-2582-4821-ac87-8f4c608890d5" />
<img width="1088" height="749" alt="Screenshot 2026-02-15 121344" src="https://github.com/user-attachments/assets/fe135180-dd83-42fe-90dd-702779dcdfa7" />
<img width="1345" height="762" alt="Screenshot 2026-02-15 121329" src="https://github.com/user-attachments/assets/1cd5222e-c6e7-43dd-b837-af8a823a629d" />
<img width="1344" height="766" alt="Screenshot 2026-02-15 121315" src="https://github.com/user-attachments/assets/ca174faf-fed6-4fb9-beba-f4b435dd2f56" />

## 🧾 Conclusion

This project demonstrates how structured data visualization reveals meaningful competitive patterns in professional sports. By integrating player metrics, team dynamics, and strategic variables, the dashboard provides actionable insights into IPL match-winning factors.

The analysis highlights the combined impact of batting efficiency, bowling control, rivalry dominance, toss decisions, and venue influence in shaping match outcomes.

