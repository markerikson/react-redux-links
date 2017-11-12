### Static Typing


#### Pros and Cons

- **The Shocking Secret about Static Types / You Might Not Need Typescript (or Static Types)**  
  https://medium.com/javascript-scene/the-shocking-secret-about-static-types-514d39bf30a3  
  https://medium.com/javascript-scene/you-might-not-need-typescript-or-static-types-aa7cb670a77b  Eric Elliott argues against use of static types in Javascript, on the grounds that the tradeoffs aren't worth it and that TDD and code review provide more benefit in reducing bugs.
  
- **Why use static types in Javascript?**  
  https://dev.to/iampeekay/why-use-static-types-in-javascript-part-1  
  Part 1 of a 4-part series on static typing: intro to Flow syntax, advantages and disadvantages of static types, and whether they should be used with Javascript.
  


#### React PropTypes

- **React Docs: Typechecking With PropTypes**  
  https://facebook.github.io/react/docs/typechecking-with-proptypes.html  
  The official reference docs for PropTypes
  
- **What are PropTypes?**  
  https://themeteorchef.com/snippets/what-are-proptypes/  
  An introduction to React's PropTypes feature and how it can help create more predictable APIs for components.
  
- **React PropTypes & Flow types cheat sheet**  
  https://medium.com/@chenglou/react-proptypes-flow-types-cheat-sheet-ed80f8e1383d  
  Some quick comparisons and gotchas between the two type declaration approaches

- **Accessing React PropTypes Meta-data**  
  https://medium.com/@nunogrilopinheiro/accessing-react-proptypes-meta-data-45b3465abda7  
  A look at how to access PropTypes info at runtime using various tooling
  
- **React: Validating Children**  
  http://www.mattzabriskie.com/blog/react-validating-children  
  Examples of using PropTypes to enforce what children can be passed to a component


#### TypeScript

- **TypeScript: the Missing Introduction**  
  https://toddmotto.com/typescript-the-missing-introduction  
  An introduction to TypeScript's concepts, with explanations of a number of terms related to compilers and static typing.
  
- **TypeScript Deep Dive**  
  https://basarat.gitbooks.io/typescript/content/  
  An online book that digs into numerous TypeScript topics
  
- **Immutable.js Records in TypeScript**  
  https://spin.atomicobject.com/2016/11/30/immutable-js-records-in-typescript/  
  Examples of setting up typing for custom classes based on Immutable.js's Record class.

- **Strongly Typing Injected React Props**  
  https://medium.com/@prashaantt/strongly-typing-injected-react-props-635a6828acaf  
  A demonstration of using TypeScript to define prop types for a React component, and enforcing behavior based on that.

- **Hybrid Types in TypeScript**  
  https://turbomack.github.io/posts/2016-12-07-hybrid-types-in-typescript.html  
  Examples of adding type checking to some dynamic code that uses d3 for visualization.
  
- **A Typed pluck: exploring TypeScript 2.1's mapped types**  
  https://medium.com/@danvdk/a-typed-pluck-exploring-typescript-2-1s-mapped-types-c15f72bf4ca8  
  Detailed explanation of how the "mapped types" feature in TS 2.1 can be used to add typing to functions that map over data
  
- **Hello World with Webpack, TypeScript, and React**  
  https://www.bennadel.com/blog/3293-hello-world-with-webpack-and-typescript-2-3-4-in-react-15-6-1.htm  
  An example of setting up a project that uses Webpack, React, an TypeScript together.
  
- **Yet Another TypeScript Book**  
  https://pagalvin.gitbooks.io/yet-another-typescript-book/content/  
  A casual introduction to the main features of TypeScript.


#### Flow Tutorials

- **The Fundamentals of Flow in 10-ish Minutes**  
  https://www.youtube.com/watch?v=xWMuAUbXcdQ  
  A short presentation that looks at what Flow is, benefits, and how to use it
  
