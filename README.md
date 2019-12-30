<div align="center">
  <img src="media/Title.svg"/>
  <br>
  <a href="https://awesome.re">
	  <img src="https://awesome.re/badge-flat.svg" alt="Awesome">
  </a>
  <p>A curated list of awesome ponyfills for writing cross-platform and cross-browser code.</p>
</div>

Use these modules when looking to support older browsers or node versions without polluting the prototype. See [ponyfill.com](https://ponyfill.com) for more info.

## Contents

- [Cross-platform](#cross-platform)
  - [ECMAScript Features](#ecmascript-features)
  - [Browser Features](#browser-features)
  - [Node.js Features](#nodejs-features)
- [Browser Environment Only](#browser-environment-only)
  - [JavaScript Features](#javascript-features)
  - [Other](#other)

## Cross-platform

### ECMAScript Features

- ⭐️ [core-js-pure](https://github.com/zloirock/core-js) - The entire standard library.
- [array-from](https://github.com/studio-b12/array-from) - [`Array.from`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from)
- [es6-promise](https://github.com/stefanpenner/es6-promise) - [`Promise`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [es6-map](https://github.com/medikoo/es6-map) - [`Map`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)
- [es6-set](https://github.com/medikoo/es6-set) - [`Set`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)
- [es6-symbol](https://github.com/medikoo/es6-symbol) - [`Symbol`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
- [array-map](https://github.com/substack/array-map) - [`Array.prototype.map`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- [array-foreach](https://github.com/twada/array-foreach) - [`Array.prototype.forEach`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
- [object-assign](https://github.com/sindresorhus/object-assign) - [`Object.assign`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
- [indexof](https://github.com/component/indexof) - [`Array.prototype.indexOf`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf) and [`String.prototype.indexOf`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf).
- [array.prototype.flatmap](https://github.com/es-shims/Array.prototype.flatMap) - [`Array.prototype.flatMap`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)
- [object-keys](https://github.com/ljharb/object-keys) - [`Object.keys`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
- [array-includes](https://github.com/es-shims/array-includes) - [`Array.prototype.includes`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
- [object.fromentries](https://github.com/es-shims/Object.fromEntries) - [`Object.fromEntries`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/fromEntries)
- [string.prototype.trim](https://github.com/es-shims/String.prototype.trim) - [`String.prototype.trim`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/Trim)
- [string.prototype.trimleft](https://github.com/es-shims/String.prototype.trimleft) - [`String.prototype.trimStart`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/TrimStart)
- [string.prototype.trimright](https://github.com/es-shims/String.prototype.trimright) - [`String.prototype.trimEnd`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/TrimEnd)
- [console.table](https://github.com/bahmutov/console.table) - [`console.table`](https://developer.mozilla.org/en-US/docs/Web/API/Console/table)

### Browser Features

- [cross-fetch](https://github.com/lquixada/cross-fetch) - [`fetch`](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- [cross-blob](https://github.com/Richienb/cross-blob) - [`Blob`](https://developer.mozilla.org/en-US/docs/Web/API/Blob)
- [cross-formdata](https://github.com/Richienb/cross-formdata) - [`FormData`](https://developer.mozilla.org/en-US/docs/Web/API/FormData)
- [abortcontroller-polyfill](https://github.com/mo/abortcontroller-polyfill) - [`AbortController`](https://developer.mozilla.org/en-US/docs/Web/API/AbortController)
- [@fastly/performance-observer-polyfill](https://github.com/fastly/performance-observer-polyfill) - [`PerformanceObserver`](https://developer.mozilla.org/en-US/docs/Web/API/PerformanceObserver)
- [performance-now](https://github.com/braveg1rl/performance-now) - [`performance.now`](https://developer.mozilla.org/en-US/docs/Web/API/Performance/now)

### Node.js Features

- [events](https://github.com/Gozala/events) - [`EventEmitter`](https://nodejs.org/api/events.html#events_class_eventemitter)
- [tickedoff](https://github.com/jamiebuilds/tickedoff) - [`setImmediate`](https://nodejs.org/api/timers.html#timers_setimmediate_callback_args)

## Browser Environment Only

### JavaScript Features

- [resize-observer-polyfill](https://github.com/que-etc/resize-observer-polyfill) - [`ResizeObserver`](https://developer.mozilla.org/en-US/docs/Web/API/ResizeObserver)
- [webcrypto-shim](https://github.com/vibornoff/webcrypto-shim) - [`crypto`](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API)

### Other

- [css-vars-ponyfill](https://github.com/jhildenbiddle/css-vars-ponyfill/) - [CSS variables/custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
