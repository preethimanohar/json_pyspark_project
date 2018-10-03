# json_pyspark_project
<p>Spring board project - Data wrangling using Json file</p>
Used pyspark instead of Python to complete this project
First step I have used sparksession to load the json file to dataframe
To find the top 10 countries with most projects I have used the spark.sql
To find the most used theme, I used explode to unpack the theme list and used dataframe select to find the most used themecodes
Finally I segregatted the empty values in Name field of the 'theme' field. By exploding and exploding again.
