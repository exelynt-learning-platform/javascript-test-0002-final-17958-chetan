# javascript-test-0002-final-17958-chetan
Final Project Assignment - This repository contains the complete final project code and documentation.

```js
let n = 5;

for (let i = n; i >= 1; i--) {

    // print starting spaces
    for (let s = 0; s < n - i; s++) {
        process.stdout.write(" ");
    }

    let num = 1;

    for (let j = 0; j < i; j++) {
        process.stdout.write(num + " ");
        num = num * (i - j - 1) / (j + 1);
    }

    console.log();
}
```
