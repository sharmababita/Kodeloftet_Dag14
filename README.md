# Kodeloftet_Dag14

Here we looked at several basic concepts of DOM Manipulation. We started by understanding how we can select elements from the HTML document using document.querySelector, and then we created new HTML elements programmatically using document.createElement. We learned how to set content for these elements using textContent, and finally we added these newly created elements to our HTML document using appendChild. Through practical examples such as dynamically creating headings and paragraphs, we gained insight into dynamically changing web page content with JavaScript.

.document.querySelector(""): A method in JavaScript that returns the first element in the document that matches a specified CSS selector. For example, document.querySelector('.myClass') will return the first element with the class "myClass". You can also use ID selectors (e.g., document.querySelector('#myId') for an element with ID "myId") and element selectors (e.g., document.querySelector('div') for the first div element).


.document.createElement(""): A JavaScript method that creates a new HTML element of the specified type (e.g., div, p, span) and returns it as a DOM object. For example, document.createElement('div') creates a new div element.


.textContent: A JavaScript property that sets or returns the textual content of an element and all of its children. For example, element.textContent = 'Hello' sets the text to "Hello" in the specified element.


.appendChild("")A JavaScript method that adds a child node to a specified parent node as the last child. For example, parentElement.appendChild(childElement) adds childElement as the last child of parentElement, making it part of the HTML structure.

To further expand on what you learned from today's lesson, you can explore more advanced DOM manipulation techniques such as event handling, style manipulation, and setting 'class' and 'attributes' on elements created in JavaScript.

Additionally, you can delve into the concept of dynamic content generation using user input, which we talked about, where we write something that is processed through JavaScript and passed to HTML. This allows you to create more interactive and dynamic web applications.



Data Types------------------------------

# Variables

const = something that is constant, should not be changed
let = something that can be changed
var = no longer activly used

# Data types

number = numbers
string = text
boolean = true or false
array = A collection of values stored in a specific order, like a list.
object = Stores different data in a list. Each piece has a name with a value, example: color: "red"

undefined = there is undefined data
null = something is empty
nan = 'Not a number' if we try to work with number methods on non numbers

# Function

function yourFunctionName(values, these are called parameters) {
write your code here
}

yourFunctionName(values, these are called arguments)

# Connect to HTML

document.querySelector('#nameOfId')

# Event Listening

variableName.addEventListener("click", function() {
what should happen when you click
})

# If/else statements

if () {
checks if something is true or false
}
else {
if not not desired true or false, this happens instead
}

# Operators

=== means something is exactly equal
!= is written to check: "if this is not equal"

# .classlist functionallity

classList.add = adds a class
classList.remove = removes a class
classList.toggle = switches between adding and removing the class name


[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/sharmababita/Kodeloftet_Dag14)
