# node-source-code
在node中require了一个js文件之后做了那些事呢
```node
node-source-code
  - index.js
  - module1.js
```
module1.js
```js
module.exports.content = 'hello hardy'
```
index.js
```js
const module1 = require('./module1')
console.log(module1.content)  // hello hardy
```
why ？？？

let's see the code~