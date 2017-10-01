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
  
- **A Dummy's Guide to Redux and Thunk in React**  
  https://medium.com/@stowball/a-dummys-guide-to-redux-and-thunk-in-react-d8904a7005d3  
  A tutorial that shows how to take a React component that does its own data fetching, and rework it to use accept data from Redux and use a thunk action creator instead.
  
- **What the heck is a "thunk"?**  
  https://daveceddia.com/what-is-a-thunk/  
  A quick explanation for what the word "thunk" means in general, and for Redux specifically..
  
- **Understanding how redux-thunk works**  
  https://medium.com/@gethylgeorge/understanding-how-redux-thunk-works-72de3bdebc50  
  An attempt to explain both redux-thunk and Redux's applyMiddleware enhancer, by rewriting the original implementations to add logging and rework names for ease of understanding.
  
- **Async Actions with Redux Thunk Demystified**  
  http://blog.jakoblind.no/2017/04/25/async-actions-with-redux-thunk-demystified/  
  A quick look at the source code for redux-thunk, how it works, and how to use it.
  
- **Sense-ible Redux Thunk**  
  https://medium.com/sensehq/sense-ible-redux-thunk-30b866ca5914  
  Examples of how to define reusable caching and authorization handling for thunks using decorators
  
- **Returning promises from Redux action creators**  
  https://medium.com/collaborne-engineering/returning-promises-from-redux-action-creators-3035f34fa74b  
  Shows how returning a promise from a thunk action creator allows the caller to chain off the promise and execute code after the action creator is complete.
  
  
#### Side Effect Approach Comparisons
  
- **Redux side effects and you**  
  https://medium.com/javascript-and-opinions/redux-side-effects-and-you-66f2e0842fc3  
  Thoughts on the proliferation of new side effect libs for Redux, and some comparisons of the commonly used approaches.
  
- **"Controversial opinion: redux-thunk is too powerful"**  
  https://twitter.com/intelligibabble/status/800103510624727040  
  https://twitter.com/dan_abramov/status/800310164792414208  
  Some discussion on the pros and cons of redux-thunk's flexibility and usage, as well as possible issues with multiple dispatches in a row.
  
- **Idiomatic Redux: Thoughts on Thunks, Sagas, Abstractions, and Reusability**  
  http://blog.isquaredsoftware.com/2017/01/idiomatic-redux-thoughts-on-thunks-sagas-abstraction-and-reusability/  
  A response to several "thunks are bad" concerns, arguing that thunks (and sagas) are still a valid approach for managing complex sync logic and async side effects.
  
- **What are the benefits, pros, and cons of redux-thunk over redux-saga?**
  https://hashnode.com/post/what-are-the-benefits-of-redux-thunk-over-redux-saga-what-pros-and-cons-do-they-have-over-each-other-ciqvyydh7065w3g53ffalif61  
  An excellent discussion of where side effects belong in a Redux app, and how thunks and sagas can be used to handle async logic.
  
- **Keeping Redux in check**  
  https://medium.com/@georgeleeme/keeping-redux-in-check-78534504b215  
  Some tips on use of the Flux Standard Actions convention, and comparison of using redux-thunk vs redux-promise.
  
- **"Argument: We should switch from thunks to sagas"**  
  http://en.arguman.org/we-should-switch-from-redux-thunk-to-redux-saga  
  An debate flowchart with arguments for and against using thunks and sagas
  
- **The Evolution of Redux Action Creators**  
  https://medium.com/@northerneyes/the-evolution-of-redux-action-creators-2973018bf2ae  
  A comparison of ways to make action creation testable, looking at redux-thunk, a custom thunk-like middleware, and redux-saga 
  
- **What is the right way to do asynchronous operations in Redux?**  
  https://decembersoft.com/posts/what-is-the-right-way-to-do-asynchronous-operations-in-redux/  
  An excellent look at the most popular libraries for Redux side effects, with comparisons of how each one works.
  
- **Redux 4 Ways**  
  https://medium.com/react-native-training/redux-4-ways-95a130da0cdc  
  Side-by-side comparisons of implementing some basic data fetching using thunks, sagas, observables, and a promise middleware
  
