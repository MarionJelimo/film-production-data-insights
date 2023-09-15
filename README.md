# Project Overview
## Business Problem

Microsoft intends to venture into creating original video content. They have decided to set up a movie studio in charge of creating movies. However, since they are new to this industry, they have tasked a data scientist to advice on what film they should make.

### Problem Statement

The task at hand is to explore what type of films are currently doing the best in the industry and tratranslate the findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

## Business Understanding

Successful movies frequently depend on a variety of elements, including genre, audience preferences, and market trends, as the film industry is quite competitive.  The goal of the data analysis will be to determine the best strategy for helping the studio choose genres and topics that are likely to optimize their chances of success and return on investment.
By clearly understanding what kinds of movies are currently succeeding at the box office, Microsoft's new movie studio will be able to:
- reduce risks by coordinating their output with established market patterns.
- maximize audience involvement and revenue.
- Create a solid basis for success in the cutthroat industry of filmmaking.

### Objectives

- To determine the most popular genres in the current market
- To determine the relationship between genre and popularity
- To determine the impact of release dates on the performance of a movie
- To identify competition in the market
- To provide insight on the type of film to create
- To provide recommendations and next steps for the business

## Data Understanding

There were 5 sources of data provided which were:
 - [Box Office Mojo](https://www.boxofficemojo.com/) 
 - [IMDB](https://www.imdb.com/)
 - [Rotten Tomatoes](https://www.rottentomatoes.com/)
 - [TheMovieDB](https://www.themoviedb.org/)
 - [The Numbers](https://www.the-numbers.com/)
 
The project utilises data from 3 sources:
- IMDB database files; `movie_basics` and `movie_ratings`tables
- `bom.movie_gross.csv`; a CSV file
- `tmdb.movies.csv`; a CSV file

### Summary of data used

***IMDB database*** 
The `movie_basics` table had 146,144 rows and 6 columns. Each row had the following information about a single movie:
 `['movie_id', 'primary_title', 'original_title', 'start_year', 'runtime_minutes', 'genres']`
They constitute the columns of the table.
From this table, the columns of interest were `movie_id`, `runtime_minutes` and `genres`

From the `movie_ratings` table, there are 3 columns: `['movie_id', 'averagerating', 'numvotes']` The column `movie_id` is the common key for both tables. The two tables were then combined into a joined table called `combined_data_table` with the following columns of interest:
`['movie_id', 'runtime_minutes', 'genres', 'averagerating', 'numvotes']`


***`bom.movie_gross.csv`*** 

***`tmdb.movies.csv`*** 

## Data Analysis


## Conclusions and Recommendations
