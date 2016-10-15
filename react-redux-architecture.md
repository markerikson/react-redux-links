### React/Redux Architecture


**Related topics**:
- [React Component Patterns](./react-component-patterns.md)
- [React State Management](./react-state-management.md)
- [React and Forms](./react-forms.md)
- [React and AJAX](./react-ajax.md)

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


#### React Component Management

- **8 no-Flux strategies for React component communication**  
  http://andrewhfarmer.com/component-communication/  
  Very helpful list of ways to have React components communicate back and forth

- **How to communicate between React components**  
  http://ctheu.com/2015/02/12/how-to-communicate-between-react-components/  
  Another good list of component communication strategies
  
- **How to Write a Google Maps React Component**  
  https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/  
  Demonstrates how to wrap a third-party component that has an imperative API, lazy-loading the dependencies, and more.
  
- **Building SVG Maps with React**  
  https://blog.komand.com/building-svg-maps-with-react  
  Demonstrates building a component that zooms and pans SVG graphics based on user input.
  
- **How to Sprinkle ReactJS into an Existing Web Application**  
  https://scotch.io/tutorials/how-to-sprinkle-reactjs-into-an-existing-web-application  
  Looks at how to incrementally add some React-based functionality into an existing app.
  
- **How to handle React context in a reliable way**  
  https://medium.com/react-ecosystem/how-to-handle-react-context-a7592dfdcbc  
  Covers what the context feature is, how to use it, and some concerns to be aware of.
  
- **Writing a good React Component**  
  https://medium.com/thoughts-from-travelperk/writing-a-good-react-component-59624ed40b8e  
  Some very good best practices for writing components.

- **Making custom renderers for React**  
  http://goshakkk.name/react-custom-renderers/  
  Describes techniques for building custom rendering components that bridge between normal rendering and something like a canvas
  

  
#### Project File Structure

- **Scaling React.js Applications**  
  https://vimeo.com/168648012  
  Max Stoiber's talk about managing large react.js applications. Covers "Feature" structure, redux-saga and CSS modules.
  
- **How to Scale React Applications**  
  https://www.smashingmagazine.com/2016/09/how-to-scale-react-applications/  
  Max Stoiber, creator of the popular "React-Boilerplate" starter kit, describes the approaches they use to lay out projects based on features.

- **Organizing Large React Applications**  
  http://engineering.kapost.com/2016/01/organizing-large-react-applications/  
  Describes "File-Type First", "Feature First / Pods" approaches, as well as other related structure issues.
  
- **Four Strategies for Organizing Code**  
  https://medium.com/@msandin/strategies-for-organizing-code-2c9d690b6f33  
  Describes "by component", "by toolbox", "by layer", and "by kind" approaches.

- **Rules for Structuring (Redux) Applications**  
  http://jaysoo.ca/2016/02/28/organizing-redux-application/  
  Gives several useful rules for structuring code, with examples.
  
- **A Better File Structure for React/Redux Applications**  
  http://marmelab.com/blog/2015/12/17/react-directory-structure.html  
  Suggests a domain-based structure, with tests kept alongside the code they relate to.
  
- **Route-Based Folder Structure**  
  https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346  
  Ryan Florence, an author of React Router, gives his suggested file structure.
  
- **How to Better Organize Your React Applications?**  
  https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1  
  Another feature-style approach, describing things in terms of "components", "scenes", and "services".
  
- **Fractal Project Structure**  
  https://github.com/davezuko/react-redux-starter-kit/wiki/Fractal-Project-Structure  
  Docs from the React Redux Starter Kit project describing their "Fractal Project Structure" concept, and advice for file and app organization.
  
- **Redux Structure: a Way to Success**  
  https://datarockets.com/blog/redux-structure  
  Thoughts on a "modules and components"-based approach to file structure, 
  
- **My journey toward a maintainable project structure for React/Redux**  
  https://hackernoon.com/my-journey-toward-a-maintainable-project-structure-for-react-redux-b05dfd999b5  
  Describes an evolution of approaches for project structure


#### Redux Architecture

  
- **Wordpress Calypso: Our Approach to Data**  
  https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md  
  The team behind Wordpress's new admin panel looks at their migration from emitters to Flux to Redux, and describes how they organize their state tree, use selectors to extract state, run queries with components, and persist their store state through refreshes.
  
- **So you've screwed up your Redux store - or, why Redux makes refactoring easy**  
  https://blog.boldlisting.com/so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy-400e19606c71  
  Describes some useful practices for organizing Redux actions, reducers, and selectors.
  
- **How we reduced boilerplate and handled asynchronous actions with Redux**  
  https://blog.algolia.com/how-we-reduced-boilerplate-and-handled-asynchronous-actions-with-redux/  
  A look at conventions that have helped the Algolia team write Redux apps.
  
- **10 Tips for Better Redux Architecture**  
  https://medium.com/javascript-scene/10-tips-for-better-redux-architecture-69250425af44  
  A great article covering when and why to use Redux, benefits, and several tips for a better application architecture.

- **Redux without Profanity**  
  https://tonyhb.gitbooks.io/redux-without-profanity/content/  
  An online book covering best practices and approaches for managing a Redux application
  
- **Where do I put my business logic in a React-Redux application?**  
  https://medium.com/@jeffbski/where-do-i-put-my-business-logic-in-a-react-redux-application-9253ef91ce1  
  Describes several options for managing logic and async behavior (thunks, sagas, etc), and introduces a new middleware as an alternative approach

- **Code Sharing Between React Native and React Web Apps**  
  https://medium.com/the-many/code-sharing-between-react-native-and-react-web-apps-b1e1de22fc53  
  Describes ways to architect Redux actions and reducers in the context of a product that shares code between React Native and React Web clients
  
- **You Might Not Need Redux**  
  https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367  
  Dan Abramov discusses the tradeoffs involved in using Redux.
  
- **Avoiding Accidental Complexity When Structuring Your App State**  
  https://hackernoon.com/avoiding-accidental-complexity-when-structuring-your-app-state-6e6d22ad5e2a  
  An excellent set of guidelines for organizing your Redux store structure.
  
- **Things I Wish I Knew About Redux**  
  https://medium.com/horrible-hacks/things-i-wish-i-knew-about-redux-9924abf2f9e0  
  https://www.reddit.com/r/javascript/comments/4taau2/things_i_wish_i_knew_about_redux/  
  A number of excellent tips and lessons learned after building an app with Redux.  Includes info on connecting components, selecting data, and app/project structure.  Additional discussion on Reddit.

- **Developing component-based web apps with React and Redux**  
  https://medium.com/@carlos_paelinck/developing-component-based-web-apps-using-react-redux-6236bc958930  
  Some examples of component structure and data handling in a drawing app.
  
- **Switching from Backbone to React and Redux**  
  https://medium.com/@royisch/moving-to-react-redux-in-baby-steps-aea0402624bf  
  https://medium.com/@royisch/6-lessons-learned-from-going-to-production-with-react-redux-19257f6724f6  
  A pair of articles describing one company's transition from a Backbone app to using React and Redux.
  
- **Black Pixel Redux Handbook**  
  http://bpxl-labs.github.io/redux-handbook/  
  Black Pixel's guidelines for project/app structure and usage