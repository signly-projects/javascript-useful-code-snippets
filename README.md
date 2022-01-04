# JavaScript - Useful Code Snippets 

### Assigning new variable name on destruction
```
const o = { p: 42, q: true };
const { p: foo, q: bar } = o;

console.log(foo); // 42
console.log(bar); // true
```
