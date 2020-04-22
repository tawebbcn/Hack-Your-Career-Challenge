# Hack Your Chareer Challenge


## Introduction

If you are reading this, it means you are one step closer to learning the nits and grits of becoming a Web Developer. Through this document you'll get to create some scripts to help us decide the space travel movie we'll watch tonight! 

You will have to deliver your challenge in a .js file. Here at Ironhack we use Visual Studio code editor, but you can use any other such as Brackets, Sublime, etc. We leave it up to your personal preference. 

Please find the data set you need to use in your exercise in the data.js file.

..............................................


## Challenge

While stuck at home and daydreaming about escaping from planet Earth until the coronavirus pandemic is under control, we’ve come across a list of the 12 best space travel movies of all times 🎥💥 We need your JavaScript skills to solve the following challenges!

  -- First things first. We don't want to watch any space travel movie, we want to watch the best rated ones! 🏆    
  **_Let's print the movies with a rate of at least 8.0 and print the "title" and "rate" in the console_**.

  -- Awesome! We would like to store these "best rated" movies somewhere, in order to watch them later 🍿    
  **_Add the movies with a rate greater or equal than 8.0 in an array called "bestMovies" and print this array to the consolee_**. 

  -- Ridley Scott movies are always entertaining, don't you think? So let's select only the movies he directed 🎬    
  **_Print to the console the movies that are from this director_**.

  -- On second thought, his movies are a bit too long and we feel tired today 😴 So... we would like to watch the shortest movie of the movies list.    
  **_Based on the "duration" (which is in minutes), can you print the shortest movie to the console?_**

  -- Finally! We've watched all the movies, and we’d like to order them by their release year.     
  **_Sort the movies in descending order (from newest to oldest) by the year_**.   
  => Bonus (not mandatory to complete the challenge): **_if two movies have the same release year, order them in alphabetical order by their title_**


..............................................


## Help Sheet

If you have never played with JavaScript or you see yourself a bit lost, we recommend performing one or a couple of free courses which will help you to have a better understanding of Javascript from the beginning. See links below:

FreeCodeCamp => focus on the "Basic JavaScript" unit:

https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/basic-javascript/:

Codecademy => here you will find another introductory course to JavaScript (units 1 to 8):

https://www.codecademy.com/learn/introduction-to-javascript

If you already know some basic JavaScript we have written some information which might help you to be successful in the challenge.


### Variables

A variable is a named location for storing a value. That way an unpredictable value can be accessed through a predetermined name.

The var statement declares a variable, optionally initializing it to a value.

Syntax
```
var varname1 [= value1]
```

Demo:
```
var x = 1;

if (x === 1) {
  var x = 2;

  console.log(x);
  // expected output: 2
}

console.log(x);
// expected output: 2
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var


### Arrays

An array is an ordered collection of data (either primitive or object depending upon the language). Arrays are used to store multiple values in a single variable. This is compared to a variable that can store only one value. 

Each item in an array has a number attached to it, called a numeric index, that allows you to access it. In JavaScript, arrays start at index zero and can be manipulated with various methods. 

Syntax:
```
[element0, element1, ..., elementN]
```

Demo:
```
var fruits = ['Apple', 'Banana'];

```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array


### For loop

The for statement creates a loop that consists of three optional expressions, enclosed in parentheses and separated by semicolons, followed by a statement (usually a block statement) to be executed in the loop.

Syntax
```
for ([initialization]; [condition]; [final-expression])
   statement
```

Demo:
```
var str = "";

for (var i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
// expected output: "012345678"
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for


### Functions

A function is a code snippet that can be called by other code or by itself, or a variable that refers to the function. When a function is called, arguments are passed to the function as input, and the function can optionally return an output. A function in JavaScript is also an object.

A function name is an identifier declared as part of a function declaration or function expression. The function name's scope depends on whether the function name is a declaration or expression.

Functions are one of the fundamental building blocks in JavaScript. A function is a JavaScript procedure — a set of statements that performs a task or calculates a value. To use a function, you must define it somewhere in the scope from which you wish to call it.

Syntax
```
function name(parameter1, parameter2) {
  // code to be executed
}
```

Demo:
```
var number = 2;

function square(number) {
  return number * number;
}

square(number);

// expected output: 4
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Glossary/Function

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions


### If statement

The if statement executes a statement if a specified condition is truthy. If the condition is falsy, another statement can be executed.

Syntax
```
if (condition)
   statement1
[else
   statement2]
```

Demo:
```
function testNum(a) {
  if (a > 0) {
    return "positive";
  } else {
    return "NOT positive";
  }
}

console.log(testNum(-5));
// expected output: "NOT positive"
```

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else


### Objects In Javascript

In JavaScript, objects are king. If you understand objects, you understand JavaScript.
All JavaScript values, except primitives (like strings), are objects.

Javascript variables can contain single values:
```
var person = "Maria Garcia ";
 ```
Javascript objects can contain many values:
```
var person = {firstName:"Maria", lastName:"Garcia", age:50, eyeColor:"blue"};
```
The named values, in JavaScript objects, are called properties.

The syntax for accessing the property of an object is either of the two below options:
- objectName.property
- objectName['property']

to reassign a property we can use:
```
person.lastName = "Jones";
```
if this propery doesnt exist it will add a new one to the object.

Documentation: 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects
