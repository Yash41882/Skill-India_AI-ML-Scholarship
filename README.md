# Skill-India_AI-ML-Scholarship
Repository shows the inventory based project management using json file

In Records.json file:
This is a inverntory of a Gym Supplement store.
1. It contains 50 Product Id's and each has 5 parameter that are - Name, Flavour, Price, Quantity and importor

In Adding a new Product:
We add the details of new product Id, Name, Flavour, Price, Quantity, and Importer and append it to existing records.jso file.

In Purchasing and Sales:
We check if the entered used_id is correct of not,
  then we check if we have enough quantity or not
    if condition satisfises then we proceed to billing and execute the order
       also if billing amount is more than 5000 than 20% discount is applied
          final bill is shown
          
Then we update the quantity and revert it back to records.json
also we generate the sales at the end.
