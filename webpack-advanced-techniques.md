### Webpack Advanced Techniques

#### Build Optimization

- **Webpack: Build Performance**  
  https://github.com/webpack/docs/wiki/build-performance  
  Webpack docs on ways to speed up builds.

- **How to make your webpack builds 10x faster**  
  http://www.slideshare.net/trueter/how-to-make-your-webpack-builds-10x-faster  
  Slideshow that lists a number of approaches for making Webpack builds faster, such as narrowing scope, using the DllPlugin, using HappyPack for parallel builds, and more.
  
- **Advanced Frontend Optimization with Webpack**  
  http://sokra.github.io/slides/frontend-optimize  
  Slides by Webpack's original author, describing ways to improve Webpack builds.  
  
- **Fixing annoying imports in React Projects**  
  https://medium.com/datawallet-tech/fixing-annoying-imports-in-react-projects-895a6ad24c24  
  A quick example of using Webpack's module aliasing to simplify import paths, with further discussion in the comments.

- **Webpack Plugins we been keeping on the DLL**  
  https://medium.com/@soederpop/webpack-plugins-been-we-been-keepin-on-the-dll-cdfdd6cb8cd7  
  An overview of Webpack's DllPlugin, and how it can be used for faster dev builds.
  
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
  
- **Tips for faster Webpack builds**  
  https://www.reddit.com/r/javascript/comments/4xuknm/webpack_dashboard/d6jdl8z  
  A Reddit comment with several useful tips to follow when trying to speed up builds
  
- **Formidable Playbook**  
  https://formidable.com/open-source/playbook/  
  Formidable Labs describes their preferred approaches for configuring Webpack, including optimization approaches.

- **Webpack Performance: The Comprehensive Guide**  
  https://github.com/lcxfs1991/blog/issues/15  
  An in-depth look at the parts that go into a Webpack build, and how each piece can be optimized for a faster build.
  
- **Speeding up Webpack performance with parallel builds**  
  http://tech.trivago.com/2015/12/15/parallel-webpack/  
  Describes a tool called `parallel-webpack`, which can build multiple entry points in multiple formats in parallel.
  
- **A React + Webpack Optimization Case**  
  https://medium.com/@kudochien/a-react-webpack-optimization-case-27da392fb3ec  
  Several useful examples of how to profile and optimize a Webpack-based project, including checking bundle contents, specific imports from libraries, ignoring Moment locales, and more.
  
- **Optimizing Wepback build times and improving caching with DLL bundles**  
  https://robertknight.github.io/posts/webpack-dll-plugins/  
  Explains the benefits of using DllPlugin for generating library bundles, shows how to configure it, and compares with other chunking methods.

- **Tree-shaking ES6 Modules in Webpack 2**  
  https://medium.freecodecamp.com/tree-shaking-es6-modules-in-webpack-2-1add6672f31b  
  A look at the concept of tree-shaking to reduce output size, how it relates to module formats, and how to configure Webpack to properly allow for tree-shaking
  
- **Webpack tree-shaking**  
  https://medium.com/@johnstew/webpack-tree-shaking-20914b7a9ca5  
  An explanation of what tree-shaking is, how to configure Webpack to apply it, and how it works.
  
- **How to optimize Moment.js with Webpack**  
  https://github.com/jmblog/how-to-optimize-momentjs-with-webpack  
  Tips on using IgnorePlugin and ContextReplacementPlugin to strip out uneeded locales from Moment
  
- **Declaratively Rendering Earth in 3D, Part 1: Building a Cesium + React App with Webpack**  
  http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/  
  Shows how to configure Webpack to load the Cesium 3D globe library, and how to set up a Webpack config that uses DllPlugin to build a separate bundle for Cesium.
  
- **Tree shake Lodash with Webpack, Jest, and Typescript**  
  https://medium.com/@martin_hotell/tree-shake-lodash-with-webpack-jest-and-typescript-2734fa13b5cd  
  Walks through ways to configure Webpack and Babel to properly tree shake Lodash so that it only includes used functions.
  
