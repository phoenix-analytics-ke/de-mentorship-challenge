# Data Engineering Mentorship Challenge

An elementary data engineering challenge to evalute potential data engineering mentees for the Q2-2025 Mentorship cohort 
of the Phoenix Mentorship Program.

### Scenario
In this challenge you are to ingest data from a remote postgres database, the credentials will be provided in challenge folder
in a text file.
The data hosted in the database is raw data that has been scrapped from a website. Your task is to write a simple pipeline ingests the raw data, perform some data cleaning and loads the data into a remote database. 

### Tools
You are required to use Pandas for data wrangling. You can use any library of your choice to connect with the database. `SQLAlchmemy` and `psycopg2` are good candidates.

Create an account in Supabase. NOTE - Supabase is just a hosted remote postgres database. Create a database, and name it `agricultural-data`. Create a table and name it `cleaned_agric_data`. Your cleaned data will be loaded in this table.

Supabase documentation - 'https://supabase.com/docs'

### Submissions
Once you are done, create a Github repository to host your solution and share the link to ths email for evaluation - `cavin.mulewa.karema@gmail.com`. 

Create a text file called `credentials.txt` which will be used to connect to your database, similar to the one provided in this repository.
