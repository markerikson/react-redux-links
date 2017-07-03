### React Component Patterns

**Related topics**:
- [Thinking in React](./thinking-in-react-and-flux.md): Articles discussing ways to think about React applications and component structure
- **[React Implementation and Concepts](./react-implemenation.md)**: Includes articles that explain the differences between "components", "elements", and "instances"


#### Component Terms, Concepts, and Types

- **React Patterns**  
  http://reactpatterns.com/  
  An excellent list of common patterns for structuring React components, with examples
  
- **React Component Jargon as of August 2016**  
  https://medium.com/@arcomito/react-component-jargon-as-of-august-2016-28451d8ceb1d  
  A very useful glossary of widely-used terms describing React components
  
- **React in Patterns**  
  https://github.com/krasimir/react-in-patterns  
  http://krasimirtsonev.com/blog/article/react-js-presentational-container-components  
   List of design patterns/techniques used while developing with React
  
- **Functional Components vs. Stateless Functional Components vs. Stateless Components**  
  https://tylermcginnis.com/functional-components-vs-stateless-functional-components-vs-stateless-components-630fdfd90c9c  
  Clarifies the meaning of the terms, which are often used in overlapping ways.
  
- **How to use Classes and Sleep at Night**  
  https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4  
  Some pragmatic opinions on when and how to use the ES6 "class" keyword, particularly in relation to React components.
  
- **Embracing Functions in React**  
  https://medium.com/javascript-inside/embracing-functions-in-react-d7d558d8bd30  
  A look at stateless functional components in React, and why they might be useful or should be considered in the first place.
  
- **React Stateless Functional Components: Nine Wins You Might Have Overlooked**  
  https://medium.com/@housecor/react-stateless-functional-components-nine-wins-you-might-have-overlooked-997b0d933dbc  
  Thoughts on reasons why you might want to write more components using the functional syntax.

- **How to declare React Components in 2017**  
  https://medium.com/@npverni/how-to-declare-react-components-in-2017-2a90d9f7984c  
  A quick overview of the three ways to declare React components, and which ones should be preferred.
  
- **Building User Interfaces with Pure Functions and Function Composition in React**  
  https://tylermcginnis.com/building-user-interfaces-with-pure-functions-and-function-composition-in-react-js/  
  A look at the idea of composing together UIs with simple components, with comparisons to the idea of combining functions together.
  
- **React Bits: React patterns, techniques, tips, and tricks**  
  https://github.com/vasanthk/react-bits  
  An extensive list of terms, concepts, patterns, and techniques for writing React components, with explanations and examples.  A few of the descriptions are overly opinionated and some items are not things the React team would recommend, but overall an excellent resource.
  
  
 
#### Component Rendering Logic
  
- **Dynamically Rendering React Components**  
  https://wail.es/dynamically-rendering-react-components/  
  Examples of how to dynamically determine which React component to render
  
- **Loading State Trick for Stateless Functional Components in React**  
  http://kyleshevlin.com/loading-state-trick-for-stateless-functional-components-in-react/  
  An example of conditionally rendering a spinner component if a list of items is empty
  
- **How to Dynamically Render React Components**  
  http://kyleshevlin.com/how-to-dynamically-render-react-components/  
  A quick example of how to dynamically decide which component type to render
  
- **All the Conditional Renderings in React**  
  https://www.robinwieruch.de/conditional-rendering-react/  
  Examples of all the possible ways to conditionally render components
  
- **"React render function organization"**  
  https://gist.github.com/markerikson/47fff93c92286db72b22bab5b02e2da3  
  My suggested approach for organizing render function logic for clarity and readability
  
- **Simplify complex React components with generators**  
  https://nvbn.github.io/2017/03/14/react-generators/  
  An interesting alternative to the usual if/else-type logic for conditionally rendering components, by using ES6 generators to yield the right pieces to render.
  
  
#### React Component Children
  
- **Ownership and Children in React**  
  http://ctheu.com/2015/02/10/ownership-and-children-in-reactjs/  
  Discusses the difference between "parent" and "owner" relationships, and what the `children` prop can look like.
  
- **ReactCasts #3: React's Children API**  
  https://www.youtube.com/watch?v=DJ53-G8EbxE  
  A screencast demonstrating how the `children` prop to compose components together
  
