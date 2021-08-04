### Boilerplates and Starter Kits


#### Suggested Starter Kits for Learners

**NOTE**: It's easy for someone new to the React/Redux ecosystem to get confused by some of these boilerplates and starter kits.  Many of them include dozens of specifically-configured libraries, and it can be hard for a learner to understand how all the pieces fit together.  If you're trying to learn React or Redux for the first time, it's suggested that you start with reading tutorials and articles first, until you have a reasonable understanding of how things work.  However, if you _do_ want to use a starter kit as a learning tool, I specifically suggest the ones in this section.  They are simpler, easier to understand, and well documented.  In particular, Create-React-App is highly recommended.  Also see [Should I use a boilerplate with React?](http://blog.jakoblind.no/should-i-use-a-boilerplate-for-react/) for similar thoughts.

- **Create-React-App**  
  https://github.com/facebookincubator/create-react-app  
  An "official", no-visible-configuration tool to instantly create a React project with bundling, minification, and basic CSS and image handling all set up and ready to go.  If you outgrow the basic features, the underlying tools can be exposed and modified using a one-time "eject" command.  It's a great tool to use to when learning React, or just to set up a project quickly. 

- **Simple Redux Boilerplate**  
  https://github.com/tsaiDavid/simple-redux-boilerplate  
  Excellent example.  Includes enough to be useful, but not too many dependencies so it's confusing.
  
- **Web-App**  
  https://github.com/cesarandreu/web-app  
  Another very good learning resource.  Heavily commented Webpack config, good default settings.
  
- **React Laboratory**  
  https://github.com/tstringer/react-laboratory  
  An absolute bare-minimum project.  One tiny Webpack config, one JS file, one component.  Pretty much the smallest possible setup to use React and JSX with Webpack.
  
- **TypeScript React Starter**  
  https://github.com/Microsoft/TypeScript-React-Starter  
  A quick start guide to setting up a TypeScript project using a TS-specific variation on Create-React-app's `react-scripts` package.  Includes instructions for adding TSLint, Jest, Enzyme, and Redux.
  
  
  
#### Full-Featured Starter Kits

- **React-Redux Universal Hot Example**  
  https://github.com/erikras/react-redux-universal-hot-example  
  Has the kitchen sink, and more.  Popular, but maybe too many things stuffed into one repo.
  
- **React-Redux Starter Kit**  
  https://github.com/davezuko/react-redux-starter-kit  
  Generally recommended.  Well laid out, good documentation.  Worth looking at.  Has become significantly more complex over time as well.
  
- **react-boilerplate**  
  https://github.com/mxstbr/react-boilerplate  
  A highly scalable, offline-first foundation for your next project with the best DX and a focus on performance and best practices.  Excellent documentation.
  
- **React Starter Kit**  
  https://github.com/kriasoft/react-starter-kit  
  A full-featured universal/isomorphic starter kit, with good documentation
  
- **React Slingshot**  
  https://github.com/coryhouse/react-slingshot  
  A flexible starter kit designed to illustrate best practices.


#### Specific Concept Demonstrations
  
- **Ultimate Hot-Reloading Example**  
  https://github.com/glenjamin/ultimate-hot-reloading-example  
  Demonstrates hot-reloading of pretty much everything, both client-side and server-side
  
- **Universal-JS**  
  https://github.com/colinmeinke/universal-js  
  A well-written universal starter with docs explaining choices, and plenty of example tests.

- **React + Electron Boilerplate**  
  https://github.com/chentsulin/electron-react-boilerplate  
  Electron application boilerplate based on React, Redux, React Router, Webpack, React Transform HMR for rapid application development

- **React-Redux-Cesium-Testing Demo**  
  https://github.com/markerikson/react-redux-cesium-testing-demo  
  Demonstrates a number of useful bits of project configuration, including offline tests with Mocha+JSDOM, live-reloading tests in the browser using mocha-loader, async loading of React components, use of the Cesium 3D globe library with React and Webpack, and using the Shrinkpack tool to manage dependencies inside the repo.  Not intended for production use, but could serve as a useful example.

- **React Static Plate**  
  https://github.com/webyak/react-static-plate  
  Build static sites with React to host on Amazon S3, Github Pages, Surge, etc.  An interesting alternative to other static page generation tools.

