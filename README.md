# ML for Netflix movies and tv shows clustering
 This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
  In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled.   It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

**Programming Language** : Python

**Libraries used** : Pandas, Numpy, Matplotlib, Seaborn, Sklearn

**NoteBook** : Google Colab

**Dataset Source** : Provided by Almabetter themself.
 
## Dataset 
We are given a Netflix movies and TV shows clustering dataset. It contains the following features.
```
- show_id : Unique ID for every Movie / Tv Show
- type : Identifier - A Movie or TV Show
- title : Title of the Movie / Tv Show
- director : Director of the Movie
- cast : Actors involved in the movie / show
- country : Country where the movie / show was produced
- date_added : Date it was added on Netflix
- release_year : Actual Releaseyear of the movie / show
- rating : TV Rating of the movie / show
- duration : Total Duration - in minutes or number of seasons
- listed_in : Genere
- description : The Summary description
```

The dataset used for Netflix movies and TV shows clustering includes information on multiple features of the titles, such as genre, director, cast, rating, release year, duration, and type. It consists of 7787 rows and 12 columns.
However, some columns, such as director, cast, and country, contain null values that need to be addressed during the data analysis process.
  
## Exploratory Data Analysis
 Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:
   - count Plot.
   - Bar Plot.
   - Pie Chart.
   - Heatmap.
   - word cloud. 
   - Correction heatmap.
   - Pair plot.
     
             
## ML Model Used:

Several machine learning algorithms were utilized. These models include:
```
1. K-means clustering
2. Hierarchical clustering
3. DBSCANE
```

## Conclusion  
1. Conducted analysis on a Netflix dataset to gain insights into the content available on the platform.
2. Explored various visualizations to understand the distribution of TV shows and movies, their durations, genres, and countries of origin.
3. Performed statistical tests to analyze differences in average durations between movies and TV shows, distribution of genres, and relationship between release year and number of seasons.
4. Handled missing values in columns such as director, cast, country, and rating, ensuring the dataset is clean and ready for analysis.
5. Utilized text normalization techniques such as lemmatization and text vectorization using TF-IDF to process and represent textual data.
6. Explored dimensionality reduction using PCA to reduce the number of features while preserving a significant amount of variance in the data.
7. Applied clustering algorithms such as k-means, hierarchical clustering, and DBSCAN to cluster the movies and TV shows based on their features.
8. Evaluated the clustering models using metrics such as silhouette score to understand the quality and structure of the clusters.
9. Identified the number of clusters that provide the highest silhouette score, enabling better understanding of the underlying patterns and similarities in the data.
10. Chose the final model based on the evaluation metrics and business requirements, considering factors such as interpretability and performance. Generated insights into the clusters, identifying distinct groups of movies and TV shows based on their features.
11. Considered the business impact of the model, highlighting the potential benefits of better content categorization and recommendation, improved user experience, and targeted marketing strategies.
12. Concluded the project with recommendations for further analysis and model refinement, considering factors like additional data sources, feature engineering, and alternative modeling techniques.
