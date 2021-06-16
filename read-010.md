# Understanding the JavaScript Call Stack

## What is a ‘call’?

 a call stack is a data structure that uses the Last In, First Out LIFO principle to temporarily store and manage function invocation call.

## How many ‘calls’ can happen at once?

 It is single-threaded. Meaning it can only do one thing at a time.

## What does LIFO mean?

it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```
(function testing(){
  var obj = {
    add
  }
  function add(a, b) {
    var result = a + b
    return result.split('')
  }
  var stringResult = obj.add("1", "2") // stringResult becomes "12"
  var numberResult = obj.add(1, 2) // numberResult is never set, an error is thrown
})()
```
## What causes a Stack Overflow?

A stack overflow occurs when there is a recursive function  without an exit point

# JavaScript error messages

## What is a ‘refrence error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

## What is a ‘syntax error’?

error ,this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.


## What is a ‘range error’?

is thrown when trying to pass a number as an argument to a function that does not allow a range that includes that number.

## What is a ‘tyep error’?

this types of errors show up when the types (number, string ...) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint?

conditional ,which will make your program stop at that point only if a condition is met.

## What does the word ‘debugger’ do in your code?

achieved the breakpoint ,by putting a debugger statement in your code in the line you want to break.