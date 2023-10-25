# BC-Project-1

https://docs.google.com/document/d/1aj4YUjle8D72KxIfCXJYWiW79JSaRPFPPV4EiBvLJp4/edit?usp=sharing

Project Title: The Fantastic Four’s take on the Amazing World of Movies!

Team Members:
Anita Kumar
Carter Jackson
Omar Khan
Mita Joshi

Project Description/Outline
 The goal for this group project is to fetch movie data from multiple sources, clean the data, merge it together, and look for correlations based on rating, time, gross, and actors, then represent that data through strong visualizations.


Tasks
Fetch movie data set through API call and clean the data
Identify movies by their ID# and fetch details about the movies 
Create a master data frame for further analysis
Obtain Oscar awards dataset and import that into a dataframe
Merge above data frames around Movie name & release year
Add iMDB ratings column to Oscar dataframe
Then merge above dataframe with Oscar dataframe for further analysis
Store image plots to png file
Identify international winner over past decade(or longer duration) and obtain the winning country’s lat-lng of the capital [obtain coords via API call]
Map those cities on world map 
Create presentation deck
Analysis Report


Research Questions to Answer
Incorporate boxplots to identify outliers for budget or some such similar quantifier towards movie’s success
Some angle on the genre of the movie - some analysis: over time what genres have gotten more popular and which ones are less popular over time.
Correlation between profitability and actor names. 
Find correlation between budget & popularity or box office earnings
Find correlation between iMDB rating & movies that receive Oscar awards 
Identify international winner over past decade(or longer duration based on available data) 
Identify 10-15 movies which have 10/10 iMDB rating and locate their origin country on map and print the capital city points on the world map
Identify movies that won both Oscar & Academy awards and try to find the factor that most influenced their success
What kind of movie user would like to watch? 
Correlate runtime of movies with popularity/box office earnings 
Group the rows in dataframe by country name and Map them on the worldmap 

Datasets to Be Used
https://developer.themoviedb.org/reference/movie-details
Kaggle Oscars dataset (CSV file) (https://www.kaggle.com/datasets/unanimad/the-oscar-award)
Kaggle Golden Globe dataset (https://www.kaggle.com/datasets/unanimad/golden-globe-awards)

Rough Breakdown of Tasks

Anita Kumar
Fetch movie data set through API call and clean the data
Identify movies by their ID# and fetch details about the movies 
Create a master data frame for further analysis


Carter Jackson
Obtain Oscar awards dataset and import that into a dataframe
Merge around Movie name & release year
Add iMDB ratings column to Oscar dataframe
Omar Khan
Then merge above dataframe with Oscar dataframe for further analysis
Store image plots to png file
Identify international winner over past decade(or longer duration) and obtain the winning country’s lat-lng of the capital [obtain coords via API call]
Mita Joshi 
      -     Map those cities on world map 
Create presentation deck
Analysis Report


Disclaimer: Research questions, tasks & datasets might be added/deleted to/from above list. 


# Data Analysis Report (All visuals can be found in https://docs.google.com/document/d/15dxeq_y3M68ayFLfHpdN4pTsG4AbOcVhJAVUuah4G1w/edit)

## Introduction
Our group project aims to source movie data from various platforms, streamline and consolidate this information, and then identify correlations concerning rating, time, genres, production countries, award wins, and gross revenue involvement. We will then present our findings using compelling visualizations. ​

In our project, we conduct various types of tests, including hypothesis testings to examine different hypotheses across different combinations of movie data. We also seek correlations between different aspects of movie data and create bar graphs and stacked bar graphs to identify specific trends in our movie analysis data.
The code processes a dataset that consists of nearly 8000 movies after the data has been cleaned, and it accomplishes this by randomly selecting 1000 movies at each instance. We've executed our code more than 15 times, each with different data samples, leading to the discovery of trends related to specific aspects of the data.
In order to present our findings, we offer two visual representations of our analysis. These visuals are created by running our code with different random sample datasets.

## Top 10 Grossing Movies in the past 100 years
We took a look at the top ten grossing movies in the past century with the plots in the link.

## Production Country Analysis
Movies are most frequently produced in the ten countries pictured in the linked file. This observation is representative of two different sample data sets from the initial movie list.

## Number of Movies per Decade
Production of movies peaked in the 2000s as shown in the linked file. It increased every year from 1920-2000 consistantly throughout our data pulls.

## Movies per Budget Category
Over 80% of movies observed in our sample set are made with a budget in the low budget category. Less than 10% of movies observed in our sample set are made with a budget in the average budget category. Less than 2% of movies observed in our sample set are made with a budget in the high budget category.

## Analysis of Movies per Budget Range by Decade
Production of movies peaked in the 2000s as shown in the linked file. It increased every year from 1920-2000 consistantly throughout our data pulls.

## Analysis of Number of Movies Produced based on their Primary Genre
Data seems to vary largely every time a sample is pulled. The pie charts displayed in the link show the top three movie genres.

## Analyzing the Distribution of Budget Data
The budget data is not normally distributed as depicted in the linked histograms.

## Analyzing Runtime of Movies over the Past Century
There is a very weak negative relationship between the runtime and year of the movies.
The runtime of the movies has slightly reduced over the past century.

## Analyzing the correlation between budget and TMDB rating of movies
Based on the statistics in linked document, there is no correlation between the budget of movies and their TMDb ratings in this sample dataset. This suggests that factors other than budget have a more substantial impact on a movie's TMDb rating.

## Analyzing the correlation between budget and IMDb rating of movies
There is a weak relationship between the budget and IMDb rating of movies. The overall trend in this sample dataset suggests that budget alone is not a strong predictor of IMDb ratings.

## Analyzing the correlation between Revenue vs IMDb Rating
The positive correlation depicted in the linked document, suggests that, on average, movies with higher revenue tend to have slightly higher IMDb ratings.

## Analyzing the correlation between Revenue vs Runtime
There is a weak positive correlation between runtime and revenue of movies. This suggests that, on average, longer movies tend to generate slightly higher revenue.

## Runtime Outliers over the Decades
Interpreting a clear trend from the box plot in the linked document is challenging. However, we do notice that the median runtime for movies produced from 1970 to 2010 falls within the range of 100 to 120 minutes. It's worth mentioning that we also observe some outliers in the data, which have influenced the values displayed in the box plot.

Furthermore, it's important to note that with each execution of the code, we obtain a completely different box plot due to the variability in the data samples. Consequently, drawing any definitive conclusions from these plots is a challenging task.
