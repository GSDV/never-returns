# never-returns

✨ The function that never returns ✨


## How to use:
```
const neverReturn = require('never-returns');

const doNotComplete = () => {
    console.log("I will run!");
    neverReturn();
    console.log("But I will never be reached.");
}
```