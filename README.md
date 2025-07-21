# TMDb-Movies-EDA
Project: Investigate a Dataset - TMDb movies
Table of Contents
Introduction
Data Wrangling
Exploratory Data Analysis
Conclusions

Introduction
Dataset Description
In this report, I will be analysing tmdb-movies.csv. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

The dataset contains the following columns:

id: an integer representing the unique ID for the movie within the dataset.

imdb_id: a string representing the movie's ID on IMDB (if available).
popularity: a float representing Popularity score for the movie on TMDB.
budget: an integer representing the budget of the movie in USD.
revenue: an integer representing the revenue of the movie in USD.
original_title: a string representing original title of the movie.
cast: The cast of the movie containing multiple values separated by |.
homepage: a string representing the URL of the official website of the movie.
director: a string representing the name of the direction of the movie.
tagline: a string representing the tagline of the movie, which is a short phrase or sentence used to advertise the film and capture the audience's attention.
keywords: The keywords associated with the movie separated by |.
overview: a string representing a short summary of the movie plot.
runtime: an integer representing the runtime of the movie in minutes.
genres: The list of genres the movies belongs to separated by |.
production_companies: The list of companies that produced the movie separated by |.
release_date: The release date of the movie in format month/day/year.
vote_count: an integer representing the vote count of the movie.
vote_average: a float representing the average votes of the movie.
release_year: The year of release of the movie.
budget_adj: The budget of the movie in terms of 2010 USD, accounting for inflation over time.
revenue_adj: The revenue of the movie in terms of 2010 USD, accounting for inflation over time.
Question(s) for Analysis
The aim of this analysis is to answer questions including:
What movie lengths are most liked by audiences according to their popularity?
Is a higher budget associated with a higher revenue?
Who holds the record for the most frequent appearances in movies?
Which movies has the highest and lowest profit?
Which genres were produced the most and which were the most popular?
Which production company has the highest # of releases over the years?
How does runtime and vote average correlate?
Which day of week does have the highest number of releases?
How do budget and release year together affect revenue?
