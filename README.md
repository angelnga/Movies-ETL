# Movies-ETL
Create an automated pipeline for Amazing Prime, a platform for streaming movies and TV shows, to update data on a daily basis for their analysis. <br>
There are two data sources:
- Scrape of Wikipedia for all movies released since 1990 
- Rating data from the Movie Land's webiste <br>
The project needs to extract the data from the two sources, transform it into one clean data set, and finally load that data set into a SQL table. 

## Process
- Deliverable 1: Write an ETL Function to Read Three Data Files<br>
  <a href = "https://github.com/angelnga/Movies-ETL/blob/main/ETL_function_test.ipynb"> ETL_function_test.ipynb </a><br>
  - wikipedia-movies.json
  - movies_metadata.csv
  - ratings.csv<br>
  <br>
- Deliverable 2: Extract and Transform the Wikipedia Data<br>
  <a href = "https://github.com/angelnga/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb"> ETL_clean_wiki_movies.ipynb </a>
  <br>
- Deliverable 3: Extract and Transform the Kaggle data<br>
  <a href = "https://github.com/angelnga/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb"> ETL_clean_kaggle_data.ipynb </a>
  <br>
- Deliverable 4: Create the Movie Database<br>
  <a href = "https://github.com/angelnga/Movies-ETL/blob/main/ETL_create_database.ipynb"> ETL_create_database.ipynb </a>

  ![data_movie:movies_table](resources/movies.png)
  ![data_movie:ratings_table](resources/ratings.png)
  

