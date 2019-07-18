### React Deployment

#### Applications

- **Understanding React deployment**  
  https://medium.com/@baphemot/understanding-react-deployment-5a717d4378fd  
  An excellent overview of the basic steps needed to deploy a React app, including solutions for common problems such as routing producing 404s and changes not showing up properly.
  
- **Surge vs Github Pages: How to deploy a create-react-app project**  
  https://medium.freecodecamp.com/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089  
  Shows how to deploy a CRA-based app onto the Surge.sh and Github Pages static hosting sites
  
- **Fullstack React: Deploying a React App**  
  https://www.fullstackreact.com/articles/deploying-a-react-app-to-s3/  
  https://www.fullstackreact.com/articles/deploying-a-react-app-with-a-server/  
  A pair of articles that show how to deploy a React app's static assets onto Amazon S3, and a backend API server onto Heroku
  
- **Deploying React + Redux to Heroku**  
  http://www.thegreatcodeadventure.com/deploying-react-redux-to-heroku/  
  Covers configuring Webpack for production, setting up build tasks and environment variables, configuring an Express server, and pushing the app to Heroku
  
- **Create-React-App with an Express Backend**  
  https://daveceddia.com/create-react-app-express-backend/  
  A quick overview showing how to configure Create-React-App to proxy API requests to a separate server (example uses Express, but applies to any other app server).
  
- **Create-React-App with Express in Production**  
  https://daveceddia.com/create-react-app-express-production/  
  Shows how to set up an React app with an Express server that serves as both API server and static file server, and deploy it to Heroku.
  
- **From React to an Electron app ready for production**  
  https://medium.com/@kitze/%EF%B8%8F-from-react-to-an-electron-app-ready-for-production-a0468ecb1da3  
  Walks through the basics of configuring a Create-React-App-based Electron app and building it for production.
  
- **React with Any Backend**  
  https://www.javascriptstuff.com/react-with-any-backend  
  Some short discussion and suggestions for project structure and deployment steps when building a React app that talks to a non-Javascript backend server.
  
- **Building a Full-Stack App with Serverless and React**  
  http://serverless-stack.com/  
  A large, well-written, in-depth tutorial that covers all aspects of building a React app with an AWS "serverless" backend: creating an AWS account, setting up the serverless backend and API, building a React app that talks to the API, and deploying the React app on AWS.
  
- **Using React in Multiple Environments**  
  https://daveceddia.com/multiple-environments-with-react/  
  Discusses strategies for handling deployments to dev/staging/prod-type environments, including configuration of API endpoints and feature flags.
  
- **Deploy a React app with SASS using Nginx**  
  http://zabana.me/notes/build-deploy-react-app-with-nginx.html  
  Covers several important notes for adding SASS to an ejected CRA app, creating a deploy step using rsync, and setting up the Nginx web server to serve the app.
  
- **How to deploy a React application: an in depth overview of various options to deploy**  
  https://codebrahma.com/deploy-react-application-depth-overview-various-options-deploy/  
  A detailed look at what deployment for production means, what files are involved, how to properly build an app for production, and places to host a react app.
  
- **So you want to host your Single Page React App on Github Pages?**  
  https://itnext.io/so-you-want-to-host-your-single-age-react-app-on-github-pages-a826ab01e48  
  Solutions for common problems encountered when trying to deploy a React app on Github Pages, especially around routing.
  

#### Libraries

- **Creating react-editables: How to build a set of reusable React components**  
  https://medium.com/@niwaa/creating-react-editables-how-to-build-a-set-of-reusable-react-components-with-an-hoc-and-write-7a685947a992  
  Looks at the steps needed to create a set of reusable React components and publish them to NPM.  Includes extended thoughts on component design for reusability.

- **Adventures in creating a React component library with Create React App and TypeScript**  
  https://medium.com/@stokedbits/adventures-in-creating-a-react-component-library-with-create-react-app-and-typescript-26d1116a7d87  
  Walks through the process of using the TS+CRA starter kit as a baseline for building and publishing a component library.
  
- **A guide to building a React component for NPM**  
  https://medium.com/@markus.s.englund/a-guide-to-building-a-react-component-for-npm-68f03b314753  
  A high-level overview of things to consider when publishing a React-based component library, including accessibility, documentation, naming, and marketing