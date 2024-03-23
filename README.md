## Movie Profitability Prediction Project

### Overview
The Movie Profitability Prediction project aims to analyze a dataset containing information about various movies, including features such as budget, genres, keywords, cast, crew, production companies, and more. The primary goal is to predict whether a movie will be profitable or not based on its features.

### Installation

1. Clone the Repository
    ```
    git clone <repository_url>
    ```


2. Install Requirements
    ```
    pip install -r requirements.txt
    ```

### Dataset
The dataset used in this project is sourced from TMDB (The Movie Database) and is available on Kaggle at [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data). It provides comprehensive information about thousands of movies, including details such as cast, crew, budget, revenue, production countries, release date.

### Project Description
The project involves the following key phases:

1. **Data Loading and Information Gathering**: The dataset is loaded, and basic information about its structure and contents is collected.

2. **Data Cleaning and Preprocessing**: The dataset undergoes cleaning and preprocessing steps to handle missing values, remove duplicates, and format data appropriately for analysis.

3. **Exploratory Data Analysis (EDA)**: In this phase, various analyses are performed to gain insights into the data. Different questions are explored, and visualizations are generated to understand the relationships between different features and movie profitability.

4. **Data Modeling**: The profitability of movies is defined as the target variable, and feature engineering is performed to select relevant features for training prediction models. Several machine learning models, including Logistic Regression, Decision Tree, Random Forest, and XGBoost, are trained and evaluated.

5. **Evaluation**: Each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Additionally, ROC-AUC plots are generated to visualize the model's performance in terms of true positive rate vs. false positive rate.

6. **Recommender System:** A recommender system is developed to suggest similar movies based on shared characteristics such as genres, keywords, and cast members. This system utilizes TF-IDF vectorization and cosine similarity to calculate similarity scores between movies and generate recommendations.


### Conclusion
The Movie Profitability Prediction project provides valuable insights into the factors influencing movie profitability and the effectiveness of machine learning models in predicting movie success. By analyzing various features and training predictive models, the project contributes to the understanding of the movie industry and its dynamics. Additionally, the recommendation system offers a personalized movie recommendation experience based on user preferences or movie attributes.
