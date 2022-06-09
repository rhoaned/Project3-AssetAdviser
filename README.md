# Project3-AssetAdviser
![roboadvisor](https://inc42.com/wp-content/uploads/2021/05/Robo-Advisor-Feature.jpg)  

## Robo-advising utilising Sentiment Analysis, Fundamental analysis and Technical analysis

## Include the name of the project and group members.

- Rhoan Edwards
- Coen Emmenegger
- Kseniya Chadayeva
- Aaron Simpson


## Motivation & Summary Slide
We want to investigate usefullness of setiment analysis in conjunction with fundamental and technical indicators for asset selection and automate buy/sell recommendations for clients based on their preference and risk tolerance.

## Project Overview

This project primary aim is to provide the most up to date trading signals to our end users as possible! Our team are able to deliver this through chatbots which utilise sentiment analysis, technical analysis and price action to determine the trade recommendation for certain asset classes.


## Model Summary
The model utilises multiple different technologies to produce the following:

- Chatbots
- Visualization
- Machine Learning Model
- Natural Language Processing
- Price Comparison
- Back testing models


## Predictive Models and Data
Our team utalised the following technology to deploy our predictive models.

- NLP
- Classification
- Vader
- sklearn
- StandardScaler
- SVM

The standard scaler to scale the data was the best to use as handling financial data based on current best practices.

## Tools Used
- AWS LEX/Lambda for chatbot
- Yahoo finance and Cryptowatch to gather fundamental and technical indicators
- NLTK to create sentiement analysis
- SKlearn for machine learning 

## Data Cleanup & Model Training
Our team utilised exhisting functions within pandas to clean data of all nuls and NAN boxes. 
Model training utalised the sklearn package to create expected results from training data.

## Data used for Fundamental and Techica Analysis

### Fundamental Indicators
 *To be gathered using Yahoo Finance package
 
 *At least 20 biggest US stocks by market cap will be explored
 - P/E
 - EV/EBIT
 - EV/EBITDA
 - P/Sales
 - BV
 - Div Yield

Using Cryptowatch API we allow our users to pull pricing data for over ~6000 assets. 

### Technical Indicators

- Moving Average (MA) for different time spans
- Momentum indicator (MOM)
- Trading Volume (VOL)

## Exploration and Cleanup Process.

Utilise APIs to pull data from at least the last 2 years into python dictionaries and then into CSV formatted files for easy data manipulation and visualisation.

After relevant calculation for economic and technical indicators are performed, model for buy/sell decision will be created with specific percentag weighting across 3 types of analysis outcome.

News APIs were used to pull news articles for specific keywords and based on those cleaned up the data and applied the Vader sentiment analysis to determine compound scores.


## Learning Opportunities

Preparing the data was arguably the most difficult portion of the excercise because of the high fees involved with pulling financial data from data aggregators!   
Other challanges involved training models which require as much data as possible to make accurate predictions. However, fixing the above point influenced the outcome of data available. 

## Cloud resources used, training time required, issues with training.

All of our models do not have much data to digest and provide a forecast incredibly quickly. However, creating a great foundation was the objective which was achieved and now the next steps are to gain more data for the machines to process.  

## Model Evaluation
https://user-images.githubusercontent.com/95939850/172811526-3f700030-0437-4a41-b1b3-68b098fb973c.mov


## Model Performance.
Our team utalised standard analytical analysis to evalute model performance. This performance was measured with the following:
- SMA
- Sharpe Ratios
