### Redux Techniques

**Related Topics**:
- [Redux Reducers and Selectors](./redux-reducers-selectors.md)
- [Redux UI Management](./redux-ui-management.md)


#### Debugging

- **Hot reloading and time travel debugging: what are they?**  
  https://code-cartoons.com/hot-reloading-and-time-travel-debugging-what-are-they-3c8ed2812f35  
  A short but informative article describing these concepts and why they're useful.

- **Debugging is in Flux**  
  https://vimeo.com/166342150  
  A fantastic talk that demonstrates use cases and examples for time-travel debugging in a Flux-style architecture, including crash reporting.  The demo is built in Alt, but obviously completely applies to Redux as well.
  
- **Drew Bug**  
  https://www.youtube.com/watch?v=n8vkg_RVIRo  
  A video demonstrating a Redux crash reporter and time travel debugger.
  
- **Redux DevTools Without Redux**  
  https://medium.com/@zalmoxis/redux-devtools-without-redux-or-how-to-have-a-predictable-state-with-any-architecture-61c5f5a7716f  
  Instructions on setting up the Redux DevTools browser extension to use things other than a single Redux store (such as reducers for use within a React component, or other state libs)
  
- **Redux Error Reports Concept**  
  https://medium.com/@jrullmann/redux-error-reports-concept-ab85b658f53e  
  A semi-hypothetical description of tools that could be built to report errors by leveraging Redux
  
- **A Quick Look at the React and Redux DevTools**  
  http://mediatemple.net/blog/tips/a-quick-look-at-the-react-and-redux-devtools/  
  An intro to using the React DevTools and Redux DevTools extensions for debugging
  
- **Improve your development workflow with the Redux DevTools Extension**  
  https://medium.com/@zalmoxis/improve-your-development-workflow-with-redux-devtools-extension-f0379227ff83  
  The author of the Redux DevTools extension describes new features, including "pause/locking" for iteration on behavior, and some changes needed to add it to the store.
  
- **Time Travel in React Redux apps using the Redux DevTools**  
  https://onsen.io/blog/react-redux-devtools-with-time-travel/  
  Examples of configuring a Redux store to use the DevTools enhancers, and using both the DevTools components and the browser extension for debugging.
  
- **Redux Logging in Production / Maximizing Debuggability in Redux**  
  https://blog.logrocket.com/redux-logging-in-production-3b2a4816b713  
  https://blog.logrocket.com/maximizing-debuggability-with-redux-79b2ad07b64c  
  A pair of articles discussing a variety of aspects and approaches for debugging Redux apps.  Includes several mentions of the LogRocket service, but also covers other tools and approaches, including building your own analytics pipeline.
  
- **Redux DevTools for Dummies**  
  https://medium.com/@tylerwclark/redux-devtools-for-dummies-74566c597d7  
  An overview of the Redux DevTools Extension, including examples of how to properly add the DevTools when setting up a Redux store, and explanations of the various parts of the extension's UI.
  
- **How to treat Errors as first-class citizen in Flux (and Redux)**  
  https://medium.com/@jamiedixon/how-to-treat-errors-as-first-class-citizens-in-flux-and-redux-fca7f3d5c02d  
  Discusses how the FSA structure expects actions to have an optional `error` field, and how to write code that deals with that.
  
- **Redux in Action: Using the Redux DevTools**  
  https://www.slideshare.net/ManningBooks/redux-in-action-learn-to-manage-and-consolidate-state  Some slides from the authors of the book "Redux in Action", explaining what the Redux DevTools are, how to set them up, and how to use them to view dispatched actions and debug state changes
  

  
#### Other  

  
- **Connecting the Linode API to Redux with Higher-Order Functions**  
  https://engineering.linode.com/2016/08/17/Using-metaprogramming-in-the-manager.html  
  Linode explains how they generate customized action creators and reducers to talk to different parts of their API
  
- **A Finite State Machine Helper for Redux**  
  https://hackernoon.com/a-finite-state-machine-helper-for-redux-c18519643719  
  Describes a small but useful library for managing state machines using Redux reducers.
  
- **Standard actions in Redux**  
  https://medium.com/@jtbennett/standard-actions-in-redux-c6a415c8aea4  
  A description of the Flux Standard Action specification, and how it can be used with Redux
  
- **Redux runtime reconfiguration techniques**  
  https://www.youtube.com/watch?v=ZvbZTXs3Y3E  
  http://redux-reconfig.surge.sh/  
  http://codepen.io/vnovick/pen/pEgKww/?editors=0010#0  
  Discussion and demonstration of some ways to load reducers and components at runtime.
  
- **Secure file uploads with redux-plupload**  
  http://engineering.tes.com/post/secure-file-uploads/  
  Some examples of how to use Redux-Plupload to manage file uploads
  
- **{Persist}ence is Key: Using Redux-Persist to Store Your State in LocalStorage**  
  https://medium.com/@clrksanford/persist-ence-is-key-using-redux-persist-to-store-your-state-in-localstorage-ac6a000aee63  
  A quick introduction to using redux-persist to reuse store state between page refreshes
  
