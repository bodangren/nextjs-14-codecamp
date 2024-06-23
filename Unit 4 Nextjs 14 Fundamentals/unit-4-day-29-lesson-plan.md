# Unit 4, Day 29: Introduction to Next.js 14 and Project Structure Lesson Plan

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the core concepts and benefits of Next.js 14
2. Set up a new Next.js 14 project with TypeScript
3. Comprehend the Next.js 14 file and folder structure, focusing on the App Router
4. Configure basic Next.js 14 settings using next.config.js and tsconfig.json

## Content Chunks

### Chunk 1: Introduction to Next.js 14 (45 minutes)

#### Information to Present:
- What is Next.js and its role in modern web development
- Key features and benefits of Next.js 14 (App Router, Server Components, etc.)
- How Next.js 14 enhances React applications
- Brief overview of Server-Side Rendering (SSR) and Static Site Generation (SSG)

#### Comprehension Check Questions:
1. What are the main advantages of using Next.js 14 over a standard React application?
2. How does Next.js 14 handle routing differently from previous versions?

#### Practical Task:
Ask the user to research and list three real-world applications built with Next.js and explain why Next.js was a good choice for each.

### Chunk 2: Setting Up a Next.js 14 Project (60 minutes)

#### Information to Present:
- Prerequisites for Next.js 14 development (Node.js, npm/yarn)
- Creating a new Next.js 14 project with TypeScript
- Understanding the initial project structure
- Running and debugging a Next.js 14 application

#### Comprehension Check Questions:
1. What command is used to create a new Next.js 14 project with TypeScript?
2. What are the key differences between a Next.js project with and without TypeScript?

#### Practical Task:
Guide the user through creating a new Next.js 14 project with TypeScript, running it locally, and making a simple modification to the home page.

### Chunk 3: Next.js 14 File and Folder Structure (45 minutes)

#### Information to Present:
- Detailed explanation of the App Router folder structure
- Role of key files: layout.js, page.js, loading.js, error.js
- Understanding route groups and how they affect the URL structure
- Organizing components, styles, and assets in a Next.js 14 project

#### Comprehension Check Questions:
1. How does the App Router determine the routing based on the folder structure?
2. What is the purpose of the layout.js file in the App Router structure?

#### Practical Task:
Ask the user to create a basic multi-page Next.js 14 application with a nested route structure, including custom layout and error pages.

### Chunk 4: Configuring Next.js 14 (30 minutes)

#### Information to Present:
- Introduction to next.config.js and its role
- Common configuration options in next.config.js
- Understanding and customizing tsconfig.json for Next.js 14 projects
- Best practices for configuration in Next.js 14

#### Comprehension Check Questions:
1. What are some common use cases for modifying next.config.js?
2. How does tsconfig.json in a Next.js 14 project differ from a standard TypeScript project?

#### Practical Task:
Guide the user through adding custom configuration to next.config.js, such as setting up environment variables and customizing the build output.

## Extended Coding Challenge (60 minutes)

Create a "Next.js 14 Portfolio Starter" project that demonstrates the basic structure and features of Next.js 14. The project should include:

1. A home page with a brief introduction
2. An "About" page with more detailed information
3. A "Projects" page with a list of sample projects
4. A dynamic route for individual project pages
5. Custom layouts for different sections of the site
6. Basic styling using CSS modules

The project should demonstrate:
- Proper use of the App Router structure
- Implementation of layouts and nested routes
- Use of TypeScript for component props and basic type safety
- Basic configuration using next.config.js
- Correct usage of page.js, layout.js, and other special files

Evaluation Criteria:
- Correct implementation of the App Router structure
- Proper use of TypeScript for components and pages
- Effective use of layouts and nested routes
- Basic configuration set up in next.config.js
- Clean, organized, and maintainable code structure
- Functional navigation between different pages and routes

## Additional Resources
- Next.js 14 Documentation: https://nextjs.org/docs
- Next.js 14 Learn Course: https://nextjs.org/learn
- TypeScript Documentation: https://www.typescriptlang.org/docs/
- React Documentation: https://reactjs.org/docs/getting-started.html

## Notes for LLM Instructor
- Emphasize the differences between Next.js 14 (with App Router) and previous versions or standard React applications
- Use real-world examples to illustrate the benefits of Next.js 14
- Be prepared to explain the concept of Server Components at a high level (detailed coverage will come in later lessons)
- Guide students through the transition from React concepts to Next.js-specific features
- Encourage students to explore the Next.js documentation for additional features and configurations
- Be ready to troubleshoot common setup issues (e.g., Node.js version compatibility)
- Adapt explanations based on the user's responses and provide additional examples if needed
- Remind students that this is just an introduction, and deeper dives into specific features will come in subsequent lessons

