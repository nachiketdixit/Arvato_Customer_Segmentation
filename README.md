## Arvato Customer Segmentation Report - A Data Science Capstone Project
Arvato is an internationally active services company that develops and implements innovative solutions for business customers from around the world. These include SCM solutions, financial services and IT services, which are continuously developed with a focus on innovations in automation as well as data and analytics.

## Table of Contents
- [Project Overview](#project-overview)
- [Description](#description)
- [Datasets](#datasets)
- [Technical Overview](#technical-overview)
- [Results](#results)
- [Acknowledgement](#acknowledgement)

## Project Overview
In this project, the demographic data of the German population and the customer data have been analyzed to perform Customer Segmentation and Customer Acquisition. The goal of this project was to characterize the customer segment of the population, and to build a model that will be able to predict customers for Arvato Financial Solutions

## Description
The Project is divided in the following Sections:
1. Customer Segmentation Report: In this section, a thorough data analysis and feature engineering steps are performed to prepare the data for further steps. A Principal Component Analysis (PCA) is performed for dimensionality reduction. Then K-Means Clustering is performed on the PCA components to cluster the general population and the customer population into different segments. These clusters are studied to determine what features make a customer with the help of cluster weights and component weights.

2. Supervised Learning Model: In this section, the customers data with defined targets indicating the past responses of the customers has been used to train Supervised Learning algorithms. The trained model is used to make predictions on unseen test data to determine whether a person could be a possible customer.

## Datasets
The data is provided by Bertelsmann Arvato Analytics.
1. `AZDIAS` — Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
2. `CUSTOMERS` — Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
3. `TRAIN` — Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
4. `TEST` — Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Additionally, there were 2 more files for describing attributes:
1. `DIAS Attributes Values` — Explains values encoding.
2. `DIAS Information Attributes` — Explains column names meanings.

## Technical Overview
The project has covered various technical steps which include:

1. Exploratory Data Analysis
2. Data Preprocessing (Feature Engineering)
3. Dimensionality Reduction (PCA)
4. K-Means Clustering
5. Supervised Learning
6. Model Evaluation
7. Predictions on Test data

## Results
The main findings of the code can be found at the post available at [medium](https://medium.com/@nachiket.dixit/targeting-potential-customers-effectively-d76a783b5dd1)

## Acknowledgement
Must give credit to [Arvato Bertelsmann](https://www.bertelsmann.com/divisions/arvato/#st-1) and [Udacity](https://www.udacity.com/) for providing the data.
