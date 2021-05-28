# React Bookstore App

## Introduction
The web app is built with the MERN stack.
Versions:
- Node: 16.0.0
- React: 17.0.2
- MongoDB: 4.4.5
- Express: 4.17.1

## Instructions
(1) Start the mongoDB database.
No additional step is required, only need mongoDB CLI installed and has it started as system service.

Installation guide: https://docs.mongodb.com/manual/mongo/

(2) Start Server.
The system must have Node installed.
Installation guide: https://nodejs.org/en/
Default port: 5000

```
cd server
npm install
npm run data_import
npm start
```

(3) Start Client
```
cd client
npm install
npm start
```

(4) To access the main page, the default url is: localhost:3000

## Requirements
### Functionalities
- Login page: accomplished with cookies. When user with correct credential log in, server sends a cookie with verified token.
- Create account page: will send a post request to server, if deny registration if username already exist. Also, auto log user in after registration.
- Main page: includes category sorting, search bar and price sorting. Default display every books in the database.
- Book info page: display single book with all information
- Cart page: will tell user if there is no items in cart, otherwise show details of cart such as quantity, price and sum. Implemented with local storage
- Invoice: Display import after checkout
- Checkout: prompt user to register or login if no login cookie, otherwise show address form. 
- Logout page: same page as login page, only show when user is logged in.

### UI/UX
- Responsive web features: web pages are designed for both mobile and desktop view. 
- CSS implementation: done with component library: chakra UI.

## Screenshot
![main_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/main.png "main")
![register_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/register.png "register")
![cart_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/cart.png "cart")
![book_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/book.png "book")
![delivery_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/main.png "delivery")
![invoice_page](https://github.com/manyan-chan/BookStore-React-App/blob/master/screenshot/main.png "invoice")
