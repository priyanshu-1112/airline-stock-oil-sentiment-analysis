# Airline Stock – Oil Price & News Sentiment Analysis

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
data/
    raw_airline_dataset.csv
    cleaned_airline_dataset.xlsx

report/
    project_summary.pdf
    full_research_report.pdf
```

## Tools Used
- Python
- Pandas
- NumPy
- Excel
- Bloomberg Terminal

## My Contribution
Data extraction using Bloomberg Terminal, data cleaning, and supporting the statistical analysis and interpretation of results.

## Authors
Dissertation(Group Project) – MSc Business Analytics  
Queen Mary University of London

Project Team:
- Priyanshu Choudhary
- Viraj Pahade
- Tu Anh Tran
- Shrey Jain
- Pooja Bhosale
