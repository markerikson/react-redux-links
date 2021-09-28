### Redux UI Management

#### UI and Widget Implementations

- **"How can I display a modal dialog in Redux?"**  
  http://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions/35641680  
  Dan Abramov describes a great technique for descriptively managing React modal dialogs using Redux actions and state, by storing names of components and their props.

- **Creating Reusable Generic Modals in React and Redux**  
  http://blog.isquaredsoftware.com/2016/11/posts-on-packtpub-generic-redux-modals-and-building-better-bundles/  
  https://www.reddit.com/r/reactjs/comments/4wjmme/implement_a_confirm_modal_using_react_redux/d68ajcw?context=3  
  Describes an extension to Dan's technique that allows generic "picker" dialogs such as a ColorPicker to be reused by different parts of an application while keeping the Redux state serializable. (Blog post is based on my original comment on Reddit.)

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

- **A Redux-Saga Implementation of Modal Confirmation Dialogs in React**  
  https://decembersoft.com/posts/a-redux-saga-implementation-of-modal-confirmation-dialogs-in-react-redux/  
  Some examples of using sagas for controlling flow of async calls and dialog management

- **Practical Recursion: Implementing a File Item Tree View in React & Electron**  
  https://codeburst.io/practical-recursion-implementing-a-file-tree-view-in-react-electron-af62e7b46d26?gi=da3b8e9bf9ee  
  Demonstrates implementing a tree view component that shows folder structure read from the filesystem, and managing the visibility of tree nodes in Redux

- **How To Manage UI State with Redux**  
  https://codeburst.io/how-to-manage-ui-state-with-redux-24deb6cf0d57  
  An informative discussion of application state vs internal component state, how "UI state" fits into app state, and how to write a UI reducer that tracks UI state.

- **Introduce Redux local state to your React App**  
  https://medium.com/@tangbenze/introduce-redux-local-state-to-your-react-app-9f96f18d4f35  
  Demonstrates setup and use of a addon library to manage scoped actions, reducers, and connections for isolated component state.

- **Using react-redux-set-local**  
  https://www.andrewfong.com/blog/2017/07/03/react-redux-set-local/  
  Discussion of the rationale and implementation of a library for connecting isolated portions of a Redux store state to a component while maintaining separation between presentation and state management.

- **Making Toast from Scratch in React-Redux**  
  https://spin.atomicobject.com/2017/07/12/react-redux-toast/  
  A short tutorial that shows how to build your own "toast" notifications in React+Redux, with a link to the resulting implementation.

- **Toast notification system in a React/Redux application**  
  https://www.deployhq.com/blog/toast-notification-system-in-a-react-redux-application  
  The Natterly team walks through how they built a Redux-connected toast notification implementation.

- **A Functional Canvas Approach with Redux**  
  https://medium.com/@peterxjang/a-functional-canvas-approach-with-redux-ce59a369241b  
  https://medium.com/@peterxjang/a-functional-canvas-approach-with-redux-bab357d6c33c  
  Some simple examples of how to use Redux and vanilla JS canvas code to draw canvas-based UIs with minimal dependencies.

- **React/Redux with Mapbox**  
  https://medium.com/@mcculloughrt/react-redux-with-mapbox-78fa3767211e  
  Useful techniques for driving the appearance and behavior of a Mapbox-based geospatial app from React and Redux.

- **React/Redux: Modals and Dialogs**  
  https://medium.com/front-end-hacking/react-redux-no-need-to-component-state-for-modals-73871157b52e  
  Discussion of the pros and cons of powering modals via Redux, with examples of how to show them using React 16's Portals.

- **Handling Keyboard Commands with Redux**  
  https://medium.com/@sandropadin/handling-keyboard-commands-with-redux-67584decb3ff  
  Discussion of an approach for managing keybard interaction in a React+Redux app, with an interactive embedded example app on CodeSandbox

- **Modular, fast, small: how we built a server-rendered IDE**  
  https://repl.it/site/blog/ide  
  The repl.it team describes how they built a Redux-based plugin architecture that handles window management and layout, with plugins able to interact via Redux actions.

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

- **Here's what you can do to make migrating your forms to Redux easier in the future**  
  https://goshakkk.name/prep-forms-for-redux/  
  Simple but useful advice on extracting form logic as reducer functions inside of classes

- **Redux Form Validation Tutorial Example From Scratch**  
  https://appdividend.com/2017/11/05/redux-form-validation-tutorial-example/  
  A tutorial that demonstrates setting up a Redux app that uses Redux-Form, and adding validation logic to that form.
