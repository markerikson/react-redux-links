### Redux Techniques


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


#### Reducers

- **Redux Docs: Structuring Reducers**  
  http://redux.js.org/docs/recipes/StructuringReducers.html  
  Comprehensive information on writing reducers and structuring data, covering reducer composition, use of `combineReducers`, normalizing data, proper immutable updating, and more.

- **"Reducer composition without slicing state"**  
  https://www.reddit.com/r/javascript/comments/42ey9e/redux_reducer_composition_without_slicing_state/  
  Discussion of ways to organize actions and reducer logic

- **Taking Advantage of `combineReducers**  
  http://randycoulman.com/blog/2016/11/22/taking-advantage-of-combinereducers/  
  Examples of using `combineReducers` multiple times to produce a state tree, and some thoughts on tradeoffs in various approaches to reducer logic.

#### Selectors and Normalization

- **Querying a Redux Store**  
  https://medium.com/@adamrackis/querying-a-redux-store-37db8c7f3b0f  
  A look at best practices for organizing and storing data in Redux, including normalizing data and use of selector functions.
  
- **Normalizing Redux Stores for Maximum Code Reuse**  
  https://medium.com/@adamrackis/normalizing-redux-stores-for-maximum-code-reuse-ae6e3844ae95  
  Thoughts on how normalized Redux stores enable some useful data handling approaches, with examples of using selector functions to denormalize hierarchical data.
  
- **Redux Normalizr: Improve your State Management**  
  http://www.robinwieruch.de/the-soundcloud-client-in-react-redux-normalizr/  
  A tutorial describing how to use Normalizr for improved data management of nested data in Redux

- **Using normalizr.js in a Redux store**  
  https://medium.com/@mcowpercoles/using-normalizr-js-in-a-redux-store-96ab33991369  
  Some examples of using Normalizr and selectors to manage normalized data
  
- **Memoize-Immutable: efficient memoizer for Redux**  
  https://blog.prototypo.io/memoize-immutable-efficient-memoizer-for-redux-and-other-immutable-environments-59277fefa45f  
  Discusses principles of immutability and memoization, and a library they built to help memoize Redux data lookups
  
- **Two mistakes I made working with Redux**  
  http://www.mattzeunert.com/2016/06/01/redux-mistakes.html  
  Some suggestions on how to handle denormalizing data and defining actions.

- **Practical Redux: Using Redux-ORM**  
  http://blog.isquaredsoftware.com/2016/10/practical-redux-part-1-redux-orm-basics/  
  http://blog.isquaredsoftware.com/2016/10/practical-redux-part-2-redux-orm-concepts-and-techniques/  
  A look at how Redux-ORM can help manage normalized data in a Redux store, including use cases, basic usage, key concepts, and advanced techniques.


#### UI and Widget Implementations

- **"How can I display a modal dialog in Redux?"**  
  http://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions/35641680  
  Dan Abramov describes a great technique for descriptively managing React modal dialogs using Redux actions and state, by storing names of components and their props.

- **"Generic Modal Dialogs with Feature-Specific Actions"**  
  https://www.reddit.com/r/reactjs/comments/4wjmme/implement_a_confirm_modal_using_react_redux/d68ajcw?context=3  
  A follow-on to Dan's technique, with a short suggestion for using generic modal components in a variety of situations by including actions as props.
  
- **Implement a confirm modal using React & Redux**  
  http://jslancer.com/2016/08/07/implement-a-confirm-modal-using-react-redux/  
  Demonstrates wrapping up an existing modal library to be controlled by Redux actions
  
- **Implementing Search/Filter on a list in React and Redux**  
  https://medium.com/@yaoxiao1222/implementing-search-filter-a-list-on-redux-react-bb5de8d0a3ad  
  Some quick examples of using Redux to supply a list of items as a prop, and using React local component state to store a filtered version based on inputs.
  
- **Creating Reusable Generic Modal Dialogs with React and Redux**  
  https://www.packtpub.com/books/content/creating-reusable-generic-modals-react-and-redux  
  A quick look at how to get results from generic dialogs like a ColorPicker, while keeping your Redux state serializable and component structure decoupled.
  
  
#### Redux and Forms

- **Abstracted Form State with Redux-Form**  
  https://speakerdeck.com/erikras/abstracted-form-state-with-redux-form  
  Slides by the author of Redux-Form, discussing how forms work in plain HTML/Javascript, in React, and how the Redux-Form library can integrate them into Redux.
  
- **React, Redux, and Redux-Form**  
  https://jokeyrhyme.github.io/2016/06/27/react-redux-redux-form.html  
  Thoughts on the merits of using the Redux-Form library
  
- **Conversational sign-up form UI with React and Redux**  
  http://jsforallof.us/2016/09/08/conversational-sign-up-form-ui-with-react-and-redux/  
  An example of form management with Redux
  
- **Should you store your form state in Redux?**  
  http://goshakkk.name/should-i-put-form-state-into-redux/  
  Thoughts on the tradeoffs involved in storing form data in component state vs Redux, and different potential use cases.

  
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
  
  
#### Network Management

- **Ajax Polling in React with Redux and Sagas**  
  http://notjoshmiller.com/ajax-polling-in-react-with-redux/  
  http://notjoshmiller.com/ajax-polling-part-2-sagas/  
  Covers a couple different ways to manage the logic for AJAX polling.

- **Firebase with Redux**  
  https://medium.com/@prescottprue/firebase-with-redux-82d04f8675b9  
  Examples for combining Firebase into a Redux application
  
  