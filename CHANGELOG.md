3.1.1 / 2016-11-22
==================

Bugfix, eslint-plugin-react peer dependency is necessary

3.1.0 / 2016-11-22
==================

* Updated dependencies to latest minor versions
* Cleaned up deprecation warnings
* Tidied up peer dependencies

3.0.0 / 2016-10-25
==================

* Increased [maximum line length](http://eslint.org/docs/rules/max-len) from 100 to 120 characters
* Disabled [rule that enforces function names](http://eslint.org/docs/rules/func-names)
* Updated dependencies to latest and greatest:
  * [Babel](http://babeljs.io/) 6
  * [ESLint](http://eslint.org/) 3
  * [React](https://facebook.github.io/react/) 15

2.0.0 / 2016-09-22
==================

Switched rule [quotes](http://eslint.org/docs/rules/quotes) from double to single quotes.

1.0.5 / 2016-06-10
==================

Removed [no-nested-ternary](http://eslint.org/docs/rules/no-nested-ternary), can't really see what's
supposed to be so confusing about those.

1.0.4 / 2016-05-31
==================

Added [experimentalObjectRestSpread](http://eslint.org/docs/1.0.0/user-guide/configuring), which is
very useful for concise syntax in Redux code.

1.0.3 / 2016-05-13
==================

Removed [no-return-assign](http://eslint.org/docs/rules/no-return-assign) – we use return assignment
a lot in Mocha tests.

1.0.2 / 2016-05-12
==================

Changed [jsx-closing-bracket-location](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-closing-bracket-location.md)
to “after-props”.

1.0.1 / 2016-05-12
==================

Removed [jsx-indent-props](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-indent-props.md)
rule because it's really annoying.


1.0.0 / 2016-04-14
==================

Initial version based on eslint-config-mobile v6.1.0


