# Los Angeles Crime Data Analysis using Machine Learning

![Los Angeles Crime Data Analysis]([https://github.com/rkukreja24/Crime-Rate-Prediction-in-LA/blob/main/crimes_in_LA.png])

This project explores the use of machine learning algorithms such as K-Means Clustering and Random Forest to analyze crime data from the city of Los Angeles. The goal of our project is to gain a better understanding of the patterns in crime across Los Angeles and to build predictive models that can be used to identify what type of crime could be committed based on certain parameters.

## Introduction
The Crime in Los Angeles dataset contains information on criminal incidents that occurred within the city of Los Angeles from the past several years. This project was conducted by Deepak Bhadouria, Ritu Kukreja, and Surendra Pothuri as part of their work at Drexel University in Winter 2023.

## Dataset
The dataset used for this analysis was obtained from the Los Angeles Police Department's Crime Mapping and Analysis Website. It contains over 1.6 million records and includes various attributes such as date, time, location, crime type, victim information, and more.

## Exploratory Data Analysis
The dataset underwent preprocessing and exploratory data analysis to clean and prepare it for machine learning modeling. Key steps included data cleaning, handling missing values, and filtering the data to remove irrelevant records. Some of the insights gained during EDA are highlighted in the project report.

## Methodology
### Feature Engineering and Selection
- StringIndexer and OneHotEncoder were used for encoding categorical features.
- VectorAssembler was used to combine relevant features into a single vector for modeling.

### Machine Learning Modeling
Two machine learning models were built:
1. **K-Means Clustering**: To group data based on similarity between features using Euclidean distance.
2. **Random Forest Classifier**: To predict crime type based on various attributes.

## Results
The project's findings and results are summarized in the report. Notably, K-Means Clustering showed strong similarity between data points, while the Random Forest Classifier achieved an accuracy of 50%.

## Conclusion and Future Work
The project concludes by highlighting the effectiveness of the K-Means algorithm in measuring similarity and the Random Forest model's moderate performance in crime type prediction. Future work may include further data cleaning, feature extraction, and exploring other machine learning algorithms.

--

