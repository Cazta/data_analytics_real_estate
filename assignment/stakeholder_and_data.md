# Stakeholder Driven Real Estate Data Analysis

Dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

Stakeholder: 
+ Family of 7 incl. 5 children
+ Very limited financial resources (assuming low 15% of market)
+ nice, social neighborhood (meaning central and family friendly)
+ asking for recommendation it buying timing and feasible criteria


[Data card on Kaggle](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

[King County official data (source)](https://info.kingcounty.gov/assessor/esales/Glossary.aspx)

[Best zip codes for families in King County](https://www.niche.com/places-to-live/search/best-places-for-families/c/king-county-wa/?map=true&page=4)

[Most family friendly neighborhood in King County](https://www.niche.com/about/methodology/best-places-for-families/)

The score includes public schools, rate of higher education in the population, cost of living, crime rates, family amenities, diversity, percent of household with children, percent of children below poverty, residents 17 years old an under - based on the US Census.


### Column Definitions

+ social-ngh (engineered feature) - dummy for most family friendly districts (A-rating) in Seattle and suburbs
+ id - Unique ID for each home sold
+ date - Date of the home sale
+ price - Price of each home sold
+ bedrooms - Number of bedrooms
+ bathrooms - Number of bathrooms, where .5 accounts for a room with a toilet but no shower
+ sqft_living - Square footage of the apartments interior living space
+ sqft_lot - Square footage of the land space
+ floors - Number of floors
+ waterfront - A dummy variable for whether the apartment was overlooking the waterfront or not
+ view - An index from 0 to 4 of how good the view of the property was
+ condition - An index from 1 to 5 on the condition of the apartment,
+ grade - An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design
+ sqft_above - The square footage of the interior housing space that is above ground level
+ sqft_basement - The square footage of the interior housing space that is below ground level
+ yr_built - The year the house was initially built
+ yr_renovated - The year of the house’s last renovation
+ zipcode - What zipcode area the house is in
+ lat - Lattitude
+ long - Longitude
+ sqft_living15 - The square footage of interior housing living + space for the nearest 15 neighbors
+ sqft_lot15 - The square footage of the land lots of the  nearest 15 neighbors


+ For engineered features see presentation.pdf in this repo 



