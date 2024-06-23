# Unit 1, Day 4: Introduction to TypeScript and Basic Types Lesson Plan

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
1. Understand what TypeScript is and its benefits
2. Use basic TypeScript types (number, string, boolean, array)
3. Understand and use type annotations
4. Work with tuple and enum types
5. Use the 'any' and 'unknown' types appropriately

## Content Chunks

### Chunk 1: Introduction to TypeScript (30 minutes)

#### Information to Present:
- What is TypeScript?
- Benefits of using TypeScript (type safety, better tooling, enhanced productivity)
- TypeScript's relationship with JavaScript
- TypeScript compilation process

#### Comprehension Check Questions:
1. How does TypeScript differ from JavaScript?
2. What are the main benefits of using TypeScript in a project?

#### Practical Task:
Guide the user through setting up a simple TypeScript project and compiling a basic "Hello, World!" program.

### Chunk 2: Basic Types - Number, String, and Boolean (45 minutes)

#### Information to Present:
- Number type in TypeScript
- String type and template literals
- Boolean type
- Type annotations and type inference

#### Comprehension Check Questions:
1. How does type inference work in TypeScript?
2. When would you explicitly use type annotations?

#### Practical Task:
Ask the user to create variables of each type (number, string, boolean) using both type inference and explicit type annotations.

### Chunk 3: Arrays and Tuples (45 minutes)

#### Information to Present:
- Array types in TypeScript
- Typed arrays
- Tuple types and their use cases
- Difference between arrays and tuples

#### Comprehension Check Questions:
1. How do you define an array of numbers in TypeScript?
2. What is the key difference between an array and a tuple in TypeScript?

#### Practical Task:
Guide the user through creating and manipulating both arrays and tuples in TypeScript.

### Chunk 4: Enum Type (30 minutes)

#### Information to Present:
- What are enums and their use cases
- Numeric enums
- String enums
- Const enums and their benefits

#### Comprehension Check Questions:
1. When would you use an enum in your TypeScript code?
2. What's the difference between numeric and string enums?

#### Practical Task:
Ask the user to create both a numeric and a string enum, and use them in a simple function.

### Chunk 5: Any and Unknown Types (30 minutes)

#### Information to Present:
- The 'any' type and its implications
- The 'unknown' type and type safety
- Best practices for using 'any' and 'unknown'

#### Comprehension Check Questions:
1. What are the potential drawbacks of using the 'any' type?
2. How does the 'unknown' type differ from 'any'?

#### Practical Task:
Guide the user through scenarios where 'any' and 'unknown' might be used, emphasizing type safety.

## Extended Coding Challenge (30 minutes)

Create a simple inventory management system using TypeScript. The system should:

1. Use an enum for product categories
2. Have an array of product objects, each with a name (string), price (number), and category (enum)
3. Include a tuple to represent a product's stock information [quantity, lastRestockDate]
4. Implement a function that calculates the total value of the inventory
5. Use type annotations throughout the code

Evaluation Criteria:
- Correct use of TypeScript types (enum, array, tuple, basic types)
- Proper type annotations
- Functional implementation of the inventory system
- Code readability and organization

## Additional Resources
- TypeScript Handbook (Basic Types): https://www.typescriptlang.org/docs/handbook/basic-types.html
- TypeScript Playground: https://www.typescriptlang.org/play
- TypeScript Deep Dive (TypeScript's Type System): https://basarat.gitbook.io/typescript/type-system

## Notes for LLM Instructor
- Emphasize the benefits of TypeScript in catching errors early and improving code quality.
- Use real-world examples to illustrate the practical applications of each type.
- Encourage students to experiment with the TypeScript Playground to see immediate results.
- Be prepared to explain the concept of type inference in detail, as it's a key feature of TypeScript.
- Highlight the importance of choosing the right type for the right situation, especially when discussing 'any' and 'unknown'.
- Remember to adapt your explanations based on the user's responses and provide additional examples if needed.
