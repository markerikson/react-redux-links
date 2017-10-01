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
   https://medium.com/alexkrolick/react-composition-patterns-from-the-ground-up-8401aaad93d7  
   Comparison of patterns such as Lifting State, Higher-Order Components, Render Callbacks, and "Renderless" State Providers, and how they relate to React's component model.
 
