# React/Redux Links
Curated tutorial and resource links I've collected on React, Redux, ES6, and more, meant to be a collection of high-quality articles and resources for someone who wants to learn about the React-Redux ecosystem, as well as a source for quality information on advanced topics and techniques.  Not quite "awesome", but hopefully useful as a starting point I can give to others.  Suggestions welcome.

Another important resource is the **Reactiflux community on Discord**, which has chat channels dedicated to discussion of React, Redux, and other related technologies.  There's always a number of people hanging out and answering questions, and it's a great place to ask questions and learn.  The invite link is at **https://www.reactiflux.com**.

You might also want to check out my categorized list of Redux-related addons, libraries, and utilities, at [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links).  Also see [Community Resources](community-resources.md) for links to other links lists, podcasts, and email newsletters.  Finally, I also keep a dev blog at [blog.isquaredsoftware.com](http://blog.isquaredsoftware.com), where I write about React, Redux, Webpack, and more.


## Table of Contents

#### Getting Started
- [Basic Concepts and Overviews](./basic-concepts.md)
- [Community Resources](./community-resources.md)
- [Javascript Resources](./javascript-resources.md)
- [Git Resources and Tutorials](./git-resources.md)
- [Node.js and NPM](./node-js-and-npm.md)
- [Webpack Tutorials](./webpack-tutorials.md)
- [Boilerplates and Starter Kits](./boilerplates-and-starter-kits.md)

#### Basic Tutorials
- [ES6 Features and Samples](./es6-features.md)
- [React Tutorials](./react-tutorials.md)
- [Flux Tutorials](./flux-tutorials.md)
- [Redux Tutorials](./redux-tutorials.md)
- [MobX Tutorials](./mobx-tutorials.md)

#### Intermediate Concepts

- [Using React with ES6](./using-react-with-es6.md)
- [Functional Programming](./functional-programming.md)
- [Immutable Data](./immutable-data.md)
- [React/Redux Testing](./react-redux-testing.md)
- [React Native](./react-native.md)
- [React Tips and Techniques](./react-techniques.md)

#### Advanced Topics

- **Architecture and Structure**
  - [Project Structure](./project-structure.md)
  - [React Component Patterns](./react-component-patterns.md)
  - [React Component Composition](./react-component-composition.md)
  - [React State Management](./react-state-management.md)
  - [React Architecture and Best Practices](./react-architecture.md)
  - [Redux Architecture and Best Practices](./redux-architecture.md)
  - [React/Redux Performance](./react-performance.md)
  - [React Deployment](./react-deployment.md)
- **React**:
  - [React Implementation and Concepts](./react-implementation.md)
  - [React and Forms](./react-forms.md)
  - [React and AJAX](./react-ajax.md)
  - [React Styling](./react-styling.md)
  - [React Server Rendering](./react-server-rendering.md)
  - [React and Routing](./react-routing.md)  
- **Redux**
  - [Redux Reducers and Selectors](./redux-reducers-selectors.md)
  - [Redux Middleware](./redux-middleware.md)
  - [Redux Side Effects](./redux-side-effects.md)
  - [Redux UI Management](./redux-ui-management.md)
  - [Redux Tips and Techniques](./redux-techniques.md)
  - [Using Redux Without React](./redux-without-react.md)
- **Other**
  - [Webpack Advanced Techniques](./webpack-advanced-techniques.md)
  - [Static Typing](./static-typing.md)


#### Comparisons and Discussion
- [React/Flux/Redux Pros, Cons, and Discussion](./pros-cons-discussion.md)
- [Framework Comparisons](./framework-comparisons.md)



## Recommended Learning Path

**You should usually learn these technologies in the following order:**

1.  **"How Web Apps Work":** a series of posts that lays out the big picture of the core technologies, terms, and concepts used in client/server web apps
2.  **JavaScript:** If you don't know JavaScript, nothing else will make sense
3.  **React:** You can use React by itself, or with Redux and/or TypeScript. Learning it separately will minimize the number of new concepts and syntax you have to learn at once.
4.  **Redux:** Redux can be used separately, but it's most commonly used with React.
5.  **TypeScript:** Because it adds static types on top of JS, you need to understand JS first. Also, it's easiest to understand React and Redux first, _then_ learn how to use them with static types.

The resources in this page are listed in that order.

**You are not required to read every single link and article listed in this page.** However, you should try to read through as many of the articles linked in the "Recommended Primary Resources" sections as possible, especially for topics you are not already familiar with. Many of the recommended tutorials do cover the same topics, so feel free to skip past concepts you've already learned.

Links in the "Additional Resources" sections are available as references and reading as needed.

### How Web Apps Work

Mark's post series that describes the key terms, concepts, technologies, syntax, and data flow used in web apps.

#### Recommended Primary Resources (should read)

- [How Web Apps Work: HTTP and Servers](https://blog.isquaredsoftware.com/2020/11/how-web-apps-work-http-server/)
- [How Web Apps Work: Client Development and Deployment](https://blog.isquaredsoftware.com/2020/11/how-web-apps-work-client-dev-deployment/)
- [How Web Apps Work: Browsers, HTML, and CSS](https://blog.isquaredsoftware.com/2020/11/how-web-apps-work-html-css/)
- [How Web Apps Work: JavaScript and the DOM](https://blog.isquaredsoftware.com/2020/11/how-web-apps-work-javascript-dom/)
- [How Web Apps Work: AJAX, APIs, and Data Transfer](https://blog.isquaredsoftware.com/2020/11/how-web-apps-work-ajax-apis-data/)

### Javascript

#### Recommended Primary Resources (should read)

##### General JS

- **Slides:** [Mark's "JavaScript for Java Developers" slides](https://blog.isquaredsoftware.com/2019/05/presentation-js-for-java-devs/)
- **Read:** [MDN: A re-introduction to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
- **Read:** [The Modern JavaScript Tutorial](https://javascript.info/)
- **Read:** [Javascript Cheatsheet](https://javascript.pythoncheatsheet.org/)
- **Exercises:** [CodeCademy - Introduction to JavaScript Tutorial](https://www.codecademy.com/learn/introduction-to-javascript)

##### Specific Topics

- Array methods:
  - [Modern JS Tutorial - Array Methods](https://javascript.info/array-methods)
  - [Which Array Function When?](https://dev.to/andrew565/which-array-function-when)
  - [Learn about JS Array Methods](https://www.scaler.com/topics/array-methods-in-javascript/)
- Equality and Comparisons
  - [MDN - Equality comparisons and sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)
  - [JS Equality Comparison Table](https://dorey.github.io/JavaScript-Equality-Table/)
- Closures
  - [MDN - Closures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
  - [Modern JS Tutorial - Closures](https://javascript.info/closure)
- `this` keyword and scopes
  - [A gentle explanation of `this` keyword in JavaScript](https://dmitripavlutin.com/gentle-explanation-of-this-in-javascript/)
  - [`this` in JavaScript](https://zellwk.com/blog/this/)
  - [Everything you wanted to know about JavaScript scope](https://ultimatecourses.com/blog/everything-you-wanted-to-know-about-javascript-scope)
- The JS event loop
  - [Watch: What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ&vl=en)
  - [The JavaScript Event Loop](https://flaviocopes.com/javascript-event-loop/)
- CSS and layout
  - [CSS: From Zero to Hero](https://dev.to/aspittel/css-from-zero-to-hero-3o16)
  - [MDN - Visual Formatting Model](https://developer.mozilla.org/en-US/docs/Web/CSS/Visual_formatting_model)
  - [MDN - Introduction to the CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  - [HTML and CSS is Hard (but it doesn't have to be)](https://internetingishard.com/html-and-css/)
  - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
  - [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- Node / NPM
  - [How to install Node.js](https://nodejs.dev/learn/how-to-install-nodejs)
  - [An introduction to the npm package manager](https://nodejs.dev/learn/an-introduction-to-the-npm-package-manager)
- Build Tools
  - [The Many Jobs of JS Build Tools](https://www.swyx.io/jobs-of-js-build-tools/)
- Debugging
  - [The definitive guide to debugging JavaScript](https://flaviocopes.com/javascript-debugging/)
  - [Intro to debugging React Applications](https://medium.com/@baphemot/intro-to-debugging-reactjs-applications-67cf7a50b3dd)

#### Additional Resources (read as needed)

##### General JS

- **Core References:**
  - [MDN: JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
  - [The Modern JavaScript Tutorial](https://javascript.info/)
  - [Online book: JavaScript for Impatient Programmers](http://exploringjs.com/impatient-js/toc.html)
- **Syntax Overviews:**
  - [Javascript Cheatsheet](https://javascript.pythoncheatsheet.org/)
  - [ES6 Overview in 350 Bullet Points](https://ponyfoo.com/articles/es6)
  - [ES6 Feature Examples](http://es6-features.org)
- **Additional Books / References:**
  - [The Complete JavaScript Handbook](https://medium.freecodecamp.org/the-complete-javascript-handbook-f26b2c71719c)
  - [Eloquent JavaScript](https://eloquentjavascript.net/)
  - [Exploring JS books](http://exploringjs.com/) (cover what's new in each yearly revision of the language)
  - [Links: ES6+ Features and Syntax](https://github.com/markerikson/react-redux-links/blob/master/es6-features.md) (links to additional articles on new features in ES6+)
  - [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) (advanced concepts and understanding of JS behavior)

##### Specific Topics

- Array/object methods / immutability
  - [Does It Mutate?](https://doesitmutate.xyz/)
  - [Array Explorer](https://sdras.github.io/array-explorer/) and [Object Explorer](https://sdras.github.io/object-explorer/)
- JS Event Loop
  - [The JavaScript Event Loop](https://flaviocopes.com/javascript-event-loop/)
- Regular Expressions
  - [A Guide to JavaScript Regular Expressions](https://flaviocopes.com/javascript-regular-expressions/)
  - [A Beginner's Guide to Regular Expressions in JavaScript](https://blog.bitsrc.io/a-beginners-guide-to-regular-expressions-regex-in-javascript-9c58feb27eb4)
- CSS
  - [Online Interactive CSS Cheat Sheet](https://htmlcheatsheet.com/css/)
  - [A Practical CSS Cheat Sheet](https://www.toptal.com/css/css-cheat-sheet)
  - [GRID: A simple visual cheatsheet for CSS Grid Layout](http://grid.malven.co/)
- Node / NPM
  - [Introduction to Node.js](https://nodejs.dev/learn)
  - [The package.json guide](https://nodejs.dev/learn/the-package-json-guide)
- Lodash
  - [Lodash documentation](https://lodash.com/docs/)
- Build Tools
  - Babel
    - [Babel Docs](https://babeljs.io/)
    - [Babel Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/babeljs/index.htm)
    - [A Beginner's Guide to Babel](https://www.sitepoint.com/babel-beginners-guide/)
    - [A Short and Simple Guide to Babel](https://flaviocopes.com/babel/)
  - Webpack
    - [Webpack docs](https://webpack.js.org/)
    - [Webpack Academy](https://webpack.academy/)
    - [Webpack from First Principles](https://www.youtube.com/watch?v=WQue1AN93YU)

### React

#### Recommended Primary Resources (should read)

##### General React

Start with reading the official docs first. The React team is in the process of starting a major rewrite of the React docs site to focus on teaching function components and hooks first, which is now available in beta. We've linked to that rather than the existing "main" documentation.

These other listed tutorials are also excellent and may explain things in a different way.

- **Read: [official React docs](https://beta.reactjs.org/)**
  - [Getting Started](https://reactjs.org/docs/getting-started.html) (docs overview and related resources)
  - [Main Concepts](https://reactjs.org/docs/hello-world.html) (read the whole series, but especially these two):
    - [Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)
    - [Thinking In React](https://reactjs.org/docs/thinking-in-react.html)
  - [React Hooks guide](https://reactjs.org/docs/hooks-intro.html) (lays out the motivation, teaches hooks, API reference, in-depth FAQ)
- **Read: [React docs (converted to show hooks)](https://reactwithhooks.netlify.app/)**

  - [Tutorial](https://reactwithhooks.netlify.app/tutorial/tutorial.html)

- **Watch:** [React Tutorial for Beginners](https://egghead.io/courses/the-beginner-s-guide-to-react)
- **Read:** [Intro to React, Redux, and TypeScript for 2020](https://blog.isquaredsoftware.com/2020/12/presentations-react-redux-ts-intro/) (Mark's presentation slides)
- **Read:** [Build a CRUD App in React with Hooks](https://www.taniarascia.com/crud-app-in-react-with-hooks/)
- **Read:** [A Comprehensive Guide to React in 2020](https://medium.freecodecamp.org/a-comprehensive-guide-to-react-js-in-2018-ba8bb6975597)
- **Exercises:** [Learn React - Interactive Tutorials](https://scrimba.com/g/glearnreact)

##### Project Setup

- **Read: [Simple React Development in 2019](https://hackernoon.com/simple-react-development-in-2017-113bd563691f)** (a guide to setting up an app, development environment, and deployment)
- **Use: [CodeSandbox.io](https://codesandbox.io)** (an online IDE that uses VS Code's editor, and can let you develop and run your apps completely in the browser)
- **Use: [Create-React-App](https://facebook.github.io/create-react-app/)** (the official CLI tool for creating a React app with one command. Sets up a project with good default build settings out of the box.)

##### Specific Topics

- Understanding how React works conceptually / internally
  - [React as a UI Runtime](https://overreacted.io/react-as-a-ui-runtime/) (deep dive - not _required_ reading, but will definitely help you understand React better)
  - [Mark Erikson: A (Mostly) Complete Guide to React Rendering Behavior](https://blog.isquaredsoftware.com/2020/05/blogged-answers-a-mostly-complete-guide-to-react-rendering-behavior/)
  - [Build your own React](https://pomb.us/build-your-own-react/)
- State and props
  - [A Visual Guide to State in React](https://daveceddia.com/visual-guide-to-state-in-react/)
- Component lifecycles
  - [React component lifecycle interactive diagram](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)
- AJAX requests
  - [AJAX Request in React - How and Where to Fetch Data](https://daveceddia.com/ajax-requests-in-react/)
- Immutability
  - [Immutability in React and Redux: The Complete Guide](https://daveceddia.com/react-redux-immutability-guide/)
  - [Redux docs: Immutable Update Patterns](https://redux.js.org/recipes/structuring-reducers/immutable-update-patterns)
- Functional Programming basics
  - [The Little Idea of Functional Programming](https://jaysoo.ca/2016/01/13/functional-programming-little-ideas/)
  - [What is Functional Programming?](http://blog.jenkster.com/2015/12/what-is-functional-programming.html)
- Forms and "controlled inputs"
  - [React docs - Forms](https://reactjs.org/docs/forms.html)
  - [Controlled and uncontrolled form inputs in React don't have to be complicated](https://goshakkk.name/controlled-vs-uncontrolled-inputs-react/)
  - [Transitioning from uncontrolled inputs to controlled](https://goshakkk.name/turn-uncontrolled-into-controlled/)
- React's new "hooks" API
  - [React docs - Hooks](https://reactjs.org/docs/hooks-intro.html) (lays out the motivation, teaches hooks, API reference, in-depth FAQ)
  - [A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/) (very long article, but a must-read. Teaches how hooks use closures, defining when effects run, and much more.)
  - [What are React Hooks?](https://www.robinwieruch.de/react-hooks/)
  - [React Hooks: Not Magic, Just Arrays](https://medium.com/@ryardley/react-hooks-not-magic-just-arrays-cd4f1857236e) (looks under the hood to explain how hooks are implemented)

#### Additional Resources (read as needed)

##### General React

- **Resource Collections**
  - [Mark Erikson's React-Redux links collection (many categories of links to articles)](https://github.com/markerikson/react-redux-links)
  - [Mark's suggested resources for learning React](https://blog.isquaredsoftware.com/2017/12/blogged-answers-learn-react/)
  - [Dave Ceddia's blog](https://daveceddia.com/archives/) (everything he's written)
  - [Robin Wieruch's blog](https://www.robinwieruch.de/categories/react/) (also everything he's written)
- **Additional Books / References**
  - [The Road to React](https://roadtoreact.com/)
  - [Learn Pure React](https://daveceddia.com/pure-react/)

### Redux

#### Recommended Primary Resources (should read)

##### General Redux

Start with reading the official docs first.

The other tutorials are also excellent and may explain things in a different way.

- **Read: [Redux core docs](https://redux.js.org/)**
  - **["Redux Essentials" tutorial](https://redux.js.org/tutorials/essentials/part-1-overview-concepts):** explains "how to use Redux, the right way", using the latest recommended techniques and practices like Redux Toolkit and the React-Redux API, while building a real-world-ish example app.
  - **["Redux Fundamentals" tutorial](https://redux.js.org/tutorials/fundamentals/part-1-overview):** teaches "how Redux works, from the ground up". including core Redux data flow and why standard Redux patterns exist.
  - ["Typescript quick start"](https://redux-toolkit.js.org/tutorials/typescript): explains how to configure Redux Toolkit with type safety from action creators through to selectors.
- **Use: [Redux Toolkit](https://redux-toolkit.js.org/)** (an official Redux package to simplify common tasks, including store setup and writing reducers)
  - Example project: [https://github.com/reduxjs/redux-essentials-example-app/tree/tutorial-steps](https://github.com/reduxjs/redux-essentials-example-app/tree/tutorial-steps)
- **Read: [React-Redux docs](https://react-redux.js.org/)**
  - **[React-Redux hooks API reference](https://react-redux.js.org/api/hooks)**
  - These APIs are now considered outdated, but are widely used in existing Redux codebases
    - [`connect()`: Extracting Data with `mapStateToProps`](https://react-redux.js.org/using-react-redux/connect-mapstate)
    - [`connect()`: Dispatching Actions with `mapDispatchToProps`](https://react-redux.js.org/using-react-redux/connect-mapdispatch)
- **Watch:** Dan Abramov's tutorial videos on Egghead
  - [Getting Started with Redux](https://egghead.io/courses/getting-started-with-redux)
  - [Building React Apps with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux)
- **Read:** [A Complete React-Redux Tutorial](https://daveceddia.com/redux-tutorial/)
- **Read:** [React Redux Tutorial for Beginners: The Definitive Guide](https://www.valentinog.com/blog/redux/)
- **Read:** [Leveling Up with React: Redux](https://css-tricks.com/learning-react-redux/)

##### Mark Erikson's Redux Resources

- **Read: ["Idiomatic Redux" concepts and opinion series](https://blog.isquaredsoftware.com/series/idiomatic-redux/)**. A series of blog posts that describes standard Redux development best practices, why they exist, and how Redux is meant to be used. (These are not required reading to get started, but highly recommended once you understand the basics.)
- Legacy resources (do not cover "Modern Redux", but still informative)
  - **Read: [Redux Fundamentals Workshop slices](https://blog.isquaredsoftware.com/2018/06/redux-fundamentals-workshop-slides/)**: a 2-day internal workshop that covers Redux from the ground up. Includes complete recordings of each section, slides, and an exercises repo. (Does not cover "Modern Redux", but
  - **Read: ["Practical Redux" blog tutorial series](https://blog.isquaredsoftware.com/series/practical-redux/)**. Covers multiple React and Redux concepts through building a larger example application

##### Specific Topics

- Tradeoffs of using Redux:
  - [Mark Erikson: When (and when not) to Reach for Redux](https://changelog.com/posts/when-and-when-not-to-reach-for-redux)
  - [Dan Abramov: the Case for Flux](https://medium.com/swlh/the-case-for-flux-379b7d1982c6)
  - [Dan Abramov: You Might Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)
- Reducer functions
  - [Redux docs - Structuring Reducers](https://redux.js.org/recipes/structuring-reducers/structuring-reducers)
- Selector functions
  - [Idiomatic Redux: Using Reselect Selectors for Encapsulation and Performance](https://blog.isquaredsoftware.com/2017/12/idiomatic-redux-using-reselect-selectors/)
- Side effects
  - [Stack Overflow: How do we dispatch an action with a timeout?](https://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559)
  - [Stack Overflow: Why do we need middleware for async flow?](https://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594)
  - [What the heck is a "thunk"?](https://daveceddia.com/what-is-a-thunk/)
  - [What is the right way to do asynchronous operations in Redux?](https://decembersoft.com/posts/what-is-the-right-way-to-do-asynchronous-operations-in-redux/) (side-by-side comparison of multiple side effects approaches)
  - [Redux Power Tools: Redux-Saga](https://formidable.com/blog/category/redux-saga/)
- Normalizing data
  - [Redux docs - Normalizing State Shape](https://redux.js.org/recipes/structuring-reducers/normalizing-state-shape)
  - [Normalizing Redux Stores for Maximum Code Reuse](https://medium.com/@adamrackis/normalizing-redux-stores-for-maximum-code-reuse-ae6e3844ae95)

#### Additional Resources (read as needed)

- **Resource Collections**
  - [**Redux Style Guide**](https://redux.js.org/style-guide/style-guide): best practices and recommendations for using Redux the right way
  - [**Redux FAQ**](https://redux.js.org/faq) (answers to many common questions about Redux)
  - [Redux Ecosystem Links](https://github.com/markerikson/redux-ecosystem-links) (a curated list of Redux-related addons and utilities)
- **Books and Courses**
  - [Pure Redux course](https://daveceddia.com/pure-redux/) by Dave Ceddia
  - [Redux course](https://tylermcginnis.com/courses/redux/) by Tyler McGinnis
  - [Learn Redux course](https://learnredux.com/) by Wes Bos (free)
  - [Redux in Action](https://www.manning.com/books/redux-in-action)
  - [The Complete Redux Book](https://leanpub.com/redux-book) (free)
  - [Taming the State in React](https://www.robinwieruch.de/learn-react-redux-mobx-state-management/)

##### Specific Topics

- How does Redux work?
  - [Build Yourself a Redux](https://zapier.com/engineering/how-to-build-redux/)
  - [Idiomatic Redux: The History and Implementation of React-Redux](https://blog.isquaredsoftware.com/2018/11/react-redux-history-implementation/)

### TypeScript

#### Recommended Primary Resources (should read)

- **Read: [official TypeScript docs](https://www.typescriptlang.org/docs/home.html)**
- [Typescript Playground](https://www.typescriptlang.org/play) - an interactive playground for testing typescript behavior and reproducing issues - includes some built-in examples
- **Read: [Get Started with TypeScript in 2019](https://www.robertcooper.me/get-started-with-typescript-in-2019)**
- **Read: [The Definitive TypeScript Guide](https://www.sitepen.com/blog/update-the-definitive-typescript-guide/)**
  - [TypeScript Cheat Sheet](https://www.sitepen.com/blog/typescript-cheat-sheet)
- **Read: [The TypeScript Guide](https://flaviocopes.com/typescript/)**

##### Specific Topics

- `interface` vs `type`
  - [TypeScript Interface vs Type](https://pawelgrzybek.com/typescript-interface-vs-type/)
    - [Interface vs Type sandbox example](https://www.typescriptlang.org/play?q=287#example/types-vs-interfaces)
- ["Typescript quick start"](https://redux-toolkit.js.org/tutorials/typescript): explains how to configure Redux Toolkit with type safety from action creators through to selectors.

#### Additional Resources (read as needed)

- **Resource Collections**
  - **[React+TypeScript Cheatsheets](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet)** (a definitive set of information on how to use TypeScript with React)
  - [React + Redux in TypeScript - Static Typing Guide](https://github.com/piotrwitek/react-redux-typescript-guide) (a comprehensive set of info on using React, Redux, and TS together, with a focus on getting complete / "correct" type coverage of an app)
- **Techniques**
  - [Redux with Code-Splitting and Type Checking](https://www.matthewgerstman.com/tech/redux-code-split-typecheck/)
