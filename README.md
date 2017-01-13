# Angular 2 Components 

> Basic and useful components for any project in Angular 2

## Goal

Angular 2 Components, is a project where I create the most basic and useful components used by any Web Site which use *Angular 2*.

### Features

| Feature                                | Summary                                                                                                                                                                                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sass support                           | Compile [Sass](http://sass-lang.com/) into CSS with ease, bringing support for variables, mixins and more. (Run `gulp serve` or `gulp` for production)                                                                                                      |
| Performance optimization               | Minify and concatenate JavaScript, CSS, HTML and images to help keep your pages lean. (Run `gulp` to create an optimised version of your project to `/dist`)                                                                                                |
| Code Linting                           | JavaScript code linting is done using [ESLint](http://eslint.org) - a pluggable linter tool for identifying and reporting on patterns in JavaScript. Web Starter Kit uses ESLint with [eslint-config-google](https://github.com/google/eslint-config-google), which tries to follow the Google JavaScript style guide.                                                                                                |
| ES2015 via Babel 6.0                   | Optional ES2015 support using [Babel](https://babeljs.io/). To enable ES2015 support remove the line `"only": "gulpfile.babel.js",` in the [.babelrc](.babelrc) file. ES2015 source code will be automatically transpiled to ES5 for wide browser support.  |
| Built-in HTTP Server                   | A built-in server for previewing your site locally while you develop and iterate                                                                                                                                                                            |
| Live Browser Reloading                 | Reload the browser in real-time anytime an edit is made without the need for an extension. (Run `gulp serve` and edit your files)                                                                                                                           |
| Angular 2                              | [Angular](https://angular.io/) is a development platform for building mobile and desktop web applications |

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 9+

## Installation

1. **Clone** or **Download** the git project.

2. [Use npm](https://docs.npmjs.com/cli/install) to install all dependencies in the _package.json_.
```sh
npm install
```

3. Once you finish to install the dependencies you can start the project using the *gulp tasks*. 
(please review the *gulpfile.babel.js*.

## Usage

#### Run development tasks:
By default *gulp* command run the *development* task.

- Start the server in development mode
```
gulp serve
```

- Start the server in production mode
```
gulp serve:dist
```

## Licence
**
Apache 2.0
    
