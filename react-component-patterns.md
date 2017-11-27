### React Component Patterns

**Related topics**:
- [Thinking in React](./thinking-in-react-and-flux.md): Articles discussing ways to think about React applications and component structure
- **[React Implementation and Concepts](./react-implementation.md)**: Includes articles that explain the differences between "components", "elements", and "instances"
<a id="higher-order-components"></a>
<a id="composing-components-with-functional-programming"></a>
- **[React Component Composition](./react-component-composition.md)**: Articles explaining ways to compose components, including Higher-Order Components, Function-as-Child / "render props", and other functional composition approaches


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
  
- **Embracing Functions in React**  
  https://medium.com/javascript-inside/embracing-functions-in-react-d7d558d8bd30  
  A look at stateless functional components in React, and why they might be useful or should be considered in the first placee.
  
- **Building User Interfaces with Pure Functions and Function Composition in React**  
  https://tylermcginnis.com/building-user-interfaces-with-pure-functions-and-function-composition-in-react-js/  
  A look at the idea of composing together UIs with simple components, with comparisons to the idea of combining functions together.
  
- **React Bits: React patterns, techniques, tips, and tricks**  
  https://github.com/vasanthk/react-bits  
  An extensive list of terms, concepts, patterns, and techniques for writing React components, with explanations and examples.  A few of the descriptions are overly opinionated and some items are not things the React team would recommend, but overall an excellent resource.
  
- **Simple React Patterns**  
  http://lucasmreis.github.io/blog/simple-react-patterns/  
  A clearly written set of examples that showcase common React component patterns like "container/presentational", "Higher-Order Components", "Function-as-Child" / "render props", and "providers".
  
- **React Component Patterns**  
  https://medium.com/gitconnected/react-component-patterns-ab1f09be2c82  
  A summary of common React component patterns with short examples.
  
- **10 React mini-patterns**  
  https://hackernoon.com/10-react-mini-patterns-c1da92f068c5  
  Ten useful patterns for working with React components, including data flow, techniques for working with inputs, controlling CSS usage, switching between components, and more.
  
- **React Training: Advanced React - React Patterns**  
  https://reacttraining.com/patterns/  
  The lecture videos from React Training's "Advanced React" course.  The videos themselves are now free.  Covers topics like declarative vs imperative, compound components, context, Higher Order Components, render props, and controlled components.
  

#### Component Definition Approach Comparisons
  
- **How to use Classes and Sleep at Night**  
  https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4  
  Some pragmatic opinions on when and how to use the ES6 "class" keyword, particularly in relation to React components.
  
- **React Stateless Functional Components: Nine Wins You Might Have Overlooked**  
  https://medium.com/@housecor/react-stateless-functional-components-nine-wins-you-might-have-overlooked-997b0d933dbc  
  Thoughts on reasons why you might want to write more components using the functional syntax.
  
- **7 Reasons to Outlaw React's Functional Components**  
  https://medium.freecodecamp.org/7-reasons-to-outlaw-reacts-functional-components-ff5b5ae09b7c 
  The author of the "Nine Wins" post gives some counter-arguments on why you might want to prefer writing class components instead of functional components.  Some good discussion in the comments.
  
- **How to declare React Components in 2017**  
  https://medium.com/@npverni/how-to-declare-react-components-in-2017-2a90d9f7984c  
  A quick overview of the three ways to declare React components, and which ones should be preferred.
  
- **We Jumped the Gun Moving React Components to ES2015 Class Syntax**  
  https://medium.com/dailyjs/we-jumped-the-gun-moving-react-components-to-es2015-class-syntax-2b2bb6f35cb3  
  A Netflix engineer raises concerns about React deprecating `createClass` and pushing users to use ES6 classes.  I personally think his concerns are overstated, but there's some interesting points, plus good discussion in the comments.
  

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
  
- **Tips on Creating Reusable Components**  
  http://dylanpaulus.com/reactjs/2017/09/08/tips-on-creating-reusable-components.1/  
  Examples of using `children` and other props to make components more composable and reusable.
  

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
  
- **How to use React's Provider pattern**  
  https://www.robinwieruch.de/react-provider-pattern-context/  
  Walks through the concepts and implementation of a "Provider" component that makes data available to deeply nested children, similar to the ones that come with Redux and MobX
  
- **Passing Data Between React Components**  
  https://medium.com/@ruthmpardee/passing-data-between-react-components-103ad82ebd17  
  Some short examples of how to pass data between parents, children, and siblings.
  
- **How to structure components in React?**  
  https://reallifeprogramming.com/how-to-structure-components-in-react-54fc43e71546  
  Compares multiple ways to pass data from a parent to a child, including no props, passing a value object, passing required props, passing a map of props, and using `children`.
  
