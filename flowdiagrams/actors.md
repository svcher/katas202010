Actors
=======

| Actor  | Description  |
|---|---|
| *Customer* | Takes food from frige, reacts to marketing effort, pays, orders, enters health info  |
| *Cook* | Takes orders from the system and makes meals  |
| *Shipper* | Takes food from the kitchen and delivers to the locations   |
| *Meal Analyst* | Enters meal nutrition info and cost structure   |
| Fridge | Dispenses food, authenticates customers, accepts payments   |
| Fiscal Register | Records financial transaction for accounting purposes and audits   |
| Fridge Adaptor | Takes stock data from Fridge for reconciliation, accepts transactions from fridge   |
| Stock Processor | Keeps track of the current stock, expiration dates, creates replenisment orders, predicts demand   |
| Location Controller | Knows physical locations of friges, can compute best route for the shipper, compoute best route for the customer   |
| Customer Health Profile Storage | Stores user health info, preferences   |
| Meal Relevance Mapper | Builds propencity map meal-to-health-feature   |
| Meal Profiler |  Stores meals nutrients features  |
| Customer Reaction Store |  Stores a list of customer reactions, e.g. ordered, cancelled, and bought adhock meals  |
| Customer Mobile App | mobile eComerce |
| Customer Web site | eCommerce site   |
| Admin Web site | Site for analysts to edit info about meals   |
| Shipper's Mobile App | mobile eComerce |
| Cook's Monitor | Tablet App to show new meals to cook, prints barcodes to track ready meals   |
| Order Processor | Shopping cart service |
