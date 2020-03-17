# Property Price Prediction for King County
![Image description](https://www.racialequityalliance.org/wp-content/uploads/2016/10/assessors_social-1.jpg)

Real estate decision makers would benefit from accurate forecasts of house prices and of the variance of future prices. For example, developers and investors could decide whether the projected returns from a housing development were sufficient to offset the risks. Prospective homeowners could balance the consumption value of a home against risks and rewards from the investment component.

By this Project we can help buyer as well as seller

Housebuyer: This client wants to find their next dream home with a reasonable price tag. They have their locations of interest ready. Now, they want to know if the house price matches the house value. With this study, they can understand which features (ex. Number of bathrooms, location, etc.) influence the final price of the house. If all matches, they can ensure that they are getting a fair price.

Houseseller: Think of the average house-flipper. This client wants to take advantage of the features that influence a house price the most. They typically want to buy a house at a low price and invest on the features that will give the highest return. For example, buying a house at a good location but small square footage. The client will invest on making rooms at a small cost to get a large return.

---------------------------------------------------------------------------------------------------------------------------
#### Overview

1. Importing Modules
2. Data Preprocessing
3. Creating a Simple Linear Regression
4. Visualizing and Examining Data
5. Binning
6. Multiple Regression
7. Regularization
- Ridge
- Lasso


---------------------------------------------------------------------------------------------------------------------------
#### Key findings and conclusions:

1. My model shows that the primary driver for property prices in King County is the square footage of the living space. Property prices are also highly impacted by its location in the city (derived from zipcode): in particular, properties in premium areas in and near the city have higher prices than it outer suburbs. Building grade as set by the county authority is also another factor as higher grade properties are in better condition and thus can fetch a higher price. Waterfront view is another factor that pushes the property price up due to the prime views.

2. With an r-squared value of 0.73 by polynomial regression(degree=3) for our model, can conclude that the property price in King County can be reasonably predicted. However, I am confident that the model can be further refined if more data is available. As our model factors in the impact of the location, additional area information (for example, by zipcode) such the number of schools, public transportation and crime rate would be very useful. We believe that the high property prices in the premium areas of the city are partly driven by these factors.

3. I worked on the assumption that areas with significantly higher price per square feet (of living space) than the overall county constitute as premium locations. Cross-referencing our findings with a zipcode map , we noted that Seattle (Highest Price: $4000000) is most premium location in King County, driven by its proximity to the city centre and great waterfront views facing Lake Washington. In addition, zipcodes around Belleview and downtown Seattle are also identified as premium locations.

