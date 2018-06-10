# Introduction

`vuex-dry` is a library to help keep your vuex codes DRY.

# Install

```bash
npm i vuex-dry -D
```

Add the plugin to your vuex store.

```js
import { plugin } from "vuex-dry";

new Vuex.Store({
  plugins: [plugin],
  ...
});
```