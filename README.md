# eslint-config-concrete-react
[![Build Status](https://travis-ci.org/concrete-cc/eslint-config-concrete-react.svg?branch=master)](https://travis-ci.org/concrete-cc/eslint-config-concrete-react)

Extending Airbnb's extensible shared config for React projects.

## Usage

Our default export extends [eslint-config-airbnb](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) ESLint rules, including ECMAScript 6+. It requires `eslint`, `eslint-plugin-import`, `eslint-plugin-jsx-a11y` and `eslint-plugin-react`.

1. `npm install --save-dev eslint-config-concrete-react eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint`
2. add `"extends": "concrete-react"` to your .eslintrc
