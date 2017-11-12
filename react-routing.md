### React and Routing

#### Routing

- **Routing React Apps: The Complete Guide**  
  https://scotch.io/tutorials/routing-react-apps-the-complete-guide  
  An in-depth article covering use of React-Router (v2)
 
  
- **Do I Even Need a Routing Library?**  
  http://jamesknelson.com/even-need-routing-library/  
  Another excellent article from James K Nelson that digs into the core concepts behind a topic, this time looking at what routing libraries do, issues with browser history, and what to consider when deciding on a routing approach.
  
- **Webpack code splitting with Create React App and React Router**  
  https://www.drewbolles.com/blog/2016/11/14/webpack-code-splitting-with-create-react-app-react-router/  
  A quick example of how to use React-Router's hooks to set up code splitting with Webpack
  
- **Multifactor Authentication in your React Apps**  
  https://scotch.io/tutorials/multifactor-authentication-in-your-react-apps  
  A tutorial demonstrating how to use the Auth0 service, along with React Router, to implement multi-factor authentication for an app.
  
- **How to Handle Routing in React**  
  https://code.tutsplus.com/tutorials/understanding-how-to-handle-routing-in-react--cms-27355  
  A quick example of using React-Router v2 in a small React app
  
- **React-router alternative: switch**  
  https://medium.com/@daveford/react-router-alternative-switch-acd7961f08db  
  Some examples of simply using switch statements and the history API for routing
  
- **Routing in React, the uncomplicated way**  
  https://hackernoon.com/routing-in-react-the-uncomplicated-way-b2c5ffaee997  
  Examples of how to implement a custom routing approach, with minimal external dependencies.
  
- **Build your own React Router v4**  
  https://tylermcginnis.com/build-your-own-react-router-v4/  
  Tyler McGinnis, a React Training partner, walks through the process of building a miniature version of React Router v4 to help explain its concepts and implementation.
  
- **A little bit of history**  
  https://medium.com/@pshrmn/a-little-bit-of-history-f245306f48dd  
  A deep look at the "history" library, which is the core of React Router and used by other routing libraries as well.
  
- **Building a context-free React router**  
  https://reactarmory.com/guides/context-free-react-router  
  A tutorial that teaches how to create a simple push-state based React router without relying on React's context API.
  
- **All About React Router 4**  
  https://css-tricks.com/react-router-4/  
  A deep look at patterns and strategies for using React-Router v4 successfully.
  
- **Advanced React Router concepts: recursive path, code splitting, animated transitions, and more**  
  https://blog.logrocket.com/advanced-react-router-concepts-code-splitting-animated-transitions-scroll-restoration-recursive-17096c0cf9db  
  A tutorial that demonstrates how to implement a variety of useful features using React-Router v4.
  
- **React Router 4 Tutorial From Scratch**  
  https://appdividend.com/2017/09/12/react-router-tutorial-example-scratch/  
  A short tutorial demonstrating use of React Router v4
  
  
#### Routing with Redux
  
- **Let the URL Do the Talking**  
  http://formidable.com/blog/2016/07/11/let-the-url-do-the-talking-part-1-the-pain-of-react-router-in-redux/  
  http://formidable.com/blog/2016/07/19/let-the-url-do-the-talking-part-2-bargaining-and-acceptance-with-redux-and-react-router/  
  http://formidable.com/blog/2016/07/25/let-the-url-do-the-talking-part-3-empower-the-url-with-redux-little-router/  
  http://formidable.com/blog/2016/09/13/introducing-nested-routing-in-redux-little-router/  
  A series of articles discussing pain points when using React-Router and Redux together, and introducing a library called Redux-Little-Router as an alternative
  

- **An Introduction to the Redux-First Routing Model**  
  https://medium.freecodecamp.com/an-introduction-to-the-redux-first-routing-model-98926ebf53cb  
  An article that argues in favor of keeping location state in Redux, updating it with actions, and syncing the browser URL based on that state.  Includes a sample implementation for the approach, and a link to the actual library the author built.
  
