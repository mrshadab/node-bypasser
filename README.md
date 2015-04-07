# node-bypasser
Bypass URL shortener websites

## Example:

```javascript
var Bypasser = require('./node-bypasser/bypasser.js');

var w = new Bypasser('http://adf.ly/1DX0XD');
w.decrypt(function(err, result) {
	console.log('Decrypted: ' + result);
});
```

The output will be 
```
Decrypted: https://github.com/matteocontrini/node-bypasser/
```

## Supported websites
* Adf.ly
* Linkbucks.com (main domain) (5 seconds required)
* Shorte.st (sh.st) (5 seconds required)
* AdFoc.us

## Coming soon
```
// TODO bit.ly
// TODO goo.gl
```