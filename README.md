## e-Commerce platform built with the MERN stack & Redux(for managing global state of the application).

## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Admin Order details page
- Mark orders as delivered option
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)

## DOWN TO TOP APPROACH

1. MAKE CONTROLLERS
2. MAKE THE ROUTES
3. CHECK THE ROUTES USING POSTMAN
4. EXPORT CONSTANTS
5. CREATE THE REDUCER
6. BRING THE REDUCER IN THE STORE
7. CREATE THE ACTIONS
8. BRING WHAT YOU WANT TO GET FROM THE STATE IN THE SCREEN
9. MODIFY THE SCREEN
10. USEEFFECT TO DISPATCH THE ACTION IN THE SCREEN

## Redux description

dispatch action => pass it to the reducer(because thats what we gave to the store when we created it)
actions => description of the change that you want to make in the global state
dispatch => vechile for taking the actions to the reducer
reducer => take the action and determine what the new state is
actioncreator => return the action object that you care about

## Main store functions

subscribe is a method where we call a function that runs everytime a change is made to the store
getState is a method used to get the currrent state of our applications data
dispatch is also a store function

## react-redux hooks

useSelector => get pieces of state from the global state
useDispatch => dispatching our actions
redux-thunk => enables the ability to return functions from the action creators which does all sorts of async stuffs first and uses the dispatcher. thunk is used as a middleware
