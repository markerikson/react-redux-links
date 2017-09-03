### React and AJAX

#### Basic Concepts

- **AJAX Requests in React: How and Where to Fetch Data**  
  https://daveceddia.com/ajax-requests-in-react/  
  An overview of where AJAX requests fit into React usage.
  
- **How to make AJAX requests in React?**  
  https://medium.com/@baphemot/how-to-make-ajax-requests-in-react-a6a52bb5a8b1  
  A helpful introduction to making AJAX requests, including libraries to use, where to run requests, and a couple examples of handling "loading..." status.
  
- **Understanding React: data hydration / initialization**  
  https://medium.com/@baphemot/understanding-reactjs-data-hydration-initialization-bacbb790c7cb  
  Describes several possible approaches to loading data from a server at app startup, including API calls and ways to embed data into the page.
  
- **Where to fetch Data: componentWillMount vs componentDidMount**  
  https://daveceddia.com/where-fetch-data-componentwillmount-vs-componentdidmount/  
  A quick comparison of when these two lifecycle methods are called, and why AJAX calls should generally be done in `componentDidMount`
  
- **How to fetch data in React**  
  https://www.robinwieruch.de/react-fetching-data/  
  An excellent look at several key aspects of fetching in data in React apps, including what components should containg the fetching and display logic, what lifecycle methods to use for API calls, and how to abstract out the fetching process into its own component.

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
  https://marufsarker.github.io/blog/2016/05/09/react-redux-with-graphql/  
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
  
- **You don't need a fancy framework to use GraphQL with React**  
  https://edgecoders.com/you-dont-need-a-fancy-framework-to-use-graphql-with-react-b47b436626fb  
  A detailed explanation of how to construct GraphQL queries in a client and load the data into React components, without using any complicated libraries.
  

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
  
- **Dealing with APIs in React with ReactRemoteData**  
  http://javascriptplayground.com/blog/2017/03/remote-data-react-components/  
  The author of the RemoteDataJS libraries shows a small React wrapper he created and how to use it
  
- **A Better Way To Handle Loading State In Redux**  
  http://nikolay.rocks/2017-06-18-better-redux-loading  
  Discusses several ways to store "loading/success/failure" state, and tradeoffs of the approaches.  Talks about Redux, but applies to React as well.