### Table of Contents

1. [Installation](#installation)
2. [Project Summary](#summary)
3. [File Descriptions](#files)
4. [Summary of Results](#results)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

Libraries used: 
Pandas
Numpy
Math
Json
Matplotlib
Sklearn

## Project Summary <a name="summary"></a>

A Capstone Project on the Starbucks dataset for the Udacity Data Scientist Nanodegree program. This project aims to develop a machine learning model that classifies whether a user will be responsible to a certain type of offer, based on several independent variables.

## File Descriptions <a name="files"></a>

There are three datasets - portfolio.json, profile.json and transcript.json.

portfolio.json — Contains offer ids and meta data about each offer (duration, type, etc)
profile.json — Demographic data for each custmer
transcript.json — Records for transactions, offers received, offers viewed, and offers completed

## Summary of Results <a name="results"></a>

The resulting model using Random Forest Classifier was able to correctly classify a customer 68.3% of the time. The best model was determined using cross validation score and grid search CV to determine the best parameters for this classifier.


