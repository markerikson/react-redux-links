### React Component Composition

#### Higher-Order Components

- **Mixins Are Dead. Long Live Composition**  
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
  
- **ReactCasts: Higher Order Components**  
  https://youtu.be/LTunyI2Oyzw  
  A screencast that walks through the idea and usage of Higher Order Components
  
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
  
- **Why you should keep your React components pure by using HOCs**  
  https://medium.com/@DjamelH/why-you-should-keep-your-react-components-pure-by-using-hocs-67e5c7f80c81  
  Walks through extracting stateful behavior into an HOC so that it's more reusable and the wrapped components are simpler.
  
- **A gentle introduction to Higher Order Components**  
  https://www.robinwieruch.de/gentle-introduction-higher-order-components/  
  An excellent article demonstrating several ways to use HOCs to manage conditional rendering logic in a reusable way.
  
- **Why Higher Order Components Make Sense**  
  https://medium.com/javascript-inside/why-higher-order-components-make-sense-fe4145b4e305  
  Several examples and some discussion of how HOCs can be used to compose and transform behavior.
  
- **Simple explanation of Higher-Order Components**  
  http://blog.jakoblind.no/simple-explanation-of-higher-order-components-hoc/  
  A short, easy-to-read explanation of the basic concepts and examples of HOCs.
  
- **Real World Higher-Order Components**  
  http://blog.jakoblind.no/real-world-higher-order-components-hocs/  
  Several useful examples of actual HOCs, such as adding a hidden prop, providing toggle functionality, and only showing a component if a feature flag is turned on.
  
- **Composing React components through props transference**  
  https://blog.echobind.com/composing-react-components-through-property-transference-d8bc2dbecef5  
  Quick examples of how to use `React.children.map()` and `React.cloneElement()` to pass props onto arbitrary child elements.
  
- **Higher Order Components in React**  
  https://www.sitepen.com/blog/2017/08/15/higher-order-components-in-react/  
  Shows an example of a React app that needs to authenticate routes, and how a HOC can help handle that in a reusable way.  Also includes example HOCs for A/B-testing features, collecting metrics, and injecting props.
  
- **Save the "zombines": How to add state and lifecycle methods to stateless React components**  
  https://codeburst.io/save-the-zombies-how-to-add-state-and-lifecycle-methods-to-stateless-react-components-1a996513866d  
  A humorously-written look at how to extract state management logic into HOCs.
  
- **HOC in a nutshell**  
  http://coding4real.com/2017/12/23/hoc-nutshell-bonus-example/  
  Describes how HOCs can be used to encapsulate reusable code, and demonstrates HOcs that help with route authentication and work with Redux.
  
- **Composing Higher-Order Components**  
  https://medium.com/@caseymorrisus/react-composing-higher-order-components-hocs-3a5288e78f55  
  Gives examples of common use cases for HOCs, shows some example implementations, and  demonstrates how to compose HOcs together.
  
- **Use Default HOcs for Component Logic**  
  http://arianv.com/post/use-default-hocs-for-component-logic/  
  Demonstrates how default behavior and logic can be put into a HOC to simplify code and enable reuse.
  
- **Higher-Order Components: The Ultimate Guide**  
  https://medium.freecodecamp.org/higher-order-components-the-ultimate-guide-b453a68bb851  
  An extensive look at how HOCs can be used to create composable single-purpose components that encapsulate logic like filtering and sorting.
  

  

#### Render Props/Function As Child

- **Function as Child Components**  
  https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9  
  Explains the "function as a child" technique as an alternative to Higher Order Components
  
- **ReactCasts: Function as Child Component**  
  https://www.youtube.com/watch?v=WE3XAt9P8Ek  
  A screencast that introduces the idea of Functions as Children and demonstrates usage

- **React Patterns - Render Callback**  
  http://leoasis.github.io/posts/2017/03/27/react-patterns-render-callback  
  An explanation of the "render callback" or "function as child" pattern, including concepts and example uses
  
- **Sharing stateful UI logic in React apps using Render Callback components**  
  https://trevordmiller.com/blog/react-render-callback-components  
  Examples of how to use the "render callback" / "function as a child" pattern to extract common logic for reuse.
  
- **Declarative Components in React**  
  https://blog.echobind.com/declarative-components-in-react-b21ced9895b5  
  Demonstrates ways to make reusable flexible components using the "function as a child" pattern. 
  
- **Upgrade your React.js HOC with renderProps**  
  https://reactrocket.com/post/turn-your-hocs-into-render-prop-components/  
  Gives examples of how to adapt HOCs for use with the render props pattern.
  
- **Use a Render Prop!**  
  https://cdb.reacttraining.com/use-a-render-prop-50de598f11ce  
  https://news.ycombinator.com/item?id=15651808  
  Michael Jackson describes why he gave his "Never Write Another HOC" talk, looks at some of the problems with both mixins and HOCs, and how render props can help solve those.  There's some related discussion in the HN comments.
  
- **How to give rendering control to users with prop getters**  
  https://blog.kentcdodds.com/how-to-give-rendering-control-to-users-with-prop-getters-549eaef76acf  
  Kent C Dodds describes how "prop getter" functions can be used with render props to provide more control over how rendering behavior is hooked together.
  
- **Rendering a function with React**  
  https://blog.kentcdodds.com/rendering-a-function-with-react-ca3eaf0751e2  
  Kent C Dodds looks at some unusual use cases for reusing React components, and a possible solution that uses a somewhat hacky approach of marking a function as an iterable.
  