- **Pre Release: Redux-First Router - A Step Beyond Redux-Little-Router**  
  https://medium.com/faceyspacey/pre-release-redux-first-router-a-step-beyond-redux-little-router-cd2716576aea  
  An opinionated article that argues against the approaches used by both React-Router and Redux-Little-Router, in favor of basing routing state in Redux, with a corresponding new library.
  
- **Routedux - Routing the Redux way**  
  https://cjdev.github.io/routedux/  
  An article introducing a library that maps URLs to actions and vice versa.
  
- **Entering/Leaving hooks of routing for Redux apps**  
  https://medium.com/@kuy/entering-leaving-hooks-of-routing-for-react-redux-app-22e6eea055a5  
  Discusses use of enter/leave routing hooks for handling component data fetching needs, and how that is handled with the author's Redux-based routing library.
  
- **Routes as State in React**  
  https://blog.boon.gl/2017/06/29/routes-as-state-in-react.html  
  Some thoughts on why tracking route data as state might make sense, and some examples of how to approach that.
  
- **Redux-First Router data fetching; solving the 80% use case for async middleware**  
  https://medium.com/faceyspacey/redux-first-router-data-fetching-solving-the-80-use-case-for-async-middleware-14529606c262  
  An extended article discussing "component-first" vs "route-first" data fetching approaches, and how the author's library helps solve the "route-first" approach.
  
- **Redux-First Router: Just Dispatch Actions**  
  https://survivejs.com/blog/redux-first-router-interview/  
  An interview with the author of the redux-first-router library.  The author describes the core concepts, how it differs from React-Router, useful features, and why he developed it.
  
- **A Redux First Router Saga**  
  https://medium.com/@bryanfillmer/a-redux-first-router-saga-67c2cda9252e  
  Examples and discussion of how to use sagas in conjunction with Redux-based routing to handle side effects that are connected to route changes.
  
- **Redux First Router - First Impressions**  
  https://www.dailydrip.com/topics/react/drips/redux-first-router-first-impressions  
  A short tutorial that shows how to add redux-first-router to a CRA project and configure it.
  
  
#### Authentication

- **How to Build a React Application with User Login and Authentication**  
  https://stormpath.com/blog/build-a-react-app-with-user-authentication  
  Builds a small React app from the ground up, with use of React-Router for routing and the Stormpath SDK to handle authentication and authorization.

- **JWT Authentication with React + Redux**  
  http://www.thegreatcodeadventure.com/jwt-authentication-with-react-redux/  
  Demonstrates handling sign-in flow, including a dynamic login/logout link, and implementing routes that can only be seen by logged-in users.
  
- **Role-based authorization using React-Router**  
  http://frontendinsights.com/role-based-authorization-using-react-router/  
  A look at some ways to control component routes based on user roles
  
- **Role based authorization in React**  
  https://hackernoon.com/role-based-authorization-in-react-c70bb7641db4  
  Some alternative approaches to the previous post, using React component patterns like Higher Order Components to control authorization and rendering
  
- **Dealing with Authentication in React**  
  https://medium.com/@nesbtesh/dealing-with-authentication-in-react-cadb679fbc0f  
  Some short examples of saving an authentication token, writing queries to use and update that token, and checking the token when rendering components.
  
- **Role based routing with React and Redux**  
  http://crazysigma.com/blogs/2017/04/16/role-based-routing-react-redux/  
  A description of a fairly simple approach for defining role-based handling of routes, with sample code.
  
- **Preact Authentication Tutorial**  
  https://auth0.com/blog/preact-authentication-tutorial/  
  A tutorial that demonstrates how to build an app with Preact, including authentication, and makes some comparisons to doing so in React.
  
- **How to Implement Authentication for Your React App**  
  https://medium.appbase.io/how-to-implement-authentication-for-your-react-app-cf09eef3bb0b  
  https://medium.appbase.io/securing-a-react-web-app-with-server-side-authentication-1b7c7dc55c16  
  A pair of posts that demonstrate implementing both client-side and server-side authentication behavior for a React/Node app.