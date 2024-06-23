# Unit 5, Day 41: CSS Modules in Next.js 14 Lesson Plan

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the concept and benefits of CSS Modules
2. Set up and configure CSS Modules in a Next.js 14 project
3. Implement component-scoped styles using CSS Modules
4. Manage global styles alongside CSS Modules in Next.js 14
5. Apply best practices for organizing and naming CSS Modules

## Content Chunks

### Chunk 1: Introduction to CSS Modules (45 minutes)

#### Information to Present:
- What are CSS Modules and why they are useful
- How CSS Modules solve common styling problems (e.g., global scope issues, naming conflicts)
- Comparison of CSS Modules to other styling approaches (global CSS, inline styles, CSS-in-JS)
- How CSS Modules work in Next.js 14

#### Comprehension Check Questions:
1. What are the main benefits of using CSS Modules over traditional global CSS?
2. How do CSS Modules help prevent naming conflicts in large applications?

#### Practical Task:
Guide the user through creating a new Next.js 14 project and examining the default CSS setup.

### Chunk 2: Setting Up CSS Modules in Next.js 14 (45 minutes)

#### Information to Present:
- File naming conventions for CSS Modules (e.g., `Component.module.css`)
- Configuring Next.js 14 to use CSS Modules (usually pre-configured)
- Basic syntax and usage of CSS Modules
- Importing and using CSS Modules in React components

#### Comprehension Check Questions:
1. What file extension is used for CSS Modules in Next.js 14?
2. How do you import and use a CSS Module in a React component?

#### Practical Task:
Ask the user to create a simple React component with a corresponding CSS Module, and apply some basic styles.

### Chunk 3: Advanced CSS Modules Techniques (60 minutes)

#### Information to Present:
- Using composition in CSS Modules
- Working with global selectors within CSS Modules
- Handling dynamic classnames with CSS Modules
- CSS Modules and TypeScript integration

#### Comprehension Check Questions:
1. How can you compose styles from multiple CSS Modules?
2. What is the purpose of the `:global` selector in CSS Modules?

#### Practical Task:
Guide the user through refactoring a component to use more advanced CSS Modules techniques, including composition and dynamic classnames.

### Chunk 4: Managing Global Styles with CSS Modules (30 minutes)

#### Information to Present:
- Strategies for managing global styles alongside CSS Modules
- Using the `globals.css` file in Next.js 14
- Best practices for organizing global styles and CSS Modules

#### Comprehension Check Questions:
1. How can you include global styles in a Next.js 14 project using CSS Modules?
2. What types of styles are typically kept in global stylesheets versus CSS Modules?

#### Practical Task:
Ask the user to set up a global stylesheet for their Next.js 14 project and apply some global styles alongside their CSS Modules.

## Extended Coding Challenge (90 minutes)

Create a "Next.js 14 Blog Layout with CSS Modules" that demonstrates comprehensive use of CSS Modules for styling. The project should include:

1. A main layout component with header, footer, and content area
2. A blog post list component with individual post previews
3. A single blog post component with styled content
4. A sidebar component with author info and recent posts
5. Proper use of CSS Modules for all component-specific styles
6. A global stylesheet for base styles and variables

The project should demonstrate:
- Effective use of CSS Modules for component-scoped styling
- Composition of styles using CSS Modules
- Integration of global styles with CSS Modules
- Responsive design using CSS Modules
- TypeScript integration with CSS Modules

Evaluation Criteria:
- Correct implementation of CSS Modules for all components
- Effective scoping of styles to prevent global namespace pollution
- Proper use of composition and dynamic classnames where appropriate
- Integration of global styles for consistent theming
- Clean, efficient, and well-organized code structure
- Correct usage of TypeScript with CSS Modules

## Additional Resources
- Next.js 14 CSS Support: https://nextjs.org/docs/app/building-your-application/styling/css-modules
- CSS Modules GitHub: https://github.com/css-modules/css-modules
- CSS Tricks - CSS Modules 101: https://css-tricks.com/css-modules-part-1-need/

## Notes for LLM Instructor
- Emphasize the benefits of CSS Modules in large-scale applications
- Provide real-world examples of how CSS Modules solve common styling issues
- Encourage students to think about the organization of their styles from the beginning
- Be prepared to discuss the trade-offs between CSS Modules and other styling approaches
- Highlight the seamless integration of CSS Modules with Next.js 14 and TypeScript
- Adapt explanations based on the user's responses and provide additional examples if needed
- Reinforce the importance of maintaining a balance between component-scoped and global styles
- Discuss best practices for naming conventions and file organization when using CSS Modules

