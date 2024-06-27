---
title: "'Good' Pull Requests"
teaching: 5
exercises: 0
---
::::::::::::::::::::::::::::::::::::::: objectives

- "Become familiar with what makes a 'good' PR."

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- "What does it mean to be a 'good' PR?"
- "What should you do to make a 'good' PR?"

::::::::::::::::::::::::::::::::::::::::::::::::::

## What makes a 'Good' Pull request?

Now that we are familiar with the basic makeup of a pull request, we want
to address the question, "What makes a good pull request?"

There are many answers to this question, and, like anything, there is no
single right answer, but here are some useful tips.

### The Single Responsibility Principle

One of the SOLID principles, the Single Responsibility Principle says, "A
module should be responsible to one, and only one, actor." This principle
also applies for pull requests.

When making changes and getting ready to submit a PR, the changes within that
PR should all be related and, ideally, doing _one_ clear thing.

This will make it easier to review and to ensure that changes don't introduce
new, seemingly "unrelated" bugs.


:::::::::::::::::::::::::::::::::::::::::  callout

## Do one thing, and one thing only

If your PR has many unrelated changes together, separate it into multiple
different PRs.

::::::::::::::::::::::::::::::::::::::::::::::::::

### Reasonable Size

Have you ever been assigned to review a PR with several hundreds or thousands
of line changes? These are monstrous, difficult to review, and can take much
longer to merge back into the code base.

Keep your PRs a reasonable size! Some changes are, in fact, just big; however,
if you can, split big changes into several smaller PRs to increase the
reviewability and make discussions more productive.

:::::::::::::::::::::::::::::::::::::::::  callout

## Break it down

If your PR is very large, split it into smaller PRs.

::::::::::::::::::::::::::::::::::::::::::::::::::

### Be Descriptive

When making your PR, be descriptive in the title and description. Include
the answers to common questions:

1. What is being changed?
1. How did it change (and what other effects might there be)?
1. Why is this change being suggested?

Putting the answer to these questions in the description section of the PR
will make it clear the motivation and give a higher level overview for reviewers
so they know more about the suggested changes.

:::::::::::::::::::::::::::::::::::::::::  callout

## What, How, Why

Preemptively answer common questions in the description of your PR to
streamline the review process.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: keypoints

- "A pull request should contain _ONE_ cohesive change."
- "A pull request should, ideally, be quickly reviewable."
- "A pull request description should give an overview of what, how, and why something changed."

::::::::::::::::::::::::::::::::::::::::::::::::::