- **React.Children and the React Top-Level API**  
  http://callahan.io/blog/2016/09/16/react-dot-children-and-the-react-top-level-api/  
  Overviews and examples of the `React.Children` APIs, and how they can be used to manipulate component children
  
- **Send Props to Children in React**  
  http://jaketrent.com/post/send-props-to-children-react/  
  Examples of how to pass new props to child components using `React.Children`
  
- **A deep dive into children in React**  
  http://mxstbr.blog/2017/02/react-children-deepdive/  
  An in-depth look at the power and capabilities of React's `children` prop, and how children can be reused and modified.  Includes several examples and demos.
  
- **The "Forwarded Refs" pattern**  
  https://github.com/reactjs/react-redux/pull/270#issuecomment-175217424  
  An example of the "forwarded refs" pattern, where a parent component passes a callback through one or more layers of children, it's used as a `ref` callback, and the parent receives the nested DOM element reference directly.
  
- **React component composition cheatsheet**  
  https://github.com/xat/react-component-composition-cheatsheet  
  A useful list of ways to combine components together
  
- **Avoiding deeply nested component trees**  
  https://medium.com/@RubenOostinga/avoiding-deeply-nested-component-trees-973edb632991  
  Examples of `children` to include arbitrary content inside of a component for more flexible handling of presentation and composition.
  
  
  
#### React Component Lifecycle

- **React Docs: Component Specs and Lifecycle**  
  https://facebook.github.io/react/docs/component-specs.html  
  The official React docs page on component lifecycle
  
- **Understanding the React Component Lifecycle**  
  http://busypeoples.github.io/post/react-component-lifecycle/  
  A good look at which lifecycle methods run in which situations, as well as the signatures of each method.
  
- **Dissecting React Lifecycle Methods**  
  https://medium.com/@fay_jai/dissecting-reactjs-lifecycle-methods-be4fdea11c6d  
  Breaks the lifecycle methods down into "mount/unmount" and "update" categories, and describes the purpose and use of each.
  
- **The React Component Lifecycle**  
  https://www.kirupa.com/react/component_lifecycle.htm  
  Another useful description of the order and purpose of the lifecycle methods.
  
- **React In-Depth: The React Life Cycle**  
  https://developmentarc.gitbooks.io/react-indepth/content/  
  A deep dive into the lifecycle methods, and various techniques for using them.
  
- **React Lifecycle Cheatsheet**  
  https://gist.github.com/bvaughn/923dffb2cd9504ee440791fade8db5f9  
  A table listing the lifecycle methods, when they're called, whether each method allows side effects or state updates, and examples uses for each method
  
- **React Lifecycle Methods - how and when to use them**  
  https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1  
  A helpful description of the major component lifecycle methods, including descriptions of common use cases for each one, and whether you can call `setState` inside.
  
  
#### Component Communication

- **8 no-Flux strategies for React component communication**  
  http://andrewhfarmer.com/component-communication/  
  Very helpful list of ways to have React components communicate back and forth

- **How to communicate between React components**  
  http://ctheu.com/2015/02/12/how-to-communicate-between-react-components/  
  Another good list of component communication strategies
  
- **How React Components Communicate**  
  http://react.tips/how-reactjs-components-communicate/  
  A careful tutorial-based explanation of how to communicate between parent and child components.
  
- **How to handle React context in a reliable way**  
  https://medium.com/react-ecosystem/how-to-handle-react-context-a7592dfdcbc  
  Covers what the `context` feature is, how to use it, and some concerns to be aware of.
  
- **How to safely use React context**  
  https://medium.com/@mweststrate/how-to-safely-use-react-context-b7e343eff076  
  Guidelines for when and how to actually use React's `context` feature
  
- **Context All the Things with React**  
  https://www.youtube.com/watch?v=k9AhBMwj1w4  
  A talk on what `context` is, and how to use it safely
  
- **ReactCasts #4-5: Context (Parts 1 and 2)**  
  https://www.youtube.com/watch?v=lxq938kqIss  
  https://www.youtube.com/watch?v=mwYHDXS6uSc
  A two-part series explaining what React's `context` feature can be used for, and some potential concerns to be aware of when using it.    
  
