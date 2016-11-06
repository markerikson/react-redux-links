### React State Management

#### State Types and Data Flow

- **The 5 Types of React Application State**  
  http://jamesknelson.com/5-types-react-application-state/  
  Describes different categories of state: data, communication, control, session, and location
  
- **"M" and "C" in "MVC"**  
  https://www.youtube.com/watch?v=fUpkYixd03k
  https://github.com/jamesknelson/m-and-c-in-mvc-talk  
  James K. Nelson's talk at ReactNext, talking about the multiple categories of state and how controller components can manage them.
  
- **Exploring React's State Propagation**  
  https://www.sitepoint.com/exploring-reacts-state-propagation/  
  Discusses data flow in React, the difference between `state` and `props`, and the usefulness of immutability
  
- **Redux'ing without Redux**  
  https://medium.com/@m.mollaverdi/reduxing-without-redux-75dbd5c05336  
  Thoughts on how some of Redux's goodness can perhaps be utilised without actually using Redux.
  
- **Dataflow through React**  
  https://jurassix.gitbooks.io/dataflow-through-react/content/index.html  
  An online book that covers a number of topics on React components and data flow.
  
- **React Anti-Patterns: Props in Initial State**  
  https://medium.com/@justintulk/react-anti-patterns-props-in-initial-state-28687846cc2e  
  Discussion of why using props to initialize a component's state may or may not be a bad idea.
  

  
- **Best Practices for Component State in React**  
  http://brewhouse.io/blog/2015/03/24/best-practices-for-component-state-in-reactjs.html  
  Some excellent suggestions and approaches for state handling and structure.
  
- **A Visual Guide to State in React**  
  https://daveceddia.com/visual-guide-to-state-in-react/  
  Describes what "state" is, what kinds of data should be included into React state, and how state flow relates to component updates.


#### Using `setState`

- **React component state cheatsheet**  
  https://twitter.com/dan_abramov/status/749710501916139520  
  Dan Abramov pseudocodes his guidelines for when to put something into component state

- **Where to Hold React Component Data: state, store, static, and this**  
  https://medium.freecodecamp.com/where-do-i-belong-a-guide-to-saving-react-component-data-in-state-store-static-and-this-c49b335e2a00  
  A great summary of different places to store state, and when and why you should use each.
  
- **How to handle state in React: The Missing FAQ**  
  https://medium.com/react-ecosystem/how-to-handle-state-in-react-6f2d3cd73a0c  
  An article that dispels misunderstandings and answers common questions about how to handle state in React.
  
- **Finding `state`'s place with React and Redux**  
  https://medium.com/@adamrackis/finding-state-s-place-with-react-and-redux-e9a586630172  
  A look at when and how using React component state may be useful, even when using Redux for primary app state
  
- **A case for setState**  
  https://medium.com/@zackargyle/a-case-for-setstate-1f1c47cd3f73  
  An article arguing that React component state still has a number of uses.