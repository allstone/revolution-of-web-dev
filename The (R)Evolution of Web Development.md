# The (R)Evolution of Web Development

## Intro

My name is Mark Erikson, and  I work for the BACN program as part of the BIB application team.  This talk is about the tools, technologies, and concepts involved in modern web development.  The most important things for you to take away from this talk are:


- The tools and technologies used to build web applications have changed dramatically in the last few years
- The modern web development technology ecosystem includes a wide variety of tools, approaches, and concepts that are commonly used or considered to be "best practices"
- These modern tools and technologies can be complex, but also enable building powerful and complex web applications that weren't previously possible, as well as development techniques that improve development speed and maintainability


## A Brief History of Web Development

- Web 1.0 (1991-2001)
  - Typical site: static HTML, hosted on GeoCities, and written in FrontPage or DreamWeaver
  - Technologies: /CGI-BIN -> Perl -> PHP/ASP -> Java / .NET
  - Applications: scripts or mid-sized servers
  - Interactivity: Java applets, ActiveX, DHTML
  - Browsers: Mosaic, Netscape, IE
  - Major milestones: Birth of JS / HTML / CSS
  - Code sharing: "script list" sites
  - Common data format: plain HTML with tables
- Web 2.0 (2001-2010)
  - Typical site: server-rendered pages, MySQL database, running on J2EE or Rails
  - Server technologies: J2EE, ASP.NET, Rails, Django, LAMP
  - Client technologies: AJAX, MooTools/Prototype, jQuery
  - Browsers: Mozilla -> Firefox, IE6 -> IE8, Opera, Chrome
  - Rich Internet Applications (Flash, Silverlight, GWT)
  - Major milestones: AJAX, smartphones, JSON
  - Code sharing: SourceForge
  - Common data format: XML
- The Modern Era (2010-2016)
  - Typical site: client-side JS, JSON API, microservices built with Node running on AWS, NoSQL DB
  - Server technologies: Node/Express, AWS, Play, DropWizard, ASP.NET MVC, Heroku
  - Client technologies: HTML5, Backbone, Angular, Ember, React, Bootstrap
  - Browsers: Chrome, FF, Edge, all "evergreen"
  - Single-Page Applications
  - HTML5: canvas / WebGL, WebSockets, Web Workers, data storage, flexbox, OS/native APIs
  - Major milestones: Node, death of plugins
  - Code Sharing: Github
  - Common data format: JSON


- History of Javascript
  - Invention
  - ES3
  - jQuery
  - ES5
  - Node
  - Backbone, Underscore, CoffeeScript
  - ES6
  - Beyond

## The Modern Web Dev Landscape

- "Dancing Monkeys" (?)
  - Not just doing tiny scripts any more - now building complete applications where all the logic lives in the browser ( https://news.ycombinator.com/item?id=11782234 ).  More than just "render some HTML to show our data".
  - Keep state out of the DOM
- Driving concerns
  - Minimize bytes over the wire
  - Compatibility between browsers
  - Fill in gaps in JS standard library and language spec
  - Code reuse and sharing
  - Increasing size and complexity of applications
- Tools and Concepts
  - Languages
    - ES6 / ES2015
    - Babel
    - TypeScript
    - SASS/LESS
  - Code Reuse and Sharing
    - Module formats: AMD, CommonJS, ES6
    - Packaging: Node, NPM
  - Build Tools
    - Bundling, minification, code splitting
    - Grunt, Gulp
    - Browserify, Webpack
  - Dev Experience
    - Live reloading, Hot reloading, Sourcemaps
  - Testing
    - Test runners: Mocha, Jasmine, Tape, Karma
    - Assertions: Chai
    - Mocking: Sinon
    - Browser testing: Selenium, PhantomJS; JSDOM
  - Linting
    - ESLint
  - Standard Library fillins
    - jQuery, Underscore/Lodash, etc
  - JS Frameworks
    - "Every framework is..." (https://www.reddit.com/r/reactjs/comments/39wsfi/what_are_pros_and_cons_of_using_reactjsflux/cs7msvp)
    - Backbone
    - Angular
    - Ember
    - React
  - Routing
  - Data Management
    - Flux
    - Redux
  - Other Trends
    - Backends
      - X as a Service, "serverless" backends
      - Microservices, containers
    - Client/Server
      - Data transfer schemas/tools: GraphQL, Falcor
      - Isomorphic/universal apps
      - Cross-platform / desktop / mobile JS apps
    - Client-side
      - Component architecture
      - Virtual DOM
      - CSS in JS
      - WebGL, Web Workers, Service Workers
      - Alternate languages (Elm, Clojure)
    - Conceptual
      - Functional Programming
      - Reactive Programming
      - Typing


## Building a Modern Web App

- Quick Kontour v1 demo (w/ GE plugin?)
- GWT concerns / rationale
- Goals / drivers
  - Non-deprecated tech stack with modern tools
  - Improved dev experience
  - Better maintainability (code structure, debugging, dataflow / reasoning)
  - Thinking in React principles ( http://banderson.github.io/reactive-component-ui-presentation/#/2 )
- Technologies
  - ES6
  - React
  - Redux
  - Webpack
  - Mocha test stack
  - Cesium
  - Semantic-UI
- Kontour v2 prototype demo
  - File watching
  - Hot reloading
  - Redux DevTools and time travel debugging
  - Selected item editing
  - Test running

## Closing

- Summary: Tons of tools. Don't get overwhelmed, don't have to use everything or chase the new shiny. Pick stuff that fits your task.
- Further resources