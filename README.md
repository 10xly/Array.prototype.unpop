# Array.prototype.unpop
Annoyed by inconsistent Javascript nomenclature?

- removing an element from the head of an array? *shift*
- adding an element to the head of an array? *unshift*
- removing an element from the tail of an array? *pop*
- adding an element to the tail of an array? **unpop** - obviously!

This is a better version of [unpop](https://npmjs.com/unpop) with TS definitions.
## Installation
```
npm install array.prototype.unpop
```

## Examples
```javascript

require('array.prototype.unpop');
const myArray = [1, 2, 3];
myArray.unpop(4);
console.log(myArray); // [1, 2, 3, 4]
```