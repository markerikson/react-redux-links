### React Performance and Optimization


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