- **React Context and Component Coupling**  
  https://medium.com/differential/react-context-and-component-coupling-86e535e2d599  
  Discussion on the pros and cons of using `context` to pass data between components, and some examples of how to do so
  
- **Higher Order With Context**  
  https://dev.to/kayis/higher-order-with-context  
  https://dev.to/kayis/higher-order-components-and-context-example 
  Examples of using Higher Order Components to pass data to nested components using `context`
  
- **Context in React Applications**  
  http://javascriptplayground.com/blog/2017/02/context-in-reactjs-applications/  
  An overview of what `context` is, how it works, and when you should use it for passing data
  
- **Callback functions in React**  
  https://medium.com/@thejasonfile/callback-functions-in-react-e822ebede766  
  Some basic explanations of how a React app uses callback functions to communicate from children to parents
  
  
#### Component Categories

- **Presentational and Container Components**  
  https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0  
  Dan Abramov's foundational article on classifying components based on intent and behavior.  A must-read for anyone using React.
  
- **"People are reading way too much into 'presentational' vs 'container'"**  
  https://twitter.com/dan_abramov/status/802569801906475008  
  Dan Abramov follows up his article by emphasizing that "presentational" and "container" was just a pattern he had noticed, rather than an approach that _must_ be followed
  
- **Leveling Up with React: Container Components**  
  https://css-tricks.com/learning-react-container-components/  
  Describes the container component pattern and how to use it to split up responsibilities between fetching and displaying data.
  
- **Smart and Dumb Components in React**  
  http://jaketrent.com/post/smart-dumb-components-react/  
  Another look at ways to conceptually categorize components based on responsibilities, and some ways you can organize your code based on those concepts.
  
- **Ramblings About React and Redux Architecture**  
  https://medium.com/@kurtiskemple/ramblings-about-react-and-redux-architecture-c27dfff79ddf  
  Thoughts on structuring components as "Providers", "Behavior", and "Presentational"
  
- **The Anatomy of a React Redux App**  
  https://medium.com/@rajaraodv/the-anatomy-of-a-react-redux-app-759282368c5a  
  Breaks down the component structure of a typical React/Redux app, and classifies the different types of components that usually show up
  
- **React and Flux in Production Best Practices**  
  https://medium.com/@delveeng/react-and-flux-in-production-best-practices-c87766c57cb6  
  Delve's practice of describing components as "containers", "smart", and "dumb"
  
- **Content vs Container**  
  https://hackernoon.com/content-vs-container-e0a1ada681c1  
  General advice for determining component responsibilities in terms of content, layout, and logic
  
- **The React + Redux Container Pattern**  
  http://www.thegreatcodeadventure.com/the-react-plus-redux-container-pattern/  
  Explanation and examples of "container" and "presentational" components and their responsibilities.  Uses Redux for the examples, but the principles apply to "just" React as well.
  
- **Refactoring React - Extracting Layout Components**  
  http://erikaybar.name/refactoring-react-extracting-layout-components/  
  Demonstrates creating reusable components that manage some aspects of styling and layout, such as a button with multiple sizes and colors.
  
- **Share Code between React and React Apps**  
  https://hackernoon.com/code-reuse-using-higher-order-hoc-and-stateless-functional-components-in-react-and-react-native-6eeb503c665  
  An exploration of how to refactor code to extract functional components and higher-order components for improved code reuse,  including reusing the same components in both React and React Native apps.
  
  
#### Higher-Order Components

- **Mixins Are Dead.  Long Live Composition**  
  https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750  
  A look at some of the issues with using mixins, and reasons why higher-order components are (usually) an improvement.
  
- **Mixins Considered Harmful**  
  https://facebook.github.io/react/blog/2016/07/13/mixins-considered-harmful.html  
  https://news.ycombinator.com/item?id=12087796  
  Dan Abramov explains why the React team discourages use of mixins, and prefers HoCs
  
- **Higher Order Components: Theory and Practice**  
  http://engineering.blogfoster.com/higher-order-components-theory-and-practice/  
  Gives practical use cases for HOCs, such as authentication, routing, and data management, with samples.

