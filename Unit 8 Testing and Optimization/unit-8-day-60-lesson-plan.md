# Unit 8, Day 60: Introduction to Unit Testing with Jest and React Testing Library

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the importance of unit testing in Next.js applications
2. Set up Jest and React Testing Library in a Next.js 14 project
3. Write basic unit tests for React components
4. Test custom hooks
5. Implement test coverage reporting

## Content Chunks

### Chunk 1: Introduction to Unit Testing in Next.js (30 minutes)

#### Information to Present:
- Definition and importance of unit testing
- Benefits of unit testing in React and Next.js applications
- Overview of Jest and React Testing Library
- Testing philosophy: Testing behavior, not implementation

#### Comprehension Check Questions:
1. Why is unit testing important in Next.js applications?
2. How does React Testing Library's approach differ from other testing libraries?

#### Practical Task:
Ask the user to list three benefits of unit testing in their own words and provide an example of how unit testing could prevent a bug in a Next.js application.

### Chunk 2: Setting Up Jest and React Testing Library (45 minutes)

#### Information to Present:
- Installing necessary dependencies (jest, @testing-library/react, @testing-library/jest-dom)
- Configuring Jest for Next.js (jest.config.js)
- Setting up test files and naming conventions
- Creating a custom render function for Next.js components

#### Comprehension Check Questions:
1. What additional configuration does Jest need for Next.js projects?
2. Why might we need a custom render function for testing Next.js components?

#### Practical Task:
Guide the user through setting up Jest and React Testing Library in their Next.js project from Unit 7. They should create a jest.config.js file and a custom render function in a test utils file.

### Chunk 3: Writing Basic Unit Tests for React Components (60 minutes)

#### Information to Present:
- Structure of a unit test (Arrange-Act-Assert)
- Using React Testing Library queries (getBy, queryBy, findBy)
- Testing component rendering and content
- Testing user interactions (clicks, input changes)
- Using jest-dom for enhanced assertions

#### Comprehension Check Questions:
1. What's the difference between getBy, queryBy, and findBy queries?
2. How can you test a button click in a React component?

#### Practical Task:
Ask the user to write unit tests for a simple React component from their Unit 7 project. The tests should cover rendering, content checking, and a user interaction (e.g., button click or input change).

### Chunk 4: Testing Custom Hooks (45 minutes)

#### Information to Present:
- Strategies for testing custom hooks
- Using @testing-library/react-hooks for hook testing
- Writing tests for hooks with side effects
- Testing hooks that use context

#### Comprehension Check Questions:
1. Why might testing custom hooks be challenging?
2. How can you test a hook that uses React context?

#### Practical Task:
Guide the user through writing tests for a custom hook from their Unit 7 project. If they don't have a suitable hook, ask them to create a simple custom hook (e.g., useCounter) and write tests for it.

### Chunk 5: Implementing Test Coverage Reporting (30 minutes)

#### Information to Present:
- Importance of test coverage
- Configuring Jest for coverage reporting
- Interpreting coverage reports
- Setting coverage thresholds

#### Comprehension Check Questions:
1. What does a test coverage report tell us?
2. Why might 100% test coverage not always be a good goal?

#### Practical Task:
Ask the user to configure Jest for test coverage reporting in their project. They should run the coverage report and interpret the results, identifying areas that might need more testing.

## Extended Coding Challenge (90 minutes)

Enhance the "Next.js Application with Dual Database Integration" from Unit 7 with comprehensive unit tests:

1. Write unit tests for at least three React components in the application
2. Create tests for any custom hooks used in the application
3. Implement tests for utility functions, especially those related to data manipulation
4. Write tests for any context providers used in the application
5. Achieve at least 80% test coverage for the components and hooks tested
6. Use mocking to test components that interact with the databases (Firestore or Cloud SQL)

The project should demonstrate:
- Proper use of Jest and React Testing Library
- A variety of query methods and assertions
- Tests for different aspects: rendering, user interactions, state changes
- Proper test organization and descriptive test names
- Use of mocking for external dependencies
- Implementation of test coverage reporting

Evaluation Criteria:
- Correct setup and configuration of Jest and React Testing Library
- Comprehensive test cases covering various aspects of components and hooks
- Proper use of React Testing Library queries and jest-dom assertions
- Effective use of mocking for database interactions
- Clear and descriptive test organization
- Achievement of at least 80% test coverage for tested parts
- Tests that focus on component behavior rather than implementation details
- Proper handling of asynchronous operations in tests
- Clean, efficient, and well-organized test code
- Appropriate use of TypeScript in test files

## Additional Resources
- Jest Documentation: https://jestjs.io/docs/getting-started
- React Testing Library: https://testing-library.com/docs/react-testing-library/intro/
- Testing Next.js: https://nextjs.org/docs/testing
- Kent C. Dodds' "Common Mistakes with React Testing Library": https://kentcdodds.com/blog/common-mistakes-with-react-testing-library

## Notes for LLM Instructor
- Emphasize the importance of writing meaningful tests that enhance confidence in the code
- Encourage thinking about edge cases and potential bugs when writing tests
- Provide real-world examples of how unit tests can catch and prevent bugs
- Be prepared to explain concepts like mocking and asynchronous testing in simple terms
- Adapt explanations based on the user's grasp of testing concepts
- Highlight best practices in test writing, such as arranging tests in a "Arrange-Act-Assert" pattern
- Discuss how to balance testing thoroughness with development speed
- Be ready to provide guidance on testing more complex scenarios, like components with context or routing
- Relate the day's lessons to best practices in professional React and Next.js development
- Encourage the user to start thinking about how these tests will fit into a larger testing strategy, including integration and end-to-end tests

