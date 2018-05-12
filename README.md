# Front End Boilerplate Dev Setup

## Description

This "template" is quite fleshed out to anticipate many of a front-end project's needs. You can examine the package.json and gulpfile.js files and prune down what you don't need. There are some pre-built common gulp tasks within the "gulp/tasks" subdirectory - you can prune these down/modify as needed.

## Commands
### Install + Update
Git clone or fork repo and rename.

`ncu -u` then `npm install`. See [npm-check-updates](https://www.npmjs.com/package/npm-check-updates)

### Usage
`gulp watch` Spins up local dev server, watches for markup or asset changes then dynamically loads new content

`gulp build` Outputs a build of the app to directory `dist`, compressing all assets and images

## Included dev dependencies
-`"autoprefixer": "^8.0.0"` Used with gulp to add browser prefixes to styles where need be

-`"babel-core": "^6.26.0"` ES6 transpiler

-`"babel-loader": "^7.1.4"`

-`"babel-preset-es2015": "^6.24.1"`

-`"browser-sync": "^2.23.6"` Used with gulp to watch for markup/style/script change and then refresh browser

-`"del": "^3.0.0"` Used in the build task to delete the previous dist directory

-`"gulp": "^3.9.1"` Main task runner

-`"gulp-cli": "^2.0.1"`

-`"gulp-cssnano": "^2.1.3"` Minifies CSS

-`"gulp-imagemin": "^4.1.0"` Compresses images

-`"gulp-modernizr": "^2.0.1"` Adjusts or replaces styles that are unsupported in browsers to make them work again

-`"gulp-postcss": "^7.0.1"` Css preprocessor

-`"gulp-rename": "^1.2.2"` Used in build task

-`"gulp-rev": "^8.1.1"` Used to give a version no. to new builds

-`"gulp-uglify": "^3.0.0"` Uglifies JS

-`"gulp-usemin": "^0.3.29"`

-`"gulp-watch": "^5.0.0"` Works with browsersyn plugin

-`"postcss-hexrgba": "^1.0.0"` Allows you to input

-`"postcss-import": "^11.1.0"` Allows for importing of postcss modules

-`"postcss-mixins": "^6.2.0"` Allows for css mixins(like media queries)

-`"postcss-nested": "^3.0.0"` Allows for nested css syntax

-`"postcss-simple-vars": "^4.1.0"` Allows for css variables(like colour values)

-`"waypoints": "^4.0.1"` JS library that facilitates function execution when you scroll to an element

-`"webpack": "^4.5.0"` JS/module bundler

-`"webpack-cli": "^2.0.14"`
