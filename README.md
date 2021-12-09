# boilerplate-npm-html
* main entry point is `main.js`

A boilerplate npm project for generating HTML using npm and a build toolchain. Using:
* `node-sass` which compiles `.scss` files in CSS
* `autoprefixer` & `postcss-cli` to add vendor prefixes to compiled CSS
* `stylelint` to check for errors in CSS
* `onchange` to rebuild CSS whenever a change occurs in an `.scss` file
* `browser-sync` to run a local web server
* `bpm-run-all` to run multiple npm-scripts in parallel or sequential mainly for Windows systems
* `imagemin-cli` to minify images
* `webpack` & `babel` to use modern JS syntax and transpile into browser compatible JS
* `eslint` to keep the code more consistent and to avoid bugs
* `posthtml` & `posthtml-modules` to use HTML partials i.e. `<module href="/components/head.html"></module>`

## Javascript
* Always import Javascript modules into `main.js` to keep things tidy

## SCSS
* Always import scss modules into `index.scss` to keep things tidy

## npm commands
* `npm run build` runs all `build:*` scripts in parallel
* `npm run watch` runs all `watch:*` scripts and starts the local web server in parallel
* `npm run serve` runs a web server using files in the `/dist` directory

## Quickstart
1. run `npm i` to install all dependecies
2. run `npm run build` to build to the output `/dist` directory


