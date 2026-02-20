🎬 Movie Rating Prediction
📌 Overview

This project builds a regression model to predict movie ratings based on features such as genre, director, and actors. The objective is to analyze historical movie data and estimate the rating a movie might receive.

📊 Dataset Features

The dataset includes:

Genre

Director

Actor 1, Actor 2, Actor 3

Additional metadata

Rating (Target Variable)

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

🔍 Data Preprocessing

Removed missing target values

Filled missing categorical values

Combined actor columns into single feature

Applied TF-IDF vectorization on actor data

Removed raw text columns

Selected numerical features for modeling

🤖 Model Used

RandomForestRegressor

📈 Evaluation Metrics

RMSE (Root Mean Squared Error)

R² Score

These metrics help evaluate prediction accuracy and variance explanation.

🚀 Future Improvements

Hyperparameter tuning

Gradient Boosting / XGBoost

Director frequency encoding

Review sentiment analysis

Model deployment using Streamlit

▶ How to Run
pip install -r requirements.txt
python movie_rating_model.py
📦 requirements.txt
pandas
numpy
scikit-learn
matplotlib
seaborn
