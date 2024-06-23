# Unit 1, Day 8: Introduction to Generics and Utility Types Lesson Plan

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
1. Understand the concept and purpose of generics in TypeScript
2. Implement generic functions and classes
3. Work with generic constraints
4. Understand and use built-in utility types
5. Create custom utility types

## Content Chunks

### Chunk 1: Introduction to Generics (45 minutes)

#### Information to Present:
- What are generics and why are they useful?
- Syntax for generic functions and classes
- Type inference in generics
- Multiple type parameters

#### Comprehension Check Questions:
1. How do generics improve code reusability?
2. What's the difference between using `any` and using generics?

#### Practical Task:
Guide the user through creating a generic function that works with arrays of any type, such as finding the first element of an array.

### Chunk 2: Generic Constraints (45 minutes)

#### Information to Present:
- Using `extends` keyword for constraints
- Constraining types to have specific properties
- Using type parameters in generic constraints
- The `keyof` constraint

#### Comprehension Check Questions:
1. Why would you want to constrain generic types?
2. How does the `keyof` constraint work with generics?

#### Practical Task:
Ask the user to implement a generic function that accepts objects with a specific property, using constraints to ensure type safety.

### Chunk 3: Generic Classes and Interfaces (45 minutes)

#### Information to Present:
- Creating generic classes
- Generic interfaces
- Using generic types with React components (brief introduction)
- Generic type aliases

#### Comprehension Check Questions:
1. How do generic classes differ from generic functions?
2. In what scenarios would you use a generic interface?

#### Practical Task:
Guide the user through creating a generic data structure, such as a simple key-value store or a minimal state management class.

### Chunk 4: Introduction to Utility Types (45 minutes)

#### Information to Present:
- Overview of built-in utility types
- Partial<T> and Required<T>
- Pick<T, K> and Omit<T, K>
- Record<K, T>

#### Comprehension Check Questions:
1. What problem do utility types solve in TypeScript?
2. How does `Partial<T>` differ from `Required<T>`?

#### Practical Task:
Ask the user to refactor a complex interface using utility types to create derived types for different use cases.

### Chunk 5: Creating Custom Utility Types (30 minutes)

#### Information to Present:
- Combining generics and mapped types to create utility types
- Real-world scenarios for custom utility types
- Best practices for creating and using utility types

#### Comprehension Check Questions:
1. When would you need to create a custom utility type?
2. How do generics and mapped types work together in utility types?

#### Practical Task:
Guide the user through creating a custom utility type, such as a `DeepPartial<T>` that makes all nested properties optional.

## Extended Coding Challenge (30 minutes)

Create a type-safe, generic data management system. The system should:

1. Implement a generic `DataStore<T>` class that can store and retrieve items of type T
2. Include methods for adding, removing, and updating items
3. Implement a `find` method that accepts a predicate function
4. Use utility types to create a `ReadonlyDataStore<T>` variant
5. Create a custom utility type `FilteredKeys<T, U>` that extracts keys from T whose values extend U

Evaluation Criteria:
- Correct use of generics and generic constraints
- Proper implementation of utility types
- Type-safe methods and operations
- Effective use of custom utility types
- Code readability and organization
- Bonus: Implement a simple observer pattern to notify of changes to the data store

## Additional Resources
- TypeScript Handbook (Generics): https://www.typescriptlang.org/docs/handbook/2/generics.html
- TypeScript Handbook (Utility Types): https://www.typescriptlang.org/docs/handbook/utility-types.html
- TypeScript Deep Dive (Generics): https://basarat.gitbook.io/typescript/type-system/generics

## Notes for LLM Instructor
- Emphasize how generics provide type safety while maintaining flexibility.
- Use analogies to explain generics, such as "type variables" or "type parameters".
- Be prepared to explain the difference between generics and `any` multiple times.
- When discussing utility types, relate them back to real-world TypeScript and React development scenarios.
- Encourage students to experiment with the TypeScript Playground to see how generics and utility types work.
- Be ready to provide additional examples of generic constraints and their use cases.
- Remember to tie these concepts back to previous lessons on advanced types where applicable.
- Adapt your explanations based on the user's responses and provide additional examples if needed.
