# React Docs - Forms

## What is a ‘Controlled Component’?

a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

we update the state with their responses as soon as they enter them.

typically maintain their own state and update it based on user input.


## How do we target what the user is entering if we have an event handler on an input field? 

you can add a name attribute to each element and let the handler function choose what to do based on the value of `event.target.name.`

# The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?

 do the same exact thing if does in just one line of code
that led to  shorter code yields us the same result.

## Rewrite the following statement using a ternary statement:
```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

it will become 

```
if(x===y) ? console.log(true) : console.log(false)
```