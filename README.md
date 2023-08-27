# TODO

This repository contains 4 functional test cases for the React TODO app using [Playwright](https://playwright.dev/)  in TypeScript.

## Project Setup

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.

## Running Tests

1. Execute all tests with: `npm test`
2. Run Specific Test Files: 
npm test -- --test="tdp.test.ts"         //create to-do test
npm test -- --test="editTodo.test.ts"    //edit to-do test
npm test -- --test="complete.test.ts"    //complete to-do
npm test -- --test="delete.test.ts"      //delete to-do

3.You can also run tests in parallel to speed up the execution by using the '--workers' flag:
npm test -- --workers=2 

3. By default, tests run in headless mode. To run tests in headful mode (with a browser window), set the PLAYWRIGHT_HEADLESS environment variable to false: PLAYWRIGHT_HEADLESS=false npm test


4. After running the tests, Playwright Test generates test reports that include logs and screenshots for each test run. You can find the reports in the ./test-results directory.

## Contributing

Feel free to contribute by adding more test cases or improving existing ones.

## License

This project is licensed under the [MIT License](LICENSE).
