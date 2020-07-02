# starsSystem

it's a simple javascript object that allows you to draw an animation of stars in an html element.

usage : 
import the function, create an instance with the parent element in constructor, then use it.

ex: 
```
const starsSystemInstance = starSystem(parent);//the parent is an HTML element
starsSystemInstance.drawStars(parent.width/2,parent.height/2, 16); //drawing at the center
```
