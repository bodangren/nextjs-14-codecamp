# Unit 8, Day 62: Integration Testing for React Components and Next.js Pages

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the difference between unit and integration testing
2. Set up an environment for integration testing in Next.js
3. Write integration tests for complex component interactions
4. Test Next.js pages, including those with dynamic routes
5. Implement tests for Next.js API routes
6. Use mock service worker (MSW) for mocking API requests in integration tests

## Content Chunks

### Chunk 1: Introduction to Integration Testing (30 minutes)

#### Information to Present:
- Definition and importance of integration testing
- Differences between unit and integration tests
- Benefits of integration testing in React and Next.js applications
- Overview of tools for integration testing (Jest, React Testing Library, MSW)

#### Comprehension Check Questions:
1. How does integration testing differ from unit testing?
2. Why is integration testing important in a Next.js application?

#### Practical Task:
Ask the user to identify three scenarios in their Unit 7 project that would benefit from integration testing rather than unit testing. Have them explain their reasoning for each scenario.

### Chunk 2: Setting Up Integration Testing Environment (45 minutes)

#### Information to Present:
- Configuring Jest for integration testing
- Setting up mock service worker (MSW) for API mocking
- Creating test utilities for integration tests
- Strategies for managing test data and state

#### Comprehension Check Questions:
1. Why might we use mock service worker (MSW) in our integration tests?
2. How does the setup for integration tests differ from unit tests?

#### Practical Task:
Guide the user through setting up MSW in their Next.js project. Have them create a basic handler for one of their API routes.

### Chunk 3: Testing Complex Component Interactions (60 minutes)

#### Information to Present:
- Strategies for testing components that interact with each other
- Testing state changes across multiple components
- Simulating user flows that span multiple components
- Dealing with components that have side effects

#### Comprehension Check Questions:
1. How would you test a user flow that involves multiple components?
2. What challenges might you face when testing components with side effects?

#### Practical Task:
Ask the user to identify a user flow in their application that spans multiple components (e.g., a multi-step form or a data entry process). Have them write an integration test for this flow.

### Chunk 4: Testing Next.js Pages and Dynamic Routes (45 minutes)

#### Information to Present:
- Approaches to testing Next.js pages
- Testing pages with dynamic routes
- Mocking Next.js routing in tests
- Testing pages with getServerSideProps or getStaticProps

#### Comprehension Check Questions:
1. How does testing a Next.js page differ from testing a regular React component?
2. What considerations do you need to keep in mind when testing pages with dynamic routes?

#### Practical Task:
Guide the user in writing an integration test for a Next.js page from their Unit 7 project. If they have a page with a dynamic route, have them write a test for that page.

### Chunk 5: Testing Next.js API Routes (60 minutes)

#### Information to Present:
- Strategies for testing API routes
- Using supertest for API route testing
- Mocking database calls in API route tests
- Testing error handling in API routes

#### Comprehension Check Questions:
1. Why might testing API routes be important in a Next.js application?
2. How can you test error handling in an API route?

#### Practical Task:
Ask the user to write integration tests for one of their API routes. The tests should cover successful responses, error handling, and any middleware used in the route.

## Extended Coding Challenge (90 minutes)

Enhance the "Next.js Application with Dual Database Integration" from Unit 7 with comprehensive integration tests:

1. Implement integration tests for a complex user flow that spans multiple components (e.g., user registration, task creation and assignment)
2. Write tests for at least two Next.js pages, including one with a dynamic route
3. Implement tests for at least two API routes, covering both success and error scenarios
4. Use mock service worker (MSW) to mock API requests in your integration tests
5. Test a feature that involves both Firestore and Cloud SQL interactions
6. Implement a test for a page that uses getServerSideProps or getStaticProps
7. Ensure your integration tests cover key user journeys in your application

The project should demonstrate:
- Proper setup of an integration testing environment
- Effective use of Jest and React Testing Library for integration testing
- Correct implementation of MSW for API mocking
- Comprehensive testing of complex user flows
- Proper testing of Next.js pages and API routes
- Handling of asynchronous operations in integration tests

Evaluation Criteria:
- Correct setup and configuration of integration testing environment
- Comprehensive test cases covering key user journeys
- Proper use of MSW for API mocking
- Effective testing of Next.js pages, including those with dynamic routes
- Comprehensive tests for API routes, including error scenarios
- Tests that accurately simulate user interactions across multiple components
- Proper handling of asynchronous operations in tests
- Clear and descriptive test organization
- Tests that provide valuable confidence in application functionality
- Clean, efficient, and well-organized test code

## Additional Resources
- Next.js Testing Documentation: https://nextjs.org/docs/testing
- Mock Service Worker Documentation: https://mswjs.io/docs/
- Testing Next.js API routes: https://www.mikealche.com/software-development/how-to-test-next-js-api-routes-with-jest-and-supertest
- Integration Testing Best Practices: https://kentcdodds.com/blog/write-tests
- Simulating User Interactions with React Testing Library: https://testing-library.com/docs/user-event/intro

## Notes for LLM Instructor
- Emphasize the importance of integration testing in catching bugs that unit tests might miss
- Encourage thinking about real user journeys when designing integration tests
- Provide real-world examples of how integration tests can improve application reliability
- Be prepared to explain the differences between unit and integration tests in practical terms
- Adapt explanations based on the user's grasp of testing concepts
- Highlight best practices in integration test writing, such as keeping tests focused and avoiding brittleness
- Discuss how to balance integration testing with other forms of testing (unit, e2e)
- Be ready to provide guidance on testing more complex scenarios, like authenticated routes or real-time updates
- Relate the day's lessons to best practices in professional Next.js development
- Encourage the user to think critically about what to test at the integration level vs. unit or e2e level