- **Achieving modifiability with your React Components**  
  https://medium.com/@josclovisramrezdelarosa/achieving-modifiability-with-your-react-components-2d99373fae74  
  Looks at a use case for a customizable reporting component, and how render props can be used to enable disabling or overriding parts of the standard report UI.
  

  
  

#### Functional Composition

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
  
- **Destroy All Classes: Turn React Components Inside Out with Functional Programming**  
  https://www.bignerdranch.com/blog/destroy-all-classes-turn-react-components-inside-out-with-functional-programming/  
  Demonstrates progressively refactoring a class component with logic into separate functional components, and then tying them together with Recompose
  
- **A React journey: from vanilla, to type-safe, to monadic**  
  https://medium.com/@giuseppemaggiore/a-react-journey-from-vanilla-to-type-safe-to-monadic-41beaa386910  
  Demonstrates adding TypeScript to a JS React app for type-checking, then using a specialized library called Monadic-React to perform complex and type-safe composition of React components and logic.
  
- **Using Recompose to build higher-order components**  
  https://blog.bigbinary.com/2017/09/12/using-recompose-to-build-higher-order-components.html  
  Examples of refactoring components using the Recompose library, including use of `branch` and `compose`.
  
- **Curry away in React**  
  https://hackernoon.com/curry-away-in-react-7c4ed110c65a  
  Examples of using currying to create reusable callback functions that can be passed to child components.
  
- **Killing Switch Statements in React with the Strategy Pattern**  
  https://glcheetham.name/2016/05/20/killing-switch-statements-in-react-with-the-strategy-pattern/  
   Describes why the author dislikes switch statements for determining which component to render, and gives an alternative using functions that return the right component type.
  
- **Functional Approach to Higher Order Components and Recompose**  
  https://codebrahma.com/functional-approach-higher-order-components-recompose/  
  Discusses approaches for composing components using functions
  
  

#### Comparing Composition Approaches

- **Functions as Child Components and Higher Order Components**  
  http://rea.tech/functions-as-child-components-and-higher-order-components/  
  Comparisons and examples for these two component patterns
  
- **Simplifying life with React render callbacks**  
  https://medium.com/@adamrackis/simplifying-life-with-react-render-callbacks-cb37d58e55  
  An overview of several different ways to wrap up components, including cloning children, HOCs, and render callbacks.
  
- **"HOCs vs render callbacks / function-as-child"**  
  https://twitter.com/mjackson/status/890725796117176321  
  https://twitter.com/acdlite/status/890727843302301700  
  A short but interesting Twitter thread with some comments from Michael Jackson, Andrew Clark, and others, on the mental differences between using HOCs and render callbacks.

- **Never Write Another HoC**  
  https://youtu.be/BcVAq3YFiuc  
  Michael Jackson demonstrating that a component with render prop can do anything a HOC can do, and more.
  
 - **React Composition Patterns from the Ground Up**  
   https://hackernoon.com/react-composition-patterns-from-the-ground-up-8401aaad93d7  
   Comparison of patterns such as Lifting State, Higher-Order Components, Render Callbacks, and "Renderless" State Providers, and how they relate to React's component model.
 
- **Solving the problems of Higher Order Components without throwing the baby out with the bathwater**  
  https://hackernoon.com/solving-the-problems-of-higher-order-components-without-throwing-the-baby-out-with-the-bathwater-40ddc72df5aa  
  A response to some criticisms of HOCs, such as indirection and naming collisions, showing some ways to compose HOCs to avoid the issues.
  
- **Randomness in React Props**  
  https://medium.com/@joshuawcomeau/randomness-in-react-props-3929c1669f8b  
  Demonstrates several approaches to structuring logic for generating values and passing them to children, including initialization in a constructor, creating a wrapper component, and using a function-as-a-child.
  
- **Simplifying life with React render callbacks**  
  https://medium.com/@adamrackis/simplifying-life-with-react-render-callbacks-cb37d58e55  
  Compares several approaches for passing data from a parent component directly to a child, including cloning children, using a HOC, and using render props.
  
- **React Developer's Everyday Struggle - Extending Big Applications**  
  https://blog.callstack.io/react-developers-everyday-struggle-extending-big-applications-84ec4e62e2ad  
  Looks at different possible solutions to handling form inputs and validation logic, including existing form libs, a validation HOC, and a function-as-children approach.
  
- **Seven patterns by example: the many ways to `type="radio"` in React**  
  https://techblog.commercetools.com/seven-patterns-by-example-the-many-ways-to-type-radio-in-react-bfe14322bb6f  
  Compares multiple approaches for rendering and controlling a group of radio inputs, including passing a list of options as an array, creating a RadioOption component, compound components, context, function as a child, prop getters, and dynamic RadioOption creation.
  
- **How "Controllable" React components maximize reusability**  
  https://medium.com/myheritage-engineering/how-controllable-react-components-maximize-reusability-86e3d233fa8e  
  Gives examples of uncontrolled, controlled, and controllable components, looks at pros and cons of those approaches, and describes how controllable components improve reusability.
  
- **Composing Reusable Components in React**  
  https://medium.com/@adamrackis/composing-reusable-components-in-react-de44d862fe5a  
  Walks through the implementation of a reusable accordion component that supports several modes of operation, and demonstrates several useful techniques for composition.