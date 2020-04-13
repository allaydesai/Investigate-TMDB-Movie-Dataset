# Investigate-TMDB-Movie-Dataset
Use numpy, pandas and matplotlib to investigate a dataset

UDACITY | Data Analyst Nanodegree Program

---

### OVERVIEW

In this project we will be analyzing data associated with imdb movie reviews from the year 1960 to 2015. In particular we will be looking at how the popularity of various genres have changed over time. Further we will be investigating the various attributes which make a movie successful. Is it possible to predict the success of a movie before its released? How has the runtime of movies varied? These are some of the questions we look to answer.

### PROJECT FILES
<ul>
  <li>TMDb_MovieDataset_Analysis.ipynb</li>
  <li>TMDb_MovieDataset_Analysis.html</li>
  <li>tmdb-movies.csv</li>
</ul>

### DATASET

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Dataset Link: https://www.kaggle.com/tmdb/tmdb-movie-metadata/data

Cleaned version of the above dataset was provided by udacity for the purpose of this project so it may not exactly match. 

| Column Name   |
|----------|
| id |
| imdb_id |
| popularity |
| budget |
| revenue |
| original_title |
| cast |
| homepage |
| director |
| tagline |
| keywords |
| overview |
| runtime |
| genres |
| production_companies |
| release_date |
| vote_count |
| vote_average |
| release_year |
| budget_adj |
| revenue_adj |

### DATASET CLEANUP
<ul>
  <li>1. Drop unwanted columns</li>
  <li>2. Drop rows with some columns containing null value</li>
  <li>3. Drop duplicate rows</li>
  <li>4. Fix numerical columns with 0 values</li>
  <li>5. Split all the columns containing seperator '|'</li>
</ul>

### RESEARCH QUESTIONS
<ul>
  <li>1. Which genres have been successful over the years?</li>  
  <li>2. What are the attributes of a successful movie?</li>
  <li>3. How has runtime of movies changed over the years?</li>
  <li>4. What is the relation between vote count and rating?</li>
  <li>5. What keywords have trended over the years?</li>
</ul>

### RESULTS

To conclude this research lets summarize the findings. The goal of this research was to explore a dataset comprising of last 45 years of various movie attributes. There were 5 questions which were posed and here are the findings:

1. Which genres have been successful over the years?
> The comedy genre was most successful over the years followed closely by drama and action.

2. What are the attributes associated with succesful movies?
> There are few cast, director, genre and production company that seldomly showed up in movies that were a financial success. It was also found that most successful movies made a profit of about 195 million and had an average vote of 6.4

3. How has runtime of movies changed over the years?
> It was found that most movies had a runtime of 103 minutes, with 25% being in the 90 minutes timeframe and 75% in 122 minutes timeframe.

4. What is the relation between vote count and rating?
> Upon analysis of data it was found that movies with a higher vote average did not directly relate to number of votes it received

5. What keywords have trended over the years?
> 1960's and 1970's had the same keyword trending "based on novel". Thereafter the keyword for next decade is "nudity" in 1980s followed by "independent film" in 1990s and "feature women director" in 2000s

The dataset is quite intresting and there were few unexpected findings as well as others which confirmed our assumptions.

The results disclosed above are strictly based on the dataset and the analysis is generalized.





