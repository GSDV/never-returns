# never-returns

✨ The function that never returns ✨


## How to use:
Install the package:
```npm install never-returns```

Import the function and run off into the sunset:
```
const neverReturn = require('never-returns');

const doNotComplete = () => {
    console.log("I will run!");
    neverReturn();
    console.log("But I will never be reached.");
}
```