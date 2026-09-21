# EXP-6: SQL Queries using Node.js, Express.js and SQLite

## Description

This project demonstrates SQL queries using a SQLite database with Node.js and Express.js. It provides a REST API to retrieve and work with product data.

## Technologies Used

- Node.js
- Express.js
- SQLite
- JavaScript
- REST API

## Features

- SQLite database for storing product information
- REST API for retrieving products
- SQL queries for product data
- Express.js server

## API Endpoint

### Get All Products

**GET**
`/products`

Returns all products from the SQLite database.

### Live Website

https://exp6-query.onrender.com/products

## Sample Response

```json
{
  "count": 5,
  "products": [
    {
      "id": 1,
      "name": "Laptop",
      "category": "Electronics",
      "price": 999.99,
      "year": 2023
    }
  ]
}
## How to Run

Install the required packages:

```bash
npm install

start the server:
node server.js

The server will run on:
http://localhost:3000

Deployment
The project is deployed using Render.

Live URL:
https://exp6-query.onrender.com/products
