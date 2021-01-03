# Combining-Data-Flat-FIle-API-and-Website
I was tasked to combine three data sources to create one database. The three sources come from a website, an API and a flat file. The API and flat file are related by Type. For example, the cocktail recipe will call for vodka and that is a Type in the flat file. The flat file and total wine are related by the product name. For example, the Tanqueray is in the flat file as well as on the Total Wine Website. I had to clean the data significantly to combine the data. This database could help bars and restaurants price cocktails. 

-	Website 
-- https://www.totalwine.com/
  o	Reviews on liquor
  o	Price of liquor today
•	API
  o	https://www.thecocktaildb.com/api.php?ref=apilist.fun
  o	Cocktail recipes
  o	Includes up to 15 ingredients. 
•	Flat File
  o	https://www.kaggle.com/schmidtpalexander/worlds-largest-liquor-store-product-list
  o	Price of alcohol (Price per litter)
  o	Name of Alcohol
  o	Product Group
  o	Type
  o	Style
