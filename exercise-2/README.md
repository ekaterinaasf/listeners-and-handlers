* [Challenge](./challenge.html)
* [Solution](./solution.html)

### 1

It seems there is an error in thirdHandler:

console.assert(event.target._ === 'third', 'third: target.className');

All class names have a form like "third-class", "second-class", "first-class", so only "third" is incorrect.

### 2
In thirdHandler:

console.assert(event.type === 'undefined', 'second: event.type');

Corrected output to print 'third' at place of 'second'. Not sure if it's made on purpose or not.