# dotmm
dotmm is a lightweight memory prototype designed to help people use global variables quickly.<br/>
You can use our node package `dotmm` to create your own dotmm file. View a example below this.

```js
const { variables } = require('dotmm')();
console.log(variables.myVariable); // "This is a example dotmm variable"
```
```
myVariable="This is a example dotmm variable"
```

> dotmm can accept values as strings, numbers, arrays, objects and booleans.

## How to setup

**Requires Node version 14 or greater.**<br/>
As you can see, dotmm is a easy-to-setup node package.
Install dotmm by the NPM command: ``npm install dotmm`` or install an old version: ``npm install dotmm@1.0.0``.<br/>

## License

This project (dotmm) and this repository is licensed under [**Apache License 2.0**](https://github.com/dotmm/dotmm/blob/main/LICENSE).
