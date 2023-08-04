### Introduction
This is a simplified version of a problem that we have encountered and solved at float.

**Situation**: A customer's 3rd party integration has broken. 
It is no longer possible to see through Shopify what the end-customer is returning; only the amount they're returning for.

**Problem**: <br>
To be able to deliver our analytical insights we need to know what items has been returned.

**Data**
`sales.csv` is a sample dataset illustrating this broken integration.
It contains the following columns:
* `order_id` (int): The id of the order
* `item_id` (int): The line item id of the order
* `product_id` (int): The id of the product that was sold
* `product_title` (str): The title of the product
* `sales` (int): The sales value of the item

`returns.json` is a json file where each key and corresponding value is the `order_id` and the amount the end-customer has returned for
The returned amount corresponds to some combination of the items that was sold on the order.
The problem is just: We don't know which.

**What you should do**
Write up a solution that figures out what has been returned.
Test and document your solution based on the sample dataset: `sales.csv` and `returns.json`

Solution rules:
* The solution must be written in Python
* The ideal solution is well-structured and well-documented
* You can use any external libraries of your choice
