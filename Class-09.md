





# Today's topics about Layout CSS:
 

>  **1. HTML  Forms**
>  **2. Lists, Tables & Forms”**
>  **3. Events**

 # **In Details  :**
 ## **1. HTML  Forms**
An HTML form is used to collect user input. The user input can then be sent to a server for processing.

## HOW TO CREATE FORM:

### BY  `<form>` Element

The HTML  `<form>`  element defines a form that is used to collect user input:

    <form>
    </form>
    
  An HTML form contains  **form elements**.

Form elements are different types of input elements, like: text fields, checkboxes, radio buttons, submit buttons, and more.

### The `<input>` Element

The  `<input>`  element is the most important form element.

The  `<input>`  element is displayed in several ways, depending on the  **type**  attribute.

Here are some examples:

| Type | Description |
|`<input type="text">`|Defines a single-line text input field|
| `<input type="radio">` | Defines a radio button (for selecting one of many choices) |


## Text Fields

`<input type="text">`  defines a single-line input field for  **text input**.
### Example

A form with two text input fields:

    <form>  
    <label for="fname">First name:</label><br>  
    <input type="text"  id="fname"  name="fname"><br>  
    <label for="lname">Last name:</label><br>  
    <input type="text"  id="lname"  name="lname">  
    </form>
### The `<label>` Element

Notice the use of the  `<label>`  element in the example above.

The  `<label>`  tag defines a label for many form elements.

The  `<label>`  element is useful for screen-reader users, because the screen-reader will read out loud the label when the user is focused on the input element.

The  `<label>`  element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The  `for`  attribute of the <label> tag should be equal to the  `id`  attribute of the <input> element to bind them together.

### The Submit Button

`<input type="submit">`  defines a button for  **submitting**  the form data to a  **form-handler**.

The form-handler is typically a page on the server with a script for processing input data.

The form-handler is specified in the form's  **action**  attribute.

    <form action="/action_page.php">  
    <label for="fname">First name:</label><br>  
    <input type="text"  id="fname"  name="fname"  value="SAHDI"><br>  
    <label for="lname">Last name:</label><br>  
    <input type="text"  id="lname"  name="lname"  value="ZAQOUT"><br><br>  
    <input type="submit"  value="Submit">  
    </form>

## **2. Lists, Tables & Forms**
## 1. List
### 1.  list-style-type
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker).
It can be used on rules that apply to the `<ol>, <ul>`, and `<li>` elements.

 - Unordered Lists
 - ordered Lists
 - decimal
 - decimal-leading-zero
 - lower-alpha
 - upper-alpha
 - lower-roman
 - upper-roman
 
### 2. list-style-image
You can specify an image to act as a bullet point using the list-style-image property.

The value starts with the letters url and is followed by a pair  
of parentheses. Inside the parentheses, the path to the image is given inside double quotes.

This property can be used on rules that apply to the `<ul>` and `<li>` elements.

The example on this page also shows the use of the margin property to increase the vertical gap between each item in the list.

    ul {  
    list-style-image: url("images/chape.png");}
    
  ### 3. list-style-position
  Lists are indented into the page by default and the list-style- position property indicates whether the marker should appear on the inside or the outside of the box containing the main points.

This property can take one of two values:

 - outside

The marker sits to the left of the block of text. (This is the default behaviour if this property is not used.)

 - inside
The marker sits inside the box of text (which is indented).

## 2. Tables Properties

 1. **width** to set the width of the table
 2. **padding** to set the space between the border of each table cell and its content
 3. **text-transform** to convert the content of the table headers to uppercase
 4. **letter-spacing, font-size** to add additional styling to the content of the table headers
 5. **border-top, border-bottom** to set borders above and below the table headers
 6. **background-color** to change the background color of the alternating table rows
 7. **:hover** to highlight a table row when a user's mouse goes over row

## 3.  Forms
### 1. styling-text-inputs

	**1. font-size** sets the size of the text entered by the user.
	**2.color** sets the text color, and **background-color** sets the background color of the input.
	**3.border** adds a border around the edge of the input box, and **border-radius** can be used to create 	rounded corners (for browsers that support this property).
	4.The **:focus** pseudo-class is used to change the background color of the text input when it  
is being used, and the **:hover** psuedo-class applies the same styles when the user hovers over them.
**5.background-image** adds a background image to the box. Because there is a different image for each input, we are using an attribute selector looking for the value of the id attribute on each input.

### 2. styling-submit-buttons

 - **color** is used to change the color of the text on the button.
 - **text-shadow** can give a 3D look to the text in browsers that support
   this property.
 - **border-bottom** has been used to make the bottom border of the button
   slightly thicker, which gives it a more 3D feel.
 - **background-color** can make the submit button stand out from other
   items around it. (Creating a consistent style   for all buttons helps
   users understand how they should interact with the site.)
 - The **:hover** pseudo-class   has been used to change the appearance of
   the button when the user hovers over it. In this case, the background
   changes, the text gets darker, and the thicker border is applied to
   the top of the button.


 ## **3. JavaScript  Events**
HTML events are  **"things"**  that happen to HTML elements
When JavaScript is used in HTML pages, JavaScript can  **"react"**  on these events.

## HTML Events

An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

-   An HTML web page has finished loading
-   An HTML input field was changed
-   An HTML button was clicked

Often, when events happen, you may want to do something.

JavaScript lets you execute code when events are detected.

HTML allows event handler attributes,  **with JavaScript code**, to be added to HTML elements.

With single quotes:

    <element event='some JavaScript'>
In the following example, an `onclick` attribute (with code), is added to a `<button>` element:

    <button onclick="document.getElementById('demo').innerHTML=Date()">The time is?</button>
In the example above, the JavaScript code changes the content of the element with id="demo".
## What can JavaScript Do?
Event handlers can be used to handle, and verify, user input, user actions, and browser actions:

-   Things that should be done every time a page loads
-   Things that should be done when the page is closed
-   Action that should be performed when a user clicks a button
-   Content that should be verified when a user inputs data
