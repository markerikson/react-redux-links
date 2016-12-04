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
  
- **Tips for faster Webpack builds**  
  https://www.reddit.com/r/javascript/comments/4xuknm/webpack_dashboard/d6jdl8z  
  A Reddit comment with several useful tips to follow when trying to speed up builds
  
- **Formidable Playbook**  
  https://formidable.com/open-source/playbook/  
  Formidable Labs describes their preferred approaches for configuring Webpack, including optimization approaches.
  
- **Code Chunking with Webpack**  
  https://medium.com/react-weekly/code-chunking-with-webpack-a-pragmatic-approach-e17e8bcc6453  
  Covers how to configure chunked bundles and dynamic bundle loading with Webpack and React-Router.
  
- **Lazily Load Code Declaratively in React and Webpack**  
  https://gist.github.com/iammerrick/f3f9edfbf5dc279af775f73020193dcc  
  Demonstrates one way to request and render components on demand, using Webpack's bundle-loader
  
- **Webpack Bloat**  
  http://www.jamesonnetworks.com/entry/webpack-bloat  
  Discussion of how to improve production configurations for smaller bundle sizes
  
- **Dynamic Vendor Bundling in Webpack**  
  https://medium.com/jeremy-gayed/dynamic-vendor-bundling-in-webpack-528993e48aab  
  An approach to dynamically adding anything from `node_modules` to a "vendor" bundle

- **"Vector.im bundle is too big - analysis"**  
  https://github.com/vector-im/vector-web/issues/2498  
  Web perf expert Nolan Lawson analyzes why the JS bundle for the Vector.im web app is too big, and ways it could potentially be improved using code splitting and app structure changes.  A good example of ways to improve bundle sizes.
  
- **Webpack Performance: The Comprehensive Guide**  
  https://github.com/lcxfs1991/blog/issues/15  
  An in-depth look at the parts that go into a Webpack build, and how each piece can be optimized for a faster build.
  
- **Webpack Config: Commons Chunk Plugin part 1**  
  https://www.youtube.com/watch?v=-xzWMKuiS2o  
  An intro to what the Webpack Commons Chunk Plugin does and how it works
  
- **A beginner's step-by-step guide to Code Splitting with Webpack 2 and React Router**  
  http://brotzky.co/blog/a-beginners-step-by-step-guide-to-code-splitting-with-webpack-2-and-react-router/  
  An excellent guide to concepts and configuration needed for code splitting.
  
- **Speeding up Webpack performance with parallel builds**  
  http://tech.trivago.com/2015/12/15/parallel-webpack/  
  Describes a tool called `parallel-webpack`, which can build multiple entry points in multiple formats in parallel.
  
- **Building Vendor and Feature Bundles with Webpack**  
  http://odetocode.com/blogs/scott/archive/2016/12/01/building-vendor-and-feature-bundles-with-webpack.aspx  
  Demonstrates using DllPlugin to build a vendor bundle, and generating multiple bundles for different features by dynamically building up multiple entry points.
  
  
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
  
- **React - Hot Module Reload**  
  https://medium.com/@baphemot/react-hot-module-reload-f6b3d34b9b86  
  An explanation of how to set up HMR using React-Hot-Loader 3.0
  
- **Adding HMR to Create-React-App**  
  http://chrisshepherd.me/posts/adding-hot-module-reloading-to-create-react-app  
  A quick example of the basic pattern for using plain HMR with Webpack
  
- **Webpack Hot Reloading and React**  
  https://ctheu.com/2015/12/29/webpack-hot-reloading-and-react-how/  
  An explanation of how Hot Reloading works, and how the various pieces fit together.
  
- **ReactCasts #7: Hot Module Replacement in Create-React-App**  
  https://www.youtube.com/watch?v=hcl3lNjgj-E  
  A screencast talking about what HMR is, and two ways to add it to projects created with Create-React-App
  
- **"Difference between Webpack HMR and React-Hot-Loader?"**  
  https://github.com/facebookincubator/create-react-app/issues/1063#issuecomment-261788083  
  Dan Abramov clarifies that HMR is the API and capability that Webpack gives you, while React-Hot-Loader is a specialized tool that uses the HMR API to automatically add HMR handling to React code.


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
  https://medium.com/@okonetchnikov/long-term-caching-of-static-assets-with-webpack-1ecb139adb95  
  Gathers documentation on proper use of asset caching into one article to act as a complete guide.
  
- **Goodbye "../../../"**  
  http://davidboyne.co.uk/2016/04/29/react-webpack-gem.html  
  Tips and discussion on removing relative paths when importing
  
- **Using the HTML Webpack Plugin for generating HTML files**  
  http://javascriptplayground.com/blog/2016/07/webpack-html-plugin/  
  Basic instructions for setting up the HTML Webpack plugin
  
- **Setting up CSS Modules with React and Webpack**  
  http://javascriptplayground.com/blog/2016/07/css-modules-webpack-react/  
  Covers setting up and configuring Webpack to use CSS Modules for styling
  
- **Webpack Map Entity Loader**  
  http://drhayes.io/secret-game/map-entity-loader.html  
  A small example of writing a custom Webpack loader for game data
  
  
#### Webpack Tools

- **Webpack Dashboard**  
  https://github.com/FormidableLabs/webpack-dashboard  
  A CLI dashboard for your webpack dev server

- **Webpack Visualizer**  
  https://chrisbateman.github.io/webpack-visualizer/  
  A tool and plugin to visualize the (pre-minified) sizes of files in a Webpack bundle
  
- **Webpack Bundle Analyzer**  
  https://github.com/th0r/webpack-bundle-analyzer  
  Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap, and can parse minified bundles to show true minified (and gzipped) sizes
