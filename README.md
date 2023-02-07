# Project3_CleaningData : New Markets Data

## Team 

Rachad and Clémence

## Project Description

The goal of this project is to combine data wrangling, cleaning, and manipulation with Pandas in a real dataset, and show some highlights after the cleaning. 

## Steps Followed 

- Load the data: excel file
- Analyze the data and create a plan for data preparation

- Use python to create function in order to follow the cleaning steps:
-- Cleaning Text and Removing Special Characters
-- Check ou the type of data and change if needed
-- Check for missing values and fill them if needed 
-- Check the dupliactes in IDs and put the ID as index 
-- Check for low variance columns and possible outliers (check ou the 0)
-- Check the incoherence between columns: "Age and Profession", "Age and Work experience", "Graduated and Profession"
-- Check out the Var_1 column containing different categories and figure out what these categories are based on
-- Export the cleaned table from Python to Mysql and store it as csv file

- Mysql analysis part:
-- Queries to load and work on the data 
-- Relationship between:
--- study the profile of most and least spenders: age, gender and profession
--- Evaluate the profession based on gender 
--- Evaluate gender / marital status / spendings 
--- Evaluate marital status / family size
--- Evaluate categories and spending 

## Obstacles encountered 

The main obstacle was to understand the inconsistencies between the data. We chose to highlight them in our analysis, without discarding them from the dataset, but this reduced the analyses we could ultimately do. 
An other obstacle was the missing values, and how to replace it without corrupting the data set. 

## Lessons learned 

We learned that the order in the data cleaning is important to take attention because you have to well understand all the possible issues in your dataset before change something. 
We learned that it is more important to be able to highlight the incoherencies or mistakes than always replace it. 
We learned how to connect python and mysql, and do some SQL queries from Python Notebook. 

## Deliverables
- CSV file with clean data containing the results of our data wrangling work.
- Python file containing all Python code and commands used in the importing, cleaning, manipulation, and exporting of our data set.
- MySQL queries file containing the code to obtain table of our analysis.
- A README.md file containing a detailed explanation of the process followed in the importing, cleaning, manipulation, and exporting of our data as well as our results, obstacles encountered, and lessons learned. 
