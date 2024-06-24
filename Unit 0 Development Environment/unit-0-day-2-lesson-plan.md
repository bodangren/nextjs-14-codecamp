# Unit 0, Day 2: Git and GitHub Basics for Personal Blog Application

## Lesson Objectives
By the end of this session, students should be able to:
1. Understand the concept of version control and its importance in blog development
2. Use basic Git commands for local version control of the blog project
3. Create and manage a GitHub repository for the Personal Blog Application
4. Implement a workflow between local Git and remote GitHub repositories for the blog project

## Content Chunks

### Chunk 1: Introduction to Version Control and Git (30 minutes)

#### Information to Present:
- What is version control and why is it crucial for blog development?
- Introduction to Git and its benefits for managing blog content and code
- How Git can facilitate collaboration and track changes in the blog project

#### Comprehension Check Questions:
1. How can version control benefit the development of our Personal Blog Application?
2. Why is Git particularly suitable for managing a blog project?

#### Practical Task:
Guide the student through installing Git and configuring their username and email.

### Chunk 2: Basic Git Commands for Local Blog Version Control (60 minutes)

#### Information to Present:
- Initializing the blog project as a Git repository (`git init`)
- Staging changes to blog files (`git add`)
- Committing blog updates (`git commit`)
- Checking status and history of blog changes (`git status`, `git log`)

#### Comprehension Check Questions:
1. Why is it important to stage changes before committing in our blog project?
2. What information should be included in a commit message for a blog post update?

#### Practical Task:
Ask the student to initialize the Personal Blog Application as a Git repository, create a new blog post file, stage it, and commit it with a meaningful commit message.

### Chunk 3: Branching and Merging in the Blog Project (45 minutes)

#### Information to Present:
- Using branches for different blog features or post drafts
- Creating and switching branches (`git branch`, `git checkout`)
- Merging completed blog features (`git merge`)
- Resolving conflicts in blog content

#### Comprehension Check Questions:
1. How can branches be useful in managing different aspects of our blog (e.g., content, design, features)?
2. What might cause a merge conflict in our blog project and how can we resolve it?

#### Practical Task:
Guide the student through creating a new branch for a blog feature (e.g., "add-comment-section"), making changes, and merging it back to the main branch.

### Chunk 4: Introduction to GitHub for Blog Hosting (45 minutes)

#### Information to Present:
- GitHub as a platform for hosting and showcasing the blog project
- Creating a GitHub repository for the Personal Blog Application
- Importance of README files for project documentation
- Using .gitignore for excluding sensitive blog data or build files

#### Comprehension Check Questions:
1. How can GitHub enhance the development and presentation of our blog project?
2. What content should be included in the README file for our Personal Blog Application?

#### Practical Task:
Ask the student to create a GitHub repository for their Personal Blog Application and initialize it with a README file.

### Chunk 5: Connecting Local Blog to GitHub (30 minutes)

#### Information to Present:
- Linking the local blog repository to GitHub (`git remote add`)
- Pushing blog updates to GitHub (`git push`)
- Pulling changes from GitHub for collaboration (`git pull`)
- Cloning the blog repository on different machines (`git clone`)

#### Comprehension Check Questions:
1. Why is it important to regularly push our blog changes to GitHub?
2. In what scenarios would we need to use `git pull` in our blog project?

#### Practical Task:
Guide the student through linking their local blog repository to the GitHub repository, and pushing their local commits to GitHub.

## Extended Coding Challenge (30 minutes)

Enhance the Personal Blog Application with version control and GitHub integration:

1. Ensure the entire blog project is properly tracked by Git
2. Create a .gitignore file to exclude unnecessary files (e.g., node_modules, .next)
3. Develop a new blog feature in a separate branch (e.g., "add-about-page")
4. Merge the new feature into the main branch
5. Update the README with project setup instructions and feature list
6. Push all changes to the GitHub repository

Evaluation Criteria:
- Proper use of Git commands throughout the workflow
- Meaningful commit messages that reflect blog development stages
- Correct setup and use of branches
- Comprehensive .gitignore file appropriate for a Next.js project
- Clear and informative README file
- Successful push of the entire project to GitHub

## Additional Resources
- Git Documentation: https://git-scm.com/doc
- GitHub Guides: https://guides.github.com/
- Next.js Deployment Documentation: https://nextjs.org/docs/deployment

## Notes for LLM Instructor
- Use blog-specific analogies to explain Git concepts. For example, commits can be likened to saving drafts of a blog post.
- Emphasize the importance of meaningful commit messages for tracking the blog's development history.
- Discuss how Git and GitHub can be used for blog post version control and collaboration with other writers or developers.
- Encourage students to think about how they might use branches for different blog features or content categories.
- Be prepared to explain how version control can help in managing long-term projects like a blog.
- Adapt explanations based on the student's familiarity with blogging and provide additional examples if needed.
