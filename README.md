**# Movies-ETL**

Amazing Prime wants to keep the dataset updated on a daily basis. Britta wants to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Code is being refactored to create one function that takes in the three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data and performs the ETL process by adding the data to a PostgreSQL database.

- 1: Write an ETL Function to Read Three Data Files
write a function that reads in the three data files and creates three separate DataFrames.

- 2: Extract and Transform the Wikipedia Data
Extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. 

- 3: Extract and Transform the Kaggle Data
Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

- 4: Create the Movie Database
Add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
