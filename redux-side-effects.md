### Redux Side Effects


#### Basic Concepts and Thunks

- **Stack Overflow: Dispatching Redux Actions with a Timeout**  
  http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559  
  Dan Abramov explains the basics of managing async behavior in Redux, walking through a progressive series of approaches (inline async calls, async action creators, thunk middleware).
  
- **Stack Overflow: Why do we need middleware for async flow in Redux?**  
  http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594  
  Dan Abramov gives reasons for using thunks and async middleware, and some useful patterns for using thunks.


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
  
- **Handling Async in Redux with Sagas**  
  http://wecodetheweb.com/2016/01/23/handling-async-in-redux-with-sagas/  
  Covers the basic concepts and syntax of sagas, and how they can improve testability.
  
  
  
