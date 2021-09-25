# 

* Reading: Context API



## Describe use cases useState() vs useReducer()

* Next state depends on the previous : using reducer helps in case like this.
* Complex state shape When the state consists of more than primitive values, like nested object or arrays.
* Easy to test.


### ```Why do custom hooks need the use prefix?```
***Custom hooks follow the same convention as built-in hooks because they have to be used in the same fashion. The use prefix is just a convention to identify hook functions which are usually call at the very top of a component render method.***

### ```What do custom hooks usually do```
***Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.***

### ```Using any list of custom hooks, research and name one that you think will be useful in your applications?```
***using reducer i think is going to be benefisial becuase it has the same function as useStast only better.***

### ```Describe how a hook that fetches API data might work?```
***when using usestate to fetches API data by naming neccessary variables to defined that would take intial value where they could be used to call the data in the api.***

### reducer:
***A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently***
