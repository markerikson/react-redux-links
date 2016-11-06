### React Implementation and Concepts


#### Core Concepts

- **React Components, Elements, and Instances**  
  https://medium.com/@dan_abramov/react-components-elements-and-instances-90800811f8ca  
  Clarifies the differences between these related terms.
  
- **React Elements vs React Components vs Component Backing Instances**  
  https://medium.com/@fay_jai/react-elements-vs-react-components-vs-component-backing-instances-14d42729f62  
  Another solid comparison of what these terms mean, how React uses them, and how they differ.
  
- **React - Basic Theoretical Concepts**  
  https://github.com/reactjs/react-basic  
  React team member Seb Markbage dives into his mental model for how React works.  (Note: after the first few paragraphs, _not_ "basic" at all.  Definitely an involved read, but informative.)
  
- **Our First 50,000 Stars**  
  https://facebook.github.io/react/blog/2016/09/28/our-first-50000-stars.html  
  A post celebrating React's progress, including a history of how React's concepts came together over time
  

#### Miniature React Implementations

- **Building React from Scratch**  
  https://www.youtube.com/watch?v=_MAD4Oly9yg  
  Paul O'Shannessy walks through building a mini React implementation
  
- **Building Your Own React Clone in Five Easy Steps**  
  http://blog.javascripting.com/2016/10/05/building-your-own-react-clone-in-five-easy-steps/  
  Builds a mini-React implementation to illustrate the basic principles

- **Reverse Engineering React**  
  https://vimeo.com/album/3930691  
  A video series covering the implementation of an alternative/miniature version of React called "Reaction".  Note that it doesn't look at React itself, but does cover all the equivalent concepts in a simpler implementation.
  
- **Tiny React Reimplementation**  
  http://jsbin.com/qiguyibolu/1/edit?js,output  
  A _very_ tiny (100 lines) implementation of React's basic algorithm
  
- **Tiny React Renderer**  
  https://github.com/iamdustan/tiny-react-renderer  
  A heavily commented learning implementation of a bare basic React renderer
  
- **How to write your own Virtual DOM**  
  https://medium.com/@deathmood/how-to-write-your-own-virtual-dom-ee74acc13060  
  https://medium.com/@deathmood/write-your-virtual-dom-2-props-events-a957608f5c76  
  A series of articles that build up a small Virtual DOM system from scratch.
  
  
#### Implementation and Internals

- **React.js Reconciliation**  
  https://www.infoq.com/presentations/react-reconciliation  
  A video presentation digging into how React's reconciliation algorithm determines how to properly update nodes based on render output.
 
- **React Source Code Annotations**  
  https://annot.io/github.com/facebook/react  
  Crowdsourced annotations and descriptions for files in the React codebase

- **ReactJS: Under the Hood**  
  https://www.youtube.com/watch?v=xsKYAa1ZXpQ  
  A talk digging into React's internal concepts and implementation, including the split between the core library and the renderers.
  
- **React Implementation Notes**  
  https://facebook.github.io/react/contributing/implementation-notes.html  
  An in-depth explanation of how React's current internal algorithms work
  
- **Dive Into React Codebase: Transactions**  
  http://reactkungfu.com/2015/12/dive-into-react-codebase-transactions/  
  A deep dive into the implementation of React's internal "transactions" concept
 
- **React Events In Depth**  
  https://www.youtube.com/watch?v=dRo_egw7tBc  
  A Javascript Air episode focused on how React's Events system works, with React team members Dan Abramov and Ben Alpert

- **Dive Into React Codebase: Handling state changes**  
  http://reactkungfu.com/2016/03/dive-into-react-codebase-handling-state-changes/  
  A deep dive into how React implements component state and `setState()`
  
- **On the Async Nature of `setState` in React**  
  http://thereignn.ghost.io/on-the-async-nature-of-setstate-in-react/  
  Digs into the behavior of `setState`, and whether it is actually always async or not.  Some decent info, although the final section does make some strange statements.
  
- **setState() State Mutation Operator May Be Synchronous in ReactJS**  
  https://www.bennadel.com/blog/2893-setstate-state-mutation-operation-may-be-synchronous-in-reactjs.htm  
  Digs into the behavior of React's setState method, and discusses when it may be synchronous vs asynchronous
  

#### React Fiber
  
- **React Fiber Architecture**  
  https://github.com/acdlite/react-fiber-architecture  
  A description of React's new core algorithm, React Fiber
  
- **What's Next for React - React Fiber**  
  https://www.youtube.com/watch?v=aV1271hd9ew  
  Andrew Clark describes the concepts, implementation, and potential benefits of the in-progress React Fiber internal algorithm reimplementation.
  
- **React Fiber Resources**  
  https://github.com/koba04/react-fiber-resources  
  Links and info on the new React Fiber algorithm