- **Immuto: Strongly Typed Redux Composition**  
  http://danielearwicker.github.io/Immuto_Strongly_Typed_Redux_Composition.html  
  http://danielearwicker.github.io/Immuto_Working_with_React_An_Example_.html  
  http://danielearwicker.github.io/Immuto_Radical_Unification.html  
  http://danielearwicker.github.io/Immuto_Epilogue.html  
  An interesting series of experiments in adding typed cursor-like behavior to Redux.  The author appears to give up on the idea in the end, but the writing and thought process are informative.
  
- **Using Actions in Redux the Correct Way**  
  http://cmichel.io/using-actions-in-redux-the-correct-way/  
  An interesting trick using ES6 proxies to ensure wrong action types aren't accidentally used.
  
- **Object Oriented Functional Programming, or, How You Can Use Classes as Redux Reducers**  
  https://medium.com/@ustunozgur/object-oriented-functional-programming-or-how-can-you-use-classes-as-redux-reducers-23462a5cae85  
  An exploration of how to use Immutable.js Record classes with methods as Redux reducers.  This is a very non-idiomatic approach, but the article is reasonably informative.
  
- **Exploring Interaction History with Redux-DAG-History**  
  https://blog.atsid.com/exploring-interaction-history-d09a52a7d186  
  The Microsoft Research group describes a library they built to implement a "branching" approach to application history and undo/redo capabilities.
  
- **Roll the Dice: Random Numbers in Redux**  
  https://daveceddia.com/random-numbers-in-redux/  
  Some excellent examples of how "impure values" like random numbers should fit into a Redux application.
  
- **Random in Redux**  
  https://blog.ohlman.io/random-in-redux-b6b9932ad061  
  Another quick example of how to use seed values to safely generate random numbers in Redux.
  
- **Things I learned about Redux: Don't Dispatch from React Lifecycle Methods**  
  https://github.com/carlsverre/talk-react-redux-learnings  
  https://docs.google.com/presentation/d/1J82fXkgUKL6-k17ADVtozXMRfMGXnx5R6r5UnOm8z8g/edit?usp=sharing  
  Resources from an excellent presentation on potential timing issues that result from dispatching Redux actions in React lifecycle methods.  Repo includes sample code demonstrating the issues, and a link to the video of the meetup talk.
  
- **Let the Buyer Beware: React Redux Rerender Gotcha**  
  https://www.nathanl.in/posts/let-the-buyer-beware-react-redux-rerender-gotcha  
  An article describing some similar concerns regarding timing of Redux actions and React lifecycle methods, especially in regards to tracking loading state.

- **Manage analytics actions in React**  
  https://medium.com/trainline-engineering/manage-analytics-actions-in-react-67fae61495de  
  Discusses using Redux middleware and redux-observable to manage analytics behavior in isolation from the rest of the application.
  
- **VR Redux / ReactVR Redux Revisited**  
  http://jimpurbrick.com/2017/01/04/vr-redux/  
  http://jimpurbrick.com/2017/07/04/react-vr-redux-revisited/  
  http://jimpurbrick.com/2017/11/10/replaying-replicated-redux/  
  A set of posts that discuss using ReactVR and Redux to implement a networked VR application, including using a Redux middleware to synchronize actions between the clients, and approaches to managing consistency and optimistic updates.
  
- **Using dynamic localization to improve accessibility with React and Redux**  
  https://medium.com/checkr/using-dynamic-localization-to-improve-accessibility-with-react-and-redux-7650878af6ef  
  Some quick examples and discussion of how Checkr uses the react-redux-i18 package to set up localization for their app.
  
- **Evil things you do in Redux - dispatch in updating lifecycle methods**  
  https://hackernoon.com/evil-things-you-do-with-redux-dispatch-in-updating-lifecycle-methods-ad116de882d4  
  Thoughts on the pros and cons of dispatching Redux actions in React lifecycle methods, such as causing cascades of re-renders and updates in other components.
 
- **Redux and JSON Schema**  
  https://blog.prismatik.com.au/redux-and-json-schema-c63368931143  
  Short discussion of the overall benefits of using JSON Schema to define data structures, and a Redux library that helps use those for Redux.
  
- **A Simple Way to Implement Timers and Timeouts in Redux**  
  https://spin.atomicobject.com/2017/11/20/timers-timeouts-redux/  
  A quick example of storing a "current time" value and timers as "expire times".
  
  
  
#### Reducing Boilerplate

- **Why I created Redux-Tiles library to deal with Redux verbosity**  
  http://blog.bloomca.me/2017/06/02/why-i-created-redux-tiles-library.html  
  https://news.ycombinator.com/item?id=14482215  
  Describes several concerns with increasing verbosity and complexity in Redux apps, and how the author's library can help simplify those.
  
- **Reducing Redux Boilerplate with redux-actions**  
  http://www.hypertext.io/redux/react/2017/10/30/redux-actions.html  
  A short look at how the `redux-actions` lib can simplify the process of defining action type, action creators. and reducers.

