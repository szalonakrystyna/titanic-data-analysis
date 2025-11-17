**Overview**
This project explores the Titanic passenger dataset using Python, pandas, and scikit-learn.
The goal is to perform data cleaning, exploratory data analysis (EDA), visualize key patterns, and build a simple predictive model for passenger survival.

**Objectives**
- Load and inspect the dataset
- Handle missing values
- Explore relationships between variables
- Visualize distributions and correlations
- Build a baseline ML model predicting survival
- Summarize insights
  
**Repository Structure**
titanic-data-analysis/
│
├── data/
│   └── titanic.csv
│
├── notebook/
│   └── titanic_analysis.ipynb
│
├── images/
│   └── charts.png      # any plots exported from the notebook
│
└── README.md

**Tools & Libraries**
Python 3.x
pandas
numpy
matplotlib / seaborn
scikit-learn
Jupyter Notebook

**Key Steps**
1. Data Cleaning
- Detect missing values
- Impute age using median
- Encode categorical variables
- Drop irrelevant columns

2. Exploratory Data Analysis
- Examples of questions explored:
- Do women survive more often than men?
- Does socioeconomic status (Pclass) affect survival?
- How age distribution differs between survivors and non-survivors?

3. Visualizations
- Histograms
- Countplots
- Heatmaps of correlation
- Scatterplots

4. Machine Learning Model
A simple model (Logistic Regression or RandomForestClassifier) trained to predict survival.
Metrics included:
- Accuracy
- Confusion matrix
- ROC-AUC

**Results Summary**
Women had a significantly higher survival rate than men.
Passengers in higher classes (Pclass 1) had better chances of survival.
Younger passengers tended to survive slightly more often.
The baseline ML model achieved solid accuracy (exact value depends on run).

**Contact**
Project maintained by Anna Stefańska.
If you have questions or suggestions, feel free to reach out.
