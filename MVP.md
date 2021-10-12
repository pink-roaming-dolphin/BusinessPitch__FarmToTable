## Supplying the Local Grocery Store from the Surrounding Farmers Markets ##
## (Farm to Table Aisle) ##

I realized that the following can be deducted from the USDA Farmers Markets (whole country) database: 

- Frequency of the day of the week the market is set up
![Frequence](https://github.com/zey-o/Farm_to_Table/blob/main/Weekdaychart.png)

- The seasonality  
![Seasonality](https://github.com/zey-o/Farm_to_Table/blob/main/Seasons.png)

- Availability of Benefits Programs  
![Benefits](https://github.com/zey-o/Farm_to_Table/blob/main/Percentage%20of%20benefits%20programs%20allowed.png)

- Availability of Credit Cards  
![Credit](https://github.com/zey-o/Farm_to_Table/blob/main/Accept%20Credit.png)

- Distribution of Categories   
Products gathered into 7 subcategories: BEV(Beverages, Coffee & Wine), BBG (Bread, Baking& Grains), DEC (Dairy, Eggs & Cheese), PRO (Produce, Nuts etc), FLP (Flowers & Plants), MSF(Meat, Poultry, Seafood), PCP(Petfood, Crafts, Personal Care, Prepared - the Miscellaneous Category) 
The subcategories categorized into supcategories according to essentialness to Grocery Store(GS):Essentials1, Essentials2, Essentials3
Below is an example of the breakdown of Essentials 1 according to how many markets carry it (this is from a filter for all farmer markets in the STATE of New York, not CITY thus the larger number) 
![Supcategories](https://github.com/zey-o/Farm_to_Table/blob/main/Percentage%20of%20Essentials1.png)

**Pilot Program**
I narrowed the database to work with farmers markets in New York only, in the 5 boroughs (143 farms/rows). This allows for specificity and the reduction of data given the 70+ columns. 

Given a grocery market (first market is in zip code 11215: the highest income in Brooklyn borough), I am working on a pilot program that will: 
- Select the first FM according to distance from GS1. This is called the Brownsville Pitkin YM, open on Saturdays. Following is a breakdown of the categories it carries:    
![Percentage supcategories](https://github.com/zey-o/Farm_to_Table/blob/main/Essential%20Categories%20Sold%20by%20Percentage.png)
![Subcategories](https://github.com/zey-o/Farm_to_Table/blob/main/Percentage%20of%20Categories%20sold.png)
![Types of Categories](https://github.com/zey-o/Farm_to_Table/blob/main/Types%20of%20Groceries%20Carried.png)

- Given the day of the week FM1 is set up, add a FM2 that will bring the percentage of categories covered up. 
- Give a percentage for the organics with the addition of FM2 and also benefits availability.  
- Possibly bring in FM3 + FM4. 
- Now move onto Day2 and execute the same. 
- After Day 1-7 covered, try a GS2 to see how it scales across boroughs. 
