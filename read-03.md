# React Docs - lists and keys

## What does .map() return?

 new array returned by map();

## If I want to loop through an array and display each value in JSX, how do I do that in React?

two steps :

- using the JavaScript map() function.
- using it in the curly braces {}.

## Each list item needs a unique ____.

Each list item needs a unique __key__.

## What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed.

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li key={number.toString()}>
    {number}
  </li>
);
```

# The Spread Operator 

## What is the spread operator? 

is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

## List 4 things that the spread operator can do.

1- Copying an array

2- Adding an item to a list

3- Combining objects

4- Converting NodeList to an array

## Give an example of using the spread operator to combine two arrays.

```
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

## Give an example of using the spread operator to add a new item to an array.

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```
## Give an example of using the spread operator to combine two objects into one.

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```


# How to Pass Functions Between Components

## In the video, what is the first step that the developer does to pass functions between components?

create object ,like `<person />`, because function pass like prompt pass.

## In your own words, what does the increment function do?

change a count value inside the stats by increase it by one each time of click in button.

## How can you pass a method from a parent component into a child component? 

using props consept like that `nameOfFunction(this name I use it in child coponenet)  = {this.nameOfFunction}` this commaned shoud write down inner return in parent component.

## How does the child component invoke a method that was passed to it from a parent component?

using props like that `this.props.nameOfFunction()` inner child component.