- **Webpack for real tasks: decreasing front-end size and improving caching**  
  https://iamakulov.com/notes/webpack-front-end-size-caching/  
  Covers a variety of ways to improve bundle sizes, including minification with Uglify, tree shaking imports, referencing external libraries, and more.
  
- **Webpack 3 + React - Production Build Tips**  
  https://medium.com/netscape/webpack-3-react-production-build-tips-d20507dba99a  
  General advice for improving Webpack builds, including code splitting, minification, and several more.  Includes a complete Webpack config file at the end with the proper settings.
  
- **d-l-l: Easy, automatic, optimized DLL config handler for Webpack**  
  https://survivejs.com/blog/dll-interview/  
  An interview with the author of a tool for automatically generating DLL bundles, discussing how to use it and how it works.
  
- **High-performance webpack config for front-end delivery**  
  https://www.codementor.io/drewpowers/high-performance-webpack-config-for-front-end-delivery-90sqic1qa  
  Covers 7 optimizations you can add to a Webpack setup to build bundles faster and make them smaller.
  
- **Unpacking the Mysteries of Webpack**  
  https://www.viget.com/articles/unpacking-the-mysteries-of-webpack-a-novices-journey  
  Recaps some high-level Webpack terms and concepts, and walks through several changes to speed up compilation and improve bundle size.
  
  
  
#### Code Splitting and Chunking

- **React-Router and Webpack in Production**  
  https://reactjsnews.com/webpack-in-production  
  Tips on dynamically loading route views and optimizing chunk sizes

- **Webpack Async Bundle Loading**  
  http://jilles.me/webpack-async-bundle-loading/  
  A quick look at how to delay-load some portion of your app's code.
  
- **Code Chunking with Webpack**  
  https://medium.com/react-weekly/code-chunking-with-webpack-a-pragmatic-approach-e17e8bcc6453  
  Covers how to configure chunked bundles and dynamic bundle loading with Webpack and React-Router.
  
- **Dynamic Vendor Bundling in Webpack**  
  https://medium.com/jeremy-gayed/dynamic-vendor-bundling-in-webpack-528993e48aab  
  An approach to dynamically adding anything from `node_modules` to a "vendor" bundle
  
- **Webpack Config: Commons Chunk Plugin part 1**  
  https://www.youtube.com/watch?v=-xzWMKuiS2o  
  An intro to what the Webpack Commons Chunk Plugin does and how it works
  
- **A beginner's step-by-step guide to Code Splitting with Webpack 2 and React Router**  
  http://brotzky.co/blog/a-beginners-step-by-step-guide-to-code-splitting-with-webpack-2-and-react-router/  
  An excellent guide to concepts and configuration needed for code splitting.
  
- **Lazily Load Code Declaratively in React and Webpack**  
  https://gist.github.com/iammerrick/f3f9edfbf5dc279af775f73020193dcc  
  Demonstrates one way to request and render components on demand, using Webpack's bundle-loader
  
- **Building Vendor and Feature Bundles with Webpack**  
  http://odetocode.com/blogs/scott/archive/2016/12/01/building-vendor-and-feature-bundles-with-webpack.aspx  
  Demonstrates using DllPlugin to build a vendor bundle, and generating multiple bundles for different features by dynamically building up multiple entry points.
  
- **Components a la carte**  
  http://darrennewton.com/2016/12/21/components-a-la-carte/  
  Describes a technique for dynamically loading only certain features that a user should see
  
- **Dynamic Imports with Webpack 2**  
  https://dev.to/kayis/dynamic-imports-with-webpack-2  
  A quick example of how to use dynamic imports to load pages or components at runtime
  
