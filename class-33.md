## Reading: <Login /> and <Auth />


## Why is the Context API useful?
***The Context API is useful for sharing state between components that you can’t easily share with props***

## Can a component outside of a provider get its context?
***the descendant components of a Provider can use the Consumer component. The Consumer component makes use of the renderProp function. The Context itself passes down the functions which could be called to update the context.***

## What are some common use cases for using the Context API?
***you can pass down themes, user authentication ,and any thing you want to apply on every component***

## Describe “Context Hell”
***Context hell is the nasty code you get taking advantage of the React Context API.***

## Term

### global state
***global state is the data that is shared between all the components within a React application. When the state is changed, or let’s say a filter is added, the components re-render accordingly***

### global context :
***This global context helps you look at what makes you different from others and what you share with others. This is a starting point for understanding other people in your community and beyond. What it means to be human. This global context is not just about studying the time and place of an event.***

### provider
***Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes. The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. One Provider can be connected to many consumers.***


### consumer
***where the stored information ends up. It can request data via the provider and manipulate the central store if the provider allows it. Is ReactJS a front-end or back-end library? React is a library for building user interfaces on the client, so it is mainly used on the front end of an application.***
