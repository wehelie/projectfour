## Website Performance Optimization portfolio project

# OPTIMIZATION DONE ON MAIN.JS FOR PIZZA PAGE
-I inserted cs loader per google's recommendation, this function loads the css after the initial painting of the page. This applies styles when the page is finished loading without blocking the render of the crtical content. 


-In the updatePosition(), I added topScrol variable which takes scrollTop and divides it by viewport size.

- Combined css loader function with main.js file, then minified it (combined-min.js).

- optimized for loops in UpdatePositions function and

- added eventListener on DOMContentLoaded which appends new pizzas
- sliding pizza reduced to 31 as it is enough to fill the screen

<!-- - added window.requestAnimationFrame method and used updatePosition as parameter
 -->
 - changed queryselector to getElmentById which is faster.
- created a new var called randPizzaBox which holds which I then looped in order to apply new width

- optimized loops in the ChangePizzaSizes function
# project4


https://cloud.githubusercontent.com/assets/3928442/6568888/f9806022-c69c-11e4-92ed-f100b7af18f6.png