- **Lazy Loaded React Components with Webpack 2**  
  https://dev.to/kayis/lazy-loaded-react-components-with-webpack-2  
  A follow-on to the previous article, showing how to extend the dynamic imports approach to lazily load and render components
  
- **Vendor and code splitting in Webpack 2**  
  https://medium.com/@adamrackis/vendor-and-code-splitting-in-webpack-2-6376358f1923  
  An excellent dive into multiple aspects of code splitting, including basic setup, advanced config, and some Webpack gotchas/tips.
  
- **How to use Webpack's new "magic comment" feature with React Universal Component + SSR**  
  https://medium.com/webpack/how-to-use-webpacks-new-magic-comment-feature-with-react-universal-component-ssr-a38fd3e296a  
  Introduces Webpack's new "magic comments" feature for defining chunk names, and shows how to use that in association with a couple of libraries for optimized server-side rendering approaches
  
- **React Universal Component 2.0 & babel-plugin-universal-import**  
  https://medium.com/faceyspacey/announcing-react-universal-component-2-0-babel-plugin-universal-import-5702d59ec1f4  
  Introduces some new Webpack addons and changes that enable dynamic import expressions, including use with SSR.
  
- **Using Redux Saga and code splitting to async load React components**  
  https://gist.github.com/jballands/accc2ff19a3702685d469c612d6f0776  
  A gist that demonstrates using sagas to drive the loading of React components as needed, with some discussion in the comments of the best way to handle those components once they're received by the app.
  
- **Impress Your Friends with Code Splitting in React**  
  https://hackernoon.com/impress-your-friends-with-code-splitting-in-react-9f9a3ca2ae6e  
  Examples of using `async/await` and dynamic `import()` to lazy-load React components and display them after they're loaded.
  
- **ECMAScript Asychronicity - dynamic import**  
  https://blog.eleven-labs.com/en/ecmascript-asynchronicity-dynamic-import/  
  Recaps ES6 module behavior and use of Webpack's CommonsChunkPlugin, and describes how to lazy load code using `require.ensure` and the new dynamic `import()` capability.
  
  
#### Bundle Sizes and Visualization

- **Building Better Bundles**
  http://blog.isquaredsoftware.com/2016/11/posts-on-packtpub-generic-redux-modals-and-building-better-bundles/  
  An article describing what `process.env.NODE_ENV` means, and how it is used as part of a production build process to optimize build sizes

- **Chat discussion - summary of process.env.NODE_ENV and its use with Webpack**  
  https://gist.github.com/markerikson/6776848172c33aaa4db882627c689e18  
  An overview of how the `process.env.NODE_ENV` variable is often used to define optimizations for Webpack production builds

- **Webpack Bloat**  
  http://www.jamesonnetworks.com/entry/webpack-bloat  
  Discussion of how to improve production configurations for smaller bundle sizes

- **"Vector.im bundle is too big - analysis"**  
  https://github.com/vector-im/vector-web/issues/2498  
  Web perf expert Nolan Lawson analyzes why the JS bundle for the Vector.im web app is too big, and ways it could potentially be improved using code splitting and app structure changes.  A good example of ways to improve bundle sizes.
  
- **Unlocking a Mystery: Visualizing the Common Webpack Bundles**  
  https://www.redfin.com/blog/2016/12/unlocking-a-mystery-visualizing-the-common-webpack-bundles.html  
  A recap of some previous tools used to analyze Webpack bundle sizes, and description of a new tool they built to provide better bundle visualization
  
- **Analysing and minimising the size of client side bundle with Webpack and source-map-explorer**  
  https://medium.com/@nimgrg/analysing-and-minimising-the-size-of-client-side-bundle-with-webpack-and-source-map-explorer-41096559beca  
  Tips on using source-map-explorer to check the size of code included in a minified bundle, and removing unneeded polyfills
  
- **How to use source-map-explorer with Webpack**  
  https://www.sivadass.in/using-source-map-explorer-with-webpack/  
  Examples of using the source-map-explorer tool to visualize the contents of a bundle
  
