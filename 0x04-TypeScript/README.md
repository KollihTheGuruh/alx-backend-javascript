# 0x04-TypeScript

## Tasks

### 0. Lockboxes

You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and each box may contain keys to the other boxes.

Write a method that determines if all the boxes can be opened.

**Prototype:** `def canUnlockAll(boxes)`

- `boxes` is a list of lists
- A key with the same number as a box opens that box
- You can assume all keys will be positive integers
- There can be keys that do not have boxes
- The first box `boxes[0]` is unlocked
- Return `True` if all boxes can be opened, else return `False`

### 1. Creating an interface for a student

Copy the following configuration files into the task_0 directory: `package.json`, `.eslintrc.js`, `tsconfig.json`, `webpack.config.js`

Write your code in the `main.ts` file:

- Write an interface named `Student` that accepts the following elements: `firstName(string)`, `lastName(string)`, `age(number)`, and `location(string)`
- Create two students, and create an array named `studentsList` containing the two variables
- Using Vanilla Javascript, render a table and for each element in the array, append a new row to the table
- Each row should contain the first name of the student and the location
  ...

### 2. Let's build a Teacher interface

Create a directory `task_1` and copy these configuration files into this folder: `package.json`, `tsconfig.json`, `webpack.config.js`

- Write a `Teacher` interface:
  - `firstName(string)` and `lastName(string)` should only be modifiable when a `Teacher` is first initialized
  - `fullTimeEmployee(boolean)` this attribute should always be defined
  - `yearsOfExperience(number)` this attribute is optional
  - `location(string)` this attribute should always be defined
  - Add the possibility to add any attribute to the Object like `contract(boolean)` without specifying the name of the attribute
  ...

### 3. Extending the Teacher class

Write an interface named `Directors` that extends `Teacher`. It requires an attribute named `numberOfReports(number)`

- Example:

  ```javascript
  const director1: Directors = {
    firstName: 'John',
    lastName: 'Doe',
    location: 'London',
    fullTimeEmployee: true,
    numberOfReports: 17,
  };
  console.log(director1);
  // should print
  // Object
  // firstName: "John"
  // fullTimeEmployee: true
  // lastName: "Doe"
  // location: "London"
  // numberOfReports: 17
