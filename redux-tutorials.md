### Redux Tutorials


#### Basic Introductions
- **Redux Docs**  
  http://redux.js.org/index.html  
  The official Redux documentation.  FANTASTIC writing - not just "here's the API", but "here's what you want to do and how we came up with this"

- **Getting Started with Redux - Video Series**  
  https://egghead.io/series/getting-started-with-redux  
  https://github.com/tayiorbeii/egghead.io_redux_course_notes  
  Dan Abramov, the creator of Redux demonstrates various concepts in 30 short (2-5 minute) videos.  The linked Github repo contains notes and transcriptions of the videos.

- **Building React Applications with Idiomatic Redux - Video Series**  
  https://egghead.io/series/building-react-applications-with-idiomatic-redux  
  https://github.com/tayiorbeii/egghead.io_idiomatic_redux_course_notes  
  Dan Abramov's second video tutorial series, continuing directly after the first.  Includes lessons on store initial state, using Redux with React Router, using "selector" functions, normalizing state, use of Redux middleware, async action creators, and more.  The linked Github repo contains notes and transcriptions of the videos.

- **Single State Tree + Flux**  
  http://merrickchristensen.com/articles/single-state-tree.html  
  Describes the benefits of a Flux architecture, and a single state tree like Redux has

- **Understanding Redux**  
  http://www.youhavetolearncomputers.com/blog/2015/9/15/a-conceptual-overview-of-redux-or-how-i-fell-in-love-with-a-javascript-state-container  
  A higher-level description of what Redux is, the major concepts, and why you would want to use it.  Also some additional article links.

- **A Cartoon Guide to Redux**  
  https://code-cartoons.com/a-cartoon-intro-to-redux-3afb775501a6#.3k23w6m18  
  Another high-level description of Redux, with cartoons
  
- **Redux-Tutorial**  
  https://github.com/happypoulp/redux-tutorial  
  A file-based tutorial to Redux (click on each numbered .js file in the repo)
  
- **Leveling Up with React: Redux**  
  https://css-tricks.com/learning-react-redux/  
  A very well-written introduction to Redux and its related concepts, with some nifty cartoon-ish diagrams.
  
- **Functionally Managing State with Redux**  
  http://wecodetheweb.com/2015/09/29/functionally-managing-state-with-redux/  
  A quick overview of Redux's core concepts, and how to use it with React
  
- **Redux: From Twitter Hype to Production**  
  http://slides.com/jenyaterpil/redux-from-twitter-hype-to-production#/  
  An extremely well-produced slideshow that visually steps through core Redux concepts, usage with React, project organization, and side effects with thunks and sagas.  Has some absolutely _fantastic_ animated diagrams demonstrating how data flows through a React+Redux architecture.
  
- **Redux diagrams**  
  https://github.com/reactjs/redux/issues/653  
  A variety of user-provided diagrams illustrating how the pieces of Redux fit together.

- **How I Learned to Stop Worrying and Love Redux**  
  https://medium.com/@shopsifter/how-i-learned-to-stop-worrying-and-love-redux-9b50e505e802
  A new Redux user describes how she was able to overcome initial problems learning Redux.

- **Introduction to Redux and React-Redux**  
  http://julienrenaux.fr/2016/05/30/introduction-to-redux-and-react-redux/  
  A quick overview of core Redux concepts, with code examples for creating a store and hooking up React components to read the data.
  
- **Redux and React Redux**  
  http://www.pshrmn.com/tutorials/react/redux/  
  http://www.pshrmn.com/tutorials/react/react-redux/  
  A pair of articles covering basic Redux concepts and usage.
  
- **An Introduction to Redux**  
  https://www.smashingmagazine.com/2016/06/an-introduction-to-redux/  
  An overview and intro to the basic concepts of Redux.


#### Project-Based Tutorials


- **Managing Data Flow on the Client Side**  
  http://blog.madewithlove.be/post/redux/  
  Walks through a small Redux example, and talks about the benefits

- **Getting Started with Redux**  
  http://www.jchapron.com/2015/08/14/getting-started-with-redux/  
  Walks through setting up a small Redux app, and builds up each layer

- **Full-Stack Redux Tutorial**  
  http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html  
  A full-blown, in-depth tutorial that builds up a complete client-server application.

