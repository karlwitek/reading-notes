Pseudo Classes

A pseudo class behaves like an additional value of a class attribute.

You can apply different styles to links based on the user's interaction.

All pseudo classes are before the first curly brace and after the 'a' element.
Place a colon before the pseudo class.

example-

a:link {                //  set the style of a link that has not been visited 
    color: blue;
    text-decoration: none;
}

a:visited {             //  change the color after the user has visited this link
    color: red;         // ('clicked' on the link)
}

a:hover {               // add an underline to the link and change the color to green
    color: green;       // when the user hovers over the item
    text-decoration: underline;
}

button:active {         // style changes when activated by the user.  The button  
    color: black;       // changes color to black after the user clicks on it.
}

input:focus {           // the color of the input boxes changes color when the cursor
    color: gray;        // is inside it. (when the user is about to start typing)
}

<----  The user can use the tab key to move through the elements that have a pseudo class -->
<---   associated with it.>