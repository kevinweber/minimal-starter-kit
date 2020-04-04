# Minimal Starter Kit

Minimal build setup using Webpack, Babel (ES6-support), SCSS and ESLint.

This starter kit is made so you can quickly write small prototypes using JavaScript and SCSS.

## Usage:

1. Download kit to your computer. Run in terminal: `git clone https://github.com/kevinweber/minimal-starter-kit.git`
2. Navigate into the root folder of the downloaded kit: `cd minimal-starter-kit/`
3. If you don't have NPM on your machine yet, install it: https://docs.npmjs.com/getting-started/installing-node
4. Run `npm install` to install dependencies.
5. Run `npm start` to bundle JavaScript and SCSS.
6. Open `dist/index.html` in your browser (e.g. by running `npm run open`).

## It comes with:

- NPM for managing packages and running tasks.
- Babel so you can utilize the latest JavaScript features.
- SCSS for convenience. (You can still write basic CSS in a SCSS file.)
- ESLint to ensure basic code quality.
- Webpack for compiling and bundling everything.
- Task: `npm start` bundles JS and SCSS into two separate files.
- Task: `npm run watch` bundles JS and SCSS whenever a JS or SCSS file changes.
- Task: `npm run production` bundles, minifies and optimizes everything.

## It does NOT include:

- Yarn
- React/JSX or other libraries
- Express server
- LiveReload/BrowserSync

... to keep the build setup simple and easily adjustable for individual needs.
