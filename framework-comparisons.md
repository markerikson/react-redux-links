### Javascript Framework Comparisons

#### React, Angular, Ember, and Vue

- **Angular vs React vs Vue: A 2017 Comparison**  
  https://medium.com/unicorn-supplies/angular-vs-react-vs-vue-a-2017-comparison-c5c52d620176  
  The best framework comparison article I've seen. Covers multiple important considerations when choosing a framework, clearly describes the pros, cons, approaches, and tradeoffs of each library, and gives some suggestions for why you might want to choose one framework over the other.  Also links to several additional comparison articles at the end.

- **Comparing Frontend Approaches**  
  https://medium.com/@peterxjang/comparing-frontend-frameworks-part-1-introduction-6cf3d49e42cf  
  A series that builds the same notes app with jQuery, Vue, React, and Elm, and compares the pros and cons of the approaches.
  
- **Web Framework Comparisons**  
  https://www.sitepen.com/blog/2017/06/13/if-we-chose-our-javascript-framework-like-we-chose-our-music/  
  https://www.sitepen.com/blog/2017/11/10/web-frameworks-conclusions/  
  A 9-part series that compares Angular 2+, React+Redux, Vue, Ember, Dojo 2, and Aurelia.  Covers topics like UI development, UX design, foundational technologies, common usage, testing, and soundness.  The series is written by a company that works on Dojo, but the comparisons and descriptions are fair.  Links go to the first and last articles in the series.
  
- **How I stopped loving Angular**  
  https://codeburst.io/how-i-stopped-loving-angular-c2935f7378c4  
  An extensive article detailing the author's critiques of Angular 2+, and why they ultimately chose to switch to Vue instead.
  
- **React vs Angular: An In-depth Comparison**  
  https://www.sitepoint.com/react-vs-angular/  
  A well-written post that not only offers comparisons between React and Angular, but gives suggested approaches for comparing tools and ecosystems in general.
  
- **React vs Angular 2+: Developer Ergonomics**  
  https://medium.com/@stelly_ryan/react-vs-angular-2-developer-ergonomics-b6d5103e8699  
  Specific opinion-based comparisons on the developer experience for React and Angular in areas like components, testing, and framework-specific syntax, based on writing equivalent example apps using both frameworks.
  
- **How is React different from Vue?**  
  https://javascriptreport.com/how-is-react-different-from-vue/  
  A higher-level overview of some of the similarities and differences between React and Vue, including quotes from Dan Abramov and Evan You.
  
- **Unopinionated comparison of Glimmer and React**  
  https://wyeworks.com/blog/2017/12/20/unopinionated-comparison-of-glimmer-and-react  
  A well-written comparison of small React and Glimmer components that implement the same functionality.


#### React and Flux vs Backbone

- **Relieving Backbone Pain with Flux & React**  
  http://product.hubspot.com/blog/moving-backbone-to-flux-react  
  A fantastic video that walks through common problems with using Backbone, and how React can help solve those

- **Avoiding Event Chains in Single-Page Applications**  
  http://www.code-experience.com/avoiding-event-chains-in-single-page-applications/  
  Describes potential problems with Backbone-style events triggering further events, etc

- **From Backbone to React: Experience Scaling an App**  
  http://www.techsonian.net/2014/09/from-backbone-to-react-our-experience-scaling-a-web-application/  
  Thoughts on potential complexity issues in a Backbone app

- **From Backbone to React (comments)**  
  https://news.ycombinator.com/item?id=8329837  
  Discussion on the previous article


#### Migrating to React

- **How to migrate an application from AngularJS to React and Redux**  
  https://hackernoon.com/how-to-migrate-an-application-from-angularjs-to-react-and-redux-de0e2d1f70aa  
  Recaps several useful techniques to use when migrating an Angular 1.x app to React and Redux, including moving the build to use Webpack, rendering React components inside of Angular directives, sharing dependencies, and integrating Redux into the application.
  
- **Octopus Deploy 4.0 - Why we chose React over Angular when rewriting the Octopus 4.0 UI**  
  https://octopus.com/blog/octopus-v4-angular-to-react  
  Thoughts on how their original Angular 1 app had become unmaintainable, why they picked React, use of TypeScript, and how they approached architecting the React version.
  
- **AngularJS migration to React/Redux**  
  https://hashnode.com/post/angularjs-migration-to-reactredux-cj7t0m67x012ehowugcvjn1xj  
  Examples of how to approach migrating an Angular 1 app by first switching some components to use React, then adding state management to use Redux.
  
- **Migrating complex Javascript applications**  
  https://javascriptplayground.com/blog/2017/08/migrating-complex-javascript-angular-react/  
  Jack Franklin describes the lessons learned when his team migrated from Angular to React, including why they migrated, how they approached the architecture changes, how they prioritized what to change, and more.  Includes some examples of the Angular->React change, but also good advice in general.
  
- **A Chip off the Monolith**  
  https://medium.com/onfido-tech/a-chip-off-the-monolith-ec71e06a3015  
  The Onfido team describes how they extracted a portion of their monolithic Rails+Ember app into a separate React+Redux app.