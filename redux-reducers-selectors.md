### Redux Reducers and Selectors


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
  
- **The Power of Higher-Order Reducers**  
  http://slides.com/omnidan/hor#/  
  A slideshow from the author of redux-undo and other libraries, explaining the concept of higher-order reducers and how they can be used
  
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
  
- **Using Currying to Compose Reducers**  
  http://www.guyzissman.com/posts/pipe-reducers/  
  Some short but helpful examples of how currying functions can be used to reuse reducer logic for similar use cases.
  
- **Higher Order Reducers - It just sounds scary**  
  https://medium.com/@danielkagan/high-order-reducers-it-just-sounds-scary-2b9e5dbfc705  
  Explains how reducers can be composed like Lego bricks to create reusable and testable reducer logic.
  
- **Functional Redux Reducers with Ramda**  
  https://alligator.io/react/functional-redux-reducers-with-ramda/  
  Shows how to write a somewhat complex Redux reducer using only composition of functions from the Ramda library
  
- **Combine Redux reducers like a Tetris ninja**  
  https://engineering.legalstart.fr/combine-redux-reducers-like-a-tetris-ninja-6f4eb690aed5  
  Discusses the intended use case and limitations of `combineReducers`, and presents a custom utility called `combineMultiKeyReducers` that will pass along specified slices of state to a reducer.
  
- **A small trick to write clean reducers**  
  https://hackernoon.com/a-small-trick-to-write-clean-reducers-a0b1b1eff3d2  
  Shows a contrived example of updating deeply nested state, and discusses use of `lodash/fp` to simplify the update logic instead.
  
- **Dynamic Store Injection for Redux**  
  https://docs.google.com/presentation/d/1JA9hhBgx9-k0sHO9UVSTiD1WTBvsZJ13cWIudUao9vE/edit#slide=id.gcb9a0b074_1_0  
  A slideshow that demonstrates the basic approach for dynamically adding reducers at runtime.
  
- **State Snapshots with Redux**  
  https://medium.com/@kyleshevlin/state-snapshots-with-redux-209884cca170  
  Describes a useful technique for saving known state values and using those to reset or restore an earlier state.
  
- **Code splitting Redux reducers**  
  https://medium.com/front-end-hacking/code-splitting-redux-reducers-4073db30c72e  
  Comprehensive instructions on how to properly code-split reducers for dynamic loading at runtime.
  
- **Dynamic Redux Reducers**  
  https://tylergaw.com/articles/dynamic-redux-reducers/  
  Demonstrates setting up the "async reducers" approach described by Dan Abramov, and adding reducers based on routes using HOCs to abstract the process.


#### Selectors

- **Idiomatic Redux: Using Reselect Selectors for Performance and Encapsulation**  
    http://blog.isquaredsoftware.com/2017/12/idiomatic-redux-using-reselect-selectors/  
    Introduces the core concepts of using selector functions to derive data from a Redux store, memoizing functions for performance, how to use the Reselect library to create memoized selector functions, and advanced techniques for working with selectors when writing `mapState` functions for `connect`.
    
- **ReactCasts #8: Selectors in Redux**  
  https://www.youtube.com/watch?v=frT3to2ACCw  
  A great overview of why and how to use selector functions to retrieve data from the store, and derive additional data from store values
  
- **React, Reselect, and Redux**  
  https://medium.com/@parkerdan/react-reselect-and-redux-b34017f8194c  
  An explanation of how Reselect's memoized selector functions are useful in Redux apps, and how to create unique selector instances for each component instance.
  
- **Use Selectors in Redux for Great Good**  
  https://medium.com/@TomasEhrlich/use-selectors-in-redux-for-great-good-59286ce2e2a1  
  A short article explaining the importance of selectors, with a few examples of how they benefit applications and how to use them.
  
- **Reselect with Redux and React**  
  https://www.youtube.com/watch?v=6Xwo5mVxDqI  
  A screencast that introduces the Reselect library and discusses why it's useful in Redux apps
  
- **Optimizing React Redux Application Development with Reselect**  
  https://codebrahma.com/reselect-tutorial-optimizing-react-redux-application-development-with-reselect/  
  A good tutorial on Reselect.  Covers the concept of "selector functions", how to use Reselect's API, and how to use memoized selectors to improve performance.
  
