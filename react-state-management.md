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
  
- **ReactJS: Props vs State**  
  http://lucybain.com/blog/2016/react-state-vs-pros/  
  Explains that "props" are data passed in to a component, while "state" is data managed inside a component.
  
- **React state management patterns**  
  http://vijayt.com/post/react-state-management-patterns/  
  Useful summaries of some common patterns for managing state (encapsulated vs uni-directional flow, single store or multiple stores, shared state between components).
  
- **Watch Out for Undefined State**  
  https://daveceddia.com/watch-out-for-undefined-state/  
  Discusses the common mistake of making data requests and not having data fields initialized for use in the initial render, and looks at several ways to handle the issue.
  
- **How to Work with and Manipulate State in React**  
  https://www.sitepoint.com/work-with-and-manipulate-state-in-react/  
  Covers how to access and update state in components, the difference between state and props, and working with stateless components.
  
- **Lowest Common Ancestor**  
  https://blog.embermap.com/lowest-common-ancestor-fbf5d5313a1  
  An article that discusses the principle of keeping shared state at the "lowest common ancestor" of the components that need it.  Actually talks about Ember, but the concepts are completely applicable to React as well.
  
- **Understanding State and Props in React**  
  https://hackernoon.com/understanding-state-and-props-in-react-94bc09232b9c  
  A helpful explanation of the difference between "props" and "state".
  
- **Local Storage in React**  
  https://www.robinwieruch.de/local-storage-react/  
  Demonstrates how to persist state in React using local storage, how to use it as a cache, and how to make it expire.


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
  
- **Using a function in `setState` instead of an object**  
  https://medium.com/@shopsifter/using-a-function-in-setstate-instead-of-an-object-1f5cfd6e55d1  
  An introduction to a lesser-known feature of `setState`: the ability to pass a callback function to update the state.  Useful for ensuring proper updates.
  
- **"Best kept React secret: declare state changes separately from component classes"**  
  https://twitter.com/dan_abramov/status/824308413559668744  
  Dan Abramov shows some screenshots that demonstrate how to define state update functions outside a component, then pass them to `setState`
  
- **Functional `setState` is the future of React**  
  https://medium.freecodecamp.com/functional-setstate-is-the-future-of-react-374f30401b6b  
  Discusses passing a function to `setState` to perform updates, why that approach is useful, and how that pattern can be used to separate state update logic from component definition
  
- **Does React have a `setState` problem? / `setState() Gate: Navigating Behavior Confusion**  
  https://twitter.com/i/moments/842710066826530816  
  https://medium.com/javascript-scene/setstate-gate-abc10a9b2d82  
  Eric Elliott recently posted a tweet saying that `setState` is bad for learners, and advanced devs have learned to avoid it.  That spawned a large Twitter thread arguing the idea.  Elliott later posted an article explaining his concerns in detail.  Some excellent reading and points to consider all around - the "Moments" link includes a few of the tweets, but the whole thread is worth reading.
  
- **Understanding ReactJS: `setState`**  
  https://medium.com/@baphemot/understanding-reactjs-setstate-a4640451865b  
  Several helpful tips and concepts for understanding how component state and `setState` work, including how to initialize component state, ways to call `setState`, and common errors.
  
- **Stack Overflow: "Do I need to use `setState(function)` overload?"**  
  http://stackoverflow.com/questions/43428456/do-i-need-to-use-setstatefunction-overload-in-this-case/43440790#43440790  
  Dan Abramov gives a great in-depth answer explaining when and why to pass an updater function to `setState` instead of passing an object
  
- **"`setState` doesn't actually care whether you've mutated your data or not"**  
  https://news.ycombinator.com/item?id=14706862  
  A couple comments from myself, talking about how `setState` actually behaves in practice in relation to mutation and immutability.