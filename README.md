# eslint-config-barrett

[![npm version](https://badge.fury.io/js/eslint-config-barrett.svg)](https://badge.fury.io/js/eslint-config-barrett)

This package provides my .eslintrc as an extensible shared config.

## Usage

The default export contains all ESLint rules, including ECMAScript 6+ and React. It requires `eslint`, `eslint-config-airbnb` `eslint-plugin-import` `eslint-plugin-react` `eslint-plugin-jsx-a11y` `eslint`.

1. `npm install --save-dev eslint-config-barrett eslint-config-airbnb eslint-plugin-import eslint-plugin-react eslint-plugin-jsx-a11y eslint`
2. add `"extends": "barrett"` to your .eslintrc

See [Airbnb's Javascript styleguide](https://github.com/airbnb/javascript) and
the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.


