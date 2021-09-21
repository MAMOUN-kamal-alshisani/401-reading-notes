### How can we ensure that an effect hook runs only once?

***If we pass an empty array [] , it just renders the component only once like componentDidMount .***

### Can useState() update more than one state variable at the same time?
***You could combine the loading state and data state into one state object and then you could do one setState call and there will only be one render. Note: Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely***

### Is useState() synchronous?
***useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.***

### State Hook
***useState is a Hook that allows you to have state variables in functional components. You pass the initial state to this function and it returns a variable with the current state value (not necessarily the initial state) and another function to update this value.***

### Component Lifecycle
***Each component in React has a lifecycle which you can monitor and manipulate during its three main phases.***

***The three phases are: Mounting, Updating, and Unmounting.***

