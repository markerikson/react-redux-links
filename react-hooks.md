### React Hooks

> Hooks were an experimental proposal, available in an alpha release up until the [release of React 16.8](https://reactjs.org/blog/2019/02/06/react-v16.8.0.html). They allow use of state and other React features like lifecycle events from within a functional component rather than a class. Hooks also allow you to share reusable stateful logic between components. Hooks are JavaScript functions, the [rules of Hooks](https://reactjs.org/docs/hooks-rules.html) should be understood and are covered in the React Docs.

#### Official Resources

- **React Docs: Hooks (Proposal)**  
  https://reactjs.org/docs/hooks-intro.html  
  The main resource for learning hooks.  Includes an intro with motivation, tutorials on `useState` and `useEffect`, discussion of custom hooks, the full hooks API reference, and an in-depth FAQ.  **Read the Hooks docs before anything else!**
  
- **ReactConf 2018: React Today and Tomorrow**  
  https://www.youtube.com/watch?v=dpw9EHDh2bM  
  Sophie Alpert and Dan Abramov's talk unveiling hooks, live at ReactConf 2018.
  
- **Making Sense of React Hooks**  
  https://dev.to/dan_abramov/making-sense-of-react-hooks-2eib  
  Dan Abramov provides a lot of additional context around the hooks proposal, including potential benefits like co-locating related logic, examples of how to use hooks, whether they are "magic", and more.  **Also a must-read.**
  
#### Hooks Tutorials

- **A Simple Intro to React Hooks**  
  https://daveceddia.com/intro-to-hooks/  
  Dave Ceddia continues his excellent easy-to-read React tutorials with a friendly intro to the basics of the `useState` hook.  Also see [the other articles in his hooks intro series](https://daveceddia.com/archives/) as well.
  
- **What are React Hooks?**  
  https://www.robinwieruch.de/react-hooks/  
  An excellent article by Robin Wieruch.  Includes examples of problems that hooks can help solve, discussion of how the changes affect React overall, and multiple examples for the `useState` and `useEffect` hooks.
  
- **Everything you need to know about React Hooks**  
  https://dev.to/vcarl/everything-you-need-to-know-about-react-hooks-doh  
  A thorough post from Carl Vitullo that digs into the potential use cases of all of the built-in hooks.  Definitely worth reading once you've gotten your head around the basic ideas.

- **An Introduction to Hooks in React**  
  https://www.fullstackreact.com/articles/an-introduction-to-hooks-in-react/#community-reaction-to-hooks  
  An extensive article with numerous examples of `useState`, `useEffect`, and `useContext`.  Also covers `useRef`, custom hooks, writing tests for hooks, and some community reactions.

- **How to Use Basic React Hooks for Context**  
  https://www.telerik.com/blogs/how-to-use-basic-react-hooks-for-context  
  After tackling the basics of `useState` and `useEffect` we can see how the React Context API is used in the context of React Hooks.

- **Everything You Need to Create a Custom React Hook**  
  https://www.telerik.com/blogs/everything-you-need-to-create-a-custom-react-hook  
  An article focusing on the basic rules for creating simple custom React Hooks from a beginners level perspective.

- **How to Use Basic React Hooks for Reducers**  
  https://www.telerik.com/blogs/how-to-use-basic-react-hooks-for-reducers  
  Understand how to make the jump between `useState` and `useReducer` while building a simple Todo application.

#### Understanding Hooks Internals

- **React Hooks Demystified**  
  https://dev.to/kayis/react-hooks-demystified-2af6  
  Implements a tiny fake version of React, then illustrates how hooks are "just" implemented with some global variables, like an array to track which hooks were used in the current function component.
  
- **React hooks: not magic, just arrays**  
  https://medium.com/@ryardley/react-hooks-not-magic-just-arrays-cd4f1857236e  
  Describes how the "rules of hooks" are all about React's use of arrays (or linked lists) internally, with diagrams to illustrate how the behavior is implemented.
  
- **Under the Hood of React's hooks system**  
  https://medium.com/the-guild/under-the-hood-of-reacts-hooks-system-eb59638c9dba  
  A well-written explanation of how hooks work internally, with some useful diagrams and snippets of the relevant React implementation code.
  
- **React RFC #68: React Hooks**  
  https://github.com/reactjs/rfcs/pull/68  
  The official RFC announcing hooks.  There's hundreds of comments from the community debating various pros and cons of the API design.  Probably not worth reading the entire thread, but some interesting thoughts in there.

- **Why React Hooks, and how did we even get here?**  
  https://medium.freecodecamp.org/why-react-hooks-and-how-did-we-even-get-here-aa5ed5dc96af  
  This article explores how React Hooks have learned from the trade-offs of mixins, HOC's, and render props bringing us new ways to create contained, composable behaviors consumable in a flat and declarative manner.