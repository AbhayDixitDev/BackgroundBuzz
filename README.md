#BackgroundBuzz

This project demonstrates a dynamic background color changer using HTML, CSS, and JavaScript. When a user hovers over a color box, the background color of the entire page changes to match the color of the hovered box.

Features:

Grid layout of color boxes using CSS Grid
Dynamic background color change on hover using JavaScript
Smooth transition effect on hover using CSS transitions
Technologies Used:

HTML5
CSS3 (Grid, Transitions)
JavaScript (DOM manipulation, event listeners)
How it Works:

The HTML structure consists of a grid container with multiple grid boxes, each with a unique background color.
The CSS styles the grid layout and adds a hover effect to each grid box.
The JavaScript code adds event listeners to each grid box, listening for mouseover and mouseout events.
When a grid box is hovered over, the JavaScript code retrieves the background color of the hovered box using ` document.querySecelor('#boxid').style.backgroundColor ` and sets it as the background color of the entire page using document.body.style.background.
When the mouse is moved out of the grid box, the background color of the page is reset to its original value.
