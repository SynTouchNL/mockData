# Product dataset generator

When discovering new applications as a data engineer, it is sometimes hard to exactly pinpoint the difference.
Reading capabilities and going over the new application using clean test data does not give you enough information.
This script is build to generate a product orders dataset that can be used to test new applications.
The data set is artifically "decleaned" so that it can serve this purpose.

## Columns

- column_id: The id of the user
- customer_name: The name of the customer
- customer_email: The email of the customer
- order_data: The date on which a product is ordered
- product_id: The id of a product
- product_name: The name of a product
- product_price: The price of a product 

## How to run
- Download the code from this github page
- Look at the variables in main.py and change to your liking
- install a vm with the command make make_vm
- Install the dependencies using the requirement file
- Execute main.py
- The resulting files can be found in the output folder
