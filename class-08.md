# HTML/CSS book, Ch. 15, “Layout” (again; repeat of Class 4 reading)

### Key Concepts in Positioning Elements

CSS treats each HTML element as if it is in its
own box.

type of elements

1. Block-level elements
`<h1> <p> <ul> <li>`
2. Inline elements 
`<img> <b> <i>`

If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

Controlling the Position of Elements
specify the positioning scheme using the position property in CSS.

1. Normal flow

In normal flow, each block-level
element sits on top of the next
one.
```
body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
h1 {
background-color: #efefef;
padding: 10px;}
p {
width: 450px;}
```

2. Relative Positioning

Relative positioning moves an
element in relation to where it
would have been in normal flow.
```
p.example {
position: relative;
top: 10px;
left: 100px;}
```

3. Absolute positioning

When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page.
```
h1 {
position: absolute;
top: 0px;
left: 500px;
width: 250px;}
p {
width: 450px;}
```

4. Fixed Positioning

Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.
```
h1 {
position: fixed;
top: 0px;
left: 50px;
padding: 10px;
margin: 0px;
width: 100%;
background-color: #efefef;}
p.example {
margin-top: 100px;}
```

5. Floating Elements

The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.

```
blockquote {
float: right;
width: 275px;
font-size: 130%;
font-style: italic;
font-family: Georgia, Times, serif;
margin: 0px 0px 10px 10px;
padding: 10px;
border-top: 1px solid #665544;
border-bottom: 1px solid #665544;}
```

### Using Float to Place Elements Side-by-Side.

A lot of layouts place boxes
next to each other. The float
property is commonly used to
achieve this.

```
body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
p {
width: 230px;
float: left;
margin: 5px;
padding: 5px;
background-color: #efefef;}
```

![Float](https://i.stack.imgur.com/CmuhZ.png)

### Screen Sizes

Different visitors to your site will have different sized screens that show
different amounts of information.

When designing for print, you
always know the size of the
piece of paper that your design
will be printed on.

![Screen Sizes ](https://i.pinimg.com/736x/14/5e/c4/145ec45256e8b07f671d42053fce3b1b.jpg)