### React Implementation and Concepts


#### Resources

- **React Team core Notes**  
  https://github.com/reactjs/core-notes  
  Notes from the React team's weekly-ish meetings
  

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
  
- **React Elements vs React Components**  
  https://tylermcginnis.com/react-elements-vs-react-components/  
  An explanation of how elements represent DOM nodes, what `createElement` does, and how components and rendering relate to elements
  
  
#### JSX and Events

- **How the JSX Transform Works**  
  https://jaketrent.com/post/how-jsx-transform-works/  
  A helpful explanation of how JSX tags are transformed into React elements, with example snippets

- **JSX In Depth - an interactive tutorial**  
  http://blog.klipse.tech/javascript/2016/12/14/jsx.html  
  An interactive version of the "JSX in Depth" tutorial from the React docs
  
- **Events in React**  
  https://www.kirupa.com/react/events_in_react.htm  
  An introduction to React's event handling system, including useful tips and some gotchas
  
- **React events in depth**  
  https://www.youtube.com/watch?v=dRo_egw7tBc  
  A video chat between Kent C Dodds, Dan Abramov, and Ben Alpert, discussing how events work in React
  

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
  
- **Write Your Own React.js!**  
  https://medium.com/@calebmer/write-your-own-react-js-776dbef98b8  
  Some thoughts on why and how you might want to try writing your own React-alike, and some of the tradeoffs involved in writing something like React.
  
- **Didact: Learning how React works by building it from scratch**  
  https://engineering.hexacta.com/didact-learning-how-react-works-by-building-it-from-scratch-51007984e5c5  
  https://engineering.hexacta.com/didact-element-creation-and-jsx-d05171c55c56  
  https://engineering.hexacta.com/didact-rendering-dom-elements-91c9aa08323b  
  https://engineering.hexacta.com/didact-instances-reconciliation-and-virtual-dom-9316d650f1d0  
  https://engineering.hexacta.com/didact-components-and-state-53ab4c900e37  
  An ongoing series of articles showing how to build parts of React's API and implementation, like `createElement`.
  
- **deact: React under the hood**  
  https://github.com/lukebelliveau/deact  
  A repository for learning about how React works internally.  Has a link to a slide set that explains the concepts, and has branches for the various lessons.
  
  
  
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
  
- **React Internals: Through the Lens of a Renderer**  
  https://www.youtube.com/watch?v=VVxQAoNK_XQ  
  A talk exploring how a React renderer works, and how to implement a tiny renderer
  
- **Making custom renderers for React**  
  http://goshakkk.name/react-custom-renderers/  
  Describes techniques for building custom rendering components that bridge between normal rendering and something like a canvas
  
- **The Inner Workings of Virtual DOM**  
  https://medium.com/@rajaraodv/the-inner-workings-of-virtual-dom-666ee7ad47cf  
  An in-depth article that digs into how a Virtual DOM implementation works, using Preact as an example.  Includes some detailed flowcharts of their behavior.
  
- **React Internals**  
  https://zackargyle.github.io/react-internals-slides/#/  
  An informative slideshow that walks through many aspects of React's implementation and behavior, including rendering, reconciliation, setState, Fiber, and more, with helpful visualizations.
  
 - **Preact Internals**  
   https://medium.com/@asolove/preact-internals-1-the-easy-parts-3a081fa36205  
   https://medium.com/@asolove/preact-internals-2-the-component-model-36a05e32957b  
   A series of posts that walk through the Preact codebase and explain its implementation, as well as the component model.
   
- **The React Source Code: A Beginner's Walkthrough**  
  https://medium.com/@ericchurchill/the-react-source-code-a-beginners-walkthrough-i-7240e86f3030  
  A long, detailed walkthrough of large parts of the React codebase
  
- **Preact: Into the void 0**  
  https://youtu.be/LY6y3HbDVmg  
  A talk by Jason Miller, author of Preact, covering some of the core implementation concepts behind Preact (and other virtual DOM/component libraries), as well as some important aspects for DOM manipulation performance.
  
- **Under the hood: ReactJS**  
  https://bogdan-lyashenko.github.io/Under-the-hood-ReactJS/  
  An incredibly detailed walkthrough of React's entire codebase and execution flow, with many diagrams and flowcharts illustrating things.  Very impressive. 
   

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
  
- **Why, What, and How of React Fiber**  
  https://www.youtube.com/watch?v=crM1iRVGpGQ  
  Kent C Dodds interviews Dan Abramov and Andrew Clark about what React Fiber is intended to do, how it works, and what it means for the React codebase.
  
- **ReactConf 2017: A Cartoon Intro to Fiber**  
  https://www.youtube.com/playlist?list=PLb0IAmt7-GS3fZ46IGFirdqKTIxlws7e0  
  A fantastic presentation by Lin Clark, explaining the core concepts and implementation of React Fiber with cartoon illustrations.
  
- **React Fiber: A Closer Look at the New Engine of React**  
  https://www.infoq.com/news/2017/05/react-fiber-closer-look  
  A useful summary of the goals and implementation approach for the new React Fiber algorithm