# alx-backend-javascript - JavaScript Backend Development Exercises

Welcome to the **alx-backend-javascript** repository! This repository contains a series of JavaScript exercises and tasks related to backend development. Below are the tasks for this repository:

## Task 0: Keep Every Promise
Return a Promise using the prototype function `getResponseFromAPI()`.

0-promise.js

## Task 1: Don't Make a Promise If You Can't Keep It
Return a promise based on the `getFullResponseFromAPI(success)` prototype. Resolve or reject the promise based on a boolean argument.

1-promise.js

## Task 2: Catch Me If You Can!
Append handlers to the `handleResponseFromAPI(promise)` function to handle resolved and rejected promises.

2-then.js

## Task 3: Handle Multiple Successful Promises
Import functions from `utils.js` and use the `handleProfileSignup()` prototype to collectively resolve promises and log results.

3-all.js

## Task 4: Simple Promise
Create a resolved promise using the `signUpUser(firstName, lastName)` prototype.

4-user-promise.js

## Task 5: Reject the Promises
Write a function named `uploadPhoto(filename)` that returns a rejecting promise.

5-photo-reject.js

## Task 6: Handle Multiple Promises
Import functions from previous tasks and create a function `handleProfileSignup(firstName, lastName, fileName)` that returns an array of promise statuses and values.

6-final-user.js

## Task 7: Load Balancer
Write a function `loadBalancer(chinaDownload, USDownload)` that returns the value of the first resolved promise.

7-load_balancer.js

## Task 8: Throw Error / Try Catch
Create a function `divideFunction(numerator, denominator)` that handles division by zero using error handling.

8-try.js

## Task 9: Throw an Error
Write a function `guardrail(mathFunction)` that captures return values and errors from a given function.

9-try.js

Feel free to explore and complete these tasks to enhance your JavaScript skills for backend development.

## Task 100: Asynchronous Function - Upload User Data

Import `uploadPhoto` and `createUser` from `utils.js`.

Write an asynchronous function named `asyncUploadUser` that calls these two functions and returns an object with the following format:
