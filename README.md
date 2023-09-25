# nosql-challenge

In this challenge we were tasked to take data from the UK Food Standards Agency and load it into a Mongo Database that we created. The information was passed to us in the "establishments.json" file. We imported the data to our local Mongo Database using the terminal :

Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

We added in a new restaurant called "Penang Flavours" which allowed us to practice inserting data to the database as well as validating the data type for numerical analysis. Primarirly focusing on hygience score and store rating.

We were able to extract the Mongo data and convert it into a pandas DataFrame.