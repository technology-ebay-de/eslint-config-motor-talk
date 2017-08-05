# eslint-config-motor-talk

This package provides an _.eslintrc_ file as an extensible shared config.

[ESLint](http://eslint.org) is a tool for checking the syntax of JavaScript code.

The configuration provided in this artifact is used by projects related to the 
**MOTOR-TALK.de** platform, which is owned and maintained by **mobile.de GmbH**, 
part of the **[eBay Classifieds Group](https://github.com/technology-ebay-de)**.

## Usage

We export three ESLint configurations for your usage.

### eslint-config-motor-talk

Our default export contains all of our ESLint rules, including EcmaScript 6+
and React. It requires `eslint` and `eslint-plugin-react`.

1. `npm install --save-dev eslint-config-motor-talk eslint-plugin-react eslint`
2. add `"extends": "motor-talk"` to your .eslintrc, for example:

```
    {
        "extends": "motor-talk"
    }
```

### eslint-config-motor-talk/base

Lints ES6+ but does not lint React. Requires `eslint`.

1. `npm install --save-dev eslint-config-motor-talk eslint`
2. add `"extends": "motor-talk/base"` to your .eslintrc

### eslint-config-motor-talk/legacy

Lints ES5 and below. Only requires `eslint`.

1. `npm install --save-dev eslint-config-motor-talk eslint`
2. add `"extends": "motor-talk/legacy"` to your .eslintrc

See the [ESlint config docs](http://eslint.org/docs/user-guide/configuring#extending-configuration-files)
for more information.

## Contributing

Consider adding test cases if you're making complicated rules changes, like
anything involving regexes. Perhaps in a distant future, we could use literate
programming to structure our README as test cases for our .eslintrc?

You can run tests with `npm test`.

You can make sure this module lints with itself using `npm run lint`.

## Acknowledgements

This software is in large parts based on:

[Airbnb JavaScript Style Guide() {](https://github.com/airbnb/javascript) – A mostly reasonable approach to JavaScript
                                                                                     
Copyright © 2014-2017 Airbnb

## License

**The MIT License**

Copyright © 2017 mobile.de GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated 
documentation files (the 'Software'), to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and 
to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO 
THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS 
IN THE SOFTWARE.
