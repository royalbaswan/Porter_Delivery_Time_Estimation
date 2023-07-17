                                            Porter Delivery Time Estimation

### Problem Statement

Porter is India's Largest Marketplace for Intra-City Logistics. Leader in the country's $40 billion intra-city logistics market, Porter strives to improve the lives of 1,50,000+ driver-partners by providing them with consistent earning & independence. Currently, the company has serviced 5+ million customers

Porter works with a wide range of restaurants for delivering their items directly to the people.

Porter has several delivery partners available for delivering the food, from various restaurants and wants to get an estimated delivery time that it can provide the customers based on what they are ordering, from where, and also the delivery partners.

This dataset has the required data to train a regression model that will do the delivery time estimation, based on all those features

### Data Dictionary
Each row in this file corresponds to one unique delivery. Each column corresponds to a feature as explained below:

* market id: integer id for the market where the restaurant lies

* created at: the timestamp at which the order was placed

* actual delivery time: the timestamp when the order was delivered

* store_primary_category: category for the restaurant

* order protocol: integer code value for order protocol(how the order was placed le: through porter app, call to restaurant, pre booked, third party, porter website and others)

* total items: no of items in the order

* subtotal: final price of the order(in rupees)

* num_distinct items: the number of distinct items in the order

* min_item_price: price of the cheapest item in the order

* max_item_price: price of the costliest item in order

* total_onshift_partners: number of delivery partners on duty at the time order was placed

* total_busy_partners: number of delivery partners attending to other tasks

* total_outstanding_orders: total number of orders to be fulfilled at the moment

* estimated_store_to_consumer_driving_duration: approximate travel time from restaurant to customer
