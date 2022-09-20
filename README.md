# FakeStoreAPI by @rokuzzz and @alexh0810
## About
The [FakeStoreAPI](https://funshopping-api.herokuapp.com/api-docs/) provides free online e-commerce REST API. Can be used to develop front-end projects when placeholder data is needed without running any server-side code. 

Main paths are: 
- Users
- Admin
- Products
- Categories
- Carts

Project was developed by Roman Kuzero and Hoan Ho.

## Used Technologies
- TypeScript
- Node.js
- Express.js
- Mongoose
- Swagger
- Jest

## Getting started

1. Clone the repo
```
git clone https://github.com/alexh0810/fs11-backend.git
```
2. Install NPM packages
```
npm install
```
3. Create an .env in the root folder as instructed in .env.example.

4. Run the application
```
npm run start
```
or 
```
npm run start:dev
```

## Usage
you can fetch data with any kind of methods you know (fetch API, Axios, jquery ajax, etc.)
### Get All Products
```js
fetch("https://funshopping-api.herokuapp.com/products")
  .then((res) => res.json())
  .then((json) => console.log(json));
```
### Get Single Product
```js
fetch("https://funshopping-api.herokuapp.com/products/{id}")
  .then((res) => res.json())
  .then((json) => console.log(json));
```

## Deployment link

[Amaizng FakeStoreAPI](https://funshopping-api.herokuapp.com/api-docs/)
