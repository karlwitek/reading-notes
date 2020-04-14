Drawing a circle with Canvas.  Canvas is an html element used to draw shapes or lines
and can be styles with colors, gradients and some animation (on the border).  The 
canvas element requires an opening and closing tag and has two attributes which are
width and height. The default size is 300px wide and 150 px tall.  A custom size can 
be set in html or CSS.  If the size is set in CSS, the ratio of the initial canvas 
needs to be the same or the image will be distorted.

The canvas grid, or coordinate space uses a 1 unit to 1px correspondence.  The origin
of the grid is the top left corner (0,0).  The x values are horizontal and the y values
are vertical.

Draw a rectangle:  use the function strokeRect(x, y, width , height)  The x and y coordinates specify the starting points.  The width and height specify the size of the 
rectangle.  strokeRect draws a rectangular outline.

fillRect(x, y, width, height) - draws a filled in rectangle

clearRect(x. y, width, height) - clears the specified area.  Could have a cleared area
within a filled in rectangle.

Drawing a circle with canvas:

Use the arc() method to draw circles.  arc() has six parameters.
arc(x, y, radius, startAngle, endAngle, anitclockwise)

x and y are the coordinates for the center of the circle.
The radius is the radius (length) of the circle.
The startAngle and endAngle define the start and end point of the arc in radians 
along the curve of the circle.  These are measured from the x axis.
The anticlockwise parameter is a Boolean value. When true , the circle is drawn 
in the anticlockwise direction.

varibleName.arc(50, 50 , 100, 0, 2 * Math.PI, false)

This would draw a circle whose center is at 50, 50 on the grid.  The radius of the circle
is 100px.  The starting point would be on the x axis and the circle would be drawn in a
clockwise direction.  The endAngle is 2 * pi, which is the number of radians in a circle.


