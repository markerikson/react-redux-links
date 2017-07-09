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
  
- **Javascript Array Methods: Mutating vs Non-Mutating**  
  http://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/  
  An overview of how to accomplish add/remove/replace operations on JS arrays, comparing mutable vs immutable approaches to each.
  
- **Redux Docs: Immutable Update Patterns**  
  http://redux.js.org/docs/recipes/reducers/ImmutableUpdatePatterns.html  
  Some useful examples for correctly updating data immutably, including nested objects, inserting and removing items in arrays, and updating items in arrays, as well as some common mistakes that occur.  Important to know when using Redux, but the info is not Redux-specific.

- **Immutably setting a value in a JS array (or how an array is also an object)**  
  https://medium.com/@giltayar/immutably-setting-a-value-in-a-js-array-or-how-an-array-is-also-an-object-55337f4d6702  
  An example of how `Object.assign` can be used to immutably update an array
  
- **ReactCasts #9: Immutability in Javascript**  
  https://www.youtube.com/watch?v=4LzcQyZ9JOU  
  A screencast discussing why immutability is important and its benefits.  Compares Javascript's lack of built-in immutability with other languages, and shows how to do immutable operations in plain Javascript.

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

- **Comparing and Modifying Objects in React**  
  https://blog.komand.com/object-comparison-in-react-js-components  
  Some examples of comparing objects inside of React's lifecycle methods, and how to update them properly.
  
- **Handling State in React: Four Immutable Approaches to Consider**  
  https://medium.com/@housecor/handling-state-in-react-four-immutable-approaches-to-consider-d1f5c00249d5  
  A summary of four different ways to update state immutably
  

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
  
- **Immutable.js: An Introduction with examples written for humans**  
  http://untangled.io/immutable-js-an-introduction-with-examples-written-for-humans/  
  A detailed series of tutorials explaining how to use Immutable.js's API
  
- **Seamless-Immutable: An Alternative to Immutable.js**  
  https://medium.com/@ckoster22/seamless-immutable-an-alternative-to-immutablejs-12795d6bf577  
  Examples of how to use the Seamless-Immutable library, and how it compares to Immutable.js
  
- **Using Ramda's `evolve` in Redux reducers to create new state**  
  https://www.jernejsila.com/2017/02/25/using-ramda-evolve-redux-reducers-creating-new-state/  
  Some quick examples of how Ramda's API can be used for applying immutable data updates
  
- **How to Use Immutable.js in a React Redux Application**  
  https://codebrahma.com/how-to-use-immutable-js-in-a-react-redux-application/  
  Answers to six common questions about why and how to use Immutable.js in a React/Redux app, including whether to keep everything as Immutable.js objects, whether to use it inside of components, and potential benefits of using Immutable.js
  
- **Immutable Deep State Updates in React with Ramda.js**  
  https://vanslaars.io/post/setstate-lenses/  
  Some excellent examples of how to use Ramda's "lens" functions to define immutable state update logic
  
- **Why I Don't Use Immutable.js with Redux**  
  https://medium.com/front-end-hacking/why-i-dont-use-immutable-js-with-redux-db05004f436  
  Thoughts on the pros and cons of using Immutable.js in a Redux app
  
- **Should I use Immutable.js with Redux?**  
  https://medium.com/@fastphrase/should-i-use-immutablejs-with-redux-58f88d6fd81e  
  A detailed list of pros and cons for using Immutable.js in a Redux app

- **Practical Guide to using Immutable.js with Redux and React**  
  https://medium.com/@fastphrase/practical-guide-to-using-immutablejs-with-redux-and-react-c5fd9c99c6b2  
  A follow-up to the previous article, showing how to correctly set up and use Immutable.js with Redux
  
- **Qim: Select from your Immutable JavaScript Cake and Update It Symmetrically Too**  
  https://zapier.com/engineering/qim-immutable-javascript/  
  An in-depth look at a new lens-style immutable update utility called Qim, including what problems it helps solve and how to use it.
  
- **Lenses with Immutable.js**  
  https://medium.com/@drboolean/lenses-with-immutable-js-9bda85674780  
  Discusses how "lenses" can be used to dig into data structures and update them in an immutable way, and how to define lenses that work on Immutable.js objects.
  
