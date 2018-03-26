### React/Redux Performance and Optimization

My [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) list includes a number of useful tools for visualizing React component updates, in the [Devtools > Component Update Monitoring](https://github.com/markerikson/redux-ecosystem-links/blob/master/devtools.md#component-update-monitoring) section.


#### React Components

- **React Docs: Performance**  
  https://facebook.github.io/react/docs/advanced-performance.html  
  https://facebook.github.io/react/docs/perf.html  
  The React doc pages on performance.  Describes the core concepts, including shouldComponentUpdate, using immutable data, and the Performance API for benchmarking.
    
- **React, Inline Functions, and Performance**  
  https://cdb.reacttraining.com/react-inline-functions-and-performance-bdff784f5578  
  An excellent article Ryan Florence that pushes back against the "creating functions in render is slow" conventional wisdom in the React community.  This article is a must-read discussion on React performance.
  
- **Performance Engineering with React**  
  http://benchling.engineering/performance-engineering-with-react/  
  http://benchling.engineering/deep-dive-react-perf-debugging/  
  https://news.ycombinator.com/item?id=11036007  
  A 2-part series on React performance.  Excellent information.  Goes in-depth on use of the Perf API, shouldComponentUpdate, shallow equality, and how to properly profile components.  Highly recommended.  Further useful discussion in the HN comment thread.
  
- **Respectable React Components**  
  http://kelle.co/react-perf-slides/  
  A slideshow that walks through the core concepts of managing good React performance.
  
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
  https://bvaughn.github.io/forward-js-2017/#/  
  https://youtu.be/t4tuhg7b50I  
  An excellent talk on performance topics from Brian Vaughn, a React core team member and author of the React-Virtualized library.  Covers sources of slowness, ways to avoid re-renders, and a deep look at "windowing/virtualization" for high-performance lists.
  
- **React Component Profiling**  
  https://blog.yld.io/2016/11/25/react-component-profiling/  
  Tips on using the new browser devtools integration capability in React 15.4 to track component performance.
  
- **React Snippets: Debug Component performance with ES7 Annotations**  
  https://www.neos.io/blog/react-snippets-debug-component-performance-with-es7-annotations.html  
  Demonstrates using a custom decorator to wrap components and log information on when and why components re-rendered
  
- **How to Benchmark React Components: The Quick and Dirty Guide**  
  https://medium.com/code-life/how-to-benchmark-react-components-the-quick-and-dirty-guide-f595baf1014c  
  Suggestions for using React's Perf API to benchmark component rendering, and use of shouldComponentUpdate to cut down on unnecessary renders.
  
- **Why and How to Use PureComponent in React**  
  https://60devs.com/pure-component-in-react.html  
  A look into what React.PureComponent is, how it works, and how it can be used to improve performance
  
- **React at 60FPS**  
  https://hackernoon.com/react-at-60fps-4e36b8189a4c  
  A look at several useful techniques for benchmarking and improving React application performance
  
- **Optimizing the Performance of Your React Application**  
  https://auth0.com/blog/optimizing-react/  
  Covers several ways to improve perf, including profiling with the React Perf Addons, using correct keys for lists, and use of `shouldComponentUpdate` and `PureComponent`.
  
- **Why Did This React Component Re-Render?**  
  http://ericlathrop.com/2017/02/why-did-this-react-component-rerender/  
  A reminder that passing a style object in `render` will usually cause shallow-equality checks to fail, even if the style values are identical
  
- **React is Slow, React is Fast: Optimizing React Apps in Practice**  
  https://medium.com/dailyjs/react-is-slow-react-is-fast-optimizing-react-apps-in-practice-394176a11fba  
  A clear and informative explanation covering multiple aspects of performance, including use of the Chrome DevTools flame graph for visualizing perf, extracting components and implementing `shouldComponentUpdate`, connecting to Redux, and use of Recompose and Reselect to improve performance.
  
- **Optimizing React Performance with Stateless Components**  
  https://www.sitepoint.com/optimizing-react-performance-stateless-components/  
  Shows the basics of using functional components, discusses why `shouldComponentUpdate` is needed for perf improvements, and demonstrates use of `PureComponent` and the Recompose library as other possible approaches.
  
- **Twitter Lite and High Performance React Progressive Web Apps at Scale**  
  https://medium.com/@paularmstrong/twitter-lite-and-high-performance-react-progressive-web-apps-at-scale-d28a00e780a3  
  Excellent advice and information from the Twitter Lite dev team on how they optimized their app, including code splitting, ways to avoid "jank", optimizing React rendering, optimizing Redux usage, and more.
  
- **Optimizing React Rendering**  
  https://flexport.engineering/optimizing-react-rendering-part-1-9634469dca02  
  https://flexport.engineering/optimizing-react-rendering-part-2-7b2e9a9ea21f  
  https://flexport.engineering/ending-the-debate-on-inline-functions-in-react-8c03fabd144  
  Discusses several aspects of improving React rendering performance, including tips for ensuring your codebase is ready to use `PureComponent`.  Has a link to further discussion on HN.  Part 2 describes how they built a library called `mutation-sentinel` to detect accidental mutations, and Part 3 covers a Babel plugin for optimizing inline functions in render methods.
  
- **Introducing react-wastage-monitor**  
  https://blog.listium.com/introducing-react-wastage-monitor-404565d679b2  
  Describes a number of common perf issues in React apps, and how the react-wastage-monitor library can be used to detect them
  
- **Infinite List and React**  
  http://itsze.ro/blog/2017/04/09/infinite-list-and-react.html  
  A Twitter developer describes some of the challenges they faced in building a performant infinite scrolling list component
  
- **React at Light Speed**  
  https://blog.vixlet.com/react-at-light-speed-78cd172a6411  
  The Vixlet team discusses perf optimizations they've applied to their app.  Includes a lot of the common advice like use of `shouldComponentUpdate`, but also has advice on use of literal values and issues with performance traps with JS timer functions.
  
- **React Performance Anti-Pattern: Creating Functions in `render()`**  
  https://medium.com/@erikras/react-performance-anti-pattern-creating-functions-in-render-ddeb5ebd2933  
  Describes why creating functions inside of `render()` is bad for perf, specifically in relation to optimization and prop reference comparisons, and offers several alternate patterns as solutions.
  
- **Memoize React components**  
  https://medium.com/@planttheidea/memoize-react-components-33377d7ebb6c  
  Discusses the basic ideas of memoization, and shows how they can be applied to wrapping React components using the `moize` library (or other memoization libraries).
  
- **When to use Component or PureComponent**  
  https://codeburst.io/when-to-use-component-or-purecomponent-a60cfad01a81  
  Good advice on the potential benefits of using `PureComponent`, as well as several potential downsides or gotchas (such as binding functions in `render()`).

- **The Virtual DOM and its Anti-Patterns**  
  https://medium.com/riipen-engineering/the-virtual-dom-and-its-anti-patterns-aa4c523d00ed  
  First in a 3-part series discussing causes of slow components and wasteful rendering.  Later posts will cover ways to optimize Redux usage, and tools to find bottlenecks that can be optimized.
  
- **How to greatly improve your React app performance**  
  https://medium.com/myheritage-engineering/how-to-greatly-improve-your-react-app-performance-e70f7cbbb5f6  
  Discusses React perf issues like bad `sCU` implementations, changing the DOM too fast, and event/callback usage, with possible solutions.  
  
- **React Performance Fixes on Airbnb Listing Pages**  
  https://medium.com/airbnb-engineering/recent-web-performance-fixes-on-airbnb-listing-pages-6cd8d93df6f4  
  Excellent practical discussion of actual perf issues that were showing up in Airbnb pages and how they resolved them.  Covers performance recordings, handling initial renders, scrolling, only using component state for values that affect re-rendering, and more.
  
- **Debugging React Performance with React 16 and Chrome DevTools**  
  https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad  
  Shows how to use the Chrome DevTools to profile React code using performance recordings, including analysis of recordings to track down perf issues.
  
- **Demystifying Memory Usage using ES6 React Classes**  
  https://medium.com/@donavon/demystifying-memory-usage-using-es6-react-classes-d9d904bc4557  
  A quick look at the memory usage differences between calling `Function.bind` and using the Class Properties syntax, and the readability tradeoffs involved.
  
- **How does React decide to re-render a component?**  
  http://lucybain.com/blog/2017/react-js-when-to-rerender/  
  An easy-to-read overview of when and why a component will re-render.
  
- **Dragging React performance forward**  
  https://medium.com/@alexandereardon/dragging-react-performance-forward-688b30d40a33  
  A detailed look at how the react-beautiful-dnd library implemented performance improvements with drastically better results, including avoiding unnecessary renders and DOM reads, applying style updates, virtualizing movement, and using lookup tables. 
  
  
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

- **Javascript Start-up Performance**  
  https://medium.com/dev-channel/javascript-start-up-performance-69200f43b201  
  Addy Osmani digs into the issues involved in parsing and compiling JS scripts on load, discusses how to measure performance, and gives advice for lower parse times.
  
- **Improving first load time of a Production React App**  
  https://hackernoon.com/improving-first-time-load-of-a-production-react-app-part-1-of-2-e7494a7c7ab0  
  A detailed look at the various approaches used by UrbanClap to improve their load time, including file chunking, on-demand loading, dropping non-critical libraries, and more
  
- **Simple Pattern for Asynchronously Loading React Components**  
  https://mackness.github.io/react/patterns/2017/03/20/simple-pattern-for-asynchronously-loading-react-components.html  
  A quick example of using dynamic importing to lazy-load React components
  
- **React Progressive Web Apps**  
  https://medium.com/progressive-web-apps/react-progressive-web-apps-part-1-1cf381421672  
  https://medium.com/progressive-web-apps/react-progressive-web-apps-part-2-d55c6bd4b316  
  A pair of posts that cover how to set up an initial PWA and check its behavior against best practices, and how to add offline-first behavior to a React+Redux PWA. 
  
- **What profiling my Universal React-Redux app revealed**  
  https://medium.com/@darioghilardi/what-profiling-a-universal-react-redux-app-revealed-c5cc4986353c  
  Discusses using the Chrome DevTools to debug and do CPU profiling of a Node server process that was doing server-side rendering of a React app.
  
- **Performance-tuning a React application**  
  https://medium.com/@joshuawcomeau/performance-tuning-a-react-application-f480f46dc1a2  
  An excellent case study on improving load time for a small React+Redux app.  Describes use of gzipping, image cropping, lazy loading, and more.
  
- **A React and Preact Progressive Web App Performance Case Study: Treebo**  
  https://medium.com/dev-channel/treebo-a-react-and-preact-progressive-web-app-performance-case-study-5e4f450d5299  
  An extensive technical deep dive into how Treebo optimized their React application for good performance on mobile devices.
  
- **Firebase + React: Optimizing for the Real World**  
  https://codeburst.io/firebase-react-optimizing-for-the-real-world-4d9edbbd54c5  
  Describes shrinking a React + Firebase app bundle from 1.7MB to 230KB by switching to smaller alternative packages and analyzing bundle size.
  
- **A Pinterest Progressive Web App Performance Case Study**  
  https://medium.com/dev-channel/a-pinterest-progressive-web-app-performance-case-study-3bd6ed2e6154  
  A deep dive into how Pinterest optimized their new PWA app, including route chunking, use of babel-preset-env, service workers, and use of normalized Redux state.
  
  
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
  
  
- **Persistent data structures and structural sharing: a reason to use Immutable.js**  
  https://medium.com/@dtinth/immutable-js-persistent-data-structures-and-structural-sharing-6d163fbd73d2  
  https://www.reddit.com/r/reactjs/comments/5h7pqz/persistent_data_structures_and_structural_sharing/  
  https://twitter.com/acemarke/status/806933658204372992  
  An excellent article that describes how Immutable.js's implementation can improve performance while updating large objects, with benchmarks.  There's further good discussion on Reddit, and in the Twitter thread, Immutable.js author Lee Byron confirms that calling `toJS()` is _very_ expensive and should definitely not be used in a Redux `mapState` function.
  
- **Should I use Immutable.js with Redux?**  
  https://medium.com/@fastphrase/should-i-use-immutablejs-with-redux-58f88d6fd81e  
  A well-written comparison of several pros and cons for using Immutable.js, including perf benefits, perf negatives, enforced immutability, and overhead of use.
  
- **"Performance of immutable data updates"**  
  https://www.reddit.com/r/javascript/comments/699d6i/whats_a_transducer/dh5nzad/?context=3  
  Some Reddit comments pointing out that there is always a cost to updating data immutably, but that it's worth considering that cost in the context of the application.
  
  
#### Redux Performance
  
- **Practical Redux, Part 6: Connected Lists, Forms, and Performance**  
  http://blog.isquaredsoftware.com/2017/01/practical-redux-part-6-connected-lists-forms-and-performance/  
  Discusses the key considerations for performance in Redux apps, with some examples and pointers to further information.
  
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
  
- **An artificial example where MobX really shines and Redux is not really suited**  
  https://medium.com/@dtinth/an-artificial-example-where-mobx-really-shines-and-redux-is-not-really-suited-for-it-1a58313c0c70  
  https://www.reddit.com/r/reactjs/comments/5hf4d4/an_artificial_example_where_mobx_really_shines/  
  https://github.com/dtinth/pixelpaint/pull/1  
  An excellent in-depth article that sets up a specific benchmark example, and compares the performance of a MobX implementation vs several different Redux-based implementations.  There's valuable discussion in the Reddit comments, and Dan Abramov submitted a PR to the sample project that demonstrates some fairly simple changes that result in improved Redux performance.
  
- **Performance Optimizations in Redux's `mapStateToProps`**  
  http://cmichel.io/performance-optimizations-in-redux-mapstatetoprops/  
  Some quick tips on how to properly cache and memoize selectors for use in `mapState` functions
  
- **Surprising polymorphism in React applications**  
  https://medium.com/@bmeurer/surprising-polymorphism-in-react-applications-63015b50abc  
  A Chrome V8 engine developer digs into the nitty-gritty details of how common Redux reducer patterns result in less-optimized behavior from the JS engine running the code.
  
- **Redux isn't slow, you're just doing it wrong - an optimization guide for React-Redux**  
  http://reactrocket.com/post/react-redux-optimization/  
  An excellent summary of the basic steps for good performance with React-Redux
  
- **Measuring performance gains - AngularJS to React (with Redux or MobX)**  
  https://medium.com/@guptagaruda/measuring-performance-gains-angularjs-to-react-with-redux-or-mobx-fb221517455  
  A highly detailed article that investigates and benchmarks performance between an Angular 1.x app and equivalent React+Redux and React+MobX apps in a variety of real-world use cases.  Excellently written and researched.
  
- **The most unknown Redux performance trick**  
  https://medium.com/@jidefr/the-most-unknown-redux-performance-trick-986fdfe871fa  
  Examples of how `connect`'s lesser-known `areStatesEqual` option can be used to skip unnecessary re-renders.
  
- **Optimizing Redux Components**  
  https://medium.com/riipen-engineering/optimizing-redux-components-cbaad062abc7  
  Discusses Redux-specific perf optimizations, such as avoiding unnecessary work in `mapState` functions, memoization, and advanced comparison function options for `connect`.
  
- **React + Redux Performance and the Benchmarks to Prove It**  
  https://tech.smartling.com/react-redux-performance-and-the-benchmarks-to-prove-it-79b0bc9f25a4  
  Describes an approach for benchmarking a React+Redux app to understand how much impact performance optimizations actually give.
  
- **Redux's Connect function and areStatesEqual Option**  
  https://medium.com/@ryansperzel/reduxs-connect-function-and-arestatesequal-option-adc97e00ee0  
  Looks at one of `connect`'s options that can be used to customize comparisons and skip unnecessary `mapState` calls.
