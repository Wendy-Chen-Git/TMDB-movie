# TMDB-movie
• Dataset: TMDb movie data

• A statement of the question(s) you posed & a description of what you did to investigate those questions
1. Which genres are most popular from year to year: To solve this problem what I need to find the most popular genre each year. 
2. What kind of properties are associated with movies that have high revenues: To solve this problem, I need to find some properties may associated with revenues and use data visualization to have a closer look at the correlation.

• Which genres are most popular from year to year?
1. Cleanthecolumn‘genres’thatcontainmultiplevaluesseparatedbypipe(|) characters. Then Using explode function to explode each genre in columngenres.
2. Extract the release year from release data using to datetime function.
3. Group the release year and genres to calculate the accumulated popularity each genre in each year.
4. Using group and transform function to pick the max value of popularity that year.
5. Count the most popular times each genre.

• What kind of properties are associated with movies that have high revenues?
1. Using linear regression model to show the linear relationship between revenue & budget, revenue & popularity, revenue & vote average, revenue &runtime.
2. Using heatmap to calculate the correlation value.

• Summary the final results
1. Drama is the No.1 popular genre,action No.2,comedy No.3,thriller No.4, adventure No.5. Drama, Action and Comedy are three most-popular genres.
2. Revenue has a strong correlation with budget.Mostly,higher budget generates higher revenue. Popularity has a relatively weaker correlation compare to revenue. Some movies have a high popularity but did not make high revenue.
