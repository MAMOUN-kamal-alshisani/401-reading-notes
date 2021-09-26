## Reading: Context API - Behaviors


### When you have multiple contexts, what component type should you use (class/function) and why?
***both.
***function you will use useContext hook.***
***class you will use consumer.***

### What are some good use cases for using the Context API for global state? when changing a theme for example.

### How can you best test context?

***The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).***


### context:
***The context in React is a concept that lets you supply child components with global data, no matter how deep they are in the components tree. Using the context requires 3 steps: creating, providing, and consuming the context. When integrating the context into your application, consider that it adds a good amount of complexity.***

### useContext()
***Returns a stateful value, and a function to update it. During the initial render, the returned state (state) is the same as the value passed as the first argument (initialState). The setStatefunction is used to update the state. It accepts a new state value and enqueues a re-render of the component. During subsequent re-renders, the first value returned by useStatewill always be the most recent state after applying updates.***

### static context
***A context is a set of rules that describes the communication context, meaning the header fields. It is shared and pre-provisioned in both the end-devices and the core network. The "static context" assumes that the rule description does not change during transmission.***
