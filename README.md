
# Restaurant API

## Introduction.
This is a restaurant api
It has 3 tables restaurant,pizza,restaurantpizza

 
The following routes are available
 
* GET /restaurants: Returns a list of all restaurants in JSON format.
* GET /restaurants/:id: Returns a restaurant and its associated pizzas in JSON format. If the restaurant is not found, it returns an error with status code 404.

* DELETE /restaurants/:id: Deletes a restaurant and its associated restaurant pizzas from the database. If the restaurant is not found, it returns an error with status code 404.

* GET /pizzas: Returns a list of all pizzas in JSON format.

* * POST /restaurant_pizzas: it creates a new RestaurantPizza that is associated with an existing Pizza and Restaurant.if it is not created succesfully it returns an error.

## Ruby Version

2.4.7

## System Dependencies

Developer tools (VS code, build-essential package on Ubuntu, Ruby on rails)

## Configuration

No custom configuration is required for this app

## First-Time Setup

1. Clone the code from GitHub using `git clone https://github.com/jwillie-26/Pizzas-API.git`
2. Read this README ;
3. Install dependencies using `bundle`.
4. Seeding test data-rails db:seed to seed th data.
5. Turn on the server with `rails server`- The server will run on `http://localhost:3000`



Note: To turn off the rails server when you are done, go to the command-line where the rails server is running and type in Ctrl-C (that means hold down the "Ctrl" key and the "c" key at the same time, and then let go).




