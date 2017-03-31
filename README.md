# frontend-resources

A list of articles, books, projects, etc... about frontend development

* Books about javascript

  * Javascript
    * https://medium.com/javascript-scene/12-books-every-javascript-developer-should-read-9da76157fb3

  * Web Sites Performance
    * High performance web sites (oreilly)
    * Even faster web sites (oreilly)
    * Browser networking (oreilly)

* Redux ressources

  * https://robwise.github.io/blog/using-flow-annotations-in-your-redux-reducers
  * http://devguides.io/redux/
  * https://css-tricks.com/learning-react-redux/
  * https://egghead.io/courses/building-react-applications-with-idiomatic-redux
  * https://www.smashingmagazine.com/2016/06/an-introduction-to-redux/
  * http://blog.getstream.io/react-redux-best-practices-gotchas/?fthr=redditreact
  * https://www.ckl.io/blog/3-simple-steps-to-improve-react-redux-code/?
  * https://github.com/markerikson/redux-ecosystem-links
  * https://medium.com/javascript-scene/10-tips-for-better-redux-architecture-69250425af44
  * Redux async operations
    See this reddit thread:
    https://www.reddit.com/r/reactjs/comments/4ui5fj/is_there_a_community_consensus_on_async_actions/
    where the redux-saga emerge to me:
    https://github.com/yelouafi/redux-saga
  * Validate the shape of your state:
    see point 2 and 3
    http://movio.co/blog/5-useful-tips-real-world-redux/
  * What file hierarchy for a redux application?
    http://marmelab.com/blog/2015/12/17/react-directory-structure.html
    https://github.com/marmelab/javascript-boilerplate
    https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346
  * A Dummy’s Guide to Redux and Thunk in React
    https://medium.com/@stowball/a-dummys-guide-to-redux-and-thunk-in-react-d8904a7005d3#.hk9mhcf19
  * https://medium.com/statuscode/dissecting-twitters-redux-store-d7280b62c6b1

* App Starters

  * https://github.com/kriasoft/react-starter-kit
  * https://www.npmjs.com/package/kyt
  * Electrode, nwb, neo, next, gatsby, kyt

* Continuous integration

  * How does travis work?
    http://putaindecode.io/fr/articles/ci/travis-ci/
    http://www.raywenderlich.com/109418/travis-ci-tutorial

* Module bundlers
  * How does webpack work?
    https://egghead.io/lessons/tools-intro-to-the-production-webpack-course
    What's new in webpack 2:
    https://gist.github.com/sokra/27b24881210b56bbaff7
    http://javascriptplayground.com/blog/2016/06/react-webpack-workflow-screencast/
  * https://medium.com/@rajaraodv/two-quick-ways-to-reduce-react-apps-size-in-production-82226605771a
    1. Install DefinePlugin, DedupePlugin, UglifyJsPlugin, AggressiveMergingPlugin
    2. Serve gzipped file in production

* Transpilation
  * https://github.com/thejameskyle/babel-react-optimize

* CSS

  * How does css modules work?
  * https://www.sitepoint.com/how-and-why-you-should-inline-your-critical-css/
  * https://css-tricks.com/snippets/css/complete-guide-grid/
  * https://css-tricks.com/snippets/css/a-guide-to-flexbox/

* Node modules

  * Take a deep look on how npm works
    peerDependencies: https://nodejs.org/en/blog/npm/peer-dependencies/
    https://docs.npmjs.com/
    https://www.jayway.com/2014/03/28/running-scripts-with-npm/
  * yarn, a package manager by facebook
    https://code.facebook.com/posts/1840075619545360/yarn-a-new-package-manager-for-javascript/
    yarn cheatsheet:
    https://shift.infinite.red/npm-vs-yarn-cheat-sheet-8755b092e5cc

* Unit testing
  * http://codeutopia.net/h/mastering-javascript-unit-testing/
  * https://thoughtbot.com/upcase/fundamentals-of-tdd
  * http://thereignn.ghost.io/a-step-by-step-tdd-approach-on-testing-react-components-using-enzyme/
  * Code coverage tool
    https://github.com/gotwarlost/istanbul
    https://github.com/douglasduteil/isparta
    (Its intention is to be used with karma and karma-coverage, which
    provides code coverage reports using istanbul.)
  * https://medium.com/selleo/testing-react-components-best-practices-2f77ac302d12

* Type systems

  * Flow and Typescript
    http://putaindecode.io/fr/articles/js/flow/

* Code linting
  * Eslint
    http://codeutopia.net/docs/eslint/
  * For a faster linting
    https://www.npmjs.com/package/eslint_d

* es6

  * Learn es6
    https://egghead.io/courses/learn-es6-ecmascript-2015
  * The spread operator
    http://putaindecode.io/fr/articles/js/es2015/rest-spread/
  * Async/await
    http://putaindecode.io/fr/articles/js/es2016/async-await/
  * Object.assign
    http://putaindecode.io/fr/articles/js/es2015/object-assign/
  * Promises
    http://www.html5rocks.com/fr/tutorials/es6/promises/
    https://bitsofco.de/javascript-promises-101/

