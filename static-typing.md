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
  
- **Flow type cheat sheet**  
  http://www.saltycrane.com/blog/2016/06/flow-type-cheat-sheet/  
  A comprehensive list of built-in Flow types


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
  
