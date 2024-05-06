# Git - GitHub and Open Source practice

The best way to learn something is to practice. For better practice, you need a safe space where it is okay to make mistakes. Let's use this space as a safe environment to practice Git and GitHub following the Open Source process without fear of making mistakes. We will work collaboratively in the GitHub CodeSpace environment, and we will share what we learn in the comments. 

Feel free to share this material with anyone learning how to code, but please don't try to commercialize the content.

### Objectives
- 📣 Learn what Git and GitHub are and the difference between them. 
- Practice how I can follow a flow and work with strangers in a collaborative tool. a.k.a Open Source
- Practice how I can help with an issue, send a request, and work with others on GitHub
- Understand what happens with my local when I'm working collaboratively. 

### Setup Needed

 - For this workshop, we are working in the code environment that GitHub offers in the browser. They are called [CodeSpaces](https://github.com/features/codespaces)
 - If you prefer to watch a video on how to work with CodeSpaces, you can follow this link. You will need a GitHub account to follow this tutorial. (Video in Spanish | Video in English)

# What is Git and GitHub
Git is a distributed version control system that allows developers to track and manage changes to code. It enables multiple versions of a project to be maintained simultaneously, making it easier to experiment and collaborate without risking the main codebase. 

GitHub, on the other hand, is a cloud-based hosting service that uses Git. It provides a web-based graphical interface and collaboration features such as bug tracking, feature requests, task management, and wikis for projects. While 

You can explaind the difference between them as Git helps manage the history of code changes locally on your computer, GitHub allows teams to collaborate on projects from anywhere by hosting their Git repositories online and adding extra tools for team collaboration. 

Together, Git and GitHub facilitate coding projects by handling version control and enhancing teamwork and communication.

# First Practice 
### Connect your CodeSpace to solve an issue. 
Here's a step-by-step guide a student can follow to connect their CodeSpace to solve an issue:

**Step 1: Understand the Issue**
Review the issue details in the project's issue tracker. Make sure you understand what needs to be solved and why it's important. That could also mean asking for clarifications if the issue is not clear or checking if there are any related issues or previous attempts to solve the same problem.

**Step 2: Connect Your CodeSpace**
* Access CodeSpaces: Log in to your GitHub account and navigate to the repository where the issue is reported.
* Open CodeSpaces: Click on the 'CodeSpaces' tab in the repository. If a CodeSpace doesn’t already exist, create a new one by selecting "New CodeSpace".
* Configure CodeSpace: Ensure that your CodeSpace has the necessary development tools and dependencies installed. This might include software libraries, development servers, or database systems relevant to the project.

**Step 3: Create a New Branch**

* Branch from the Main Line: Inside your CodeSpace terminal, check out a new branch from the main development branch (commonly main or master). Use a descriptive branch name related to the issue, for example, `git checkout -b first-error`.

**Step 4: Reproduce the Issue**
* Run the application or script within your CodeSpace to see the issue firsthand. Understanding how it manifests in the application will help you in debugging.
* Ensure that you can see the problem as described in the issue tracker.
* Note: Open source use a high level definition of an Issue. Right now this practice doesn't have a 'real-life' bug, but we're simulating a colaboration. 

**Step 5: Solve the Issue**
* Develop a Fix: Modify the code to address the issue. This might involve fixing a bug, adding new functionality, or improving existing features.
* Test Locally: Run the application within CodeSpace to test your changes. Make sure your fix resolves the issue without introducing new problems.

**Step 6: Commit Changes**
* Stage Files: Add your changed files to the staging area using git add . or selectively add files with git add [file_name].
* Commit Changes: Create a commit with a clear message that describes what you have done, e.g., git commit -m "Fixed the login error by updating the authentication logic".

**Step 7: Push Changes**
* Push to GitHub: Push your branch to the remote repository using `git push origin [branch_name]`.

**Step 8: Create a Pull Request (PR)**

* Open a Pull Request: Go to the repository on GitHub. You should see your branch listed with a prompt to create a pull request. Click "Compare & pull request".
* Describe the PR: Add a description of the changes and link the issue you are solving. Tag any relevant team members for review.
* Request Reviews: Request reviews from maintainers or project collaborators as required.

**Step 9: Address Feedback**
* Make Changes if Necessary: If reviewers provide feedback, make the necessary changes in your CodeSpace. Commit and push these changes as described in Steps 6 and 7.

**Step 10: Finalize and Merge**
* Approval: Wait for the approval of your pull request.
* Merge PR: Once approved, merge the pull request into the main branch. Depending on the project setup, you might do this yourself, or a maintainer will do it.

**Step 11: Clean Up**
* Delete Branch: After merging, delete the feature branch both locally and remotely to keep the repository clean.
* Close Issue: Ensure the related issue is closed if it doesn’t automatically do so.

## Documentation
* [Learn Git Branching](https://learngitbranching.js.org/?locale=en_US)
* [An open source game about learning Git](https://ohmygit.org/)