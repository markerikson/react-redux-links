### Using React with ES6


#### React Component Definitions

- **Which React Component Class Syntax Should I Use?**  
  http://reactkungfu.com/2015/07/what-react-component-class-syntax-should-i-use/  
  Compares the standard React.createClass() syntax vs ES6 React.Component class syntax
  
- **Coding with React like a Game Developer**  
  https://medium.com/@PhilPlckthun/coding-with-react-like-a-game-developer-e39ffaed1643  
  Demonstrates React usage with ES5 vs ES6, plus some other topics
  
- **The React Quick Start Guide: ES6 Edition**  
  http://www.jackcallister.com/2015/08/30/the-react-quick-start-guide-es6-edition.html  
  An ES6 version of the other guide listed earlier
  
- **Digging Into React: Choosing Component Styles**  
  http://benmccormick.org/2016/05/02/digging-into-react-choosing-component-styles/  
  A comparison of the three ways to define a React component.  Good descriptions, and links to some other related discussions.
  
- **Refactoring React Components to ES6 Classes**  
  http://www.newmediacampaigns.com/blog/refactoring-react-components-to-es6-classes  
  Walks through the steps needed to convert an older-style `React.createClass()` component to use the newer ES6 class syntax instead.
  

#### Methods and Instance Binding

- **React and ES6 - Binding Approaches**  
  http://egorsmirnov.me/2015/08/16/react-and-es6-part3.html  
  Various methods of binding "this" in React ES6 classes

- **Why and How to Bind Methods in your React Component Classes**  
  http://reactkungfu.com/2015/07/why-and-how-to-bind-methods-in-your-react-component-classes/  
  A good look at function binding in JS, and how it works with React
  
- **React, ES6, Autobinding, and createClass()**  
  http://blog.andrewray.me/react-es6-autobinding-and-createclass/  
  A useful review of how JS function binding works, and how to handle it in ES6 with React 


#### Method Binding Utilities

- **React-Autobind**  
  https://github.com/cassiozen/React-autobind  
  A useful utility to bind class methods.  A good compromise - makes binding explicit, but removes repetition.

- **react-bind-decorator**  
  https://github.com/zackargyle/react-bind-decorator  
  Another autobinding approach, intended to be fast and performant.
  
- **react-class-binder**  
  https://github.com/Klathmon/react-class-binder  
  https://www.reddit.com/r/reactjs/comments/4p0ytu/i_made_a_small_package_to_easily_autobind_this_in/  
  Automatically bind methods defined in a React component using the ES2015 class syntax (similar to how React.createClass works).  The Reddit comments have discussion on some differences between the various libs that implement autobinding.
