# React: Component Lifecycle Events

React lets you define components as classes or functions. 

![](https://miro.medium.com/max/2800/0*0saPKFiTUk6W3FYp)

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

the ‘render’ , happens first;

## What is the very first thing to happen in the lifecycle of React?  

Mounting , first thing to happen in the lifecycle;

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor
- render
- componentDidMount 
- React Updates
- componentWillUnmount

## What does componentDidMount do? 

This method is invoked immediately after a component is mounted.

This method is a good place to set up any subscriptions.

# React State Vs Props

## What types of things can you pass in the props?

any data type, from strings to functions, objects.

## What is the big difference between props and state?

props you pass into a component ans state is handel inside of the component and props handel out of the component.

## When do we re-render our application?

when you change the state inside of your application

## What are some examples of things that we could store in state?
- the counter
- form