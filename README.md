# Recommender-for-Business-Ratings
Matrix Factorization and Regression Models for Predicting User Ratings of California Businesses.

## Objective
This project aims to find the best model to predict user ratings of Californa businesses, using data from Google Local.

### Methods Used
- Exploratory Data Analysis (EDA)
- Recommender Systems:
  - Baseline Mean Predictor
  - Latent Factor: Bias only
  - Complete Latent Factor
  - FastFM with no features
  - FastFM with features
  - Probabilistic Matrix Factorization
- Regression Models:
  - Linear Regression
  - Random Forest
  - KNN
  - SVR

### Technologies
- Python
- Numpy, Pandas
- Matplotlib, Plotly
- Tensorflow
- Scipy
- FastFM
- Surprise
- Sklearn

### Data
Data is provided by Julian McAuley's lab for the purpose of research in recommender systems. It can be found [here](https://cseweb.ucsd.edu/~jmcauley/datasets.html#google_local). For this paper, I download the review and places data.

The review dataset contains reviews about businesses from Google Local (i.e. Google Maps). It includes information such as reviewer name, rating, and review time. The places dataset contains informaton on the businesses reviewed. This includes but is not limited to name, price category, address, and hours.

## Project Description
In this paper, we investigate the performance of various models on predicting user ratings given to businesses in California. We compare matrix factorization and standard regression models. After feature engineering, fine-tuning the models, and evaluating the prediction error, we identify the best performing models for our dataset.

## Repository Contents
Reminder: To run the notebook, make sure to download the review and places data as described in the Data section. Put these datasets in a folder named 'data' under the same location as the notebook.

- `Report.pdf`: report
- `eda_and_prediction_for_google_reviews`: jupyter notebook containing all EDA and the survey of predictive models
