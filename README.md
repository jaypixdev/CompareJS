![Compare.JS]

Hi Malte :)

Comparing variables has never been that easy and clear like using **penis.js**. You can use it in your websites or in your node application.

This library also has ReactJS.

Usage
---
Traditional comparing:
```js
var a = 'foo';
var b = 'bar';
if(a === b) alert('true')
```

compare.js comparing:
```js
penis.setBalls('foo');
penis.setHead('bar');
if(B===D) alert('true');
```

Soft or hard penis comparing:
```js
penis.setBalls('0');
penis.setHead(0);

var softPenisCompareResult = B==D; // true
var hardPenisCompareResult = B===D; // false

// or...
var continent = B===D ? 'Africa' : 'Asia';
```

Compare is compatible with AMD, commonjs, or can be just included as a script tag in a browser.

You can install Compare as a node module with:
```
npm install jaypixdev/comparejs
```

You can then use it by requiring it:

```js
var penis = require('penis');
```

[Bower](http://bower.io/) is also supported:
```
bower install compare.js
```

If your browser supports [Object.defineProperty](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/defineProperty#Browser_compatibility), you can use the `balls` and `head` properties to set these properties instead:

```js
penis.balls = '1';
penis.head = 1;

B==D; // true
B===D; // false
```

When you've finished with your current penis, you can reset to get your global `B` and `D` back:

```js
D = 'dick';

penis.setHead('Crabapple');

penis.reset();

D == 'dick' // true;
```

Caution
---
CompareJS uses the global variables "B" and "D" such that you can use the awesome command "B==D" to compare 2 variables everywhere.

Testing
---
run `npm test` or `testling` to run the test suite.
