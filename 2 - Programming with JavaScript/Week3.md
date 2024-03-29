Notes by Soumyajeet Bal

# Introduction to functional programming
### Video 1 : Introduction to functional programming
- in programming, there are two commonly used paradigms
- functional programming (fp) and object oriented programming (oop)
- functional programming is used when we need to seperate data from fucntion.



### Video 2 : Function calling and recursion
- basic function calling and infinite loop recursion
- == and === recall
- let vs var keyword
- 


### Video 3 : Introduction to scope
- global and local scope


https://www.coursera.org/learn/programming-with-javascript/supplement/oPXvr/the-functional-programming-paradigm
First-class functions

It means that a function in JavaScript is just another value that we can:
* pass to other functions
* save in a variable
* return from other functions

Higher-order functions
* It accepts other functions as arguments
* It returns functions when invoked

Pure function - function which will return the same value every time as long as the input are same.


```
// Task 1: Build a function-based console log message generator
var message, style;
function consoleStyler(color, background, fontSize, txt) {
    var message = "%c" + txt;
    var style = `color: ${color};`
    style+= `background: ${background};`
    style += `font-size: ${fontSize};`
    console.log(message, style);
}

// Task 2: Build another console log message generator
function celebrateStyler(reason) {
    var fontStyle = "color: tomato; font-size: 50px";
    if (reason == "birthday") {
        console.log(`%cHappy birthday`, fontStyle);
    }
    else if (reason == "champions") {
       console.log(`%cCongrats on the title!`, fontStyle);
    }
    else {
        console.log(message, style);
    }
    
}

// Task 3: Run both the consoleStyler and the celebrateStyler functions
consoleStyler('#1d5c63', '#ede6db', '40px', 'Congrats!');
celebrateStyler('birthday');

// Task 4: Insert a congratulatory and custom message
function styleAndCelebrate(color, background, fontSize, txt, reason) {
    consoleStyler(color, background, fontSize, txt);  
    celebrateStyler(reason);
}
// Call styleAndCelebrate
styleAndCelebrate('ef7c8e', 'fae8e0', '30px',  'You made it!', 'champions');
```

### Video 4 : Scoping with var, let and const
- all the code outside of function is global and all the code inside the funtion is called local.
- ES6 version of js introduced block scope
- let and const
- let and const are scoped to the block
- use let if value will change and const if value will not chnage 




### Video 5 : Comparing var, let and const
- var variable can be used before declaration.. output will most likely be undefined
- redefining again and again using var gives no error.. the last update will be the final
- let variable needs to be declared first to use and no redeclaration
- const can be re declared but the catch  is const needs to be declared and initialized too

Additional Resources:
https://www.coursera.org/learn/programming-with-javascript/supplement/plJph/additional-resources

# Introduction to Object-Oriented Programming
### Video 1 : Introduction to object-oriented programming
- this keyword works as alias
- function paradigm and oop paradigm
- this keyword abstains us from writing custom methods.

### Video 2 : Classes
- class essentially is a blueprint to built new object
- constructor function accepts many parameters and the role of it is to assign the passed in parameters for the future object property
- inside the class, no need to specify function keyword to declare function.

Object Oriented Programming principles
https://www.coursera.org/learn/programming-with-javascript/supplement/rt3PB/object-oriented-programming-principles
var myDog = Object.create(Animal)
var myDog = new Animal()

https://www.coursera.org/learn/programming-with-javascript/supplement/rt3PB/object-oriented-programming-principles

Constructors :
https://www.coursera.org/learn/programming-with-javascript/supplement/ZhGvD/constructors


### Video 3 : Inheritance
- create syntax is used to create as many objects as we want.
- inheritence using bird and eagle1 and penguin.
- var bird{ properties }
- var eagle1 = object.create(bird);
- inheritance doesnt changes the original object prototype

Creating classes
https://www.coursera.org/learn/programming-with-javascript/supplement/VJhho/creating-classes

### Video 3 : Inheritance
### Video 3 : Inheritance
### Video 3 : Inheritance
### Video 3 : Inheritance
### Video 3 : Inheritance
### Video 3 : Inheritance
### Video 3 : Inheritance

