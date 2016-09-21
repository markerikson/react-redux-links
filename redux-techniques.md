### Redux Techniques



#### Middlewares
- **Two Weird Tricks with Redux**  
  http://jlongster.com/Two-Weird-Tricks-with-Redux  
  https://news.ycombinator.com/item?id=11488633  
  James Longster describes a couple useful approaches he found while writing the Firefox Developer Tools: checking for specific actions using a middleware, and managing multiple async requests.  The HN comments include some useful discussion.
  
- **Redux Hack: Custom Thunk APIs**  
  http://chrispearce.co/redux-quick-hack-custom-thunk-apis/  
  Demonstrates writing a custom thunk middleware that injects additional dependencies into thunks.

- **Connecting Redux to your API**  
  https://blog.boldlisting.com/connecting-redux-to-your-api-eac51ad9ff89  
  Describes imperative and declarative approaches to managing request data and metadata
  
- **Fix Ugly JSON Api Responses With Redux Middleware**  
  http://blog.benwiley.org/fix-json-responses-redux-middleware/  
  Sets up a sample project that requests JSON data, then shows how to use some custom middleware to transform the response.
  
- **You Aren't Using Redux Middleware Enough**  
  https://medium.com/@jacobp100/you-arent-using-redux-middleware-enough-94ffe991e6  
  Suggestions for using middleware to solve a number of interesting use cases

  
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


#### Type Checking

- **Checking React and Redux Code with Flow**  
  http://djcordhose.github.io/react-intro-live-coding/2016_jsunconf.html#/  
  A slideshow that shows the basics of adding type information to Redux-based code 
  
- **Using Redux with Flow**  
  http://frantic.im/using-redux-with-flow  
  Covers how to use Flow typing with Redux

- **Type Checking with Flow in React + Redux**  
  http://www.robinwieruch.de/the-soundcloud-client-in-react-redux-flow/  
  
- **Redux Flow Tutorial**  
  http://dchambers.github.io/articles/redux-flow-tutorial/  
  Covers how to set up Flow for type-checking a Redux application


#### Other
- **Applying Redux Reducers to Arrays**  
  http://blog.scottlogic.com/2016/05/19/redux-reducer-arrays.html  
  Looks at one way to implement the classic "multiple instances of one connected component" issue in Redux.
  
- **Ajax Polling in React with Redux and Sagas**  
  http://notjoshmiller.com/ajax-polling-in-react-with-redux/  
  http://notjoshmiller.com/ajax-polling-part-2-sagas/  
  Covers a couple different ways to manage the logic for AJAX polling.
  
- **"How can I display a modal dialog in Redux that performs asynchronous actions?"**  
  http://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions  
  A detailed answer describing how you can declaratively drive pieces of your UI by putting descriptive pieces of data into your state (such as the name of the current dialog component to show, and what props that dialog should have)
  
- **Implement a confirm modal using React & Redux**  
  http://jslancer.com/2016/08/07/implement-a-confirm-modal-using-react-redux/  
  Demonstrates wrapping up an existing modal library to be controlled by Redux actions
  
- **Two mistakes I made working with Redux**  
  http://www.mattzeunert.com/2016/06/01/redux-mistakes.html  
  Some suggestions on how to handle denormalizing data and defining actions.
  
- **Encapsulation in Redux: the Right Way to Write Reusable Components**  
  http://blog.javascripting.com/2016/02/02/encapsulation-in-redux/  
  A look at one way to write encapsulated action handling in Redux
  
- **Querying a Redux Store**  
  https://medium.com/@adamrackis/querying-a-redux-store-37db8c7f3b0f  
  A look at best practices for organizing and storing data in Redux, including normalizing data and use of selector functions.
  
- **React, Redux, and Redux-Form**  
  https://jokeyrhyme.github.io/2016/06/27/react-redux-redux-form.html  
  Thoughts on the merits of using the Redux-Form library
  
- **A Quick Look at the React and Redux DevTools**  
  http://mediatemple.net/blog/tips/a-quick-look-at-the-react-and-redux-devtools/  
  An intro to using the React DevTools and Redux DevTools extensions for debugging
  
- **Real-World React and Redux**  
  https://dzone.com/articles/real-world-reactjs-and-redux-part-1  
  https://dzone.com/articles/real-world-reactjs-and-redux-part-2  
  A series of articles covering practical architecture lessons learned from building Redux apps, especially regarding use of custom middleware
  
- **Connecting the Linode API to Redux with Higher-Order Functions**  
  https://engineering.linode.com/2016/08/17/Using-metaprogramming-in-the-manager.html  
  Linode explains how they generate customized action creators and reducers to talk to different parts of their API
  
- **A Finite State Machine Helper for Redux**  
  https://hackernoon.com/a-finite-state-machine-helper-for-redux-c18519643719  
  Describes a small but useful library for managing state machines using Redux reducers.
  
- **Conversational sign-up form UI with React and Redux**  
  http://jsforallof.us/2016/09/08/conversational-sign-up-form-ui-with-react-and-redux/  
  An example of form management with Redux
  
  
#### UI and Widget Implementations

- **"How can I display a modal dialog in Redux?"**  
  http://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions/35641680  
  Dan Abramov describes a great technique for descriptively managing React modal dialogs using Redux actions and state

- **"Generic Modal Dialogs with Feature-Specific Actions"**  
  https://www.reddit.com/r/reactjs/comments/4wjmme/implement_a_confirm_modal_using_react_redux/d68ajcw?context=3  
  A follow-on to Dan's technique, with a short suggestion for using generic modal components in a variety of situations by including actions as props.
  
  
  
#### Variations on Redux Architectures

- **Redux Saga in Action**  
  https://medium.com/@totaldis/redux-saga-in-action-s-f7d11cffa35a  
  Some interesting thoughts on ways to organize the majority of your app's logic using redux-saga
  
- **Scalable Single-Page Application Architecture with Redux and Angular 2**  
  http://blog.mgechev.com/2016/04/10/scalable-javascript-single-page-app-angular2-application-architecture/  
  An in-depth article covering how to architect an application using Redux, Angular 2, and RxJS.  
  
- **Redux and the Elm Architecture**  
  http://salsita.github.io/redux-elm/  
  Redux lacks built-in abstractions for real-world, maintainable, scalable applications. In particular, it is difficult to create and distributed encapsulated, reusable components.  The Elm Architecture clearly addresses some important areas where Redux alone is lacking.
  
- **Scaleable FE with Redux and Elm Architecture**  
  https://medium.com/@hunterbmt/scaleable-fe-with-redux-and-elm-architecture-c6812ed0125e  
  Examples of using Elm-style approaches to writing Redux code
  
- **redux-scuttlebutt; eventually consistent shared state among peers**  
  https://medium.com/@grrowl/redux-scuttlebutt-eventually-consistent-shared-state-among-peers-191d48102079  
  Describes how to use the Redux-Scuttlebutt library to sync actions and updates between multiple instances of a Redux application
  
- **Write Better Redux with redux-module-builder**  
  https://www.fullstackreact.com/articles/better-redux-module-management/  
  Describes how to use the utilities included in the redux-module-builder package to better organize a Redux application
  
- **The Elegance of React, Redux, and Ramda**  
  https://medium.com/javascript-inside/the-elegance-of-react-ebc21a2dcd19  
  Demonstrates ways to use Ramda to compose together React components and Redux behavior