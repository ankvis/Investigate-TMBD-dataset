# Investigate-TMBD-dataset

## Dataset Overview: This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Brief Description of Columns
- id: Identification Number
- imdb_id: Id used on Imdb website
- Popularity: Rating for the movie
- budget: Total cost of producting
- revenue: Total revenue
- original_title: Name of the movie
- cast: Name of the people casting in the movie
- homepage: Website URL
- director: Director responsible for shooting the film
- tagline: Caption
- keywords: words to indicate content of the movie
- overview: Brief description of the movie
- runtime: Duration
- genres: Category/Categories of the movie
- production_companies: Companies responsible for producting the movie
- release_date: Release date in Month/Day/year format
- vote_count: Number of votes submitted
- vote_average: Mean of the votes
- release_year: Year of the movie release
- budget_adj: budget of the associated movie in terms of 2010 dollars,accounting for inflation over time
- revenue_adj: revenue of the associated movie in terms of 2010 dollars,accounting for inflation over time

# Conclusions
1. The dataset has quite number challenges, I had to do get rid of lot of columns like tagline, overview, homepage because they were mostly strings with description which does not help in analyzing.

2. Columns like budget, revenue and adjusments had a lot of null and '0' values(around 60% approx). I would have definitely used them for exploratory data analysis if the values were provided or only a few were missing. Using some satistics operations to alter the '0' values is not justifiable.

3. Drama and Comedy have shown dominace throughtout our findings.

4. Overall the graphs shows the the entertainment/movie industry have shows huge progression, people engagement has increased.
Other variables I could have used:

5. 'director' - something like most number of releases or average releases per year.
Could have used a combination of genres but it would have increased the instances for genres, making it hard to visualize
'vote_count' and 'vote average' are good variables to have good relation to find popularity and interest of genres