- **Go with the Flow - A Static Type Checking Tool for Javascript**  
  https://www.theodo.fr/blog/2016/11/go-with-the-flow-a-static-type-checking-tool-for-javascript/  
  A quick introduction to Flow, its usage, and some comparisons with Typescript.

- **Setting up Flow when you've already got Babel in place**  
  https://medium.freecodecamp.com/using-flow-with-babel-c04fdca8d14d  
  Instructions for integrating Flow into an existing project
  
- **Eradicate Runtime Errors in React with Flow**  
  http://technologyadvice.github.io/eradicate-runtime-errors-in-react-with-flow/  
  An introduction to Flow's benefits in a project, and how to use it
  
- **Flow Guide: The Definitive Guide for using Flow**  
  https://github.com/ryyppy/flow-guide  
  Instructions on setting up Flow, a style guide, and links to further info
  
- **Why Use Flow?**  
  https://blog.aria.ai/post/why-use-flow/  
  A look at the concepts of static typing and type inference, examples of using Flow to add type declarations to code, and pointers to further information on Flow.
  
- **Why You Need Types**  
  http://jaysoo.ca/2016/08/23/why-you-need-types/  
  Some thoughts on how static typing can help development, with examples using Flow.

- **Better docs and static analysis**  
  https://blog.scottnonnenberg.com/better-docs-and-static-analysis/  
  A walk through setting up Flow, some possible problems you might encounter, and ways to customize and improve the typing process.
  
- **Getting Started with Flow and Webpack**  
  https://blog.iansinnott.com/getting-started-with-flow-and-webpack/  
  Walks through the process for adding Flow to an existing Webpack+Babel project.
  
- **Flow type cheat sheet**  
  http://www.saltycrane.com/blog/2016/06/flow-type-cheat-sheet/  
  A comprehensive list of built-in Flow types
  
- **Notes on Flow type checking in Javascript**  
  https://davidxmoody.com/2016/notes-on-flow-type-checking-in-javascript/  
  A variety of quick notes and snippets of Flow syntax for various use cases
  
- **Flow Fundamentals for JavaScript Developers**  
  https://gist.github.com/busypeoples/61e83a1becc9ee9d498e0db324fc641b  
  A JS file in a gist that provides a commented walkthrough of Flow concepts and syntax.


#### React, Redux, and Static Types

- **Checking React and Redux Code with Flow**  
  http://djcordhose.github.io/react-intro-live-coding/2016_jsunconf.html#/  
  A slideshow that shows the basics of adding type information to Redux-based code 
  
- **Using Redux with Flow**  
  http://frantic.im/using-redux-with-flow  
  Covers how to use Flow typing with Redux

- **Type Checking with Flow in React + Redux**  
  http://www.robinwieruch.de/the-soundcloud-client-in-react-redux-flow/  
  Demonstrates setting up static typing with an existing project
  
- **Redux Flow Tutorial**  
  http://dchambers.github.io/articles/redux-flow-tutorial/  
  Covers how to set up Flow for type-checking a Redux application

- **Typed Redux**  
  https://blog.callstack.io/typed-redux-2aa8bff926ff  
  Examples of how to use Flow to add typing to Redux apps
  
- **Tagged Unions, React, and Redux**  
  https://hackernoon.com/tagged-unions-react-and-redux-55e262e4d0ea  
  Examples of using Flow union types to define component props
  
- **Typing React Components**  
  https://datarockets.com/blog/typing-react-components  
  Examples of migrating from React PropTypes to Flow, as well as typing Redux usage 
  
- **Type-Checking React and Redux with Flow**  
  https://blog.callstack.io/type-checking-react-and-redux-thunk-with-flow-part-1-ad12de935c36  
  https://blog.callstack.io/type-checking-react-and-redux-thunk-with-flow-part-2-206ce5f6e705  
  Examples of how to define Flow types for React components and Redux functions
  
- **How the Debugger got into the Flow**  
  http://jasonlaster.github.io/devtools/js/2017/01/20/typing-the-debugger.html  
  A look at how the Firefox DevTools team uses Flow to help type their React and Redux code for improved maintainability
  
