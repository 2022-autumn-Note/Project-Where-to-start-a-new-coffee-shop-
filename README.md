# Project-Where-to-start-a-new-coffee-shop-
A competition project on Datacamp:https://app.datacamp.com/workspace/w/09ede490-2d7a-4ff7-b767-8841ded65b99/edit#where-to-open-a-new-coffee-shop


Where to open a new coffee shop?
📖 Background
You are helping a client who owns coffee shops in Colorado. The company's coffee shops serve high-quality and responsibly sourced coffee, pastries, and sandwiches. They operate three locations in Fort Collins and want to expand into Denver.
Your client believes that the ideal location for a new store is close to affluent households, and the store appeals to the 20-35 year old demographic.

Your team collected geographical and demographic information about Denver's neighborhoods to assist the search. They also collected data for Starbucks stores in Denver. Starbucks and the new coffee shops do not compete for the same clients; the team included their location as a reference.
💾 The data
You have assembled information from three different sources (locations, neighborhoods, demographics):

Starbucks locations in Denver, Colorado
"StoreNumber" - Store Number as assigned by Starbucks
"Name" - Name identifier for the store
"PhoneNumber" - Phone number for the store
"Street 1, 2, and 3" - Address for the store
"PostalCode" - Zip code of the store
"Longitude, Latitude" - Coordinates of the store

Neighborhoods' geographical information
"NBHD_ID" - Neighborhood ID (matches the census information)
"NBHD_NAME" - Name of the statistical neighborhood
"Geometry" - Polygon that defines the neighborhood

Demographic information
"NBHD_ID" - Neighborhood ID (matches the geographical information)
"NBHD_NAME' - Nieghborhood name
"POPULATION_2010' - Population in 2010
"AGE_ " - Number of people in each age bracket (< 18, 18-34, 35-65, and > 65)
"NUM_HOUSEHOLDS" - Number of households in the neighborhood
"FAMILIES" - Number of families in the neighborhood
"NUM_HHLD_100K+" - Number of households with income above 100 thousand USD per year

Starbucks locations were scrapped from the Starbucks store locator webpage by Chris Meller.
Statistical Neighborhood information from the City of Denver Open Data Catalog, CC BY 3.0 license.
Census information from the United States Census Bureau. Publicly available information.
💪 Challenge
Provide your client a list of neighborhoods in Denver where they should consider expanding. Include:

A visualization of Denver's neighborhoods and the Starbucks store locations.
Find the neighborhoods with the highest proportion of people in the target demographic.
Select the top three neighborhoods where your client should focus their search.
Note:
To ensure the best user experience, we currently discourage using Folium and Bokeh in Workspace notebooks.

🧑‍⚖️ Judging criteria
This is a community-based competition. The top 5 most upvoted entries will win.

The winners will receive DataCamp merchandise.

✅ Checklist before publishing
Rename your workspace to make it descriptive of your work. N.B. you should leave the notebook name as notebook.ipynb.
Remove redundant cells like the judging criteria, so the workbook is focused on your work.
Check that all the cells run without error.
⌛️ Time is ticking. Good luck!
