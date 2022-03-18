# Movie_Recommender_System_Project
Various recommender systems are used in various fields, such as playlists for video and music services, product recommendations for online stores, and content recommendations for social media platforms. In this project, we are creating a movie recommendation. The dataset was found from the movies/tv rating website called IMDB. The website includes data from nearly all the movies, tv, shorts and web videos in existence. The original dataset was acquired from datasets.imdbws.com which is a self hosted link from the creators of the website. The dataset consists of 7 TSV files totaling 7 GB of data. In modern society, due to the prevalence of the Internet, people have too many choices to choose from, which is why we need a recommender system. As an example, Netflix has a large selection of movies. People have a hard time selecting the items that they actually want to see, even though the amount of available information has increased. Recommender systems can help with this

# Data Acquisition and Preprocessing
IMDB
Web scraping
Preprocessing – Merging, Cleaning and Formatting

# Exploratory Data Analysis (EDA)
Bar Graph and Line graphs
Pie chart
Histogram

# Recommendation System
Collaborative Filtering - matches persons with similar interests and provides recommendations based on this matching. 
KNN - determine the corresponding similar movie or a user based on cosine similarity
Results

# Dataset
The dataset is found from this link: (https://datasets.imdbws.com/). It contains many different datasets such as name-basics, title, rating, episode, ect which includes real data with direct movies records from people's searching.

#Three Types of Recommender systems

1- Demographic Filtering- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. 

2- Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. 

3- Collaborative Filtering- Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items. in this project we used collaborative filtering approach, to recommend a movies by Movie Name.

# K-Nearest Neighbor (KNN) 
classification algorithm is one of the simplest methods in data mining classification. K nearest neighbors, means that every sample can be represented by its K nearest neighbors.KNN algorithm is used to determine the corresponding similar movie or a user based on cosine similarity. K value is defined and desired number of nearest neighboring movies/users are returned.A new dataset is created from the existing merged dataset by grouping the unique user id and movie title combination and the ratings by a user to the same movie in different instances (timestamps) are averaged and stored in the new dataset.


# How to Use
Download both the notebook and and the dataset. Run all cells in the notebook.
