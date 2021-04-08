# ASSESSMENT 3: Interview Practice Questions

Answer the following questions.

First, without external resources. Challenge yourself to answer from memory as if you were in a job interview.

Then, research the question to expand on your answer. Even if you feel you have answered the question completely, there is always something more to learn. Write your researched answer in your OWN WORDS.


1. What is object destructuring?

  Your answer: Object destructuring allows properties within an object to be assigned into specific variables. 

  Researched answer: Destructuring allows one to assign properties of an array or object to variables using syntax that looks similar to array or object literals. 



2. What are React lifecycle methods? Provide three examples.

  Your answer: The three stages of a react component are mounting, updating, and unmounting. Mounting is when the component is first rendered, updating is if any changes are made, and unmounting is when the component is no longer displayed. Each stage includes built-in methods to make changes to each stage.

  Researched answer: 
  There are multiple built in methods to handle React Lifecycle components. For example, in mounting, the constructor() method is called first. This initiates the initial state and initial values. To update a component one can call getDerivedStateFromProps() method. It sets the state object based on the initial props. To remove a component from the DOM, componentWillUnmoun() handles this function.



3. What is the difference between a class and an object?

  Your answer: A class can define properties for objects as well as it's behavior; essentially a blueprint. While, an object is a part of a class and it's properties must be specifically coded or it will take the attributes of the class.

  Researched answer: A class may describe the contents of the objects that belong to it while an object is an instance of a class. Objects are components of the program; while, a class just specifies behavior for how those instances act.



4. What is the difference between a HTML div and a span?

  Your answer: div is used to wrap large portions of code; while span is used to wrap smaller portions of code. 

  Researched answer: div is a block element, while span is an inline element. div is used to make divisions of content while span is generally used for styling.



5. What is a React Fragment (or <>) and why would you want to use it?

  Your answer: Fragments are used in react as dividers that indicate JSX is being implemented in the render.

  Researched answer: Allows component to return multiple elements and fragments allow programs to have a list of children grouped without adding nodes to the DOM.



6. What does it mean to create a responsive UI? What are three options for creating responsive design?

  Your answer: Responsive UI is when UI elements dynamically change and interact with the user without needing to refresh the entire page. Bootstrap allows tools to build mobile-first responsive websites. React is another way that blends HTML and JSX with re-usability as the focus by rendering components on their own. 


  Researched answer:  Responsive UI is the approach that design and development should respond to the user's behavior and environment based on screen size, platform, and orientation. 


7. What are props in React?

  Your answer: props allow the passage of properties from child to parent in react developments. 

  Researched answer: Allways passed in the contructor of the component via the super() method, props are arguments passed into react components in a uni-directional flow from component to component. 



8. What is `this` in JavaScript?
 
  Your answer: 'this' allows an object or function to be referenced someweher else in React. 

  Researched answer: 'this' refers to an object which is executing a bit of JS code. the keyword is called when calling an object or function to act at that moment. 



9. STRETCH: What is a ternary operator in JavaScript?

  Your answer: ternary operator has a built in if/else statement of true or false. The programmer sets a condition. If it is true it will return one function, but if it is false it will return another one instead. 

  Researched answer: The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark (?), then an expression to execute if the condition is truthy followed by a colon (:), and finally the expression to execute if the condition is falsy. This operator is frequently used as a shortcut for the if statement.



10. STRETCH: What is an anonymous function in JavaScript?

  Your answer: an anonymous function is a function that has been declared without any name or nomenclature. 

  Researched answer: anonymous functions are nameless and are inaccessable after their initial creation. They are often used as arguments of other functions; such as in .sort() to subtract a-b



## Looking Ahead: Terms for Next Week
- Ruby - It is a web application focused programming language. It is object orientented and is used in conjunction with Ruby on Rails. 
- Object oriented programming - javascript and ruby are examples, OOP, focuses on the objects to be manipulated rather than the logice required to manipulate them. 
- RSpec - Ruby testing tool and used in behavior driven development
- Instance variable - in Ruby, instance variables begin with @ and allows objects to store data and attributes.
- Ruby blocks - Ruby blocks are anonymous functions that can be passed into methods. Blocks are enclosed in a do-end statement or curly braces {}. do-end is usually used for blocks that span through multiple lines while {} is used for single line blocks. Blocks can have arguments which should be defined between two pipe | characters.
- Ruby hashes - A Hash is a collection of key-value pairs, similar to an Array, except that indexing is done via arbitrary keys of any object type, not an integer index.
