# NBA Game Outcome Prediction Model

This project builds a machine learning model to predict NBA game outcomes using Elo ratings and home court advantage.

## Dataset
NBA Elo dataset from FiveThirtyEight.

## Features
- Team Elo rating
- Opponent Elo rating
- Home court indicator
- Season

## Model
Logistic Regression

## Results
Test Accuracy: ~68%

The model outperforms a simple Elo baseline (~64%).

## Visualizations
- Win probability vs Elo difference
- Model calibration curve
- Accuracy by Elo difference

## Key Insights
- Large Elo differences lead to ~91% prediction accuracy
- Evenly matched teams drop to ~63% accuracy
- Elo alone cannot capture factors like injuries, lineup matchups, or shooting variance

## Future Improvements
- Player level metrics
- Injury reports
- Rest days
- Advanced team efficiency metrics
- XGBoost / Random Forest models
