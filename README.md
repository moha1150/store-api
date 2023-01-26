# store-api

This code is a Node.js web API that uses the Express.js framework to handle HTTP requests and Mongoose.js to interact with a MongoDB database. It defines routes for creating, fetching, updating, and deleting products and wishlists, using Mongoose models for the Product and Wishlist collections. The API allows users to:

Post a new product to the database, using the title and price from the request body
Get all products from the database
Create a new wishlist with a default title, or add a product to an existing wishlist
Get all wishlists, including the products in each wishlist
Delete a wishlist by its ID
To use this API, you will need to have Node.js and MongoDB installed, and run the MongoDB server on your localhost. You also need to install the necessary npm modules by running npm install in your project directory.

To run the API, use the command node server.js or nodemon server.js (if you have nodemon installed) and it will start listening on port 3000.
