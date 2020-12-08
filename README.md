# Dagens Job Test

Hi applicant! This repo contains the starter code for Dagens job test, as well as the problem description for both client and server.

## Read this first

The server has an in-memory "database"-array with 1000 products. This is your database. You are _not_ supposed to set up any database service like MongoDB or similar. Adding, updating and deleting objects from this "database" should simply be altering the array. Don't spend your time on setting up a real database. And don't spend time on reading from / writing to file. 


## Problems

- (server) Write an endpoint, `/products`, where a client can `POST` a JSON payload to create a new product. `/products` accept the following payload, `{name: String, category: String, price: Number}`. The product should be stored in the "database"-array with an `id: String` in addition to the three fields provided.
- (client) Write a form where a user can submit the following JSON payload to endpoint `/products` `{name: String, category: String, price: Number}`. Styling/CSS is not important at all. What we want to see here is that you're able build a form and submit data to an endpoint. You're free to choose whether you want the category to be a free text input, radio buttons, a dropdown or similar. We're using the three categories `<meat, greens, fish>` in the pre-populated database, but feel free to let the user add more categories if you like - no right or wrong here.
- (server) Write an endpoint, `/similar`. This endpoint has one required parameter `?productId=<productId: String>`, this is a product id...




