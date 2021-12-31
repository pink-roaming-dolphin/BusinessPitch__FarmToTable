## Farm to Table Aisle ##

**Abstract**

The goal of this project was to pitch a certain grocery store chain based in NYC to start a 
Farmers’ Market Aisle and to stock it in accordance with the data science proposal we formulated. 
I used the database from USDA about Farmers’ Markets (FM), looking at which products are more likely to be available 
at the FMs as well as which days of the market they are most likely to be found at. 
The project outlines a pilot program in which a Grocery Store’s truck makes the daily rounds at the closest markets 
and aims to gather as many of the broader “Basics, Necessities, Good to Have” categories as possible. 

**Design**

This project pitches a ‘farm to table aisle’ to a major grocery store chain making available 
a high variety of farmers’ markets’ products around the clock. The data science solution proposes 
that given the location of a pilot program, in this case a grocery store at the highest income zip code in Brooklyn, 
we can look at the surrounding markets by the day of the week they are active in and build a route 
for a truck to cover farmer’s markets sourcing a certain percentage of the products needed at the grocery store. 
The numbers were chosen as 75% of the basic product category (1st tier), 50% of the necessities product category (2nd tier) 
and 25% of the good-to-have product category (3rd tier). The assumption was made that at most 5 markets would be visited. 

**Data**

- Original Dataset and Preliminary EDA (with initial visualizations) available here: 
[USDA Farmers Market Data](https://docs.google.com/spreadsheets/d/1rVTCxVADSRfiZGJwZ2GEJfxN4AseuxPIXi-up3wFEcg/edit#gid=537680647)

(Dataset obtained from: [Kaggle](https://www.kaggle.com/madeleineferguson/farmers-markets-in-the-united-states))

The data set contained 8804 markets to start off with, with 59 features for each market. 
After an initial EDA on the larger dataset, we decided to focus on the markets in NYC, with 143 markets. 
Of the features 29 of them focused on what products were sold at the market, and the rest included information such as: 
location and coordinates of the market, which seasons it was active in, the dates and times, whether credit card was accepted 
as well as four different categories of benefits and lastly social media information. Engineering was done around the products, 
categorizing them into subcategories and then further dividing them into 3 groups of basics, necessities and good-to-have’s. 
Further engineering was done around the days of the market; finding the distance between the market to pilot programs 
(pilot programs chosen by uploading another data set from CCC New York, Citizens’ Committee for Children) and listing distances 
to pilot according to day. Benefits and credit offerings as well as credit usage were also engineered to be categorized as percentages. 

Further initial EDA was performed on 3 datasets: Brooklyn Food Waste: Research on date labels found on dumpster dived food 
(https://www.kaggle.com/ursulakaczmarek/brooklyn-food-waste), as well as DSNY(Department of Sanitation New York)’s Organics Collection Tonnages data 
and Food Scrap Drop Off Locations data. An initial EDA analysis on these three sets was done to see the possibility of 
food waste / farmers’ markets partnerships through the grocery store’s initiative; the preliminary findings can be found 
in the Appendix of Presentation as well as spreadsheets.

**Algorithms**

- A portion of the original USDA The Farmers’ Markets Database was chosen using Python. 
- Exploratory analysis was done in Google Sheets. 
- Tableau was used  in visualization of the Farmers’ Markets and Google Sheets visualizations were performed for the preliminary analysis of the Food Scraps (Future Work section). 

**Tools**

- Pandas for initial data selection 
- Tableau for interactive visualization 
- Google Sheets for exploratory data analysis and initial visualization 

**Communication**

A pitch was prepared for the Grocery Store Chain and the findings from our data analysis were presented. 
