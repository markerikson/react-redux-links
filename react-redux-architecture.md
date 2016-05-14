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
  
- **React In-Depth: The React Life Cycle**  
  https://developmentarc.gitbooks.io/react-indepth/content/  
  A deep dive into the lifecycle methods, and various techniques for using them.


#### React Component Management

- **Presentational and Container Components**  
  https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0
  Dan Abramov's foundational article on classifying components based on intent and behavior.  A must-read for anyone using React.
  
- **Mixins Are Dead.  Long Live Composition**  
  https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750
  A look at some of the issues with using mixins, and reasons why higher-order components are (usually) an improvement.
  
- **React Components, Elements, and Instances**  
  https://medium.com/@dan_abramov/react-components-elements-and-instances-90800811f8ca
  Clarifies the differences between these related terms.
  
- **How to use Classes and Sleep at Night**  
  https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4
  Some pragmatic opinions on when and how to use the ES6 "class" keyword, particularly in relation to React components.
  
- **Higher Order Components: Theory and Practice**  
  http://engineering.blogfoster.com/higher-order-components-theory-and-practice/  
  Gives practical use cases for HOCs, such as authentication, routing, and data management, with samples.

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
  
  
#### Project File Structure

- **Organizing Large React Applications**  
  http://engineering.kapost.com/2016/01/organizing-large-react-applications/  
  Describes "File-Type First", "Feature First / Pods" approaches, as well as other related structure issues.
  
- **Four Strategies for Organizing Code**  
  https://medium.com/@msandin/strategies-for-organizing-code-2c9d690b6f33
  Describes "by component", "by toolbox", "by layer", and "by kind" approaches.

- **Rules for Structuring (Redux) Applications**  
  http://jaysoo.ca/2016/02/28/organizing-redux-application/  
  Gives several useful rules for structuring code, with examples.
  
- **A Better File Structure for React/Redux Applications**  
  http://marmelab.com/blog/2015/12/17/react-directory-structure.html  
  Suggests a domain-based structure, with tests kept alongside the code they relate to.
  
- **Route-Based Folder Structure**  
  https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346  
  Ryan Florence, an author of React Router, gives his suggested file structure.
  
- **How to Better Organize Your React Applications?**  
  https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1
  Another feature-style approach, describing things in terms of "components", "scenes", and "services".


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
  
