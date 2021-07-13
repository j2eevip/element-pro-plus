# element-pro-plus (Beta)

> a component library for Vue 3 base on element-plus

[Documentation](https://j2eevip.github.io/element-pro-plus)

## Installation

```sh
yarn add element-pro-plus
# or
npm i element-pro-plus
```

## Usage

```js
import { createApp } from 'vue';
import App from './App.vue';
import ElementPro from 'element-pro-plus';
import 'element-pro-plus/lib/styles/index.css';

createApp(App).use(ElementPro).mount('#app');
```

```vue
<template>
  <pro-layout />
</template>
```

## Development project

nodejs ^12

start

```bash
yarn

yarn dev
```

then, preview on `http://localhost:3000/`

test build

```bash
yarn build
```

before push

```bash
yarn test
```

[commit-convention](https://github.com/vuejs/vue-next/blob/master/.github/commit-convention.md)

## License

[MIT](http://opensource.org/licenses/MIT)
