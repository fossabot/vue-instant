# Vue Instant!

[![npm](https://img.shields.io/npm/v/vue-instant.svg) ![npm](https://img.shields.io/npm/dm/vue-instant.svg)](https://www.npmjs.com/package/vue-instant)
[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsantiblanko%2Fvue-instant.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsantiblanko%2Fvue-instant?ref=badge_shield)

vue instant allows you to easily create custom search controls with auto suggestions for your vue 2 applications.

[![header](http://g.recordit.co/Yeg0Bl0nJO.gif)](https://santiblanko.github.io/vue-instant/)

## Table of contents

- [Examples](#examples)
- [Installation](#installation)

# Examples

Project page

https://santiblanko.github.io/vue-instant

Fiddle with all attributes and events

https://jsfiddle.net/santiblanko/dqo6vr57

If you need a example using webpack see the example folder.

# Installation

```
npm install --save vue-instant
```

## Default import
If you need more details see the examples folder.

Install all the components:

```javascript
import Vue from 'vue'
import 'vue-instant/dist/vue-instant.css'
import VueInstant from 'vue-instant'
Vue.use(VueInstant)
```
**⚠️ You need to configure your bundler to compile `.vue` files.** More info [in the official documentation](https://vuejs.org/v2/guide/single-file-components.html).

## Browser
If you need more details see the examples folder.

```html
<link rel="stylesheet" href="vue-instant/dist/vue-instant.css"/>

<script src="vue.js"></script>
<script src="vue-clickaway.js"></script>
<script src="vue-instant/dist/vue-instant.browser.js"></script>
```

## License

MIT © [Santiago Blanco](http://twitter.com/santiblanko)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsantiblanko%2Fvue-instant.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsantiblanko%2Fvue-instant?ref=badge_large)