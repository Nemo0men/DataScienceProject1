# DataScienceProject
UVA class 4002: Data Science Project


## formating
Goal: This file serves as an orientation to everyone who comes to your repository, it should enable them to get their bearings.
Use markdown headers to divide content.
Make an H2 (##) section explaining the contents of the repository
Section 1: Software and platform section
The type(s) of software you used for the project.
The names of any add-on packages that need to be installed with the software.
The platform (e.g., Windows, Mac, or Linux) you used.
Section 2: A Map of your documentation.
In this section, you should provide an outline or tree illustrating the hierarchy of folders and subfolders contained in your Project Folder, and listing the files stored in each folder or subfolder.
Section 3: Instructions for reproducing your results. 
In this section, you should give explicit step-by-step instructions to reproduce the Results of your study. These instructions should be written in straightforward plain English, but they must be concise, but detailed and precise enough, to make it possible for an interested user to reproduce your results without much difficulty. N.B. This section will be crucial for the CS1 assignment, where you'll be required to reproduce the results of other groups. Therefore, make sure to explain this section thoroughly. 

## Section 1: Software and platform section
The software used for this project was Google Colab and Google Drive. The language used was Python (3.12.4). Additionally, the platform that was used was a Windows, and the following packages were used for this project:
* numpy
* pandas
* matplotlib
* sklearn
* kagglehub
* textblob

##Section 2: Map of your documentation
Below is an outline illustrating the hierarchy of the folders and the files stored in each

**README.md**  
- Overview of the project, software and platform used, documentation map, and instructions for reproducing results

**LICENSE.md**  
- Terms for citing and reproducing the repository

**SCRIPTS/**  
- `eda_movie_sentiment.ipynb` – Code used to perform exploratory data analysis (EDA)  
- `movie_review_sentiment_model.ipynb` – Code used to create the linear regression model

**DATA/**  
- `movie_data/` – Original dataset obtained from Kaggle (before cleaning)  
- `movieData_cleaned/` – Cleaned version of the dataset for analysis

**OUTPUT/**  
- `classification_report.txt` – Text report containing precision, recall, F1 score, and support  
- `confusion_matrix_logistic_regression.png` – Confusion matrix for logistic regression results  
- `original_score_vs_polarity.png` – Linear regression plot of original score vs. polarity score  
- `score_distribution.png` – Histogram of normalized Rotten Tomato scores and frequency  
- `score_polarity.png` – Histogram of polarity scores and frequency  
- `movie_sentiment_model.joblib` – Serialized machine learning model for predicting movie review sentiment

**REFERENCES.md**  
- References to the Kaggle site and other sources used


## git pushing:

git add .
git commit -m "i changed this..."
git push
