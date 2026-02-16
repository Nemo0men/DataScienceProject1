# DataScienceProject
DS 4002: Data Science Project

## Section 1: Software and platform section
The software used for this project was Google Colab and Google Drive. The language used was Python (3.12.4). Additionally, the platform that was used was a Windows, and the following packages were used for this project:
* numpy
* pandas
* matplotlib
* sklearn
* kagglehub
* textblob

## Section 2: Map of the documentation

**README.md**  
- Overview of the project, software and platform used, documentation map, and instructions for reproducing results

**LICENSE.md**  
- Terms for citing and reproducing the repository

**SCRIPTS/**  
- `eda_movie_sentiment.ipynb` – Code used to perform exploratory data analysis (EDA)  
- `movie_review_sentiment_model.ipynb` – Code used to create the linear regression model

**DATA/**  
- `movie_data.csv` – Original dataset obtained from Kaggle
- `movieData_cleaned.csv` – Cleaned version of the dataset for analysis

**OUTPUT/**  
- `classification_report.txt` – Text report containing precision, recall, F1 score, and support  
- `confusion_matrix_logistic_regression.png` – Confusion matrix for logistic regression results  
- `original_score_vs_polarity.png` – Linear regression plot of original score vs. polarity score  
- `score_distribution.png` – Histogram of normalized Rotten Tomato scores and frequency  
- `score_polarity.png` – Histogram of polarity scores and frequency  
- `movie_sentiment_model.joblib` – Serialized machine learning model for predicting movie review sentiment

**REFERENCES.md**  
- References to the Kaggle site 


## git pushing:

git add .
git commit -m "i changed this..."
git push
