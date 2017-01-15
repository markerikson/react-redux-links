### React and Forms

(Note: the "linked state mixin" and "two-way binding" approaches described in some of these articles are still valid, but _mostly_ discouraged at this point.  The more idiomatic approach is "one-way data flow" with "controlled inputs".)


#### "Controlled" and "Uncontrolled Inputs

- **React Docs: Forms**  
  https://facebook.github.io/react/docs/forms.html  
  The React documentation page on forms.  Describes "controlled" and "uncontrolled" form inputs.
  
- **React "controlled" vs "uncontrolled" inputs**  
  https://gist.github.com/markerikson/d71cfc81687f11609d2559e8daee10cc  
  An explanation of the terms "controlled inputs" and "uncontrolled inputs"

- **React Form Components**  
  http://donavon.js.org/react-forms/  
  A look at controlled vs uncontrolled inputs, with a useful note about issues with controlled inputs and certain browsers.
  
- **Uncontrolled components are an anti-pattern**  
  https://medium.com/@jedwards8/uncontrolled-components-are-an-anti-pattern-abbdd86fd39e  
  Argues that uncontrolled components are a bad idea and should be avoided.
  
- **ReactJS and controlled forms**  
  http://leftdevel.com/blog/reactjs-controlled-forms/  
  A look at the difference between controlled and uncontrolled inputs, and some problems that can come from using uncontrolled inputs.
  
- **Managing React Controlled Component State**  
  http://spraso.com/managing-react-controlled-component-state/  
  Some short examples of how to properly manage state for controlled inputs

- **Managing state and controlled form fields with React**  
  https://blog.iansinnott.com/managing-state-and-controlled-form-fields-with-react/  
  Describes the concepts of "controlled" and "uncontrolled" inputs.  
  
- **React Hates me: "Overcontrolled" components**  
  http://www.matthiaslienau.de/blog/2015/4/8/react-hates-me-overcontrolled-components  
  Describes some specific issues with controlled inputs and the preventDefault method
  
- **React.js Forms: Controlled Components**  
  http://lorenstewart.me/2016/10/31/react-js-forms-controlled-components/  
  An excellent article that describes the concept of controlled components, and demonstrates examples of how to interact with different types of form inputs
  
- **Controlled and uncontrolled form inputs in React don't have to be complicated**  
  http://goshakkk.name/controlled-vs-uncontrolled-inputs-react/  
  A great summary of what controlled and uncontrolled inputs are, what each approach looks like, and how to handle values from different types of inputs.
  
- **Controllable React Components**  
  https://speakerdeck.com/lettertwo/controllable-react-components  
  A slideshow discussing how React components can themselves either be controlled or uncontrolled, and introducing a library to help make components controllable.
  
- **Collecting data from a wizard form**  
  https://goshakkk.name/wizard-form-collect-info/  
  Examples of how to handle data management for a multi-step form


#### Form Tutorials and Usage

- **Learn Raw React: Ridiculously Simple Forms**  
  http://jamesknelson.com/learn-raw-react-ridiculously-simple-forms/  
  Covers the basics of implementing form rendering, updates, and validation, in plain JS
  
- **Forms in React and Redux**  
  http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/  
  Demonstrates building a simple set of wrapper components to manage forms using React and Redux
  
- **Not-so-simple Forms with React**  
  http://www.randseay.com/articles/forms-with-react  
  Explains how to set up more advanced form scenarios such as optional or repeatable sections.
  
- **Using React's state to manage data entry**  
  https://medium.com/@adamrackis/using-reacts-state-to-manage-data-entry-ed92e4fd1a42  
  Describes how to manage data for forms using React component state and some wrapper components.
  
- **Handling React Forms with Mobx Observables**  
  https://blog.risingstack.com/handling-react-forms-with-mobx-observables/  
  Some examples of working with forms in React, using MobX for the data management.
  
- **Forms in React and Redux**  
  http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/  
  A good example of how to set up form handling in conjunction with a Redux store.
  
- **Radio Buttons and Checkboxes in React**  
  http://react.tips/radio-buttons-in-reactjs/  
  http://react.tips/checkboxes-in-react/  
  Tutorials on managing various inputs in forms with React
  
- **Building a Multi-Step Registration Form with React**  
  https://www.viget.com/articles/building-a-multi-step-registration-form-with-react  
  A form example that shows how to track the current form step, render the right form component, and store all the necessary form data
  
  
#### Form Validation

- **Form Validation Tutorial with React.js**  
  https://html5hive.org/reactjs-form-validation-tutorial/  
  A good example of setting up form validation in React
  
- **Elegant Form Validation in React**  
  https://spin.atomicobject.com/2016/10/05/form-validation-react/  
  Examples of adding validation to a form
  
- **Two-Way Data Binding and Form Validation in React**  
  https://medium.com/@thejenniekim/two-way-data-binding-and-form-validation-in-react-9d0b15123176  
  Another demonstration of building a form with some logic and validation.
  
- **Form Validation as a Higher Order Component**  
  https://medium.com/javascript-inside/form-validation-as-a-higher-order-component-pt-1-83ac8fd6c1f0  
  https://medium.com/javascript-inside/form-validation-as-a-higher-order-component-pt-2-1edb7881870d  
  A 2-part series, demonstrating how to use Ramda and FP approaches to create validation logic
  
- **Form recipe: Conditionally disabling the Submit button**  
  http://goshakkk.name/form-recipe-disable-submit-button-react/  
  Some simple examples of validating data from controlled inputs
  
- **Instant form field validation with React's controlled inputs**  
  https://goshakkk.name/instant-form-fields-validation-react/  
  Examples of how to perform validation during rendering, and immediately show which inputs are invalid
  

#### Other

- **Creating new fields and widgets for Mozilla's react-jsonschema-form**  
  https://jeffersonheard.github.io/2016/11/creating-new-fields-and-widgets-for-mozillas-react-jsonschema-form/  
  Examples of working with the react-jsonschema-form library, including defining form schemas, gotchas, and customization with specific widgets and types
  
- **List or Form, why not both? Making a list with a built in editor in React**  
  http://thereactionary.net/list-or-form-why-not-both-making-a-list-with-a-built-in-editor-in-react/  
  Builds an example of a list with the ability to do inline editing of items.