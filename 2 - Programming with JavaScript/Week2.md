Notes by Soumyajeet Bal

# The Building Block Of A Program
Here you'll learn how to use objects, arrays and functions. In addition, you will learn about the most common built-in methods, and the difference between undefined, null and empty strings. And you'll explore both error handling and defensive programming. After completing this module, you will be able to:
Learning Objectives
Build and use objects, arrays, and functions
List some common built-in methods on built-in objects
Describe handling bugs and errors using try, catch, throw, and defensive programming
Explain the difference between undefined, null, and empty strings
Demonstrate how to write basic code using arrays, objects, and functions

# Arrays, Objects and Fucntions
### Video 1 : Functions
- function keyword for function declaration
- Advantage, declaration, use and call/invoke/run
- DRY acronym - Dont repeat yourself
- function parameter and arguments (unlike java )



### Video 2 : Storing data in arrays
- array
- var train1= ["wheat","barley","potato"];

Building and calling functions : https://www.coursera.org/learn/programming-with-javascript/supplement/8Xc01/building-and-calling-functions



### Video 3 : Introduction to objects
- object is basically specific state
- object has an identity, a behavior and a state. 
- object are used to relate different datas
- object declaration     d
  ```
  var a = {};
  a.first=1;
  a.second = "two";
  ```
- object are collection of related properties
- property key and property value
- ```
     var a = {
     first : 1,
     second : "two" } 
  ```
- dot notation

### code 
```
function letterFinder(word, match) {
    for(var i = 0; i < word.length; i++) {
        if(word[i] == match) {
            //check if the current characater, word[i], is equal to the match
            console.log('Found the', match, 'at', i)
        } else {
            console.log('---No match found at', i)
        }
    }
}

letterFinder("test", "t")

```


### Video 4 : Introduction to objects
- group of data
- to establish relation between datas
- variable name is property key; and variable value becomes object value.
 ```
  var name = {
  height: 6,
  social: 60,
  streetsmart: 80,
  health: 60
  } 
  ```
- object can be updated after they are created by dot notaion.
- name.study = 80;

https://www.coursera.org/learn/programming-with-javascript/supplement/ovZyv/object-literals-and-the-dot-notation
https://www.coursera.org/learn/programming-with-javascript/supplement/9j3wI/object-literals-and-the-brackets-notation

```
var fruits = [];
fruits.push("apple"); // ['apple']
fruits.push('pear'); // ['apple', 'pear']
```
https://www.coursera.org/learn/programming-with-javascript/supplement/uhT9O/math-object-cheat-sheet

### Video 5 : Math object
- Math.random()
- Math.ceil() ceil to upper integer


### Video 6 : A closer look at strings
- iterable datatypes
- strings can be iterated over
- .length
- .concat 
- .pop
- .charAt(index)


  String cheatsheet  - https://www.coursera.org/learn/programming-with-javascript/supplement/smpcZ/string-cheat-sheet 
  Object Model - https://www.coursera.org/learn/programming-with-javascript/supplement/NgndT/object-methods

### Video 7 : Typeof
- typeof
- Arrays in js are objects

Different ways to add properties to an object in js.
https://www.scaler.com/topics/add-property-to-object-javascript/

Additional Resources
https://www.coursera.org/learn/programming-with-javascript/supplement/z8HHt/additional-resources




### Video 8 : Type Of Errors
- bugs - causes a program to run in an uninteded way
- error - causes a program to stop running
- Syntax, reference and type errors
- Syntax error - "Hello;
- Reference Error - a+b; but a and b are not defined.
- Type Error - (5).pop();   - the type of 5 is number but pop is intended for array.
- bug ex- we want to add to number.. but '1'+2 gives result 12 but we expected 3.. this is because of the bug. in this case typo which caused concatenation.
- As error abruptly stops the program.thus we need to have something called error handling.




### Video 9 : Try catch blocks
- try and catch helps code continue to run even if it runs into an error.
- throw, try, catch
- i.e the error gets wrapped inside the try block and the catch block catches it for further execution.
- throw keyword helps throw error from try block to the catch block. thus the catch block will expect something an error which is an object.
- throw new ReferenceError(); - for test ; throws error
```
try{
     console.log(a+b);
     }
catch(err){ //built in reference object
    console.log(err) // error recieved an object will be printed
    console.log("There was an error");
    }
console.log("My program is still running"); //this line will get printed that shows the program is still runnning.
```

All the type of errors :  https://www.coursera.org/learn/programming-with-javascript/supplement/W5XJb/syntax-logical-and-runtime-errors
``` (10).toString(2); ```


### Video 10 : Undefined, null and empty values
- undefined can hold only 1 value i.e undefined
- it acts as a placeholder for the valus which are yet to exist.
- empty string
- 




### Video 1 : 





### Video 1 : 





### Video 1 : 





### Video 1 : 





### Video 1 : 





### Video 1 : 





### Video 1 : 




### Video 1 : 



### Video 1 : 