- **Typed Redux: Redux Revisited**  
  https://www.ajostrow.me/articles/redux-revisited  
  A follow-up to an earlier post by the author, giving an updated set of thoughts on use of TypeScript with Redux
  
- **Type-safe Flux Standard Actions in React**  
  https://www.triplet.fi/blog/type-safe-flux-standard-actions-fsa-in-react-using-typescript-fsa/  
  Describes the "Flux Standard Action" concept, and how the TypeScript FSA library can be used to help generate FSAs in a type-safe way.
  
- **Type-Safe Asynchronous Actions (Redux-Thunk) Using TypeScript FSA**  
  https://www.triplet.fi/blog/type-safe-asynchronous-actions-redux-thunk-using-typescript-fsa/  
  Examples of how to generate and use type-safe async actions in TypeScript

- **React & Redux in TypeScript - Static Typing Guide**  
  https://github.com/piotrwitek/react-redux-typescript-guide  
  A comprehensive guide to static typing "React & Redux" apps using TypeScript
  
- **Porting a React and Redux Application to TypeScript**  
  https://bytesized.xyz/react-redux-typescript/  
  Demonstrates porting an existing React+Redux sample app to use TypeScript
  
- **React Higher Order Components in TypeScript made simple**  
  https://dev.to/danhomola/react-higher-order-components-in-typescript-made-simple  
  Demonstrates how to extract an HOC and properly define types for various groups of props
  
- **React, Redux, and TypeScript: Typed Connect**  
  https://www.silviogutierrez.com/blog/react-redux-and-typescript-typed-connect/  
  Discusses a simpler set of typings for the `connect` function and how to use them with React.
  
- **A New Redux Action Pattern for TypeScript 2.4+**  
  https://spin.atomicobject.com/2017/07/24/redux-action-pattern-typescript/  
  Describes how to use the new features in TS 2.4, such as string enums, to simplify defining types for Redux actions.
  
- **Best Practices for Flow Typing React Components**  
  https://building.coursera.org/blog/2017/06/01/best-practices-for-flow-typing-react-components/  Several useful suggestions and examples for using Flow types with React components.
  
- **React Higher-Order Components using TypeScript**  
  https://www.triplet.fi/blog/react-higher-order-components-hoc-using-typescript/  
  Examples of how to properly write React HOCs in TypeScript, including adding types.
  
- **React and TypeScript: The Basics**  
  https://spin.atomicobject.com/2017/10/31/react-typescript-basics/  
  Covers important questions you might have when using React and TypeScript together, including approaches for project setup, adding NPM packages, typing React components, using Redux, and more.
  
- **Typing Higher-Order Components in Recompose with Flow**  
  https://medium.com/flow-type/flow-support-in-recompose-1b76f58f4cfc  
  Describes some of the work needed to add Flow types for the Recompose library, and how to use Recompose, Flow, and React together.
  
- **Type-safe React + Redux: Eliminating the 'any' type**  
  https://medium.com/@joeldalley/type-safe-react-redux-eliminating-the-any-type-dad21ebd3cd5  
  Examples of declaring types for data modeling, Redux actions and reducers, Redux-Observable epics, and React components.
  
- **Redux and Flow-type - getting the maximum benefit from the fewest key strokes**  https://hackernoon.com/redux-flow-type-getting-the-maximum-benefit-from-the-fewest-key-strokes-5c006c54ec87  
  Discussion of how Flow's type inference can be used to reduce duplication of type declarations for actions.
  
- **How to Reduce Action Boilerplate**  
  https://blog.angularindepth.com/how-to-reduce-action-boilerplate-90dc3d389e2b  
  Looks at how TypeScript is normally used with Redux, including "narrowing" actions with type guards and discriminated unions, and looks at ways different libraries use narrowing to help generate actions in a type-safe way.
  


#### Advancing Typing Techniques

- **Runtime Introspection of Flow Types**  
  https://medium.com/@joe_stant/runtime-introspection-of-flow-types-ddb7e5b042a5  
  A look at some ways to potentially use Flow types for further analysis using various tooling

