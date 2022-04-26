# Overview
The goal of this project is to get an idea of:
* Your ability to work with data:
  * Data Modeling 
  * Your ability to interact and handle external data sources 
* Your software engineering skills to include documentation through system design.
  * Assume you would have to present this to a technical team. 
  
Time effort: 
  * 1 day ish

# Source data
* The data used for this project will be The Movies Dataset (pulled from https://www.kaggle.com/rounakbanik/the-movies-dataset).
* Please use the copy of the data set provided at https://s3-us-west-2.amazonaws.com/com.guild.us-west-2.public-data/project-data/the-movies-dataset.zip

# Deliverables
There are several goals to this project:
1) Design a data model and include an ERD diagram (included relationships).
1) Implement an API that answers the following questions:
   * Production Company Details:
     * budget per year
     * revenue per year
   * Movie Genre Details:
     * most popular genre by year
1) Be prepared to discuss how you would implement this in a production environment.
   * How would you handle errors?

# Code 
Provide the code to your own public repo.
* Use the language of your choice.
* Code must be runnable - Document how to **build/run the code**.
* Output: 
  * Runnable local API that answers the questions above.
* Bonus (not required) : Can take a s3 endpoint to the file as a positional argument (e.g. `cmd s3://com.guild.us-west-2.public-data/project-data/the-movies-dataset.zip`) 
