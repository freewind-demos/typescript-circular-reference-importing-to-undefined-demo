TypeScript Circular Reference Importing to Undefined Demo
==========================================================

`a.ts`与`b.ts`互相引用，在同时import它们两个的时候，总会出错：
1. 要么有一个值是underfined
2. 要么报toUpper为undefined

所以我们要避免循环引用

```
npm install
npm run demo
```

Note:

`esModuleInterop` is recommended to set to `true`,
since we can have consistent importing syntax with babel,
always use:

```
import some from 'some'
```

