# Esports-Results-Project
***
This is a python-based project to predict the results of professional League of Legends (LoL) games and exemplify my Data Science, and Python skills.  LoL is a game where 2 teams of 5 players select a "champion" and fight each other for about 30-40 minutes to destroy the other team.
## Overview and Structure:

This project is contained within 3 Jupyter Notebooks, each one exemplifying a different subset of skills.  The notebooks are:
- LoL_Data_Exploration.ipynb
- LoL_Elo_System.ipynb
- LoL_Predictions.ipynb

The 1st notebook, LoL_Data_Exploration, combines 11 years of LoL esports game data into a single dataframe.  The data was gathered from Oracle Elixir (https://oracleselixir.com/tools/downloads).  I engaged in exploratory data analysis in order to identify and understand the variations in the data as well as extract meaningful insights that can assist the coaching and decision making of professional esports teams.  I also engaged in cursory logistic regression to illuminate some of the key predictive features.  The notebook, in giving me a better understanding of the data, allowed me to develop a better predictive model.

The 2nd notebook, LoL_Elo_System.ipynb is focused on creating an elo system to predict the result of games.  As part of my preprocessing, I reshaped the dataset, and label encoded the categorical data (such as player names).  The elo system used 11 different component ratings for each team to create a holistic rating.  Using NumPy to improve the efficiency of my system, I utilised matrix multiplication and used NumPy arrays as a maps.  The system was then optimised using scipy.minimize.  The notebook, by creating new features, improved the predictive performance of my machine learning models, in LoL_Predictions, and by through analysis of the elo system's results, I gained a better understanding of the predictive importance of different categorical features.

The 3rd notebook, LoL_Predictions utilises 3 different machine learning models to predict the results of games: Logistic Regression, Random Forest, and Gradient Boost; the notebook includes a description of how all 3 models work.  In preprocessing, I reshaped the data, created derivative features, and standardised the data for each position, before evaluating the effectiveness of PCA, manual dimensionality reduction, and data transformation.  Finally, I assessed the effectiveness of the models using F1 Score and accuracy.

## Skills Demonstrated in Each Notebook:
**LoL_Data_Exploration.ipynb**
- Data Visualisation
- Statistical Analysis
- Feature Engineering
- Dealing with Missing Values
- Exploratory Data Analysis

**LoL_Elo_System.ipynb**
- Data Engineering and Reshaping
- Label Encoding
- NumPy Skills
- Written Explanation of how Elo Systems Work
- Creating Custom Functions
- Data Analysis and Visualisation
- Model Error Analysis

**LoL_Predictions.ipynb**
- Data Cleaning
- Feature Engineering
- Pre-processing for Machine Learning
- Z-score normalised data
- Data Filtering
- Data Transformation
- Dimensionality Reduction
- An Understanding of how various Machine Learning Algorithms Work
- Machine Learning Optimisation
- Feature Importance Analysis

## Libraries Used:
**Primary Libraries:**
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- XGBoost

**Secondary Libraries**
- SciPy
- Seaborn
- Functools

## How to Run the Application:
- Clone this repository.
- Make sure you have the correct packages installed.
- Unzip any zipped files.
- Open each Jupyter Notebook and run the cells in order.
