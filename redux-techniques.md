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



#### Other
- **Applying Redux Reducers to Arrays**  
  http://blog.scottlogic.com/2016/05/19/redux-reducer-arrays.html  
  Looks at one way to implement the classic "multiple instances of one connected component" issue in Redux.
  
- **Checking React and Redux Code with Flow**  
  http://djcordhose.github.io/react-intro-live-coding/2016_jsunconf.html#/  
  A slideshow that shows the basics of adding type information to Redux-based code 
  
- **Using Redux with Flow**  
  http://frantic.im/using-redux-with-flow  
  Covers how to use Flow typing with Redux
  
- **Ajax Polling in React with Redux and Sagas**  
  http://notjoshmiller.com/ajax-polling-in-react-with-redux/  
  http://notjoshmiller.com/ajax-polling-part-2-sagas/  
  Covers a couple different ways to manage the logic for AJAX polling.
  
- **"How can I display a modal dialog in Redux that performs asynchronous actions?"**  
  http://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions  
  A detailed answer describing how you can declaratively drive pieces of your UI by putting descriptive pieces of data into your state (such as the name of the current dialog component to show, and what props that dialog should have)
  
- **Two mistakes I made working with Redux**  
  http://www.mattzeunert.com/2016/06/01/redux-mistakes.html  
  Some suggestions on how to handle denormalizing data and defining actions.
  
- **Encapsulation in Redux: the Right Way to Write Reusable Components**  
  http://blog.javascripting.com/2016/02/02/encapsulation-in-redux/  
  A look at one way to write encapsulated action handling in Redux
  
- **Scalable Single-Page Application Architecture with Redux and Angular 2**  
  http://blog.mgechev.com/2016/04/10/scalable-javascript-single-page-app-angular2-application-architecture/  
  An in-depth article covering how to architect an application using Redux, Angular 2, and RxJS.  
  
- **Querying a Redux Store**  
  https://medium.com/@adamrackis/querying-a-redux-store-37db8c7f3b0f  
  A look at best practices for organizing and storing data in Redux, including normalizing data and use of selector functions.