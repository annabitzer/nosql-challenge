# nosql-challenge
Within this challenge, Mongo was used to import a database of food establishemnts, pymongo was used within a jupyter notebook to update and analyze the database. After reviewing the database, a new restaurant was added. The database was queried to find all restaurants in Dover, which were then deleted. Finally, some data cleaning was performed to edit the datatypes of longitude, latitude and rating values, before moving onto analysis.

A series of queries were performed to learn more about the establishments dataset, which were then stored in pandas dataframes. Simple pymongo queries were performed to find all establishments with a hygiene score of 20 and all establishments with a Rating Value greater than 4. A more advanced aggregation query was performed to find only the top 5 restaurants with a Rating Value of 5, sorted by hygiene score. Finally, an aggregation pipeline was used to groupby Local Authority area, counting the number of restaurants with a hygiene score of 10 in each area.


Sources Used:
to check datatype: https://www.mongodb.com/docs/manual/reference/operator/aggregation/type/
finding results within a certain range: https://stackoverflow.com/questions/48365283/how-to-find-values-between-a-range-in-mongodb