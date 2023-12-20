# Netflix_movie_and_TV_Show_Clustering_Project
**AlmaBetter Capstone Project - Unsupervised: Netflix Movies And Tv Shows Clustering**

**This project is a part of the Almabetter Pro Program Curriculum(Full Stack Data Science)**

**Project Summary**

The objective of this project is to analyze and cluster a dataset related to Netflix. **The dataset consists of various attributes associated with Netflix shows and movies, such as title, genre, release year, duration, rating, and others. The aim is to explore patterns and similarities among the content available on the platform and group them into meaningful clusters.**

Next, exploratory data analysis (EDA) techniques will be utilized to gain insights into the dataset. **Visualizations and statistical summaries will be used to understand the distribution of variables, identify any trends, and explore relationships between different features.**

Once the dataset has been thoroughly analyzed, clustering algorithms such as k-means, hierarchical clustering, or density-based spatial clustering will be employed. These algorithms will group similar Netflix shows and movies together based on their attributes. **The optimal number of clusters will be determined using techniques like the elbow method or silhouette analysis.**

After the clustering process, the results will be evaluated and interpreted. The clusters will be analyzed to understand the common characteristics and patterns within each group. **This analysis will provide valuable information for Netflix in terms of content categorization, recommendation systems, and content acquisition strategies.**

Finally, the findings and insights from the clustering analysis will be summarized and presented in a clear and concise manner. Visualizations, charts, and graphs will be used to effectively communicate the outcomes of the project. Recommendations may also be provided based on the identified clusters, suggesting potential improvements or strategies for Netflix to enhance user experience and content offerings.

**Problem Statement :**

This dataset consists of tv shows and movies available on Netflix as of **2019**. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

**About the Data :**

We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle

**Dataset info**

**Number of records:** 7787

**Number of features:** 12

**Features information:**

**The dataset contains features like:**

**show_id :** Unique ID for every Movie / Tv Show

**type :** A Movie or TV Show

**title :** Title of the Movie / Tv Shows

**director :** Director of the Movie

**cast :** Actors involved in the movie / show

**country :** Country where the movie / show was produced

**date_added :** Date it was added on Netflix

**release_year :** Actual Release year of the movie / show

**rating :** TV Rating of the movie / show

**duration :** Total Duration - in minutes or number of seasons

**listed_in :** Generes

**description:** The Summary description

**Project Work flow**

**Importing Libraries**

**Loading the dataset**

**Data Summary**

**Data Cleaning & Data Analysis**

**Feature selection**

**Implementing different clustering methods**

**Conclusion**

**1- Exploring the dataset consist of 7777 records and 12 attributes, with a focus on missing value imputation and exploratory data analysis (EDA).**

**2- The analysis revealed that Netflix has a greater number of movies than TV shows, with a rapidly growing collection of shows from the United States.**

**3- It is interesting to note that the majority of the content available on Netflix consists of movies. However, in recent years, the platform has been focusing more on TV shows.**

**4- Most of these shows are released either at the end or the beginning of the year.**

**5- The United States and India are among the top five countries that produce all of the available content on the platform. Additionally, out of the top ten actors with the maximum content, six of them are from India.**

**6- When it comes to content ratings, TV-MA tops the charts, indicating that mature content is more popular on Netflix.**

**7- The value of k=15 was found to be optimal for clustering the data, and it was used to group the content into ten distinct clusters.**

**8- Using this data, a Content based recommender system was created using cosine similarity, which provided recommendations for Movies and TV shows.**

