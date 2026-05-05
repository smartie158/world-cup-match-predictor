# World Cup Match Predictor

This project predicts international soccer match outcomes using historical match data

# Goal
Predict, win, draw and loss probabilities for World Cup Matches

# Data Sources
- Historical international match results
- Team-level rolling performance features created from past matches

## Methods 
The project follows a full data science workflow:

1. Data cleaning
2. Feature engineering
3. Model training
4. Model Evaluation
5. Match Probability Prediciton

## Features Used
The model uses recent team performance metrics, including: 

- Average goals scored in last 5 matches
- Average goals concedeed in last 5 matches
- Win rate in last 5 matches
- Opponent recent form
- Goal-scoring difference
- Defensive difference
- Win-rate difference

## Model 
A random Forest Classifier was used as the baseline model because it can capture nonlinear relationships between team performance features and match outcomes. 

## AI-Generated Bracket Simulation

This Project also includes a planned AI-generated elimination bracket. The model predicts each knockout matchup, advances the team with the higher predicted win probability, and repeats the process until a projected champion is selected. 

The Bracket simulation includes:

- Round of 16
- Quarter Finals
- Semifinals
- Final
- Predicted Champion

## Repository Structure
```text
data/
  raw/
  processed/

notebooks/
01_cleaning.ipynb
02_feature_engineering.ipynb
03_modeling.ipynb
04_world-cup_predictions.ipynb

src/
visuals/
README.md
requirements.txt
