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



