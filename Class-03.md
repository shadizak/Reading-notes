
 
# Today we are going to talk about HTML  Lists,Boxes, and Decisions and Loops in JS


> ## HTML  Lists

### HTML lists allow web authors to group a set of related items in lists.

### HTML provides us with three different types:

####  1. Ordered lists
#### 2. Unordered lists
#### 3.  Definition or Description lists
 
## In Details:

 #### 1.  Ordered HTML List:
 An ordered list starts with the  `<ol>` tag. Each list item starts with the  `<li>` tag.
The list items will be marked with numbers by default:

     <!DOCTYPE html>
    <html>
    <body>
    <h2>An ordered HTML list</h2>
    <ol>
      <li>HTML</li>
      <li>CSS</li>
      <li>JS</li>
    </ol>  
    </body>
    </html>
#### 2.  UnOrdered HTML List:
 An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.
The list items will be marked with bullets (small black circles) by default:

    <!DOCTYPE html>
    <html>
    <body>
    <h2>An ordered HTML list</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JS</li>
    </ul>  
    </body>
    </html>
![enter image description here](https://www.w3docs.com/uploads/media/default/0001/01/f79ee5dc2b2caadbea97e73eab152db65e868539.png)
#### 3.  Definition or Description lists:
 A description list is a list of terms, with a description of each term.

The `<dl>` tag defines the description list, the  `<dt>` tag defines the term (name), and the  `<dd>` tag describes each term:

    <!DOCTYPE html>
    <html>
    <body>
    <h2>Description List</h2>
    <dl>
      <dt>HTML</dt>
      <dd>- HyperText Markup Lang</dd>
      <dt>PHP</dt>
      <dd>- HyperText Preprpcessor</dd>
    </dl>
    </body>
    </html>

![enter image description here](data:image/png;base64,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)
  
**Note : Lists can be nested inside one another.**
 
 

> ## Boxes
**In this Section  you will see how to:**

   ● Control the dimensions of your boxes.
   ● Create borders around boxes.
   ● Set margins and padding for boxes.
   ● Show and hide boxes.

By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.

The most popular ways to specify the size of a box are  
to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.

When you use percentages,  
the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.

When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.
For More Details with **width, height:**
 HTML File:
 

    <div>  
    <p>The Moog company pioneered the commercial
    
    manufacture of modular voltage-controlled analog synthesizer systems in the early 1950s.</p>
    
    </div>
    
CSS File.

    div.box {  
    height: 300px;  
    width: 300px; background-color: #bbbbaa;}
    
    p{  
    height: 75%;  
    width: 75%; background-color: #0088dd;}

## Overflowing content
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values: hidden This property simply hides any extra content that does not fit in the box.

##  scroll

This property adds a scrollbar to the box so that users can scroll to see the missing content.
On the left, you can see two boxes whose contents expand beyond their set dimensions. The first example has the overflow property with a value of hidden. The second example has the overflow property with a value of scroll.
The overflow property is particularly handy because some browsers allow users to adjust the size of the text to appear as large or as small as they want. If the text is set too large then the page can become an unreadable mess. Hiding the overflow on such boxes helps prevent items overlapping on the page.
Try This:
HTML FILE:

    <h2>Fender Stratocaster</h2>  
    <p class="one">The Fender Stratocaster or "Strat"
    
    is one of the most popular electric guitars of all time, and its design has been copied by many guitar makers. It was designed by Leo... </p>
    
    <h2>Gibson Les Paul</h2>  
    <p class="two">The Gibson Les Paul is a solid body
    
    electric guitar that was first sold in 1952.  
    The Les Paul was designed by Ted McCarty... </p>
CSS File:

    p.one {  
    overflow: hidden;}
    
    p.two {  
    overflow: scroll;}


> ## Border, margin & padding
Every box has three available properties that can be adjusted to control its appearance:
**1. Border**
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

**2. Margin**
		Margins sit outside the edge  
		of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

**3. Padding**
		Padding is the space between the border of a box and any content contained within it. Adding padding can 		     	increase the readability of its contents.

![enter image description here](https://miro.medium.com/max/462/1*_Q0vGWv0CTxyZhF8hl5AfA.png)

>  # Java Script
 ## Conditional Statements
 Very often when you write code, you want to perform different actions for different decisions
You can use conditional statements in your code to do this.
In JavaScript we have the following conditional statements:

-   Use  `if`  to specify a block of code to be executed, if a specified condition is true
-   Use  `else`  to specify a block of code to be executed, if the same condition is false
-   Use  `else if`  to specify a new condition to test, if the first condition is false
-   Use  `switch`  to specify many alternative blocks of code to be executed

### 1. The if Statement

Use the  `if`  statement to specify a block of JavaScript code to be executed if a condition is true
### Syntax

    if  (_condition_) {  
    // _block of code to be executed if the condition is true_}

**Note that**  `if`  is in lowercase letters. Uppercase letters (If or IF) will generate a JavaScript error.

### 2.  The else Statement
Use the  `else`  statement to specify a block of code to be executed if the condition is false.

    if  (_condition_) {  
    // _block of code to be executed if the condition is true_}  else  {  
    // _block of code to be executed if the condition is false_}

### 3. The else if Statement

Use the  `else if`  statement to specify a new condition if the first condition is false.

### Syntax

    if  (_condition1_) {  
    // _block of code to be executed if condition1 is true_}  else  if  (_condition2_) {  
    // _block of code to be executed if the condition1 is false and condition2 is true_  
    }  else  {  
    // _block of code to be executed if the condition1 is false and condition2 is false_}
    
# Switch  Statement
The `switch` statement is used to perform different actions based on different conditions.
Use the  `switch`  statement to select one of many code blocks to be executed.

### Syntax

    switch(_expression_) {  
    case  _x_:  
    _// code block  
    _break;  
    case  _y_:  
    _// code block  
    _break;  
    default:  
    //  _code block_  
    }

This is how it works:

-   The switch expression is evaluated once.
-   The value of the expression is compared with the values of each case.
-   If there is a match, the associated block of code is executed.
-   If there is no match, the default code block is executed.

## The `Break` Keyword

When JavaScript reaches a  `break`  keyword, it breaks out of the switch block.

This will stop the execution of inside the block.

It is not necessary to break the last case in a switch block. The block breaks (ends) there anyway.

**Note:** If you omit the break statement, the next case will be executed even if the evaluation does not match the case.

## The `default` Keyword

The  `default`  keyword specifies the code to run if there is no case match.

**Note:** The `default` case does not have to be the last case in a switch block.

# For Loop
###  Loops can execute a block of code a number of times.
Loops are handy, if you want to run the same code over and over again, each time with a different value.
Often this is the case when working with arrays.

## Different Kinds of Loops

JavaScript supports different kinds of loops:

-   `for`  - loops through a block of code a number of times
-   `for/in`  - loops through the properties of an object
-   `for/of`  - loops through the values of an iterable object
-   `while`  - loops through a block of code while a specified condition is true
-   `do/while`  - also loops through a block of code while a specified condition is true

## The For Loop

The  `for`  loop has the following syntax:

    for  (_statement 1_; _statement 2_; _statement 3_) {  
    //  _code block to be executed_  
    }  

**Statement 1**  is executed (one time) before the execution of the code block.

**Statement 2**  defines the condition for executing the code block.

**Statement 3**  is executed (every time) after the code block has been executed.

### Example

    for  (i =  0; i <  5; i++) {  
    text +=  "The number is "  + i +  "<br>";  
    }

From the example above, you can read:
Statement 1 sets a variable before the loop starts (var i = 0).
Statement 2 defines the condition for the loop to run (i must be less than 5)
Statement 3 increases a value (i++) each time the code block in the loop has been executed.

![enter image description here](https://www.toolsqa.com/wp-content/gallery/javascript/For-loop-3.png)
1.  _**for**  is a reserved  **keyword**  used to indicate the start of for loop._
2.  _It is the initialization part where the loop index initializes._
3.  _Loop will continue to execute until the mentioned condition is satisfied._
4.  _Increment/decrement of the index variable will happen, which controls the loop._
5.  _The body of the loop contains logical statements that need to iterate._

# While Loop
Loops can execute a block of code as long as a specified condition is true.
 

### Syntax

    while  (_condition_) {  
	  code block to be executed  
    }
In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10:
### Example

    while  (i <  10) {  
    text +=  "The number is "  + i;  
    i++;  
    }
    
## The Do/While Loop

The  `do/while`  loop is a variant of the while loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

### Syntax

    do  {  
    _// code block to be executed  
    _}  
    while  (_condition_);
