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
The software used for this project was Google Colab and Google Drive. The language used was Pythong (3.12.4). Additionally, the platform that was used was a Windows, and the following packages were used for this project:
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
│   ├── 01_eda_movie_sentiment.ipynb
│   │   └── Code used to create EDA and charts
│   ├── 02_movie_review_sentiment_model.ipynb
│   │   └── Code used to generate the model
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




## git pushing:

git add .
git commit -m "i changed this..."
git push
