# IMDB Movie Analysis

[Imdb_movie_analysis](https://docs.google.com/spreadsheets/d/1O4o2c1ecv2xWnP6lFVSH8ggYQ_5yIFo0S79XXOmaOWg/edit?usp=sharing)

## Project Description:

This data analysis project focuses on discovering the key factors that influence the success of movies on IMDb, measured by the IMDb ratings, box office collections etc. For stakeholders like producers, directors, and investors in the film industry, being aware of these metrics is crucial for making data-driven decisions in their future projects. By exploring patterns and trends within the data, the actionable insights that can shape the strategies behind successful films.

## Approach:

step 1: Understanding the dataset and choosing the right tool for the analysis.

step 2: Prepare the data for analysis. Check for data quality, completeness and accuracy.

step 2: Identifying the business tasks and check if the data you have is sufficient or not.

step 3: Modify and rearrange the dataset, and add new columns if needed to suit your analysis.

step 4: Using the data, analyze and answer the key questions and solve the business tasks.

step 5: Provide insights to the stakeholders, supported by data visualization if needed.

**Data Cleaning:**

In the imdb movie dataset, 45 duplicate rows were removed.

There were missing data in some other columns, but the dataset was large enough for the analysis.

Calculated fields for duration intervals and profit margin were added to the dataset.

## **Tech-Stack Used:**

Google Sheets as a spreadsheet tool to format and analyze data.

Notion: It is a versatile tool that can be used for a variety of tasks, including project management, data analysis, and report generation as pdf.

## Insights:

### Business tasks:

A. **Movie Genre Analysis:** Analyze the distribution of movie genres and their impact on the IMDB score.

- **Task:** Determine the most common genres of movies in the dataset. Then, for each genre, calculate descriptive statistics (mean, median, mode, range, variance, standard deviation) of the IMDB scores.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled.png)

Comedy, drama and thriller movies were the most popular genres in terms of number of movies.

Considering the imdb ratings, and also considering a minimum number of 200 movies,

war, history and biography genres have 7+ rating average.

Variance and standard deviation suggests that the values are closely clustered around the mean.

**B. Movie Duration Analysis:** Analyze the distribution of movie durations and its impact on the IMDB score.

- **Task**: Analyze the distribution of movie durations and identify the relationship between movie duration and IMDB score.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%201.png)

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%202.png)

Movies were divided based on the duration to different intervals to suit the analysis.

Most number of the movies were 60 to 120 mins long with an average imdb rating of 6.24.

Standard deviation suggests that the values are closely clustered around the mean.

**C. Language Analysis:** Examine the distribution of movies based on their language.

- **Task:** Determine the most common languages used in movies and analyze their impact on the IMDB score using descriptive statistics.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%203.png)

As one might expect, English is the widely popular language in film industry with an average rating of 6.4.

French, Spanish and Hindi makes it to the top 4.

Since there’s a huge gap in the number of movies between English and other languages, we can’t conclude anything about the average rating.

**D. Director Analysis:** Influence of directors on movie ratings.

- Task: Identify the top directors based on their average IMDB score and analyze their contribution to the success of movies using percentile calculations.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%204.png)

As expected, Christopher Nolan movies has the highest imdb rating average of 8.43.

Quentin Tarantino and Stanley Kubrick also has 8+ average imdb rating.

Steven Spielberg has done 26 movies and still maintains 7.48 average rating which is appreciable.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%205.png)

Above are the percentile calculations of the average imdb rating of Directors.

It provides a metric for us to determine the best directors.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%206.png)

**E. Budget Analysis:** Explore the relationship between movie budgets and their financial success.

- Task: Analyze the correlation between movie budgets and gross earnings, and identify the movies with the highest profit margin.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%207.png)

Profit margin is calculated as the difference between budget and the gross revenue.

Above list shows movies with the highest gross profit.The movie Avatar ranks 1 in the list.

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%208.png)

A correlation coefficient of 0.1010334778 suggests a weak positive linear relationship between budget and gross revenue.The positive sign indicates that  when budget increases, gross revenue tends to increase slightly, but the relationship is not strong.

- **Comparing imdb ratings to the gross revenue to see if highly rated movies are always successful in terms of revenue.**

![Untitled](IMDB%20Movie%20Analysis%203cabb821faa64c3e8fd0cf6cea43fc93/Untitled%209.png)

The correlation coefficient in this case is 0.19 which doesn’t show a strong relation between the variables. 

## Result:

- Comedy, drama, and thriller are the most popular genres.
- War, history, and biography genres achieved an average IMDb rating above 7
- Most movie makers prefer film duration of 60-120mins.
- English language is the widely popular one in film industry.
- Christopher Nolan has the highest IMDb rating average, followed by Quentin Tarantino and Stanley Kubrick.
- A weak positive correlation coefficient indicates a slight increase in revenue with a higher budget.
- Avatar(2009) made the highest gross profit.

Based on the analysis of imdb movie data, several key findings that provide insights into the film industry. These findings collectively reveal interesting trends in various aspects, including genre preferences, the significance of movie duration, comfort of language, and notable influences from directors.

These findings provide valuable information for stakeholders in the film industry, enabling them to make data-driven decisions for their future projects.