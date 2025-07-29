# 🏏 T20 World Cup 2022 Final – End-to-End Data Analytics Project

This is a complete end-to-end cricket data analytics project based on the ICC **T20 World Cup 2022**, focused on analyzing the **Final Match** using real-world data from ESPN Cricinfo.

We use **web scraping**, **Python**, **Pandas**, and **Power BI** to transform raw scorecards into compelling, interactive dashboards to generate actionable cricket insights.

---

## 🚀 Project Overview

The goal of this project was to identify key performers, game momentum, and impactful plays from the T20 World Cup Final between **England 🏴 and Pakistan 🇵🇰**.

Key steps included:
- Web scraping raw match, batting, bowling, and player data using **Bright Data**
- Data transformation and relationship modeling using **Python (Pandas + JSON)**
- Creating CSVs suitable for dashboard consumption
- Building an interactive dashboard in **Power BI**
- Selecting an **optimal playing XI** based on custom analytics rules

---

## 🧰 Tools & Technologies

| Tool            | Use Case                               |
|-----------------|----------------------------------------|
| **Python**      | Data extraction, transformation (ETL)  |
| **Pandas**      | Data wrangling and preprocessing       |
| **Bright Data** | Web scraping from ESPNcricinfo         |
| **Power BI**    | Dashboard creation & insight delivery  |
| **JSON/CSV**    | Data format handling                   |

---

## 📊 Dashboard Highlights

- **Interactive filters**: Analyze players by roles – Power Hitters, Anchors, Finishers, All-rounders, Bowlers.
- **Custom DAX metrics**:
  - Batting average
  - Boundary percentage
  - Bowling economy
  - Dot ball percentage
- **Visual Insights**:
  - Scatter plots (Strike Rate vs. Average)
  - Bar charts of top performers
  - Final playing XI selection logic

![Dashboard Preview](DashboardView.pdf)

---

## 📁 Project Structure

```bash
📦T20-WorldCup-Analytics/
├── data/
│   ├── t20_match_results.json
│   ├── t20_batting_summary.json
│   ├── t20_bowling_summary.json
│   └── t20_players.csv
├── notebooks/
│   └── data_transformation.ipynb
├── dashboard/
│   └── t20_final.pbix
├── images/
│   └── dashboard_preview.png
├── README.md
