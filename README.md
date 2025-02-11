# COVID-19 Tweet Sentiment Analysis

## Goal: 
Investigate whether the sentiments of Twitter comments surrounding COVID-19 were more positive or negative the day of or a few weeks after states began implementing major shutdowns on March 15, 2020. 

## Map of Documentation
```mermaid
graph TB
  A[covidproject]
  A1[README.md]
  A2[LICENSE.md]
  B[SCRIPTS]
  B1[EDA Pre Analysis.ipynb]
  B2[covid_EDA.ipynb]
  C[DATA]
  C1[Corona_NLP_test.csv]
  C2[Corona_NLP_train.csv]
  C3[Data Appendix]
  D[OUTPUT]
  D1[figures]

  A --> A1
  A --> A2
  A --> B
  B --> B1
  B --> B2
  A --> C
  C --> C1
  C --> C2
  C --> C3
  A --> D
  D --> D1
```

## Instructions for Reproducing Results
