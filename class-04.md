Controlling the Position of Elements  (cheat sheet)

5 positioning schemes:
1. Normal Flow
2. Relative Positioning
3. Absolute Positioning
4. Fixed Positioning
5. Floating Elements

Normal Flow: All block elements ( h1, p, ul, li, div for example) are displayed
on a new line.  Each element flows verically down the page.  Even if the width could
allow side by side relationship, will still be top to bottom relationship.  
( default behavior) in CSS--- position: static;  Not needed because is default.

Relative Positioning: moves an element from where it would of been placed in 
Normal Flow.  (top, bottom, left or right)  Does not affect the position of other
elements on the page.  
property is position, value is relative--- position: relative;
Following the property, can add offset properties [top, bottom, left, right] ex.( top: 10px;)

Absolute Positioning: positions the element in relation to the containing element.
The other elements are not affected.  Can result in one element on top of another.
position: absolute; followed by offset properties (top: 10px or left: or width:)

Fixed Positioning: positions the element in relation to the browser window.  These elements
do not affect the other elements and stays fixed in the window ( same place )when the user 
scrolls up or down the page.
position: fixed; followed by offset properties including color.

Floating Elements:  element can be put as far left or right of a containing box.  Other 
elements flow around it.  ( along the side if there is room)  Include the width property or the 
float element may take up the full width of the containing element.  
float: right;  example

