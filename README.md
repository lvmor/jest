# Jest

[Jest](https://jestjs.io//) is a JavaScript testing framework designed to ensure correctness of any JavaScript codebase. It allows you to write tests with an approachable, familiar and feature-rich API that gives you results quickly.


---

## It works with the following technologies:
- [Babel](https://babeljs.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Node](https://nodejs.org/en/)
- [React](https://reactjs.org/)
- [Angular](https://angular.io/)
- [Vue](https://vuejs.org/)
- and more
---

## Test Driven Development (TDD)

1. Writing a test for a small part of a functionality and checking that this new test is failing (Red step)
2. Writing the code that makes the test pass, then checking that your previous test and the new one are successful (Green step)
3. Refactoring the code to make sure it is clear, understandable, and behaves well with the previous functionalities

https://medium.freecodecamp.org/a-quick-introduction-to-test-driven-development-with-jest-cac71cb94e50


## Why use Jest?

- Super Fast - allows all your failed tests to run first
- Snapshot Testing -compares expectation to stored snapshot
- Sandboxed
- Error reporting - tells you the exact line where error is at, gives a nice output
- Zero Config - Do not have to configure anything for JS implentation

---

## Initial Setup

Installing Jest dev dependency

with npm:

```npm i --save-dev jest```

or 

with yarn:

```yarn add --dev jest```

---

## Running Tests

```npm run test```

---

## Examples
Function test:
```
// sum.js
function sum(a, b) {
    return a + b;
}

module.exports = sum;
```

```
// sum.test.js
const sum = require('./sum');

test('adds 1 + 2 to equal 3', () => {
  expect(sum(1, 2)).toBe(3);
});
```


Expected value test:
```
  test('object assignment', () => {
  const data = {one: 1};
  data['two'] = 2;
  expect(data).toEqual({one: 1, two: 2});
});
```

## Additional Resources
- [A quick introduction to test driven development with Jest](https://medium.freecodecamp.org/a-quick-introduction-to-test-driven-development-with-jest-cac71cb94e50)
- [Jest Crash Course](https://www.youtube.com/watch?v=7r4xVDI2vho)
- [Snapshot Testing](https://jest-bot.github.io/jest/docs/snapshot-testing.html)


---
