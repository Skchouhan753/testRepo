Write Mongo query to retrieve documents from the products where supplier_id is 3 .
-- db.products.find({"supplier_id":3})

Write Mongo query to retrieve the documents from the orders collection with "status": "shipped".
-- db.orders.find({"status":"shipped"})

Write Mongo query to find buyers who from state CA ?
-- db.buyers.find({"address.state":"CA"})

Write Mongo query to retrieve the amount,paymentstatus and paymentMethod from payments.
-- db.payments.find({},{amount:1,paymentstatus:1,paymentMethod:1})

Write Mongo query to retrieve documents from the orders without _id.
-- db.orders.find({},{_id:0})

Write Mongo query to retrieve name,price from the products .
-- db.products.find({},{name:1,price:1})

Write Mongo query to find buyers city and zip code ?
-- db.buyers.find({},{"address.city":1,"address.zip":1,})

Write Mongo query to find buyers name,email, city and zip code ?
-- db.buyers.find({},{"name":1,"email":1,"address.city":1,"address.zip":1})

Write Mongo query to find suppliers name and phone ?
-- db.suppliers.find({},{"name":1,"phone":1})

Write Mongo query to find suppliers name and phone ?
-- db.suppliers.find({},{"name":1,"phone":1})

Write Mongo query to find buyers name,email, city and zip code ?
-- db.buyers.find({},{"name":1,"email":1,"address.city":1,"address.zip":1})

Write Mongo query to find buyers city and zip code ?
-- db.buyers.find({},{"address.city":1,"address.zip":1})

Write Mongo query to retrieve name,price from the products.
-- db.products.find({},{"name":1,"price":1})
