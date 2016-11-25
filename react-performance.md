### React/Redux Performance and Optimization

My [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) list includes a number of useful tools for visualizing React component updates, in the [Devtools > Component Update Monitoring](https://github.com/markerikson/redux-ecosystem-links/blob/master/devtools.md#component-update-monitoring) section.


#### React Components

- **React Docs: Performance**  
  https://facebook.github.io/react/docs/advanced-performance.html  
  https://facebook.github.io/react/docs/perf.html  
  The React doc pages on performance.  Describes the core concepts, including shouldComponentUpdate, using immutable data, and the Performance API for benchmarking.
  
- **Performance Engineering with React**  
  http://benchling.engineering/performance-engineering-with-react/  
  http://benchling.engineering/deep-dive-react-perf-debugging/  
  https://news.ycombinator.com/item?id=11036007  
  A 2-part series on React performance.  Excellent information.  Goes in-depth on use of the Perf API, shouldComponentUpdate, shallow equality, and how to properly profile components.  Highly recommended.  Further useful discussion in the HN comment thread.
  
- **Respectable React Components**  
  http://kelle.co/react-perf-slides/  
  A slideshow that walks through the core concepts of managing good React performance.
  
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
  
- **Performance optimisations for React applications**  
  https://medium.com/@alexandereardon/performance-optimisations-for-react-applications-b453c597b191  
  Covers ways to make update checks fast and easy.  (NOTE: the advice given to "denormalize" data may not be the best approach - see discussion with Dan Abramov in the comments.)
  
- **Should I use shouldComponentUpdate?**  
  http://jamesknelson.com/should-i-use-shouldcomponentupdate/  
  A reminder that `shouldComponentUpdate` is itself code that has to execute, and that using it involves measured tradeoffs.
  
- **"shouldComponentUpdate - using it for performance optimizations"**  
  https://www.reddit.com/r/reactjs/comments/4gfn26/shouldcomponentupdate_using_it_for_performance/  
  Discussion on pros, cons, and approaches to using `shouldComponentUpdate`
  
- **A Cartoon Guide to Performance in React**  
  https://www.youtube.com/watch?v=-t8eOoRsJ7M  
  An excellent presentation by Lin Clark of Code Cartoons.  Covers what work browsers do when rendering, what work React does, and the main ways you can improve React performance.  Very clear and easy to understand.
  
- **Component Rendering Performance in React**  
  https://medium.com/modus-create-front-end-development/component-rendering-performance-in-react-df859b474adc  
  A comparison of how fast rendering happens in React 14 vs 15, and functional components vs class components
  
- **Performance Conditionally Rendered Content in React**  
  https://gist.github.com/ryanflorence/a301dc184f75e929a263dc1e80399a28  
  A tip for improving performance when conditionally rendering components: use a function as a child, and only call that function if the condition is true.
  
- **Dan Abramov - "Don't stress over binding in render"**  
  https://twitter.com/dan_abramov/status/760199672824815616  
  Dan advises not to worry about binding methods in render functions unless profiling shows it's a real perf problem for you
  
- **Real-World React Debugging**  
  https://www.youtube.com/watch?v=0MGTONvtlrI  
  http://jaredforsyth.com/real-world-react-debugging/#/  
  A talk on strategies for debugging React apps, with slides.
  
- **Don't Use Bind when Passing Props**  
  https://daveceddia.com/avoid-bind-when-passing-props/  
  https://www.reddit.com/r/reactjs/comments/4ri9x8/dont_use_bind_when_passing_props/  
  Advice on approaches to function binding, with further discussion.
  
- **React Perf Debugging: Animation and FLIPping**  
  https://engineering.siftscience.com/browser-dgaf-that-you-use-react/  
  https://engineering.siftscience.com/browser-dgaf-use-react-pt-2-flipping-react/  
  A deep dive into some tricky issues that come up with running animations, and some ways to work around those.
  
- **Virtualizing the Virtual DOM**  
  https://medium.com/outsystems-engineering/virtualizing-the-virtual-dom-pushing-react-further-d76a16e5f209  
  Discussion and examples of using the "virtualization" technique to only render list components that are currently in view.
  
- **Creating more efficient React views with windowing**  
  https://bvaughn.github.io/connect-tech-2016/#/  
  An excellent slideshow on performance topics from the author of the React-Virtualized library.  Covers sources of slowness, ways to avoid re-renders, and a deep look at "windowing/virtualization" for high-performance lists.
  
- **React Component Profiling**  
  https://blog.yld.io/2016/11/25/react-component-profiling/  
  Tips on using the new browser devtools integration capability in React 15.4 to track component performance.
  
- **React Snippets: Debug Component performance with ES7 Annotations**  
  https://www.neos.io/blog/react-snippets-debug-component-performance-with-es7-annotations.html  Demonstrates using a custom decorator to wrap components and log information on when and why components re-rendered
  
  
  
  
#### Code Splitting and Progressive Apps

Also see [Webpack Advanced Techniques](./webpack-advanced-techniques.md)

- **Progressive Web Apps with React**  
  https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-i-introduction-50679aef2b12  
  https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-2-page-load-performance-33b932d97cf2  
  https://medium.com/@addyosmani/progressive-web-apps-with-react-js-part-3-offline-support-and-network-resilience-c84db889162c  
  A multi-part series by Addy Osmani on building performant Progressive Web Apps, including page loading, code splitting, and offline handling.


- **Progressive loading for modern web applications via code splitting**  
  https://medium.com/@lavrton/progressive-loading-for-modern-web-applications-via-code-splitting-fb43999735c6  
  Examples of how to set up code splitting, and write components that encapsulate the process for improved loading times.
  
- **Performance Optimizing a React Single Page App**  
  https://medium.com/front-end-hacking/performance-optimizing-a-react-single-page-app-a68985fa72cc  
  https://medium.com/@ryancollinsio/performance-optimizing-a-react-single-page-app-part-2-92a0f0c83202  
  A series of articles looking at various performance-related topics, including server rendering, asset optimization, code splitting, memoization, and immutable data.
  
  
#### Immutable Data

- **Building Efficient UI with React and Redux**  
  https://www.toptal.com/react/react-redux-and-immutablejs  
  Builds a simple app using React, Redux, and Immutable.js, and looks at some of the most common misuses of React and how to avoid them.
  
- **"Comparing React to Vue for dynamic tabular data"**  
  https://news.ycombinator.com/item?id=11765477  
  Good comments from an HN thread discussing a React vs Vue benchmark.  A Discord developer talks about several lessons learned, including pros and cons of using Immutable.js, and only rendering elements that are visible.
  
- **Immutable.js: worth the cost?**  
  https://medium.com/@AlexFaunt/immutablejs-worth-the-price-66391b8742d4
  Looks at several pros and cons of using Immutable.js, such as enforced immutability (pro), and major performance problems from calling `toJS()`  frequently (con).

- **React + Redux performance optimization with shouldComponentUpdate**  
  http://stackoverflow.com/questions/37285200/react-redux-performance-optimization-with-componentshouldupdate  
  Discussion of proper Redux connection structure and use of Immutable's `toJS()`, with links to further articles and discussions.

- **"React-Immutable-Mixin vs PureRenderMixin" - comment from Lee Byron**  
  https://github.com/jurassix/react-immutable-render-mixin/issues/19#issuecomment-222567064  
  Immutable.js author Lee Byron comments on a performance discussion, giving advice on suggested Immutable.js usage patterns
  
- **"Immutable perf tip: avoid toJS"**  
  https://twitter.com/leeb/status/746733697093668864  
  Another suggestion from Lee Byron to avoid use of Immutable.js's data conversion functions based on performance reasons.
  
- **"Potential concerns with using Immutable.js"**  
  https://www.reddit.com/r/javascript/comments/4rcqpx/dan_abramov_redux_is_not_an_architecture_or/d51g4k4?context=3  
  A comment discussing a number of potential negative tradeoffs when using Immutable.js, including both performance anti-patterns and API issues
  
  
#### Redux Performance
  
- **High Performance Redux**  
  http://somebody32.github.io/high-performance-redux/  
  A detailed HTML slideshow that digs down into React Redux to show how `connect()`'s optimizations work, and has interactive demos to show various approaches.  (Note: the code-related slides advance using the down arrow to step through different lines of code - don't miss that info!)
  
