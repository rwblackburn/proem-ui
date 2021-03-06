Proem UI Framework
===========

This is a ReactJS project boilerplate. This includes, by default:

* [Redux](http://redux.js.org/) - Maintains the state of the app.
* [Babel](https://babeljs.io/) - Compiles the app.
* [Webpack](https://webpack.github.io/) - Bundles the app. 
* [Jasmine](https://jasmine.github.io/) / [Karma](https://karma-runner.github.io) - Tests the app. 
* [Axios](https://github.com/mzabriskie/axios) - Makes promise base HTTP calls for the app. 
* [Material-ui](http://www.material-ui.com/) - Makes the app pretty.

This framework is designed to be a web app (a SPA), which can easily be deployed using something like [Electron](https://www.electronjs.org/) (to deploy it as a Windows/Mac client) or [Cordova](https://cordova.apache.org/) (to deploy it as a iOS/Andoird app)

Getting Started
---------------
To create your app, run:
```shell
$ npx proem-ui my-app
```

Once done, simple run:
```
$ cd my-app
$ npm start
``` 

Directory Layout
---------------
The web directory contains the web UI.

```shell
/
├── /actions/                   # Redux action function library
├── /components/                # Shared or generic UI components
│   └── /...                    # Each component should get its own folder (that matches the name of the component)
├── /pages/                     # React components for web pages
│   ├── /about/                 # About page
│   ├── /error/                 # Error page
│   ├── /home/                  # Home page
│   └── /...                    # etc.
├── /utils/                     # Utility and helper classes
│── index.html                  # React application entry point
│── package.json                # The list of project dependencies and NPM scripts
│── renderer.js                 # This root application script, will be bundled into `renderer-bundle.js` using webpack
│── store.js                    # The root Redux data store
└── webpack.*.js                # Bundling and optimization settings for Webpack
```

Getting Help
---------------
Guides, tutorials, and tips can be found on the [Proem-UI site](http://www.proemui.com/).


