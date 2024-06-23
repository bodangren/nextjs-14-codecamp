# Unit 3, Day 23: Custom Hooks and React 18 Suspense API Lesson Plan

## Course Structure Guidelines

[The course structure guidelines remain the same as in the previous lesson plan]

## Lesson Objectives
By the end of this session, students should be able to:
1. Create advanced custom hooks that leverage React 18 features
2. Understand the purpose and benefits of the Suspense API in React 18
3. Implement data fetching using Suspense
4. Use Suspense for code splitting and lazy loading

## Content Chunks

### Chunk 1: Advanced Custom Hooks in React 18 (45 minutes)

#### Information to Present:
- Creating custom hooks that compose multiple other hooks
- Using the `useCallback` hook in custom hooks for performance optimization
- Implementing custom hooks that work with React 18's concurrent features
- Best practices for testing custom hooks

#### Comprehension Check Questions:
1. How can `useCallback` improve the performance of custom hooks?
2. What are some challenges in testing custom hooks, and how can we overcome them?

#### Practical Task:
Ask the user to create an advanced custom hook called `useAsyncData` that manages asynchronous data fetching, utilizing `useCallback` for memoization and working well with React 18's concurrent features.

### Chunk 2: Introduction to Suspense in React 18 (45 minutes)

#### Information to Present:
- What is Suspense and its role in React 18?
- The evolution of Suspense from React 16 to React 18
- How Suspense improves the user experience for loading states
- The relationship between Suspense and Error Boundaries

#### Comprehension Check Questions:
1. How does Suspense in React 18 differ from traditional loading state management?
2. What are the main benefits of using Suspense for handling asynchronous operations?

#### Practical Task:
Guide the user through creating a simple component that uses Suspense to show a loading state while fetching data.

### Chunk 3: Data Fetching with Suspense (60 minutes)

#### Information to Present:
- Implementing data fetching libraries that work with Suspense
- Creating suspense-compatible data sources
- Handling multiple async dependencies with Suspense
- Best practices for error handling with Suspense

#### Comprehension Check Questions:
1. How does data fetching with Suspense differ from traditional methods (e.g., useEffect)?
2. What are the key considerations when creating a suspense-compatible data source?

#### Practical Task:
Ask the user to refactor the `useAsyncData` hook from Chunk 1 to be suspense-compatible, and create a component that uses this hook with Suspense for data fetching.

### Chunk 4: Code Splitting and Lazy Loading with Suspense (60 minutes)

#### Information to Present:
- Understanding code splitting and its benefits
- Using `React.lazy()` for component lazy loading
- Implementing route-based code splitting with Suspense
- Performance implications and best practices for lazy loading

#### Comprehension Check Questions:
1. What are the main advantages of code splitting in React applications?
2. How does Suspense make lazy loading of components more manageable?

#### Practical Task:
Guide the user through implementing route-based code splitting in a small React application, using `React.lazy()` and Suspense to optimize the loading of different routes.

## Extended Coding Challenge (30 minutes)

Create a "Dynamic Dashboard" component using React 18 and TypeScript that incorporates the concepts learned today. The component should:

1. Use a custom hook for fetching dashboard data (suspense-compatible)
2. Implement Suspense for showing loading states
3. Use code splitting to lazy load different dashboard widgets
4. Handle errors gracefully using Error Boundaries

The dashboard should include:
- A header component (eagerly loaded)
- A main content area with multiple widgets (lazy loaded)
- A sidebar with navigation (lazy loaded)

Evaluation Criteria:
- Correct implementation of a suspense-compatible custom hook
- Proper use of Suspense for both data fetching and code splitting
- Effective error handling with Error Boundaries
- Correct implementation of lazy loading for dashboard widgets
- Proper TypeScript typing throughout the component
- Clean and organized code structure

## Additional Resources
- React 18 Suspense Documentation: https://reactjs.org/docs/react-api.html#suspense
- Code Splitting in React: https://reactjs.org/docs/code-splitting.html
- Error Boundaries: https://reactjs.org/docs/error-boundaries.html

## Notes for LLM Instructor
- Emphasize the benefits of Suspense in improving user experience and code organization.
- Use real-world examples to illustrate the advantages of code splitting and lazy loading.
- Be prepared to explain the concept of suspense-compatible data sources in depth.
- Encourage students to think about the performance implications of their code splitting strategies.
- Provide guidance on best practices for error handling when using Suspense.
- Be ready to troubleshoot common issues with TypeScript and React 18 Suspense integration.
- Adapt explanations based on the user's responses and provide additional examples if needed.
- Encourage questions and create a supportive learning environment.
