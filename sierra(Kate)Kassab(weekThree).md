### Javascript Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:

- React was created to be simple, so that even people with minimal code experience could use it and create Single Page Applications (SPAs)
- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework


 #### 2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.


 //Your Answer
Smart components: Describes how things work, provides data and does fetching
Dumb components: Describes how things look

 //Googled Answer
 Smart components: Provide no DOM markup or styles
                   Provide application data, do data fetching
                   Call Flux actions
 Dumb components: Receive only props, providing data and callbacks
                  Rarely have own state, when they do, it’s just UI state
                  Named anything that’s a UI noun

#### 3. Write a simple component that simply prints "I am a dumb component" to the screen. Be sure to include all necessary imports, expots, etc...
import React, { Component } from 'react';

Class Dumb extends Component {
  render () {
    return (
      <h1> I am a dumb component </h1>
      );
  }
}


#### 4. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?


 //Your Answer
 When we use "yarn add..."it adds dependencies and updates the package.json file.


 //Googled Answer
 n/a


#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    import React, { Component } from 'react';

    class Recipes extends Component {
      constructor(props){
        super(props)
        this.state = {
          recipes:
            {name: 'Meatballs'},
            {name: 'Mac & Cheese'}

        }
      }

      render() {

        return (

          let recipes = this.state.recipes.map(function(recipe){
            return(
              <li key={recipe.name}>{this.state.name}</li>
            )
          })

          <ul>
            <li>{this.state.recipes}</li>
          </ul>
        );
      }
    }

    export default Recipes;

#### 6. Name three input types. (NOTE: text is the default type - so it doesn't count in this case)

 //Your Answer
Three input types include submit, forms, number


 #### 7. How would you explain state to a friend who doesn't know code?

 //Your Answer
 State is the status of your object--in a sense. And the behavior of your object can change depending on what you need it to accomplish.


 //Googled Answer
n/a

 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
State is set inside of a component. You should never edit the state directly (that's what setState is for)
Props is what is simply being passed. It is a component's config/options.

 #### 9. Name three benefits of testing and TDD:
  //Your Answer
  Less bugs, better code, it can help your job hunt because employers will appreciate the extra effort.


 //Googled Answer
confidence when refactoring


#### 10. List two helpful testing matchers and two helpful enzyme simulators that we can use when writing our tests:

 //Your Answer
Jasmine, Jest
Event/Args
