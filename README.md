# Chapa-Integration
# Chapa Payment Integration
 Implementation of payment with [Chapa API](https://developer.chapa.co/docs/overview) using [expressjs](https://github.com/expressjs/express)

# Getting started
To get the Node server running locally:
- Open this folder with your favorite IDE or text editor
- <code>npm install</code>on cmd or terminal to install all required dependencies
- <code>npm run dev</code> to start the local server
- download xampp from [here](https://www.apachefriends.org/download.html) and import the database from the folder <code>chapa_app</code>
- <code>http://localhost:4400</code> go to this URL after the server starts running

# Code Overview

## Dependencies
- [mysql2](https://github.com/sidorares/node-mysql2) - The MySQL client for Node.js
- [expressjs](https://github.com/expressjs/express) - The server for handeling and routing HTTP requests
- [axios](https://github.com/axios/axios) - The Promise based HTTP client
- [ejs](https://github.com/mde/ejs) - The view engine or the front end of our app

## Application structure
- <code>index.js</code> - The entry point to our application
- <code>views/</code> - This folder contains our front end

# Running phase and requirements

In order to make a test transaction

- Go to [Chapa](https://dashboard.chapa.co/register) and register
- After registration go to setting > API and get your SECRET-KEY
- Paste the KEY in the proper section inside <code>index.js</code> I have used my own secret key but you can use yours too and paste it in the proper section ( Authorization: `Bearer YOUR SECRET KEY` ) In the index.js.
- Also get a Testing card from Chapa [Here](https://developer.chapa.co/docs/testing-cards/) 
- And Testing mobile from [Here](https://developer.chapa.co/docs/testing-mobile/)
- Now you are good to go
