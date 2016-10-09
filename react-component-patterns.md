### React Component Patterns

#### Terms and Concepts

- **React Patterns**  
  http://reactpatterns.com/  
  An excellent list of common patterns for structuring React components, with examples
  
- **React Component Jargon as of August 2016**  
  https://medium.com/@arcomito/react-component-jargon-as-of-august-2016-28451d8ceb1d  
  A very useful glossary of widely-used terms describing React components
  
- **Functional Components vs. Stateless Functional Components vs. Stateless Components**  
  https://tylermcginnis.com/functional-components-vs-stateless-functional-components-vs-stateless-components-630fdfd90c9c  
  Clarifies the meaning of the terms, which are often used in overlapping ways.
  
- **How to use Classes and Sleep at Night**  
  https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4  
  Some pragmatic opinions on when and how to use the ES6 "class" keyword, particularly in relation to React components.
  
  
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
  
  
#### Higher-Order Components

- **Mixins Are Dead.  Long Live Composition**  
  https://medium.com/@dan_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750  
  A look at some of the issues with using mixins, and reasons why higher-order components are (usually) an improvement.
  
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
  
  
#### Other Component Patterns

- **Dynamically Rendering React Components**  
  https://wail.es/dynamically-rendering-react-components/  
  Examples of how to dynamically determine which React component to render
  
- **The React Controller View Pattern**  
  http://blog.andrewray.me/the-reactjs-controller-view-pattern/  
  Describes using top-level components to hold state and pass it to children as props
  
- **Function as Child Components**  
  https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9  
  Explains the "function as a child" technique as an alternative to Higher Order Components
  
- **Functional React Series - Part 1: Get your App outta my Component**  
  https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25  
  Part 1 in a series about writing React applications by treating components as functions, not templates.