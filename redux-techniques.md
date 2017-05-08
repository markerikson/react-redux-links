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
  
- **Time Travel in React Redux apps using the Redux DevTools**  
  https://onsen.io/blog/react-redux-devtools-with-time-travel/  
  Examples of configuring a Redux store to use the DevTools enhancers, and using both the DevTools components and the browser extension for debugging.


#### Reducers

- **Redux Docs: Structuring Reducers**  
  http://redux.js.org/docs/recipes/StructuringReducers.html  
  Comprehensive information on writing reducers and structuring data, covering reducer composition, use of `combineReducers`, normalizing data, proper immutable updating, and more.

- **"Reducer composition without slicing state"**  
  https://www.reddit.com/r/javascript/comments/42ey9e/redux_reducer_composition_without_slicing_state/  
  Discussion of ways to organize actions and reducer logic

- **Taking Advantage of `combineReducers`**  
  http://randycoulman.com/blog/2016/11/22/taking-advantage-of-combinereducers/  
  Examples of using `combineReducers` multiple times to produce a state tree, and some thoughts on tradeoffs in various approaches to reducer logic.
  
- **Modifying a Leaf of the Redux State Tree**  
  http://cmichel.io/modifying-a-leaf-of-the-redux-state-tree/  
  Some useful observations on how to properly do deep immutable updates.
  
- **"How to dynamically load reducers for code splitting in a Redux application?"**  
  http://stackoverflow.com/questions/32968016/how-to-dynamically-load-reducers-for-code-splitting-in-a-redux-application  
  Dan Abramov gives a basic exapmle of how to rebuild and replace the root reducer function at runtime
  
- **Inject reducer arbitrarily rather than top level for Redux store to replace reducer**  
  https://medium.com/@jimmy_shen/inject-reducer-arbitrarily-rather-than-top-level-for-redux-store-to-replace-reducer-fdc1060a6a7  
  A quick example of the basic approach to injecting additional reducers at runtime
  
- **State Snapshots in Redux**  
  http://kyleshevlin.com/state-snapshots-in-redux/  
  Describes a useful technique for saving copies of state slices on command, and re-applying those copies at a later point to ensure a known starting point for further actions.
  
- **"Problems with Flux"**  
  http://www.code-experience.com/problems-with-flux/  
  Discusses the idea of having all state updates for an action listed in one place, vs spread throughout the store.  Written shortly after the release of Redux, but definitely relevant.
  
- **Redux Tree**  
  https://blog.shakacode.com/redux-tree-efc9e3d22d6e  
  Looks at structuring a reducer/state tree as "branches" and "leaves", and introduces the idea of an "interaction" to encapsulate all related state changes for a given action, with a library to implement the idea.
  
- **Reducer composition with Higher Order Reducers**  
  https://medium.com/@mange_vibration/reducer-composition-with-higher-order-reducers-35c3977ed08f  
  Some great examples of writing small functions that can be composed together to perform larger specific reducer tasks, such as providing initial state, filtering, updating specific keys, and more.
  

#### Selectors and Normalization

