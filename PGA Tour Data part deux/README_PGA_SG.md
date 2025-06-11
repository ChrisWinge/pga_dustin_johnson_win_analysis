
# PGA Strokes Gained Analysis

## 📊 Project Overview
This project analyzes strokes gained (SG) data from PGA Tour events to understand player performance across key metrics. The primary focus is on how Dustin Johnson performed during his tournament victories, with comparisons against other top-10 finishers and field averages.

## 🎯 Objectives
- Understand how SG metrics differentiate top finishers
- Compare Dustin Johnson’s SG stats against:
  - Other 1st place finishers (position-based averages)
  - Tournament field averages
- Visualize SG performance trends across individual tournaments
- Identify what parts of DJ's game contributed most to his wins

## 🧮 Data Processing Approach
- Load raw tournament-level strokes gained data
- Filter for top-10 finishers and 1st place performances
- Create derived columns:
  - `event label` (season + tournament name) for unique identifiers
  - SG deltas: player SG minus average SG for that position
  - SG field deltas: player SG minus tournament field average
- Aggregate SG stats across tournaments for analysis

## 📈 Visualizations
- Bar charts comparing DJ's SG performance to:
  - Other 1st place finishers
  - Tournament field averages
- Grouped bar charts (DJ vs Field) across SG categories
- One-chart-per-tournament matrix of DJ’s SG breakdown

## 📌 Metrics Analyzed
- `sg_putt` – Putting
- `sg_arg` – Around the Green
- `sg_app` – Approach Shots
- `sg_ott` – Off the Tee
- `sg_t2g` – Tee to Green
- `sg_total` – Total Strokes Gained

## 💡 Key Takeaways
- DJ’s wins were often driven by dominance off the tee and strong tee-to-green play
- His putting and around-the-green metrics were not as consistently superior
- Tournament-specific analysis highlights variability in *how* he won

---

**Future Extensions**
- Apply the same analysis to other players (e.g., Rory, Rahm, Scheffler)
- Add historical trend analysis across seasons
- Use machine learning to predict top-10 finish likelihood based on SG profiles
