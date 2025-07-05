# Young Football Players Performance Analysis in Top 5 European Leagues

## 📌 Overview

This project analyzes the performance of young football players (age ≤ 21) in Europe's top 5 leagues (Premier League, La Liga, Bundesliga, Serie A, Ligue 1) during the 2024-25 season. The analysis focuses on playing time, offensive contributions, positional distribution, and efficiency metrics to understand how young talents are integrated and perform at the highest level.

## 🎯 Objectives

- Examine the distribution and playing time of young players across leagues and clubs
- Analyze offensive contributions (goals and assists) of young players
- Evaluate efficiency metrics (xG, xAG conversion rates)
- Identify leagues and clubs that best support young talent development
- Cluster players into roles based on performance characteristics

## 📊 Key Metrics Analyzed

### Basic Statistics
- Age distribution across leagues
- Number and proportion of young players per club
- Playing minutes and starter rates

### Offensive Performance
- Goals and assists (absolute and per 90 minutes)
- Expected Goals (xG) and Expected Assists (xAG)
- Conversion rates (Gls/xG and Ast/xAG)
- Progressive passes and chance creation

### Positional Analysis
- Distribution across positions
- Average minutes by position
- Role classification (Finisher, Playmaker, Defender)

## 🛠️ Technical Implementation

### Data Sources
- Player statistics from top 5 European leagues (2024-25 season)
- Dataset: `top5-players24-25.xlsx`

### Python Libraries Used
- Pandas (data manipulation)
- Plotly & Matplotlib (visualization)
- Scikit-learn (clustering with KMeans)
- Seaborn (styling)

### Key Features
- Comprehensive data cleaning and validation
- Interactive visualizations with Plotly
- Player role clustering using KMeans
- Comparative analysis across leagues

## 📈 Key Findings

### League Comparisons
1. **Ligue 1** has the most young players (≈180) and highest proportion in squads
2. **La Liga** gives young players the most starter opportunities (60% starter rate)
3. **Premier League** provides the highest average minutes (746.83 per player)
4. **Bundesliga** players show highest offensive efficiency
5. **Serie A** has lowest young player minutes but some highly efficient individuals

### Player Insights
- Young players contribute 14% of goals and 15.6% of assists league-wide
- Top performers like Bradley Barcola (24 G+A) and Florian Wirtz (22 G+A) already have elite-level impact
- Goalkeepers get most consistent minutes when they break through
- Positional flexibility increases playing opportunities

## 🛠️ 6. Tools Used

* Plotly Express
* Plotly Graph Objects
* Plotly Subplots
* Seaborn/Matplotlib
* K-Means Clustering (scikit-learn)
* PCA Dimensionality Reduction (scikit-learn)

Author: Dzulfikri Alwi M (📧 dzulfikrialwim@gmail.com)

Dataset Source: All Football Players Stats in Top 5 Leagues 24/25 [(Kaggle)](https://www.kaggle.com/code/dzulfikrialwi/eda-young-player)

Period Covered: 2024–2025
