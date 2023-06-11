# nosql-challenge

## Sources

1. Starter Code provided in the asssignments file
2. Stack Overflow was a great help when experiencing error messages
3. I occasionally used Chat GPT to help edit code to fix errors
4. Assignment description

# Project Overview as Described in Assignment:

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. I've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## Tools Used
1. Python
2. Mongo Client
3. PyMongo
4. Pandas

## Database Set Up

Create and Update Database to include all correct information and datatypes, as well as clear it of data that the magazine is not interested in.

* Import the json from the Terminal to create the Database
* Imported all dependencies into Jupyter Notebook
* Create the instance of the Mongo Client 
* Assign variables for the Database and the Collection
* Update the Database with the new restaurant
* Locate the appropriate Business ID and Update the restaurant
* Remove any restaurants within the Dover Local Authority
* Convert datatypes for data points that should not be strings

## Exploratory Analysis

Use the cleaned database to perform analysis on some the the restaurants in the UK to aid the magazine in their efforts.

* Import all dependencies into Jupyter Notebook
* Create the instance of the Mongo Client 
* Assign variables for the Database and the Collection
* For each of the following requests: find the number of restaurants and store the information in a DataFrame
    * Establishments that have a Hygiene Score of 20
    * Establishments in London with a Rating Value greater than or equal to 4
    * Top 5 Establishments with Rating Value of 5 and the Lowest Hygiene Score, nearest to Penang Flavours
    * Number of Establishments in each Local Authority with a Hygiene Score of 0