- **Analyzing and optimizing your Webpack bundle**  
  https://medium.com/@ahmedelgabri/analyzing-optimizing-your-webpack-bundle-8590818af4df  
  Some quick suggestions for using CLI flags to show sizes of bundled chunks, and using webpack-bundle-analyzer and IgnorePlugin to exclude unneeded files.
  
- **Avoid Webpack bloat: Optimize your dependencies**  
  https://www.zillow.com/engineering/webpack-optimize-dependencies/  
  Tips for tracking bundle sizes and managing dependency handling
  
- **Webpack bits: getting the most out of the CommonsChunkPlugin**  
  https://medium.com/webpack/webpack-bits-getting-the-most-out-of-the-commonschunkplugin-ab389e5f318  
  Sean Larkin of the core Webpack team shares examples of common bundle size problems, and how to use the CommonsChunkPlugin to extract heavily used libraries into a separate bundle.
  
- **Weeding Out Your ES6 Webpack Bundle Sizes**  
  https://medium.com/lendingtree-engineering/weeding-out-your-es6-webpack-bundle-sizes-62cbc5a62a30  
  A recap of how adding a couple libraries to a production app resulted in much larger bundles, and some practical steps that can be taken to investigate and improve bundle sizes
  
- **How Webpack's ContextReplacementPlugin works**  
  https://iamakulov.com/notes/all/webpack-contextreplacementplugin/  
  An explanation of how ContextReplacementPlugin can be used to alter what files Webpack loads into a bundle.
  
- **How to do proper tree-shaking in Webpack 2**  
  https://blog.craftlab.hu/how-to-do-proper-tree-shaking-in-webpack-2-e27852af8b21  
  Explains several important concepts related to tree shaking, and how to configure Webpack and other tools to ensure it happens correctly.
  
- **3 ways to reduce Webpack bundle size**  
  http://blog.jakoblind.no/2017/05/18/3-ways-to-reduce-webpack-bundle-size/  
  A quick summary of some possible approaches to optimize bundle sizes, with links to more information
  
- **Introducing Bonsai: an open source Webpack analyzer**  
  https://medium.com/@Pinterest_Engineering/introducing-bonsai-an-open-source-webpack-analyzer-6bdfe22f8984  
  The Pinterest team describes the problems they'd encountered optimizing their Webpack bundles, and introduces a new tool to help analyze bundles and dependency trees.
  
- **Size Limit: Make the Web Lighter**  
  https://evilmartians.com/chronicles/size-limit-make-the-web-lighter  
  Demonstrates writing a tiny library that results in a 100KB Webpack bundle, and then walks through improving the Webpack settings to improve bundle size to only 17B.
  
- **Put Your Webpack Bundle On A Diet**  
  https://www.contentful.com/blog/2017/10/10/put-your-webpack-on-a-diet-part-1/  
  https://www.contentful.com/blog/2017/10/19/put-your-webpack-bundle-on-a-diet-part-2/  
  https://www.contentful.com/blog/2017/10/27/put-your-webpack-bundle-on-a-diet-part-3/  
  A multi-part series that covers approaches for shrinking bundle size, ranging from simply using Webpack's -p flag up to advanced optimizations.
  
  
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
  
 - **SurviveJS: Hot Module Replacement**  
   https://survivejs.com/webpack/appendices/hmr/  
   A guide to HMR concepts and usage, written by a Webpack core team member
  
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
  
- **Hot reload all the things!**  
  https://hackernoon.com/hot-reload-all-the-things-ec0fed8ab0  
  A tutorial that shows how to use Webpack and HMR to hot-reload both front-end and back-end code for faster development.
  
