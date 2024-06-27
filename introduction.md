---
title: "Introduction"
teaching: 5
exercises: 5
---

::::::::::::::::::::::::::::::::::::::: objectives

- "Become familiar with the purpose of PRs."

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- "What are Pull Requests (PRs)?"
- "How do PRs help with software development?"

::::::::::::::::::::::::::::::::::::::::::::::::::

## What are Pull Requests?

To borrow from Rachel Garner, "Software developers use pull requests, otherwise
known as PR, to initiate the process of integrating new code changes into the
main project repository. Pull requests are sent through git systems, like
GitLab, GitHub, and BitBucket, to notify the rest of your team that a branch
or fork is ready to be reviewed."

![](fig/vcs-image.png){alt='Image from Undraw.co for version control visualization'}

In other words, PRs are a mechanism for introducing and merging changes
into a code base in a manner that enables discussion and collaboration.

In this lesson, students will learn about better practices for GitHub PRs.

## How Pull Requests Fit in the Development Process

![](fig/gh-pr-workflow.png){alt='From Freira et al.: Visualization of the GitHub development workflow with PRs'}

The development workflow can have several different formats; however, a simple
one is this:

1. Create a feature branch
1. Make changes and commit back to the feature branch
1. Open a Pull request

## The Benefits of Pull Requests

Integrating PRs into the development process has numerous benefits. Some
of the main ones are:

- _Collaboration_: Pull requests provide a location for other developers to see and comment on proposed changes. This encourages collaboration and discussion.
- _Reduce risks_: Other team members are able to review proposed changes and make suggestions, find potential risks, etc.
- _Improve quality_: No one person knows better than a group. Using PRs allows a crowd to get involved and improve the quality of the code.

## GitHub Pull Requests

Numerous different merging systems exist - both commercial and open-source,
integrated and stand-alone.

GitHub integrates branching and merging into their version control system. Every project
on GitHub can use the integrated pull requests feature.

![](fig/intersect-nav.png){alt='INTERSECT training repository navigation bar'}

To access a repository's PRs, simply navigate to the repository root
page and click on "Pull requests" in the navigation bar. This will take you to the
page of all "Open" PRs.

Click on a PR to open it and see its details, plus any discussion.

:::::::::::::::::::::::::::::::::::::::  challenge

## Browsing Open PRs

Navigate to [https://github.com/spack/spack](https://github.com/spack/spack) and find the pull requests page.
 
* How many PRs are currently open?
* How many have been closed?
* Who is the author of the top-most PR?

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: keypoints

- "Pull Requests are a way to control the introduction of new content into a shared repository."
- "Pull Requests enable better collaboration for multiple developers."

::::::::::::::::::::::::::::::::::::::::::::::::::
