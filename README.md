```bash

 inkscape -D -z --file=Amity-Logo-Solo.svg --export-pdf=Amity-Logo-Solo.pdf --export-latex    # export to PDF with LaTeX

```


# Git and GitHub Documentation

## Table of Contents
1. Introduction to Git
2. Basic Git Commands
3. Branching and Merging
4. GitHub
5. Collaboration with Git and GitHub
6. Advanced Git Concepts
7. Conclusion

## 1. Introduction to Git
Git is a distributed version control system that allows multiple users to collaborate on a project efficiently. It tracks changes to files and allows you to revert back to previous versions, merge changes from different users, and work offline.

## 2. Basic Git Commands
Here are some essential Git commands to get started:

- `git init`: Initializes a new Git repository in the current directory.
- `git clone <repository>`: Creates a copy of a remote repository on your local machine.
- `git add <file>`: Stages a file to be committed.
- `git commit -m "message"`: Commits the staged changes with a descriptive message.
- `git status`: Shows the status of files in the repository.
- `git log`: Displays the commit history.
- `git push`: Uploads local changes to a remote repository.
- `git pull`: Downloads and incorporates changes from a remote repository.

## 3. Branching and Merging
Branching allows you to create separate lines of development within a Git repository. Here are some commands related to branching and merging:

- `git branch`: Lists all branches in the repository.
- `git branch <branch-name>`: Creates a new branch.
- `git checkout <branch-name>`: Switches to a different branch.
- `git merge <branch-name>`: Merges changes from one branch to another.
- `git branch -d <branch-name>`: Deletes a branch.

## 4. GitHub
GitHub is a web-based platform that hosts Git repositories and provides additional collaboration features. It allows you to store and share your code with others. Here are some key features of GitHub:

- Repository hosting
- Issue tracking
- Pull requests
- Code review
- Collaboration tools
- Integrations with other services

## 5. Collaboration with Git and GitHub
Git and GitHub are widely used for collaborative development. Here are some common collaborative workflows:

- Forking: Create a personal copy of a repository to propose changes to the original project.
- Pull Requests: Propose changes to a repository by submitting a pull request.
- Code Reviews: Review code changes made by others to ensure quality and maintain standards.
- Branch Protection: Restrict direct changes to important branches and enforce code review.

## 6. Advanced Git Concepts
There are several advanced Git concepts that can enhance your workflow:

- Git Hooks: Custom scripts triggered by specific Git events.
- Rebasing: Moving or combining commits to maintain a clean commit history.
- Submodules: Including another Git repository within your repository.
- Git Workflows: Implementing branching strategies like GitFlow or GitHub Flow.
- Git LFS: Managing large files with Git Large File Storage.

## 7. Conclusion
Git and GitHub provide powerful tools for version control and collaboration. By understanding the basic and advanced concepts, you can effectively manage your codebase, work with others, and contribute to open-source projects.
