### Javascript Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Name some of the data types in Javascript.

  //Your Answer
  boolean, number, null, undefined, string


  //Googled Answer
  same as above, plus symbol


#### 2. Describe what "if" does in Javascript.

  //Your Answer
  if runs a bit of code depending on true or false


  //Googled Answer
 "if" is a conditional statement that executes code depending on true or false

#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".
function ifDivisible (number) {
  if (number %3 === 0) {
  console.log(number + " is divisible by three");
} else {
  console.log(number + " is not divisible by three");
  }
}

#### 4. What is JSON?
  //Your Answer
  JSON is short for Javascript Object Notation. It is mainly used to transmit data between the web application and server. Dot notation is used to make it very readable and minimal.

  //Googled Answer
  Same as above. It also serves as an alternative to XML.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.
var kate {
  age: 20,
  gender: female,
  phone: 6194025688
}

#### 6. What is a closure?

  //Your Answer
  Closure is used all throughout our code. They are inner functions that have access to outer functions, as well.

  //Googled Answer
  They are also used widely in Node.js

#### 7. What's the difference between =, ==, and === in JavaScript?

  //Your Answer
  = assigns values
  == compares two values and determines if they are equal to one another
  === strictly equal to


  //Googled Answer

#### 8. Create an array with at least 4 items inside it, then access two of the values and console.log() them. Try to access the two values in two different ways.
var fruits = ["oranges", "apples", "kiwi", "grapefruit", "grapes"]
console.log(fruits[0]);
console.log(fruits[3]);

#### 9. Describe the different kinds of loops and why you would use them.

  //Your Answer

  for loops --should be used for arrays
  for in loops -- best if used with objects
  while loops -- will run through a bit of code while it is true
  do while loops -- will run the code once before checking for true/false



  //Googled Answer

#### 10. How would you explain "scope" in javascript?

  //Your Answer
  there is global and local scope. local pertains to properties inside of a function, while global scope stays outside of the funtions. anything out in the open of a JS file is global


  //Googled Answer
All functions and scripts on a webpage can access global scope.
