# Dagens Job Test

Hi applicant!

This repo contains the starter code for Dagens job test, as well as the task description. Please see README.md in `server/` and `client/` folders on how to install dependencies and start the server and client. The intention with this test is to have a look at how you solve a pretty straight forward problem, and then discuss it afterwards.

- The server has an _in-memory_ "database"-array with 1000 products. This is your database, you are _not_ supposed to set up any database service like MongoDB or write to file or persist data in any way.

- We're using the three categories `<meat, greens, fish>` in the pre-populated database, but feel free to let the user add more categories if you like - no right or wrong.

- Styling/CSS is _not_ important.

- Adding too much abstraction, handling every possible error and adding validation for every input and endpoint won't give you any extra points.


### Tasks

1. Users should be able to create products from a form page. The products should be appended to the database (see `server/db.js`).

2. Create one endpoint to get products. It should be possible to filter by category, maximum and minimum price. The endpoint should be paged with a page size of 24 products per page. No need to write frontend code.

3. Create one endpoint that takes a product id parameter and returns the `N` products with nearest price in the same category. You can choose `N` yourself. No need to write frontend code.

### Delivery

Clone the repo, solve the tasks and push your code to a public GitHub repo, Bitbucket repo, or similar. Send a link to the solution to Dagens.




