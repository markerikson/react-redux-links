### Redux Architecture and Best Practices

**Related Topics**:
- [Redux addons catalog - Apps and Examples](https://github.com/markerikson/redux-ecosystem-links/blob/master/apps-and-examples.md): Links to various projects built with Redux, both purpose-built-examples and "real" applications, as well as several Redux usage stories


#### When Should You Use Redux?

- **You Might Not Need Redux**  
  https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367  
  Dan Abramov discusses the tradeoffs involved in using Redux.
  
- **You Might Not Need Redux**  
  https://blog.tighten.co/you-might-not-need-redux  
  A similar article from Samantha Geitz, discussing when you might want to use Redux.
  
- **The Case for Flux**  
  https://medium.com/swlh/the-case-for-flux-379b7d1982c6#.tgrsz3zhc  
  The author of Redux lays out reasons you might want to use a Flux-style architecture
  
- **Reasons Why I Love Redux**  
  https://twitter.com/jlongster/status/780879989164081152  
  James Longster describes his appreciation for Redux, and how its constraints force you to think through your state handling
  
- **Why You Should Care About Flux**  
  http://jaysoo.ca/2015/06/02/why-you-should-care-about-flux/  
  Describes the value in separating "reads" from "writes", and eliminating local state.  Applies to Redux as well.
  
- **Redux and Why It's Good For You**  
  https://www.fullstackreact.com/articles/redux-with-mark-erikson/  
  An introduction to some benefits that Redux can give you when used in a React app, including multiple views of the same data and improved development with hot reloading.
  
- **When to use Redux**  
  https://medium.com/@fastphrase/when-to-use-redux-f0aa70b5b1e2  
  Some helpful thoughts on when you should use Redux: same app state needed in multiple components, global components that need to be accessed anywhere, too much prop passing, and more.
  
  
#### Redux Architecture

- **Wordpress Calypso: Our Approach to Data**  
  https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md  
  The team behind Wordpress's new admin panel looks at their migration from emitters to Flux to Redux, and describes how they organize their state tree, use selectors to extract state, run queries with components, and persist their store state through refreshes.
  
- **So you've screwed up your Redux store - or, why Redux makes refactoring easy**  
  https://blog.boldlisting.com/so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy-400e19606c71  
  Describes some useful practices for organizing Redux actions, reducers, and selectors.
  
- **10 Tips for Better Redux Architecture**  
  https://medium.com/javascript-scene/10-tips-for-better-redux-architecture-69250425af44  
  A great article covering when and why to use Redux, benefits, and several tips for a better application architecture.
  
- **Where do I put my business logic in a React-Redux application?**  
  https://medium.com/@jeffbski/where-do-i-put-my-business-logic-in-a-react-redux-application-9253ef91ce1  
  Describes several options for managing logic and async behavior (thunks, sagas, etc), and introduces a new middleware as an alternative approach

- **Code Sharing Between React Native and React Web Apps**  
  https://medium.com/the-many/code-sharing-between-react-native-and-react-web-apps-b1e1de22fc53  
  Describes ways to architect Redux actions and reducers in the context of a product that shares code between React Native and React Web clients
  
- **Avoiding Accidental Complexity When Structuring Your App State**  
  https://hackernoon.com/avoiding-accidental-complexity-when-structuring-your-app-state-6e6d22ad5e2a  
  An excellent set of guidelines for organizing your Redux store structure.
  
- **Redux Step by Step: A Simple and Robust Workflow for Real Life Apps**  
  https://hackernoon.com/redux-step-by-step-a-simple-and-robust-workflow-for-real-life-apps-1fdf7df46092  
  A follow-up to the "Accidental Complexity" article, discussing principles for structuring a Redux app and demonstrating how they apply to actual code.
  
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
  
- **Tips for a Better Redux Architecture: Lessons for Enterprise Scale**  
  https://hashnode.com/post/tips-for-a-better-redux-architecture-lessons-for-enterprise-scale-civrlqhuy0keqc6539boivk2f  
  Thoughts on good patterns and approaches in a large Redux app, including use of action creators instead of `dispatch` in components, module/container file structure, using sagas for flow control, and more.
  
- **Thinking in Redux (when all you've known is MVC)**  
  https://hackernoon.com/thinking-in-redux-when-all-youve-known-is-mvc-c78a74d35133  
  Some useful mental comparisons for understanding Redux when coming from an MVC architecture background
  
- **React + Redux: Architecture Overview**  
  https://medium.com/mofed/react-redux-architecture-overview-7b3e52004b6e  
  A look at the common pieces that make up a Redux application, with some very useful diagrams to illustrate what they are and how they fit together.
  
- **React Redux Architecture**  
  https://github.com/hirviid/react-redux-architecture  
  Some notes on an opinionated architecture for large React/Redux applications
  
- **Redux for state management in large web apps**  
  https://www.mapbox.com/blog/redux-for-state-management-in-large-web-apps/  
  Excellent discussion and examples of idiomatic Redux architecture, and how Mapbox applies those approaches to their Mapbox Studio application.
  
- **Reducing our Redux Code with React Apollo**  
  https://dev-blog.apollodata.com/reducing-our-redux-code-with-react-apollo-5091b9de9c2a  
  Peggy Rayzis from MLS shares a detailed look at how they used the React Apollo library and GraphQL to drastically simplify their Redux application
  
- **"I made a diagram of my first React app - do you see anything that's going to bite me?"**  
  https://www.reddit.com/r/reactjs/comments/6ec4dz/i_made_a_diagram_of_the_design_of_my_first_react/  
  A Reddit thread with some excellent discussion about how Apollo and GraphQL fit into the architecture of a Redux application.
  
  
#### Redux Best Practices
  
- **Redux Best Practices**  
  https://medium.com/lexical-labs-engineering/redux-best-practices-64d59775802e  
  Guidelines for tools, component structure, file layout, and async data handling

- **"Redux Best Practices?"**  
  https://www.reddit.com/r/javascript/comments/3p9o0j/redux_best_practices/  
  Short but good discussion on approaches.
  
- **React-Redux Style Guide**  
  https://github.com/ghengeveld/react-redux-styleguide  
  An opinionated style guide for developing applications in ES6+ with React and/or Redux.
  
- **Redux Patterns and Anti-Patterns**  
  https://tech.affirm.com/redux-patterns-and-anti-patterns-7d80ef3d53bc  
  Some tips for using Redux, including use of Immutable.js and structuring for action creators and reducers
  
- **A Simple Naming Convention for Action Creators in Redux**  
  https://decembersoft.com/posts/a-simple-naming-convention-for-action-creators-in-redux-js/  
  Some tips for consistent and understandable naming of actions and action creators
  
- **Our Redux Migration (and 5 tips for adoption in a mature codebase)**  
  https://blog.agolo.com/our-redux-migration-and-5-tips-for-adoption-in-a-mature-codebase-dc62322cb921  
  Lessons learned from migrating to Redux, including choosing a directory structure nd knowing when to use Redux.
  
- **Redux without Profanity**  
  https://tonyhb.gitbooks.io/redux-without-profanity/content/  
  An online book covering best practices and approaches for managing a Redux application
  
- **Taming Large React Applications with Redux**  
  http://slides.com/joelkanzelmeyer/taming-large-redux-apps#/  
  A slideshow with a number of best practices, including tips on using container components, immutable data, normalization, and more.
  
- **Real-World React and Redux**  
  https://dzone.com/articles/real-world-reactjs-and-redux-part-1  
  https://dzone.com/articles/real-world-reactjs-and-redux-part-2  
  A series of articles covering practical architecture lessons learned from building Redux apps, especially regarding use of custom middleware
  
- **Idiomatic Redux: Why Use Action Creators?**  
  http://blog.isquaredsoftware.com/2016/10/idiomatic-redux-why-use-action-creators/  
  Thoughts on why consistent use of action creators is a good practice, as opposed to putting logic inline into components.
  
- **Seven Months into Redux: Two Things My Team Learned Along the Way**  
  https://medium.com/@benipsen/seven-months-into-redux-two-things-my-team-learned-along-the-way-5d979c25ea61  
  Describes the benefits a dev team got from using RxJS streams and using selector functions to derive data.
  
- **Redux anti-pattern: dumb mapStateToProps**  
  http://goshakkk.name/redux-antipattern-mapstatetoprops/  
  An analysis of a somewhat common Redux anti-pattern, where `mapStateToProps` is doing too little, shifting all the domain knowledge into the component that should not be aware of it.

- **Learning and scaling a React/Redux app with a distributed team**  
  https://devblog.xero.com/learning-and-scaling-a-react-redux-app-with-a-distributed-team-e4c397def187  
  Lessons learned from working with a large application with many features, including use of common components, sagas, project structure, and utility libraries
  
- **Redux at Knewton**  
  https://tech.knewton.com/blog/2016/11/redux-at-knewton/  
  Discussion of how Redux helped Knewton improve their app, including dev middleware to catch accidental mutations, normalization to help with caching, and other tradeoffs.
  
- **4 Things for Efficient Redux**  
  https://blog.spacelab.team/4-things-for-efficient-redux-17e87b4cd6cb  
  Suggestions for improved Redux apps based on experience, including using Immutable.js, use of `combineReducers`, listening for actions in multiple reducers, and "aliasing" actions.
  
- **A Year of Development with Redux**  
  https://blog.shakacode.com/a-year-of-development-with-redux-part-i-a5791e124a7d  
  https://blog.shakacode.com/a-year-of-development-with-redux-part-ii-3035ff0b1781  
  Some quick tips for working with Redux, structuring data, and encapsulation of components
  
- **Avoiding False Cause**  
  http://sebinsua.com/avoiding-false-cause/  
  Some high-level general thoughts on cargo-culting, dogma, and best practices, followed by some specific examples of problematic Redux code (unclear reducer state shape, managing "editing" mode data, applying arbitrary value updates)
  
- **Isn't our code just the BEST**  
  https://medium.com/bumpers/isnt-our-code-just-the-best-f028a78f33a9  
  A quirkily-written look at how a dev team rewrote their project using React and Redux, including examples of project structure, component usage, and data normalization
  
- **When to Define Action Creators in Redux**  
  https://daveceddia.com/redux-action-creators/  
  An excellent overview of why action creators exist, why they’re worth using, and when you can skip them
  
- **React Redux Design Lessons Learned**  
  http://www.jeremyzerr.com/sites/default/files/React-Redux-Design-Lessons-Learned.pdf  
  A slideshow that coves some core React and Redux concepts, then discuses how the authors approached designing and developing a timesheet application
  
- **3 Things I Learned about Working with Data in Redux**  
  https://dev.bleacherreport.com/3-things-i-learned-about-working-with-data-in-redux-5fa0d5f89c8b  
  https://www.reddit.com/r/reactjs/comments/5wgh9a/3_things_i_learned_about_working_with_data_in/  
  Good practices for keeping UI state in components, using Higher-Order Components for reusability, and connecting multiple components at lower levels of the application
  
- **Some tips for getting started with Redux**  
  https://medium.com/@dave.draper20/some-tips-for-getting-started-with-redux-187fa949c0e8  
  Some excellent suggestions for getting into Redux, including not using it until you need it, use of `connect`, and making sure to call functions that were passed down as props.
  
- **Quick Redux tips for connecting your React components**  
  https://medium.com/dailyjs/quick-redux-tips-for-connecting-your-react-components-e08da72f5b3  
  A couple quick suggestions for use of `connect`, including connecting lower in the tree and using the `renderCountProp` option
  
- **Dispatch Redux actions as events, not commands!**  
  https://hackernoon.com/dispatch-redux-actions-as-events-not-commands-4de8a92b1ea5  
  Some opinionated thoughts on naming and intent for Redux actions, and why actions should be treated similar to event sourcing
  
- **Don't Overcomplicate Javascript, #0: Redux Action Constants**  
  https://bits.ristic.io/dont-overcomplicate-javascript-0  
  Some thoughts on the pros and cons of defining action constants for reuse in Redux apps, and whether it's a good idea to use libraries to help define those constants.
  
- **Is using a mix of Redux state and React local component state ok?**  
  http://blog.jakoblind.no/2017/02/08/is-using-a-mix-of-redux-state-and-react-local-component-state-ok/  
  A short article expanding on the rules of thumb for when to use Redux state given in the Redux FAQ, with some examples for each rule of thumb.
  
- **Five Tips for Working with Redux in Large Applications**  
  https://medium.com/appnexus-tech/five-tips-for-working-with-redux-in-large-applications-89452af4fdcb  
  Useful suggestions for architecting Redux apps, include use of indices / lookup tables, separation of state, and reuse of common reducer logic.
  
- **React State vs Redux State: When and Why?**  
  https://spin.atomicobject.com/2017/06/07/react-state-vs-redux-state/  
  Some helpful suggestions on how to categorize state into short/medium/long-term, and how to decide where that state should live
  
- **React Native, Redux, and Firebase for experts, by dummies**  
  https://medium.com/rumors/react-native-redux-and-firebase-for-experts-by-dummies-6376becdd5c8  
  The Rumors team describes how they've structured their Redux+Firebase application, and some of the things they ran into
  
- **Redux Architecture Guidelines**  
  http://joeellis.la/redux-architecture/  
  Several useful tips for building a good Redux app, including planning state shape, avoiding nesting, storing plain data, and more.
  
- **Getting started in React with Redux**  
  https://medium.com/@simonhfrost/getting-started-in-react-with-redux-8b2b42b66dee  
  Some quick tips for structuring a Redux app, including several related to organizing state.
  
- **Notes from my first React + Redux project**  
  https://medium.com/audelabs/notes-from-my-first-react-redux-project-3f799beeb140  
  A recap of how the author built a front end for a complex online payment site.  Doesn't really have specific suggestions, but it's well written and serves as a useful description of the common libraries and tools in a React+Redux app and how they fit together.
  
- **Journey of a Thousand Ducks**  
  https://tech.iheart.com/video-journey-of-a-thousand-ducks-f0bb1a9b982c  
  Devs from the iHeartRadio web team describe how they have approached refactoring their React app with homegrown state management to use Redux.
  
- **React+Redux: Tips and Best Practices for Clean, Reliable, & Maintainable Code**  https://speakerdeck.com/goopscoop/react-plus-redux-tips-and-best-practices-for-clean-reliable-and-scalable-code  
  An excellent slideshow with a wide variety of tips and suggestions, including keeping action creators simple and data manipulation in reducers, abstracting away API calls, avoiding spreading props, and more.
  
- **Why not to store objects in Redux**  
  https://medium.com/trainline-engineering/manage-analytics-actions-in-react-67fae61495de  
  Some quick thoughts on why you should keep plain JS objects in your store, instead of class instances.  
  
- **10 Redux tips to scale your dev team**  
  https://blog.matters.tech/10-redux-tips-from-the-trenches-55e06ed1c0a8  
  Some excellent suggestions for helping larger dev teams use Redux successfully, including planning traing/docs reading time, generalizing action types, normalizing state, and more.
  
- **Scaling Redux: Codebase Organization and Organizing State**  
  https://medium.com/@uttamkini/scaling-redux-part-1-codebase-organization-80f978cd8a72  
  https://medium.com/@uttamkini/scaling-redux-part-2-organizing-state-8a1c5e8fffbf  
  Several suggestions for managing a Redux codebase, including use of feature folders / ducks, separating data and UI state in the store, organizing data by API structure, and more.
  
- **Tips for success with React and Redux**  
  https://medium.com/@AlexFaunt/tips-for-success-with-react-and-redux-b782c6b22ff0  
  Advice on how much of your React component tree should be connected to Redux, using non-HTML components to manage things like document titles, consistently using actions for app behavior, and moving app logic out of components.
  
- **Chart the Stock Market with React, Redux, React-Vis, and Socket.io**  
  https://medium.com/@ddcreationstudi/chart-the-stock-market-with-react-redux-react-vis-and-socket-io-18caf312693c  
  An overview of approaches used and lessons learned in writing a real-time stock market charting example app.  Not a tutorial specifically, but some useful ideas for structuring things.
  
- **Growing Pains: Migrating Slack's Desktop App to BrowserView**  
  https://slack.engineering/growing-pains-migrating-slacks-desktop-app-to-browserview-2759690d9c7b  
  The Slack team discusses how they use Redux in an Electron app, including use of the `electron-redux` middleware for syncing actions between Redux stores in different Electron processes and use of `redux-observable` for managing side effects.
  
- **Redux: Architecting and scaling a new web app at the NY Times**  
  https://www.youtube.com/watch?v=lI3IcjFg9Wk  
  A talk from an NY Times developer describing how they scaled a React+Redux app to over a million users per month.
  
- **"React and Redux as a framework"**  
  https://www.reddit.com/r/javascript/comments/747vx1/react_and_redux_as_a_framework/  
  Useful discussion of where "business logic" should live in a Redux app, such as data fetching and transformation.


#### Encapsulation and Reusability

**Related topics**: [Redux Techniques - Selectors](./redux-techniques.md#selectors-and-normalization)

- **Scalable Frontend with Elm or Redux**  
  https://github.com/slorber/scalable-frontend-with-elm-or-redux  
  A repo containing ongoing discussion about ways to handle fully encapsulated reusable chunks of logic and components in Redux, with a number of submitted approaches being compared.

- **Encapsulation in Redux: the Right Way to Write Reusable Components**  
  http://blog.javascripting.com/2016/02/02/encapsulation-in-redux/  
  A look at one way to write encapsulated action handling in Redux

- **How to Reuse Redux Components**  
  https://medium.com/@MattiaManzati/how-to-reuse-redux-components-8acd5b4d376a  
  Discussion of an Elm-inspired approach to wrapping up reusable components and logic

- **Redux and the Elm Architecture**  
  http://salsita.github.io/redux-elm/  
  Redux lacks built-in abstractions for real-world, maintainable, scalable applications. In particular, it is difficult to create and distributed encapsulated, reusable components.  The Elm Architecture clearly addresses some important areas where Redux alone is lacking.
  
- **Scaleable FE with Redux and Elm Architecture**  
  https://medium.com/@hunterbmt/scaleable-fe-with-redux-and-elm-architecture-c6812ed0125e  
  Examples of using Elm-style approaches to writing Redux code
  
- **Encapsulation in Redux: the Right Way to Write Reusable Components**  
  http://blog.javascripting.com/2016/02/02/encapsulation-in-redux/  
  Examples of an Elm-style encapsulation approach
  
- **The Problem with Redux... And How to Fix It**  
  http://blog.javascripting.com/2016/05/21/the-problem-with-redux-and-how-to-fix-it/  
  Demonstration of Redux-Elm, a library that adds composable actions to Redux

- **Applying Redux Reducers to Arrays**  
  http://blog.scottlogic.com/2016/05/19/redux-reducer-arrays.html  
  Looks at one way to implement the classic "multiple instances of one connected component" issue in Redux.
  
- **Redux: Encapsulating the Redux State Tree**  
  http://randycoulman.com//blog/2016/09/13/encapsulating-the-redux-state-tree/  
  http://randycoulman.com/blog/2016/09/20/redux-reducer-selector-asymmetry/  
  http://randycoulman.com/blog/2016/09/27/modular-reducers-and-selectors/  
  http://randycoulman.com/blog/2016/11/29/globalizing-redux-selectors
  A blog series discussing approaches to encapsulating Redux data using selectors and other related approaches
  
- **Redux State Keys - A predictable yet dynamic substate**  
  http://www.robinwieruch.de/redux-state-keys/  
  Description of an approach for dividing up domain-specific state from abstract state, and reusing logic based on those slices.
  
- **The Power of Higher-Order Reducers**  
  http://slides.com/omnidan/hor#/  
  A set of slides discussing how reducers can be layered together to add capabilities

- **Redux Issue #822: "How to create a generic list as a reducer?"**  
  https://github.com/reactjs/redux/issues/822  
  Discussion of various approaches to the "generic list of reusable components" problem
  
- **Redux-Doghouse - Creating React-Redux Components through Scoping**  
  http://engineering.datadoghq.com/redux-doghouse--creating-reusable-react-redux-components-through-scoping/  
  A look at some of the issues involved in trying to write reusable connected components that can be instantiated many times, and how the library they wrote helps solve those problems.
  
- **Redux Stack: Modular Redux Configuration**  
  https://medium.com/@jondot/redux-stack-modular-redux-configuration-ec96412a2262  
  Discussion of a small library that tries to make it easier to hook together different Redux addons.
  
- **Scoped Selectors for Redux Modules**  
  http://www.datchley.name/scoped-selectors-for-redux-modules/  
  A follow-on to Randy Coulman's series on local vs global selectors, discussing tradeoffs in approaches for defining and managing selectors.
  
- **Scaling React and Redux at IOOF**  
  http://www.slideshare.net/VivianFarrell/scaling-react-and-redux-at-ioof  
  A slideshow discussing creation of enterprise-scale Redux apps built with "micro-frontends" that can be composed together, and a look at a "Redux-Subspace" library to help with that
  
- **Structuring Redux Selectors**  
  http://cmichel.io/redux-selectors-structure/  
  Another article on "globalizing" selector functions, with references to the articles by Randy Coulman and Dave Atchley.
  
- **Instance Reducers**  
  http://www.thesoftwaresimpleton.com/blog/2016/12/20/instance-reducers/  
  An interesting approach to the "multiple instances of a connected component" problem.
  
- **How to use Redux on highly scalable Javascript applications?**  
  https://medium.com/@alexmngn/how-to-use-redux-on-highly-scalable-javascript-applications-4e4b8cb5ef38  
  Discussion of ways to structure reducers, selectors, and other logic into reusable features

- **Building a simple Redux library**  
  https://medium.com/@tcclevela/building-a-simple-redux-library-44ce4f004822  
  Looks at important steps to follow when building a Redux addon library: only use middleware if really needed, keep things simple, and encapsulate abstractions.  Shows a particularly good example of using selectors in the library to encapsulate state lookups, and allowing the end user to initialize the selectors so that the data can be mounted anywhere in the state tree the user wants.


#### Variations on Redux Architectures

- **Redux Saga in Action**  
  https://medium.com/@totaldis/redux-saga-in-action-s-f7d11cffa35a  
  Some interesting thoughts on ways to organize the majority of your app's logic using redux-saga
  
- **redux-scuttlebutt; eventually consistent shared state among peers**  
  https://medium.com/@grrowl/redux-scuttlebutt-eventually-consistent-shared-state-among-peers-191d48102079  
  Describes how to use the Redux-Scuttlebutt library to sync actions and updates between multiple instances of a Redux application
  
- **Write Better Redux with redux-module-builder**  
  https://www.fullstackreact.com/articles/better-redux-module-management/  
  Describes how to use the utilities included in the redux-module-builder package to better organize a Redux application
  
- **The Elegance of React, Redux, and Ramda**  
  https://medium.com/javascript-inside/the-elegance-of-react-ebc21a2dcd19  
  Demonstrates ways to use Ramda to compose together React components and Redux behavior
  
- **Extreme Decoupling: React, Redux, Selectors**  
  http://www.thinkloop.com/article/extreme-decoupling-react-redux-selectors/  
  Discusses an API-first approach to splitting apart a Redux app into view, state, and integration layers.
  
- **Using React(-Native) with Redux and Redux Saga**  
  https://medium.com/@marcelschulze/using-react-native-with-redux-and-redux-saga-a-new-proposal-ba71f151546f  
  Description of a decoupled saga-based app structure, similar to that described in "Redux Saga in Action"
  
- **Minimal Redux Setup**  
  https://medium.com/@benevolentNinja/minimal-redux-setup-e6a10fcbcb68  
  Thoughts on using a single reducer and a single "UPDATE" action type
  
- **Scaling your Redux App with Ducks**  
  https://medium.freecodecamp.com/scaling-your-redux-app-with-ducks-6115955638be  
  An overview of a modified version of the "ducks" architecture, with the contents for a given feature in a folder instead of a single file.
  
- **Implementing Redux is tedious. But it doesn't have to be.**  
  https://medium.com/@jeswin/implementing-redux-is-tedious-but-it-doesnt-have-to-be-33702a1fb1dd  
  Describes another "minimal Redux" variation.  Definitely not "idiomatic Redux" usage, but a technically valid implementation.  Some discussion of tradeoffs in the comments.
  
- **How we reduced boilerplate and handled asynchronous actions with Redux**  
  https://blog.algolia.com/how-we-reduced-boilerplate-and-handled-asynchronous-actions-with-redux/  
  A look at conventions that have helped the Algolia team write Redux apps.
  
- **Ducks++: Redux Reducer Bundles**  
  https://medium.com/@DjamelH/ducks-redux-reducer-bundles-44267f080d22  
  Describes an enhancement to the original "ducks" proposal, adding a string constant to help define where the state is kept in the store.
  
- **Isomorphic Redux**  
  https://medium.com/@ellisande_poet/isomorphic-redux-fdaadea13bb5  
  Walks through an implementation of keeping two Redux stores in sync via distributed actions over websockets.
  
- **Introducing FilterBubbler: A WebExtension built using React/Redux**  
  https://hacks.mozilla.org/2017/06/introducing-filterbubbler-a-webextension-built-using-reactredux/  
  Describes how the authors built a browser WebExtension that uses the Redux-WebExt bridge as part of the implementation.
  
- **Scaling Redux for real-life applications**  
  https://hackernoon.com/scaling-redux-for-real-life-applications-be18c731a54d  
  Describes a variation of the "ducks" structure that divides code into "basic concepts" that contain app state and minimal logic, and "container concepts" that contain minimal data and implement most application logic.
  
- **Agile Front End Enterprise Architecture with React, Redux, and Vanilla JS**  
  https://medium.com/shiftgig-blog/agile-front-end-architectures-with-react-redux-and-vanilla-js-23f4e5626e01  
  A description of how ShiftGig organizes their architecture, including a combination of Redux usage with sagas, and traditional OOP approaches like Model classes and Services.
  
- **NgRx: Patterns and Techniques**  
  https://blog.nrwl.io/ngrx-patterns-and-techniques-f46126e2b1e5  
  Describes a variety of patterns and approaches for using the NgRx library (a clone of Redux built with RxJS and commonly used with Angular).  The labels and categories given for side effects approaches, like "content-based decider", "content enricher", etc, can be applied to existing Redux middlewares as well.  
  
- **MVC implemented by React and Causality-Redux**  
  https://medium.com/dailyjs/mvc-implemented-by-react-and-causality-redux-c4125a01e95c  
  https://medium.com/@causality_redux/react-redux-how-to-write-significantly-less-code-c0562ff06d5a  
  A pair of posts discussing how to use the "causality-redux" library to implement an MVC-type architecture on top of React and Redux.
  
- **Connecting React components to a Redux store with render callbacks**  
  https://medium.com/@gott/connecting-react-component-to-redux-store-with-render-callback-53fd044bb42b  
  Demonstrates using the React "render props" pattern to pass down data from a Redux store, rather than using `connect`.
  
- **"Anyone using Redux with a render prop?"**  
  https://twitter.com/threepointone/status/913701233394900992  
  A Twitter thread discussing use of render props as an alternative to `connect`.  Includes a reply by Dan Abramov, who points out that this is how React-Redux originally worked, but it was changed to an HOC to better deal with side effects from state changes.
  
- **The joy of React+Redux with Elixir/OTP**  
  https://limenius.com/elixir-otp-react-redux/  
  Covers building a Redux-based client that receives update messages from an Elixir server.