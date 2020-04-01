
Border Radius:

Border radius is a property that can be applied to any 'box' when creating the web page.  This property allows us to create rounded corners on the border of a box.
The associated value is expressed in pixels.  The amount of pixels would represent the length of the radius of a circle to produce the curvature of the corner.

The values can be stated individually:
border-top-right-radius: 5px;    (example)

Or 4 values at once:

border-radius: 5px, 10px, 5px, 10px;  (Clockwise order - top, right, bottom, left)

Other shapes of the curve of the corner can be created by specifying different distances for the horizontal and vertical parts of the corner.

example:  border-radius:   75px, 40px;  (a curve that is flatter on top part, steep on vertical or 'side')

To apply to only one corner : border-top-left-radius:  75px, 40px;

It is possible to state the values for all four corners on the same line:

border-radius:  2em 4em 2em 4em / 1em 2em 1 em 2em;  ( 4 horizontal values / 4 vertical values)


Lastly, you can create a circle by specifying the borde-radius the same value as
the height of the box. 
