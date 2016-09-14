## Website Performance Optimization portfolio project

## Instructions
For viewing purposes the projects files are pizza.html and index.html. Github pages can used to view either. Both can also be open by a browser locally, but pagespeed insights can only be used on Github pages or another internet platform.

## Part 1 modifications

* CSS was moved onto index.html.
* JS was moved to address render blocking message.
* Google font issue was addressed by WebFontConfig recode.
* Images run through image-optim.
* Pizzeria image replaced with optimized image suggested by Google.
* Minified (in dist)
* index.html scores after modifications are 96 Mobile, 97 Desktop.


## Part 2 modifications to main.js

* Use strict added.
* getElementsByClassName/ID replaced queryselector in several places per discussion in project webcast.
* Var i lowered to 24 from to 200 per suggestion in project webcast.
* changePizzaSizes rework to per BRO course example.
* Update Position function recode to avoid render blocking error msg in Dev tools.
* document.getElementsByClassName("mover") moved out of function.
* Items left reconfigured as transform translateX, per webcast.
* requestAnimationFrame used. 
* No grunt or gulp modifications.
* Minified (in Dist)


### modifications to style.css
* Add Transform: translateZ(0) for smoother transitions between property value per suggestion in project webcast.
* Add webkit, moz.
* Run through autoprefixer per suggestion of mentor.
* Minified(in Dist)
