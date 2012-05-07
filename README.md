# IcedCoffeeScript (JS) wrapper for SocketStream 0.3

Allows you to use [IcedCoffeeScript](http://maxtaco.github.com/coffee-script/) files (.coffee) in your SocketStream project.


### Instructions

Add `ss-icedcoffee` to your application's `package.json` file and then add this line to app.js:

```javascript
ss.client.formatters.add(require('ss-icedcoffee'));
```
