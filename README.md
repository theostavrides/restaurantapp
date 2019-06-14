# Restaurant Pickup
A web app for a fictitious restaurant that provides an order pickup service. Users can view the restaurant's menu and create their order, which the Restaurant can then accept or decline.  Users will be notified of their order status through the site and via SMS.

<br><br>
<img src="https://raw.githubusercontent.com/theostavrides/restaurantapp/master/screenshots/home.png" />
<img src="https://raw.githubusercontent.com/theostavrides/restaurantapp/master/screenshots/menu.png" />
<img src="https://raw.githubusercontent.com/theostavrides/restaurantapp/master/screenshots/cart.png" />
<img src="https://raw.githubusercontent.com/theostavrides/restaurantapp/master/screenshots/confirmed.png" />

## Features
- Users can view the restaurant's menu
- Users can build their own cart
- Each cart can contain one or more items with mulitple quantities
- Users can start a place an order with the restaurant
- Restaurant can choose to accept an order and provide the user with an ETA
- Users will be notified of their order status via browser and SMS text

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Run migrations: `npm run knex migrate:latest`
  - Check the migrations folder to see what gets created in the DB
6. Run the seed: `npm run knex seed:run`
  - Check the seeds file to see what gets seeded in the DB
7. Run the server: `npm run local`
8. Visit `http://localhost:8080/`

## Dependencies

- Node 5.10.x or above
- NPM 3.8.x or above
- body-parser
- dotenv
- ejs
- express
- knex
- morgan
- Sass
- Postgre SQL
- Twilio