- **How to optimize small updates to props of nested component?**  
  http://stackoverflow.com/questions/37264415/how-to-optimize-small-updates-to-props-of-nested-component-in-react-redux  
  Looks at how a normalized Redux state structure combined with multiple connected components can improve performance
  
- **Redux TodoMVC Pull #1: Optimization**  
  https://github.com/mweststrate/redux-todomvc/pull/1  
  An optimization pass for a Redux vs MobX benchmark, demonstrating several techniques
  
- **Redux Issue #1751: Performance issues with large collections**  
  https://github.com/reactjs/redux/issues/1751  
  Discussion of several factors that affect Redux performance
  
- **Improving React and Redux Performance with Reselect**  
  http://blog.rangle.io/react-and-redux-performance-with-reselect/  
  Covers how to use Reselect to define memoized "selector" functions that can cut down on duplicate work
  
- **Chat discussion - summary of Redux connection perf considerations**  
  https://gist.github.com/markerikson/53735e4eb151bc228d6685eab00f5f85  
  An overview of how having many connected components can improve performance
  
- **Chat discussion - single connected component vs many connected components**  
  https://gist.github.com/markerikson/6056565dd65d1232784bf42b65f8b2ad  
  An extended chat log discussing pros and cons of various approaches to managing connected components in a Redux app
  
- **React Performance Debugging: The Magic of Reselect Selectors**  
  http://rea.tech/reactjs-performance-debugging-aka-the-magic-of-reselect-selectors/  
  Discussion of React perf topics, and how Reselect selector functions can improve perf for Redux apps

- **Refactoring Components for Redux Performance**  
  https://yahooeng.tumblr.com/post/152078809581/refactoring-components-for-redux-performance  
  Discusses common perf issues, methods for analyzing perf, and ways to structure Redux-connected container components to cut down on re-rendering.
  
- **React/Redux Performance Tuning Tips**  
  https://medium.com/@arikmaor/react-redux-performance-tuning-tips-cef1a6c50759  
  A number of suggestions for improved performance with Redux