## 0x06 - Unit Tests in JavaScript

## Project Overview
This project focuses on writing unit tests for JavaScript applications, using popular tools such as Mocha, Chai, and Sinon. By the end of this project, you'll understand how to create comprehensive test suites, handle edge cases, and perform both unit and integration testing using modern JS testing frameworks.

## Learning Objectives
- Understand how to use Mocha to write test suites.
- Learn to use different assertion libraries like Node's built-in assert and Chai.
- Master the use of spies and stubs with Sinon.
- Use hooks in test suites for pre-test and post-test functions.
- Perform async testing and understand how to handle Promises in tests.
- Learn integration testing with a basic NodeJS server.

## Technologies
- JavaScript (ES6)
- NodeJS
- Mocha
- Chai
- Sinon
- ExpressJS

## Task Breakdown

## Task 0: Basic Test with Mocha and Node Assertion Library
- Files: 0-calcul.js, 0-calcul.test.js
- Objective: Create a function calculateNumber that rounds two numbers and returns their sum. Write test cases using the assert library.

## Task 1: Test with Multiple Operations
- Files: 1-calcul.js, 1-calcul.test.js
- Objective: Extend the calculateNumber function to handle SUM, SUBTRACT, and DIVIDE operations. Test edge cases like division by zero.

## Task 2: Use Chai for Testing
- Files: 2-calcul_chai.js, 2-calcul_chai.test.js
- Objective: Rewrite the test cases from Task 1 using the Chai assertion library for better readability.

## Task 3: Spies with Sinon
- Files: utils.js, 3-payment.js, 3-payment.test.js
- Objective: Use Sinon Spies to track how functions are called during the test execution. Implement a test for the sendPaymentRequestToApi function.

##Task 4: Stubs
- Files: 4-payment.js, 4-payment.test.js
- Objective: Use Sinon Stubs to simulate API calls or expensive functions for more controlled and faster tests.

## Task 5: Hooks
- Files: 5-payment.js, 5-payment.test.js
- Objective: Use beforeEach and afterEach hooks to prepare and clean up the environment before and after tests.

## Task 6: Async Tests with Done
- Files: 6-payment_token.js, 6-payment_token.test.js
- Objective: Write a test suite for async functions, using the done callback to handle asynchronous testing.

## Task 7: Skipping Tests
- Files: 7-skip.test.js
- Objective: Skip failing or incomplete tests without commenting them out or removing them.

## Task 8: Basic Integration Testing
- Files: 8-api/api.js, 8-api/api.test.js
- Objective: Write integration tests for a simple ExpressJS API. Test the / route for correct responses.

## Task 9: Regex Integration Testing
- Files: 9-api/api.js, 9-api/api.test.js
- Objective: Add validation using regex in routes and write tests for the /cart/:id endpoint.

## Task 10: Deep Equality & Post Integration Testing
- Files: 10-api/api.js, 10-api/api.test.js
- Objective: Add a new POST /login endpoint and ensure tests verify deep equality in API responses.

## How to Run the Tests
## You can run all the tests using the following command:
 npm test
## To run a specific test suite, use:
 npm test <test-file>.test.js

