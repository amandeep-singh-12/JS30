
# JS30
Javascript 30 day challenge with Wesbos

Day 7: HTML Canvas

•	Created a canvas to draw on.

•	Set dimensions and other properties of canvas.

•	Check if mouse is pressed down to start drawing.

•	Begin drawing when mouse is pressed by joining the points of the path as mouse moves and stops.
•	Change the color of the stroke as drawing occurs.

•	Make sure no drawing occurs if mouse is not pressed down.


# Involved characteristics
### Canvas:

#### Basic attributes:
  * getContext()
  * strokeStyle
  * fillStyle
  * lineCap
  * lineJoin
  * Path drawing
  * beginPath()
  * lineTo()
  * moveTo()
#### Mouse event handling:

  * mousemove
  * mousedown
  * mouseup
  * mouseout
  #### Process guide
1. The acquired HTML <canvas>elements, and set the width and height
  
2. .getContext('2d') Get the context, denoted by ctx below
  
3. Set basic properties of ctx
  * Stroke and line color
  * Line width
  * Line end shape
  
4. Painting effect
  * i. Set a variable for marking the state of painting
  * ii. Mouse event monitoring, different types of events will set the tag variable to         different values
  * iii. Write a function that is triggered when drawing occurs, and set the start and end points of the drawing path
5. Line rainbow gradient effect (using hsl the hchange in value, cumulative)
6. Line thickness gradient effect (set a range, when the range is exceeded, the line thickness will be reversed

  For detailed implementation visit https://tfrommen.de/javascript-30-day-8-html5-canvas/
  
https://github.com/soyaine/JavaScript30/tree/master/08%20-%20Fun%20with%20HTML5%20Canvas