- **3 Common Approaches to Side-Effects in Redux**  
  https://goshakkk.name/redux-side-effect-approaches/  
  An overview of what "side effects" are, how they relate to Redux, and the most common ways to handle side effects in a Redux app
  
- **Redux: Thunk vs Saga**  
  http://blog.jakegardner.me/redux-thunk-vs-saga/  
  A couple quick examples showing how to use thunks and sagas for the same task
  
- **ReactCasts #10: Redux Thunk Tricks**  
  https://www.youtube.com/watch?v=xihoZZU0gao  
  An excellent screencast that covers three useful tips for use of redux-thunk: thunk return values, multi-dispatch, and when to use `getState`
  
- **Redux Thunks Dispatching Other Thunks - Discussion and Best Practices**  
  https://medium.com/@talkol/redux-thunks-dispatching-other-thunks-discussion-and-best-practices-dd6c2b695ecf  
  Some excellent thoughts on when it's okay to have a thunk dispatch another thunk, and other possible approaches.
  
- **Redux-Observable Epics vs Redux Sagas**  
  https://shift.infinite.red/redux-observable-epics-vs-redux-sagas-8e53610c0eda  
  A humorous look at how redux-observable and redux-saga compare.  It recaps their backgrounds and basic ideas, then shows comparison implementations for some small tasks and rates the approaches.
  
- **Async operations in React Redux applications**  
  https://codebrahma.com/structuring-async-operations-react-redux-applications/  
  An introduction to the complexities of handling async logic in JS, and comparisons of how the same series of API calls could be handled using JS Promises, thunks, sagas, and observables.
  
- **"Redux and API/fetch calls. How do you handle them?**  
  https://twitter.com/rem/status/888361414070501376  
  A Twitter poll asking about people's preferences for handling async work in Redux.  The replies are interesting, and show a very wide variety of choices being used.
  

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
  
- **The Three 'R's: Refactoring, React, and Redux for robust async JS**  
  https://devblog.xero.com/the-three-rs-refactoring-react-and-redux-for-robust-async-js-252648a8632f  
  More information from Xero on how they have used sagas for async workflows, including splitting code up into smaller sagas that can be composed.
  
- **4 Quick Tips for Managing Many Sagas in a React-Redux-Saga App**  
  https://decembersoft.com/posts/4-tips-for-managing-many-sagas-in-a-react-redux-saga-app/  
  Some useful suggestions for structuring and organizing sagas
  
- **Implementing feature flags using React and Redux Saga**  
  http://blog.launchdarkly.com/implementing-feature-flags-in-single-page-apps-using-react-and-redux-saga/  
  A quick example of how to use sagas to manage feature flag API requests
  
- **Javascript Power Tools: Redux-Saga**  
  http://formidable.com/blog/2017/javascript-power-tools-redux-saga/  
  http://formidable.com/blog/2017/composition-patterns-in-redux-saga/  
  http://formidable.com/blog/2017/real-world-redux-saga-patterns/  
  A fantastic series that the concepts, implementation, and benefits behind Redux-Saga, including how ES6 generators are used to control function flow, how sagas can be composed together to accomplish concurrency, and practical use cases for sagas.
  
- **Managing Side Effects with Redux Saga: A Primer**  
  https://www.sigient.com/blog/managing-side-effects-with-redux-saga-a-primer-1  
  Looks at how side effects complicate testing, and how sagas use descriptions of side effects to make testing easier.  Also looks at how sagas fit into a Redux application architecture.
  
- **Exploring Redux Sagas**  
  https://medium.com/onfido-tech/exploring-redux-sagas-cc1fca2015ee  
  An excellent article that explores how to use sagas to provide a glue layer to implement decoupled business logic in a Redux application.
  
- **Redux-Saga: put() from inside a callback / File Upload Progress**  
  https://decembersoft.com/posts/redux-saga-put-from-inside-a-callback/  
  https://decembersoft.com/posts/file-upload-progress-with-redux-saga/  
  A pair of posts demonstrating how to use Redux-Saga's "event channel" feature to interact with non-Redux code
  
