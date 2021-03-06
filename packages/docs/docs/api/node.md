# Node.js API

```js
const vuepress = require('vuepress')
```

## Global Methods

### vuepress.dev

Start a development server.

### vuepress.build

Build dir as a static site.

### vuepress.eject

Copy the default theme into `.vuepress/theme` for customization.

### vuepress.createApp

Create a VuePress App for for customization. For example,

```js
const app = vuepress.createApp(/* options */)
app.process().then(() => {
  console.log('ready!')
  app.dev()
})
```

## App Options

### options.sourceDir

Specify the source directory for VuePress.

### options.theme

See [theme](../config/README.md#theme).

### options.plugins

See [plugins](../config/README.md#plugins).

### options.temp

See [temp](../config/README.md#temp).

### options.dest

See [dest](../config/README.md#dest).

### options.siteConfig

See [siteConfig](../config/README.md).
