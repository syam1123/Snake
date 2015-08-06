# Snake game using HTML5 Canvas
-------------------------------
This is a simple Snake game built using Canvas. The game creates a food for the snake that can be created anywhere in the canvas randomly. Here the entire screen is taken as the canvas. The snake can move using the arrow keys. Once the snake head reaches the food, the food disappears as it considered as the snake ate that and a new food created in the canvas.
# Features
----------
- The snake should not bite itself.
- The snake should not reach the boundary of the canvas.
- The speed and length will increase as the score rises.

## Pros of Canvas
----------------------
- it could manipulate pixel and apply filter effect, so easy for image processing
- Very efficient for small size games.
- Dynamic behaviour of drawing graphics.
    
The dynamic behaviour of the canvas help us to draw animations in 2D and Webgl (#D).  In the game the snake need to move everywhere in the canvas and the fact is that it is not actually moving but there is erase and draw method.

The other pros of Canvas are

- Interactive video and audio.
- Animations.
- Consistent.
- Improved accessibility.

### Cons
--------

Even though it draw graphics dynamically  Canvas is  not an obvious choice for web games. The reasons might be:

- Canvas doesn’t play well with images.
- Canvas-based redrawing is painful.
- Low efficient for very large size but with one a few elements in the game.