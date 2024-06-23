# Unit 0, Day 2: Git and GitHub Basics Lesson Plan

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
1. Understand the concept of version control and its importance
2. Install and configure Git
3. Use basic Git commands for local version control
4. Create and manage repositories on GitHub
5. Understand the workflow between local Git and remote GitHub repositories

## Content Chunks

### Chunk 1: Introduction to Version Control and Git (30 minutes)

#### Information to Present:
- What is version control?
- Why is version control important in software development?
- Introduction to Git and its distributed nature

#### Comprehension Check Questions:
1. What are the main benefits of using version control in a project?
2. How does Git differ from centralized version control systems?

#### Practical Task:
Guide the user through installing Git on their system and configuring their username and email.

### Chunk 2: Basic Git Commands for Local Version Control (60 minutes)

#### Information to Present:
- Git repository initialization (`git init`)
- Staging changes (`git add`)
- Committing changes (`git commit`)
- Checking status and history (`git status`, `git log`)

#### Comprehension Check Questions:
1. What is the purpose of the staging area in Git?
2. What information should a good commit message contain?

#### Practical Task:
Ask the user to create a new directory, initialize a Git repository, create a file, stage it, and commit it with a meaningful commit message.

### Chunk 3: Branching and Merging in Git (45 minutes)

#### Information to Present:
- Concept of branches in Git
- Creating and switching branches (`git branch`, `git checkout`)
- Merging branches (`git merge`)
- Resolving merge conflicts

#### Comprehension Check Questions:
1. Why do developers use branches in their workflow?
2. What is a merge conflict and when does it occur?

#### Practical Task:
Guide the user through creating a new branch, making changes, and merging it back to the main branch.

### Chunk 4: Introduction to GitHub (45 minutes)

#### Information to Present:
- What is GitHub and how does it relate to Git?
- Creating a GitHub account
- Creating a repository on GitHub
- README files and .gitignore

#### Comprehension Check Questions:
1. How does GitHub extend the functionality of Git?
2. What is the purpose of a .gitignore file?

#### Practical Task:
Ask the user to create a GitHub account (if they don't have one) and create a new repository.

### Chunk 5: Connecting Local Git to GitHub (30 minutes)

#### Information to Present:
- Linking local repository to GitHub (`git remote add`)
- Pushing changes to GitHub (`git push`)
- Pulling changes from GitHub (`git pull`)
- Cloning repositories (`git clone`)

#### Comprehension Check Questions:
1. What is the difference between `git push` and `git pull`?
2. When would you use `git clone`?

#### Practical Task:
Guide the user through linking their local repository to the GitHub repository they created, and pushing their local commits to GitHub.

## Extended Coding Challenge (30 minutes)

Create a simple project (e.g., a "Hello, World!" program in a language of your choice), use Git to version control it locally, and then push it to a new GitHub repository. The challenge should include:

1. Creating a new directory and initializing a Git repository
2. Creating the project files and making multiple commits
3. Creating a .gitignore file to exclude unnecessary files
4. Creating a new repository on GitHub
5. Pushing the local repository to GitHub

Evaluation Criteria:
- Proper use of Git commands
- Meaningful commit messages
- Correct setup of remote repository
- Successful push to GitHub
- Proper use of .gitignore

## Additional Resources
- Git Documentation: https://git-scm.com/doc
- GitHub Guides: https://guides.github.com/
- Interactive Git Branching Tutorial: https://learngitbranching.js.org/

## Notes for LLM Instructor
- Use analogies to explain Git concepts. For example, commits can be likened to saving a game at different points.
- Emphasize the importance of meaningful commit messages for collaboration and future reference.
- Be prepared to troubleshoot common Git issues, such as merge conflicts or authentication problems with GitHub.
- Encourage users to explore GitHub's features, such as Issues and Pull Requests, if they finish tasks early.
- Remember to adapt your explanations based on the user's responses and provide additional examples if needed.
