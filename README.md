Hash-Products
=============
To turn in:
	Attach a file hash_lastname.rb as an attachment to the assignment in Canvas
	Subject line: CIS 282, Name, Hash

To do:
Create a menu driven program to interact with a set of products.
You’ll use a hash where a random 3 digit number is the key and the value
is a two element array containing the name of the product and the price.
Initialize the hash with at least 5 products.

The format of the hash would look like this:
products = {124=>[“shoes”,59.99], 352=>[“shirt”,19.99]}

	Your program will let the user:
■	view all products
■	add a new product (make sure key is unique, in other words don’t overwrite existing pair)
■	delete a product (give error message if product does not exist)
■	update a product (give error message if product does not exist)
■	view highest priced product
■	view lowest priced product
■	view sum of all product prices
■	exit
