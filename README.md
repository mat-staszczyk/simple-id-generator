# Id generator

> Simple id generator 

## Usage example

```js
const generator = require('coig-id-generator');

const idGen = generator();
console.log(idGen.next().value); // returns 0
console.log(idGen.next().value); // returns 1
console.log(idGen.next().value); // returns 2
```