- **Getting Started with React, Redux and Immutable: a Test-Driven Tutorial**  
  http://www.theodo.fr/blog/2016/03/getting-started-with-react-redux-and-immutable-a-test-driven-tutorial-part-1/  
  http://www.theodo.fr/blog/2016/03/getting-started-with-react-redux-and-immutable-a-test-driven-tutorial-part-2/  
  Another solid, in-depth tutorial, similar to the "Full-Stack" tutorial.  Builds a client-only TodoMVC app, and demonstrates a good project setup (including a Mocha+JSDOM-based testing configuration).  Well-written, covers many concepts, and very easy to follow.
  
- **Build an Image Gallery using React, Redux, and redux-saga**  
  http://joelhooks.com/blog/2016/03/20/build-an-image-gallery-using-redux-saga  
  A step-by-step look at building a page with some complex async behavior.

- **The Soundcloud Client in React + Redux**  
  http://www.robinwieruch.de/the-soundcloud-client-in-react-redux/  
  A detailed walkthrough demonstrating project setup, routing, authentication, fetching of remote data, and wrapping of a stateful library.
  
- **Interactive Frontend Development with React and Redux**  
  https://courses.cs.ut.ee/2016/react/spring/Main/Lectures  
  An Estonian university course covering React and Redux. Lecture videos, slides, and course code are all available online (in English).  Topics include React philosophy, container components, Redux basics, async actions, middleware, routing, and optimization.



#### Redux Implementation Walkthroughs

- **Read the Source ep17 - React Redux with Dan Abramov**  
  https://youtu.be/VJ38wSFbM3A  
  Dan walks through the implementation and concepts of React-Redux.  A great follow-up to the Egghead.io tutorial series.
  
- **Connect.js explained**  
  https://gist.github.com/gaearon/1d19088790e70ac32ea636c025ba424e  
  A very simplified version of React Redux's `connect()` function that illustrates the basic implementation
  
- **Let's Write Redux!**  
  http://www.jamasoftware.com/blog/lets-write-redux/  
  Walks through writing a miniature version of Redux step-by-step, to help explain the concepts and implementation.
  
- **Hacking Redux**  
  http://paulserraino.com/javascript/2016/02/16/hacking-redux.html  
  Looks at the core concepts in Redux, and builds up a mini-Redux to demonstrate how Redux works internally.
  
- **Learning Redux with Reducks**  
  http://www.aaron-powell.com/tagged/reducks.html  
  Another "build a mini-Redux" article series.


#### Redux Middleware

- **Exploring Redux Middlewares**  
  http://blog.krawaller.se/posts/exploring-redux-middleware/  
  Understanding middlewares through a series of small experiments

- **Understanding Redux Middleware**  
  https://medium.com/@meagle/understanding-87566abcfb7a  
  Breaks down Redux's applyMiddleware function line-by-line, and explains the concepts involved
  
- **Building Redux Middleware**  
  https://reactjsnews.com/redux-middleware  
  Demonstrates building a basic Redux middleware
  
- **A Beginner's Guide to Redux Middleware**  
  https://www.codementor.io/reactjs/tutorial/beginner-s-guide-to-redux-middleware  
  A useful explanation of middleware use cases, with numerous examples
  
- **Redux Middleware**  
  http://jonnyreeves.co.uk/2016/redux-middleware/  
  A tutorial describing how Redux compares to typical "MVC", what a "middleware" is, what they can do, and how you can test them. 
  
- **Redux Middleware Tutorial**  
  http://www.pshrmn.com/tutorials/react/redux-middleware/  
  An overview of what middleware is, how `applyMiddleware` works, and how to write middleware.
  
- **Redux Middleware: Behind the Scenes**  
  http://briantroncone.com/?p=529  
  Digs into the concepts and implementation of middleware.


#### Paid Courses and Books

- **The Complete Redux Book**  
  https://leanpub.com/redux-book  
  How do I manage a large state in production? Why do I need store enhancers? What is the best way to handle form validations?  Get the answers to all these questions and many more using simple terms and sample code. Learn everything you need to use Redux to build complex and production-ready web applications.  (NOTE: Work in progress as of May 2016, but looks very promising.)


