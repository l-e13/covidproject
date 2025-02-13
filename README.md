# COVID-19 Tweet Sentiment Analysis

## Goal: 
Investigate whether the sentiments of Twitter comments surrounding COVID-19 were more positive or negative the day of or a few weeks after states began implementing major shutdowns on March 15, 2020. 

## Software and Platform Section
**Types of Software Used:**
  - Programming Language: Python
  - Data Processing & Analysis: Pandas
    - Reading, cleaning, and filtering the dataset
    - Aggregating tweet counts and sentiment scores
  - Natural Language Processing (NLP): NLTK (VADER)
    - Used nltk (Natural Language Toolkit) library 
    - Sentiment analysis using VADER
      - Assigns a compound sentiment score to each tweet
      - Helps understand public mood about topic
      - Documentation for the VADER package: https://www.geeksforgeeks.org/python-sentiment-analysis-using-vader/. 
  - Data Visualization: Matplotlib & Seaborn
    - Creating bar charts, scatter plots, and other custom visualization aesthetics
  - Data Storage & Export: CSV Files
  - Cloud Computing: Google Colab
    
**Packages Installed:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - nltk
    
**Platforms Used:** Windows & Mac

## Map of Documentation
```mermaid
graph TB
  A[covidproject]
  A1[README.md]
  A2[LICENSE.md]
  B[SCRIPTS]
  B1[EDA Pre Analysis.ipynb]
  B2[covid_EDA.ipynb]
  B3[Analysis.ipynb]
  B4[filtering for US and appending VADER.ipynb]
  C[DATA]
  C1[Corona_NLP_test.csv]
  C2[Corona_NLP_train.csv]
  C4[df_us_with_sentiment.csv]
  C3[Data Appendix]
  D[OUTPUT]
  D1[figures]
  D2[Analysis Figures.pdf]
  D3[EDA Figures.pdf]

  A --> A1
  A --> A2
  A --> B
  B --> B1
  B --> B2
  B --> B3
  B --> B4
  A --> C
  C --> C1
  C --> C2
  C --> C3
  C --> C4
  A --> D
  D --> D1
  D --> D2
  D --> D3
```

## Instructions for Reproducing Results

## References
[1] GeeksforGeeks. (2024, December, 11). “Sentiment Analysis using VADER” [Online]. Available:
https://www.geeksforgeeks.org/python-sentiment-analysis-using-vader/


[2] Datatattle. (2020). “COVID-19 NLP Text Classification Dataset” [Online]. Available:
https://www.kaggle.com/datasets/datatattle/covid-19-nlp-text-classification

