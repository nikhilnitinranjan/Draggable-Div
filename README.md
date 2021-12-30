# Draggable-Div
Draggable Div Element in HTML CSS & JavaScript
Hey friends, today in this project We create a Draggable Div Element in HTML CSS & JavaScript.
and now it’s time to create an easy draggable div using pure JavaScript.

The draggable div element means We can move the particular element anywhere on the document or page by dragging it.

We can move this modal box anywhere on the page by dragging it on the header part. When We start dragging this model, the cursor will change into a “move” icon to inform the user that this div is now dragging.We can only move this modal box by dragging it on the header.

In the JavaScript codes, first I added a mouse down event on the header, and inside the function of it, I added a mouse move event and called an onDrag function. Inside the onDrag function, I got the left and top values of the wrapper and parsed these values into an integer.

After this, I added this left and top wrapper value with movementX and movementY then gave this value to the wrapper left and top. At last, I added a mouse up event on the document, and inside the function of it, I removed the mouse move event listener. So when the user released the mouse button the div stop moving and stays in that position where a user has left it by dragging.
