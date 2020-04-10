Using CSS to align Form Controls

When creating a form, start with an opening 'form' tag. Enclose the
form with a closing tag.  This means all the divs, labels, inputs, spans, 
etc. are within the opening and closing form tags.

It is good practice to use a 'div' element for each topic of the form.
By using a 'div' each time, each topic will appear on its own line.

ex..    Name:  [input box]   // These boxes are 'form controls'
        Age:  [input box]

ex. in html:  (CAPS=attributes, ------ = text on page, (Name in first line))

form
    div
        label FOR='name' CLASS='title' ------ label
        input TYPE='text' ID='name' NAME='name' input
    div
form

Without styling with CSS, the form controls may not line up correctly. 
They might be offset from each other.  The FOR attribute indicates which
form control(input) it is a label for. In order to keep code simple, form
controls were set up to have the text appear next to it. The text is contained
within the label tag and has a class 'title'.

In CSS:
div {
    margin: 1px;
    padding-bottom: 10px;
    width: 250px;
}

.title {
    float: left;
    width: 100px;
    text-align: right;
    padding-right: 10px;
}

Set the label width to the same amount of px by using the class attribute. Use the float
property to align the label containing the text to far left of container (div) . 
Since the titles (text box) are the same width, the form controls will line up next 
to them (in-line with each other). The div uses the padding property to space it properly. 
Lastly, the text is aligned to the right for a better appearance.  The text is close to
the form controls.

            Name: [          ]
             Age: [          ]

