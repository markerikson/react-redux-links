### React Tips and Techniques

  
- **Get your React.js application translated with style**  
  https://medium.com/@jamuhl/get-your-react-js-application-translated-with-style-4ad090aefc2c  
  A short opinionated intro to several aspects of handling translation in a React app, by the author of a React internationalization library.
  
- **Adding Drag and Drop to React**  
  https://www.dailydrip.com/blog/adding-drag-and-drop-to-react.html  
  An example of using react-dnd to add drag-and-drop behavior, in conjunction with Redux.
    
- **Climbing Up the React Component Tree**  
  https://www.ynonperek.com/2017/08/05/react-parent-hirearchy/  
  https://www.reddit.com/r/reactjs/comments/6s4czp/traversing_react_tree_in_the_opposite_direction/  
  Gives examples for calculating an array describing a component's parents, including using a HOC and using context.  Not a recommended thing to try, but the exploration of the idea is interesting.
  The Reddit comments have a bit more useful discussion.
  
- **SVG Patterns in React - Build a Twitter Wall**  
  https://www.robinwieruch.de/react-svg-patterns/  
  A tutorial that covers several aspects of using SVG in React, and demonstrates how to use the svg-patterns library to generate patterend backgrounds.
  
- **Using React v16 to create self-destructing components**  
  https://medium.com/@gajus/using-react-v16-to-create-self-destructing-components-de8e4eb61d0f  
  Demonstrates how a tiny component that simply returns its own children can simplify the process of returning arrays of components in React 16.
  
  
#### Security

- **Exploiting Script Injection Flaws in ReactJS Apps**  
  https://medium.com/dailyjs/exploiting-script-injection-flaws-in-reactjs-883fb1fe36c1  
  Describes how React is safe by design as long as it's used as intended, and looks at several possible attack vectors that can result from wrong use of React.
  
- **How can I securely use CSS-in-JS with React?**  
  https://reactarmory.com/answers/how-can-i-use-css-in-js-securely  
  Covers several potential security holes that can result from allowing user input into CSS-in-JS libraries, with examples.
  
  
#### JSX

- **Is JSX Still Relevant? Are there other options?**  
  https://goshakkk.name/jsx-relevancy-options/  
  Gosha Arinich addresses complaints about using JSX and "mixing HTML into JS" by discussing how JSX is syntax sugar for `React.createElement()` calls, and how JSX is really optional.
  
- **React Without JSX**  
  https://mockbrian.com/blog/2017/08/11/react-without-jsx/  
  Describes how to add React to an existing page with no build tools, and a couple approaches to writing render functions that don't use JSX.
  
- **Integrating React and Redux Into an Existing Backbone App**  
  http://blog.isquaredsoftware.com/2017/07/react-redux-backbone-integration/
  A look at ways to show React components inside of Backbone views, and some discussion of how to simplify React rendering when JSX isn't available by using libraries like `react-hyperscript-helpers`.
  
- **How I learned to stop worrying and love the JSX**  
  http://jamesknelson.com/learned-stop-worrying-love-jsx/  
  Discusses several aspects of JSX, including "separation of concerns", how JSX translates into function calls, that JSX is optional, when to avoid using JSX, and more.
  
- **React without a build step**  
  https://medium.com/@alexkrolick/writing-react-components-for-3rd-party-embedding-50331c18e26  
  Describes how using `React.createElement` instead of JSX eliminates the need for a compile step, compares examples of equivalent JSX and `createElement` usage, and shows how to write a small embeddable widget using React/Preact that doesn't need any build step at all.
  
  
#### Debugging and Error Handling

- **Intro to Debugging React Applications**  
  https://medium.com/@baphemot/intro-to-debugging-reactjs-applications-67cf7a50b3dd  
  An excellent introduction to the basic tools, concepts, and approaches for debugging React apps, including the browser's DevTools console, network tab, and source debugger, as well as the React DevTools.
  
- **React v16 beta is out, suddenly everyone needs to catch UI errors**  
  https://medium.com/shiftgig-blog/react-v16-beta-is-out-suddenly-everyone-needs-to-catch-ui-errors-37c8c4b527e9  
  Discussion and examples of using the new `componentDidCatch` and `ErrorBoundary` features in React 16, including a demo of what errors they will and won't catch.
  
- **Catching exceptions using Higher Order Components in React 16**  
  https://codeburst.io/catching-exceptions-using-higher-order-components-in-react-16-b8a401853a10  
  https://twitter.com/dan_abramov/status/890716011133100032  
  Examples of how to write a Higher-Order-Component that adds error boundaries.  ALso worth contrasting with Dan's tweet, where he suggests that you shouldn't need to use HOCs to make use of error boundaries.