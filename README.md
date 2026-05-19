# Spotify Popularity Prediction using Machine Learning

## Overview

This project explores the prediction of Spotify track popularity using Machine Learning techniques and data analytics workflows. The project was developed as part of the MSc in Artificial Intelligence and Data Science at Keele University.

The objective is to analyse audio and metadata features from Spotify tracks, identify relationships with popularity, and evaluate the performance of different supervised learning models in predicting track success.

The project follows a complete end-to-end Data Science pipeline, including:

- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Model training and evaluation
- Model interpretability and performance analysis
- Visual analytics and reporting

---

## Project Structure

```text
spotify-popularity-prediction/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── dataset.csv
│   ├── processed/
│   │   └── aggregated_df.csv
│   │   └── featured_df.csv
│
├── notebooks/
│   ├── 01_data_understanding_and_eda.ipynb
│   ├── 02_preprocessing_and_feature_engineering.ipynb
│   ├── 03_model_training_and_evaluation.ipynb
│   └── 04_final_results_and_interpretation.ipynb
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   └── models/

```

## Dataset

The project uses a Spotify tracks dataset containing audio features and metadata such as:
Danceability
Energy
Loudness
Tempo
Valence
Acousticness
Speechiness
Genre
Artist information
Track popularity score

The dataset was obtained from publicly available Spotify-related sources for academic and educational purposes.
URL: https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset

##vMachine Learning Workflow
### 1. Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Genre exploration
- Outlier detection
- Feature relationships
### 2. Data Preprocessing
- Missing value handling
- Feature encoding
- Feature scaling
- Train-test splitting
### 3. Model Training

Models explored include:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting / XGBoost

### 4. Evaluation Metrics
- R² Score
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
### 5. Interpretability
- Feature importance analysis
- Error analysis



## How to Run the Project

1. Clone the repository

```text
git clone https://github.com/SergioAraya12/spotify-popularity-prediction.git
cd spotify-popularity-prediction
```

2. Install dependencies

```text
pip install -r requirements.txt
```

3. Launch Jupyter Notebook

```text
jupyter notebook
```
4. Run notebooks in order:

    1. Data Understanding and EDA
    2. Data Preprocessing and Feature Engineering
    3. Model Training and Evaluation
    4. Results Interpretation and Conclusions
   
## Author

Sergio Araya

MSc Artificial Intelligence and Data Science

Keele University

## License

This project is intended for academic and educational purposes.
