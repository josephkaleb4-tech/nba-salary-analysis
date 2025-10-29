# nba-salary-analysis
A 20-year analysis of NBA player salaries (2004–2024) using R — regression, visualization, and data-driven insights on league economics.
# 🏀 NBA Salary Analysis (2004–2024)
*A 20-year data analytics project using R — regression, visualization, and economic insights.*

---

## 📘 Overview
This project analyzes 20 years of NBA player salary data (2004–2024) to identify the most influential factors behind player compensation. Using R, I applied descriptive statistics, correlation matrices, and multiple linear regression to uncover how experience, position, team, and league economics affect pay trends.  

The study demonstrates how **sports data** can reveal broader lessons about **market dynamics, performance valuation, and financial growth**.

---

## 🎯 Project Objectives
- Analyze how NBA salaries evolved over two decades.  
- Identify key drivers of salary variation (experience, position, team, season).  
- Build a regression model to predict NBA player salaries.  
- Translate findings into actionable insights for sports economics and analytics.

---

## 🧰 Tools & Technologies
- **Language:** R  
- **Libraries:** ggplot2, dplyr, corrplot, broom, scales, tibble, car  
- **Data Sources:** [Basketball Reference](https://www.basketball-reference.com) and [Spotrac](https://www.spotrac.com)  
- **Visualization:** Histograms, boxplots, scatterplots, and correlation matrices  

---

## 📊 Key Insights
- **Season year** had the strongest correlation (**+0.81**) with salary — average player pay rose by ≈ **$1.28M per year** due to league revenue and salary cap growth.  
- **Experience** contributed ≈ **$650K** per additional year, though salary growth plateaus after ~10 years.  
- **Positions** mattered: Guards and Forwards earned **$2–2.5M more** than Centers.  
- **Teams** like the **Warriors, Lakers, and Bucks** offered the highest average salaries, driven by market size and competitive investment.  
- The regression model achieved an **R² of 0.73**, confirming strong predictive accuracy.  

---

## 📈 Sample Visualizations
| Visualization | Description |
|----------------|-------------|
| ![Salary vs Season](outputs/scatter_salary_vs_season.png) | Upward salary trend (2004–2024) |
| ![Position vs Salary](outputs/boxplot_position.png) | Guards and forwards earn higher median salaries |
| ![Correlation Matrix](outputs/correlation_matrix.png) | Strong positive correlation with Season variable |

---

## 🧮 Regression Model Summary
**Dependent Variable:** Salary (USD)  
**Independent Variables:** Years in League, Season, Position, Team  

| Variable | Effect on Salary |
|-----------|-----------------|
| Season | +$1.28M per year |
| Years in League | +$650K per year |
| Position (PG/SF/SG/PF) | +$1.2M–$2.5M more than Centers |
| Adjusted R² | 0.73 |

---

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/josephkaleb4-tech/nba-salary-analysis.git
