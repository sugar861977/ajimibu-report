# es6-shim 0.5.3 (September 2, 2012)
* Made `String#startsWith`, `String#endsWith` fully conform spec.

# es6-shim 0.5.2 (June 17, 2012)
* Removed `String#toArray` and `Object.isObject` as per spec updates.

# es6-shim 0.5.1 (June 14, 2012)
* Made Map and Set follow Spidermonkey implementation instead of V8.
`var m = Map(); m.set('key', void 0); m.has('key');` now gives true.

# es6-shim 0.5.0 (June 13, 2012)
* Added Number.MAX_INTEGER, Number.EPSILON, Number.parseInt,
Number.parseFloat, Number.prototype.clz, Object.isObject.

# es6-shim 0.4.1 (May 11, 2012)
* Fixed boundary checking in Number.isInteger.

# es6-shim 0.4.0 (February 8, 2012)
* Added Math.log10, Math.log2, Math.log1p, Math.expm1, Math.cosh,
Math.sinh, Math.tanh, Math.acosh, Math.asinh, Math.atanh, Math.hypot,
Math.trunc.

# es6-shim 0.3.1 (January 30, 2012)
* Added IE8 support.

# es6-shim 0.3.0 (January 27, 2012)
* Added Number.isFinite() and Object.isnt().

# es6-shim 0.2.1 (January 07, 2012)
* Fixed a bug in String#endsWith().

# es6-shim 0.2.0 (December 25, 2011)
* Added browser support.
* Added tests.
* Added Math.sign().

# es6-shim 0.1.0 (December 25, 2011)
* Initial release
