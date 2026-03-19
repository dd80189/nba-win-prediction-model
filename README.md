# NBA Game Outcome Prediction Model

This project predicts NBA game outcomes using Elo ratings and contextual features.
The model achieves ~68% accuracy, outperforming a simple Elo baseline (~64%), and provides insight into when predictive models succeed and fail in sports analytics.

## Dataset
NBA Elo dataset from FiveThirtyEight.

## Features
- Team Elo rating
- Opponent Elo rating
- Home court indicator
- Season

## Model
Logistic Regression was used for its interpretability and ability to estimate win probabilities.

## Results
Test Accuracy: ~68%

The model outperforms a simple Elo baseline (~64%).

## Visualizations
- Win probability vs Elo difference
- Model calibration curve
- Accuracy by Elo difference

## Key Insights
- Model performance improves significantly when there is a large Elo difference between teams
- Prediction accuracy drops for evenly matched teams
- Home court advantage meaningfully increases win probability
- Elo ratings are strong predictors, but miss important context like injuries and player-level data

## Future Improvements
- Player level metrics
- Injury reports
- Rest days
- Advanced team efficiency metrics
- XGBoost / Random Forest models

## Why This Matters

This project demonstrates how simple models can perform well in sports prediction tasks, while also highlighting the limitations of relying only on team-level metrics like Elo ratings.