- **Phantom Types with Flow**  
  https://medium.com/@gcanti/phantom-types-with-flow-828aff73232b  
  Description of an advanced technique for tracking data flow using types

- **Exhaustive switch in Flow**  
  https://ouicar.github.io/2016/08/08/exhaustive-switch.html  
  A trick to help catch missing case errors in switch statements.
  
- **Flow Cookbook**  
  http://sitr.us/2016/12/20/flow-cookbook.html  
  Assorted useful techniques for using Flow types
  
- **Secret Flow Types**  
  https://medium.com/@raxwunter/secret-flow-types-86b2ebb30951  
  A list of "advanced" Flow type declarations, such as Keys, Diff, and Shape.
  

#### Tool Comparisons

- **Flow as a replacement for PropTypes**  
  http://blog.rstankov.com/flow-as-replacement-for-proptype/  
  Describes some limitations of PropTypes, and how Flow can help solve those

- **Flow vs TypeScript**  
  http://djcordhose.github.io/flow-vs-typescript/flow-typescript-2.html#/  
  A comparison of the features, goals, and usage of both type systems
  
- **Typescript vs Flow**  
  https://gist.github.com/voltrevo/ecb5b7292707d29b13ae453ae0b529d9  
  A comparison of common features, advantages in either system, missing features, and other aspects.
  
- **TypeScript vs Flow**  
  https://github.com/niieani/typescript-vs-flowtype  
  An in-depth, unbiased comparison of differences and similarities between TypeScript and Flow
  
- **TypeScript vs Flow**  
  https://blog.mariusschulz.com/2017/01/13/typescript-vs-flow  
  Some quick thoughts on both Flow and TS being "non-standard JS", with good discussion in the comments.
  
- **TypeScript, Flow, and the Importance of Toolchains over Tools**  
  https://dzone.com/articles/typescript-flow-and-the-importance-of-toolchains-o  
  Some thoughts on why type checkers are important, how they differ, and what considerations go into selecting a type checking tool
  
- **Refactoring 30000 Lines of JS with types**  
  https://www.reaktor.com/blog/refactoring-30000-lines-js-types/  
  A description of the Reaktor team's approach to adding types to their project, their experience with both Typescript and Flow, and why they chose Typescript.
  
- **How we migrated a 200K+ LOC Project to TypeScript**  
  https://hashnode.com/post/how-we-migrated-a-200k-loc-project-to-typescript-and-survived-to-tell-the-story-ciyzhikcc0001y253w00n11yb  
  The Coherent Labs team discusses the tradeoffs in using static typing for JS code, why they chose TypeScript, and how they approached migrating their codebase to TypeScript.
  
- **Why I was looking forward to Flow, and then I wasn't**  
  https://medium.com/@ckoster22/why-i-was-looking-forward-to-flow-and-then-i-wasnt-7c0a86f2d603  
  Some useful thoughts on the tradeoffs involved in using Flow
  
- **Flow: What's the verdict?**  
  https://amplitude.engineering/flow-whats-the-verdict-9a458ecde27f  
  Thoughts on some pros and cons of using FLow, including dealing with code that doesn't have types, and several specific use cases the Amplitude team has run into.
  
- **Going Statically Typed with Flow**  
  https://labs.contactually.com/going-statically-typed-with-flow-72626ed86cec  
  Some thoughts on why Contactually opted to use Flow for their React+Redux app, including ease of integrating Flow into an existing app.
  
- **Typed JavaScript with TypeScript, Flow, and Elm**  
  http://djcordhose.github.io/flow-vs-typescript/elm-flow-typescript.html#/  
  A slideshow that discusses the benefits of using type systems, and looks at how TS, Flow, and Elm compare in several aspects.
  
- **Flow and TypeScript**  
  https://engineering.tumblr.com/post/165261504692/flow-and-typescript  
  The Tumblr engineering team discusses their experience comparing Flow and TS, and why they opted to use TS.