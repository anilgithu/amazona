# Mern stack

# steps

1. intro
2. install tools
3. creating git repo
4. Add Routing
5. npm i react-router-dom
6. Create rout for home screen
7. create rout for product screen
8. Create node.js server
   8.2 run npm init in root folder
   8.3 Update pakage.json set type: module
   8.4 Add.js to imports
   8.5 npm install express
   8.6 create server.js
   8.7 add start command as node backend/server .js
   8.9 require express
   8.8 create route for / return backend is ready
   8.9 move product.js from frontend to backend
   8.10 create route for /api/products
   8.11 return products
   8.12 rum npm starts

   9. fetch Product from backend
      _. set proxy in pakage.jason
      _. npm install axios
      _. use state hook
      _. use effect hook
      \*. use redcer hook

9. Manage state by manager Hook

- Define Reducer
- Updae fetch data
- Get state from useReducer

10. Add BootStrap UI frame work

- npm Install react-bootstrap bootstrap
- Update App.js

11. Create product and rating component

- Create rating component
- Create Product component
- Use rating component in product component

12. Create product details screen

- fetch product from backend
- create 3 columns for image

13. Loading and essage component

- create loading component
- Use spinner component
- create message component
- create utils.js to get error function

14. Implement Add to cart

- create react context
- define reducer
- create store provider
- implement add to cart button click handler

15. complete add to cart
* check existing item in the list
* check count in stock in back end
16. Create cart screen
* create 2 columns
* display Items list
* create action column
17. Complete Cart Screen
    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler for checkout
 18. Create Signin Screen
    1. create sign in form
    2. add email and password
    3. add signin button