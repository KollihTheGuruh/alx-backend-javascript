# ALX Backend JavaScript - ES6 Basics

This repository contains exercises for the ALX Backend JavaScript track, focusing on ES6 basic features.

## Tasks

### 0. Const or let?
**Description:** Modify the functions to use `const` and `let` instead of `var`.
```javascript
// 0-constants.js
export function taskFirst() {
  const task = 'I prefer const when I can.';
  return task;
}

export function taskNext() {
  let combination = 'But sometimes let';
  combination += getLast();
  return combination;
}
Usage

$ npm run dev 0-main.js
