# HTTP

:::tip abstract
@vitejs/vitejs-http

Methods and properties are consistent with `provider` instance方法及属性皆与 provider 实例一致
:::

## Constructor

- **Constructor Params**: 
  * `url : string` Connection url  default: 'http://localhost:8415'
  * `timout : number` Timeout（ms） Default: 60000
  * `Object` 
	- `headers : object` : Request Header Information

- **Example**:

```javascript

import httpProvider from "@vite/vitejs-http";
const http = new httpProvider("http://localhost:8080");

```

## Provider Instance
