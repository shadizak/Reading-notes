




# Today's topics about  Handling Errors and  JS Debugging:
   
 # **1. Handling Errors**
**Exception handling** is the process of responding to the occurrence of exceptions – anomalous or exceptional conditions requiring special processing - during the execution of a program. In general, an exception breaks the normal flow of execution and executes a pre-registered exception handler; the details of how this is done depend on whether it is a hardware or software exception and how the software exception is implemented. It is provided by specialized programming language constructs, hardware mechanisms like interrupts, or operating system (OS) inter-process communication (IPC) facilities like signals. Some exceptions, especially hardware ones, may be handled so gracefully that execution can resume where it was interrupted.

An alternative approach to exception handling in software is error checking, which maintains normal program flow with later explicit checks for contingencies reported using special return values, floating point status flags. Input validation, which preemptively filters exceptional cases, is also an approach.

## HOW TO  Exception Handling in JS?
### BY >>Throw and Try to Catch
 1. The  `try`  statement lets you test a block of code for errors.

2. The  `catch`  statement lets you handle the error.

3. The  `throw`  statement lets you create custom errors.

4. The  `finally`  statement lets you execute code, after try and catch, regardless of the result.

## Errors Will Happen!
When executing JavaScript code, different errors can occur.

Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.

In this example we have written alert as adddlert to deliberately produce an error:

    <p id="demo"></p>  
      
    <script>  
    try  {  
    adddlert("Welcome guest!");  
    }  
    catch(err) {  
    document.getElementById("demo").innerHTML  = err.message;  
    }  
    </script>

 
 ## JavaScript try and catch

The  `try`  statement allows you to define a block of code to be tested for errors while it is being executed.

The  `catch`  statement allows you to define a block of code to be executed, if an error occurs in the try block.

The JavaScript statements  `try`  and  `catch`  come in pairs:

    try {  
    Block of code to try  
    }   catch(err) {  
    Block of code to handle errors  
    }
## JavaScript Throws Errors
The  `throw`  statement allows you to create a custom error.

Technically you can  **throw an exception (throw an error)**.

The exception can be a JavaScript  `String`, a  `Number`, a  `Boolean`  or an  `Object`:

    throw  "Too big"; // throw a text  
    throw  500; // throw a number
If you use `throw` together with `try` and `catch`, you can control program flow and generate custom error messages.
## Input Validation Example
This example examines input. If the value is wrong, an exception (err) is thrown.

The exception (err) is caught by the catch statement and a custom error message is displayed:

    <!DOCTYPE html>  
    <html>  
    <body>  
      
    <p>Please input a number between 5 and 10:</p>  
      
    <input id="demo"  type="text">  
    <button type="button"  onclick="myFunction()">Test Input</button>  
    <p id="p01"></p>  
      
    <script>  
    function  myFunction() {  
    var  message, x;  
    message = document.getElementById("p01");  
    message.innerHTML  =  "";  
    x = document.getElementById("demo").value;  
    try  {  
    if(x ==  "")  throw  "empty";  
    if(isNaN(x))  throw  "not a number";  
    x = Number(x);  
    if(x <  5)  throw  "too low";  
    if(x >  10)  throw  "too high";  
    }  
    catch(err) {  
    message.innerHTML  =  "Input is "  + err;  
    }  
    }  
    </script>  
      
    </body>  
    </html>
## HTML Validation
The code above is just an example.

Modern browsers will often use a combination of JavaScript and built-in HTML validation, using predefined validation rules defined in HTML attributes:

    <input id="demo"  type="number"  min="5"  max="10"  step="1">
  ## The finally Statement
  The `finally` statement lets you execute code, after try and catch, regardless of the result:
  ### Syntax: 
 

     try {  
    Block of code to  try  
    }  
    catch(err) {  
    Block of code to handle errors  
    }  
    finally {  
    Block of code to be executed regardless of the  try  /  catch  result  
   }
# **2. JS Debugging**
## HOW TO DEAL WITH ERRORS:
1. DEBUG THE SCRIPT TO FIX ERRORS

If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.

You will find that the developer tools available in every major modern browser will help you with  
this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in Chrome are identical to those in Opera.)

 
2.  HANDLE ERRORS GRACEFULLY You can handle errors gracefully using try, catch,

throw, and f i na1ly statements.

Sometimes, an error may occur in the script for a reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code.
## Debugging TOOLS:
 ### 1.  BROWSER DEV.  TOOLS & JAVASCRIPT CONSOLE
  ### 2 .JAVASCRIPT http://www.jslint.com http://www.jshint.com
