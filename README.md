# Lighthouse BnB

Lighthouse BnB is an app that will revolutionize the travel industry!
It's a full-stack app that allows users to rent out their homes to people on vacation, search from a database of listings, make reservations, and add reviews for previous bookings.

The purpose of this web application project is to:
- design a database and use server-side JavaScript to display the information from queries to web pages
- build back-end SQL queries that allow users to search for accommodations in an online travel app 
- connect to PSQL and write the queries that deliver the right data to the front end, enabling interaction with the data from a web page

## Getting Started

1. [Create](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) a new repository using this repository as a template.
2. Clone your repository onto your local device.
3. Install dependencies using the `npm install` command.
4. Create a database called lightbnb from the PSQL terminal and use login info:
- `user:` "vagrant",
- `password:` "123",
- `host:` "localhost",
- `database:` "lightbnb"

5. Run `schema` and `seeds` files against lightbnb database on PSQL using the following command:
- `\i migrations/01_schema.sql`
- `\i seeds/01_seeds.sql`
- `\i seeds/02_seeds.sql`

6. Start the web server using the `npm start` command. The app will be served at <http://localhost:3000/>.
7. Go to <http://localhost:3000/> in your browser.

## Final Product

Landing Page / Sign Up 

![sign up page](https://user-images.githubusercontent.com/100328767/173737227-c7d53e5f-f577-4e45-bce5-4769bae33736.png)

Home Page

![homepage](https://user-images.githubusercontent.com/100328767/173737255-4f4d2c5a-7795-4468-8d88-6aeb02aa8aa2.png)

Search For a Listing

![search listing](https://user-images.githubusercontent.com/100328767/173737288-b55b3576-865e-4bea-afd9-8ae52094e6b2.png)

Create a Listing

![create a listing](https://user-images.githubusercontent.com/100328767/173737311-f9f10772-51d3-4647-9387-e438d255086c.png)

Reservations Page

![reservations page](https://user-images.githubusercontent.com/100328767/173737330-5e708cb5-e51f-4b5c-b41a-8832af92e533.png)

My Listings Page

![my listings page](https://user-images.githubusercontent.com/100328767/173737360-2fa93447-640c-4d03-823a-2a70eeaa8af5.png)

## Dependencies

- bcrypt 
- body parser
- cookie-session
- express
- nodemon
- pg
