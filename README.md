# Sentiment-Analysis
This dataset was derived from the Kaggles MoviesOnStreamingServices dataset.  I utilized Exploratory Analysis, Sentiment Analysis, Topic Modeling, and visualizations to conduct my research.

## **Problem Statement and Review of Related Work**
I wanted to research movie and TV show titles on streaming platforms. I obtained an appropriate data set from Kaggle, named “Movies on Streaming Platforms” to do so. This data set has 9515 observations and 11 variables. I have explained each variable below after my Problem Statements are provided. I had several questions based on the values provided in this data set. I wanted to utilize the movie titles, the age demographic, the rating, and the year to delve deeper into the data. For some of the questions
that I wanted to research, exploratory data analysis would be enough to find the solution, however, other questions required tidying data, TF-IDF over Titles, and Topic Modeling. See below for all of my initial research questions.

1. What words appeared the most throughout all of these titles?
2. What word pairs were most common?
3. What movies and TV shows were the most popular per decade?
4. What movies are available on all streaming Platforms?
5. What platforms are most popular per age group?
6. What Titles had the highest Rating on Rotten Tomatoes?
7. What words were most common and what is the importance of a word in the Movie Titles and TV
Show Titles?
8. How many topics were present and what were the possibilities of each word contributing to each
topic?

 ##**Column Descriptions**
ID: A unique identifier for each movie within the data set. 
Title: The full title of the movie as it appears on the streaming platforms. 
Year: The release year of the movie, indicating when the movie was first made available to the public. 
Age: The recommended age group for the movie’s audience, such as ‘7+’, ‘13+’, ‘16+’, or ‘18+’. 
Rotten Tomatoes: The movie’s score on Rotten Tomatoes, which reflects critics’ reviews and can be used as a measure of the movie’s reception. 
Netflix: A binary indicator (0 or 1) of whether the movie is available on Netflix, with 1 indicating availability. 
Hulu: A binary indicator (0 or 1) of whether the movie is available on Hulu. 
Prime Video: A binary indicator (0 or 1) of whether the movie is available on Amazon Prime Video. 
Disney+: A binary indicator (0 or 1) of whether the movie is available on Disney +. 
Type: A categorical indicator distinguishing the content as either a ‘Movie’ or a ‘TV Show’.

### **Additional Data Set Attributes**
Each row in the data set represents a single movie, with its corresponding attributes spread across the
aforementioned columns. The data set is comprehensive and potentially updated regularly, ensuring a
current snapshot of movies across major streaming platforms. There are columns for additional streaming
platforms, which can be included in the analysis as needed. Some entries may have missing values, especially
in age ratings, which could be due to various factors such as the movie being unrated or newly released.

[title] (https://www.kaggle.com/datasets/sanyacodes/movies-dataset-netflix-prime-video-disney)

