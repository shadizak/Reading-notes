 
# Today we are going to talk about texts,CSS and JS in HTML

## Text

1. Headings and paragraphs
2. Bold, italic, emphasis
3. Structural and semantic markup
 
 
 ##  Headings
 
HTML has six "levels" of headings:
<h1> is used for main headings <h2> is used for subheadings
If there are further sections under the subheadings then the <h3> element is used, and so on...
Browsers display the contents of headings at different sizes. The contents of an <h1> element is the largest, and the contents of an <h6> element is the smallest. The exact size at which each browser shows the headings can vary slightly. Users can also adjust the size of text in their browser. You will see how to control the size of text, its color, and the fonts used when we come to look at CSS.
 
_For Example_
 
```
html>
    <body>
         <h1>This is a Main Heading</h1>
         <h2>This is a Level 2 Heading</h2>
         <h3>This is a Level 3 Heading</h3>
         <h4>This is a Level 4 Heading</h4>
         <h5>This is a Level 5 Heading</h5>
         <h6>This is a Level 6 Heading</h6>
         
    </body>
</html>
```
### Paragraphs 
To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag.
By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.
 _For Example_
 
```
    <p>Shadi</p>
    <p>Zaqout</p>
 ```
##  Bold & iTalic 

1.the  <b>  
By enclosing words in the tags <b> and </b> we can make characters appear bold.
The <b> element also represents a section of text that would be presented in a visually different way (for example key words in a paragraph) although the use of the <b> element does not imply any additional meaning.

2. the <i>  
By enclosing words in the tags <i> and </i> we can make characters appear italic.
The <i> element also represents a section of text that would be said in a different way from surrounding content — such as technical terms, names of ships, foreign words, thoughts, or other terms that would usually be italicized. 
  
# Superscript and Subscript

1. ``` <sup> ```
The <sup> element is used
to contain characters that should be superscript such
as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

2. ``` <sub> ```
The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

## Horizontal rules and Line breaks
There are two tags that can be used to control the layout of your page.
1. Horizontal Rule ``` <hr> ```

To create a break between themes — such as a change of topic in a book or a new scene
in a play — you can add a horizontal rule between sections using the <hr /> tag.
There are a few elements that do not have any words between an opening and closing tag. They are known as empty elements and they are written differently.
An empty element usually
has only one tag. Before the closing angled bracket of an empty element there will often be a space and a forward slash character. Some web page authors miss this out but it is a good habit to get into.

2. Line break ``` <br> ``` inserts a end of line where it appear
As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag <br />.


NOTE: Neither have a closing tag or associated text, their use is fairly straightforward.

## Strong & Emphasis
The <strong> and <em> tags are used for emphasizing parts of a text. The <strong> tag should be used to indicate strong importance, seriousness, or urgency, like to indicate key phrases in a text for someone skimming it. The <em> tag should be used to represent stress emphasis, like when you'd read the emphasized text in a different tone of voice. Both tags can be used together, where it makes sense.
 
 
 
 ```
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>HTML:The strong and em tags</title>
</head>
<body>
      <p>Where recognition of the inherent dignity and of the <strong>equal and inalienable rights</strong> of <em>all members of the human family</em> is the foundation of <strong><em>freedom, justice and peace in the world</em></strong>.</p>
 
 </body>
</html>

 ```
 
## The Abbreviation element

``` <abbr> ```

The ```<abbr>``` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
 
```
<!DOCTYPE html>
<html>
<body>

<h1>The abbr element</h1>

<p>The <abbr title="Cascading Style Sheets">CSS</abbr> was founded in Read 02 :) .</p>

</body>
</html>
```
##  auTHor deTails

``` <address> ```
he <address> element has quite a specific use: to contain contact details for the author of the page.
It can contain a physical address, but it does not have to. For example, it may also contain a phone number or email address.
Browsers often display the content of the <address> element in italics.
You may also be interested in something called the hCard microformat for adding physical address information to your markup.

 ``` <address>
<p><a href="mailto:homer@example.org">
homer@example.org</a></p>
<p>742 Evergreen Terrace, Springfield.</p>
</address> 
```
## Example Text

his is a very simple HTML page that demonstrates text markup.
```
<html>
  <head>
<title>Text</title> </head>
<body>
<h1>The Story in the Book</h1>
<h2>Chapter 1</h2>
<p>Molly had been staring out of her window for about
an hour now. On her desk, lying between the copies of <i>Nature</i>, <i>New Scientist</i>, and all the other scientific journals her work had appeared in, was a well thumbed copy of <cite>On The Road</cite>. It had been Molly's favorite book since college, and the longer she spent in these four walls the more she felt she needed to be free.</p>
<p>She had spent the last ten years in this room, sitting under a poster with an Oscar Wilde quote proclaiming that <q>Work is the refuge of
people who have nothing better to do</q>. Although many considered her pioneering work, unraveling the secrets of the llama <abbr title="Deoxyribonucleic acid">DNA</abbr>, to be an outstanding achievement, Molly <em>did</em> think she had something better to do.</p>
  </body>
</html>
```

