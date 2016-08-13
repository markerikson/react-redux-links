### Webpack Advanced Techniques

#### General Articles and Slideshows

#### Build Optimization

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

- **Webpack Plugins we been keeping on the DLL**  
  https://medium.com/@soederpop/webpack-plugins-been-we-been-keepin-on-the-dll-cdfdd6cb8cd7  
  An overview of Webpack's DllPlugin, and how it can be used for faster dev builds.
  
- **Webpack Async Bundle Loading**  
  http://jilles.me/webpack-async-bundle-loading/  
  A quick look at how to delay-load some portion of your app's code.
  
- **DllPlugin usage summary**  
  https://github.com/erikras/react-redux-universal-hot-example/issues/616#issuecomment-228956242  
  Notes from a user who wants to document his findings on usage of DllPlugin.  Pretty thorough.
  
  
- **Implement Webpack DLL Plugin for React-Boilerplate**  
  https://github.com/mxstbr/react-boilerplate/pull/495  
  A PR adding usage of DllPlugin to React-Boilerplate.  Thorough and well-commented - should be a very useful reference to anyone trying to set it up in their own project.
  
- **Optimizing Webpack**  
  http://engineering.invisionapp.com/post/optimizing-webpack/  
  Explains how to use DllPlugin to pre-bundle vendor libraries for faster build times.
  
- **Manually Tuning Webpack Builds**  
  https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44  
  Tips for cutting down bundle sizes by removing duplicate library instances and fine-tuning usage of various libraries.
  
- **Chat discussion - summary of process.env.NODE_ENV and its use with Webpack**  
  https://gist.github.com/markerikson/6776848172c33aaa4db882627c689e18  
  An overview of how the `process.env.NODE_ENV` variable is often used to define optimizations for Webpack production builds
  
#### Hot Module Replacement

- **Webpack and Hot Module Replacement**  
  https://medium.com/@rajaraodv/webpack-hot-module-replacement-hmr-e756a726a07  
  A great in-depth walkthrough of how HMR works
  
- **Webpack's HMR and React Hot-Loader - The Missing Manual**  
  https://medium.com/@rajaraodv/webpacks-hmr-react-hot-loader-the-missing-manual-232336dc0d96  
  Demonstrates three ways to enable HMR, and usage with three different React application scenarios

- **Hot Reloading in React**  
  https://medium.com/@dan_abramov/hot-reloading-in-react-1140438583bf  
  Dan Abramov walks through the history of his React Hot Loader and React Transform tools, describes their implementation, flaws, and weaknesses, and looks at a potential solution (later implemented in React Hot Loader 3.0).
  
- **HMR Tutorial Series**  
  http://andrewhfarmer.com/why-use-hmr/  
  http://andrewhfarmer.com/understanding-hmr/  
  http://andrewhfarmer.com/3-ways-webpack-hmr/  
  http://andrewhfarmer.com/webpack-hmr-tutorial/  
  A very readable and informative series of articles on using HMR.  
  
- **Live Editing Javascript with Webpack**  
  http://jlongster.com/Backend-Apps-with-Webpack--Part-III  
  Some interesting and advanced tricks for ways HMR could be used.

- **Using React with "plain" Webpack HMR**  
  https://github.com/reactjs/redux/pull/1455  
  Dan Abramov removes use of the React-Transform plugin from Redux's examples, and demonstrates how to use the "plain" Webpack HMR API to do reloading of updated components, reducers, and other code.
  
- **Basic HMR Usage Example**  
  https://gist.github.com/markerikson/dc6cee36b5b6f8d718f2e24a249e0491  
  An extracted example demonstrating using "plain" HMR to reload components, reducers, and even sagas.
  



#### Other Tips and Examples

- **Course: Using Webpack for Production Javascript Apps**  
  https://egghead.io/courses/using-webpack-for-production-javascript-applications  
  A video course by Kent C. Dodds, covering a number of very useful Webpack techniques for real-world apps.  Requires an Egghead subscription, but solid and useful info.

- **Javascript at Tumblr - Switching to Webpack**  
  https://javascript.tumblr.com/post/143583264647/here-at-tumblr-we-use-a-js-bundler-to-compile-our  
  Tumblr's dev team talks about switching from Browserify to Webpack, their migration steps, and some useful tips learned about pieces like CommonsChunkPlugin.

- **Webpack HTML plugin in a Nutshell**  
  http://www.jonathan-petitcolas.com/2016/01/23/webpack-html-plugin-in-a-nutshell.html  
  Looks at what the HTML Webpack plugin can do and how to use it.
  
- **Truly Multiple Entries with Webpack**  
  https://kuzzmi.com/blog/truly-multiple-entries-with-webpack  
  Instructions on how to configure multiple entry points properly
  
- **Long-term caching of static assets with Webpack**  
  https://medium.com/@okonetchnikov/long-term-caching-of-static-assets-with-webpack-1ecb139adb95  Gathers documentation on proper use of asset caching into one article to act as a complete guide.
  
- **Goodbye "../../../"**  
  http://davidboyne.co.uk/2016/04/29/react-webpack-gem.html  
  Tips and discussion on removing relative paths when importing
  
- **Using the HTML Webpack Plugin for generating HTML files**  
  http://javascriptplayground.com/blog/2016/07/webpack-html-plugin/  
  Basic instructions for setting up the HTML Webpack plugin
  
- **Setting up CSS Modules with React and Webpack**  
  http://javascriptplayground.com/blog/2016/07/css-modules-webpack-react/  
  Covers setting up and configuring Webpack to use CSS Modules for styling