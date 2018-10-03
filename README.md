# json_pyspark_project
<p>Spring board project - Data wrangling using Json file</p>
<p>Used pyspark instead of Python to complete this project
<p>First step I have used sparksession to load the json file to dataframe
<p>To find the top 10 countries with most projects I have used the spark.sql
<p>To find the most used theme, I used explode to unpack the theme list and used dataframe select to find the most used themecodes
<p>Finally I segregated the empty values in Name field of the 'theme' field. By exploding and exploding again.
