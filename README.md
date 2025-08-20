# Mental Load and Consumer Decisions

## Project Overview
This project investigates whether people make worse decisions when exposed to too many options.  
Using simulated data for 500 participants across 6 choice scenarios, we explore the impact of mental load on decision quality, satisfaction, regret, and decision time.

## Dataset
- 500 participants
- Variables:
  - `participant_id`: unique ID
  - `age`: 18–65
  - `gender`: Male, Female, Other
  - `education_level`: High School, Bachelor, Master, PhD
  - `num_choices`: 6
  - `scenario_type`: Simple, Medium, Complex
  - `decision_time`: seconds taken
  - `mental_load_score`: 1–10
  - `satisfaction_score`: 1–10
  - `regret_score`: 1–10
  - `decision_quality`: Good, Average, Poor

## Methods
- Data simulation using Python
- Exploratory Data Analysis (EDA)
- Statistical Analysis:
  - ANOVA
  - Pearson Correlation
  - Multiple Linear Regression

## Key Findings
- Scenario complexity significantly affects decision time, satisfaction, and mental load (ANOVA, p<0.001)
- Higher mental load correlates with lower satisfaction (r=-0.67) and higher regret (r=0.69)
- Regression shows mental load is the strongest negative predictor of satisfaction (coef=-0.37)

## Tools
- Python (pandas, numpy, seaborn, matplotlib, statsmodels)
- Optional: Tableau / Power BI for interactive dashboards

## Folder Structure
