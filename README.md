## A starter template for Node.js + TypeScript

First run `npm install` then:

  

Run `npm start` to compile and run index.ts.

  

Run `npm test` to recursively compile and run tests in `test` folder.

  

- Current issue: if test files import from `src` those files will be compiled to .js and won't be deleted.


####  <u>TODO</u>
- [ ]  Remove .js files generated in `src` when running `npm test` 
-  [X] Add test command to run .ts tests in `test` recursively
- This is [not trivial](https://github.com/nodejs/help/issues/3902#issuecomment-1307124174)
- Done using shell script