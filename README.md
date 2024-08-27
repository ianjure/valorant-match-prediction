# Valorant Match Prediction &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ianjure/valorant-match-prediction/blob/main/Valorant_Match_Prediction.ipynb)
The VALORANT Champions Tour (VCT) is a premier global circuit organized by Riot Games, featuring the world's top teams in a year-long competition. The tour is divided into three tiers: Challengers, Masters, and Champions. This project aims to develop a machine learning model to predict the game winners of VCT 2023. We will train various classification models and identify the most effective one.

## Data Overview
The **[original](https://www.kaggle.com/datasets/ediashtarevin/vct-champions-2023-stats)** dataset from **Kaggle** has some missing and unreadable values. Instead, we will use the semi-processed **[VCT 2023](https://github.com/ianjure/valorant-match-prediction/blob/main/VCT2023.csv)** dataset from this repository. This dataset includes basic statistics for each player and team per game, with 22 columns and over 6,000 rows.

## Project Method
1. **Clean the Data:** Select relevant features, handle categorical variables, compute average values, and shuffle the dataset.
2. **Explore the Data:** Derive meaningful insights by addressing analytical questions.
3. **Build the Model:** Train different algorithms to determine the best-performing one.
4. **Test the Model:** Create a simple GUI in Google Colab to evaluate the model with new data.

## Next Steps
* **Evaluate** additional classification models.
* **Deploy** the model by developing a simple web application.
