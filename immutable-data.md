### Immutable Data


#### Basic Concepts

- **Pros and Cons of Using Immutability With React**  
  http://reactkungfu.com/2015/08/pros-and-cons-of-using-immutability-with-react-js/  
  Excellent description of what immutability is, how to use use these concepts with React, and pros and cons of managing data immutably.  While the title refers to React, most of the writing just deals with plain Javascript concepts.

- **Javascript and Immutability**  
  http://t4d.io/javascript-and-immutability/  
  A description of how to properly immutably update objects and arrays using functions like assign and slice

- **Immutable Javascript using ES6 and Beyond**  
  http://wecodetheweb.com/2016/02/12/immutable-javascript-using-es6-and-beyond/  
  Describes ways to handle data immutably using "just" built-in Javascript functions, particularly ES6 syntax

- **Pure javascript immutable arrays**  
  http://vincent.billey.me/pure-javascript-immutable-array  
  A reminder to avoid the built-in Array functions that mutate the array, with snippets demonstrating alernative immutable functionality

- **Javascript Array: slice vs splice**  
  https://ariya.io/2014/02/javascript-array-slice-vs-splice  
  A reminder that "slice" and "splice" are different functions with different behavior

- **Immutable Data from Scratch**  
  https://ryanfunduk.com/articles/immutable-data-from-scratch/  
  Demonstrates building up an immutable update utility library similar to React's Update Addons

- **Immutable Objects with `Object.freeze`**  
  http://adripofjavascript.com/blog/drips/immutable-objects-with-object-freeze.html  
  A quick look at how to use `Object.freeze` to enforce immutability.

- **Immutability in Javascript**  
  http://www.sitepoint.com/immutability-javascript/  
  Describes a couple basic concepts of immutable data in Javascript, and how the Immutable.js library can be used for those concepts.

- **Immutable Data Structures and Javascript**  
  http://jlongster.com/Using-Immutable-Data-Structures-in-JavaScript  
  In-depth article covering the value of immutable data, and two common JS libraries
  
- **Immutability is Not Enough**  
  https://codewords.recurse.com/issues/six/immutability-is-not-enough  
  A look at how using an immutable data approach doesn't magically prevent all bugs.



#### Immutability and React

- **Immutability in React**  
  http://www.sitepoint.com/immutability-react/  
  Covers the reasons and basic concepts of using immutable data with React
  
- **Why Should I Care About Immutable Data In React?**  
  http://www.bennadel.com/blog/2903-why-should-i-care-about-immutable-data-in-reactjs.htm  
  Describes the major benefits of using immutable data in React, with a demo

- **React: A (very brief) talk about immutability**  
  https://medium.com/pro-react/a-brief-talk-about-immutability-and-react-s-helpers-70919ab8ae7c
  Talks about the issues with mutation, and some ways to update immutably



#### Immutable Data Libraries

- **List of immutable libraries**  
  https://gist.github.com/jlongster/bce43d9be633da55053f  
  A follow-up to James Longster's article, with pointers to numerous immutable data libraries
  
- **Redux Ecosystem Links: Immutable Data**  
  https://github.com/markerikson/redux-ecosystem-links/blob/master/immutable-data.md  
  A large list of libraries for managing immutable data in Javascript.  Some of them are Redux-specific, but also includes many general-purpose immutable data libraries as well.
  
- **Painless Immutability**  
  https://guigrpa.github.io/2016/06/16/painless-immutability/  
  A somewhat opinionated article from the author of a new immutable data library comparing different options, but still well-written and informative about the pros and cons of each.
  
- **Immutable.js**  
  http://seanamarasinghe.com/developer/immutable-js/  
  An introduction to the API and use cases for Immutable.js
  
- **How to use Immutable.js Records with React and Redux**  
  https://medium.com/azendoo-team/immutable-record-react-redux-99f389ed676  
  Examples for using Immutable.js records for clarity and consistency of data management