- **Effects as Data**  
  https://gist.github.com/iammerrick/fc4a677cea11d9c896e8d3a29a184f91  
  A small essay on the benefits of treating effects as data, and how it enables decoupling
  
- **redux-saga factories and decorators**  
  https://medium.com/@TomasEhrlich/redux-saga-factories-and-decorators-8dd9ce074923  
  Some quick examples of creating reusable sagas to reduce duplicate code
  
- **Handling action errors in Redux-Saga using Either**  
  https://medium.com/@jamiedixon/handling-errors-in-redux-saga-using-either-12671bc6cf90  
  Demonstrates an approach to handling error cases in Flux Standard Actions using the functional programming "Either" concept.
  
- **Writing more testable code with Redux-Saga**  
  https://medium.com/grey-frogs/writing-more-testable-code-with-redux-saga-c1561f995225  
  Gives examples of some sagas for managing complex async query handling logic, and how to use the redux-saga-test-plan library to help test their behavior.
  
- **Analytics on easy mode with Redux-Saga**  
  https://goshakkk.name/analytics-easy-redux-saga/  
  Quick examples of how to use Redux-Saga to implement analytics handling.
  
- **Modelling common patterns with redux-saga**  
  https://medium.com/@chanakyabhardwaj/modelling-common-patterns-with-redux-saga-464a380a37ce  
  Examples of saga logic patterns for behaviors like "first-amongst-these", "keep-doing-until", and "step-by-step".
  
- **Building an event system using Redux and Sagas**  
  http://blog.servicebot.io/building-our-event-and-user-notification-system-in-express-using-redux-and-sagas/  
  Some quick examples of using Redux-Saga in a Node Express app to handle processing for things like sending emails.
  
- **Redux Saga Retry Patterns**  
  https://medium.com/@bryanfillmer/keep-trying-redux-saga-style-b273882b9ec  
  https://codeburst.io/try-again-more-redux-saga-patterns-bfbc3ffcdc  
  A pair of articles discussing ways to handle reconnects, retries, and error handling in sagas.
  
- **Redux, Firebase, and the Saga in between**  
  https://medium.com/rumors/redux-firebase-and-the-saga-in-between-c2bd5adf6de1  
  Discussion and examples of how to use sagas to simplify and generalize interaction with Firebase in a Redux app.
  
- **When should I use a saga?**  
  https://medium.com/@felixclack/when-should-i-use-a-saga-708cb3c75e9a  
  Some quick rules of thumb for determining if building a saga is a good choice for a given feature.
  
  
  
#### Other Side Effect Approaches

- **Epic Middleware in Redux**  
  https://medium.com/@kevinsalter/epic-middleware-in-redux-e4385b6ff7c6  
  Discussion and examples of using Redux-Observable and RxJS to create "epics" which can transform actions.
  
- **Better async Redux**  
  https://blog.scottnonnenberg.com/better-async-redux-i18n-and-node-js-versions/  
  Comparisons and examples of using Redux-Loop for declarative side effects
  
- **Action Streams and Redux**  
  https://medium.com/@markusctz/action-streams-and-redux-77f8ac99c2e9  
  Examples of how Redux-Observable can simplify complex async logic
  
- **A simplified approach to calling APIs with Redux**  
  http://www.sohamkamani.com/blog/2016/06/05/redux-apis/  
  A well-written example of creating a "data service" middleware that handles API requests, as well as examples of handling some request status state.
  
- **Elm Architecture with Redux**  
  https://smallbusinessforum.co/elm-architecture-with-react-redux-redux-loop-645a67070b1a  
  A short look at how Elm handles side effects, and how Redux-Loop can help implement a similar approach in Redux
  
- **Redux-cycles**  
  http://nick.balestra.ch/talk/redux-cycles/#/0  
  A slideshow that describes the basics of Cycle.js, and how the redux-cycles library can be used to handle side effects in Redux
  
- **How to make your React app fully functional, fully reactive, and able to handle all those crazy side effects**  
  https://medium.freecodecamp.org/how-to-make-your-react-app-fully-functional-fully-reactive-and-able-to-handle-all-those-crazy-e5da8e7dac10  
  A lengthy look at Cycle.js and the redux-cycles library, with plenty of diagrams to illustrate how it handles data flow.