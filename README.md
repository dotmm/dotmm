# dotmm
dotmm is a lightweight memory prototype designed to help people use global variables quickly.<br/>
You can use our node package `dotmm` to create your own dotmm file. View a example below this.

```js
const { variables } = require('dotmm')();
variables.myVariable;
if(variables.anotherVariable) console.log("anotherVariable is true");
```
```
myVariable="This is a example dotmm variable"
anotherVariable=true
```

> dotmm can accept values as strings, numbers, arrays, objects and booleans.

## How to setup

**Requires Node version 14 or greater.**<br/>
As you can see, dotmm is a easy-to-setup node package. To begin, you will need to install dotmm in your project.<br/>
``npm install dotmm`` or install an old version: ``npm install dotmm@1.0.0``.<br/>
After you need to create a `.mm` file to create variables. You can see a dotmm file example at the start of this README.<br/><br/>

And now, use this JavaScript code below to start your journey.
```js
const { variables } = require('dotmm')();
```

## License

This project (dotmm) and this repository is licensed under [**Apache License 2.0**](https://github.com/dotmm/dotmm/blob/main/LICENSE).
