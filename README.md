# nosql-challenge
  Module 12 is based on the following scenario: The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
  It is broken down into two parts: NoSQL_setup_starter & NoSQL_analysis_starter. These two notebooks comprise three total parts as follows:

  ## NoSQL_setup
  1. Database and Jupyter Notebook Setup
     - Import the JSON file and Name the database
     - Create an Instance of the Mongo Client
     - Assign the collection to a variable to prepare for collection use
  2. Update the Database (modifications made)
     - Add a new restaurant to the db
     - Find and return the business type Id and business type
     - Update the business type ID
     - Remove establishments in the Dover Local Authority and check how many items were removed
     - Update some number values that are stored as str to int

  ## NoSQL_analysis
  3. Exploratory Analysis
     Answers the following questions:
       - Which establishments have a hygiene score equal to 20?
       - Which establishments in London have a RatingValue greater than or equal to 4?
       - What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new 
         restaurant added, "Penang Flavours"?
       - How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to 
         lowest, and print out the top ten local authority areas.
  