- **Usage of Reselect in a React-Redux Application**  
  https://dashbouquet.com/blog/frontend-development/usage-of-reselect-in-a-react-redux-application  
  Discusses the importance of memoized selectors for performance, and good practices for using Reselect.
  
- **Redux: Up your game with selectors**  
  https://medium.com/@emilycoco/redux-up-your-game-with-selectors-9aee3a6928ae  
  A quick look at the benefits of using selector functions to encapsulate looking up data from the store.

- **Better Redux Selectors with Ramda**  
  https://medium.com/@grrttn/better-redux-selectors-with-ramda-c1ab7af3f16  
  A long article that describes how to use the Ramda FP utility library to create selectors, including use of functional composition.
  
- **Selectors: Slice your concerns like butter!**  
  https://bmbarker90.github.io/selectors-presentation/#/  
  A slideshow that discusses what selector functions are and why you would want to use them.

- **Reselect's Memoization in 3 Functions**  
  https://hackernoon.com/reselect-style-memoization-in-3-functions-aff30f8cba11  
  A dive into the Reselect source code, with explanations of memoization concepts and how Reselect implements memoization.
  
- **Memoize-Immutable: efficient memoizer for Redux**  
  https://blog.prototypo.io/memoize-immutable-efficient-memoizer-for-redux-and-other-immutable-environments-59277fefa45f  
  Discusses principles of immutability and memoization, and a library they built to help memoize Redux data lookups
  
- **"Any deep-dive/advanced tutorials on reselect?"**  
  https://www.reddit.com/r/reactjs/comments/5dxasp/any_deepdiveadvanced_tutorials_on_reselect/  
  Discussion on passing arguments to Reselect selectors, and how to use "factory functions" to define per-component selectors for Redux `mapState` functions
  
- **Selectors in Redux are a MUST**  
  https://hackernoon.com/selectors-in-redux-are-a-must-d6b0637c79b7  
  Examples of how nested Redux state can be difficult to work with, how to separate and structure domain data and UI data, and how and why to write selectors that extract and reshape the data as needed for different parts of the application.
  
- **Be Selective With Your State**  
  https://medium.com/riipen-engineering/be-selective-with-your-state-8f1be76cb9f4  
  A helpful overview of when and why to use selectors and Reselect with Redux, some issues with using selectors in multiple components, and using `re-reselect` to create "cached" selectors.
  
- **Scaling data selection on the client**  
  https://medium.com/@skovy/scaling-data-selection-on-the-client-5e4411de6984  
  Describes several reasons to use selector functions, and gives examples of writing selectors to handle normalized state.
  

#### Normalization

