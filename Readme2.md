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

