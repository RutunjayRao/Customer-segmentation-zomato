# Customer-Archetype-Segmentation-using-Zomato-dataset

### MySQL

Data cleaning, preprocessing and exploration:

  1. Checked all the details of table such column name, data types and constraints.
  2. Checked for duplicate values in [RestaurantId] column.
  3. Removed unwanted columns from table.
  4. Merged 2 differnt tables and added the new column of Country_Name with the help of primary key as [CountryCode] column.
  5. Identitfied and corrected the mis-spelled city names.
  6. Counted the no.of restaurants by rolling count/moving count using windows functions.
  7. Checked min,max,avg data for votes, rating & currency column.
  8. Created new category column for rating

Data Analysis:

  1. According to this Zomato Dataset, 90.67% of data is related to restaurants listed in India followed by USA(4.45%).
  2. Out of 15 Countries only 2 countries provides Online delivery options to their customers, to be precised only 28.01% of restaurants in India and 46.67% of restaurants in       UAE provides online delivery options.
  3. As this dataset contains data most related to India so worked on gaining insights on Indian Restaurants.
  4. Connaught Place in New Delhi has the most listed restaurants (122) follwed by Rajouri Garden (99) and Shahdara (87).
  5. Most popular cuisines in Connaught Place is North Indian Food.
  6. Out of 122 restaurants in Connaught Place only 54 restaurants provide table booking facility to their customers.
  7. Average Ratings for restaurants with table booking facility is 3.9/5 compared to restaurants without table booking facility is 3.7/5 in Connaught Place,New Delhi.
  8. Best modrately priced restaurants with average cost for two < 1000, rating > 4, votes > 4 and provides both table booking and online delivery options to their customer with indian cuisines is located in Kolkata,India named as 'India Restaurant',(RestaurantID - 20747).

### Python for visualization and Clustering of customers 

![image](https://github.com/RutunjayRao/Customer-segmentation-zomato/assets/89570687/d443a39f-e480-4b45-a087-a4c3c0b325bf)

#### K-means clustering for **New Delhi**
![kmeans](https://github.com/RutunjayRao/Customer-segmentation-zomato/assets/89570687/c4618c96-c048-41d5-8aa6-4caec3d1a119)

### Best rated restaurants vs Geography
![rating](https://github.com/RutunjayRao/Customer-segmentation-zomato/assets/89570687/b1c85b6e-351f-4090-a96a-8a85abd314e8)

### Correlation between number of cuisines and ratings
![image](https://github.com/RutunjayRao/Customer-segmentation-zomato/assets/89570687/f93723a2-e0f1-4487-8041-718c5abed0ad)
