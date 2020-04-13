Nodelists

When more than one element is returned from a DOM query, it is called a 
nodelist.  A nodelist is similar to an array, but are actually a type of
object called a collection.  Like an array,  nodes of an element have an 
index number and can can be used in a loop if access to each node is 
desired.  One example would be to change the value of a class attribute 
of each node of an element.  A nodelist can have properties and methods.

The length property can be used to tell how many items are in the nodelist.

The item() method can access an individual item in the nodelist. Parentheses
or brackets can be used to specify an index of the node.

Examples of three different DOM queries:

getElementsByTagName('h2') - returns all h2 elements. Each h2 would have its 
own index number.

getElementsByClassName('first-list') - returns only the elements with first-list
as the class name.

querySelectorAll('h2[id]') - returns all the h2 elements that have an id
attribute, even if the values of the attributes are different.

Example of selecting elements by class attribute:

let elements = document.getElementByClassName('first-list');
if (elements > 0) {
    let elem = elements[1];
    elem.className = 'second-list';
}

This example starts with an if statement to check if there are elements to access. 
A new variable is assigned the value of the second element.  The class is changed to
'second-list' for this element. The variable elem does not store the second element in 
the nodelist.  It stores a reference to where the node is in the DOM tree. 