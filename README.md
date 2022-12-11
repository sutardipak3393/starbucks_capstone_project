# starbucks_capstone_project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>


Must runing with Python 3 with libraries of numpy, pandas, matplotlib, seaborn and sklearn libraries.

## Project Motivation<a name="motivation"></a>

This project is created to answer following questions

1. What is the income range where the most of the customers falls? Whats is minimum and maximum income of Starbucks Customers?
2. Which age group and gender uses the Starbucks app the most?
3. What types of offers are mostly offered by the Starbucks?
4. What Type of offer the customers attracted towards (i.e. customers completes these offers)?
5. Prediction of if the customer will complete or offer or not.


## File Description <a name="files"></a>

There is a notebook provided
1. Starbucks_Capstone_notebook.ipynb -  This provides data analysis from understanding the data, preprocessing and visualisations of the same and after that drawing consusions from the results obtitained. Also implements model for predicting whether the customer will complete the offer or not.

The data folder contains following three dataset json files
1. portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
2. profile.json - demographic data for each customer
3. transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Results<a name="results"></a>

The classfication model we have used here is giving 81% overall accuracy for detection customer will complete an offer or not.

The detailed analysis can be found in this [blog](https://medium.com/@das.academics/starbucks-offers-analysis-and-prediction-287652bef94b).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Starbucks to make the data available and Udacity for providing the same.