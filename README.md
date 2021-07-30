## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## How to edit content

This template have a CMS support with CosmicJS. You can easily put your content there by creating and linking your CosmicJS account.

In order to customize your portfolio, you must create a CosmicJS account and a new fresh bucket on it. Once done, you must update credentials of the **.env** file.

To do this, you just have to modify the variables contained in the ENV file (API token, bucket slug and read key).

```env
# CosmicJS
VUE_APP_COSMICJS_TOKEN=" "
VUE_APP_COSMICJS_BUCKET_SLUG=" "
VUE_APP_COSMICJS_BUCKET_READ_KEY=" "
```
