# JavaScript ES6 Promise Tasks

This repository contains a set of JavaScript tasks focused on ES6 Promise concepts. Below are the tasks and their descriptions.

## Task 0: Keep every promise you make and only make promises you can keep

```javascript
import getResponseFromAPI from "./0-promise.js";

const response = getResponseFromAPI();
console.log(response instanceof Promise);
