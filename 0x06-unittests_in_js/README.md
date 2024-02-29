# Unittests in js

## Tasks

### 0. Basic test with Mocha and Node assertion library

- File: 0-calcul.js
- Task Question:
  - Install Mocha using npm.
  - Set up a script in your package.json to quickly run Mocha using npm test.
  - Use assert.
  - Create a function named calculateNumber. It should accept two arguments (number) a and b.
  - The function should round a and b and return the sum of it.
  - Create test cases for this function.

### 1. Combining descriptions

- File: 1-calcul.js
- Task Question:
  - Create a new file named 1-calcul.js.
  - Upgrade the function created in the previous task.
  - Add a new argument named type as the first argument of the function. type can be SUM, SUBTRACT, or DIVIDE (string).
  - Implement different behaviors based on the type argument (SUM, SUBTRACT, or DIVIDE).
  - Create test cases for this function.

### 2. Basic test using Chai assertion library

- File: 2-calcul_chai.js
- Task Question:
  - Copy the file 1-calcul.js to a new file 2-calcul_chai.js.
  - Copy the file 1-calcul.test.js to a new file 2-calcul_chai.test.js.
  - Rewrite the test suite using expect from Chai.
  - Ensure all tests pass without any warning.

### 3. Spies

- File: 3-payment.js, 3-payment.test.js
- Task Question:
  - Install Sinon with npm.
  - Create a new file named utils.js.
  - Create a new module named Utils and export it.
  - Create a new property named calculateNumber in Utils module.
  - Create a new function named sendPaymentRequestToApi in 3-payment.js.
  - Use sinon.spy to verify that the math used in sendPaymentRequestToApi is the same as Utils.calculateNumber.
  - Create test cases for this function.

### 4. Stubs

- File: 4-payment.js, 4-payment.test.js
- Task Question:
  - Copy the code from 3-payment.js to a new file 4-payment.js.
  - Copy the code from 3-payment.test.js to a new file 4-payment.test.js.
  - Stub the function Utils.calculateNumber to always return the same number (e.g., 10).
  - Verify that the stub is being called correctly.
  - Add a spy to verify that console.log is logging the correct message.
  
### 5. Hooks

- File: 5-payment.js, 5-payment.test.js
- Task Question:
  - Copy the code from 4-payment.js to a new file 5-payment.js.
  - Inside the same describe, create 2 tests:
    - The first test will call sendPaymentRequestToAPI with 100 and 20.
    - The second test will call sendPaymentRequestToAPI with 10 and 10.
  - Verify the behavior of the tests using only one spy.
  - Use beforeEach and afterEach hooks to complete this exercise.

### 6. Async tests with done

- File: 6-payment_token.js, 6-payment_token.test.js
- Task Question:
  - Create a new file named 6-payment_token.js.
  - Create a new function named getPaymentTokenFromAPI.
  - The function should return a resolved promise with the object {data: 'Successful response from the API'} when success is true.
  - Write test cases to test the result of getPaymentTokenFromAPI(true).
  - Use the done callback to execute this test.

### 7. Skip

- File: 7-skip.test.js
- Task Question:
  - Using the file 7-skip.test.js, make the test suite pass without fixing or removing the failing test.
  - Ensure every test passes without any warning.

### 8. Basic Integration testing

- File: 8-api/package.json, 8-api/api.js, 8-api/api.test.js
- Task Question:
  - Copy the provided package.json to a new folder 8-api.
  - Create a new file api.js with specified functionalities.
  - Write integration tests for the API endpoints defined in api.js.

### 9. Regex integration testing

- File: 9-api/api.js, 9-api/api.test.js, 9-api/package.json
- Task Question:
  - Modify the file api.js to add a new endpoint GET /cart/:id.
  - Add a regex in the path to support the use case.
  - Write test suites for the cart page with different scenarios.

### 10. Deep equality & Post integration testing

- File: 10-api/api.js, 10-api/api.test.js, 10-api/package.json
- Task Question:
  - Modify the file api.js to add two new endpoints: GET /available_payments and POST /login.
  - Write test suites for both endpoints, ensuring deep equality and correct behavior.