## IntroducIng CSS
  
In this section, we will look at how to make your web pages more attractive, controlling the design of them using CSS.
 
 **Content table**

1. Introduce you to how CSS works
2. Teach you how to write CSS rules
3. Show you how CSS rules apply to HTML pages
 
**What is CSS?**

CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

**Why CSS?**
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.


CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

```
p {
    font-family: Arial;
}
```

![CSS Rule](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

This rule indicates that all "p" elements should be shown in the Arial typeface.

Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.


**How to write CSS**

First you need to find the selector you want to apply **CSS** on it like paragraph or anything else like bellow
```
p, h1, h2, li {
    color: #cccccc;
    font-weight: 700; // 700 will give you a Bold text
}
```


 ## How to apply CSS in your page

There are three way to implement your CSS with
1. Inline CSS
2. Add style tag into head and put your css on it
3. External CSS file the link it to you page

 
 

## JavaScript 
##  JavaScript is the programming language of HTML and the Web.

##  Why Study JavaScript?
JavaScript is one of the 3 languages all web developers must learn:

   1. HTML to define the content of web pages

   2. CSS to specify the layout of web pages

   3. JavaScript to program the behavior of web pages

Web pages are not the only place where JavaScript is used. Many desktop and server programs use JavaScript. Node.js is the best known. Some databases, like MongoDB and CouchDB, also use JavaScript as their programming language.

##  Basic Knowledge in JavaScript

## STATEMENT
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.
Statements should end with a semicolon (;).

##  COMMENTS
You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. Like This : /* Thi s script displays a greeting to the user based upon the current time. It is an example from JavaScript &jQuery book */

##  WHAT IS A VARIABLE?

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

When you write JavaScript, you have to tell the interpreter every individual step that you want it to perform. This sometimes involves more detail than you might expect.

Think about calculating the area of a wall; in math the area of a rectangle is obtained by multiplying two numbers:
width x height = area

You may be able to do calculations like this in
your head, bu t when writing a script to do this calculation, you need to give the computer very detailed instructions. You might tell it to perform the following four steps in order:

1. Remember the value for width
2 . Remember the value for height
3. Multiply width by height to get the area 4.Return the result to the user

In this case, you would use variables to "remember" the values for width and height. (This also illustrates how a scrip( contains very explicit instructions about exactly what you want the computer to do.)
You can compare variables to short-term memory, because once you leave the page, the browser will forget any information it holds.

Ex:

var price1 = 5;
var price2 = 6;
var total = price1 + price2;
 
## Expressions and Operators:

1. JavaScript has the following types of operators.
2. Assignment operators
3. Comparison operators
4. Arithmetic operators
5. Logical operators
6. String operators
7. Relational operators


## JavaScript Function:

A function is a series of statements that do something, such as calculate a value, perform a task, or complete another action. The difference between writing a function and just writing a bunch of statements is that a function encapsulates what you want to do. You get to use it again in a way similar to how we use variables to hold data types.


## Define a function using the keyword function, followed by a name, followed by parentheses. Insert the code to be executed by the function inside curly brackets and don't forget to add semicolons:

function sayHello() {
    alert("Hello");
};

You defined the function, but did not yet call or execute it.

Type sayHello(); to call the function by its name and a set of parentheses (). You just executed your function!

sayHello();

While this was a good step, we want a function that takes in some data (also called parameters) and does something with it.

## Make a version of sayHello() that greets you by name, like so:

function sayHello(name) {
  alert("Hello " + name);
};

Here we now have a function called "sayHello" that takes a parameter as an input in its parantheses called "name". Inside the function, we create an alert that displays "Hello " followed by the value of name that was input to the function.

Now call it with your name as a string in place of name. Don’t forget the quotes:

sayHello("Shadi hahahahha");

## return Keyword

// With return
function sum(num1, num2) {
  return num1 + num2;
}

Without return, so the function doesn't output the sum

function sum(num1, num2) {
  num1 + num2;
}

functions return (pass back) values using the return keyword. return ends function execution and returns the specified value to the location where it was called. A common mistake is to forget the return keyword, in which case the function will return undefined by default.



 ## Summary 
 
 A script is made up of a series of statements.
 Each statement is like a step in a recipe.
Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
Variables are used to temporarily store pieces of information used in the script.
Arrays are special types of variables that store more than one piece of related information.
JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
Expressions evaluate into a single value. Expressions rely on operators to calculate a value.


