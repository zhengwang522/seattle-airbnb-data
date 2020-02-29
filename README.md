# airbnb-seattle-data

This repository designated for a project that analyzes a dataset which contains 2016 Seattle Airbnb data. This dataset is available and downloadable from Kaggle https://www.kaggle.com/airbnb/seattle. 

In this project, several business questions were proposed and answered through data exploration. A detailed write-up for this project is available on Medium https://medium.com/@zhwang.btbu/airbnb-listings-in-seattle-6006a8d36ddd

## Install

The code is written in Python 3 with Jupyter Notebook. A set of libraries used in this analysis include numpy, pandas, matplotlib, seaborn, and NLTK. Execute the following code in a Notebook cell to install NLTK:
`nltk.download()`

## Data

Data used in this project are included in the \data folder.
It includes three data files 'calendar.csv', 'listings.csv', and 'reviews.csv'. A detailed description on these files can be found at the Kaggle link provided in the first paragraph of this readme file.

## Data handling

There are few data cleaning steps under data preparation. No special handling was done for missing data or categorical variables since they're not required to answer the proposed questions.
