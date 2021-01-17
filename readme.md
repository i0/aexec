
# Introduction
Async EXEC (aexec) is the promised-based version of the exec function in Node.js. It executes shell commands, returns the output, and you can await for the output.


# Install

```bash
npm install aexec
```

# Usage

```js
import aexec from "aexec";

console.log(await aexec("ls"));
/* Output:
index.js
package.json
readme.md
*/
```
