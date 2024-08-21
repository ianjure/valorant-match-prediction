# Valorant Match Prediction &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ianjure/valorant-match-prediction/blob/main/Valorant_Match_Prediction.ipynb)
The VALORANT Champions Tour (VCT) showcases the world's top teams in a year-long, global circuit organized by Riot Games.
This tour comprises three tiers of competition: challengers, masters, and champions.
The goal of this project is to create a machine learning model to predict the game winners of VCT 2023.
We will train classification models and find the top-performing one.

## Data Overview
Since the **[original](https://www.kaggle.com/datasets/ediashtarevin/vct-champions-2023-stats)** dataset from **Kaggle** contains some missing and unreadable values,
we will be using the **[VCT 2023](https://github.com/ianjure/valorant-match-prediction/blob/main/VCT2023.csv)** dataset from this repository, which is already semi-processed.
This dataset contains the basic statistics of each player and team for each game, containing 22 columns and 6,000+ rows.

## Project Method
1. **Clean the Data:** Select relevant features, handle categorical variables, calculate average values, and shuffle the data.
2. **Explore the Data:** Find meaningful insights by answering analytical questions.
3. **Build the Model:** Train the algorithms and find the best one.
4. **Test the Model:** Build a simple GUI in Google Colab to test new data.

## Next Steps
1. **Test** more classification models.
2. **Deploy** the model by building a simple web application.
