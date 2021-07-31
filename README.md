# E-commerce-command-
 This application is an e-commerce back end application.  It creates and seed the database as well as contains all of the nessicary routes to create, read, update, and delete data on the database it creates and seeds.  

## Built With: 
* NodeJS
* JavaScript
* mysql2
* Express
* Sequilize

## Instalation:
User should run npm seed 
User should run npm start

## Constructing the Models:
In the Category.js, Product.js, ProductTag.js, Tag.js files I created models using "sequilize" that established tables in the databse. These tabels were than seeded when the user runs "npm run seed."

## Constructing the Routes: 
I created routes in the following files: 
* category-routes.js
* product-routes.js
* tag-routes.js

In the category-routes.js file I created five routes in total, two of those routes were "get" routes followed by a "post" route and a "put" route and the last was a "delete" rout. In the product-routes.js file I created a total three routes, the first two were "get" routes then a the bottom of the page I created the missing "delete" route.  In the tag-routes.js file I created a total of five routes. The first two were "get" routes followed by a "post" route and "put" route and last a "delete" route. 

[Walk Through Video part1](https://drive.google.com/file/d/1bbzSmrDLkh4g9nco3xvi53PWocyZrY2E/view)
[Walk Through Video part2](https://drive.google.com/file/d/1sEMICd3qTC7ddLwWZz50i601unHzqFeJ/view)