- **Reducing Redux: avoiding boilerplate with redux-scc**  
  https://medium.com/onfido-tech/reducing-redux-avoiding-boilerplate-with-redux-scc-b72c80c338e5  
  https://medium.com/onfido-tech/redux-scc-update-combined-actions-and-custom-types-ce346ea91e85  Looks at how the redux-scc library allows building "store chunks", which simplify the amount of work needed to define and update a Redux store.
  
- **Redux Action Creator Creators**  
  https://hackernoon.com/redux-action-creator-creators-6684b051d4c6  
  An example of using functions that take additional arguments, and using those to generate action creators.  Includes example of using this to add analytics and promises to actions.
  
- **The only action you will ever need**  
  https://medium.com/riipen-engineering/the-only-action-you-will-ever-need-f3a42661d2dd  
  Looks at creating a reusable "fetch" action creator that can be customized to generate fetching logic for different REST API endpoints.
  
- **Redux mapStateToProps and mapDispatchToProps Shorthand**  
  https://medium.com/@atomarranger/redux-mapstatetoprops-and-mapdispatchtoprops-shorthand-67d6cd78f132  
  A quick example of the "object shorthand" supported by `connect` for `mapDispatch`, and use of Reselect's `createStructuredSelector` for equivalent behavior of `mapState`.
  
- **Less Redux Boilerplate with Union Types**  
  https://codeburst.io/less-redux-boilerplate-with-union-types-3d5fd6acb53c  
  Examples of using Elm-inspired "union types" to define Redux logic, as well as combining action creators and reducers in a single file similar to the "ducks" approach.
  
- **ARC - Simplifying async requests in Redux apps**  
  https://medium.com/front-end-hacking/arc-simplifying-async-requests-in-redux-apps-e8052b874216  Describes the "async action" pattern commonly used with Redux, and how the ARC library can simplify the process of generating actions, action creators, and reducers that work with async actions.
  
- **Abstracting Vuex/Redux Action Patterns**  
  https://medium.com/coding-stones/abstracting-vuex-redux-action-patterns-8df36b0e2fcc  
  Examples of generating action types and action creators that use similarly-formatted actions (such as FETCH_DATA_REQUEST/SUCCESS/ERROR).
  
- **Stop writing mapStateToProps, start using declarative models**  
  https://medium.com/@kyleramirez/part-1-stop-writing-mapstatetoprops-start-using-declarative-models-ce72716db9fc  
  https://medium.com/@kyleramirez/part-2-stop-writing-mapstatetoprops-start-using-declarative-models-403734a5f9ee  
  Discusses a library called ReactiveRecord, which encapsulates the process of defining client-side models for REST APIs, fetching data, and reading it from the store.
  
- **"Comments on 'reducing boilerplate'"**  
  https://www.reddit.com/r/reactjs/comments/7069ct/i_love_redux_but_i_hate_the_boilerplate/dn1mj4s/  
  A great comment on what "boilerplate" actually means, how people optimize too much for initial dev time, and how Redux improves long-term maintainability.
  
- **How to delete hundreds (or thousands) of lines of ReduxJS code**  
  https://medium.com/@ianduvall/how-to-delete-hundreds-or-thousands-of-lines-of-reduxjs-code-4736b34f7345  
  Short examples of reusable action creator and reducer logic for handling "loading" state for multiple features in an app.
  
  
#### Network Management

- **Ajax Polling in React with Redux and Sagas**  
  http://notjoshmiller.com/ajax-polling-in-react-with-redux/  
  http://notjoshmiller.com/ajax-polling-part-2-sagas/  
  Covers a couple different ways to manage the logic for AJAX polling.

- **Firebase with Redux**  
  https://medium.com/@prescottprue/firebase-with-redux-82d04f8675b9  
  Examples for combining Firebase into a Redux application
  
- **Redux: Perils of Time**  
  http://redux-perils-of-time.surge.sh/#/?presenter  
  A slideshow with some intriguing thoughts on how to manage offline experiences, cached data, and optimistic UI in a Redux app.
  
- **Introducing Redux Offline: Offline-First Architecture for Progresive Web Applications**  
  https://hackernoon.com/introducing-redux-offline-offline-first-architecture-for-progressive-web-applications-and-react-68c5167ecfe0  
  An excellent blog post explaining the need for better offline behavior in web apps, and introducing a new Redux-based library that helps manage that behavior.
  
- **Offline GraphQL Queries with Redux Offline and Apollo**  
  http://www.east5th.co/blog/2017/07/24/offline-graphql-queries-with-redux-offline-and-apollo/  
  Discussion of how to use Redux Offline to enable persistance and Apollo queries of data while offline
  
- **Redux Websocket Integration**  
  https://medium.com/@ianovenden/redux-websocket-integration-c1a0d22d3189  
  A summary of one possible approach for integrating Websocket functionality into a React/Redux application architecture.

- **What's the best way to store tokens in Redux?**  
  https://michaelwashburnjr.com/whats-the-best-way-to-store-tokens-in-redux/  
  Discusses pros and cons of storing auth tokens in app state vs localStorage, and what code should be responsible for handling the tokens.