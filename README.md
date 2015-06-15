# react-bind-polyfill

This repo exists in order to define a bower package (react-bind-polyfill), I am not the author of this code. Taken from the fine folks at [Facebook](https://github.com/facebook/react/blob/3dc10749080a460e48bee46d769763ec7191ac76/src/test/phantomjs-shims.js).

I am aware of [this other bind polyfill from Mozilla](https://github.com/kdimatteo/bind-polyfill) – hey, most of this readme file comes from there – but it wasn’t working perfectly (`instanceof called on an object with an invalid prototype property`) and this one was, so I decided to package it and get on with my life.

Not needed for IE9+, FF4+ Webkit, Chrome 12+ (_but is needed for PhantomJS_). See [ES5 Compatibility Table](http://kangax.github.io/es5-compat-table/#Function.prototype.bind) for details.
