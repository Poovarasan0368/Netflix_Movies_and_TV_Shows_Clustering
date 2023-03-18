# Netflix_Movies_and_TV_Shows_Clustering

![image.png](https://images.squarespace-cdn.com/content/v1/599bbf76914e6bb960c6d0bb/1570094672119-ZKYXULH7KGAG1EXODHNE/netflix-logo.gif?format=1000w)

## Introduction 📘
Netﬂix is a media distribution company. It started with  DVD distribution via mail, but has evolved substantially  over the course of its existence. Today, Netﬂix is focused  on streaming video. Some of its content is licensed, and  some of the content is produced in-house. Netﬂix originally focused on movies, but today  television shows are probably the more common  format. Netﬂix works on a subscription model, where  users get unlimited access to content with a paid  subscription.

## Problem Description 🤔  
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is  collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix  has nearly tripled since 2010. The streaming service’s number of movies has decreased by more  than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting  to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also  provide many interesting findings.

### The contents of Netflix Data are:
The	dataset consists of listings of all the movies and tv shows available on Netflix, along with details  such as - cast, directors, ratings, release year, duration, etc.

* **show_id :** Unique ID for every Movie / Tv Show
* **type :** Identifier - A Movie or TV Show
* **title :** Title of the Movie / Tv Show
* **director:** Director of the Movie
* **cast :** Actors involved in the movie / show
* **country :** Country where the movie / show was produced
* **date_added :** Date it was added on Netflix
* **release_year :** Actual Release year of the movie / show
* **rating :** TV Rating of the movie / show
* **duration :** Total Duration - in minutes or number of seasons
* **listed_in :** Genre
* **description:** The Summary description

## The series of steps followed in this project 📃

    1. Importing Packages
    2. Reading Data
    3. Explore the structure of the Datasets
    4. Data Cleaning
    5. Exploratory Data Analysis (EDA)
    6. Data Transformation
    7. Principal Component Analysis (PCA)
    8. creating ML Models
    9. Displayng Wordcloud
    10. creating Recommendations System
    	
## The tools that are going to be used for this project would be 💾
   
    1. Numpy 
    2. Pandas
    3. Matplotlib
    4. Seaborn
    5. Sklearn
    6. plotly
    7. datetime
   
**which I have learnt from the course.**

## Algorithm that used in this project are 🔣

    1. K-means clustering
    2. Agglomerative clustering 
    3. Birch clustering
    
## Vectorizer that used in this project are 🔼
 
    1. TfidfVectorizer
    2. CountVectorizer

## Conclusion ✌

**KMeans Clustering with TfidfVectorizer and Elbow method has the best overall Silhouette Coefficient of 60 percentage and best overall Davies bouldin score 59 percentange. The optimal Silhouette Coefficient for Agglomerative Clustering with TfidfVectorizer and Dendrogram, Birch Clustering with TfidfVectorizer was 58 and 53 percentage respectively. The optimal Silhouette Coefficient for KMeans Clustering with Tf-idf Vectorizer and Silhouette Score and Agglomerative Clustering with Tf-idf Vectorizer and Silhouette Score models is 74 and 72 percentage respectively. however the optimal clusters is only 2 for both models so we can't this as best model. we'll make KMeans Clustering with TfidfVectorizer and Elbow method model and Agglomerative Clustering with TfidfVectorizer and Dendrogram model as our best model because it provides good overall Davies bouldin score, Silhouette Coefficient and optimum clusters.**

* Movies make up 69% of the content on Netflix, while TV shows make up the remaining 31%.

* This was surprising to discover that movies make up the majority of the Netflix content. But lately, it has been concentrating more on television shows.

* The majority of this content is made available either towards the end of the year or at the beginning.

* The ratings TV-MA and TV-14 have a lot of television shows and movies that are suitable for adults and teenagers, respectively.

* The majority of Netflix TV shows only have a single season, while the majority of the movies have running times between 80 and 100 minutes.

* America and India produces the majority of movies and television Shows, But in India Movies are more well produced than television shows.

* Netflix's addition of movies and television shows increased from 2016 to 2019, but from 2019 to 2021, it gradually dropped, possibly as a result of COVID.