- **Sharing and Testing Code in React with Higher Order Components**  
  http://blog.carbonfive.com/2016/02/02/sharing-and-testing-code-in-react-with-higher-order-components/  
  Demonstrates extracting HOCs from existing code, and testing them.
  
- **Higher Order React Components**  
  http://natpryce.com/articles/000814.html  
  A solid explanation of what HoCs are, with examples and use cases
  
- **Higher Order Components: A React Application Design Pattern**  
  https://www.sitepoint.com/react-higher-order-components/  
  A discussion of how to use Higher Order Components to keep your React applications tidy, well structured and easy to maintain.  Also, how pure functions keep code clean and how these same principles can be applied to React components.
  
- **Connected Higher Order Components with React and Redux**  
  http://www.avitzurel.com/blog/2016/08/03/connected-higher-order-components-with-react-and-redux/  
  Demonstrates creating HoCs that are connected to Redux
  
- **React, Higher Order Components, and Legacy Applications**  
  http://browniefed.com/blog/react/  
  Examples of how to integrate React into an existing application using HoCs
  
- **React Higher Order Components in depth**  
  https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e  
  A very detailed article looking at some advanced HoC patterns
  
- **Real World Examples of Higher Order Components**  
  http://rea.tech/reactjs-real-world-examples-of-higher-order-components/  
  Explanations and examples of HOCs and their uses
  
- **Function as Child Components**  
  https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9  
  Explains the "function as a child" technique as an alternative to Higher Order Components
  
- **Functions as Child Components and Higher Order Components**  
  http://rea.tech/functions-as-child-components-and-higher-order-components/  
  Comparisons and examples for these two component patterns
  
- **ReactCasts: Higher Order Components**  
  https://youtu.be/6nVxCWUAEPM  
  A screencast that walks through the idea and usage of Higher Order Components
  
- **ReactCasts: Function as Child Component**  
  https://www.youtube.com/watch?v=WE3XAt9P8Ek  
  A screencast that introduces the idea of Functions as Children and demonstrates usage
  
- **Annotations about React Higher-Order Components**  
  https://blog.codeminer42.com/annotations-about-react-higher-order-components-e3561bc7c27a  
  An explanation of what HOCs are, what they can be used for, and when to use them.
  
- **Single-Prop HOCs - Better Composition in React**  
  https://www.okgrow.com/posts/compose-react-sphoc  
  Thoughts and examples of composing multiple small focused HOCs together into a final combined HOC
  
- **What are Higher Order Components?**  
  https://benmccormick.org/2016/12/14/what-are-higher-order-components/  
  A short, simple explanation of what an HOC is, and how they can be used
  
- **Higher Order What?**  
  https://dev.to/kayis/higher-order-what  
  A quick introduction to the concept of Higher Order Functions and Components
  
- **Reusable State with Higher Order Components**  
  https://daveceddia.com/extract-state-with-higher-order-components/  
  An easy-to-read explanation of how HOCs work, and examples of how to extract common logic into a reusable HOC
  
- **React Patterns - Render Callback**  
  http://leoasis.github.io/posts/2017/03/27/react-patterns-render-callback  
  An explanation of the "render callback" or "function as child" pattern, including concepts and example uses
  
- **Simplifying life with React render callbacks**  
  https://medium.com/@adamrackis/simplifying-life-with-react-render-callbacks-cb37d58e55  
  An overview of several different ways to wrap up components, including cloning children, HOCs, and render callbacks.
  
- **Why you should keep your React components pure by using HOCs**  
  https://medium.com/@DjamelH/why-you-should-keep-your-react-components-pure-by-using-hocs-67e5c7f80c81  
  Walks through extracting stateful behavior into an HOC so that it's more reusable and the wrapped components are simpler.
  
- **A gentle introduction to Higher Order Components**  
  https://www.robinwieruch.de/gentle-introduction-higher-order-components/  
  An excellent article demonstrating several ways to use HOCs to manage conditional rendering logic in a reusable way.
  

#### Wrapping Non-React Code

- **React and third-party libraries**  
  http://krasimirtsonev.com/blog/article/react-third-party-library-integration  
  Demonstrates how to build a React component that wraps up non-React code like a jQuery UI plugin
  