**Related topics**: 
- [Redux Architecture - Encapsulation](./redux-architecture.md#encapsulation-and-reusability)
- [Redux Performance](./react-performance.md#redux-performance)


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
  
- **"How do you add/remove to a redux store generated with normalizr?**  
  http://stackoverflow.com/questions/34954726/how-do-you-add-remove-to-a-redux-store-generated-with-normalizr  
  Stack Overflow discussion of how to handle updates to normalized data

- **"Any deep-dive/advanced tutorials on reselect?"**  
  https://www.reddit.com/r/reactjs/comments/5dxasp/any_deepdiveadvanced_tutorials_on_reselect/  
  Discussion on passing arguments to Reselect selectors, and how to use "factory functions" to define per-component selectors for Redux `mapState` functions

- **ReactCasts #8: Selectors in Redux**  
  https://www.youtube.com/watch?v=frT3to2ACCw  
  A great overview of why and how to use selector functions to retrieve data from the store, and derive additional data from store values
  
- **GraphQL is not only for Backend**  
  https://riad.blog/2017/01/07/graphql-is-not-only-for-backend-react-redux/  
  A look at how to use GraphQL to query into a Redux store
  
- **Dissecting Twitter's Redux Store**  
  https://medium.com/statuscode/dissecting-twitters-redux-store-d7280b62c6b1  
  https://medium.com/@nuncamind/diving-deeper-into-twitters-redux-store-adventures-in-minified-vendor-javascript-67fbac5dc219  
  An informative look at the contents of the Redux store for Twitter's new mobile site.  The second article shows how to dig through the minified JS to enable use of the Redux DevTools against a production site.
  
- **Advanced Redux Entity Normalization**  
  https://medium.com/@dcousineau/advanced-redux-entity-normalization-f5f1fe2aefc5  
  Describes a "keyWindow" concept for tracking subsets of entities in state, similar to an SQL "view".  A useful extension to the idea of normalized data.
  
- **"Why are you supposed to normalize data in Redux?"**  
  https://twitter.com/AdamRackis/status/847883670950219776  
  A Twitter thread with some excellent discussion, explaining why use of normalized data is encouraged with Redux.
  
- **Redux Clerk: Reusable action creators and reducers for async CRUD**  
  https://inside.getambassador.com/redux-clerk-reusable-action-creators-and-reducers-for-async-crud-b0b6954f7056  
  Discussion of a library that tries to reduce the repetitive nature of async CRUD work in Redux


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
  
- **Animating with React, Redux, and D3**  
  https://medium.com/swizec-a-geek-with-a-hat/animating-with-react-redux-and-d3-80852153a25b  
  Explanation and examples of drawing animated particles using D3 to calculate new positions, Redux to store the state, and React to render them.
  
- **Open Sourcing a Redux Component**  
  https://medium.com/@itsBenCripps/open-sourcing-a-redux-component-bb82f260ff62  
  Details how the author developed a complex React+Redux grid component, including HTML structure, proper use of Immutable.js for good perf, and lib exports.
  
- **Scalable Modals with React and Redux**  
  https://codersmind.com/scalable-modals-react-redux/  
  Demonstrates implementing the basic Redux modal manager technique described by Dan Abramov in his Stack Overflow answer.
  
- **A Redux-Saga Implementation of Modal Confirmation Dialogs in React**  
  https://decembersoft.com/posts/a-redux-saga-implementation-of-modal-confirmation-dialogs-in-react-redux/  
  Some examples of using sagas for controlling flow of async calls and dialog management
  
  
#### Redux and Forms

- **Practical Redux, Part 7: Form Change Handling, Data Editing, and Feature Reducers**  
  http://blog.isquaredsoftware.com/2017/01/practical-redux-part-7-forms-editing-reducers/  
  Demonstrates how to use a custom form wrapper component to buffer input change events
  
- **Practical Redux, Part 8: Form Draft Data Management**  
  http://blog.isquaredsoftware.com/2017/01/practical-redux-part-8-form-draft-data-management/  
  Discusses how to implement logic to handle "draft/work-in-progress" data while editing items
  
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
  
- **Writing maintainable forms with Redux**  
  https://medium.com/@SBoudrias/writing-maintainable-forms-with-redux-2ef30b5d0e35  
  Some basic examples for handling validation, loading initial data, and change tracking in forms.
  
- **Using forms in React-Redux: Tips and Tricks**  
  https://medium.com/@royisch/using-forms-in-react-redux-tips-and-tricks-48ad9c7522f6  
  Some helpful suggestions for using Redux-Form to manage forms in a Redux app
  
- **Dealing with forms in React/Redux - A simple pattern**  
  https://medium.com/@jonasjensen/dealing-with-forms-in-react-redux-a-simple-pattern-7b94b393eb26  
  Helpful examples for writing some simple generic form-handling reducers and action creators

  
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
  