**Related topics**: 
- [Redux Architecture - Encapsulation](./redux-architecture.md#encapsulation-and-reusability)
- [Redux Performance](./react-performance.md#redux-performance)

- **Querying a Redux Store**  
  https://medium.com/@adamrackis/querying-a-redux-store-37db8c7f3b0f  
  A look at best practices for organizing and storing data in Redux, including normalizing data and use of selector functions.
  
- **Normalizing Redux Stores for Maximum Code Reuse**  
  https://medium.com/@adamrackis/normalizing-redux-stores-for-maximum-code-reuse-ae6e3844ae95  
  Thoughts on how normalized Redux stores enable some useful data handling approaches, with examples of using selector functions to denormalize hierarchical data.
  
- **Practical Redux: Using Redux-ORM**  
  http://blog.isquaredsoftware.com/2016/10/practical-redux-part-1-redux-orm-basics/  
  http://blog.isquaredsoftware.com/2016/10/practical-redux-part-2-redux-orm-concepts-and-techniques/  
  A look at how Redux-ORM can help manage normalized data in a Redux store, including use cases, basic usage, key concepts, and advanced techniques.
  
- **Advanced Redux Entity Normalization**  
  https://medium.com/@dcousineau/advanced-redux-entity-normalization-f5f1fe2aefc5  
  Describes a "keyWindow" concept for tracking subsets of entities in state, similar to an SQL "view".  A useful extension to the idea of normalized data.
  
- **Redux Normalizr: Improve your State Management**  
  http://www.robinwieruch.de/the-soundcloud-client-in-react-redux-normalizr/  
  A tutorial describing how to use Normalizr for improved data management of nested data in Redux

- **Using normalizr.js in a Redux store**  
  https://medium.com/@mcowpercoles/using-normalizr-js-in-a-redux-store-96ab33991369  
  Some examples of using Normalizr and selectors to manage normalized data
  
- **Two mistakes I made working with Redux**  
  http://www.mattzeunert.com/2016/06/01/redux-mistakes.html  
  Some suggestions on how to handle denormalizing data and defining actions.
  
- **"How do you add/remove to a redux store generated with normalizr?**  
  http://stackoverflow.com/questions/34954726/how-do-you-add-remove-to-a-redux-store-generated-with-normalizr  
  Stack Overflow discussion of how to handle updates to normalized data

- **GraphQL is not only for Backend**  
  https://riad.blog/2017/01/07/graphql-is-not-only-for-backend-react-redux/  
  A look at how to use GraphQL to query into a Redux store
  
- **Dissecting Twitter's Redux Store**  
  https://medium.com/statuscode/dissecting-twitters-redux-store-d7280b62c6b1  
  https://medium.com/@nuncamind/diving-deeper-into-twitters-redux-store-adventures-in-minified-vendor-javascript-67fbac5dc219  
  An informative look at the contents of the Redux store for Twitter's new mobile site.  The second article shows how to dig through the minified JS to enable use of the Redux DevTools against a production site.
  
- **"Why are you supposed to normalize data in Redux?"**  
  https://twitter.com/AdamRackis/status/847883670950219776  
  A Twitter thread with some excellent discussion, explaining why use of normalized data is encouraged with Redux.
  
- **Redux Clerk: Reusable action creators and reducers for async CRUD**  
  https://inside.getambassador.com/redux-clerk-reusable-action-creators-and-reducers-for-async-crud-b0b6954f7056  
  Discussion of a library that tries to reduce the repetitive nature of async CRUD work in Redux
  
- **json-api-normalizer: An Easy Way To Integrate the JSON API and Redux**  
  https://www.smashingmagazine.com/2017/05/json-api-normalizer-redux/  
  An in-depth article discussing why normalization of data is a good practice with Redux, and how use of the JSON API format can make normalized data easier to work with.
  
- **How I Stumbled Upon Normalizing Redux State**  
  http://kyleshevlin.com/how-i-stumbled-upon-normalizing-redux-state/  
  A short summary of the benefits and concept behind normalizing state

- **The only reducer you will ever need**  
  https://medium.com/riipen-engineering/the-only-reducer-you-will-ever-need-4dd41206f980  
  Demonstrates using Normalizr and seamless-immutable to write a generic entity merging reducer
  
- **How to use Normalizr to organize data in a Redux store**  
  https://dashbouquet.com/blog/frontend-development/using-normalizr-to-organize-data-in-stores-practical-guide  
  https://dashbouquet.com/blog/frontend-development/using-normalizr-to-organize-data-in-store-part-2  
  A 2-part post with examples of normalizing nested data using Normalizr, using Redux-Saga to control the fetching logic, and denormalizing the data for use in the UI.
  
- **Introducing @ngrx/entity**  
  https://medium.com/ngrx/introducing-ngrx-entity-598176456e15  
  Describes an NgRX-based library for generating reducer operations and selectors for normalized entities.
  
- **Shape your Redux store like your database**  
  https://hackernoon.com/shape-your-redux-store-like-your-database-98faa4754fd5  
  Discusses the merits of storing data in arrays vs lookup tables for access speed, and adding additional indices to allow easily lookup up items based on other values besides IDs.
  
- **Redux Patterns: Rethinking `byId` and `byHash` Structures**  
  https://hackernoon.com/redux-patterns-rethinking-byid-and-byhash-structures-854e8a0fa32d  
  Thoughts on dropping the common list of "all IDs" in a normalized state structure, and just iterating over all items using `Object.keys()` to grab the IDs.

- **Organising Redux State**  
  https://medium.com/@onoufriosm/organising-redux-state-4b4c2b99eece  
  Short examples of how Labstep defines state structure for their normalized entities
  
- **Normalizing Data into Relational Redux State with Normalizr**  
  https://medium.com/@onoufriosm/organising-redux-state-4b4c2b99eece  
  Tips on using Normalizr to normalize data, including defining schemas and overriding Normalizr's default processing and merging strategies.