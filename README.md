## Project Proposal

Airbnb is an online marketplace which bridges the gap between property owners and those looking to rent a space. With listings in over 220 countries, it is no surprise that this company has rapidly increased in popularity. Airbnb has allowed various countries, regions, and cities to experience a tremendous economic impact. The United States, specifically, has earned over 33.8 billion dollars from Airbnb traffic, alone. 

Perhaps one of the most popular cities in the world and on Airbnb is New York City. Boasting over 65 million visitors per year, NYC attracts tourism for its art, history, entertainment, food, architecture, and energy. For this reason, this project serves to explore a NYC Airbnb dataset to learn more about the distribution of rental properties, the impact of location on price, and other various features that impact a property’s price, number of reviews, or availability.    
 
Sources:
- https://www.osc.state.ny.us/reports/osdc/tourism-industry-new-york-city#:~:text=New%20York%20City%20hosted%2066.6,reduction%20(see%20Figure%201).
- https://www.stratosjets.com/blog/airbnb-statistics/#:~:text=Airbnb%20has%20listings%20in%20more%20than%20220%20countries%20and%20regions.&text=People%20stay%20an%20average%20of,Airbnbs%20than%20at%20hotel%20stays.





## Questions:

- How are Airbnb properties distributed in NYC? (Borough and Neighborhood)
- How do considerations like location, number of reviews, and availability affect price of Airbnb property?
- Which neighborhoods have the most listings?
- Which borough or neighborhood has the most affordable properties?


These are interesting questions to consider as they have the potential to reveal what features a customer finds most valuable. For example, will a customer go for a property at a higher price point due to its location, or will they trade of a popular location for a lower priced property. 


## Data

- https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

## Variables

| Variable Name | Type | Description |
|:- |:- |:- |
|id | (int64) |ID of listing                          
|name | (object)| Name of listing
|host_id |(int64) |ID of property owner
|host_name |(object) |Name of property owner
|neighbourhood_group| (object) |Borough
|neighbourhood| (object) | Neighbourhood / Area
|latitude |(float64) | latitude of listing
|longitude |(float64) |longitude of listing
|room_type| (object) | listing space type
|price |(int64) : | price in dollars
|minimum_nights |(int64) | amount of nights minimum 
|number_of_reviews |(int64) |number of reviews
|last_review| (object) | latest review
|reviews_per_month |(float64) |number of reviews per month
|calculated_host_listings_count |(int64) |amount of listing per host
|availability_365 |(int64) |number of days when listing is available for booking
