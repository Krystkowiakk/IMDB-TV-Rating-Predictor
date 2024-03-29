# IMDB TV Rating Predictor
###### METIS Data Science and Machine Learning Bootcamp 2022 by Krystian Krystkowiak
###### project/month(2/7) focus: REGRESSION
#### Code - scraping [GitHub](https://github.com/Krystkowiakk/IMDB-TV-Rating-Predictor/blob/60bfd533768c127be9c4e1829276ba51c021bad6/1.%20METIS_Krystkowiak_Krystian_Project_2_Regression%20-%20scraping.ipynb)
#### Code - cleaning&preprocessing [GitHub](https://github.com/Krystkowiakk/IMDB-TV-Rating-Predictor/blob/main/2.%20METIS_Krystkowiak_Krystian_Project_2_Regression%20-%20cleaning&preprocessing.ipynb)
#### Code - eda&regression [GitHub](https://github.com/Krystkowiakk/IMDB-TV-Rating-Predictor/blob/06f183158df96d5fe78f44f189b8cda11be0efdf/3.%20METIS_Krystkowiak_Krystian_Project_2_Regression%20-%20eda&regression.ipynb)
#### Presentation [GitHub](https://github.com/Krystkowiakk/IMDB-TV-Rating-Predictor/blob/72ef954c90fff0f1ec5b64aaf42d63157105691d/Project%20Presentation/Krystkowiak_Krystian_Project_2_Regression_on_IMDB_TV.pdf)

ABSTRACT

- Scraped data, used linear regression, lasso, and ridge regularisation to predict the  IMDB TV show ratings.
- The goal of this project was to use linear regression model to predict IMDB TV show user ratings and identify the factors that influence them. These insights can be useful for TV professionals and investors in making production planning decisions. The model can also be of interest to fans waiting for new shows, as it can help them estimate which shows are most likely to be highly rated.

To achieve this goal, I scraped data from https://www.imdb.com and combined numerical and categorical features in my analysis to create a linear regression model. It seemed that the relationships between the input features and the target variable may not be strong enough to make reliable predictions. Despite this, we were able to identify features that could potentially be more important. I used Matplotlib and Seaborn to visualize and communicate my results.

DESIGN

- Scrape data from IMDB website for TV shows released from 2000 to now (2022)
- Clean and process the data for use of linear regression model to predict IMDB ratings and identify factors influencing
- Visualize and communicate the results using Matplotlib and Seaborn plots

2000-present has been hailed as a new Golden Age of Television. Many people prefer to immerse themselves in the magic of moving pictures from the comfort of their own homes rather than visiting intimidating movie theaters.

Understanding the factors that shape IMDB TV show user ratings could help viewers save time and potentially improve the quality of TV shows produced in the future.

DATA

I scraped the data for this project from IMDb (https://www.imdb.com). The dataset contains 1335 rows with 10 features for each.
- Numerical: s01_episodes, avg_runtime, rel_date.
- Categorical: genres, MPAA certification, origin, company, creators, stars
The data covers the period from 2019-2021 to fucus on modern shows.

ALGORITHMS

- Scraped data from https://www.imdb.com
- Combined numerical and categorical features in analysis
- Used feature engineering techniques such as converting categorical features to dummy variables and searching for interactions
- Applied logistic regression, Ridge and Lasso regularization
- Split dataset into 75/25 train/test
- Evaluated model using R-squared score (0.096/-0.021 R-squared)
- Visualized and communicated results using Matplotlib and Seaborn

TOOLS

- BeautifulSoup for scraping data from IMDB
- Numpy and Pandas for data manipulation and preparation
- Scikit-learn and statsmodels for modeling and evaluating performance
- Matplotlib and Seaborn for visualizing and communicating the results of the analysis

COMMUNICATION

5-minute slide presentation.
The presentation was designed to clearly convey significant factors that influenced IMDB ratings and recommendations.

![IMDB TV Rating Predictor](files/cover.jpg)


