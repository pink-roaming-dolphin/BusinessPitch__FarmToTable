**Project Definition/ Title:** \
*FARM TO TABLE GROCERY AISLE: A PROPOSAL TO THE NEIGHBORHOOD MARKET* 


***Project Identification*** \
**Problem/ Opportunity:** \
Create a well sourced / optimized farm to table supply chain in order to: 
Initiate a ‘farm to grocery store’ aisle at the local grocery store chain \
**Problem Type:** Grouping \
**Opportunity:** Create a well sourced / optimized farm to table supply chain (Supply Chain Optimization)  \
**Impact:** Incorporate a ‘farm to grocery store’ aisle in the grocery store \
**Solution Path:** Create a list of neighborhoods which would be open to a ‘prestige’ project like this
Using these neighborhoods as a base, determine a weekly schedule for a delivery truck to visit farmer’s markets each day of the week and pick up groceries \
**Hypothesis:** Given the prevalence of the farm to table movement, we want to incorporate a wide variety of local farmers’ products into our grocery store. We hypothesize that local farmer’s markets are the best places to scout potential farms as suppliers thus we want to empower and incorporate farmer’s markets as partners in this endeavor. We want to locate the farmer’s markets with the most diverse set of farms.   


***Non-technical Scoping***\
**Obstacle/ Opportunity/ Business Need \
Potentially Impacted Parties (external/ internal) \
Main Constraints Faced by the Project** \
Inspired by two books, *Grocery: The Buying and Selling of Food in America* by Michael Ruhlman and *The Third Plate: Field Notes on the Future of Food* by Dan Barber; we propose to the widest reaching grocery store chain that they work with local farmer’s markets in establishing a ‘farm to grocery store’ aisle making available the fresh food that we find in the farmer’s markets around the city available throughout the week. 

Farmers markets host a diverse group of farms, by size, location and products. By working directly with the farmer’s markets, the grocery chain would reach the most diverse group of farmers. We could also partially automate the role of the supply chain organizer at the grocery store by framing the selection of farms out of the list of farms at the farmer’s markets as a mission statement. 

One big constraint of the project is that the farmer's markets might not want to establish such a partnership with the grocery market chain. 


***Technical Scoping***\
**Potential Solution Paths: \
Data Sources (ideal/ available)**  \
We will start with a pilot taking Broklyn as the epicenter of the project, thus looking at farmers markets in the state of NY. Then we will expand to other large cities in the country, first looking at the state of California which has the second highest number of farmers markets. We will scale from there. 

For NY: 
We will make a list of the most diverse farmer’s markets in the region and decide on a route and time schedule to pick up produce from these farmer’s markets. 

Ideal data set would be one with a list of all the farms within 100 miles of Brooklyn, and the type of product they produce. 

Instead, we have available the USDA dataset that lists the farmer’s markets in the USA (8804 entries, with 59 columns with info on: city, county, state, social media & website urls, seasons, location, type of payment accepted (cash, credit, SNAP etc), and type of food sold (seafood, herbs, meats, nuts, plants, poultry, wine, coffee, eggs, cheese etc). Of these markets, 673 of them are based in the state of New York which would be the subset we would concentrate on. 
Dataset available at: https://www.kaggle.com/madeleineferguson/farmers-markets-in-the-united-states 

One obstacle here is that only about 250 of these entries have a Time value aka. a non-null value as to when the market is set (eg. Saturday mornings, Monday all day etc). 

For our pilot, we will incorporate the US census data to look at demographics in Brooklyn and choose neighborhoods in which to pilot the program. 


***Collaborative Scoping - Current State***\
**Definition of Success (clear goal) \
Current Status Quo & Baseline Performance \
List of Unknowns** \
With this project, a successful outcome would be the selection of an itinerary by day of the week, optimizing total weekly distance driven and maximizing food variety. 

Currently there are local farmers from whom we source products, but it’s not a wide variety of products nor farmers (diversity in terms of large/small, organic/not, type of product etc). 

List of unknowns include: whether this rerouting will amount to profits or losses(!). 
Unknowns: Do the grocery stores already employ a truck, or are deliveries done by the suppliers themselves? What is the ‘advertising’ profit from a prestige project like this - does it justify the costs? 


***Collaborative Scoping - Future State***\
**Action Project Will Inform \
Technical Processes For Enabling the Action \
Project Timeline** \
The data science work we will be doing will help draw a route the grocery store truck should be taking each day during the week in order to pick up the most amount of diverse products from the most diverse group of farmers. 
The grocery store should test out the route and report on the costs incurred to the DS team so we can adjust the model accordingly. 

Project Timeline should be 2 cycles of weekly pickups & deliveries: one cycle for initial testing, second cycle for reading accurate data. 


***Collaborative Scoping - Tradeoffs*** \
**Costs of Failure Types \
Benefits of Success Types \
Above Tradeoffs in Data Science Metrics** \
Costs of Failure: If the route drawn and the cost of having a truck + driver does not justify the costs of the project, there would be monetary costs incurred.  
Benefits of Success: Popularity with the neighborhood shoppers; if the pilot gets buy in from farmer’s markets, they might decide to give discounts to the grocery store as it creates a big distribution outlet for them. 
Data Science Metrics to measure both would be dollar loss & profit. 


***Collaborative Scoping - Evaluation*** \
**Expected Performance of Proposed Data Science Solution \
Size of Business Impact Driven by this Expected Performance \
Validation Method** \
We expect this to be an expensive project but given its ‘prestige’ value, it might justify the extra costs incurred. If successful and has a buy in from the shoppers as well as farmer’s markets/ farmers, the potential distribution network created could create a big impact in terms of creating a local food distribution channel. 

Validation of the DS project will be in customizing a route that can minimize mileage for the truck and maximize the diversity of products. 


