# nosql-challenge
Eat Safe, Love
Part 1: Database and Jupyter Notebook Set Up
Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments.

Within this markdown cell, copy the line of text you used to import the data from your Terminal. This way, future analysts will be able to repeat your process.

Dataset Import:

mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

mistakenly ran my code with a few spelling errors and had to create a fresh database to get correct answers

Part 2: Update the Database
An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add the following restaurant "Penang Flavours" to the database.

Part 3: Exploratory Analysis
Unless otherwise stated, for each question:

Use count_documents to display the number of documents contained in the result.
Display the first document in the results using pprint.
Convert the result to a Pandas DataFrame, print the number of rows in the DataFrame, and display the first 10 rows.
1. Which establishments have a hygiene score equal to 20?
