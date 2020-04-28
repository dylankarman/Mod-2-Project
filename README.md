Which factors correlate the most with the price of a house?
Through the KC housing prices data set provided, we are able to find out whether or not the variables such as the number of bedrooms and bathrooms etc, correlate with and affect the price of a house, negatively or positively. 
Through data cleaning and using my own best judgement I was able to fill or drop missing values from the data set. This allowed me to then normalize the data which puts all of the variables on the same field so that the machine can run the regression. 
After going through the data and running train/test models, I have determined that every variable effects the housing price in a positive way.

# Column Names and descriptions for Kings County Data Set
* **id** - unique identified for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zipcode** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
