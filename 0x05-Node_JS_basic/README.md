# Project Tasks

## Task 0: Executing basic javascript with Node JS

- File: `0-console.js`
- Function: `displayMessage`
- Description: Create a function named `displayMessage` that prints the string argument to STDOUT.

## Task 1: Using Process stdin

- File: `1-stdin.js`
- Description: Create a program named `1-stdin.js` that displays a message, prompts for user input (name), and outputs the name. It should also display a closing message when the program ends.

## Task 2: Reading a file synchronously with Node JS

- File: `2-read_file.js`
- Function: `countStudents`
- Description: Create a function named `countStudents` that reads the provided database file synchronously and logs the number of students in each field.

## Task 3: Reading a file asynchronously with Node JS

- File: `3-read_file_async.js`
- Function: `countStudents`
- Description: Create a function named `countStudents` that reads the provided database file asynchronously and returns a Promise.

## Task 4: Create a small HTTP server using Node's HTTP module

- File: `4-http.js`
- Description: Create a small HTTP server using Node's HTTP module that listens on port 1245 and displays "Hello Holberton School!" for any endpoint.

## Task 5: Create a more complex HTTP server using Node's HTTP module

- File: `5-http.js`
- Description: Create a more complex HTTP server using Node's HTTP module. It should display different messages based on the URL path and include student information.

## Task 6: Create a small HTTP server using Express

- File: `6-http_express.js`
- Description: Install Express and create a small HTTP server using Express module that displays "Hello Holberton School!" for the endpoint "/".

## Task 7: Create a more complex HTTP server using Express

- File: `7-http_express.js`
- Description: Create a more complex HTTP server using Express that displays different messages based on the URL path and includes student information.

## Task 8: Organize a complex HTTP server using Express

- Structure:
  - Directories: `controllers`, `routes`
  - Files: 
    - `full_server/utils.js`
    - `full_server/controllers/AppController.js`
    - `full_server/controllers/StudentsController.js`
    - `full_server/routes/index.js`
    - `full_server/server.js`
- Description: Organize a full server in a directory named `full_server` using Express and Babel. Create controllers, routes, and a server file as specified.
