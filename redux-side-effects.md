### Redux Side Effects


#### Basic Concepts and Thunks

- **Stack Overflow: Dispatching Redux Actions with a Timeout**  
  http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559  
  Dan Abramov explains the basics of managing async behavior in Redux, walking through a progressive series of approaches (inline async calls, async action creators, thunk middleware).
  
- **Stack Overflow: Why do we need middleware for async flow in Redux?**  
  http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594  
  Dan Abramov gives reasons for using thunks and async middleware, and some useful patterns for using thunks.

- **Pure Functionality and Side Effects with Redux**  
  https://blog.hivejs.org/building-the-ui-2/  
  An overview of what side effects are, how they fit into Redux, and several approaches for managing them.
  
- **"Async Redux workflow: calling actions outside Redux?"**  
  https://www.reddit.com/r/reactjs/comments/4upe9t/async_redux_workflow_calling_actions_outside_redux/d5sgy5s?context=3  
  A comment explaining why using action creator functions is a good practice
  
- **Why doesn't Redux support AJAX out of the box?**  
  http://goshakkk.name/redux-no-ajax-by-default/  
  Looks at how AJAX calls fit into a Redux application
  
- **Adding Customized Asynchrony to Redux**  
  https://anyperk.engineering/im-lauren-and-i-m-a-frontend-apprentice-here-at-anyperk-a1a40106d231  
  A quick introduction to some of the libraries that can be used to manage asynchronous behavior in Redux.


#### Sagas

- **Master Complex Redux Workflows with Sagas**  
  http://konkle.us/master-complex-redux-workflows-with-sagas/  
  Describes what sagas are, how Redux-Saga uses generators to run sagas, some potential concerns, and how to use them.

- **Stack Overflow: Why do we need middleware for async flux in Redux?**  
  http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34623840#34623840  
  A comparison of imperative thunks vs declarative sagas, and some of the benefits that sagas can provide for testing and decoupling of logic.

- **Managing Side Effects in React + Redux using Sagas**  
  http://jaysoo.ca/2016/01/03/managing-processes-in-redux-using-sagas/  
  Demonstrates various ways to implement a Timer app as a state machine, including using sagas to manage the periodic updates.
  
- **Persist Redux State By Using Sagas**  
  http://engineering.invisionapp.com/post/persist-redux-state-by-using-sagas/  
  A very well-written set of examples showing how to use sagas to implement some complex store persistence logic.
  
- **Handling async in Redux with Sagas**  
  http://wecodetheweb.com/2016/10/01/handling-async-in-redux-with-sagas/  
  Covers the basic concepts and syntax of sagas, and how they can improve testability.  (Updated version of a 2015 post, covering the latest version of redux-saga.)
  
- **Redux Saga conceptual diagram**  
  https://twitter.com/kuy/status/731484272234663937  
  A useful diagram illustrating the various things a saga can do
  
- **"Redux Sagas benefits?"**  
  https://www.reddit.com/r/reactjs/comments/4ng8rr/redux_sagas_benefits/  
  Discussion of when and why you might want to use sagas, with some great examples in the comments.
  
- **Manage Side Effects Efficiently with Redux Saga**  
  https://youtu.be/QJVdcIlqGwc  
  A presentation describing the concepts of generators and sagas.
  
- **Redux Saga conceptual diagram**  
  https://qiita-image-store.s3.amazonaws.com/0/69860/8cc1a873-c675-9009-570d-9684da4a704f.png  
  A nifty diagram from @kuy illustrating the general interaction of Redux Saga's async flow operators 
  
- **Async Operations using Redux-Saga**  
  https://medium.com/@andresmijares25/async-operations-using-redux-saga-2ba02ae077b3  
  An example of using Redux-Saga to coordinate multiple async calls based on another article's flight data scenario.

- **Should I use redux-saga or not?**  
  https://speakerdeck.com/kuy/should-i-use-redux-saga-or-not  
  A presentation from Yuki Kodama, comparing side effect approaches.  In Japanese, but still has a number of useful diagrams that can be understood by English speakers.
  
- **Interview with Redux-Saga Author Yassine Eloaufi**  
  http://survivejs.com/blog/redux-saga-interview/  
  An interview with the author of Redux-Saga, where he describes some of its concepts and history

- **Lazy registration with Redux and Sagas**  
  http://goshakkk.name/lazy-auth-redux-saga-flow/  
  Examples of using Redux-Saga to implement an async series of user interactions.
  
- **A Saga that led Xero to Redux**  
  https://devblog.xero.com/a-saga-that-led-xero-to-redux-aa1361b9a800  
  Examples of how Xero's async logic for their dashboard evolved over team, from nested callbacks to promises to Redux with sagas