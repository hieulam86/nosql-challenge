# nosql-challenge

# Exploratory Analysis of UK Food Hygiene Ratings
This project involves performing an exploratory analysis of food hygiene ratings for establishments in the United Kingdom. The analysis is conducted using MongoDB for data retrieval and processing. The tasks performed include importing data, setting up a MongoDB database, executing queries, and analyzing the data to provide insights.

## Tasks Completed
## Part 1: Database and Jupyter Notebook Set Up

1. Database Setup
    - Imported data from the establishments.json file into a MongoDB database named uk_food and a collection named establishments.

2. Jupyter Notebook Setup
    - Imported necessary Python libraries such as PyMongo and Pretty Print (pprint).
    - Created an instance of MongoClient and confirmed the creation of the database and loading of data.

Part 2: Update the Database
    - Added a new halal restaurant "Penang Flavours" in Greenwich to the database and updated its BusinessTypeID.
    - Checked and removed establishments within the "Dover" Local Authority.
    - Converted latitude, longitude, and RatingValue to the appropriate data types.

Part 3: Exploratory Analysis
    - Identified establishments with a hygiene score equal to 20 and displayed relevant information.
    - Explored establishments in London with a RatingValue greater than or equal to 4.
    - Found the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score, nearest to a new restaurant "Penang Flavours."
    - Counted the number of establishments with a hygiene score of 0 in each Local Authority area and displayed the top 10.

## How to Replicate
1. Database Import and Setup
    - Import the data using mongoimport and the provided JSON file.
    - Set up a MongoDB database named uk_food and a collection named establishments.

2. Jupyter Notebook
    - Open the provided Jupyter Notebook (NoSQL_setup_starter.ipynb) to execute the tasks.

3. Task Execution
    - Follow the instructions in the notebook to complete the tasks.
