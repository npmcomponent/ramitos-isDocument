*This repository is a mirror of the [component](http://component.io) module [ramitos/isdocument](http://github.com/ramitos/isdocument). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-isdocument`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# isDocument

## install

```bash
component install ramitos/isDocument
```

## api

```js
var isDocument = require('isDocument')

isDocument(document) // => true
isDocument(window) // => false
```