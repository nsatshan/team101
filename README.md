# CS 490 - Collaboration and Ownership Lab

## Objective

This lab is about collaboration, ownership, and visible contribution.

This is not a programming exercise. The goal is not to build an application. The goal is to experience a professional Git and GitHub workflow while working as a team.

By the end of this lab your team will:

* fork a repository
* collaborate through GitHub
* create branches
* commit and push changes
* open and review pull requests
* merge work into a shared repository
* submit a pull request back to the instructor repository

The artifacts you create in this lab will also establish your project teams for the semester.

## This is a graded assignment

This lab will be treated as our second "homework" assignment. While each team will submit one final pull request, each person must have a commit in order to earn full credit. The grading rubric is below.

# Repository Workflow

Go to the instructor's repository at [https://github.com/njit-prof-bill/cs-490-141-summer-lab-1](https://github.com/njit-prof-bill/cs-490-141-summer-lab-1).

Fork the repository into one GitHub account owned by your team.

The repository's owner must add all teammates as collaborators to the new repo.

Each teammate will clone the team repository locally.

Relevant Git commands:

* `git clone`

# Initial Team Setup

The project manager should:

* create a folder for the team under `teams/`
* copy the example files into the new team folder
* rename the files appropriately
* update `team.md` with the team information

The project manager should commit and push these changes first.

Relevant Git commands:

* `git add`
* `git commit`
* `git push`

Once the project manager has pushed the initial setup, all teammates should synchronize their local repositories.

Relevant Git commands:

* `git pull`

# Individual Student Work

Each student must:

* synchronize their repository before starting work
* create their own branch
* update `team.md`
* create and complete their own member file
* commit and push their work
* open a pull request into the team repository

Relevant Git commands:

* `git checkout`
* `git add`
* `git commit`
* `git push`

Suggested branch naming convention:

```text
feature/<your-name>
```

Example:

```text
feature/jane-doe
```

---

# Workflow Guidance

The project manager should merge pull requests one at a time.

Students should synchronize their repositories after pull requests are merged.

Avoid having multiple students edit the same section of `team.md` simultaneously. Poor synchronization is one of the most common causes of unnecessary merge conflicts.

If merge conflicts occur, resolve them as a team.

Relevant Git commands:

* `git pull`
* `git merge`

---

# Pull Request Reviews

Before merging a pull request, the project manager should:

* review the changes
* verify the student updated the correct files
* ensure the repository remains organized

At least one pull request should include review feedback before it is merged.

The goal is to experience the collaboration workflow, not simply move files into the repository.

---

# Final Submission

Once all student pull requests have been merged:

* verify the repository contains all required files
* synchronize the repository one final time
* open a pull request from the team repository back to the instructor repository

The final pull request should contain:

* the completed `team.md`
* all student member files
* visible commit history from all team members

# Deliverables

Each team must submit:

* one completed team repository
* one pull request back to the instructor repository

Each student must contribute:

* at least one branch
* at least one commit
* at least one pull request
* updates to both `team.md` and their own member file

## Grading Rubric

One point for each of the following ...

* Proper repository is forked
* Team information provided
* Individual information provided
* Individual commit
* PR submitted that can be automatically merged

# Notes

GitHub Desktop, VS Code Git integration, JetBrains tools, and the Git CLI are all acceptable for this lab.

The important thing is understanding the workflow underneath the tooling.

Professional engineers use many different interfaces to Git. The concepts remain the same.

Collaboration leaves artifacts. Your repository history, pull requests, branches, and commits should clearly show how your team worked together.
# cs-490-collaboration-lab-template
The template repository for the collaboration lab
