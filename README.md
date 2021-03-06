# Polystyling

[Polymer](https://www.polymer-project.org/1.0/) example of shared styles using CSS files.

Warning. This is a deprecated method, but currently polymer provides no alternative.

### Styling the Shadow DOM with a CSS file

Using a style module
```html
<dom-module id="shared-style">
  <link rel="import" type="css" href="stylesheet.css">
  <template>
  </template>
</dom-module>

<dom-module id="my-component">
  <template>
  	<style include="shared-style"></style>
  </template>
</dom-module>
```

Directly importing the CSS file
```html
<dom-module id="my-component">
  <link rel="import" type="css" href="stylesheet.css">
  <template>
  </template>
</dom-module>
```

### Requirements

[NPM](https://www.npmjs.com/)

[Bower](http://bower.io/)

### Development

Install dependencies
```bash
$ bower update
$ npm install
```

Run on local webserver
```bash
$ npm start
```