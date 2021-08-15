# Movies-ETL Analysis
Module 8 Challenge Data Analysis File Links
- ![ETL_function_test.ipynb](https://github.com/aseo67/Movies-ETL/blob/main/ETL_function_test.ipynb)
- ![ETL_clean_wiki_movies.ipynb](https://github.com/aseo67/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
- ![ETL_clean_kaggle_data.ipynb](https://github.com/aseo67/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
- ![ETL_create_database.ipynb](https://github.com/aseo67/Movies-ETL/blob/main/ETL_create_database.ipynb)
- ![Resources Folder: wikipedia-movies.json, movies_metadata.csv, movies_query.png, ratings_query.png](https://github.com/aseo67/Movies-ETL/tree/main/Resources)

## Overview of Movies-ETL Analysis
Amazing Prime Video is a streaming platform for movies and TV shows on Amazing Prime, the world's largest retailer. The Amazing Prime Video team is sponsoring a hackathon, where participants will use a clean dataset of movie data - provided by Amazing Prime Video - to predict popular movies. To prepare these datasets, there are two data sources used: a Wikipedia scrape for all movies released since 1990 and rating data from Movie Land's website. First, the data will need to be extracted from these sources, transformed into one clean dataset, and loaded into a SQL database table. 

## Results Summary
1. First an ETL function was written to outline and test the process. 
 
 **Screenshot: ETL_function_test code**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%201_ETL%20function%20code.png)
 
 **Screenshot: ETL_function_test output - wiki_movies_df**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%201_wiki_movies_df.png)
 
 **Screenshot: ETL_function_test output - kaggle_metadata**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%201_kaggle_metadata.png)
 
 **Screenshot: ETL_function_test output - ratings**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%201_ratings.png)

2. Next, the wikipedia and kaggle data were cleaned and transformed into consolidated data tables. 

 **Screenshot: ETL_clean_wiki_movies output - wiki_movies_df**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%202_wiki_movies_df.png)
 
 **Screenshot: ETL_clean_wiki_movies output - wiki_movies_df columns**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%202_wiki_movies_df%20columns.png)

 **Screenshot: ETL_clean_kaggle_data output - movies_df**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%203_movies_df.png)
 
 **Screenshot: ETL_clean_kaggle_data output - movies_with_ratings_df**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%203_movies_with_ratings_df.png)

3. Finally, the final code is put together to also load the extracted and tranformed data into the database. 
 
 **Screenshot: ETL_create_database output - Runtime**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_Deliverable%204_Runtime.png)
 

 **Screenshot: ETL_create_database output - movies count**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_MoviesCount.png)

 **Screenshot: ETL_create_database output - movies query & output**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/movies_query.png)
 

 **Screenshot: ETL_create_database output - ratings count**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/Screenshot_RatingsCount.png)
 
 **Screenshot: ETL_create_database output - ratings query & output**
   ![Screenshot](https://github.com/aseo67/Movies-ETL/blob/main/Resources/ratings_query.png)



