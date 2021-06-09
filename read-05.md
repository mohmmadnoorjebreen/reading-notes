# React Docs - thinking in React

## How would you break a mock into a component heirarchy? 

- The first thing you’ll want to do is to draw boxes around every component in the mock and give them all names.

- Separate your UI into components, where each component matches one piece of your data model.

- italicized the data each component represents.

## What is the single responsibility principle and how does it apply to components?

is a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

that takes your data model and renders the UI but has no interactivity.

## Once you have a static application, what do you need to add?

- build components that reuse other components.

- pass data using props. props are a way of passing data from parent to child.

## What are the three questions you can ask to determine if something is state? 

1- Is it passed in from a parent via props? If so, it probably isn’t state.

2- Does it remain unchanged over time? If so, it probably isn’t state.


3- Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

follow these steps to figure it out

- identify every component that renders something based on that state

- Find a common owner component 

- Either the common owner or another component higher up in the hierarchy should own the state.

- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state.

