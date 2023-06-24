# Vue 3 MockBook

Vue 3 wrapper for CSS only mockup of a macbook for displaying screenshots on your website.

## Getting started

Install via NPM:

```sh
npm i @freeotoole/vue-mockbook
```

Import the package and styles to use in your Vue 3 project:

```js
import { VueMockbook } from 'vue-mockbook'
import '@onthetools/vue-mockbook/dist/style.css'
```

Then to use the component pass a required screenshot prop and optional url to display in the address bar

```js
<VueMockbook screen-shot="path-to/screenshot.png" url="optionalurl.com" />
```

![alt text](/dist/mockbook.png)
