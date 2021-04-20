# Chapter 7: “Forms” (p.144-175)

printed document that contains
spaces for you to fill in information.

HTML borrows the concept of a form to refer to different
elements that allow you to collect information from visitors to
your site.

![](https://cdn.wpml.org/wp-content/uploads/2019/08/form-en.png)

## Form Controls 

There are several types of form controls that:

1. ADDING TEXT:

   * Text input (single-line)    
   * Password input
   * Text area (multi-line)

2. Making Choices:  
    * Radio buttons
    * Checkboxes
    * Drop-down boxes

3. Submitting Forms: Uploading Files:

    * Submit buttons
    * Image buttons

4. Uploading Files: 
 
    * File upload

## How Forms Work

A user fills in a form and then presses a button
to submit the information to the server.

![](https://img.webnots.com/2014/01/How-HTML-Form-Works.png)

# Chapter 14: “Lists, Tables & Forms” (pp.330-357)

## Bullet Point Styles `list-style-type`

The list-style-type property
allows you to control the shape
or style of a bullet point.

```
ol {
list-style-type: lower-roman;}
```

## table Properties

You have already met several
properties that are commonly
used with tables.

1. width

2. padding

3. text-transform

4. letter-spacing, font-size

5. border-top, border-bottom

6. text-align

7. background-color

8. :hover

```
body {
font-family: Arial, Verdana, sans-serif;
color: #111111;}
table {
width: 600px;}
th, td {
padding: 7px 10px 10px 10px;}
th {
text-transform: uppercase;
letter-spacing: 0.1em;
font-size: 90%;
border-bottom: 2px solid #111111;
border-top: 1px solid #999;
text-align: left;}
tr.even {
background-color: #efefef;}
tr:hover {
background-color: #c3e6e5;}
.money {
text-align: right;}
```

## Styling Forms

CSS is commonly used to
control the appearance of form
elements.

It is most common to style:

- Text inputs and text areas
- Submit buttons
- Labels on forms, to get the
form controls to align nicely

![](https://webninjahq.com/assets/forms.jpg)

# Chapter 6: “Events” (pp.243-292)

An event refers to an action or occurrence that happens in the system you are programming. 

## DIFFERENT EVENT TYPES
Here is a selection of the events that occur in the browser while you are
browsing the web.

## HOW EVENTS TRIGGER JAVASCRIPT CODE

there are three
steps involved in getting it to trigger some JavaScript code:

1. Select he element
node(s) you want the
script to respond to.

2. Indicate which event on
the selected node(s) will
trigger the response.

3. State the code you want
to run when the event
occurs.

## THREE WAYS TO BIND AN EVENT TO AN ELEMENT

- HTML EVENT
HANDLERS

- TRADITIONAL DOM
EVENT HANDLERS

- DOM LEVEL 2 EVENT
LISTENERS