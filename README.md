# D3.js Skills Test
## Objective
This is a small test to determine whether your skills are suitable for a role in working with the Panalysis team using the D3.js visualisation library.

Please note that this is not just a test of your technical skills. We are looking for people to work with us who can take both broad directions or detailed specifications and deliver professional results.

Your response will be assessed on the following criteria:
* __Technical Skills__. I.e. have you demonstrated that you have sufficient experience and understanding in applying the D3.js and related libraries.
* __Visual Techniques__. We will be assessing the work on how well it has been designed. 
* __Creative Approach__. How innovative is your work.

## Task Details
The task is to design and create a geographic visualisation of sales data from a small e-commerce website.

The problem that the client is trying to solve is to find a way to understand how their sales are distributed across the country by suburb and state. They want to see the total number of transactions as well as the total revenue by suburb and state. Revenue should only be for the sale but not including shipping and taxes.

An additional criteria is to display the shipping costs per suburb and state.

Three files are supplied:
* au-states.geojson: This is the map of Australia and its states in the GeoJSON format
* orders_export.csv: This is the data from the ecommerce website (see data dictionary below)
* Australian_Post_Codes_Lat_Lon.zip: A CSV file that contains the postcode, name of the suburb and the latitude and longitude coordinates for that suburb.

## Order Data File Fields
| Field | Description |
| --- | --- |
| ID | Transaction Identifier |
| Subtotal | The total revenue for all items purchased |	
| Shipping | The cost of shipping the items |
| Taxes | Tax for the sale |
| Total | Subtotal + Shipping + Taxes |
| Created at | Date & time of the sale |
| Billing City | Suburb for the customer |
| Billing Zip	| Postcode for the customer |
| Billing Province | State for the customer |
| Billing Country | Country for the customer |

## Submitting Your Work
Please create a zip file of your work and submit this via Upwork or alternative create a Git repository and send the details.