- **Context 101**  
  http://reactboston.surge.sh/#/  
  Slides from Ken Wheeler's ReactBoston talk on React's `context` feature. Covers what context is, why you might want to use it, and when/ how to use it/
  

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
  
- **Reusable state for React UI components**  
  https://medium.com/@efreyreg/reusable-state-for-react-ui-components-e38c5af40be4  
  An example of taking a component that has both state, logic, and presentation, and extracting the logic and presentation into separate components.  Also demonstrates using a Redux-like approach to update logic without actually using Redux.
  
- **Extracting Logic from React Components**  
  https://javascriptplayground.com/blog/2017/07/react-extracting-logic/  
  Demonstrates taking a component that includes some logic for formatting a value, and refactoring it to extract out the formatting logic into separate functions.

- **Refactoring React**  
  https://8thlight.com/blog/josh-mccormick/2017/08/21/refactoring-react.html  
  Demonstrates extracting state and logic out of a component to separate responsibility and improve ease of testing.
  
- **How do you separate React components?**  
  https://reactarmory.com/answers/how-should-i-separate-components  
  Describes four categories of React components ("view", "control", "controllers", and "containers"), and gives suggestions on when and how to factor out new components.
  
- **Refactoring: Moving API calls to a higher-order component**  
  https://medium.com/@guigonc/refactoring-moving-api-calls-to-a-higher-order-component-53062c086cb  
  Shows how to progressively refactor fetching logic out of a component and move it into a parent component, then make that parent component reusable.
  
- **The React + Redux Container Pattern**  
  https://dev.to/sophiedebenedetto/the-react--redux-container-pattern-bmk  
  An excellent explanation of what "container components" and "presentational components" are, with discussion of how they fit together and a good sample project implementing the ideas.
  

  

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
  
- **React components as jQuery plugins**  
  https://swizec.com/blog/using-react-in-the-real-world/swizec/6710  
  Demonstrates how to wrap up a React component as a jQuery plugin for integration with non-React apps.
  
- **Using D3 and React Together to Make Visualizations with TypeScript**  
  https://spin.atomicobject.com/2017/07/20/d3-react-typescript/  
  Examples of some possible approaches to using D3 inside of React, including use of refs and components.
  
- **Wrapping Web Components With React**  
  https://www.sitepen.com/blog/2017/08/08/wrapping-web-components-with-react/  
  A detailed walkthrough of how to create React components that wrap up existing web components, including managing props, handling events, and keeping the DOM in sync.
  
- **Migrating complex Javascript applications**  
  https://javascriptplayground.com/blog/2017/08/migrating-complex-javascript-angular-react/  
  Jack Franklin describes the lessons learned when his team migrated from Angular to React, including why they migrated, how they approached the architecture changes, how they prioritized what to change, and more.  Includes some examples of the Angular->React change, but also good advice in general.
  

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
  
- **Good React Modals**  
  https://medium.com/@elsdoerfer/good-react-modals-548cd9c2f7f4  
  Covers ways to handle issues with modal content not being rendered while doing animations, and side-loading data for a modal while maintaining a loading indicator.
  
- **Using a React 16 Portal to do something cool**  
  https://hackernoon.com/using-a-react-16-portal-to-do-something-cool-2a2d627b0202  
  Demonstrates using React 16's `createPortal` API to control a separate browser window from the original React component tree.
 

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
  
- **Using React v16 to create self-destructing components**  
  https://medium.com/@gajus/using-react-v16-to-create-self-destructing-components-de8e4eb61d0f  
  Demonstrates how a tiny component that simply returns its own children can simplify the process of returning arrays of components in React 16.
  
- **3 React Gripes**  
  https://gist.github.com/jlongster/febd2a397aff9501abec0c2d66075ec8  
  https://twitter.com/jlongster/status/921016877408837632  
  James Long describes three things about React that bother him: inability to easily have parents get refs to nested elements, PureComponents comparing both props and state, and a general tendency to do lots of processing in `componentWillReceiveProps`.  Some good discussion in both the gist comments and Twitter.
  
- **React without `this`**  
  https://medium.com/@baronmaximilianwilleford/react-without-this-39a76b8f2160  
  Describes an alternate approach to writing components using factory functions to eliminate the need for the `this` keyword
  
- **You don't need to know "Dependency Injection"**  
  https://hackernoon.com/you-dont-need-to-know-dependency-injection-2e9d2ba1978a  
  Looks at the concept of dependency injection, and three ways that that relates to React components and props.
  
