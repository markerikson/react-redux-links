### Redux Middleware

#### Tutorials

- **Exploring Redux Middlewares**  
  http://blog.krawaller.se/posts/exploring-redux-middleware/  
  Understanding middlewares through a series of small experiments

- **Understanding Redux Middleware**  
  https://medium.com/@meagle/understanding-87566abcfb7a  
  Breaks down Redux's applyMiddleware function line-by-line, and explains the concepts involved

- **Introduction to Redux Saga**  
  https://www.loginradius.com/blog/async/introduction-to-redux-saga/  
  An easy to understand high level introduction to Redux Saga.  
  
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
  https://github.com/pshrmn/notes/blob/master/redux/redux-middleware.md  
  An overview of what middleware is, how `applyMiddleware` works, and how to write middleware.
  
- **Redux Middleware: Behind the Scenes**  
  http://briantroncone.com/?p=529  
  Digs into the concepts and implementation of middleware.
  
- **Middlewares and React Redux Lifecycle**  
  https://medium.com/@rajaraodv/using-middlewares-in-react-redux-apps-f7c9652610c6  
  A description of what a middleware is, and how it works in Redux
  
- **ReactCasts #6: Redux Middleware**  
  https://www.youtube.com/watch?v=T-qtHI1qHIg  
  A screencast that describes how middleware fit into Redux, their uses, and how to implement a custom middleware 
  
- **Redux Middleware**  
  https://vmayakumar.wordpress.com/2016/12/27/redux-middleware/  
  Some analogies for understanding middleware in terms of the OOP "Decorator Pattern" vs  Functional Programming composition
  
- **Workshop Slides: Redux Middleware**  
  http://www.slideshare.net/visualengin/workshop-22-reactredux-m  
  A slideshow that explains how Redux middleware work, with several helpful visualizations
  
- **Understanding Redux Middleware and Writing Custom Ones**  
  https://dev.to/imwiss/understanding-redux-middleware-and-writing-custom-ones  
  Describes the concept of middleware in Redux, possible use cases, and gives an example of writing a middleware to handle caching.
  
- **Build your own Redux middleware**  
  https://blog.campvanilla.com/redux-middleware-basics-getting-started-17dc31c6435c  
  A good explanation of how middleware fit into the Redux data flow, how middleware are defined, and how to write a simple logging middleware.
  
- **Learning Redux Middlewares by Reading Their Source**  
  https://www.ynonperek.com/2017/08/21/learning-redux-middlewares-by-reading-their-source/  
  Explores the source code for redux-thunk, redux-promise, and redux-batch-middleware to help understand how middleware work.
  

#### Middleware Techniques

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
  
- **Defining user on-boarding flows with Redux middleware**  
  https://medium.com/@JohnRandom/defining-user-on-boarding-flows-with-redux-middlewares-217885acbafc  
  Demonstrates implementing an on-boarding feature by implementing a Redux middleware to track user behavior and dispatch actions in response.
  
- **"Do I always need to return a value from a Redux middleware?"**  
  https://stackoverflow.com/questions/45964129/do-i-always-need-to-return-a-value-from-a-redux-middleware/45964310#45964310  
  My answer to a question about whether middleware should do `return next(action)`.  Short version: yes, always, unless you want to alter expected behavior.
  
- **Practical Advanced Redux Webinar: Redux Middleware**  
  https://www.youtube.com/watch?v=DqWiuvuK_78  
  A recorded screenshare livestream that discusses the usefulness of Redux middleware, and demonstrates building middleware for fetching data, logging, and throttling.
  
- **Redux: Drawing the Lines between Actions and Middleware**  
  https://michaelwashburnjr.com/redux-actions-middleware/  
  Compares examples of behavior between thunks and middleware, and discusses when you might want to implement behavior in a middleware.
  
- **Redux Middleware and Enhancers**  
  https://chariotsolutions.com/blog/post/redux-middleware-and-enhancers-getting-redux-to-log-debug-and-process-async-work/  
  Describes some common Redux middleware and their uses, as well as how to set up the Redux DevTools enhancer for debugging. 
  
- **Redux analytics, without middleware**  
  http://web.archive.org/web/20170617100422/http://blog.reactandbethankful.com/posts/2016/09/27/redux-analytics-without-middleware/  
  Discusses pros and cons of using middleware for analytics, and shows how to create a store enhancer that wraps `subscribe` to allow providing selectors and callbacks.
  
- **How to use Redux middleware to decouple AJAX call?**  
  http://www.albertgao.xyz/2017/12/07/how-to-use-redux-middleware-to-decouple-ajax-call/  
  Demonstrates writing a middleware that accepts a plain object description of an HTTP request, and executes the request
  
- **Custom Form Validation in React with Redux Middleware**  
  http://tech.tunecore.com/redux-form-validation-middleware  
  A detailed example of how middleware can be used to implement some complex form validation logic in a centralized way.