* React

  * Look for Michael Jackson and Ryan Florence
  * HOC
    http://putaindecode.io/fr/articles/js/react/higher-order-component/
    https://www.sitepoint.com/react-higher-order-components/
  * React europe
    http://blog.mojotech.com/a-look-back-at-react-europe/
  * Isomorphic
    * https://reactjsnews.com/isomorphic-react-in-real-life
    * https://github.com/DominicTobias/universal-react
    * https://github.com/petehunt/react-server-rendering-example
    * https://github.com/reactjs/redux/blob/master/docs/recipes/ServerRendering.md
    * https://medium.com/@firasd/quick-start-tutorial-universal-react-with-server-side-rendering-76fe5363d6e#.t0xw63ksc
    * http://www.electrode.io/docs/what_is_electrode.html
    * building isomorphic javascript apps oreilly book
    * Hastening React SSR with Component Memoization and Templatization
      https://www.youtube.com/watch?v=sn-C_DKLKPE
    * https://github.com/walmartlabs/react-ssr-optimization
    * https://github.com/aickin/react-dom-stream
    * https://github.com/redfin/react-server
    * Speed up server side rendering
      https://www.youtube.com/watch?v=PnpfGy7q96U
    * http://putaindecode.io/fr/articles/js/react/cote-serveur/
    * https://github.com/zeit/next.js
  * React howto by pete hunt
    https://github.com/petehunt/react-howto
  * State handling
    https://medium.com/react-ecosystem/how-to-handle-state-in-react-6f2d3cd73a0c#.v5am41omg
  * React ressources, awesome list
    https://github.com/enaqx/awesome-react
  * React starter kit (boilerplate)
    https://github.com/kriasoft/react-starter-kit
    https://github.com/gaearon/react-hot-boilerplate
  * React patterns
    https://github.com/krasimir/react-in-patterns
    https://blog.risingstack.com/react-js-best-practices-for-2016/
    https://www.reactenlightenment.com
    https://medium.com/@marcacyr/domain-architecture-software-engineering-23a0510ebdf
  * Top 10 react articles in july 2016
    https://medium.mybridge.co/top-10-react-js-articles-for-the-past-month-v-july-9840fd0ddb0#.ofa9pxx8h
  * http://devtalk.com/learn-react-js/
  * React monocle, A developer tool to visualize a React application's component hierarchy.
    https://github.com/team-gryff/react-monocle
  * Binding methods in components
    http://egorsmirnov.me/2015/08/16/react-and-es6-part3.html
    http://stackoverflow.com/questions/35734008/how-to-add-arguments-to-event-handler-in-es6-react-when-functions-are-bound-in-c
  * React native
    http://nativebase.io/
  * Components
    http://blueprintjs.com/
    https://github.com/brillout/awesome-react-components
    http://jxnblk.com/rebass
  * A react faq
    https://github.com/timarney/react-faq
  * React fiber
    https://github.com/acdlite/react-fiber-architecture
  * React performance tools
    https://facebook.github.io/react/docs/perf.html

* Express: learn how it works http://expressjs.com/

* Web Ressources to track
  https://nodejs.org/en/blog/
  https://facebook.github.io/react/blog/
  http://putaindecode.io/

* Code quality
    http://developer.telerik.com/featured/improving-quality-front-end-projects-automatically-pt-3-javascript-accessibility/

* Browser Performance
    What forces layout / reflow:
    https://gist.github.com/paulirish/5d52fb081b3570c81e3a
    see what css property triggers what:
    https://csstriggers.com/
    https://jakearchibald.com/2016/fun-hacks-faster-content/
    https://jakearchibald.github.io/isserviceworkerready/

* Immutable data
    https://github.com/markerikson/redux-ecosystem-links/blob/master/immutable-data.md

* Progressive Web Apps
    https://developers.google.com/web/progressive-web-apps/

* Progressive loading
    https://medium.com/@lavrton/progressive-loading-for-modern-web-applications-via-code-splitting-fb43999735c6#.e57nyr6bf
    https://medium.com/react-weekly/code-chunking-with-webpack-a-pragmatic-approach-e17e8bcc6453
    http://brotzky.co/blog/a-beginners-step-by-step-guide-to-code-splitting-with-webpack-2-and-react-router/?utm_source=reactnl&utm_medium=email

* Frontend masters
    https://frontendmasters.com/courses/good-parts-javascript-web/

* Error handling
  * https://www.sitepoint.com/logging-errors-client-side-apps/

* Angular
    https://medium.com/javascript-scene/angular-2-vs-react-the-ultimate-dance-off-60e7dfbc379c

* Vim

  * Vim test for running your tests:
    https://github.com/janko-m/vim-test
  * Setup vim for javascript:
    https://davidosomething.com/blog/vim-for-javascript/
  * vim snippets for React
    https://github.com/epilande/vim-react-snippets
  * vim snippets for es6
    https://github.com/epilande/vim-es2015-snippets

* Misc

  * How can translation keys string not be more than 80 characters?
    http://stackoverflow.com/questions/24562849/translating-multi-line-strings-in-javascript-with-django
    https://www.gnu.org/software/gettext/manual/html_node/Long-Lines.html
  * A pool to measure the usage of tools used by the js community: http://stateofjs.com/

* DDD
  * Eric Evans
    https://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215

  * Three Rules For Structuring (Redux) Applications
    https://jaysoo.ca/2016/02/28/organizing-redux-application/

* Metrics
  * https://github.com/rangle/redux-beacon
  * https://github.com/rangle/redux-segment
  * http://engineering.blogfoster.com/redux-for-better-in-app-analytics/
  * https://github.com/nfl/react-metrics
  * https://github.com/yahoo/react-i13n
  * https://github.com/rangle/redux-segment

* I18n internationalization
  * https://www.smashingmagazine.com/2017/01/internationalizing-react-apps/
