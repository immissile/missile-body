
## install
```js
npm i --save missile-body
```

## usage
```js
var parse = require('missile-body');
app.post('/any', parse, function (req, res, next) { /* ... */ });
app.post('/json', parse.json, function (req, res, next) { /* ... */ });
app.post('/text', parse.text, function (req, res, next) { /* ... */ });
app.post('/form', parse.form, function (req, res, next) { /* ... */ });
```
