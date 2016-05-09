### React/Redux Architecture


#### React Component Lifecycle

- **React Docs: Component Specs and Lifecycle**  
  https://facebook.github.io/react/docs/component-specs.html  
  The official React docs page on component lifecycle
  
- **Understanding the React Component Lifecycle**  
  http://busypeoples.github.io/post/react-component-lifecycle/  
  A good look at which lifecycle methods run in which situations, as well as the signatures of each method.
  
- **Dissecting React Lifecycle Methods**  
  https://medium.com/@fay_jai/dissecting-reactjs-lifecycle-methods-be4fdea11c6d
  Breaks the lifecycle methods down into "mount/unmount" and "update" categories, and describes the purpose and use of each.
  
- **The React Component Lifecycle**  
  https://www.kirupa.com/react/component_lifecycle.htm  
  Another useful description of the order and purpose of the lifecycle methods.


#### React Component Management

- **8 no-Flux strategies for React component communication**  
  http://andrewhfarmer.com/component-communication/  
  Very helpful list of ways to have React components communicate back and forth

- **How to communicate between React components**  
  http://ctheu.com/2015/02/12/how-to-communicate-between-react-components/  
  Another good list of component communication strategies
  
  
  
#### React and AJAX

- **React AJAX Best Practices**  
  http://andrewhfarmer.com/react-ajax-best-practices/  
  Covers four ways to approach managing queries and data fetching.

- **AJAX/HTTP Library Comparison**  
  http://andrewhfarmer.com/ajax-libraries/  
  A useful overview of the most popular AJAX libraries, including platform support and feature comparisons.


#### Redux Architecture


- **Reddit: "Redux - Reducer composition without slicing state?"**  
  https://www.reddit.com/r/javascript/comments/42ey9e/redux_reducer_composition_without_slicing_state/  
  Some very informative discussion on how to organize reducers and actions.
  
  
- **Wordpress Calypso: Our Approach to Data**  
  https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md  
  The team behind Wordpress's new admin panel looks at their migration from emitters to Flux to Redux, and describes how they organize their state tree, use selectors to extract state, run queries with components, and persist their store state through refreshes.

- **Redux and the Elm Architecture**  
  http://salsita.github.io/redux-elm/  
  Redux lacks built-in abstractions for real-world, maintainable, scalable applications. In particular, it is difficult to create and distributed encapsulated, reusable components.  The Elm Architecture clearly addresses some important areas where Redux alone is lacking.
  
