# Component-Based Architecture

Component-based architecture:

 is a branch of software engineering which provides a higher level of abstraction than object-oriented design principles.

## What is a Component?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface and is a software object, intended to interact with other components, encapsulating certain functionality.

### different views of Component

1- Object-oriented view

2- Conventional view

3- Process-related view

![](https://www.hebergementwebs.com/image/f7/f7ff2ce429c26c468e6e16a6f3e9f7c8.jpg/component-based-architecture.jpg)

## What are the charactistics of a component?

- Reusability : Components are usually designed to be reused in different situations in different applications.

- Replaceable : Components may be freely substituted with other similar components.

- Not context specific : Components are designed to operate in different environments and contexts.

- Extensible : A component can be extended from existing components to provide new behavior.

- Encapsulated : A A component depicts the interfaces.

- Independent : Components are designed to have minimal dependencies on other components.

## What are the advantages of using component based architecture?

1- Ease of deployment

2- Reduced cost

3- Ease of development

4- Reusable

5- Modification of technical complexity

6- Reliability

# What is Props and How to Use it in React

React is a component-based library,
which divides the UI into little reusable pieces

the way to pass data between components is by using props.

## What is props short for?

Propsis a special keyword in React, which stands for properties.

used for : passing data from one component to another.

## How are props used in React?

To use props there are 3 steps to follow:

1- Defining Attribute & Data

attributes and values to HTML tags:

`<a href="www.google.com">Click here to visit Google</a>;`

define our own attributes & assign values with interpolation { }:

`<ChildComponent someAttribute={value} anotherAttribute={value}/>`

declaring attribute to the ChildComponent and then assign a string value:

`<ChildComponent text={“I’m the 1st child”} />`

2- Passing Data using Props

Arguments passed to a function:

```
const addition = (firstNum, secondNum) => {  
  return firstNum + secondNum; 
};
```

Arguments passed to a React component:


```
const ChildComponent = (props) => {  
  return <p>I'm the 1st child!</p>; 
};

```

3- Rendering Props Data

render the props object by using string interpolation:

`{props}`

log props to console and see what it shows:

`console.log(props);`

## What is the flow of props?

Props can only be passed to components in one-way (parent to child).



# Reference

- [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

- [What is “Props” and how to use it in React?](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0)