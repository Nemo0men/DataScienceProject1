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

Project-Repository/
│
├── README.md
│   └── Overview, software requirements, documentation map, and reproduction instructions
│
├── LICENSE.md
│   └── MIT License describing terms of use and citation
│
├── SCRIPTS/
│   ├── 01_data_import_and_cleaning.py
│   │   └── Loads raw data and performs initial cleaning
│   ├── 02_feature_engineering.py
│   │   └── Creates derived variables used in analysis
│   ├── 03_analysis_models.py
│   │   └── Runs statistical / machine learning models
│   └── 04_generate_outputs.py
│       └── Produces tables and figures saved to OUTPUT/
│
├── DATA/
│   ├── raw/
│   │   └── original_dataset.csv
│   ├── processed/
│   │   └── final_analysis_dataset.csv
│   └── Data_Appendix.pdf
│       └── Descriptive statistics, variable definitions, and dataset documentation
│
└── OUTPUT/
    ├── figures/
    │   ├── figure_1.png
    │   └── figure_2.png
    ├── tables/
    │   └── summary_statistics.csv
    └── model_results.txt


README.md
* Software and platform, map of documentation, and instructions for reproducing results

LISCENSE.md
* Terms in which the repositor can be cited and reproduced

SCRIPTS/
* eda_movie_sentiment.ipynb: Code used to create EDA
* movie_review_sentiment_model.ipynb: Code used to create linear regression model

DATA/
* movie_data: Containscsv file of original data obtained from Kaggle (before cleaning)
* movieData_cleaned: Contains csv file of cleaned data
Project-Repository/

OUPUT/
* classification_report.txt: Image containing information about the precision, recall, f1 score, and support
* confusion_matrix_logistic_regression.png: Image of confusion matrix logistic regression results
* original_score_vs_polarity.png: Image of linear regression model of orginal score vs. polarity score
* score_distribution.png: Histogram of normalized rotten tomato score and the frequency
* score_polarity.png: Histogram of polarity score and frequency


## git pushing:

git add .
git commit -m "i changed this..."
git push
