### Javascript Course Assessment

## Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. SQL stands for Structured Query Language. In your own words (no need to write a googled answer), what role does SQL play in a full-stack web application? How does this relate to MVC organization?
SQL is used for databases. It cannot be translated without sequelize when coding in JS. MVC (model view controller)


#### 2. Here is a basic SQL query. What are the various parts of this statement doing? (Comment the code to explain each piece)

     SELECT //we are selecting the name, breed, vaccinations, and age set to the human equivalent
      name,
      breed,
      vaccinations,
      age * 15 AS equivalent_human_age,
    FROM //declares which database
      mydogs
    WHERE //setting conditions
      equivalent_human_age > 20
    ORDER BY //setting an order of view
      equivalent_human_age DESC



#### 3. What is a foreign key?

// Your Answer
A foreign key is used to grab only the information that is wanted from one database and apply it to another.

// Googled Answer
A column that references another column from another database.


#### 4. What is this Sequelize code doing? Comment the code to explain each peice.

    ComicBook //this is taking the database and basically turning it into a class to map through
      .all({limit: 2}) //takes all of the ComicBook info
      .then(function(comics){ //declares the function and sets comics as a parameter
      let mapped = comics.map(function(cb){ //mapping through comics in C
         return cb.get() //.get() is a function that can return a specific element, but it is simply returning all
      })
      console.log(mapped) //displays all the info that was mapped through in the console
    })



#### 5. Try to explain the role of an ORM in a full-stack application. Include at least two benefits of implementing an ORM.

//Your Answer
ORM--Object Relation Mapper
Purposes: We can treat tables as classes, capable of connecting to two different databases

 //Googled Answer

#### 6. Write a command to alter the TABLE water_monsters in the monster DATABASE to name it "sea_monsters" instead.(assume we are using a postgres databse)

 //Your Answer
 ALTER TABLE water_monsters RENAME TO sea_monsters



 #### 7. What does CRUD stand for? And what do we use CRUD actions for?

 //Your Answer
 CREATE, READ, UPDATE, DESTROY. These are the four basic functions that we use all of the time when working with databases; our database is considered incomplete if we do not have all four.


 #### 8. When working with Sequelize, how do we make changes on a table or database level? Give a code example along with your answer.

 We could use create or build (create is permanent)
 ---
 let connection = require('./models/sequelize-connection')

 let Flower = require('./models/flower')

 let forgetmenot = Flower.create({
   name: 'Forget-Me-Not',
   color: 'Light blue',
   location: 'forests'
 })


 #### 9. During the review we came across the idea of primitives types in Javascript but didn't really get to go into detail about them, other than the fact that they sometimes behave differently than objects and arrays. Do 5 min of research about primitives and record your findings here:

 //Googled Answer
Five different types: undefined, boolean, string, number, null.
Primitives have no properties.

#### 10. Friday's lesson was difficult because Sequelize updated its syntax. What did you think about this problem, and how might you deal with breaking updates like this in the future?

//Your Answer
I found it to be somewhat frustrating, but I know now how important it is to simply stay up to date with these things. The solution I can think of is to follow some blogs/podcasts that talk about things like this.
