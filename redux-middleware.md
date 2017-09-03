### Redux Middleware

#### Tutorials

- **Exploring Redux Middlewares**  
  http://blog.krawaller.se/posts/exploring-redux-middleware/  
  Understanding middlewares through a series of small experiments

- **Understanding Redux Middleware**  
  https://medium.com/@meagle/understanding-87566abcfb7a  
  Breaks down Redux's applyMiddleware function line-by-line, and explains the concepts involved
  
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
  http://www.pshrmn.com/tutorials/react/redux-middleware/  
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