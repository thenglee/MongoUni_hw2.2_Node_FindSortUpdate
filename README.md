Mongo Univeristy Week 2 Homework 2.2

Question: 
Write a program that finds the document with the highest recorded temperature for each state, and adds a "month_high" field for that document, setting its value to true.


Use the weather dataset in 'weather_data.csv'
Populate using the following command:
mongoimport --type csv --headerline -d -c data weather_data.csv



Solution:
Find all the weather documents, sort first by state, then by temperature. 
Next, iterate through the documents and store the first document (with the highest temperature) of each state into an array. 

Finally, iterate through the array of documents with highest temperature of each state and perform update function to set their "month_high" field in the database. 

