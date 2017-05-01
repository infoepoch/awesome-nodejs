# awesome-nodejs
我们常用的 Node.js 方法和模块整理

## Table of Contents

- [Packages](#packages)
	- [Command-line apps](#command-line-apps)
	- [HTTP](#http)
	- [Debugging / Profiling](#debugging--profiling)
	- [Logging](#logging)
	- [Command-line utilities](#command-line-utilities)
	- [Build tools](#build-tools)
	- [Hardware](#hardware)
	- [Templating](#templating)
	- [Web frameworks](#web-frameworks)
	- [Documentation](#documentation)
	- [Filesystem](#filesystem)
	- [Control flow](#control-flow)
	- [Streams](#streams)
	- [Real-time](#real-time)
	- [Image](#image)
	- [Text](#text)
	- [Number](#number)
	- [Math](#math)
	- [Date](#date)
	- [URL](#url)
	- [Data validation](#data-validation)
	- [Parsing](#parsing)
	- [Humanize](#humanize)
	- [Compression](#compression)
	- [Network](#network)
	- [Database](#database)
	- [Testing](#testing)
	- [Security](#security)
	- [Benchmarking](#benchmarking)
	- [Minifiers](#minifiers)
	- [Authentication](#authentication)
	- [Email](#email)
	- [Job queues](#job-queues)
	- [Node.js management](#nodejs-management)
	- [Polyfills](#polyfills)
	- [Natural language processing](#natural-language-processing)
	- [Process management](#process-management)
	- [Automation](#automation)
	- [AST](#ast)
	- [Static site generators](#static-site-generators)
	- [Content management systems](#content-management-systems)
	- [Forum](#forum)
	- [Blogging](#blogging)
	- [Weird](#weird)
	- [Miscellaneous](#miscellaneous)
- [Resources](#resources)
	- [Tutorials](#tutorials)
	- [Discovery](#discovery)
	- [Articles](#articles)
	- [Newsletters](#newsletters)
	- [Videos](#videos)
	- [Podcasts](#podcasts)
	- [Books](#books)
	- [Blogs](#blogs)
	- [Courses](#courses)
	- [Cheatsheets](#cheatsheets)
	- [Tools](#tools)
	- [Community](#community)
	- [Miscellaneous](#miscellaneous)


## Packages
### Command-line apps

- [Babel](https://babeljs.io/docs/usage/cli/) - Use next generation JavaScript, today.
- [ESLint](http://eslint.org) - The pluggable linting utility for JavaScript.
- [JSCS](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
- [Standard](https://github.com/feross/standard) - JavaScript Standard Style — One style to rule them all.
- [http-server](https://github.com/indexzero/http-server) - Simple, zero-config command-line HTTP server.

### HTTP

- [request](https://github.com/request/request) - Simplified HTTP request client.

### Debugging / Profiling

- [node-inspector](https://github.com/node-inspector/node-inspector) - Debugger based on Blink Developer Tools.

### Logging

- [log4js-node](https://github.com/nomiddlename/log4js-node) -  The Logging Framework for JavaScript.

### Build tools

- [gulp](http://gulpjs.com) - Streaming and fast build system that favors code over config.
- [browserify](https://github.com/substack/node-browserify) - Browser-side require() the Node.js way.
- [webpack](https://github.com/webpack/webpack) - Packs modules and assets for the browser.

### Templating

- [EJS](https://github.com/mde/ejs) - Simple unopinionated templating language.

### Web frameworks

- [Koa](http://koajs.com) - A new web framework designed by the team behind Express, which aims to be a smaller, more expressive, and more robust foundation for web applications and APIs.
	* [koa-json](https://github.com/koajs/json) - JSON pretty-printed response middleware. Also converts node object streams to binary.
	* [koa-router](https://github.com/alexmingoia/koa-router) - Router middleware for koa
	* [koa-views](https://github.com/queckezz/koa-views) - Template rendering middleware for koa
	* [koa-generic-session](https://github.com/koajs/generic-session) - koa generic session store by memory, redis or others
	* [koa-redis](https://github.com/koajs/generic-session) - Generic session middleware for koa, easy use with custom stores such as redis or mongo, supports defer session getter. different from koa-session(it is cookie session).
	* [koa-onerror](https://github.com/koajs/onerror) - an error handler for koa, hack ctx.onerror.
	* [koa-compress](https://github.com/koajs/compress) - Compress middleware for Koa
	* [koa-static](https://github.com/koajs/static) - Koa static file serving middleware, wrapper for koa-send.
	* [koa-bodyparser](https://github.com/koajs/bodyparser) - A body parser for koa, base on co-body. support json, form and text type body.
- [Express](http://expressjs.com) - A minimal and flexible web application framework, providing a robust set of features for building single and multi-page, and hybrid web applications.
- [ThinkJS](https://thinkjs.org) - Framework with ES2015+ support, WebSockets, REST API.

### Text

- [i18n-node](https://github.com/mashpie/i18n-node) - Simple translation module with dynamic JSON storage.

### Math

- [mathjs](https://github.com/josdejong/mathjs) - An extensive math library.

### Date

- [Moment.js](http://momentjs.com) - Parse, validate, manipulate, and display dates.


### Parsing

- [xml2js](https://github.com/Leonidas-from-XIV/node-xml2js) - XML to JavaScript object converter.

### Database

- Drivers
  - [MongoDB](https://github.com/mongodb/node-mongodb-native) - MongoDB driver.
  - [MySQL](https://github.com/felixge/node-mysql) - MySQL client.
	- [Redis](https://github.com/luin/ioredis) - Redis client.
- ODM / ORM
	- [Mongoose](http://mongoosejs.com) - Elegant MongoDB object modeling.
	- [Sequelize](https://github.com/sequelize/sequelize) - Multi-dialect ORM. Supports PostgreSQL, SQLite, MySQL.

### Minifiers

 - [UglifyJS2](http://lisperator.net/uglifyjs/) - JavaScript minifier.
 - [clean-css](https://github.com/jakubpawlowicz/clean-css) - CSS minifier.
 - [minimize](https://github.com/Swaagie/minimize) - HTML minifier.
 - [imagemin](https://github.com/imagemin/imagemin) - Image minifier.

### Email

 - [Nodemailer](https://github.com/andris9/Nodemailer) - The fastest way to handle email.

### Polyfills

 - Node.js
 - JavaScript
 	- [es6-shim](https://github.com/paulmillr/es6-shim) - Collection of ES2015 polyfills.
 	- More ES2015 polyfills at [es6-tools](https://github.com/addyosmani/es6-tools#polyfills).


### Process management

  - [PM2](https://github.com/Unitech/pm2) - Advanced Process Manager.
  - [forever](https://github.com/foreverjs/forever) - A simple CLI tool for ensuring that a given script runs continuously (i.e. forever).
  - [nodemon](https://github.com/remy/nodemon) - Monitor for changes in your app and automatically restart the server.

## License
