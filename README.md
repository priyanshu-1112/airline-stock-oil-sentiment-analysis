# Airline Stock – Oil Price & News Sentiment Analysis

This repository contains a university team project analysing the relationship between oil prices, financial news sentiment, and airline stock performance using Bloomberg data.

## Project Overview
This project investigates how oil price movements and financial news sentiment influence airline stock performance. The airline industry is highly sensitive to fuel prices, and investor sentiment can amplify market reactions.

The aim of the project was to analyse whether oil price shocks and financial news sentiment can help explain airline stock returns across major global airlines.

This work was completed as part of a team project for the MSc Business Analytics programme at Queen Mary University of London.

## Dataset
The dataset was collected using the Bloomberg Terminal and includes:

- Airline stock prices for 8 major global airlines (AAL, DAL, LHA, RYA, SIA, QAN, IAG, AI)
- Oil benchmarks (Brent and WTI crude)
- Bloomberg financial news sentiment scores
- Selected macroeconomic indicators

The dataset contains daily observations from 2018 to 2024 (around 1,600 trading days).

## Methods Used
The analysis involved several steps:

- Data cleaning and preprocessing
- Exploratory data analysis
- Correlation analysis
- Regression modelling
- Event study analysis

These methods were used to examine the relationship between oil prices, investor sentiment, and airline stock returns.

## Key Insights
Some key findings from the analysis include:

- Airline stock returns generally respond negatively to oil price increases.
- News sentiment provides additional explanatory power beyond oil price movements.
- The sensitivity to oil shocks varies across airlines and regions.
- Macroeconomic conditions can amplify the effects of both oil prices and sentiment.

## Repository Structure
```
README.md
analysis.ipynb

data/
    raw_airline_dataset.csv
    cleaned_airline_dataset.xlsx

report/
    project_summary.pdf
    full_research_report.pdf

## Team Code Notebooks

The folder `team_notebooks/` contains individual analysis python codes contributed by each team member.
```

## Tools Used
- Python
- Pandas
- NumPy
- Excel
- Bloomberg Terminal

## My Contribution
My main contributions to this team project included:

- Extracting financial and sentiment data from the Bloomberg Terminal
- Cleaning and structuring the dataset for analysis
- Supporting the statistical analysis and interpretation of results
- Assisting with the documentation of Bloomberg data access and methodology

## Authors
Dissertation(Group Project) – MSc Business Analytics  
Queen Mary University of London

Project Team:
- Priyanshu Choudhary
- Viraj Pahade
- Tu Anh Tran
- Shrey Jain
- Pooja Bhosale
