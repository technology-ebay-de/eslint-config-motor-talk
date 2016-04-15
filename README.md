# eslint-config-motor-talk

This package provides Motor-Talk's .eslintrc as an extensible shared config.

It is based on a copy from mobile.de's .eslintrc artifact in the eBay corp GitHub repository 
[mobile-de/mde-javascript-styleguide](https://github.corp.ebay.com/mobile-de/mde-javascript-styleguide/).

## Usage

We export three ESLint configurations for your usage.

### eslint-config-motor-talk

Our default export contains all of our ESLint rules, including EcmaScript 6+
and React. It requires `eslint` and `eslint-plugin-react`.

1. `npm install --save-dev eslint-config-motor-talk eslint-plugin-react eslint`
2. add `"extends": "motor-talk"` to your .eslintrc, for example:

    {
        "extends": "motor-talk"
    }

### eslint-config-motor-talk/base

Lints ES6+ but does not lint React. Requires `eslint`.

1. `npm install --save-dev eslint-config-motor-talk eslint`
2. add `"extends": "motor-talk/base"` to your .eslintrc

### eslint-config-motor-talk/legacy

Lints ES5 and below. Only requires `eslint`.

1. `npm install --save-dev eslint-config-motor-talk eslint`
2. add `"extends": "motor-talk/legacy"` to your .eslintrc

See [mobile.de's Javascript styleguide](https://github.corp.ebay.com/mobile-de/mde-javascript-styleguide/) and
the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.

## Improving this config

Consider adding test cases if you're making complicated rules changes, like
anything involving regexes. Perhaps in a distant future, we could use literate
programming to structure our README as test cases for our .eslintrc?

You can run tests with `npm test`.

You can make sure this module lints with itself using `npm run lint`.
