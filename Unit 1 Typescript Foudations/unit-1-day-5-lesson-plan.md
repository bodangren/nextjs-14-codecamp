# Unit 1, Day 5: Interfaces, Type Aliases, and Type Inference Lesson Plan

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
1. Understand and create interfaces in TypeScript
2. Use type aliases for complex types
3. Leverage type inference in TypeScript effectively
4. Understand the differences between interfaces and type aliases
5. Apply interfaces and type aliases in practical scenarios

## Content Chunks

### Chunk 1: Introduction to Interfaces (45 minutes)

#### Information to Present:
- What are interfaces in TypeScript?
- Syntax for defining interfaces
- Optional and readonly properties
- Extending interfaces

#### Comprehension Check Questions:
1. How do interfaces help in structuring code?
2. What's the difference between optional and required properties in an interface?

#### Practical Task:
Guide the user through creating an interface for a `Person` object with both required and optional properties, and then implement a function that uses this interface.

### Chunk 2: Advanced Interface Concepts (45 minutes)

#### Information to Present:
- Function types in interfaces
- Indexable types
- Class types and implementing interfaces
- Interfaces extending classes

#### Comprehension Check Questions:
1. How can you define a function type within an interface?
2. What are indexable types and when might you use them?

#### Practical Task:
Ask the user to create an interface for a simple data structure (e.g., a basic key-value store) that includes both indexable types and a method definition.

### Chunk 3: Type Aliases (45 minutes)

#### Information to Present:
- What are type aliases?
- Syntax for creating type aliases
- Union and intersection types with aliases
- Differences between interfaces and type aliases

#### Comprehension Check Questions:
1. When would you use a type alias instead of an interface?
2. How do union and intersection types work with type aliases?

#### Practical Task:
Guide the user through creating type aliases for complex types, including a union type and an intersection type.

### Chunk 4: Type Inference in Depth (45 minutes)

#### Information to Present:
- How TypeScript infers types
- Type inference in variable declarations
- Type inference in functions
- Contextual typing

#### Comprehension Check Questions:
1. In what situations does TypeScript use type inference?
2. How does contextual typing work in TypeScript?

#### Practical Task:
Ask the user to write a series of variable declarations and functions without type annotations, then use TypeScript to infer the types. Discuss the results.

### Chunk 5: Practical Application of Interfaces and Type Aliases (30 minutes)

#### Information to Present:
- Real-world scenarios for using interfaces and type aliases
- Best practices for choosing between interfaces and type aliases
- Common patterns in TypeScript codebases

#### Comprehension Check Questions:
1. In a React component, how might you use interfaces to define prop types?
2. When working with APIs, how can interfaces and type aliases improve your code?

#### Practical Task:
Guide the user through refactoring a small JavaScript snippet into TypeScript, using interfaces and type aliases where appropriate.

## Extended Coding Challenge (30 minutes)

Create a simple task management system using TypeScript. The system should:

1. Use an interface to define a `Task` object with properties like id, title, description, status, and dueDate
2. Create a type alias for a union type representing task status (e.g., 'pending', 'in-progress', 'completed')
3. Implement a `TaskManager` interface with methods for adding, updating, and listing tasks
4. Create a class that implements the `TaskManager` interface
5. Use type inference where appropriate to reduce verbosity

Evaluation Criteria:
- Correct use of interfaces and type aliases
- Proper implementation of the `TaskManager` interface
- Effective use of type inference
- Code readability and organization
- Bonus: Include error handling for invalid inputs

## Additional Resources
- TypeScript Handbook (Interfaces): https://www.typescriptlang.org/docs/handbook/interfaces.html
- TypeScript Handbook (Type Inference): https://www.typescriptlang.org/docs/handbook/type-inference.html
- TypeScript Deep Dive (Interfaces): https://basarat.gitbook.io/typescript/type-system/interfaces

## Notes for LLM Instructor
- Emphasize the role of interfaces and type aliases in creating scalable and maintainable code.
- Use examples from popular libraries or frameworks to show real-world applications of these concepts.
- Be prepared to explain the nuances between interfaces and type aliases, as this is often a point of confusion.
- Encourage students to think about how these TypeScript features can improve their existing JavaScript code.
- When discussing type inference, highlight both its benefits and potential pitfalls.
- Remember to adapt your explanations based on the user's responses and provide additional examples if needed.
