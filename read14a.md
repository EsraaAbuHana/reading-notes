# In this read, I will introduce some new features in CSS3
- Transform Syntax
## 2D Transforms
- transformation methods
`translate()`
`rotate()`
`scaleX()`
`scaleY()`
`scale()`
`skewX()`
`skewY()`
`skew()`
`matrix()`
# ![](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)
## 3D Transforms
`transform`
`rotateX()`
`rotateY()`
`rotateZ()`

# Transitions & Animations
-Transitions
-an element must have a change in state, and different styles must be identified for each state. 
-using the `:hover`, `:focus`, `:active`, and `:target pseudo-classes.`
-properties : `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`. 

# Animations
Transitions build out visual interactions from one state to anothers. However, when more control is required, transitions need to have multiple states. 
CSS allows animation of HTML elements without using JavaScript or Flash!
- example code:
> ` @keyframes slide { `
> ` 0% {`
> `  left: 0;`
> `   top: 0;`
>`  }`
>` 50% {`
>  `  left: 244px;`
>  ` top: 100px;`
>`  }`
>`  100% {`
>`   left: 488px;`
> `   top: 0;`
>`  }`
> `}`
- Animation Duration, Timing Function, & Delay
- first declared the  animation-name property on an element,
duration, timing function, and delay if desired. To start, animations need a duration declared using the animation-duration property. 
