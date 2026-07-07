# World-Cup-2026-data-analysis-
FIFA World Cup 2026 Data Analysis &amp; Insights


# Project Overview

This project performs an Exploratory Data Analysis (EDA) on FIFA World Cup 2026 match data using Python.

The goal is to analyze team performance, match statistics, attendance, tactics, and key factors that influence match outcomes.

# The analysis covers:

- Match performance
- Goals analysis
- Attendance insights
- Possession trends
- Shooting performance
- Set pieces analysis
- Team statistics comparison
- Tactical formations
- Referee analysis
- Team-level performance metrics

---

# Dataset

Source: Kaggle - FIFA World Cup 2026 Matches Dataset

The dataset contains match-level information including:

 Match Information
- Competition round
- Gameweek
- Date
- Start time
- Home team
- Away team
- Venue
- Referee

 # Match Results
- Score
- Home goals
- Away goals
- Penalty shootouts

 # Team Performance Metrics

- Possession
- Total shots
- Shots on target
- Saves
- Corners
- Crosses
- Interceptions
- Fouls
- Offsides
- Cards

 Tactical Information

- Formation
- Manager
- Captain

---

 # Technologies Used

Python

Libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regex

---

# Score Cleaning

Some knockout matches contained penalty shootouts:

Example:

```
(3)1–1(4)
```

The score was processed to extract the actual match result:

```
Home Score = 1
Away Score = 1
```

Penalty values were separated from the final score.

---

# Possession Analysis

Analyzed:

- Average possession
- Home vs Away possession
- Team possession ranking

---

# Shooting Analysis

Analyzed:

- Total shots
- Shots on target
- Relationship between shots and goals

---

# Corners Analysis

Analyzed corner kick performance.

Visualization:

- Corner distribution boxplot

---

# Cards Analysis

Total cards:

Visualization:

- Yellow vs Red card comparison

---

# Team Performance Analysis

A team level dataset was created by combining:

- Home team statistics
- Away team statistics


Features:

```
Goals Scored
Goals Against
Shots
Shots on Target
Possession
Corners
Fouls
```

---

# Top Scoring Teams

Top performers by goals scored:

| Team | Goals |
|-|-:|
| France | 14 |
| Norway | 12 |
| Argentina | 11 |
| Germany | 11 |
| England | 11 |


---

# Team Visualizations

Created visualizations:

# 1. Top 10 Teams by Goals Scored

Shows the strongest attacking teams.

---

# 2. Goals For vs Goals Against

Evaluates:

- Offensive strength
- Defensive performance


---

# 3. Possession Ranking

Shows teams with the highest average possession.


---

# 4. Shots vs Shots on Target

Analyzes attacking efficiency.


---

# 5. Team Performance Radar Chart

Comparison of top teams based on:

- Goals
- Shots
- Shots on Target
- Possession
- Corners


---

## 6. Correlation Heatmap

Analyzes relationships between:

- Possession
- Shots
- Goals
- Corners
- Fouls

---

# Future Improvements (due to the lack of large data) 

Possible future extensions:

- Build a machine learning model to predict match winners
- Use SVM / Random Forest / XGBoost for predictions
- Predict tournament winner
- Create interactive dashboard using:
  - Power BI
  - Tableau
  - Streamlit


---

# Project Summary

This project demonstrates data cleaning, exploratory data analysis, statistical analysis, and visualization techniques using Python to extract insights from FIFA World Cup 2026 match data.
