### React/Flux/Redux Pros, Cons, and Discussion

**Related Topics**:
- [Redux addons catalog - Apps and Examples](https://github.com/markerikson/redux-ecosystem-links/blob/master/apps-and-examples.md): Links to various projects built with Redux, both purpose-built-examples and "real" applications, as well as several Redux usage stories
- [Redux Architecture and Best Practices](./redux-architecture.md): many "lessons learned"-type articles after having used Redux


#### High-Level Comparisons and Business Cases

- **Using React is a Business Decision, Not a Technology Choice**  
  https://formidable.com/blog/2015/12/04/using-react-is-a-business-decision-not-a-technology-choice/  
  A higher-level, more business-case look at the pros of React

- **React: A Competitive Edge and a Business Decision**  
  https://reactjs-tampabay-b63e2.firebaseapp.com/#/  
  A slideshow laying out a number of arguments for using React
  
- **One Year of React.js at Arkency**  
  http://blog.arkency.com/2015/05/one-year-of-react-dot-js-in-arkency/  
  Thoughts on experience with using React
  
- **Productive Javascript Development**  
  http://benmccormick.org/2015/11/25/productive-javascript-development/  
  Looks at 6 ways different frameworks make things "easy": concepts, reading/writing code, architecting / maintaining / debugging apps. 
  
- **How React Helped Us Scale a Large Web App**  
  https://medium.com/opengov-developers/how-react-helped-us-scale-a-large-web-app-d89f96c4790a  
  A look at how React has been used to scale the OpenGov app architecture in terms of both users and developers.
  
- **The Other Reasons We Chose React**  
  https://wheniwork.engineering/the-other-reasons-we-chose-react-fbb37e570999  
  A summary of how When I Work evaluated several different frameworks for future development, and the reasons why they picked React
  
- **When Does a Project Need React?**  
  https://css-tricks.com/project-need-react/  
  Some useful thoughts on when it makes sense to use React: when there's lots of state, spaghetti code, or lots of DOM management.
  
- **Which Projects Need React?  All of Them!**  
  https://css-tricks.com/projects-need-react/  
  A response to the previous article, suggesting that React has benefits across a wide variety of applications.
  
- **Why I'm betting on React Native for my next Startup**  
  https://calbucci.com/why-im-betting-on-react-native-for-my-next-startup-3b8ff5ae03e4  
  A startup product lead gives several reasons why he's using React Native for their large app, including uniformity of experience, testing, recruiting, and scalability.
  
- **Why Choose React?**  
  https://www.lullabot.com/articles/why-choose-react  
  Some high-level thoughts on the benefits of choosing React, including proven use at scale, influence on the community, versatility, and that it's "just Javascript".
  
- **Why We Chose React To Help Serve Millions of Educators**  
  http://engineering.teacherspayteachers.com/2017/08/02/why-we-chose-react-to-help-serve-millions-of-educators.html  
  The Teachers Pay Teachers team describes why they chose React to rebuild their UI, including the small API size, size of the community, battle-tested capabilities, and more.
  
- **Justifying React to the Business**  
  https://daveceddia.com/react-business-value/  
  Covers several reasons why using React is a good business decision, including ease of maintenance, long-term usefulness, and risk, with a summary of justifications.
  
- **Why we built our new UI in React, from the ground up**  
  https://blog.cloud-elements.com/dev-discuss-why-we-built-our-new-ui-in-react-from-the-ground-up  
  The Cloud Elements team describes why they rewrote their UI in React, and how the React ecosystem worked well for their approach.
  
- **Advocating for software quality at METRO**  
  https://www.thoughtworks.com/insights/blog/advocating-software-quality-metro  
  The METRO Cash & Carry team discusses how they've handled migrating parts of their app from Reflux to Redux, including motivation, business issues, the case for quality, and their strategy for migrating.
  
  
#### Redux/Flux Comparisons
  
- **Redux: Concept Over Implementation**  
  http://www.schibsted.pl/2015/09/redux-concept-over-implementation/  
  Some high-level thoughts on why Redux over standard Flux
  
- **Why use Redux over Flux?**  
  http://stackoverflow.com/questions/32461229/why-use-redux-over-facebook-flux  
  Another good post from Redux's author comparing Redux and Flux
  
  
#### Other Comparisons
  
- **Flux is the new WndProc**  
  https://bitquabit.com/post/the-more-things-change/  
  https://news.ycombinator.com/item?id=10381015  
  An intriguing comparison between a React + a Flux-type architecture, and the classic Win32 WndProc message switch handling approach.  Plenty of good discussion in the comments.
  
- **I'm Sticking with React (For Now)**  
  https://hackernoon.com/im-sticking-with-react-for-now-47b792be555d  
  Some thoughts on the differences between React and other similar libs like Preact and Inferno, and why there's value in staying with React.
  
- **My experience with Redux**  
  https://medium.com/@ajchambeaud/my-experience-with-redux-90e4e4a31518  
  A look at Redux's influences, some experience using Redux, Dan Abramov's involvement with the community, and some other libs that may be interesting to look at.
  
- **What's good about Redux**  
  http://danielearwicker.github.io/What_s_good_about_Redux.html  
  Some thoughts on Redux's core "what-if?" questions, and some of the potential implications of those decisions.
  
- **Use Redux before it's too late**  
  https://medium.com/@ian.mundy/use-redux-before-its-too-late-a73d837a06aa  
  A response to the "you may not need Redux" discussions, suggesting that it's worth using Redux because it changes how you think about your data.

- **Redux is the Pivotal Frontend Innovation**  
  https://medium.com/@maxlynch/redux-is-the-pivotal-frontend-innovation-a406736552cb  
  An opinionated article that says state management is even more important than components.
  
- **Reflections on React**  
  https://medium.com/@burkeholland/reflections-on-react-65d152a13d9e  
  A former Telerik dev gives his thoughts on the current state of the React world, including how much people like it, use of standard JS syntax like classes, the variety of UI libs, and the lack of serious enterprise-class components like data grids and schedulers.  Some good discussion in the comments, too.
  
- **The delight of working on a React + Redux app**  
  https://medium.com/dailyjs/the-delight-of-working-on-a-react-redux-app-affc22757e81  
  Some interesting personal opinions on the benefits of working with React+Redux, including explicitness, traceability, and easy unit testing.
  
- **Don't Blame it on React or Redux**  
  https://diessi.ca/blog/dont-blame-it-on-react-or-redux/  
  Some short but well-written thoughts that argue in favor of React and Redux's "do it yourself" / "don't prescribe how to solve everything" approach, and that blaming them for bad app design or boilerplate is wrong.
  
- **What's So Great About Redux?**  
  https://medium.freecodecamp.org/whats-so-great-about-redux-ac16f1cc0f8b  
  https://twitter.com/modernserf/status/886426115874717697  
  Deep and fascinating analysis of how Redux compares to OOP and message-passing, how typical Redux usage can devolve towards Java-like "setter" functions with more boilerplate, and something of a plea for a higher-level "blessed" abstraction on top of Redux to make it easier to work with and learn for newbies.  Very worth reading.  The author originally wrote a tweetstorm, which I captured in the Storify link, and wrote the blog post to expand on those thoughts.  Finally, he followed up with a few more thoughts on abstract vs concrete examples in another shorter tweet thread.
  
- **Thoughts on Redux and its similarities with OOP**  
  https://medium.com/@dhruvrajvanshi/thoughts-on-redux-and-its-similarities-with-oop-6d200f34656  
  Another post that's very similar to "What's So Great About Redux?".  with thoughts on the overall benefits of Redux and some potential disadvantages in relation to use of TypeScript.  Some good discussion in the comments, too.
  
- **6 mistakes Reacters make that Re-framers avoid**  
  https://purelyfunctional.tv/article/react-vs-re-frame/  
  https://news.ycombinator.com/item?id=15157527  
  https://news.ycombinator.com/item?id=15158334  
  Comparisons between common React/Redux patterns, and how ClojureScript developers using the Reframe toolkit might solve the problems instead.  Some decent discussion in the HN comments, including one comment that directly responds to the points in the original article, and discusses how React+Redux give you the power to solve the specific problems you're dealing with.
  
- **Me on React: an old dog with new tricks**  
  https://remysharp.com/2017/08/14/me-on-react-an-old-dog  
  Remy Sharp, creator of JSBin, gives his thoughts and experiences learning React.  Discusses tooling support, styled-components, server-side rendering, hot reloading, tradeoffs and abstractions, and more.
  

#### Comment Threads and Discussions

- **What's Your #1 Problem With React?**  
  https://www.reddit.com/r/reactjs/comments/3pm4b8/we_all_love_react_but_whats_your_1_problem_with_it/  
  Developers discuss problems they've run into with React

- **Application Architecture with React**  
  https://news.ycombinator.com/item?id=10213905  
  More article discussion on React and Flux experiences

- **"Pros and Cons of React and Flux"**  
  https://www.reddit.com/r/reactjs/comments/39wsfi/what_are_pros_and_cons_of_using_reactjsflux/cs7msvp  
  A FANTASTIC comment that points out how each JS framework is a reaction to a specific category of problems

- **"Any Serious / Large / Real Web Apps with React and Flux?"**  
  https://www.reddit.com/r/reactjs/comments/3jcdfk/has_anyone_did_any_serious_large_real_web/  
  Good discussion of scaling React and Flux past a small toy app

- **"Redux feels bloat - what alternatives?"**  
  https://www.reddit.com/r/reactjs/comments/3towfy/redux_feels_bloated_complicated_and_not_easy_what/  
  Thoughts on Redux, its ecosystem, and API

- **"Getting Started with Redux" discussion**  
  https://www.reddit.com/r/javascript/comments/3u0167/getting_started_with_redux_a_free_30part_video/  
  Some great discussion on real-world experience with Redux, particularly by user TheAceOfHearts

- **"Why has Redux become so popular vs other Flux solutions"?**  
  https://www.reddit.com/r/reactjs/comments/3u54ju/why_has_redux_become_so_popular_vs_altjs_and/  
  Thoughts on the benefits and pros of using Redux

- **"Has anybody actually built a decent sized React app?"**  
  https://www.reddit.com/r/reactjs/comments/3wi0cx/has_anybody_actually_built_a_decent_sized_react/  
  More good discussion on practical experiences

- **"Here we see the culmination of the great Frameworks vs Libraries divide"**  
  https://news.ycombinator.com/item?id=10969819  
  A great piece of insight: "pick and choose libraries" vs "use a full framework" is a personal choice based on trust and decisiveness
  
- **"What are the real benefits of using Flux/Redux?"**  
  https://www.reddit.com/r/javascript/comments/3w8uey/what_are_the_real_benefits_of_using_fluxredux/  
  Discussion of some of the actual practical advantages of using Redux, with some thoughts on
similar structures in ClojureScript.

- **"React Tutorial: Cloning Yelp"**  
  https://news.ycombinator.com/item?id=11778663  
  https://news.ycombinator.com/item?id=11782234  
  Around 250 comments on React, dependency management, tutorial writing, and library churn.  Also a great quote on the inherent complexity of developing any application.
  
- **"9 things every ReactJS beginner should know"**  
  https://www.reddit.com/r/javascript/comments/42fo3m/9_things_every_reactjs_beginner_should_know/  
  Some interesting discussion on easy vs simple, desktop vs web, and managing container components.
  
- **"React.js Introduction for People Who Know Just Enough jQuery"**  
  https://news.ycombinator.com/item?id=9856855  
  https://news.ycombinator.com/item?id=9859143  
  https://news.ycombinator.com/item?id=9860960  
  A long discussion thread about many aspects related to use of React and frameworks.  Plenty of good discussion overall.  In addition, buried in the overall thread, some specifically insightful comments about managic codebase size and complexity, and doing web apps "by hand" with direct DOM manipulation vs what a framework like React provides.
  
- **"I'm a web dev who uses jQuery for a large app - How can I convince my bosses a JS framework is the way to go?"**  
  https://www.reddit.com/r/javascript/comments/3v43qf/im_a_web_developer_who_uses_jquery_to_write_a/  
  Another long, in-depth discussion thread on the merits of JS frameworks, as well as "big-bang" rewrites
  
- **"Why isn't AJAX present in Many examples of React/Flow/Redux?"**  
  https://www.reddit.com/r/reactjs/comments/4pbq2x/why_isnt_ajax_present_in_many_examples_of/  
  A long discussion thread that covers several topics related to tutorials, articles, and official docs, and various approaches.  Includes a couple comments from Dan Abramov on the limited size and scope of the React team.
  
- **"How can I better market my Javascript library?"**  
  https://news.ycombinator.com/item?id=11833301  
  The developer of a Redux wrapper library asks how to get more attention online.  I offer a pretty long reply comment describing the various network effects involved in any addon library, and critique his specific library from a Redux user's perspective.
  
- **"Our conversion from Angular to React"**  
  https://www.reddit.com/r/reactjs/comments/4upt6t/netlify_our_conversion_from_angular_to_react/d5smdih  
  A comment pointing out that React's "mostly the view" status enables it to be used in a wide variety of situations, which also means it works best when you are willing and able to come up with your own architecture.
  
- **"Dan Abramov: Redux is not an architecture or a pattern, it's just a library"**  
  https://www.reddit.com/r/javascript/comments/4rcqpx/dan_abramov_redux_is_not_an_architecture_or/  
  A discussion thread covering a number of aspects of Redux usage, including its relation with other libraries and patterns such as event sourcing.
  
- **"Why isn't AJAX present in many examples of React/Flow/Redux?"**  
  https://www.reddit.com/r/reactjs/comments/4pbq2x/why_isnt_ajax_present_in_many_examples_of/  
  Discussion of why a typical React app is made up of many different libraries and pieces.
  
- **"Confused: Redux or MobX?"**  
  https://www.reddit.com/r/reactjs/comments/4npzq5/confused_redux_or_mobx/  
  An in-depth thread comparing the two libraries.  Includes comments from both Dan Abramov of Redux and Michel Weststrate of MobX describing their libraries, as well a number of other good comparisons.
  
- **"A SoundCloud client in React and Redux**  
  https://news.ycombinator.com/item?id=11890229  
  Includes an extended discussion on use of Redux with forms
  
- **"Why Learning Angular 2 was Excruciating"**  
  https://news.ycombinator.com/item?id=12534296  
  https://news.ycombinator.com/item?id=12536634  
  Another very long thread about the JS ecosystem and versioning.  The linked comment describes how React, Redux, and Webpack have brought predictability to a particular application.
  
- **"React perf and optimization tests"**  
  https://twitter.com/AdamRackis/status/751486423232966656  
  Discussion of React's performance compared to an existing Handlebars/Knockout app
  
- **"Why is everying in Javascript changing so fast?**  
  https://news.ycombinator.com/item?id=11833301  
  https://news.ycombinator.com/item?id=12760268  
  https://news.ycombinator.com/item?id=12758514  
  Yet another rant thread about Javascript churn, but with a couple very insightful comments about the unique complexities and challenges involved in writing applications for the web.
  
- **"Youtube is being rebuilt on Web Components"**  
  https://www.reddit.com/r/javascript/comments/59ax4f/youtube_is_being_rebuilt_on_web_components_and/d97rsdd/  
  Some interesting thoughts on how various frameworks have approached composition, and how React helps make it more approachable.
  
- **"Modern JS developer workflow makes me sad"**  
  https://www.reddit.com/r/javascript/comments/5fphiw/modern_js_developer_workflow_makes_me_sad/  
  A fairly well-written rant about problems a dev was experiencing due to complexity of build tools.  There's extended discussion with some excellent suggestions and advice, and ultimately the author was able to resolve some of the complaints about build times and sourcemaps.
  
- **"Create an Instagram-like App with React, Node, and Redux"**  
  https://www.reddit.com/r/javascript/comments/5pyeni/tutorial_create_an_instagramlike_app_with_react/dcvlvzw/  
  A humorous comment summarizing the benefits of using React over jQuery, and Redux/MobX along with plain React.
  
- **"Is it a good practice to use Create-React-App for learning?"**  
  https://news.ycombinator.com/item?id=13944449  
  https://www.reddit.com/r/reactjs/comments/60vurv/is_using_create_react_app_bad_practice/  
  My comments addressing why CRA exists, and why it's a good idea to use it when learning React (especially in comparison to a "learn Webpack+Babel first" approach).
  
- **"React/Redux or Angular 2 better for big enterprise project?"**  
  https://www.reddit.com/r/javascript/comments/5wixxc/reactredux_or_angular_2_better_for_big_enterprise/  
  Some good discussion on what "enterprise" means, and the relative merits of various frameworks for building enterprise apps.
  
- **"Redux is overused. Use setState first unless you know why you need Redux"**  
  https://twitter.com/_jayphelps/status/846226930416345088  
  Jay Phelps, author of redux-observable, starts a long and involved Twitter thread about when it's appropriate to use Redux - use cases, app sizes, and reasons.  Lots of interesting opinions.
  
- **"Redux app size, boilerplate, and abstraction"**  
  https://news.ycombinator.com/item?id=15341562  
  https://news.ycombinator.com/item?id=15344600  
  https://news.ycombinator.com/item?id=15344447  
  A long subthread of the "React 16" announcement post that discusses several aspects of Redux "boilerplate" and abstraction.  I answered a lot of questions about how Redux can and should be used, and there were actually some excellent comments about how Redux usage pays off for long-term app maintainability.
  
- **How Redux can make you a better developer**  
  https://medium.cobeisfresh.com/how-redux-can-make-you-a-better-developer-30a094d5e3ec  
  https://www.reddit.com/r/javascript/comments/7buksy/how_redux_can_make_you_a_better_developer/  
  A blog post recapping aspects of functional programming and immutability in JS and Redux.  The Reddit thread has some excellent discussion on pros and cons of using Redux and how it has benefited people.
  
- **"React is focused on making your code understandable, not on making simple examples as short as possible"**  
  https://twitter.com/dan_abramov/status/930380316463726593  
  Some great points from Dan Abramov about React focusing on code predictability, maintainability, and data flow, rather than terseness.
  
- **"Ways to compose components and functionality without altering components?"**  
  https://twitter.com/andrestaltz/status/939123607426486274  
  https://twitter.com/andrestaltz/status/939257877600104448  
  https://gist.github.com/staltz/08bf613199092eeb41ac8137d51eb5e6  
  A couple very long Twitter threads with discussion from Andre Staltz (creator of Cycle), Dan Abramov, and Andrew Clark, looking at possible ways to handle composition of functionality for a "current humanized time" behavior.  Lots of interesting comments in the Twitter thread, and the example gist.  Also some useful comments from Andre on how someone from outside the React community might approach trying to solve problems using React.
  
  
  
#### React's PATENTS License

##### License Change to MIT

- **Relicensing React, Jest, Flow, and Immutable.js**  
  https://code.facebook.com/posts/300798627056246/relicensing-react-jest-flow-and-immutable-js/  
  Facebook's announcement that React and other projects are now using the MIT license

- **4 Lessons from the 'React Patent License' Controversy**  
  https://hackernoon.com/4-lessons-from-the-react-patent-license-controversy-3da3c4baf3a4  
  Some reactions to the MIT license change, and thoughts on how it affects React.



##### Prior Patents Discussion

- **Dan Abramov Twitter threads addressing patent concerns**  
  https://twitter.com/dan_abramov/status/754992075087745024  
  https://twitter.com/dan_abramov/status/766210972776337408  
  https://gist.github.com/gaearon/df0c4025e67399af72786d7ac7c819cc  
  A couple of extended discussions from Dan debunking myths about React's PATENTS clause, and a collection of further related links
  
- **React's license: necessary and open?**  
  http://lu.is/blog/2016/10/31/reacts-license-necessary-and-open/  
  Analysis from a lawyer on the merits of React's patent license, and whether it still qualifes as "Open Source".
  
- **React, Facebook, and the Revocable Patent License: Why it's a Paper Tiger**  
  https://medium.com/@dwalsh.sdlr/react-facebook-and-the-revokable-patent-license-why-its-a-paper-25c40c50b562  
  Analysis of the React patent license from an IP lawyer, in response to the latest set of discussions and arguments online
  
- **3 Points to Consider before Migrating Away from React because of Facebook's 'BSD+Patent' License**  
  https://medium.com/progressive-web-apps/react-progressive-web-apps-part-2-d55c6bd4b316  
  Several valuable thoughts from a patent attorney on what the React PATENTS license actually means, how it relates to "React alternatives" like Preact, and how it affects React users legally.
  
- **Open Source Community Over-REACTS to X Rated Code**  
  https://heathermeeker.com/2017/08/19/open-source-community-over-reacts-to-x-rated-code/  
  A patent attorney gives perspective on how React's PATENTS license is similar to already-existing licenses, and what that means for both the Apache Software Foundation and other React users.
  
- **Undersatnding the Facebook vs Apache Software Foundation License Kerfluffle**  
  http://writing.jan.io/2017/08/19/understanding-the-facebook-vs-asf-license-kerfuffle.html  
  A no-nonsense, clearly-written explanation of exactly what has happened regarding the Apache Software Foundation and the Facebook BSD+Patents license, including a timeline of events, summary of stances on both sides, and an FAQ on what it means.
  
- **Comments from other companies on the acceptability of the license**  
  https://wptavern.com/automattic-will-continue-to-use-react-js-in-calypso-despite-patent-clause  
  https://twitter.com/paul_irish/status/754864479460929536  
  https://twitter.com/palmerj3/status/766236192669073412  
  https://blogs.windows.com/buildingapps/2016/04/13/react-native-on-the-universal-windows-platform/  
  Comments from developers at Automattic, Google, Spotify, and Microsoft, indicating they're fine with using React
  
- **"Comment on the Apache Foundation's statement about Facebook's BSD+Patents license"**  
  https://www.reddit.com/r/programming/comments/6nnxir/apache_foundation_bans_use_of_facebook_bsdpatents/dkb3v4p/?context=3  
  One of the best layman's summaries I've seen about what the patents file actually means and is intended to do.
  
- **Further discussions**  
  https://news.ycombinator.com/item?id=12108273  
  https://news.ycombinator.com/item?id=12108526  
  https://vimeo.com/170598656#comment_14699807  
  https://github.com/facebook/react/issues/7293  
  https://news.ycombinator.com/item?id=12597488  
  https://www.reddit.com/r/reactjs/comments/6nx6jv/is_anyone_here_concerned_about_the_recent/  
  More discussion threads regarding the PATENTS license
  