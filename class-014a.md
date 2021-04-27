# Transforms 

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

## Transform Syntax 

The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
## 2d Transforms
### 2D Rotate 

The rotate value provides the ability to rotate an element from 0 to 360 degrees.

```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```

There are many of Transforms (2d):

- 2D Scale
- 2D Skew
- 2D Translate
- Combining Transforms 
- Transform Origin
- Perspective 
- Perspective Origin
 
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSO15zUtGQ7t4X6velkAV5Bhi1MZ1h9g5be-ramEI2h4e0mYb-zqZcCUxvv4DW7c5m3A-g&usqp=CAU)

### 3D Transforms

Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

There are many of Transforms (3d):

- 3D Rotate
- 3D Scale
- 3D Translate 
- 3D Skew
- Backface Visibility
- 3D Cube Demo 

![](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)

# Transitions & Animations

## Transitions 

As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```
There are many of Transitions (3d):

* Transitional Property

     The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.

* Transition Duration

   The duration in which a transition takes place is set using the transition-duration property.

* Transition Timing

  The transition-timing-function property is used to set the speed in which a transition will move.

* Transition Delay

  On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property.


## Animations

when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

### Animations Keyframes

To set multiple points at which an element should undergo a transition, use the @keyframes rule. 

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}

```

![](https://res.cloudinary.com/css-tricks/image/fetch/w_1200,q_auto,f_auto/https://css-tricks.com/wp-content/uploads/2017/12/css-animation-box.gif)