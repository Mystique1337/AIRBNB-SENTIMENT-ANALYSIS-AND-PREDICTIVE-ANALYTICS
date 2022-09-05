# AIRBNB-SENTIMENT-ANALYSIS-AND-PREDICTIVE-ANALYTICS
**Datasets**:

[Air-bnb-reviews-top 50 cities](https://drive.google.com/file/d/14-NIljR74Imltim1NRicvAG3QylzaiQa/view?usp=drivesdk)

**Description**: This dataset collects information about various reviews by different users of airbnb in the top 50 cites in the US with every detail associated with the data

[Air-bnb-users-top 50 cities](https://drive.google.com/file/d/1e5JpzUd5TkFhddqgy2IYMl0a6MkCZfkX/view?usp=drivesdk)

**Description**: This dataset collects information about users across the top 50 users of Air BnB int the US.

[Air-bnb-listings-top 50 cities](https://drive.google.com/file/d/1yN7p3TLJM4ws-xUcfh8H6F46Au9O7nfB/view?usp=drivesdk)

**Description**: This dataset collects information about various listings of Airbnb

[Data Dictionary](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit?usp=sharing)

The Data dictionary describes all the features in the data set.

Data Wrangling and preprocessing, Sentiment Analysis and Predictive Analysis was done in this [notebook]('www.xxx.xxx') and the dataset containing just the negative reviews and users was selected for this analysis

The following was deducted from the analysis
Location
1. The state with most negative reviews is California
2. Cities that are popular tend to have the most negative reviews

**Age**
1. The distribution of age is rightly skewed  but centered around 30 years of age
2. This is highly expected as youths tend to Use Airbnb often

**Gender**
1. 78% of users giving the negative reviews are men and 22% are women
2. It is highly expected as men tend to host their female partners more often

**Race**
1. The largest proportion of users giving negative reviews are whites
2. This is also expected as the remaining groups are minorities in the US

**First Time Users**
1. Almost all the negative reviews came from new users.
2. The experienced users hardly give a negative review

**Rating vs Sentiment**
1. A huge percentage of negative reviews have positive ratings
2. The ratings cannot be trusted as means of analysing the set  


**LIMITATIONS**

1. The dataset is very large, a random sample was selected to manage computation resources.

2. The data was not totally consistent, some unusual forms of data and irregularities were found which could have affected the analysis because it was dropped.

3. Most of the columns are categorical, hence the use of Bar charts and Pie charts, Only Age was quantitative and could be visualised with appropraite means.

4. The Location Data should have included the gographical coordinates for better analysis as to how a location can affect the choice of the patient.

5. The dataset is incomplete as a machine learning model was used to predict the demography of the users

**RECOMMENDATION**


1. A more complete dataset to include the demographic profile of the users as the Machine Learning model is 93% accurate
2. The computation required a lot of resources due to the use of Machine learning models to get features.
3. Geolocation data will make the analysis easier.
