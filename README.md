Babel Helper Modules
====================

Regard as an alternative to [babel-runtime](https://www.npmjs.com/package/babel-runtime).

A distribution of the modules from [babel-helpers](https://www.npmjs.com/package/babel-helpers), compiled into ES5 using a modified script from `babel-runtime`.

This is meant to be used in conjunction with [babel-plugin-transform-helper-modules](https://www.npmjs.com/package/babel-plugin-transform-helper-modules), in order to reuse the helpers when creating bundles without including the [core-js](https://www.npmjs.com/package/core-js) library etc. like `babel-runtime` do.  This lets you choose which polyfill you want, for instance the [babel-polyfill](https://www.npmjs.com/package/babel-polyfill), which includes a version of `core-js` that lets you use polyfilled instance methods like `Array.prototype.find()`.
