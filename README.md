## web-app-boilerplate

Starter boilerplate template for web apps

**Setup**

```sh
$ npm install
```

**Develop with Livereload**

```sh
$ npm run dev
```

  > * [nodemon](https://github.com/remy/nodemon) to monitor and reload `server.js` changes
  > * [watchify](https://github.com/substack/watchify) to rebuild `app.js` on file change and livereloads in browser
  > * [Browsersync](https://www.browsersync.io/) to reload browser when server or client code changes

**Test**  

[mocha](https://mochajs.org/) tests with [es6 babel](https://babeljs.io/docs/setup/#mocha) support

Tests are located in `test/`

```sh
$ npm test
```

**Build**

```sh
$ npm run build
```

**Files**

* `server.js` - express server
* `app.js` - client side app
* `config/index.js` - config data

# TODO

* remove hard coded sleep for browsersync start.
  * poll every second for port 3000 in use, when it is, launch browsersync