- **Declaratively Rendering Earth in 3D, Part 2: Controlling Cesium with React**  
  http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-2-cesium-react/  
  A detailed description of how to create React components that wrap up a 3D globe library, including use of lifecycle methods for controlling imperative non-React APIs.
  
- **When to use Ref on a DOM Node in React**  
  https://www.robinwieruch.de/react-ref-attribute-dom-node/  
  An explanation of the `ref` property, how to use it to access real DOM nodes, and when you should use it.
  
- **Using React and jQuery Together**  
  http://tech.oyster.com/using-react-and-jquery-together/  
  Examples of how to use jQuery inside a React component, and React inside jQuery-controlled elements
  
- **Using React and PixiJS**  
  http://www.rinconstrategies.io/using-react-and-pixijs.html  
  Demonstrates how to use React's component lifecycle methods to control the imperative PixiJS API
  
- **Mapping declarative React components to imperative external APIs**  
  http://reactkungfu.com/2016/02/mapping-declarative-react-components-to-imperative-external-api/  
  A quick example of using `componentWillReceiveProps` to pass updates to an imperative API
  
- **How to Write a Google Maps React Component**  
  https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/  
  Demonstrates how to wrap a third-party component that has an imperative API, lazy-loading the dependencies, and more.
  
- **Building SVG Maps with React**  
  https://blog.komand.com/building-svg-maps-with-react  
  Demonstrates building a component that zooms and pans SVG graphics based on user input.
  
- **How to Sprinkle ReactJS into an Existing Web Application**  
  https://scotch.io/tutorials/how-to-sprinkle-reactjs-into-an-existing-web-application  
  Looks at how to incrementally add some React-based functionality into an existing app, including interaction with jQuery.
  
- **How to Use jQuery Libraries in the React Ecosystem**  
  https://medium.com/@superKalo/how-to-use-jquery-libraries-in-the-react-ecosystem-7dfeb1aafde0  
  Some excellent examples of using React components to wrap up jQuery plugins: creating the plugin instance, updating the plugin from React props, and destroying the plugin on unmount.
  
- **Introducing React into an Existing Application**  
  https://medium.com/nthrive-analytics/introducing-react-into-an-existing-application-17490841796e  
  Some examples of how to progressively add React components into an existing jQuery-based application and keep them in sync with the rest of the app.
  
- **How to use D3.js in React**  
  http://cmichel.io/how-to-use-d3js-in-react/  
  An overview of three ways to integrate D3 into a React app: using React to render, using D3 to render, and a hybrid approach.
  
- **Renderless Components, or How Logic Doesn't Always Need a UI**  
  http://kyleshevlin.com/renderless-components/  
  Shows how you can create components that return null from `render`, and use React's lifecycle methods to drive imperative logic rather than rendering UI.
  
- **Getting Started with React and Leaflet**  
  https://www.azavea.com/blog/2016/12/05/getting-started-with-react-and-leaflet/  
  Examples of how to create React components that interact with the Leaflet maps library.
  
- **How (and why) to use D3 with React**  
  https://hackernoon.com/how-and-why-to-use-d3-with-react-d239eb1ea274  
  A good overview of some of the libraries and approaches you can make use of to use D3 in a React app
  
- **Integrating React with an Existing jQuery Web Application**  
  http://www.primaryobjects.com/2017/05/08/integrating-react-with-an-existing-jquery-web-application/  
  Covers 3 methods for methods for integrating React and jQuery: referencing jQuery from within React, using a helper class passed to React, and using a pub-sub model passed to React.
  
- **Building D3 Components with React**  
  https://hackernoon.com/building-d3-components-with-react-7510e4743288  
  A detailed walk through custom integration of D3 and React without use of an additional library.
  
- **PixiJS Application in a React Component**  
  https://www.protectator.ch/post/pixijs-v4-in-a-react-component  
  A quick example of loading PixiJS and wrapping it in a React component, showing the basics for integration.
  
  
#### Modal Dialogs
  
- **How to Render Components Outside the Main React App**  
  https://blog.komand.com/how-to-render-components-outside-the-main-react-app  
  An example of a technique that's also know as the "portal" approach, commonly used for rendering modals on top of the rest of an application. 
  
- **Modals in React**  
  https://medium.com/@david.gilbertson/modals-in-react-f6c3ff9f4701  
  A demonstration of building a reusable modal component using the "portals" technique

