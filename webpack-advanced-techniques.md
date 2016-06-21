### Webpack Advanced Techniques

#### Articles and Slideshows

- **Webpack: Build Performance**  
  https://github.com/webpack/docs/wiki/build-performance  
  Webpack docs on ways to speed up builds.

- **How to make your webpack builds 10x faster**  
  http://www.slideshare.net/trueter/how-to-make-your-webpack-builds-10x-faster  
  Slideshow that lists a number of approaches for making Webpack builds faster, such as narrowing scope, using the DllPlugin, using HappyPack for parallel builds, and more.
  
- **Advanced Frontend Optimization with Webpack**  
  http://sokra.github.io/slides/frontend-optimize  
  Slides by Sokra describing ways to improve Webpack builds.  
  
- **React-Router and Webpack in Production**  
  https://reactjsnews.com/webpack-in-production  
  Tips on dynamically loading route views and optimizing chunk sizes
  
- **Fixing annoying imports in React Projects**  
  https://medium.com/datawallet-tech/fixing-annoying-imports-in-react-projects-895a6ad24c24  
  A quick example of using Webpack's module aliasing to simplify import paths, with further discussion in the comments.
  
- **Webpack and Hot Module Replacement**  
  https://medium.com/@rajaraodv/webpack-hot-module-replacement-hmr-e756a726a07  
  A great in-depth walkthrough of how HMR works
  
- **Webpack's HMR and React Hot-Loader - The Missing Manual**  
  https://medium.com/@rajaraodv/webpacks-hmr-react-hot-loader-the-missing-manual-232336dc0d96  
  Demonstrates three ways to enable HMR, and usage with three different React application scenarios

- **Hot Reloading in React**  
  https://medium.com/@dan_abramov/hot-reloading-in-react-1140438583bf  
  Dan Abramov walks through the history of his React Hot Loader and React Transform tools, describes their implementation, flaws, and weaknesses, and looks at a potential solution (later implemented in React Hot Loader 3.0).
  
- **Webpack Plugins we been keeping on the DLL**  
  https://medium.com/@soederpop/webpack-plugins-been-we-been-keepin-on-the-dll-cdfdd6cb8cd7
  An overview of Webpack's DllPlugin, and how it can be used for faster dev builds.


#### Examples

- **Using React with "plain" Webpack HMR**  
  https://github.com/reactjs/redux/pull/1455  
  Dan Abramov removes use of the React-Transform plugin from Redux's examples, and demonstrates how to use the "plain" Webpack HMR API to do reloading of updated components, reducers, and other code.
  
- **Basic HMR Usage Example**  
  https://gist.github.com/markerikson/dc6cee36b5b6f8d718f2e24a249e0491  
  An extracted example demonstrating using "plain" HMR to reload components, reducers, and even sagas.