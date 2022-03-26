### React Tips and Techniques

- **React and Accessibility Tips and Best Practices**  
  https://www.aditus.io/talks/react-and-accessibility/  
  A transcript of a talk with accessibility tips in general and with some React best practices. Includes tips in React Router, and Formik.
    
- **Get your React.js application translated with style**  
  https://medium.com/@jamuhl/get-your-react-js-application-translated-with-style-4ad090aefc2c  
  A short opinionated intro to several aspects of handling translation in a React app, by the author of a React internationalization library.
  
- **Adding Drag and Drop to React**  
  https://www.dailydrip.com/blog/adding-drag-and-drop-to-react.html  
  An example of using react-dnd to add drag-and-drop behavior, in conjunction with Redux.
  
- **SVG Patterns in React - Build a Twitter Wall**  
  https://www.robinwieruch.de/react-svg-patterns/  
  A tutorial that covers several aspects of using SVG in React, and demonstrates how to use the svg-patterns library to generate patterend backgrounds.
  
- **Translating React Apps**  
  https://tech.gadventures.com/translating-react-apps-99dede52d924  
  Discusses how to use the React-Intl library to add translations to a React app
  
- **Lessons from migrating a large codebase to React 16**  
  https://blog.discordapp.com/lessons-from-migrating-a-large-codebase-to-react-16-e60e49102aa6  
  An excellent post from the Discord team recapping how they migrated an older React codebase to work with React 16, including use of codemods, replacing private API usage, upgrading dependencies, and other issues they ran into.
  
- **Robust React User Interfaces with Finite State Machines**  
  https://css-tricks.com/robust-react-user-interfaces-with-finite-state-machines/  
  An excellent article that describes the concepts of state machines, how they relate to applications, and how they can be applied to help manage React component behavior.
  
- **The Complete Firebase in React Authentication Tutorial**  
  https://www.robinwieruch.de/complete-firebase-authentication-react-tutorial/  
  A comprehensive article that covers setting up a React app that uses React Router for handling routes, and Firebase for authentication and user management.
  
- **Don't Over React! Rendering Binary Data**  
  https://www.bignerdranch.com/blog/dont-over-react/  
  Useful approaches for handling file blobs in a React app
  
- **Global Component Registration**  
  http://dylanpaulus.com/reactjs/2017/12/08/global-component-registration/  
  An example of extending the standard approach for looking up component types at runtime, by allowing the lookup table to be modified.
  
- **Getting Started with Web Accessibility**  
  https://medium.com/@emilymears/getting-started-with-web-accessibility-in-react-9e591fdb0d52  
  An excellent look at ways to handle accessibility in React, including use of refs for focus, ARIA attributes, helpful tools, and more.
  

#### Security

- **Exploiting Script Injection Flaws in ReactJS Apps**  
  https://medium.com/dailyjs/exploiting-script-injection-flaws-in-reactjs-883fb1fe36c1  
  Describes how React is safe by design as long as it's used as intended, and looks at several possible attack vectors that can result from wrong use of React.
  
- **How can I securely use CSS-in-JS with React?**  
  https://reactarmory.com/answers/how-can-i-use-css-in-js-securely  
  Covers several potential security holes that can result from allowing user input into CSS-in-JS libraries, with examples.
  
  
#### JSX and Events

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
  
- **9 Things You Should Know About JSX**  
  https://dev.to/sarah_chima/9-things-you-should-know-about-jsx-3bm  
  A useful explanation of what JSX syntax is, how it works, and and how to use it.
  
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

- **Using React Fragments for the first time**  
  https://www.jackfranklin.co.uk/blog/react-fragments/
  Describes the Fragment "component" and syntax introduced in React 16.2, the problems Fragments solve, and how to use them.

  
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
