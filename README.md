# Personalized-Wellness-AI
This project is a proof-of-concept machine learning system designed to generate personalized wellness insights using synthetic data. It was created as part of an assignment to demonstrate end-to-end understanding of data science pipelines in a wellness context.

## Project Overview

The goal of this notebook is to:
- Generate realistic synthetic wellness data
- Visualize wellness trends and relationships
- Train a model to predict mood scores from daily habits
- Reflect on the real-world impact, risks, and challenges in building wellness AI systems


## Features Simulated

The following features were synthetically generated based on wellness research and assumptions:
- `age`
- `gender`
- `sleep_duration` (hours)
- `daily_steps`
- `stress_level` (1–10)
- `diet_quality` (`Poor`, `Average`, `Good`)
- `water_intake` (liters)
- `screen_time` (hours)
- `mood_score` (target variable: 1–10)


## Key Visualizations

- **Scatter Plot:** Daily Steps vs. Sleep Duration  
- **Histogram:** Distribution of Mood Scores  

These plots help uncover patterns in lifestyle and wellness relationships.


## Machine Learning Approach

- **Problem Type:** Regression (predicting `mood_score`)
- **Model Used:** Random Forest Regressor
- **Evaluation Metrics:** RMSE, MAE, R² Score


## Results

| Metric      | Value |
|-------------|-------|
| RMSE        | ~0.82 |
| MAE         | ~0.61 |
| R² Score    | ~0.39 |


## Real-World Impact

- Personalized recommendations for sleep, stress, water, screen time
- Early insights into mental health
- Encourages behavior change through passive monitoring

### Considerations
- Data privacy must be maintained
- Avoid over-reliance on AI-generated suggestions
- Need for real-world validation with diverse user data


## Author Reflection

This project challenged me to design realistic synthetic datasets and make modeling choices that align with both data quality and ethical AI deployment. It strengthened my ability to work across the full ML lifecycle — from simulation to impact evaluation.


## File

- `ml_wellness_project_rohan_dobriyal.ipynb` — full notebook with markdown Q&A, code, and visualizations
