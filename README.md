![ES6 for Everyone](https://es6.io/images/es6-facebook-share.png?cool=yah)

# ES6 for Everyone Starter Files

Everything you need to Learn ES6 over at [ES6.io](https://ES6.io)

---

## LOGS

### Day 1: 12 May 2017
Got this course for free from [Wes Bos](https://github.com/wesbos) as an appreciation gift :heart:
Started looking at the overview of this course and setting up Slack.

**Thoughts:**
 - Completed Module #1 New Variables - Creation, Updating and Scoping
 - `var` is function scope
 - We can redeclare it multiple times in same scope
 - `let` & `const` are block scope
 - We can not redeclare it twice in same scope
 - You can update a `let` variable, but `const` variables cannot be updated
 - However, the properties of a `const` variable can change. That's because the entire object is not immutable.
 - Came to know about [Object.freeze()](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze), so that nothing can be added to or removed from the properties set of a frozen object.
 - Also, completed Module #2 Function Improvements: Arrows and Default Arguments
 - I had known about Arrow Functions from the #Javascript30 course, but more in details about it today
 - Learnt more about arrow functions, implicit returns, when & when not to use arrow functions, `this` inside arrow functions
 - Also, about default function arguments


### Day 2: 14 May 2017
Completed Module #3 - Template Strings

**Thoughts:** Learnt about:-
 - Template strings, creating html fragments with template literals
 - Using if, loop and functions inside template strings
 - Tagged templates, some use cases and sanitizing user data with tagged templates
 - Found about [DOMPurify](https://github.com/cure53/DOMPurify) which helps to sanitize data in DOM

### Day 3: 15 May 2017
Completed Module #4 - Additional String Improvements

**Thoughts:**
 - Learnt about `startsWith()`, `endsWith()`, includes() & repeat() methods and did some practice related to them
 - Also, looked into `str.endsWith(searchString[, length])` and `str.startsWith(searchString[, position])`

### Day 4: 16 May 2017
Completed Module #5 - Destructuring

**Thoughts:**
 - Learnt about destructuring objects, renaming variables and default values
 - Learnt about destructuring arrays, functions and swapping variables
 - Snippets 1: `const { first, last, twitter } = someObjectHere`
 - Snippets 2: `const [ first, last, twitter ] = someArrayHere`

### Day 5: 17 May 2017
Completed Module #6 - Completed Module #6 Iterables & Looping

**Thoughts:**
 - Learnt about some advantages of `for of` loop over `for`, `foreach` and `for in`
 - `for-of` makes is easier for looping through array elements and most array-like objects like DOM NodeList, arguments
 - Learnt about `Array.prototype.entries()` method and how we can use it with `for-of` loop
 - Snippets 1: `for (const cut of cuts)`, just to get the values
 - Snippets 2: `for (const [i, cut] of cuts.entries())`, used to both index and value

### Day 6: 18 May 2017
Completed Module #7 - An Array of Array Improvements

**Thoughts:**
 - Learnt about `Array.from()` & `Array.of()` method
 - Array prototype methods like `find`, `findIndex`, `some` & `every`
 - Use Case 1 for [`Array.from()`](https://pbs.twimg.com/media/DAHWQDGUwAAdOZV.jpg)
 - Use Case 2 for Array.prototype [`.some()` & `.every()`](https://pbs.twimg.com/media/DAHdt4YU0AAv31R.jpg)

### Day 7: 19 May 2017
Completed Module #8 - Say Hello to ...Spread and ...Rest

**Thoughts:**
 - Learnt about ...Spread operator & ...Rest parameters and there various use cases with lots of examples
 - Some use cases for [`Rest parameters`](https://pbs.twimg.com/media/DAMnqDdUwAYmYes.jpg)

### Day 8: 20 May 2017
Completed Module #9 - Object Literal Upgrades

**Thoughts:**
 - Learnt about some handy stuffs like property value shorthand, method definition shorthand and computed property keys

Completed Module #10 - Promises

**Thoughts:**
 - Learnt about how Promises works, creating my own promises, chaining them and working with multiple promises
 - As the Promise.prototype.then() and Promise.prototype.catch() methods return promises, they can be chained like
 - [Chaining promises](https://pbs.twimg.com/media/DAP3qFIVYAA2tPp.jpg)

### Day 9: 23 May 2017
Completed Module #11 - Symbols (Newest primitive data type)

**Thoughts:**
 - Learnt about Symbol data type and various use cases.
 - We can use it as object key as [unique identifier](https://pbs.twimg.com/media/DAhIFkYW0AAXLhD.jpg)


### Day 10: 24 May 2017
**Thoughts:**
 - Learnt about [ESLint](http://eslint.org/) and it's [usability](http://eslint.org/demo/)
 - Also, looked into the [Airbnb's settings](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb) and did some practice
 - Looked into various [ESLint rules](http://eslint.org/docs/rules/) and tried to understand their importance and when to use them.

### Day 11: 25 May 2017
**Thoughts:**
 - Today learnt about ESLint file & line specific settings for enabling/disabling rules
 - More info [here](http://eslint.org/docs/user-guide/configuring.html#disabling-rules-with-inline-comments)


### Day 12: 26 May 2017
**Thoughts:**
 - Completed Module #12 - Code Quality with ESLint
 - Today learnt about JavaScript modules and WebPack 2 tooling setup

### Day 13: 27 May 2017
**Thoughts:**
 - Learnt about creating our own JavaScript modules and importing/exporting them
 - Also, looked into [export statement](https://developer.mozilla.org/en/docs/web/javascript/reference/statements/export) and various syntax.


### Day 14: 28 May 2017
**Thoughts:**
 - Completed Module #13 - JavaScript Modules and Using npm
 - Did more practice on ES6 Modules
 - Learnt about how to import specific modules when its needed

### Day 15: 29 May 2017
**Thoughts:**
 - Completed Module #14 - ES6 Tooling
 - Learnt about SystemJS, Babel & [Polyfills](https://polyfill.io/v2/docs/) for ES6
 - Polyfills gives very good coverage for all ES6 features in old browsers

 - Completed Module #15 - Classes
 - Learnt about creating a new class (declaration-form), defining static methods & prototype methods, get & set methods
 - Also, learnt about extending an existing class, subclassing methods of a parent class and subclassing built-ins
 - Simple use case for Subclassing built-in classes and DOM [here](https://pbs.twimg.com/media/DBAfi7pUIAAupmH.jpg)

### Day 16: 30 May 2017
**Thoughts:**
 - Completed Module #16 - Generators
 - Learnt about Generators function, which returns a Generator object. Using it for ajax flow control (awesome stuff)
 - Simple use-case for [`Generators`](https://pbs.twimg.com/media/DBFCKe-VoAEiVxr.jpg)

### Day 17: 01 June 2017
**Thoughts:**
 - Learnt about ES6 Proxies and its various use cases.
 - It provide JavaScript with an intercession API, enabling us to trap or intercept all of the operations on a target object and modify how this target operates

### Day 18: 05 June 2017
**Thoughts:**
 - Completed Module #18 - Sets and WeakSets
 - The `Set` object lets us store unique values of any type, whether primitive values or object references.
 - The `WeakSet` object lets us store weakly held objects in a collection.
 - If there is no other reference to an object stored in the `WeakSet`, they can be garbage collected.
 - Also, `WeakSet` are not enumerable

### Day 19: 06 June 2017
**Thoughts:**
 - Completed Module #19 - Map and Weak Map
 - A `Map` object holds key-value pairs.
 - The `Map` object iterates its elements in insertion order - a `for...of` loop returns an array of `[key, value]` for each iteration.
 - The `WeakMap` object is a collection of key/value pairs in which the keys are weakly referenced.

### Day 20: 28 Sep 2017
**Thoughts:**
 - This course was updated recently.
 - Updated for ES7/ES2016 and ES8/ES2017 including Async+Await, Babel 7 and more!
 - Started looking into it from today.
 - Started with native promises and its use-cases.
 - Also looked into creating custom promises.

### Day 21: 29 Sep 2017
**Thoughts:**
 - Today I reviewed the Async+Await once more.
 - Also, looked into a generic way for error handling async functions.

### Day 22: 30 Sep 2017
**Thoughts:**
 - Today I looked into using multiple promises.
 - Looked into one more use case for [`Promise.all()`][promise-all]
 - Learned about how we can promisify functions so that we can use Async+Await on the them.

### Day 23: 02 Oct 2017
**Thoughts:**
 - Today I looked into some new & future language additions
 - Looked into Class properties
 - Also, looked into ES8 [`padStart`][string-padStart] and [`padEnd`][string-padEnd]
 - ES7 Exponentiation Operator
 - Trailing commas (sometimes called "final commas") in literals

### Day 24: 04 Oct 2017
**Thoughts:**
 - Today I looked into use cases of `Object.entries()` and `Object.values()`
 - Learned about how it can be used in specific scenarios.
 - Fnially finished the course :tada:

<!-- Links here -->
[promise-all]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all
[string-padStart]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart
[string-padEnd]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd
