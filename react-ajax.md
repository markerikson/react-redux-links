### React and AJAX

#### Basic Concepts

- **AJAX Requests in React: How and Where to Fetch Data**  
  https://daveceddia.com/ajax-requests-in-react/  
  An overview of where AJAX requests fit into React usage.

- **React AJAX Best Practices**  
  http://andrewhfarmer.com/react-ajax-best-practices/  
  Covers four ways to approach managing queries and data fetching.

- **AJAX/HTTP Library Comparison**  
  http://andrewhfarmer.com/ajax-libraries/  
  A useful overview of the most popular AJAX libraries, including platform support and feature comparisons.
  
- **Loading data from APIs in React**  
  http://javascriptplayground.com/blog/2017/01/http-requests-reactjs/  
  A 10-minute screencast that demonstrates how to create a component that fetches data from an API and renders it in a page.  Covers how to use the React lifecycle to make requests, using the `fetch` API, and dealing with response successes and failures.
  
- **3 Libraries and 3 Ways to handle AJAX in React Apps**  
  https://appendto.com/2017/01/3-libraries-and-3-ways-to-handle-ajax-in-react-apps/  
  Demonstrates three approaches to structuring AJAX calls (root component, containers, and via Redux middleware), and lists three of the most popular AJAX libraries.
  

#### Request Implementation Examples
  
- **Implementing React Redux with GraphQL**  
  https://marufsarker.github.io/blog/posts/2016/05/09/react-redux-with-graphql.html  
  Walks through the implementation of a server/client Todo app that uses GraphQL mutations for the async actions.
  
- **Rendering Backend Requests with React**  
  https://blog.boldlisting.com/rendering-backend-requests-with-react-7e493103c2b6  
  Describes a pattern for dealing with components that depend on loading data from a backend
  
- **Build a React + Flux App with User Authentication**  
  https://scotch.io/tutorials/build-a-react-flux-app-with-user-authentication  
  Builds a React app that calls a remote API and authenticates users.  Uses a specific auth provider and basic Flux implementation, but the concepts are widely applicable.
  
- **Building Realtime Collaborative Offline-First Apps with React, Redux, PouchDB, and Websockets**  
  http://blog.yld.io/2015/11/30/building-realtime-collaborative-offline-first-apps-with-react-redux-pouchdb-and-web-sockets/  
  A blog post and sample project demonstrating various layers of client-server syncing, eventually driving a Redux store and React UI.
  
- **Handling AJAX In Your React Application with Agility**  
  https://hackernoon.com/handling-ajax-in-your-react-application-with-agility-413f1f21fc70  
  Describes three approaches to fetching data in a React app: within a React component, using the Relay GraphQL library, and using Redux middleware
  

#### Handling Request Status with State

- **React-Redux issue #210: "dispatching in componentWillMount?"**  
  https://github.com/reactjs/react-redux/issues/210#issuecomment-244774674  
  Some valuable extended discussion about how managing requests and data really involves several distinct possible states.

- **"Slaying a UI Antipattern" comparisons**  
  http://blog.jenkster.com/2016/06/how-elm-slays-a-ui-antipattern.html  
  https://medium.com/javascript-inside/slaying-a-ui-antipattern-in-fantasyland-907cbc322d2a  
  https://medium.com/@gcanti/slaying-a-ui-antipattern-with-flow-5eed0cfb627b  
  https://medium.com/@marsbergen/nice-pattern-for-redux-state-b8641b6ff9d1 
  Articles by different authors that demonstrate how to handle the common "loading/no data/data" issue with various static typing approaches and FP principles.
  
- **Better data fetching with RemoteDataJS**  
  http://javascriptplayground.com/blog/2016/06/remote-data-js/  
  Examples of how to use the author's RemoteDataJS library to manage request state.  Helpful to see the list of states it tracks, even if you don't use the library.
  