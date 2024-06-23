# Unit 1, Day 6: Functions, Objects, and Advanced Types Lesson Plan

## Course Structure Guidelines

This course is delivered by an AI Language Model (LLM) with the following structure:

1. Each day's session lasts approximately 3-4 hours.
2. The LLM breaks down topics into small, manageable chunks.
3. For each chunk:
   a. The LLM presents the information.
   b. Comprehension-check questions are asked to ensure understanding.
   c. The LLM corrects any misunderstandings.
   d. Where relevant, short code submissions are requested from the user.
   e. The LLM provides guidance to improve the user's code.
4. Once per topic, there's a more extensive coding/implementation challenge (about 30 minutes long).
5. The LLM evaluates the user's solution to this challenge.

## Lesson Objectives
By the end of this session, students should be able to:
1. Define and use function types and signatures in TypeScript
2. Work with object types and optional properties
3. Understand and implement union and intersection types
4. Use literal types and type narrowing techniques
5. Begin to grasp advanced type concepts like mapped types

## Content Chunks

### Chunk 1: Function Types and Signatures (45 minutes)

#### Information to Present:
- Function type expressions
- Call signatures
- Construct signatures
- Generic functions

#### Comprehension Check Questions:
1. How do you define a function type in TypeScript?
2. What's the difference between a call signature and a construct signature?

#### Practical Task:
Guide the user through creating various function types, including a generic function, and implementing functions that match these types.

### Chunk 2: Object Types and Optional Properties (45 minutes)

#### Information to Present:
- Object type literals
- Optional properties
- Readonly properties
- Index signatures
- Extending object types

#### Comprehension Check Questions:
1. How do you define an object type with optional properties?
2. What's the purpose of an index signature in an object type?

#### Practical Task:
Ask the user to create a complex object type representing a product in an e-commerce system, including optional properties and an index signature for custom attributes.

### Chunk 3: Union and Intersection Types (45 minutes)

#### Information to Present:
- Union types and their use cases
- Intersection types and their use cases
- Type narrowing with union types
- Discriminated unions

#### Comprehension Check Questions:
1. When would you use a union type versus an intersection type?
2. How does type narrowing work with union types?

#### Practical Task:
Guide the user through creating a shape system using union and intersection types, including a function that uses type narrowing to calculate the area of different shapes.

### Chunk 4: Literal Types and Type Narrowing (45 minutes)

#### Information to Present:
- String, number, and boolean literal types
- Combining literal types with unions
- Type narrowing techniques (typeof guards, instanceof guards, in operator)
- User-defined type guards

#### Comprehension Check Questions:
1. How can literal types enhance type safety in your code?
2. What are different ways to perform type narrowing in TypeScript?

#### Practical Task:
Ask the user to implement a function that takes a union type and uses various type narrowing techniques to handle different cases.

### Chunk 5: Introduction to Advanced Type Concepts (30 minutes)

#### Information to Present:
- Brief overview of mapped types
- The keyof operator
- Conditional types (basic introduction)

#### Comprehension Check Questions:
1. What is a mapped type and when might you use one?
2. How does the keyof operator work in TypeScript?

#### Practical Task:
Guide the user through creating a simple mapped type, such as making all properties of an interface optional.

## Extended Coding Challenge (30 minutes)

Create a type-safe event system using TypeScript. The system should:

1. Define a set of event types using literal union types
2. Create an `EventData` type that maps event types to their corresponding payload types
3. Implement an `EventEmitter` class with methods to emit events and register event listeners
4. Use function types to ensure type safety for event callbacks
5. Implement type narrowing in the event handling logic

Evaluation Criteria:
- Correct use of union types, literal types, and function types
- Proper implementation of type narrowing
- Type-safe event emission and listening
- Code readability and organization
- Bonus: Implement a generic constraint to ensure only valid event types can be used

## Additional Resources
- TypeScript Handbook (Functions): https://www.typescriptlang.org/docs/handbook/2/functions.html
- TypeScript Handbook (Object Types): https://www.typescriptlang.org/docs/handbook/2/objects.html
- TypeScript Handbook (Narrowing): https://www.typescriptlang.org/docs/handbook/2/narrowing.html
- TypeScript Deep Dive (Union Types): https://basarat.gitbook.io/typescript/type-system/discriminated-unions

## Notes for LLM Instructor
- Emphasize how these advanced types can make code more robust and self-documenting.
- Use real-world scenarios to illustrate the practical applications of union types, intersection types, and type narrowing.
- Be prepared to explain type narrowing in detail, as it's a crucial concept for working with union types.
- When introducing mapped types and conditional types, focus on their basic usage and utility, as these topics will be covered more in-depth in future lessons.
- Encourage students to think about how these TypeScript features can help prevent bugs in their code.
- Remember to adapt your explanations based on the user's responses and provide additional examples if needed.
