# Simple-Ball-Animation
This project demonstrates a simple bouncing ball animation using HTML and CSS. The ball changes color whenever it hits the ground.

## Demo

## Explanation

### HTML Structure
- The HTML structure consists of a div container that holds another div for the ball. The container is styled to be centered on the page and provides a boundary for the ball to bounce within.

### CSS Styling and Animation

- Container Styling:
    - The container is styled with a fixed height of 400px, a dark background color, and rounded corners.
    - It uses position: relative to allow the ball to be positioned absolutely within it.

- Ball Styling:
    - The ball is styled to be a 50x50px circle with an initial color of tomato red.
    - It is positioned absolutely at the top of the container and horizontally centered using left: 50% and transform: translateX(-50%).

- Animation:
    - The @keyframes bounce rule defines the bouncing motion.
    - The animation changes the top property from 0% (top) to 50% (bottom) and back to 0%.
    - animation-timing-function is used to create a smooth easing effect (ease-in for the upward motion and ease-out for the downward motion).
    - The ball's background color changes to green when it hits the bottom (50%) and back to its original color at the top (0% and 100%).




  
