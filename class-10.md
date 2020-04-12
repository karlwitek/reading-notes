Error Objects and Types of Errors

When the interpreter comes across an error, it creates an error object.

An error object contains four properties.
Since it is an object, it has key: value pairs.

name: type of execution
message: description
fileNumber: name of Javascript fileNumber
lineNumber: line number of error

There are 7 types of built-in error objects in Javascript:

1. SyntaxError:  Incorrect use of the language. Often a 
typo in the code.  Non-matching quotes, missing parantheses or
bracket, a space where there shouldn't be, etc..

2. ReferenceError:  occurs when a variable is not declared or
out of scope.  An undefined function will also cause this error.

3. TypeError:  this error occurs when trying to use an object or
method that does not exist.  It could be from an incorrect case or
spelling of a function. Or calling a function that does not exist. 
Another example would be using a DOM node that does not exist.
An example would be calling getElementById with an incorrect argument.

4. Error:  this is a generic error object which acts as a template
(prototype), which all other error objects are created.

5. RangeError:  occurs when calling a function that takes numbers as 
arguments and the numbers are out of range.  
ex.  price.toFixed(25);  toFixed accepts numbers 1-20

6. URIError:  occurs when certain characters are used without an escape
character in an URI (source location or URL - 'http://cnn.com/news/.....')
The characters that will cause the error are: / ? & # : ;

7. EvalError:  this error is rare and often the interpreter will display
other errors instead of EvalError.   The eval() function evaluates text and
runs it as code.  