- **React NPM Component Starter**  
  https://github.com/yogaboll/react-npm-component-starter  
  A minimal boilerplate project for building a React component library for NPM.

#### Other

- **React Starter Project Search Tool**  
  https://www.javascriptstuff.com/react-starter-projects/  
  Search for starter kits with/without specific libraries and sort by GitHub stars, number of dependencies, or recently updated.
  
- **Awesome React Boilerplates**  
  http://habd.as/awesome-react-boilerplates/  
  Another good curated list of boilerplates for both React and React Native
  
- **React Community: Starter Kit**  
  https://reactjs.org/community/starter-kits.html  
  A list of starter kits that are officially recommended by the React team, as well as other kits from the community.
  
  
  
#### React Project Setup

- **Simple React Development in 2018**  
  https://hackernoon.com/simple-react-development-in-2017-113bd563691f  
  An excellent set of instructions for setting up a React project with minimal fuss and effort needed.  Includes links to some useful resources, and info on deploying the app to production.
  
- **Taming the React Setup**  
  http://developer.telerik.com/featured/taming-react-setup/  
  Describes seven different setups for writing React code, from simple (plain react.js loaded into the browser), to complex (use of Babel with Webpack or JSPM).
  
- **Kick-Start React Projects with Create-React-App**  
  https://www.sitepoint.com/create-react-app/  
  Some quick tips on how to use Create-React-App to create a new React project and tweak the setup.
  
- **Getting Started with React the Easy Way**  
  http://codeutopia.net/blog/2016/01/10/getting-started-with-react-the-easy-way/  
  Shows the simplest way to load React into a web page and start using it
  
- **The Minimal React Webpack Babel Setup**  
  https://www.robinwieruch.de/minimal-react-webpack-babel-setup/  
  A clear walkthrough for the key steps needed to set up a useful Webpack+Babel config from scratch for a productive React dev environment.  Very helpful if you choose not to use Create-React-App.
  
- **Hipster Boilerplate**  
  https://github.com/Jordaanm/hipster-boilerplate  
  A learning-oriented repo that builds up a small project config step-by-step.  Each commit adds one new feature or capability (Babel+ES6, Webpack bundling, a small Redux app, LESS styling, routing, and hot-reloading).  
  
- **JavaScript Stack from Scratch**  
  https://github.com/verekia/js-stack-from-scratch  
  This is a minimalistic and straight to the point guide to assembling a JavaScript stack. It teaches you how to set up ES6, Babel, Gulp, ESLint, React, Redux, Webpack, Immutable, Mocha, Chai, Sinon, and Flow. It requires some general programming knowledge, and JavaScript basics. It focuses on wiring all these tools together and giving you the simplest possible example for each tool. You can see this tutorial as a way to write your own boilerplate from scratch.

- **React Ecosystem Setup - Step-By-Step**  
  https://codeburst.io/react-ecosystem-setup-step-by-step-walkthrough-721ff45a7fc1  
  An in-depth walkthrough that shows to to set up Webpack and Babel, and explains why each bit of configuration is needed.
  
- **Always up-to-date Guide for Modern JavaScript Development**  
  https://mvilrokx.gitbooks.io/always-up-to-date-guide-for-modern-javascript-dev/content/  
  An opinionated guide for setting up a modern JS development environment.
  
- **Setup a React Environment using Webpack and Babel**  
  https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel  
  A tutorial that teaches how to set up a basic Webpack 2 + Babel config from scratch.
  
- **Setting up a Front-End Project**  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-1-d7fbaaaa5e14  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-2-cbbae56ffd15  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-3-38f1681d310b  
  https://medium.com/@Torwori/setting-up-a-front-end-project-part-4-b6fe32e58e5  
  An in-depth tutorial series covering setup and configuration of many tools, including Git, Webpack, Babel, ESLint, and Typescript.
  
- **Setting up Webpack, Babel, and React from scratch in 2017**  
  https://stanko.github.io/webpack-babel-react-revisited/  
  A step-by-step tutorial that demonstrates each piece of the process needed to set up a build system from scratch.
  
- **How to set up React, Webpack 3, and Babel, in 2017**  
  https://www.valentinog.com/blog/react-webpack-babel/  
  A clear explanation of how to create a basic Webpack+Babel setup for a React app, with descriptions of why each step is necessary.
