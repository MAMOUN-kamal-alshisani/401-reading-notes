# Readings: Redux - Asynchronous Actions

### How granular should your reducers be?
***The concept of a Reducer became popular in JavaScript with the rise of Redux as state management solution for React. … Basically reducers are there to manage state in an application. For instance, if a user writes something in an HTML input field, the application has to manage this UI state (e.g. controlled components)***


### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
***multiple reducers can “fire” when a commonly named action is dispatched Not always we need to fire all reducer in one action dispatch***

### Name a strategy for preventing the above
***Using Redux middleware thunk, allows for evaluating the actions***


## Term

#### store
***A store is an immutable object tree in Redux. A store is a state container which holds the application’s state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer. Let us see how we can create a store using the createStore method from Redux.***

### combined reducers
****It turns out that Redux lets us combine multiple reducers into one that can be passed into createStore by using a helper function named combineReducers. The way we combine reducers is simple, we create one file per reducer in the reducers directory. We also create a file called index.js inside the reducers directory.***