- **Modal Dialogs in React**  
  https://daveceddia.com/open-modal-in-react/  
  An excellent example of how to approach rendering modals in React, by controlling them with props
  
- **Modal window in React from scratch**  
  https://peteris.rocks/blog/modal-window-in-react-from-scratch/  
  Walks through creating a Modal component with styling and display logic
  
- **React Modals**  
  https://medium.com/@danparkk/react-modals-scalable-customizable-neat-components-f2088d60f3d3  
  An extended discussion of what concepts are involved in creating modals in web pages, why this can become complex, and how to implement them in a scalable way using React and Redux.
  
- **Tasks and Portals in React**  
  https://medium.com/@MoneyhubEnterpr/tasks-and-portals-in-react-1df2438cdebb  
  Describes how MoneyHub implemented modal dialogs with wizard-like workflows that tie together multiple screens, using a combination of container components and portals.
  
  
#### Composing Components with Functional Programming
  
  
- **Functional React Series - Part 1: Get your App outta my Component**  
  https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25  
  Part 1 in a series about writing React applications by treating components as functions, not templates.
  
- **Functional Components with React stateless functions and Ramda**  
  https://medium.com/@mirkomariani/functional-components-with-react-stateless-functions-and-ramda-e83e54fcd86b  
  Examples of using Ramda functions to compose together components
  
- **Composing React Components with Ramda**  
  https://medium.com/let-s-learn/lets-learn-composing-react-components-with-ramda-5db457997554  
  Another set of examples showing how to use composition of small functional components to create a larger set of behaviors.
  
- **Deconstructing the React Component: A Functional Approach to Building React Apps**  
  https://jaysoo.ca/2017/04/30/learn-fp-with-react-part-1/  
  https://jaysoo.ca/2017/05/10/learn-fp-with-react-part-2/  
  An excellent series that shows how to apply advanced Functional Programming techniques towards combining and composing React components together.
  
- **How to add state to functional components using Recompose**  
  http://blog.jakoblind.no/2017/04/03/how-to-add-state-to-functional-components-using-recompose/  
  Some quick examples of using the Recompose library to wrap components with additional behavior.
  
- **Top 5 Recompose HOCs**  
  https://medium.com/@abhiaiyer/top-5-recompose-hocs-1a4c9cc4566  
  A list of 5 useful HOCs provided by the Recompose library, including `branch` and `withHandlers`.
  
- **ReactCasts #11: Recompose**  
  https://youtu.be/SQtrgiLy3Fo  
  A screencast that introduces the Recompose library and explains some of its useful tools like `withState` and `branch`.
  
  
#### Other Component Patterns

- **The React Controller View Pattern**  
  http://blog.andrewray.me/the-reactjs-controller-view-pattern/  
  Describes using top-level components to hold state and pass it to children as props

- **Make Your React Components Pretty**  
  https://medium.com/walmartlabs/make-your-react-components-pretty-a1ae4ec0f56e  
  Techniques for making your components easier to read, including using functional components, using JSX spread for props, and use of destructuring.
  
- **Component Factories in React.js**  
  https://github.com/szabototo89/create-it/blob/master/docs/article-full.md  
  A variation on Dependency Injection for React components
  
- **"What is the ideal way to pass data to a callback prop?**  
  https://gist.github.com/jazlalli/fdee443405680f96d19211daa15d1d38  
  Discussion and examples of various ways to pass data to callbacks between children and parents
  
- **On Privacy with React Context**  
  https://medium.com/@amireh/on-privacy-with-react-context-aa77ffd08509  
  Thoughts on some potential issues with various component/state patterns (globals, Redux, Flux, Ember), and a sketch of a notional approach that might help solve some of those issues.
  
- **Internationalizing React Apps**  
  https://www.smashingmagazine.com/2017/01/internationalizing-react-apps/  
  An extended investigation of server and client aspects needed for internationalization.
  
- **Creating a cross-domain React component with xcomponent**  
  https://medium.com/@bluepnume/creating-a-cross-domain-react-component-with-xcomponent-fbcccc4778fd  
  A look at how to wrap a React component using the xcomponent library, so that it can be rendered and used across domains.
  