- **How to Hot-Load React Components in 7 Days**  
  https://medium.com/@antonkorzunov/how-to-hot-load-react-component-in-7-days-part-1-webpack-d8b77eea61eb  
  https://codeburst.io/how-to-hot-load-react-component-in-7-days-part-2-react-28ce2b61d0c7  
  A 2-part article that discusses how to set up plain HMR and add React-Hot-Loader, as well as many of the complexities of using RHL.


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
  
- **Webpack Tricks**  
  https://github.com/rstacruz/webpack-tricks  
  A useful list of tips for improving Webpack usage
  
- **Useful Webpack DefinePlugin Usage**  
  http://tomasalabes.me/blog/_site/web-development/2017/01/03/Useful-Webpack-Define-Plugin-Usages.html  
  Several useful tips and use cases for using the Webpack DefinePlugin, including logging, feature flags, and handling multiple environments
  
- **Artsy Webpack Tour**  
  https://github.com/TheLarkInn/artsy-webpack-tour  
  Sean Larkin of the Webpack core team gives a visually annotated tour of the Webpack 2 source code
  
- **Squeezing Webpack into backend frameworks**  
  https://infinum.co/the-capsized-eight/squeezing-webpack-into-backend-frameworks  
  Covers how to use Webpack to replace the Rails asset pipeline
  
- **Easy Offline First Apps with Webpack's Offline Plugin**  
  https://dev.to/kayis/easy-offline-first-apps-with-webpacks-offline-plugin  
  A look at how to use the OfflinePlugin to cache Webpack-generated assets for offline use.
  
- **Working with Fonts with Webpack**  
  https://shellmonger.com/2016/01/22/working-with-fonts-with-webpack/  
  Explains how to configure Webpack to use external font files.
  
- **Working on OkCupid "in production" with Webpack and localhost**  
  https://tech.okcupid.com/working-on-okcupid-in-production-with-webpack-and-localhost/  
  Describes setting up Webpack-Dev-Server to serve local files during development in a distributed build system.
  
- **Predictable long term caching with Webpack**  
  https://medium.com/@schnibl/predictable-long-term-caching-with-webpack-d3eee1d3fa31  
  A detailed look at issues that cause caching problems, and how to configure Webpack to get consistent chunk definitions for good caching results
  
- **Environment based application configuration using Webpack**  
  https://kostasbariotis.com/environment-based-application-configuration-using-webpack/  
  An explanation of how environment-based configuration is useful, and a couple examples of ways to handle config files for varying environments.
  
- **From Grunt and Bower to Webpack, Babel, and Yarn - Migrating a legacy front-end build system**  
  https://medium.com/appifycanada/migrate-to-webpack-from-grunt-bower-legacy-build-system-344526f47873  
  A recap of the steps needed to migrate an Angular app's build system to Webpack, including managing imports, handling global variables, and code splitting.
  
- **Case study: improving the Polished size for Webpack users**  
  https://iamakulov.com/notes/polished-webpack/  
  A detailed investigation of bundle size issues for the Polished library, and steps taken to improve the sizes for distribution.
  
- **Unambiguous Webpack Config with Typescript**  
  https://medium.com/webpack/unambiguous-webpack-config-with-typescript-8519def2cac7  
  Shows how to use Typescript and type definitions to ensure correct setup of Webpack configs.
  
- **Webpack 2 & Semantic-UI Theming**  
  https://medium.com/webmonkeys/webpack-2-semantic-ui-theming-a216ddf60daf  
  Discusses how to configure Webpack to load Semantic-UI's LESS files to allow use of a custom theme.
  

  
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

- **source-map-explorer**  
  https://github.com/danvk/source-map-explorer  
  Analyze and debug JavaScript (or Sass or LESS) code bloat through source maps.  Help determine which file each byte in your minified code came from.
  
- **bundle-buddy**  
  https://github.com/samccone/bundle-buddy  
  Bundle Buddy is a tool to help you find source code duplication across your javascript chunks/splits. This enables you to fine tune code splitting parameters to reduce bundle invalidation rates as well as improve repeat page load performance.
