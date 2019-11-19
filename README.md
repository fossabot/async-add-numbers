## async-add-numbers

### Usage

Installation: `npm i --save async-add-numbers`

```javascript
const addNumbers = require('async-add-numbers')

addNumbers(1, 2)
  .then(answer => console.log(answer)); // 3

addNumbers(-1, -2)
  .then(answer => console.log(answer)); // -3
  
addNumbers("a", -1)
  .then(answer => console.log(answer))
  .catch(error => console.error(error)); // Either 'a' or 'b' is not a number
```
