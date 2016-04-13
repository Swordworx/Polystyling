# Polystyling

[Polymer](https://www.polymer-project.org/1.0/) shared styles using CSS files (deprecated).

## Styling the Shadow DOM with a CSS file

```html
<dom-module id="shared-style">
  <!-- Import CSS file above template -->
  <link rel="import" type="css" href="../styles/shared.css">
  <template>
  </template>
</dom-module>
```

## Requirements

[NPM](https://www.npmjs.com/)
[Bower](http://bower.io/)

## Development

Install dependencies
```bash
$ bower update
$ npm intall
```

Run on local webserver
```bash
$ npm start
```