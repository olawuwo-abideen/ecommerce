# Ecommerce

Backend to an e-commerce platform that empowers businesses to sell products online and enables customers to login, browse, shop, give reviews and make secure online purchases. This
application aims to provide a seamless shopping experience with a focus on user-friendly design, product management, and payment processing.

## Features

- **User**: User can register, login, logout, update profile, and update password.

- **Order**: User can update, get, and create Order.

- **Products**: Admin can update, get, and create Product.

- **Review**: User can update, get, and create Reviews.

## Built With:

- JavaScript
- Node
- Express
- dotenv
- mongoose
- nodemon
- cors
- bcryptjs
- express-async-error
- helmet
- joi
- swagger-ui-express
- jsonwebtoken
- http-status-code
- morgan

## Installation

- clone the repository

```sh
git clone git@github.com:olawuwo-abideen/ecommerce.git
```

- navigate to the folder

```sh
cd ecommerce.git
```

## Run the app in development mode

Open a terminal window session, or the equivalent on your machine, and enter the following command to install all the
Node modules needed to run the app:

```sh
npm install
```

After doing an `npm install` enter the following `npm start` command:

```sh

npm start

```

Set up the environment variables:

Create the .env file and setup the MongoDB URL.

The server will start running on the specified port (default: 3000) and establish a connection to the MongoDB database.

This will start the app and set it up to listen for incoming connections on port 3000. Open up your browser of choice
and go to the url

```sh

http://localhost:3000

```

to start using the app.

## API Endpoints

The following API endpoints are available:

- BaseUrl https://localhost:3000/

- `POST /api/v1/register` - Register a new user
- `POST /api/v1/login` - User login
- `GET /api/v1/logout` - User logout
- `GET /api/v1/showMe` - Show authenticated user
- `PATCH /api/v1/updateUser` - Update User Profile
- `PATCH /api/v1/updateUserPassword` - User update Password

* `GET /api/v1/showAllMyOrders` - Show all user order
* `GET /api/v1/:id` - Get an order
* `PATCH /api/v1/:id` - update an order

- `GET /api/v1/:id/reviews` - Get user review
- `PATCH /api/v1/:id/reviews` -Update user review
- `DELETE /api/v1/:id/reviews` - Delete user review

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/olawuwo-abideen/ecommerce/issues).

## Authors

👤 **Olawuwo Abideen**

- GitHub: [@Olawuwo Abideen](https://github.com/olawuwo-abideen)
- Twitter: [@Olawuwo Abideen](https://twitter.com/olawuwo_abideen)
- LinkedIn: [@Olawuwo Abideen](https://www.linkedin.com/in/olawuwo-abideen/)
