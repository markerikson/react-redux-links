### React Performance and Optimization

My [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) list includes a number of useful tools for visualizing React component updates, in the [Devtools > Component Update Monitoring](https://github.com/markerikson/redux-ecosystem-links/blob/master/devtools.md#component-update-monitoring) section.



- **React Docs: Performance**  
  https://facebook.github.io/react/docs/advanced-performance.html  
  https://facebook.github.io/react/docs/perf.html  
  The React doc pages on performance.  Describes the core concepts, including shouldComponentUpdate, using immutable data, and the Performance API for benchmarking.
  
- **Performance Engineering with React**  
  http://benchling.engineering/performance-engineering-with-react/  
  http://benchling.engineering/deep-dive-react-perf-debugging/  
  A 2-part series on React performance.  Excellent information.  Goes in-depth on use of the Perf API, shouldComponentUpdate, shallow equality, and how to properly profile components.  Highly recommended.
  
- **Respectable React Components**  
  http://kelle.co/react-perf-slides/  
  A slideshow that walks through the core concepts of managing good React performance.
  
- **Building Efficient UI with React and Redux**  
  https://www.toptal.com/react/react-redux-and-immutablejs  
  Builds a simple app using React, Redux, and Immutable.js, and looks at some of the most common misuses of React and how to avoid them.
  
- **Optimizing React Performance using keys, component lifecycle, and performance tools**  
  http://jaero.space/blog/react-performance-1  
  http://jaero.space/blog/react-performance-2  
  Another pretty good in-depth look at performance, with a number of useful illustrations.  Only downside is that some of the examples follow bad practice by directly mutating state, but the performance information is solid.
  
- **shouldComponentUpdate Will Short-Circuit an Entire Subtree of Components in React**  
  http://www.bennadel.com/blog/2904-shouldcomponentupdate-will-short-circuit-an-entire-subtree-of-components-in-reactjs.htm  
  A reminder that SCU skips a component's children as well as that component, with a demo.
  
- **Index as a Key is an Anti-Pattern**  
  https://medium.com/@robinpokorny/index-as-a-key-is-an-anti-pattern-e0349aece318  
  A reminder that unique keys are the best idea for arrays of components.
  
- **React.js pure render performance anti-pattern**  
  https://medium.com/@esamatti/react-js-pure-render-performance-anti-pattern-fb88c101332f  
  Looks at common ways that you might accidentally stop pure rendering from doing its job, such as passing in new object references or creating new functions as props.
  
- **How to Make Your React Apps 15x Faster**  
  https://reactjsnews.com/how-to-make-your-react-apps-10x-faster  
  A couple quick tips: using NODE_ENV=production, and Babel's React constant/inline transformations
  
- **Optimising React rendering**  
  https://medium.com/@lavrton/how-to-optimise-rendering-of-a-set-of-elements-in-react-ad01f5b161ae  
  Another couple quick tips: only updating changed elements, and making children smarter
  
  
- **High Performance Redux**  
  http://somebody32.github.io/high-performance-redux/  
  A detailed HTML slideshow that digs down into React Redux to show how `connect()`'s optimizations work, and has interactive demos to show various approaches.  (Note: the code-related slides advance using the down arrow to step through different lines of code - don't miss that info!)
  
- **Performance optimisations for React applications**  
  https://medium.com/@alexandereardon/performance-optimisations-for-react-applications-b453c597b191  
  Covers ways to make update checks fast and easy.  (NOTE: the advice given to "denormalize" data may not be the best approach - see discussion with Dan Abramov in the comments.)
