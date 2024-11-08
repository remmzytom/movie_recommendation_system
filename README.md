# movie recommendation system
#### Movie recommendation system


## Scenario
As a movie streaming platform, I want to understand movie trends and user preferences based on movie features, so that I can provide personalized recommendations to my users. The goal is to analyze movie data, uncover patterns in movie ratings, genres, and other key factors, and then implement a content-based recommendation system to suggest similar movies to users.


## What this usecase will teach me
At the end of this use case I will:

Clean and preprocess a movie dataset, including handling missing values.
Perform exploratory data analysis (EDA) to uncover insights into movie trends, ratings, and genres
Use machine learning techniques to predict movie ratings based on multiple features.
Visualize patterns in the dataset using data visualization techniques.
Build a content-based recommendation system using movie metadata.

## Introduction
This project aims to explore movie data and develop a content-based recommendation system. Movie recommendation systems are widely used in streaming platforms like Netflix and Amazon Prime to enhance user experience by suggesting movies based on their viewing history or preferences. By leveraging a dataset of movies with attributes like genre, ratings, runtime, and brief descriptions, we aim to analyze key factors that influence movie success and develop a system that recommends similar movies based on content.

In this project, we use a dataset containing movies, genres, ratings, and more, to uncover trends in movie success and develop a recommendation system. The content-based recommendation system will utilize features such as genre and textual movie descriptions to suggest similar movies to users based on the attributes of movies they have enjoyed in the past.

The dataset includes information on:

- Movie titles, genres, and release year
- Ratings and number of votes
- Movie runtime and description
- Cast and directors



## Skills Applied in the Movie Recommendation Project
- Data Processing & Preparation:
- Data Cleaning & Transformation:
- One-Hot Encoding & Feature Engineering:
- Text Processing:
- Exploratory Data Analysis (EDA):
- Visual Libraries:
- Utilized Visual Libraries like Matplotlib, Seaborn, and WordCloud to create clear and informative visualizations.
- Machine Learning & Modeling:
- Unsupervised Learning:
- Dimensionality Reduction(PCA):
- Similarity Measures(cosine similarity):
- Data Standardization(standarsScaler):
- Pandas & Numpy:
- Scikit-Learn:
- Utilized for TF-IDF Vectorization, K-Means clustering.



### Number of Movies Released Per Year
This analysis was conducted to examine the number of movies released each year, highlighting the trends in movie production over time. A bar chart was created to display the top 20 years with the highest number of movie releases, providing a clear view of how the movie industry has evolved.
## ![barchat](images/one.png)

This bar chart presents the trend of movie releases from 2001 to 2020, showing a significant rise in production over time, with the peak occurring in 2020 at 2,442 movies. The visual highlights a gradual increase in movie releases from 2001, where fewer than 50 movies were released annually, to a marked acceleration in recent years

### Key Insights:

- 2020 saw a dramatic surge in movie releases, reaching the highest point in the dataset. This could be due to the proliferation of digital platforms like Netflix and Amazon Prime, enabling more films to be distributed directly to consumers.
- The second highest number of releases occurred in 2019 with 1,420 movies, suggesting a consistent upward trend in the last decade.
Prior to 2010, movie production was relatively low compared to recent years. Between 2001 and 2007, the number of annual releases was below 100, but a steady increase is observed after 2008.
The sharp rise after 2014 aligns with the growth of independent film-making, streaming services, and lower production costs, which have democratized the movie industry.
- Explanation for the Trend: This trend reflects the transformation of the movie industry, driven by technological advancements and the shift toward online streaming platforms. It also points to the increasing demand for content, as well as changes in the way movies are produced and distributed. Understanding these trends is essential for building predictive models or recommendation systems that cater to current production and consumption patterns.


### Number of Movies Released in Different Decades
This analysis provides a long-term view of how the movie industry has evolved over the years, highlighting significant periods of growth and change.
## ![barchat](images/two.png)

This bar chart shows how many movies were released in each decade, from the 1930s to the 2020s. The data reveals some important trends:

### Key Insights:

- 2010s: The 2010s saw the highest number of movie releases, with 5,451 movies. This huge increase is likely due to the rise of streaming platforms like Netflix and Amazon Prime, which made it easier to produce and distribute movies.
- 2020s: Even though the 2020s aren't over yet, there have already been 3,702 movies released, showing that the movie industry continues to grow rapidly.
- 2000s: The 2000s marked the beginning of this upward trend, with 637 movies released. This is when digital filmmaking and online distribution started to gain popularity.
Earlier Decades: From the 1930s to the 1990s, movie production was much lower, with fewer than 100 movies released per decade. This was because making and distributing films was more expensive and harder to do before the digital age.
### Explanation for Trends:

- Technology: Starting in the 2000s, new technology made it cheaper and easier to make movies. The rise of digital cameras and editing software lowered the cost, allowing more filmmakers to enter the industry.
- Streaming Services: Platforms like Netflix and Amazon Prime have played a big role in the huge increase in movie releases, especially in the 2010s and 2020s. These platforms have increased the demand for more content, leading to more movies being made.


### Analysing the trend of average rating, votes and runtime
![](images/three.png)

