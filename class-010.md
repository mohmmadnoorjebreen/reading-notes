# JavaScript book, Ch. 10, “Error Handling & Debugging”

When you are writing JavaScript, do not expect to write it perfectly the first time.

## ORDER OF EXECUTION

To find the source of an error, it helps to know how scripts are processed.

## EXECUTION CONTEXTS

Every statement in a script lives in one of three
execution contexts:

1. GLOBAL CONTEXT (There is only one global context in any page.)

2. FUNCTION CONTEXT (Each function has its own function context.)

3. EVAL CONTEXT (NOT SHOWN)

## The stack

A stack is a data structure that holds a list of elements.

![](https://miro.medium.com/max/1592/0*ryPdDzB_jghiVi2e.png)

## EXECUTION CONTEXT & HOISTING

- PREPARE

  1. The new scope is created
  2. Variables, functions, and arguments are created
  3. The value of the this keyword is determined

- EXECUTE

 1. Now it can assign values to variables
 2. Reference functions and run their code
 3. Execute statements

## UNDERSTANDING SCOPE

 scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript.

![](https://www.learnsimpli.com/wp-content/uploads/2020/02/2-4.png)

## UNDERSTANDING ERRORS

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

## ERROR OBJECTS

Error objects can help you find where your mistakes are
and browsers have tools to help you read them.

When an Error object is created, it will contain the
following properties:

1. name(Type of execution)

2. message(Description)

3. file Number(Name of the JavaScript file)

4. line Number

5. Line number of error

There are seven types of built-in error objects in
JavaScript.

- Error
- Syntax Error
- ReferenceError
- TypeError
- Range Error
- URI Error
- Eval Error

## A DEBUGGING WORKFLOW

Debugging is about deduction: eliminating potential causes of an error.