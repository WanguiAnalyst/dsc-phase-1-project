# Phase 1 Project
Student Information
* Student name: Jane Mwangi
*	Student pace: Part-time
*	Scheduled project review date/time: Monday, 24th July 2023
*	Instructor name: Stella Waithera

## Project Overview

For this project, you will use exploratory data analysis to generate insights for a business stakeholder.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

From the above folder the following are the datasets I used for my analysis.

* Movie Budgets
*	Tmdb.Movies
*	Title.Basics


## Method
1.	Data Mining: Identifying data that would answer the business question.
2.	Loading of Libraries
3.	Data Cleaning: Checking for missing values, duplicates, outliers, valid labels, and using up-to-date data to ensure maximum value of the results.
4.	Data Exploration (Exploratory Data Analysis): Highlighting patterns and relationships in data using descriptive statistics such as mean.
5.	Data Visualization: Creating plots such as histograms, scatter plots, and line graphs to identify trends and gain insights.

## Loading All the Datasets

## Data Cleaning and Preprocessing

## Data Merging

## Data Visualization / Results

* Matrix Heatmap
The heatmap provides a quick overview of the patterns and relationships between the selected numerical columns.

![Heatmap](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/9e345854-6a91-4142-a858-836dc5899440)

* Scatter Plots
Scatter plots show a side-by-side comparison of the Domestic ROI (D_ROI) and Worldwide ROI (W_ROI) against the index values of the 'movies_merged' data.

![Scatter 1](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/465aded2-30aa-4dd5-8b33-b4306faeac37)


* Filtered Scatter Plots
Filtered scatter plots show the Domestic ROI and Worldwide ROI after removing the outliers.

![Scatter2](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/51f08798-cef7-4aab-a1e7-2011eeb49878)


* Top 20 Genres vs. Domestic and Worldwide ROI with the highest mean Domestic ROI.
The scatter plot will help us to visually observe any patterns or relationships between Domestic ROI and Worldwide ROIs within the selected genres.

![Scatter 3](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/802cfb42-b3c8-4ded-af3e-1813813afd07)


* The following Scatter plot depicts the relationship between popularity and genres.

![Scatter4](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/4faf4851-f4d5-461a-8721-5b23e65d7e7e)



* Top 20 Genres vs. Domestic and Worldwide ROI
Bar plots show the performance of the top 20 movie genres based on their mean Domestic ROI, Worldwide ROI, and popularity.

![Barplot1](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/2a20251d-d039-4da0-8aa9-599da367644e)


* Languages vs. Frequency & Popularity
Bar plots compare the top five languages and their relationship with popularity.

![Barplot2](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/71e1826e-9577-46c0-9791-79d556b2e9e3)


* Top 20 Original Languages vs. Domestic and Worldwide ROI
Bar plots show the relationship between Return on Investment and the top 20 original languages.

![Barplot3](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/b80fae61-55d6-4635-bbc7-832628352710)


* Runtime vs. Popularity
A scatter plot illustrates the relationship between the runtime of a movie and its popularity.

![Scatterplot5](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/34a3e372-0023-4544-8b08-ca41b6d18695)


* Release Year vs. Average ROI
Line plots compare the average ROI for both the domestic and worldwide movie markets over the years.

![Lineplot1](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/125726694/40f84207-9da8-4b4b-a00d-eb8bdbdfbeaf)


## Recommendations
* Focus on Genres with High Domestic ROI: Concentrate on genres like 'Comedy, Documentary,' 'Comedy, Horror,' and 'Action, Comedy, Fantasy' that have historically shown high performance in the domestic market.

* Explore Genres with High Worldwide ROI: Consider genres like 'Action, Horror, Sci-fi' that have demonstrated exceptional worldwide performance for potential global success.
  
* Leverage Popularity of Action Movies: Incorporate action elements into various genres to capitalize on the high popularity of action films.

* Language Selection: English and Chinese movies have consistently achieved high ROI worldwide. Expanding into the Chinese market can enhance global reach.

* Caution with Production Budget: Be mindful of budget allocation, as higher production costs do not guarantee a high ROI. Prioritize engaging storytelling and effective marketing.

* Balance Domestic and Worldwide Focus: As the domestic market's average ROI declines, maintain a balanced approach between domestic and international film productions to ensure overall success and diversity in the movie portfolio.

## Conclusion

The analysis of the movie industry data offers valuable insights for Microsoft's new movie studio. By identifying genres with high domestic and worldwide ROI, the studio can strategically focus on producing successful films for both markets. Action movies, being popular, present promising investment opportunities, and exploring genres like 'Action, Horror, Sci-fi' can lead to global success. 

However, caution is necessary regarding the relationship between production budgets and ROI, as other factors influence a movie's financial success. Understanding market trends and making informed decisions based on historical data can increase the chances of creating profitable films.

Acknowledging the declining domestic ROI trend while recognizing higher worldwide ROI, the studio should balance domestic and international film releases for optimal success in the competitive movie industry. A data-driven approach and understanding of market dynamics can position Microsoft's movie studio for positive impact and growth in the entertainment landscape.
