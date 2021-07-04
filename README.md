# IMDB-Movie-Data-Visualisation
**Assignment: Problem Statement**
We have the data for the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online. In this assignment, we will try to find some interesting insights into these movies and their voters, using Python.
**Objective:**  Need to perform exploratory data analysis(EDA) on given movies dataset to find some interesting insights into these movies and their voters, using Python.


**Steps to be followed:-**
1) Read the Movies Data : Import data into a dataframe 
2) Inspect the data : Check shape i.e. dimension of data, null values available in data, column wise info and also check statistical summary of data.
3) Data Analysis: Now that we have loaded the dataset and inspected it, we see that most of the data is in place. As of now, no data cleaning is required, so let's start with some data manipulation, analysis, and visualisation to get various insights about the data.
(a) Profit computation :
 => Here we will calculate 'profit' for each movie using 'gross' and 'bugdet' given.
 => Thus we can find top 10 most profitable movie.
 => Plotted 'profit' vs 'budget' scatter plot to visualize how the movie's profit varies with budget.
 (b) Rating or score calculation: 
 => We are required to find out the highest rated movies which have been liked by critics and audiences alike using MetaCritic and IMDb_rating.
  (c) Find the Most Popular Trios: Using facebook likes of these actors.
 4) Demographic analysis:
 => We will find out top 10 genres based on votes. We can use this to extract exciting insights about the voters.
 => Since we have the vote counts for both males and females, across various age groups, let's now see how the popularity of genres vary between the two genders.
 => We will use heatmap to find out inferences about voting and rating gender wise.
 => Also we will visualize how both the US and the non-US voters have responded to the US and the non-US movies using box plots.
 => We will explore how top 1000 voters have voted across the genres using bar plots.
