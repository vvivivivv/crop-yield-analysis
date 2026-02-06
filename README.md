# crop-yield-analytics

**Course**: BC2407 Analytics II: Advanced Predictive Analytics  
**Semester**: AY24/25 Sem 2  

**Project**: Crop Yield Prediction Using Regression Models

**Assessment Type**: Computer-Based Assessment (Individual Project)

---

## 📘 Project Description
This project investigates crop yield prediction using historical agricultural and environmental data from India, based on a case scenario provided by the **Ministry of Agriculture and Farmers Welfare**. The objective is to develop and compare predictive models that estimate crop yield productivity and output, and to derive data-driven insights that may inform agricultural planning and policy decisions.

The following regression-based models were evaluated:
- Linear Regression  
- MARS (Multivariate Adaptive Regression Splines)  
- Random Forest 

---

## 📁 Structure
- `code/` - R script for preprocessing and modeling
- `data/` - Raw dataset

---

## 🧪 Project Tasks Overview

### 🔍 Part A: Data Exploration & Research Questions (30%)
Exploratory analysis was conducted to understand crop yield patterns across:
- Crop types and states
- Seasonal effects
- Weather conditions (e.g. rainfall)
- Agricultural inputs (fertiliser and pesticide usage)

#### Research Questions
1. How do agricultural factors (crop type, fertiliser usage, pesticide usage) and natural factors (season, annual rainfall) affect crop yield productivity and output?

2. To what extent do these factors, as well as their combined effects, influence crop yield productivity and
output?

#### Methodology Overview
- Research Question 1 was addressed using association rules and predictive models to identify relationships between explanatory factors and yield outcomes. Statistical significance and variable importance were used to assess influence.
- Research Question 2 was explored through model coefficients, interaction terms, hinge functions (MARS), and variable importance measures to evaluate the magnitude and combined effects of factors.

Together, these questions aim to identify key yield drivers and uncover interaction effects that reflect real-world agricultural conditions.

### 🤖 Part B: Model Building & Evaluation (40%)
- Trained models using pre-2018 data, tested on 2018 and beyond.
- Evaluated performance across Linear Regression, MARS, and Random Forest, via RMSE and R².
- Model outputs were used to answer the research questions and assess predictive capability.

### 🧠 Part C: Insights & Recommendations (30%)
- Synthesised model findings into actionable insights.
- Highlighted key trends, influential factors, and interaction effects.
- Proposed strategic recommendations for improving agricultural productivity and yield forecasting.

---

## 🛠 Technologies Used
- R (with `earth`, `randomForest`, `caret`)
- RStudio

---

## 🚀 How to Run
1. Open `code/crop_yield_analytics.R` in RStudio.
2. Install required packages.
3. Retrieve raw input dataset in `data/`.
4. Run the script to reproduce the analysis and models.

---

## 📌 Notes
- All identifying student information has been removed for privacy.
- Dataset was provided as part of the BC2407 assessment and is not open-source.
