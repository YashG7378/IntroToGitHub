# IntroToGitHub

A practice repository for learning version control, Git commands, SSH authentication, issues, pull requests, and Markdown.

> **What is version control?** It tracks changes to files over time so you can review history, undo mistakes, and collaborate without overwriting each other's work.
This repository is my practice space for learning Git and GitHub.
As a Task , working on the Issues and how to Use and Merge it.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Git Commands Learned](#git-commands-learned)
- [Workflow Practiced](#workflow-practiced)
- [Sample Project: Expense Tracker](#sample-project-expense-tracker)
- [Learning Goals](#learning-goals)
- [Author](#author)

## Repository Structure

```text
IntroToGitHub/
├── README.md        # Project documentation (this file)
├── SSH.txt          # Notes/test file from SSH setup
├── Code2.txt        # Practice file for commits and branches
├── project.txt      # Project notes
└── screenshot.png   # Sample mockup used in this README
```

## Git Commands Learned

| Command | Purpose |
|---|---|
| `git init` | Create a new local repository |
| `git add` | Stage changes |
| `git commit -m "msg"` | Save a snapshot of staged changes |
| `git push` / `git pull` | Upload / download changes |
| `git branch` / `git checkout` | Create and switch branches |
| `git merge` | Combine branches |

## Workflow Practiced

1. Set up **SSH keys** to authenticate with GitHub without passwords.
2. Opened an **issue** describing a small improvement.
3. Created a **branch**, made the fix, and committed it.
4. Opened a **pull request** that closes the issue, then **merged** it.

## Sample Project: Expense Tracker

A simple web app for recording and viewing personal expenses, built with HTML, CSS, and a little JavaScript as my first GitHub project.

## Description

This project helps users:

- Add expenses with a name, amount, and category
- See a running total of spending
- Learn the basics of web development and Git/GitHub

> **Note:** This is a beginner project created for learning purposes.

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Page structure |
| CSS | Styling and layout |
| JavaScript | Basic interactivity |

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:YashG7378/IntroToGitHub.git
   ```
2. Move into the project folder:
   ```bash
   cd IntroToGitHub
   ```
3. Open `index.html` in your web browser.

## Usage

1. Enter the expense name and amount.
2. Choose a category.
3. Click **Add** to see it in the list.

## Sample Project: Expense Tracker

![Expense tracker screenshot](screenshot.png)

## Learning Goals

- [x] Create a GitHub repository
- [x] Configure SSH and push over SSH
- [x] Use issues and pull requests
- [x] Write a README in Markdown
- [ ] Build and publish the expense tracker with GitHub Pages
      
## Author

**Yash Gupta**, Computer Science student at CU Boulder

## Links/Resources

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Docs](https://docs.github.com/)
