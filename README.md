# Jest

Jest is a JavaScript Testing Framework with a focus on simplicity.

- [Jest](https://jestjs.io//)

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
- Snapshot Testing 
- Sandboxed
- Error reporting - tells you the exact line where error is at, gives a nice output
- Zero Config - Do not have to configure anything

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

```npm test```

---

## Examples




```
  test('object assignment', () => {
  const data = {one: 1};
  data['two'] = 2;
  expect(data).toEqual({one: 1, two: 2});
});
```

## Additional Resources
- [A quick introduction to test driven development with Jestl](https://medium.freecodecamp.org/a-quick-introduction-to-test-driven-development-with-jest-cac71cb94e50)

---
