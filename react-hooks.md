### React Hooks


#### Official Resources

- **React Docs: Hooks**  
  https://reactjs.org/docs/hooks-intro.html  
  The main resource for learning hooks.  Includes an intro with motivation, tutorials on `useState` and `useEffect`, discussion of custom hooks, the full hooks API reference, and an in-depth FAQ.  **Read the hooks docs first before looking at anything else!**
  
- **ReactConf 2018: React Today and Tomorrow**  
  https://www.youtube.com/watch?v=dpw9EHDh2bM  
  Sophie Alpert and Dan Abramov's talk unveiling hooks, live at ReactConf 2018.

- **A Complete Guide to `useEffect`**  
  https://overreacted.io/a-complete-guide-to-useeffect/  
  An incredibly detailed deep dive by Dan Abramov into the mindset of using hooks correctly.  Covers the relationship between class lifecycles and hooks, how to work with the dependencies array, dealing with closures and stale data, and much much more. This is required reading for anyone using hooks.
  
- **Making Sense of React Hooks**  
  https://dev.to/dan_abramov/making-sense-of-react-hooks-2eib  
  Dan Abramov provides a lot of additional context around the hooks proposal, including potential benefits like co-locating related logic, examples of how to use hooks, whether they are "magic", and more.  **Also a must-read.**
  
  
#### Hooks Tutorials

- **Why React Hooks?**  
  https://tylermcginnis.com/why-react-hooks/  
  A great introduction to hooks by Tyler McGinnis, with a focus on "why do these exist, and what problems do they solve?". 

- **A Simple Intro to React Hooks**  
  https://daveceddia.com/intro-to-hooks/  
  https://daveceddia.com/usestate-hook-examples/  
  https://daveceddia.com/usereducer-hook-examples/  
  https://daveceddia.com/useeffect-hook-examples/  
  https://daveceddia.com/usecontext-hook/  
  Dave Ceddia continues his excellent easy-to-read React tutorials with a friendly intro to the basics of several hooks.
  
- **What are React Hooks?**  
  https://www.robinwieruch.de/react-hooks/  
  https://www.robinwieruch.de/react-hooks-fetch-data/  
  An excellent article by Robin Wieruch.  Includes examples of problems that hooks can help solve, discussion of how the changes affect React overall, and multiple examples for the `useState` and `useEffect` hooks.  A follow-up post discusses how to handle data fetching.
  
- **Everything you need to know about React Hooks**  
  https://dev.to/vcarl/everything-you-need-to-know-about-react-hooks-doh  
  A thorough post from Carl Vitullo that digs into the potential use cases of all of the built-in hooks.  Definitely worth reading once you've gotten your head around the basic ideas.

- **An Introduction to Hooks in React**  
  https://www.fullstackreact.com/articles/an-introduction-to-hooks-in-react/#community-reaction-to-hooks  
  An extensive article with numerous examples of `useState`, `useEffect`, and `useContext`.  Also covers `useRef`, custom hooks, writing tests for hooks, and some community reactions.


#### Understanding Hooks Concepts

- **React Hooks Demystified**  
  https://dev.to/kayis/react-hooks-demystified-2af6  
  Implements a tiny fake version of React, then illustrates how hooks are "just" implemented with some global variables, like an array to track which hooks were used in the current function component.
  
- **React hooks: not magic, just arrays**  
  https://medium.com/@ryardley/react-hooks-not-magic-just-arrays-cd4f1857236e  
  Describes how the "rules of hooks" are all about React's use of arrays (or linked lists) internally, with diagrams to illustrate how the behavior is implemented.
  
- **Getting Closure on Hooks**  
  https://www.youtube.com/watch?v=KJP1E-Y-xyo  
  https://www.swyx.io/getting-closure-on-hooks/  
  Shawn Wang's excellent talk and post that shows how hooks work by building a mini-React with hooks in just a few lines of code
  
- **Why React Hooks, and how did we even get here?**  
  https://medium.freecodecamp.org/why-react-hooks-and-how-did-we-even-get-here-aa5ed5dc96af  
  A look back at earlier common patterns for reusing React logic (mixins, higher-order components, and render props), some of their strengths and weaknesses, and how hooks improve on those patterns.
  
- **Under the Hood of React's hooks system**  
  https://medium.com/the-guild/under-the-hood-of-reacts-hooks-system-eb59638c9dba  
  A well-written explanation of how hooks work internally, with some useful diagrams and snippets of the relevant React implementation code.

- **React RFC #68: React Hooks**  
  https://github.com/reactjs/rfcs/pull/68  
  The official RFC announcing hooks.  There's hundreds of comments from the community debating various pros and cons of the API design.  Probably not worth reading the entire thread, but some interesting thoughts in there.
