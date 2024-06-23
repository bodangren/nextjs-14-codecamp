# Unit 0, Day 3: Node.js, npm, and Project Initialization Lesson Plan

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
1. Understand what Node.js is and its role in web development
2. Install Node.js and npm
3. Understand the purpose and structure of package.json
4. Use basic npm commands
5. Initialize a Next.js project with TypeScript support

## Content Chunks

### Chunk 1: Introduction to Node.js (30 minutes)

#### Information to Present:
- What is Node.js?
- The role of Node.js in web development
- Node.js architecture (event-driven, non-blocking I/O)

#### Comprehension Check Questions:
1. How does Node.js differ from traditional server-side languages?
2. What are some advantages of using Node.js for web development?

#### Practical Task:
Guide the user through installing Node.js and verifying the installation by checking the version in the terminal.

### Chunk 2: Introduction to npm (Node Package Manager) (45 minutes)

#### Information to Present:
- What is npm and why is it important?
- Understanding package.json
- Basic npm commands (init, install, uninstall, update)
- Global vs local package installation

#### Comprehension Check Questions:
1. What is the purpose of the package.json file?
2. When would you use global package installation versus local?

#### Practical Task:
Ask the user to create a new directory, initialize a new npm project, and install a simple package (e.g., lodash) both globally and locally.

### Chunk 3: Managing Dependencies with npm (45 minutes)

#### Information to Present:
- Understanding dependencies vs devDependencies
- Semantic versioning in npm
- The purpose of package-lock.json
- Using scripts in package.json

#### Comprehension Check Questions:
1. What's the difference between dependencies and devDependencies?
2. How does semantic versioning work in npm?

#### Practical Task:
Guide the user through adding both a regular dependency and a devDependency to their project, and creating a custom npm script.

### Chunk 4: Introduction to Next.js (45 minutes)

#### Information to Present:
- What is Next.js and its benefits
- Next.js features (SSR, SSG, API routes)
- Next.js vs Create React App
- TypeScript integration in Next.js

#### Comprehension Check Questions:
1. What are the main benefits of using Next.js for React applications?
2. How does Next.js handle routing differently from traditional React apps?

#### Practical Task:
Ask the user to research and list three key features of Next.js that they find interesting.

### Chunk 5: Initializing a Next.js Project with TypeScript (45 minutes)

#### Information to Present:
- Using create-next-app
- Configuring TypeScript in a Next.js project
- Next.js project structure
- Running a Next.js development server

#### Comprehension Check Questions:
1. What command is used to create a new Next.js project?
2. How does TypeScript integration benefit a Next.js project?

#### Practical Task:
Guide the user through creating a new Next.js project with TypeScript support using create-next-app.

## Extended Coding Challenge (30 minutes)

Create a simple Next.js application with TypeScript that includes:

1. A home page with a welcome message
2. A custom 404 page
3. An API route that returns a JSON response
4. A new npm script in package.json to run the development server

Evaluation Criteria:
- Correct use of Next.js file-based routing
- Proper TypeScript usage (types for props, API response)
- Functional API route
- Correct configuration in package.json
- Ability to run the development server successfully

## Additional Resources
- Node.js Documentation: https://nodejs.org/en/docs/
- npm Documentation: https://docs.npmjs.com/
- Next.js Documentation: https://nextjs.org/docs
- TypeScript Documentation: https://www.typescriptlang.org/docs/

## Notes for LLM Instructor
- Emphasize the importance of understanding Node.js and npm as foundational technologies for modern web development.
- Encourage students to read documentation and explore npm packages on their own.
- Be prepared to troubleshoot common issues with Node.js installation or npm package conflicts.
- Highlight the benefits of TypeScript in catching errors early and improving code quality.
- If students finish tasks early, encourage them to explore additional Next.js features or experiment with their project structure.
- Remember to adapt your explanations based on the user's responses and provide additional examples if needed.
