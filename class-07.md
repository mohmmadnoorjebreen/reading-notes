# Domain Modeling

he domain model is a representation of meaningful real-world concepts pertinent to the domain that need to be modeled in software.

```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
```

## Generate random numbers

 random number between 0 and 1, use the Math. random() function. If you want a random number between 1 and 10, multiply the results of Math. random by 10, then round up or down

```
EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
```

# Chapter 6: “Tables” (pp.126-145)

A table is a data structure that organizes information into rows and columns.

### Basic Table Structure

```
<table>
<tr>
<td>15</td>
<td>15</td>
<td>30</td>
</tr>
```

### Table Headings

The `<th>` element is used just
like the `<td>` element but its
purpose is to represent the
heading for either a column or
a row.

Sometimes you may need the
entries in a table to stretch
across more than one column and one row.

for that we use :

1. Spanning Columns , for columns

![Spanning Columns](https://www.dummies.com/wp-content/uploads/412171.image0.jpg)
2. Spanning row , for row 

![Spanningrow](https://lh3.googleusercontent.com/proxy/Ho8rgUx6dTRZi-q1TJ6xYMD-_O_CPc0NPZBwmRqypi2VOx8L09RuNI2qGZzY-gSx6xpR-rIh0VoKFDE1SBpk-6WHxIN6qcoxpvBCTJxfo3s-luP4YBAQp3Xtkg)

## Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

The way to create an "object type", is to use an object constructor function.

### CREATING OBJECTS USING CONSTRUCTOR SYNTAX

```
var hotel = new Object();
hotel.name= 'Park';
hotel.rooms = 120;
hotel .booked = 77;
hotel .checkAvailability = function()
return this . rooms - this.booked;
} ;
```

### ADDING AND REMOVING PROPERTIES

do this using the dot
notation.
```
hotel .gym = t rue;
hotel .pool = fal se;
delete hotel .booked;
```
### RECAP: STORING DATA

In JavaScript, data is represented using name/value pairs.
In arrays and objects the name is also known as a key.

1. VARIABLES

A variable has just one key.

`var hotel= 'Quay' ;`

2. ARRAYS

Arrays can store multiple pieces of information.

```
var hotel s = [
'Quay ' ,
' Park' ,
' Beach' ,
'Bloomsbury'
]
```