# Team_Project
# Team Collaboration Using GitHub

## Aim

To learn how to collaborate on a software project using GitHub by creating a shared repository, working with branches, managing Issues, creating Pull Requests, performing code reviews, and documenting the project using `README.md`.

## Objectives

* To create a GitHub repository for a team project.

* To form a team of 2 or 3 students.

* To assign tasks to each team member.

* To work safely using separate branches.

* To track work using GitHub Issues.

* To merge code using Pull Requests.

* To review and improve team members’ code.

* To prepare project documentation using `README.md`.

## Requirements

* GitHub account

* Git installed on the computer

* VS Code or any code editor

* Internet connection

* Two or three team members

* A project such as a login system, portfolio, or student management system

## Team Formation

Form a group of 2 or 3 students.

Example:

|
Team Member

|

Responsibility

|
| --- | --- |
|

Student 1

|

Project setup and HTML

|
|

Student 2

|

CSS design and JavaScript

|
|

Student 3

|

Testing, documentation, and database

|

For a two-member team:

|
Team Member

|

Responsibility

|
| --- | --- |
|

Student 1

|

Frontend development

|
|

Student 2

|

JavaScript, testing, and documentation

|

# Procedure

## Step 1: Create a GitHub Repository

1. Open GitHub: GitHub .

2. Log in to your account.

3. Click the + icon.

4. Select New repository.

5. Enter a repository name.

Example:

```
team-login-project
```

6.  Add a short description.

7. Select Public or Private.

8. Select Add a README file.

9. Click Create repository.

## Step 2: Add Team Members

1. Open the created repository.

2. Click Settings.

3. Select Collaborators or Collaborators and teams.

4. Click Add people.

5. Enter the GitHub usernames of the team members.

6. Send invitations.

7. Team members accept the invitations.

## Step 3: Clone the Repository

Open VS Code terminal or Command Prompt and run:

Bash

```
git clone https://github.com/USERNAME/team-login-project.git
```

Move into the project folder:

Bash

```
cd team-login-project
```

Check the repository status:

Bash

```
git status
```

## Step 4: Create Tasks Using Issues

GitHub Issues are used to divide the project into smaller tasks.

Example Issues:

|
Issue

|

Task

|
| --- | --- |
|

Issue 1

|

Create login page

|
|

Issue 2

|

Create registration page

|
|

Issue 3

|

Add CSS styling

|
|

Issue 4

|

Add JavaScript validation

|
|

Issue 5

|

Prepare README documentation

|
|

Issue 6

|

Test the complete project

|

Each issue can be assigned to a team member.

## Step 5: Create Branches

Each student should work in a separate branch.

Create a branch:

Bash

```
git checkout -b login-page
```

Another student can create:

Bash

```
git checkout -b registration-page
```

A third student can create:

Bash

```
git checkout -b documentation
```

Check the current branch:

Bash

```
git branch
```

### Benefits of Branches

* Avoids changes to the main code.

* Allows multiple students to work at the same time.

* Makes testing easier.

* Helps manage different tasks separately.

## Step 6: Add and Commit Code

After completing a task:

Bash

```
git add .
```

Commit the changes:

Bash

```
git commit -m "Created login page"
```

Push the branch to GitHub:

Bash

```
git push -u origin login-page
```

For another branch:

Bash

```
git push -u origin registration-page
```

## Step 7: Create a Pull Request

A Pull Request is used to request that code from one branch be merged into the main branch.

Procedure:

1. Open the GitHub repository.

2. Select the pushed branch.

3. Click Compare & pull request.

4. Add a title.

Example:

```
Added login page
```

5.  Add a description of the changes.

6. Select a team member as reviewer.

7. Click Create pull request.

## Step 8: Perform Code Review

The reviewer checks:

* Code correctness

* Naming of variables

* HTML structure

* CSS formatting

* JavaScript errors

* Security problems

* Duplicate code

* Project requirements

The reviewer can:

* Approve the Pull Request.

* Request changes.

* Add comments.

* Suggest improvements.

After approval, the Pull Request can be merged into the main branch.

## Step 9: Merge the Pull Request

After code review:

1. Open the Pull Request.

2. Click Merge pull request.

3. Click Confirm merge.

4. Delete the branch if it is no longer required.

Update the local main branch:

Bash

```
git checkout main
git pull origin main
```

# Git Workflow

```
Create Repository
        ↓
Create Issues
        ↓
Assign Tasks
        ↓
Create Branches
        ↓
Write Code
        ↓
Commit Changes
        ↓
Push Branch
        ↓
Create Pull Request
        ↓
Code Review
        ↓
Merge into Main
        ↓
Update Project
```

# Useful Git Commands

|
Command

|

Description

|
| --- | --- |
|

`git init`

|

Creates a Git repository

|
|

`git clone URL`

|

Downloads a GitHub repository

|
|

`git status`

|

Shows current changes

|
|

`git branch`

|

Displays branches

|
|

`git checkout -b branch-name`

|

Creates and switches to a branch

|
|

`git add .`

|

Adds all changes

|
|

`git commit -m "message"`

|

Saves changes with a message

|
|

`git push`

|

Uploads changes to GitHub

|
|

`git pull`

|

Downloads latest changes

|
|

`git log`

|

Displays commit history

|
|

`git merge branch-name`

|

Merges a branch

|
|

`git checkout main`

|

Switches to the main branch

|

# README.md Documentation

The `README.md` file explains the project to other developers.

Example:

Markdown

```
# Team Login Project

## Project Description

This project is a web-based login and registration system
developed using HTML, CSS, JavaScript, and Firebase.

## Team Members

1. Student 1 - Frontend Development
2. Student 2 - JavaScript Development
3. Student 3 - Documentation and Testing

## Features

- User registration
- User login
- Password validation
- User dashboard
- Logout option
- Firebase authentication

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Firebase
- GitHub

## How to Run

1. Clone the repository.
2. Open the project folder.
3. Open `index.html` using VS Code Live Server.
4. Configure Firebase if required.

## Git Workflow

- Create an issue.
- Create a new branch.
- Complete the assigned task.
- Commit and push the code.
- Create a Pull Request.
- Complete code review.
- Merge the Pull Request.

## Conclusion

This project demonstrates team collaboration using GitHub,
branches, Issues, Pull Requests, and code reviews.
```

## Expected Output

A shared GitHub repository containing:

```
team-login-project/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
```

The repository should also contain:

* Assigned Issues

* Separate student branches

* Commit history

* Pull Requests

* Code review comments

* Merged code

* Project documentation

## Result

A shared GitHub repository was created successfully. Team members worked on separate branches, assigned tasks using Issues, uploaded code through commits, created Pull Requests, reviewed each other’s code, and merged the completed work into the main branch. The project was documented using `README.md`.<img width="821" height="734" alt="image" src="https://github.com/user-attachments/assets/8db87c76-b50c-4a9c-a0ab-bcc23c5fb993" />


## Conclusion

GitHub provides an effective platform for team-based software development. Using branches, Issues, Pull Requests, and code reviews helps team members work together without overwriting each other’s code. The `README.md` file provides clear information about the project, technologies, team members, and execution steps.
