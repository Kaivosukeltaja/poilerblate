[![Build Status](https://travis-ci.com/skope/poilerblate.svg?token=jnzpgovcYpqFiQcSVa8D&branch=master)](https://travis-ci.com/skope/poilerblate)

# poilerblate

What's included:

- [React](https://github.com/facebook/react)
- [React Router 4](https://reacttraining.com/react-router/)
- [Redux](http://redux.js.org/)
- [React Redux](https://github.com/reactjs/react-redux)
- [SASS](http://sass-lang.com/)
- [Jest](https://facebook.github.io/jest/)

## Building

Issue command `npm run build`.

Production ready bundle is stored in `dist/` and can be used as-is.

## Running tests

Issue command `npm test`. It runs test cases once and exits.

If you want to run tests in watch mode, you can install [jest](https://facebook.github.io/jest/) globally with `npm i -g jest` and calling it with `jest --watch`.

Component specific tests are stored in `src/components/<ComponentName>/<ComponentName>.test.js` and actions/reducers tests in `__tests__/`.

## Development

Type `npm start` and development server is launched to (http://localhost:3000). If you want to set another port, environment variable PORT can be passed to the start script like `PORT=4000 npm start`.

Main index page template is located in `src/templates/index.html`.

All code must be located in `src/`.
