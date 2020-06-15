


# Today's topics are interestin and very Important:

**>  1. Object-Oriented Programming,**
**>  2.  HTML Tables**
 

> # 1. Object-Oriented Programming:
1. Object– An Object is a unique entity which contains property and methods. For example “car” is a real life Object, which have some characteristics like color, type, model, horsepower and performs certain action like drive. The characteristics of an Object are called as Property, in Object Oriented Programming and the actions are called methods. An Object is an instance of a class. Objects are everywhere in JavaScript almost every element is an Object whether it is a function,arrays and string.
Note: A Method in javascript is a property of an object whose value is a function.
Object can be created in two ways in JavaScript:
**1. Using an Object Litera**

    //Defining object 
    let person = { 
    	first_name:'shadi', 
    	last_name: 'zaqout', 
    
    	//method 
    	getFunction : function(){ 
    		return (`The name of the person is 
    		${person.first_name} ${person.last_name}`) 
    	}, 
    	//object within object 
    	phone_number : { 
    		mobile:'12345' 
     	} 
    } 
    console.log(person.getFunction()); 
    console.log(person.phone_number.landline); 


**2. Using an Object Constructor**

    //using a constructor 
    function person(first_name,last_name){ 
    this.first_name = first_name; 
    this.last_name = last_name; 
    } 
    //creating new instances of person object 
    let person1 = new person('shadi','zaqout	'); 
    let person2 = new person('hani','zaqout'); 
    
    console.log(person1.first_name); 
    console.log(`${person2.first_name} ${person2.last_name}`); 

Object literal property values can be of any data type, including array literals, functions, and nested object literals. Here is another object literal example with these property types:

    var Swapper = {
        // an array literal
        images: ["smile.gif", "grim.gif", "frown.gif", "bomb.gif"],
        pos: { // nested object literal
            x: 40,
            y: 300
        },
        onSwap: function() { // function
            // code here
        }
    };
**3. Using Object.create() method**
  

      
    const coder = { 
    	isStudying : false, 
    	printIntroduction : function(){ 
    		console.log(`My name is ${this.name}. Am I 
    		studying?: ${this.isStudying}.`) 
    	} 
    } 
    // Object.create() method 
    const me = Object.create(coder); 
    
    // "name" is a property set on "me", but not on "coder" 
    me.name = 'Shadi'; 
    
    // Inherited properties can be overwritten 
    me.isStudying = 'True'; 
    
    me.printIntroduction(); 

    
    
2. **Classes**– Classes are **blueprint** of an Object. A class can have many Object, because class is a **template** while Object are **instances** of the class or the concrete implementation.

   

 

    // Defining class using es6 
        class Vehicle { 
        constructor(name, maker, engine) { 
        	this.name = name; 
        	this.maker = maker; 
        	this.engine = engine; 
        } 
    getDetails(){ 
    	return ( The name of the bike is ${this.name}. ) 
    } 
    } 
    // Making object with the help of the constructor 
    let bike1 = new Vehicle('Hayabusa', 'Suzuki', '1340cc'); 
    let bike2 = new Vehicle('Ninja', 'Kawasaki', '998cc'); 
    
    console.log(bike1.name); // Hayabusa 
    console.log(bike2.maker); // Kawasaki 
    console.log(bike1.getDetails());



  > # 2. HTML Tables
Object literals are defined using the following syntax rules:

 HTML tables allow web authors to arrange data into rows and columns.
 An HTML table is defined with the  `<table>`  tag.

Each table row is defined with the  `<tr>`  tag. A table header is defined with the  `<th>`  tag. By default, table headings are bold and centered. A table data/cell is defined with the  `<td>`  tag.

## HTML Table - Adding a Border

If you do not specify a border for the table, it will be displayed without borders.

A border is set using the CSS  `border`  property:

    table, th, td {  
    border:  1px solid black;  
    }
## HTML Table - Collapsed Borders

If you want the borders to collapse into one border, add the CSS  `border-collapse`  property:
 
    table, th, td  {  
    border:  1px solid black;  
    border-collapse:  collapse;  
    }
