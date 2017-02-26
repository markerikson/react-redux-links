### React Architecture and Best Practices


#### Thinking in React

- **Thinking in React**  
  https://facebook.github.io/react/docs/thinking-in-react.html  
  The original guide to breaking a UI into components and setting up data flow

- **Removing User Interface Complexity, or Why React is Awesome**  
  http://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome  
  A long walkthrough that builds up a pseudo-React-like library, demonstrating what React does and why you would want to use it. Has lots of embedded demos.

- **Describing UI State with Data**  
  http://nicolashery.com/describing-ui-state-with-data/  
  Demonstrates modeling the state and actions of an application, and updating the UI based on that.

- **Components, React, and Flux**  
  http://slides.com/danabramov/components-react-flux-wip#/  
  A fantastic HTML slideshow that discusses how to organize code as reusable components, and the basic concepts and benefits of a Flux unidirectional architecture
  
- **"Trying to understand why React prefers one-way data binding"**  
  https://www.reddit.com/r/javascript/comments/4ni311/trying_to_understand_why_react_prefers_oneway/  
  Some excellent and very informative discussion on why the "one-way data flow" paradigm is used with React, vs two-way data binding.
  
- **You're Missing the Point of React**  
  https://medium.com/@dan_abramov/youre-missing-the-point-of-react-a20e34a51e1a  
  Dan Abramov explains React's real value: not popularizing the virtual DOM, but its use of composition and unidirectional data flow 
  
- **How to solve a Problem with React**  
  https://codequs.com/p/HyLJOnBt/how-to-solve-a-problem-with-react/  
  A guide explaining ways to approach planning out a React app: composing individual components into larger components, or working top-down to plan out a component hierarchy.
  
- **A Conceptual Introduction to React Components**  
  https://ifelse.io/2016/10/20/introducing-react-components/  
  Examples and suggestions for how to approach breaking a UI concept into components with relationships
  
- **Common React Mistakes - Unneeded State**  
  http://reactkungfu.com/2015/09/common-react-dot-js-mistakes-unneeded-state/  
  Examples of how to think about and model data and UI state

- **Understanding the Functional Revolution in Front-End Applications**  
  http://blog.reactandbethankful.com/posts/2015/09/15/understanding-the-functional-revolution/  
  Higher-level tutorial describing functional programming and how it relates to Javascript, UI, and client-side applications

- **Functional UI and Components as Higher Order Functions**  
  https://blog.risingstack.com/functional-ui-and-components-as-higher-order-functions/  
  Another tutorial on functional programming and how it relates to React

- **Reactive, Component-Based UIs**  
  http://banderson.github.io/reactive-component-ui-presentation/#/  
  Another fantastic HTML slideshow describing the three principles of React: "functional over OOP", "stateless over stateful", "clarity over brevity" (use arrow keys to advance slides)

- **Lessons Backbone Developers Can Learn From React**  
  http://benmccormick.org/2015/09/09/what-can-backbone-developers-learn-from-react/  
  Discusses 3 lessons from React: "UIs are trees of reusable components", "modern JS is cleaner code", and "don't use DOM for state"

- **State is an Anti-Pattern**  
  https://www.reddit.com/r/reactjs/comments/3bjdoe/state_is_an_antipattern/  
  Some long-winded but useful thoughts on what makes a good component: "intuitive", "same input -> same output", "pure", and "only side effects are Flux actions"

- **Why Local Component State is a Trap**  
  https://www.safaribooksonline.com/blog/2015/10/29/react-local-component-state/  
  Thoughts on a "single state tree" vs local component state
  
- **Functional Javascript: Reverse-Engineering the Hype**  
  http://banderson.github.io/functional-js-reverse-engineering-the-hype/#/  
  A slideshow that talks about why functional-type programming matters, and how it relates to React-type apps.
  
- **Principles of Strong Components**  
  http://gedd.ski/post/strong-components/  
  Generic advice on designing good components.  Not React-specific, but highly applicable to React.
  
- **Some Thoughts on Function Components in React**  
  https://medium.com/javascript-inside/some-thoughts-on-function-components-in-react-cb2938686bc7  
  Suggestions for ways to approach writing components, particularly using React's functional component syntax
  
- **Why React is Awesome at Scale**  
  https://medium.com/@cowi4030/why-react-is-awesome-at-scale-acfd9ce53c23  
  Examples of how React's use of declarative rendering simplifies the need to think about imperative state transitions.
  
- **"What are the biggest 'aha' moments you had while learning React?"**  
  https://www.reddit.com/r/reactjs/comments/5gmywc/what_were_the_biggest_aha_moments_you_had_while/  
  Some great discussion of important concepts and things to understand about React.
  
- **React "aha" moments**  
  https://tylermcginnis.com/react-aha-moments/  
  Tyler McGinnis shares some of his own "aha" moments in thinking about React
  
- **From Backbone to React: How to write great code**  
  https://frontendne.co.uk/talks/from-backbone-to-react-how-to-write-great-code  
  A talk that looks at a number of key ideas that React helps you understand, and uses some comparisons between Backbone and React to illustrate them.
  
- **Thinking Statefully**  
  https://daveceddia.com/thinking-statefully/  
  Some great examples of how to think in declarative/stateful terms (such as passing an `isOpen` prop to a modal instead of calling `open()` ).


#### React Best Practices

- **Nine things every React beginner should know**  
  https://camjackson.net/post/9-things-every-reactjs-beginner-should-know  
  A solid list of concepts and suggestions for writing a React-based app.
  
