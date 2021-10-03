
## Readings: Redux - Combined Reducers


### Why choose Redux instead of the Context API for global state?
***Redux enables tracking actions and data change, it greatly simplifies debugging. If you don’t want server response to directly change the state of your application. Redux adds a layer, where you can decide how, when and if this data should be applied.***

### What is the purpose of a reducer?
***are pure functions that take the current state of an application, perform an action, and return a new state. These states are stored as objects, and they specify how the state of an application changes in response to an action sent to the store.***

### What does an action contain?
***s message that we send to redux store. It can be of any type like mostly object which contain payload and action type. Action creator is function which create and return function dynamically.***

### Why do we need to copy the state in a reducer?

***If the application’s state is managed by Redux, the changes happen inside a reducer function — this is the only place where state changes happen. The reducer function makes use of the initial state of the application and something called action, to determine what the new state will look like.***



## Term

### immutable state
***One of Redux’s core tenets is maintaining state immutability to ensure state determinism, this is core principle of redux to manage state and don’t change current state always create new state object You probably have one question now though. What is immutability? An immutable object is one whose state cannot be modified once created.***

### time travel in redux
***Time travel is one of the most powerful features of Redux DevTools, it allows us to see how our app’s state has reached the current point. In certain cases, to analyze application behavior, we might need to remove a particular action from the timeline. This is not possible within the time travel mechanism.***

### action creator
***An action creator is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch () function.***

### reducer
***Redux is nothing but an open-source javascript library that contains the state of the application. The working of Redux is very simple to understand.***

### dispatch
***To dispatch, being to send something, normally with speed implied and a despatch being a missive of some kind.***
