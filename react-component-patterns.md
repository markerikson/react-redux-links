### React Component Patterns

**Related topics**:
- [Thinking in React](./thinking-in-react-and-flux.md): Articles discussing ways to think about React applications and component structure

#### Terms and Concepts

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
  
- **Ownership and Children in React**  
  http://ctheu.com/2015/02/10/ownership-and-children-in-reactjs/  
  Discusses the difference between "parent" and "owner" relationships, and what the "children" prop can look like.
  
  
#### Component Categories

- **Presentational and Container Components**  
  https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0  
  Dan Abramov's foundational article on classifying components based on intent and behavior.  A must-read for anyone using React.
  
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
  
  
#### Other Component Patterns

- **Dynamically Rendering React Components**  
  https://wail.es/dynamically-rendering-react-components/  
  Examples of how to dynamically determine which React component to render
  
- **The React Controller View Pattern**  
  http://blog.andrewray.me/the-reactjs-controller-view-pattern/  
  Describes using top-level components to hold state and pass it to children as props
  
- **Functional React Series - Part 1: Get your App outta my Component**  
  https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25  
  Part 1 in a series about writing React applications by treating components as functions, not templates.
  
- **Make Your React Components Pretty**  
  https://medium.com/walmartlabs/make-your-react-components-pretty-a1ae4ec0f56e  
  Techniques for making your components easier to read, including using functional components, using JSX spread for props, and use of destructuring.
  
- **Component Factories in React.js**  
  https://github.com/szabototo89/create-it/blob/master/docs/article-full.md  
  A variation on Dependency Injection for React components
  
- **Functional Components with React stateless functions and Ramda**  
  https://medium.com/@mirkomariani/functional-components-with-react-stateless-functions-and-ramda-e83e54fcd86b  
  Examples of using Ramda functions to compose together components
  
- **"What is the ideal way to pass data to a callback prop?**  
  https://gist.github.com/jazlalli/fdee443405680f96d19211daa15d1d38  
  Discussion and examples of various ways to pass data to callbacks between children and parents