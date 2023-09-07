## Football Match Prediction Project Using Random Forest (RF) Classifier

### Table of Contents
1. Project Overview
2. Repository Contents
   * Web Scraping
   * Model Development
3. Model Evaluation
4. Results
5. Future Improvements

#### Project Overview
In this project, I harnessed machine learning classifier called Random Forest classifier to predict football match outcomes. This choice was driven by the classifier's strength in capturing non-linear relationships within the data, an important aspect in predicting football match results. This project aims to provide insights into the world of football match forecasting. Whether you are a sports enthusiast, a sports bettor, or simply curious about the power of data and machine learning in predicting football match results, this project provides valuable insights.

#### Repository Contents
**Web Scraping**  
web scraping premier league data.ipynb: This file scrapes historical football match data from [fbref](https://fbref.com/en/comps/9/Premier-League-Stats), cleans it meticulously, and saves it as a CSV file for further analysis and model development.
**Model Development**  
Matches_prediction_model.ipynb: The main script. It imports the pre-processed match data, conducts data wrangling, analysis, and feature extraction. Features are engineered to capture essential factors affecting match outcomes. The Random Forest classifier is used to build a predictive model, and GridSearchCV fine-tunes its hyperparameters for optimal performance.

### Model Evaluation**
Our final Random Forest classifier boasts a precision score of 60%. Which means the model was correct 60% of the time. Precision measures the accuracy of positive predictions in football match outcomes, meaning our model correctly predicts winning teams with a 60% accuracy rate.

### Results
Our Random Forest classifier has demonstrated a precision score of 60%, showcasing its capability to predict football match outcomes accurately. This project offers valuable insights into the intersection of sports analytics and machine learning, highlighting the power of data-driven predictions in the world of football. Enjoy exploring and predicting the beautiful game!

### Future Improvements
There are many areas this project can be improved on to provide better predictions for upcoming fixtures:
1. Aligning for deployment
2. Considering relative team strength
3. Ranking teams in order of strength



