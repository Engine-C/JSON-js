JSON_Parse添加对单引号的支持，虽然不符合规范，但挺有用的.


support single quotes around.


```js
  const arr = json_parse("['123',123]")
  // arr: ['123',123]
```
