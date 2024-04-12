# Project Description
This repository contains a codebase for an online store application that provides functionalities for user authentication,user dashboard and a checkout process.

## Running the project
My projects runs under the above listed functionalities.

### User authentication
This is where a user keys in their details (email and password) for them to proceed or navigate to the user dashboard. if the user enters an incorrect password or username, access to the dashboard will be denied.To be able to login ,user must have their details indicated in the db.json file where they are permanently stored else they're unrecognised hence access to the dashboard will be denied.

#### User dashboard
After a successful login, the user will now navigate in the dashboard. This where all the products available in the store are displayed having their details well indicated i.e. the product's title,price,category and rating where users can browse through for purchase by clicking on the "add to cart" button that's shown below every product.

In relation to real life situation where we pick items from the shelves in a supermarket putting them in a basket to pay after selection is what is happening here literally. In this case "my cart" is the user's  basket.

By clicking on the "Add to cart" button, the product selected will be added to the "my cart" list where the products are stored locally. "My cart" list contains all the products that the user has selected for purchase. After adding any product to cart the "Add to cart" button gets disabled to avoid the user from selecting the product multiple times. 
if the user wants to remove a product from the cart they use the "Remove from cart" button that's just right below the product and the product will be removed hence the number of products in the cart will reduce.

After picking items in a supermarket you must proceed to the counter and make some payments for you to possess the items. The same thing is happening here,after the user adds to cart their preferred product, they will have to make some payment for the products. in the "My Cart" page,the  total amount for all the selected products shows on the top left of the page. just alongside the "Total" is the "proceed to checkout" where you click to navigate to where the user will make their payments.

##### Checkout process
In this page is a written procedure on how the user will make their products' payment. After making the transaction,the user is expected to upload their receipt or key in their payment code for confirmation purposes then click on the "submit" button for submission. If the user tries to submit without the payment code or receipt uploaded,they'll get a "please fill out this field" error message.

After making the payments, the user clicks on the "logout" button on the top right to exit the website page.

###### My API
In this project,i've used an open public API to fetch information about the products.
https://fakestoreapi.com/products =This is the products API
images/saf.png = This is the API i've used to fetch my checkout image.

on the users.json i input the data manually,,,created my own API.

 


# Future improvements
- Search functionality
- Category listing
- Account creation
- Admin panel to manage products and accounts
- Payment integration