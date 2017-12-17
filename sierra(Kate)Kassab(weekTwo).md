### Javascript Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. How do you link a css file to your html page?
//Your Answer
You link a css file in the head of your HTML file.
The code is: link type="text/css" rel="stylesheet" href= "fileName.css"


 //Googled Answer
 n/a


 #### 2. What is a css class? How do you use declare one in html? How do you use it in css?
//Your Answer
 When using a CSS class, you're calling multiple elements. Otherwise, it's an ID. You can declare one in HTML by using
 <p class = "nameExample">hello this is an example</p> and then call .nameExample {} in your CSS.

To call an ID, you would use <p id="nameExample"> hello this is an example </p> in your HTML, and then call #nameExample {} in your css file.



 //Googled Answer
 n/a


#### 3. The class "heading-box" exists in our html file - write the css code that would:
##### 1) align this box to the center of its container,
.heading-box {
  align-content: center;
}
##### 2) give it a black border that is 5px wide,
.heading-box {
  border-style: solid;
  border-width: 5px;
}

##### 3) make its text appear in the center of the box
.heading-box {
  text-align: center;
}


#### 4. What is Bootstrap? Explain a few reasons that you might choose to use it in a project?
 //Your Answer
 Bootstrap is a library containing multiple templates that can be applied to your css. For example, you could use a jumbotron as a container to display header elements; or, you could use a carousel to display pictures. Bootstrap is commonly used because it is very simple and can make web pages much more stylish.

 //Googled Answer
 n/a


#### 5. Name 4 semantic html tags.
<table> <form> <header> <footer>
#### 6. What is block scope that became available in ES6? Include how it differs from local and global scope, and what variables are block scoped.

 //Your Answer
 Block scope is a new feature that was added that allows a scope to pertain to the curly brackets. Local scope is the scope within functions. Global scope is anything that exists within the file that is not inside of a function.


 //Googled Answer
n/a
 #### 7. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?
 Front end development is the development of anything that can be seen or interacted with on the webpage.
 tools/skills: html, css, javascript, atom, github, jquery, node.js, react


 //Googled Answer
 n/a


 #### 8. Choose one of the new ES6 concepts we learned about this week (namely: block scope, classes, and string interpolation) and write example code that demonstrates the concept, with comments to explain what is going on.
 Classes: define attributes and behavior. They cannot act on their own. They are blueprints for an object.
 Example--
 class Car{
   constructor(){
     this.speed = 0,
     this.year = 2005,
     this.color = "red"
   }
 }
 let car = new Car ()
 console.log("The speed is: ", car.speed)



 #### 9. What is the difference between a div and a span?
//Your Answer
 span is inline and used for small amounts of code, whereas a div is block-line and can be used for multiple.


 //Googled Answer

#### 10. How would you explain the idea of "inheritance" in object oriented programming?
  //Your Answer
Inheritance is when a class receives properties from a parent class. It allows classes to share attributes, but be different in their own ways.

 //Googled Answer
n/a