### Average Rating per Year (Top Plot):

- The average movie ratings have remained relatively high and stable, mostly between 6.0 and 8.0, from the 1930s up to 2020.
- There is some fluctuation in ratings during the 1960s to 1990s, with peaks reaching as high as 8.0 in certain years.
- In recent years, the average ratings have been more consistent, showing a slight upward trend.
  
![](images/four.png)
### Average Votes per Year (Middle Plot):

- The number of votes has significantly increased starting from the 1960s, with a major spike around the 1980s and 1990s.
- This increase reflects the growing popularity of movies and wider audience engagement, likely due to better access to films and the rise of internet platforms where users can vote.
- After the peak in the 1980s and 1990s, the average votes per year have gradually decreased, which might suggest changes in how movies are distributed or voted on.

![](images/five.png)

### Average Runtime per Year (Bottom Plot):

- Movie runtimes have varied widely over the years. The data shows a notable increase in average runtime in the 1960s, with movies during that period running longer, peaking at around 175 minutes.
- Over time, average runtimes have gradually decreased, especially in more recent years, stabilizing around 100 minutes, possibly due to modern audiences preferring shorter films or the rise of content like TV shows and web series that are designed for quicker consumption.
- This may reflect changing audience preferences or trends toward shorter, more concise movies in the digital age.



### checking if movies with more votes tend to have higher ratings.
This analysis helps to understand if more popular movies (with higher votes) tend to have higher ratings, and vice versa.
![](images/seven.png)

This scatter plot visualizes the relationship between votes (on the y-axis) and ratings (on the x-axis) for movies. Each dot represents a movie, where its position on the x-axis indicates its rating and its height on the y-axis indicates the number of votes it received.

#### Key Insights: General Trend:

- Movies with higher ratings (closer to 10) tend to have more votes. There is a visible upward trend where movies with ratings above 7.0 generally attract more votes, suggesting that higher-rated movies are more popular and receive more viewer engagement. Cluster of Low Ratings with Few Votes:

- Movies with ratings below 6.0 tend to have fewer votes. This could indicate that lower-rated movies attract less attention or may appeal to smaller, niche audiences. Highly Voted Movies with High Ratings:

- A group of movies with ratings between 8.0 and 9.5 has received the highest number of votes (over 1 million). These are likely popular and highly rated movies that resonate with large audiences.



### what are the common genres?

![](images/nine.png)

The word cloud above shows the most common movie genres in the dataset. The bigger the word, the more common that genre is. For example, "Drama," "Comedy," "Action," and "Adventure" are the largest words, meaning these genres appear most often in the movies we have. This suggests that these types of movies are very popular or are produced more frequently.
>
Other genres, like "Documentary," "Crime," and "Animation," are also shown but are a bit smaller, which means they are less common than the top genres but still significant. You can also see a wide range of genres, like "Horror," "Romance," and "Reality-TV," showing that there is a good mix of movie types available.


### Analyzing the average number of votes per genre. Are certain genres more popular or attract more voters than others?
The goal is to determine which genres are more popular or attract more audience engagement as reflected by the number of votes.
![](images/9.png)

### Observations:

- Sci-Fi, Thriller, and Crime genres dominate with the highest average number of votes, with Sci-Fi topping the chart at nearly 40,000 average votes. These genres typically feature blockbuster films that attract broad audiences and garner significant attention.

- The Thriller and Crime genres are also highly popular, which might be due to the suspense and intense storylines that appeal to wide audiences across different demographics. Mid-Range Genres:

- Adventure, Action, Fantasy, and Biography genres fall in the middle tier, with an average of 15,000-20,000 votes. These genres likely include a mix of mainstream and niche films that generate steady but not overwhelmingly large engagement.

- Musical, Horror, and Drama genres also fall in this mid-range category, with decent engagement. These genres often include cult classics or emotionally driven films that resonate with specific audience groups. Genres with Lower Engagement:

- Reality-TV, Talk-Show, Game-Show, and News genres receive significantly fewer votes, with Game-Show and Talk-Show barely crossing the 2,000-vote threshold. This reflects their niche appeal and limited engagement compared to more widely popular movie genres.

- Documentary and Short Films also have lower average votes, likely because these genres cater to more specialized or educational audiences. Niche Genres:

- Film-Noir, Western, and Family genres, while not among the top in terms of votes, still have a steady fanbase, garnering between 8,000-12,000 votes on average. These genres have dedicated but smaller audience groups, and while they may not generate the highest vote counts, they have consistent appeal to specific viewers.


### Runtime by Genre:
comparing movie runtimes across different genres. This could reveal if certain genres (e.g., drama or action) tend to have longer or shorter runtimes.
![](images/eleven.png)

- Top Runtimes: The chart shows that genres such as war, western, and biography have the highest average runtimes, around 100 minutes. This could suggest that these genres often include detailed storytelling that requires longer screen time.
- Moderate Runtimes: Genres like thriller, horror, music, and musical have average runtimes between 80 to 90 minutes.
- Shorter Runtimes: Genres like animation, short, and game-show have the shortest average runtimes, with averages below 60 minutes. This is likely due to the nature of these genres; for example, short films are designed to be concise.








  
