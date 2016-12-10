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