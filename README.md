# TypeScript Assignment: Understanding Type Aliases, Interfaces, Callback Functions, and Objects

## Introduction

TypeScript is a statically typed superset of JavaScript that adds optional types to the language. It helps in catching errors early through a type system. This assignment will guide you through understanding and implementing some fundamental concepts in TypeScript such as type aliases, interfaces, callback functions, and objects.

### Objective

By the end of this assignment, you should be able to:

1. Define and use type aliases in TypeScript.
2. Create and implement interfaces in TypeScript.
3. Understand and write callback functions in TypeScript.
4. Work with objects in TypeScript, including defining and using custom types.

### Additional Task: Difference Between Type Alias and Interface

Before diving into the practical tasks, it's important to understand the theoretical differences between type aliases and interfaces in TypeScript.

#### Type Alias

A type alias allows you to create a new name for a type. It's similar to creating an alias or nickname for a person; it doesn't change who they are but provides a different way to refer to them. In TypeScript, type aliases can represent primitive types, union types, intersection types, tuples, and any other valid TypeScript types.

Example:
typescript type StringOrNumber = string | number;

In this example, `StringOrNumber` is a type alias representing either a string or a number.

#### Interface

An interface in TypeScript is used to define the shape of an object. It specifies what properties and methods an object should have. Unlike type aliases, interfaces are primarily used for object-oriented programming patterns, such as classes and objects that adhere to specific contracts.

Example:

typescript interface Person { name: string; age: number; }

Here, `Person` is an interface that describes an object with a `name` property of type string and an `age` property of type number.

### Practical Tasks

#### Part 1: Type Aliases

**Task:** Create a type alias named `StringOrNumber` that can accept either a string or a number.

typescript // Your solution here


#### Part 2: Interfaces

**Task:** Define an interface named `Person` with properties `name` (string) and `age` (number). Then, create an object `john` that implements this interface.


typescript // Your solution here


#### Part 3: Callback Functions

**Task:** Write a function named `processData` that takes two parameters: an array of data (`data`) and a callback function (`callback`). The `callback` function should take one parameter and return nothing. Inside `processData`, call the `callback` function with the first element of the `data` array.


typescript // Your solution here


#### Part 4: Working with Objects

**Task:** Define a custom type named `Address` with properties `street`, `city`, and `zip`. Then, create an object `myAddress` of type `Address`.


### Submission Instructions

1. Complete each part of the assignment in your TypeScript environment.
2. Save your code in a file named `assignment.ts`.
3. Compile your TypeScript code into JavaScript using the TypeScript compiler (`tsc assignment.ts`).
4. Submit both the compiled JavaScript file (`assignment.js`) and your original TypeScript source file (`assignment.ts`) as your submission.

### Grading Criteria

- **Correctness:** Does the code correctly implement the required functionality?
- **Readability:** Is the code easy to read and understand?
- **Completion:** Have all parts of the assignment been completed?

Good luck
