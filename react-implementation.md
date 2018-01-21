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
  https://engineering.hexacta.com/didact-fiber-incremental-reconciliation-b2fe028dcaec  
  An ongoing series of articles showing how to build parts of React's API and implementation, like `createElement`, `setState`, and the "Fiber" reconciliation approach.
  
- **deact: React under the hood**  
  https://github.com/lukebelliveau/deact  
  A repository for learning about how React works internally.  Has a link to a slide set that explains the concepts, and has branches for the various lessons.
  
- **React Internals**  
  http://www.mattgreer.org/articles/react-internals-part-one-basic-rendering/  
  http://www.mattgreer.org/articles/react-internals-part-two-componentWillMount-and-componentDidMount/  
  http://www.mattgreer.org/articles/react-internals-part-three-basic-updating/  
  http://www.mattgreer.org/articles/react-internals-part-four-setState/  
  A 5-part series that will recreate React from the ground up, illustrating how it works along the way.
  
- **Making a custom React renderer**  
  https://github.com/nitin42/Making-a-custom-React-renderer  
  A 4-part that teaches how to build a React reconciler for React 16 that renders to a Word document
  
- **Extending React**  
  https://www.javascriptjanuary.com/blog/extending-react  
  Walks through building a very simplified mini React clone, including `createElement`, rendering to the DOM, and `setState` updates
  
  
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
  
- **Preact Internals**  
  https://medium.com/@asolove/preact-internals-1-the-easy-parts-3a081fa36205  
  https://medium.com/@asolove/preact-internals-2-the-component-model-36a05e32957b  
  https://medium.com/@asolove/preact-internals-3-some-fiddly-little-bits-f353b1ad7abc  
  A 3-part series that dives into the implementation and concepts of the Preact library codebase.
  
- **An Interview with the React Team About Wordpress and Project Gutenberg**  
  https://wpcouple.com/interview-react-team-facebook-wordpress-gutenberg/  
  A Wordpress community site interviews Dan Abramov, Andrew Clark, and Sophie Alpert about a variety of topics, including how they prioritize features, how React is tested, dealing with breaking changes, downsides of React, and aspects of Wordpress using React for its "Project Gutenberg" tool.
  
- **The React Story: How Facebook's Instagram Acquisition Led to the Open Sourcing of React**  
  https://stackshare.io/posts/the-react-story  
  An extensive podcast interview with Pete Hunt, former React team member, recounting his early work at Facebook, how he began using React at Instagram, how that led to the growth of React inside Facebook, and how the decision to open-source React happened.  Page includes a complete transcript of the discussion.
   
- **How exactly does React handle events?**  
  https://levelup.gitconnected.com/how-exactly-does-react-handles-events-71e8b5e359f2  
  A detailed look at how React's internal event handling works, including normalization of events, SyntheticEvent objects, and more.
  
- **A look inside React Fiber**  
  http://makersden.io/blog/look-inside-fiber/  
  Traces through the source code for React 16 / React Fiber, starting with the main `render()` function and diving down from there through the system.
  
- **Understanding the React Source Code**  
  https://hackernoon.com/understanding-the-react-source-code-initial-rendering-simple-component-i-80263fe46cf1  
  https://hackernoon.com/understanding-the-react-source-code-initial-rendering-simple-component-ii-79e7e8bed56c  
  https://hackernoon.com/understanding-the-react-source-code-initial-rendering-simple-component-iii-69c2711c5f33  
  https://hackernoon.com/understanding-the-react-source-code-iv-e3c4b66da12c  
  https://hackernoon.com/understanding-the-react-source-code-v-812d69a79fb9  
  Walks through the critical path of React 15's source code, tracing how a simple component gets rendered.
  

#### React Fiber
  
- **React v16.0**  
  https://reactjs.org/blog/2017/09/26/react-v16.0.html  
  The React team officially announces the release of React 16 and describes the new features, including returning arrays, error handling, better server-side rendering, and more.
  
- **React 16: A look inside an API-compatible rewrite**  
  https://code.facebook.com/posts/1716776591680069/react-16-a-look-inside-an-api-compatible-rewrite-of-our-frontend-ui-library/  
  The React team describes how they handled building and testing React 16 to be backwards compatible with existing code.
  
- **ReactConf 2017: A Cartoon Intro to Fiber**  
  https://youtu.be/ZCuYPiUIONs  
  A fantastic presentation by Lin Clark, explaining the core concepts and implementation of React Fiber with cartoon illustrations.
  
- **Roadmap for React - Fiber and Beyond**  
  https://www.youtube.com/watch?v=QW5TE4vrklU  
  A keynote by Andrew Clark, describing the ideas behind React Fiber and the benefits it will give.
  
- **React Fiber: A Closer Look at the New Engine of React**  
  https://www.infoq.com/news/2017/05/react-fiber-closer-look  
  A useful summary of the goals and implementation approach for the new React Fiber algorithm
  
- **Top Resources to Explore React Fiber**  
  https://hackernoon.com/top-resources-to-explore-react-fiber-9a2b19114520  
  A helpful list of links to further articles and resources for learning about React Fiber
  
- **React Fiber for the rest of us**  
  http://www.benmvp.com/slides/2017/reactboston/fiber.html#/  
  Slides from Ben Ilegbodu's ReactBoston presentation, which summarize the changes in React 16.
  
- **What's new in React 16?**
  https://www.robinwieruch.de/what-is-new-in-react-16/  
  A very useful look at the new user-facing features in React 16, with code examples.
  
- **Rethinking with React 16**  
  https://www.javascriptjanuary.com/blog/rethinking-with-react-16  
  An informative overview of the major changes in React 16, including the goals of the "React Fiber" rewrite, Fragments, Error Boundaries, server-side rendering improvements, and more.
  
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
  
- **What is React Fiber?**  
  https://giamir.com/what-is-react-fiber  
  An overview of the React Fiber rewrite, and how React's reconciler has been rewritten to improve performance and make rendering more flexible.