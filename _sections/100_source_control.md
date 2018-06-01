---
title: Source Control
---

Source control allows us to work together on writing a shared codebase (really just a bunch of text files). It helps us do a few key things:

 * Get a copy of the latest code
 * Track changes to the code
 * Save ("commit") a version of the codebase
 * Share those changes with others
 * Merge in changes from others
 * Roll back changes when things go wrong
 * Store the code in a central location


### Key Concepts

#### Git vs. GitHub

Git allows you to track sets of changes to code. All of this happens on your local computer first. Git also has the concept of a remote. GitHub is an incredibly popular service that hosts git remote repositories. There are many other tools and hosted tools (Microsoft TFS, AWS CodeCommit, GitLab, etc.) that do something similar.

#### When & How to Commit, Push


#### Managing Secrets



### The STSI Way

 * Git: We use Git whenever possible. It is by far the dominant industry standard.
 * GitHub: We use GitHub by default, but often work with client-provided repositories.
 * Git Flow: We use the [gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) workflow approach to branching/merging/pull requests.
