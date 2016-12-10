### Project Structure


**Related topics**:
- [Boilerplates and Starter Kits](./boilerplate-and-starter-kits.md)
- [React Component Patterns](./react-component-patterns.md)
- [React State Management](./react-state-management.md)
- [React and Forms](./react-forms.md)
- [React and AJAX](./react-ajax.md)
- [React Architecture and Best Practices](./react-architecture.md)
- [Redux Architecture and Best Practices](./redux-architecture.md)


#### Project File Structure

- **Scaling React.js Applications**  
  https://vimeo.com/168648012  
  Max Stoiber's talk about managing large react.js applications. Covers "Feature" structure, redux-saga and CSS modules.
  
- **How to Scale React Applications**  
  https://www.smashingmagazine.com/2016/09/how-to-scale-react-applications/  
  https://twitter.com/dan_abramov/status/773912160896421889  
  Max Stoiber, creator of the popular "React-Boilerplate" starter kit, describes the approaches they use to lay out projects based on features.  The Twitter thread has discussion on some tradeoffs, including understand that Redux actions are "global", not scoped.

- **Organizing Large React Applications**  
  http://engineering.kapost.com/2016/01/organizing-large-react-applications/  
  Describes "File-Type First", "Feature First / Pods" approaches, as well as other related structure issues.
  
- **Four Strategies for Organizing Code**  
  https://medium.com/@msandin/strategies-for-organizing-code-2c9d690b6f33  
  Describes "by component", "by toolbox", "by layer", and "by kind" approaches.

- **Rules for Structuring (Redux) Applications**  
  http://jaysoo.ca/2016/02/28/organizing-redux-application/  
  Gives several useful rules for structuring code, with examples.
  
- **A Better File Structure for React/Redux Applications**  
  http://marmelab.com/blog/2015/12/17/react-directory-structure.html  
  Suggests a domain-based structure, with tests kept alongside the code they relate to.
  
- **Route-Based Folder Structure**  
  https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346  
  Ryan Florence, an author of React Router, gives his suggested file structure.
  
- **How to Better Organize Your React Applications?**  
  https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1  
  Another feature-style approach, describing things in terms of "components", "scenes", and "services".
  
- **Fractal Project Structure**  
  https://github.com/davezuko/react-redux-starter-kit/wiki/Fractal-Project-Structure  
  Docs from the React Redux Starter Kit project describing their "Fractal Project Structure" concept, and advice for file and app organization.
  
- **Redux Structure: a Way to Success**  
  https://datarockets.com/blog/redux-structure  
  Thoughts on a "modules and components"-based approach to file structure, 
  
- **My journey toward a maintainable project structure for React/Redux**  
  https://hackernoon.com/my-journey-toward-a-maintainable-project-structure-for-react-redux-b05dfd999b5  
  Describes an evolution of approaches for project structure
  
- **Building Modular Redux Applications**  
  https://vimeo.com/album/4199344/video/187454108  
  A talk discussing an approach to Redux structure by splitting logic into "data providers/sources" and presentation.
  
- **How to Structure real world Redux/React Applications**  
  https://medium.com/@yiquanzhou/how-to-structure-real-world-redux-react-application-d61e66a7dd36  
  Another look at structuring code, based on business logic, data domains, and reusability.
  
- **When a good plan comes together: React project structure for scaling**  
  http://thereactionary.net/when-a-good-plan-comes-together-react-project-structure-for-scaling/  
  More discussion of tradeoffs in various structure approaches.

  
#### Project Setup

- **Setting up a Front-End Project**  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-1-d7fbaaaa5e14  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-2-cbbae56ffd15  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-3-38f1681d310b  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-4-b6fe32e58e5  
  An in-depth tutorial series covering setup and configuration of many tools, including Git, Webpack, Babel, ESLint, and Typescript.