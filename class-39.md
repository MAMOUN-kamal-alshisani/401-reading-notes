
# Readings: Redux - Additional Topics


### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
***The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount) of a Higher Order Component that wraps your app***

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
***it exports the states that have undergone changes.***




# Term

## middleware
***The middleware sits in between the dispatch and reducers, which means we can alter our dispatched actions before they get to the reducers or execute some code during the dispatch. An example of a redux middleware is redux-thunk which allows you to write action creators that return a function instead of an action.***

## thunk
***Thunk is a programming concept where a function is used to delay the evaluation/calculation of an operation. Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object.***
