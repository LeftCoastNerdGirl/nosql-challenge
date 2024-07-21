# Using MongoDB, Python, Pandas, and Pretty Print to analyze data

This project uses food hygiene ratings data from restaurants in the UK as its datasource. 

The first part is data setup and clean up.  
-Import the libraries you need: PyMongo and Pretty Print (pprint).  
-Import the data provided in the establishments.json file from your Terminal.  
-Name the database uk_food and the collection establishments.  
-Create an instance of the Mongo Client.  
-List the databases you have in MongoDB. Confirm that uk_food is listed.  
-List the collection(s) in the database to ensure that establishments is there.  
-Find and display one document in the establishments collection using find_one and display with pprint.  
-Assign the establishments collection to a variable to prepare the collection for use.  

![image](https://github.com/user-attachments/assets/13fb6f4e-df40-4cbc-b1d9-06ec034be135)

Part 2 is data changes and additions.  
-Add new restaurant "Penang Flavours" to the dataset.  
-Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.  
-Update the new restaurant with the BusinessTypeID you found.  
-Remove any establishments in Dover.  
-Use update_many to convert latitude and longitude to decimal numbers.  
-Use update_many to convert RatingValue to integer numbers.  
-Set ratings values other than 1-5 to null.  

The final part is all about exploratory analysis.

Part 3: Exploratory Analysis
Answer the following questions:   
-Which establishments have a hygiene score equal to 20?  
-Which establishments in London have a RatingValue greater than or equal to 4?  
-What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
-How many establishments in each Local Authority area have a hygiene score of 0?  
-Sort the results from highest to lowest, and print out the top ten local authority areas.  

![image](https://github.com/user-attachments/assets/0c16e84f-3c9f-4f5a-a996-5b8e966996df)
