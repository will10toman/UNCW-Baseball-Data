# UNCW Baseball Technical Report & Data Analysis

## Overview
This repository contains the technical report and code used to analyze the **UNCW Baseball Team's** pitching data using **Trackman Technology**. Our study applies data science methodologies to examine **pitch effectiveness, leverage situations, and handedness matchups**, providing actionable insights for player development and strategic decision-making.

## Objectives
- Utilize **Trackman data** (54,000+ pitches, 167 features) to analyze pitching performance.
- Categorize and evaluate pitcher performance in **low, medium, and high-leverage situations**.
- Identify trends in **pitch selection, accuracy, and outcomes**.
- Develop **data visualizations** (heatmaps, scatter plots, and pitch variety charts) to enhance insight accessibility.

## Methodology
- **Data Cleaning & Processing:**
  - Removed missing values and normalized data.
  - Created new features such as **adjusted leverage score** and **cumulative runs**.
- **Visualization Techniques:**
  - **Heatmaps**: Displayed pitch distribution across the strike zone.
  - **Scatter Plots**: Compared ball vs. strike ratios in different leverage situations.
  - **Pie Charts**: Analyzed pitch selection frequency in various counts.
- **Statistical Analysis:**
  - Evaluated how pitchers performed under pressure.
  - Examined effectiveness of **pitcher-batter handedness matchups**.
- **Future Work:**
  - Develop **machine learning models** for predictive analytics.
  - Create an **interactive R Shiny dashboard** for real-time analysis.

## Repository Structure
```
├── data/               # Raw & processed Trackman dataset
├── notebooks/          # Jupyter notebooks with analysis & visualizations
├── figures/            # Generated visualizations
├── report/             # Full technical report & supplementary materials
├── README.md           # Project documentation (this file)
```

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/uncw-baseball-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook for exploration:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

## Key Visualizations
- **Pitch Location Heatmaps**: Show areas where pitchers are most effective.
- **Leverage-Based Scatter Plots**: Compare strike-to-ball ratios in different game situations.
- **Pitch Variety Charts**: Identify pitch selection trends based on count scenarios.

## Contributors
- **Mavin James**
- **Will Toman**
- **Sean Burke**

## Acknowledgments
Special thanks to the **UNCW Baseball Team** for providing data and **Dr. Yang Song** for guidance in applying data science techniques to sports analytics.
