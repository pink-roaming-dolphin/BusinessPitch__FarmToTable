**Project Definition/ Title:** \
*FARM TO TABLE GROCERY POP UP: A PROPOSAL TO UNION MARKET* 


***Project Identification*** \
**Problem/ Opportunity:** \
Create a well sourced / optimized farm to table supply chain in order to: 
Initiate a ‘farm to grocery store’ aisle at the local grocery store chain \
**Problem Type:** Grouping \
**Opportunity:** Create a well sourced / optimized farm to table supply chain (Supply Chain Optimization)  \
**Impact:** Incorporate a ‘farm to grocery store’ aisle in the grocery store \
**Solution Path:** Create a list of farmer’s offering the most variety of products \
**Hypothesis:** Given the prevalence of the farm to table movement, we want to incorporate a wide variety of local farmers’ products into our grocery store. We hypothesize that local farmer’s markets are the best places to scout potential farms as suppliers. We want to locate the farmer’s markets with the most diverse set of farms.  


***Non-technical Scoping***\
**Obstacle/ Opportunity/ Business Need \
Potentially Impacted Parties (external/ internal) \
Main Constraints Faced by the Project** \
Inspired by two books, *Grocery: The Buying and Selling of Food in America* by Michael Ruhlman and *The Third Plate: Field Notes on the Future of Food* by Dan Barber; we propose the neighborhood grocery store Union Market that they work with local farmer’s markets in establishing a ‘farm to grocery store’ aisle in the rapidly expanding grocery store chain making available the fresh food that we find in the farmer’s markets around the city available throughout the week. 

Farmers markets host a diverse group of farms, by size, location and products. By working directly with the farmer’s markets, the grocery chain would reach the most diverse group of farmers. We could also partially automate the role of the supply chain organizer at the grocery store by framing the selection of farms out of the list of farms at the farmer’s markets as a mission statement. 

One big constraint of the project is that actually getting in touch with the farmers will require going through the middle man aka the farmer’s market itself. 


***Technical Scoping***\
**Potential Solution Paths: \
Data Sources (ideal/ available)**  \
We will make a list of the most diverse farmer’s markets in the region and decide on a route and time schedule to pick up produce from these farmer’s markets. 

Ideal data set would be a data set with a list of all the farms within 100 miles of Brooklyn, and the type of product they produce. 

We have available the USDA dataset that lists the farmer’s markets in the USA (8804 entries, with 59 columns with info on: city, county, state, social media & website urls, seasons, location, type of payment accepted (cash, credit, SNAP etc), and type of food sold (seafood, herbs, meats, nuts, plants, poultry, wine, coffee, eggs, cheese etc). Of these markets, 673 of them are based in the state of New York which would be the subset we would concentrate on. 
Dataset available at: https://www.kaggle.com/madeleineferguson/farmers-markets-in-the-united-states 

One obstacle here is that only about 250 of these entries have a Time value aka. a non-null value as to when the market is set (eg. Saturday mornings, Monday all day etc). 


***Collaborative Scoping - Current State***\
**Definition of Success (clear goal) \
Current Status Quo & Baseline Performance \
List of Unknowns** \
With this project, a successful outcome would be the selection of an itinerary by day of the week, optimizing total weekly distance driven and maximizing food variety. 

Currently there are local farmers from whom we source products, but it’s not a wide variety of products nor farmers (diversity in terms of large/small, organic/not, type of product etc). 

List of unknowns include: whether this rerouting will amount to profits or losses(!). 
Unknowns: Do the grocery store already employ a truck, or are deliveries done by the suppliers themselves? What is the ‘advertising’ profit from a prestige project like this - does it justify the costs? 


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
Costs of Failure: If the route drawn and the cost of having a truck + driver does not justify the costs of the project 
Benefits of Success: Popularity with the neighborhood shoppers; if gets buy in from farmer’s markets, they might decide to give discounts as it creates a big distribution outlet for them. 
Data Science Metrics to measure both would be dollar loss & profit. 


***Collaborative Scoping - Evaluation*** \
**Expected Performance of Proposed Data Science Solution \
Size of Business Impact Driven by this Expected Performance \
Validation Method** \
We expect this to be an expensive project but given its ‘prestige’ value, it might justify the extra costs incurred. If successful and has a buy in from the shoppers as well as farmer’s markets/ farmers, the potential distribution network created could create a big impact in terms of creating a local food distribution channel. 

Validation of the DS project will be in customizing a route that can minimize mileage for the truck and maximize the diversity of products. 


