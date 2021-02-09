# laravue-mailer-js

[Vue Web Component](https://cli.vuejs.org/guide/build-targets.html#web-component) for formatting email message based on CSV file content. Sample backend (Laravel package): [laravue-mailer](https://github.com/damms005/laravue-mailer)

## Usage

- Link the compiled js and css files in the `dist` folder to your html file, like below:

```
<script src='dist/assets/css/app.css'></script>
...
...
...
<script src='dist/assets/js/app.js'></script>
```

This will provide you with a Vue component named `laravue-mailer`
In your code, you can then drop this custom Vue component as `<laravue-mailer></laravue-mailer>`. This will give you a UI where you can:
- paste csv format (first row are placeholders) inside textarea
- type email template into a second textarea
- randomly show build email for any of the csv data
- click send

vue-cli-service build --target wc --name laravue-mailer src/App.vue --inline-vue

## Development

If you are interested in having a dev version of this project (e.g. for customization), `cd` to the project root and run the following commands:

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

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

## Todo

- Tree-shake unused TailwindCss styles
- Write tests

## Learning resources

- https://www.codementor.io/@martinaimar/web-components-with-vue-cli-3-t1bduun66
- https://cli.vuejs.org/guide/build-targets.html#web-component
- https://medium.com/mounoydev/vue-component-rich-text-editor-wysiwyg-59b57052d5b3