- **React Best Practices and Tips**  
  http://www.toptal.com/react/tips-and-practices  
  Several excellent guidelines for component structure and behavior
  
- **Best Practices for Building Large React Applications**  
  http://blog.siftscience.com/blog/2015/best-practices-for-building-large-react-applications  
  Excellent advice for structuring components and improving reuse
  
- **Designing Simpler React Components**  
  https://medium.com/building-asana/designing-simpler-react-components-13a0061afd16  
  Tips on developing components for a scalable application, including using immutable data, pure functions, and some interesting suggestions on injecting data into components to improve separation of concerns.
  
- **React.js Best Practices for 2016**  
  https://blog.risingstack.com/react-js-best-practices-for-2016/  
  Some high-level suggestions for tools and approaches.
  
- **How to avoid refactoring in your first React.js application**  
  http://andrejgajdos.com/how-to-avoid-refactoring-in-your-first-react-application/  
  Covers several useful topics such as props vs state and use of shouldComponentUpdate, and links to several other articles on anti-patterns and component lifecycles.
  
- **The State of React.js in 2016**  
  https://speakerdeck.com/koba04/the-state-of-react-dot-js-2016  
  Looks at a number of things to consider when writing React code today, including deprecation of string refs and upcoming updates to the React rendering implementation
  
- **React Playbook**  
  https://github.com/kylpo/react-playbook  
  https://medium.com/@kylpo/redux-best-practices-eef55a20cc72  
  A variety of tips, best practices, opinions, and comparisons related to React, Redux, Immutable.js, and MobX.  Includes thoughts on component architecture, file structure, coding style, and other topics.
  
- **React Best Practices & Patterns**  
  http://seanamarasinghe.com/developer/react-best-practices-patterns/  
  A number of useful conventions for writing React code.
  
- **React Gotchas**  
  https://daveceddia.com/react-gotchas/  
  Three quick tips to keep in mind while writing React code (capitalize component names, close all JSX tags, and remember setState is asynchronous)
  
- **You're Missing the Point of JSX**  
  http://blog.andrewray.me/youre-missing-the-point-of-jsx/  
  Some arguments in favor of using JSX to define React UIs
  
- **Helpful principles when starting with React**  
  http://ignaciochavez.com/helpful-principles-starting-react/  
  Several useful tips for structuring components, managing data flow, and updating data.  Has some excellent diagrams illustrating the concepts described.
  
- **React/Redux - Best Practices and Gotchas**  
  http://blog.getstream.io/react-redux-best-practices-gotchas  
  Several useful tips for avoiding common pitfalls, structuring an application, and using various React-related tools
  
- **React Best Practices**  
  https://medium.com/@nesbtesh/react-best-practices-a76fd0fbef21  
  Suggestions and tips for effectively writing React and Redux
  
- **5 Simple Tips for Your First React + Redux Project**  
  https://blog.preen.ly/5-simple-tips-for-your-first-react-redux-project-10cbb2727b9a  
  Good suggestions for managing state and structure, including using local component state when necessary, use of selector functions, and more.
  
- **Writing a good React Component**  
  https://medium.com/thoughts-from-travelperk/writing-a-good-react-component-59624ed40b8e  
  Some very good best practices for writing components.
  
- **The Top 5 [Tips] of Effective React**  
  https://code.kiwi.com/the-top-5-of-effective-react-984e54cceac3  
  Tips include using container/presentational components, keeping components simple, and more.
  
- **Advice on large scale React apps - rebuilding the social publishing platform for Latam**  
  https://medium.com/taringa-on-publishing/advice-on-large-scale-react-js-apps-rebuilding-the-biggest-social-publishing-platform-for-latam-1f4c8fa35a4f  
  Lessons learned from migrating a PHP application to a universal React/Redux/Webpack application, including introducing React to a team, documentation, types, and more.
  
- **11 lessons learned as a React contractor**  
  https://medium.com/@jolyon_russ/11-lessons-learned-as-a-react-contractor-f515cd0491cf  
  https://news.ycombinator.com/item?id=13332138  
  A number of useful tips, including using multiple small components instead of one customizable one, migrating build processes, keeping things simple, and more.  Extended discussion in the HN comments.
  
- **Tips to Learn React + Redux**  
  https://www.robinwieruch.de/tips-to-learn-react-redux/  
  An extensive and excellent list of suggestions to follow when learning and using React and Redux.  Tips include when to use different component patterns, when to bring in a state management library, Redux state structuring, and much more.
  
- **10 Reasons why I moved from Angular to React**  
  https://www.robinwieruch.de/reasons-why-i-moved-from-angular-to-react/  
  Robin Wieruch gives some good thoughts why he chose to focus on React.  A nice overview of some of React's benefits.
  
- **Our journey migrating 100K lines of code from AngularJS to React**  
  https://tech.small-improvements.com/2017/01/25/how-to-migrate-an-angularjs-1-app-to-react/  
  The Small Improvements team describes how they implemented an Angular>React migration, starting from the bottom up.
  
- **Our Best Practices for Writing React Components**  
  https://medium.com/code-life/our-best-practices-for-writing-react-components-dec3eb5c3fc8  
  A description of the MuseFind team's approaches for writing components
  
- **Lessons Learnt Rewriting a React Library from Scratch**  
  https://www.codecks.io/blog/2017/lessons-learnt-rewriting-react-lib/  
  Some suggestions for use of context, embracing components, and writing documentation
  
- **10 React mini-patterns**  
  https://hackernoon.com/10-react-mini-patterns-c1da92f068c5  
  A collection of simple but useful patterns for writing React code, from basic top-down data flow via props to formatting text for display.