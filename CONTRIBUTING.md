# Contributing to Quorum by ConsenSys

Welcome to the QbC repository! This document describes the procedure and guidelines for contributing to the QbC project. The subsequent sections encapsulate the criteria used to evaluate additions to, and modifications of, the existing codebase.

## Contributor Workflow

The codebase is maintained using the "*contributor workflow*" where everyone without exception contributes patch proposals using "*pull-requests*". This facilitates social contribution, easy testing and peer review.

To contribute a patch, the workflow is as follows:

* Fork repository
* Create topic branch
* Commit patch
* Create pull-request, adhering to the coding conventions herein set forth

In general a commit serves a single purpose and diffs should be easily comprehensible. For this reason do not mix any formatting fixes or code moves with actual code changes.

## Style Guide

`La mode se démode, le style jamais.`

Guided by the immortal words of Gabrielle Bonheur, we strive to adhere strictly to best stylistic practices for each line of code in this software.

At this stage one should expect comments and reviews from fellow contributors. You can add more commits to your pull request by committing them locally and pushing to your fork until you have satisfied all feedback. Before merging, you should aim to have a clean commit history where each commit identifies an specific change, or where all
commits are squashed together.

#### Clear Commit/PR Messages

Commit messages should be verbose by default consisting of a short subject line (50 chars max), a blank line and detailed explanatory text as separate paragraph(s), unless the title alone is self-explanatory (such as "`Implement EXP EVM opcode`") in which case a single title line is sufficient. Commit messages should be helpful to people reading your code in the future, so explain the reasoning for your decisions. Further explanation on commit messages can be found [here](https://chris.beams.io/posts/git-commit/).

#### Test coverage

The test cases are sufficient enough to provide confidence in the code’s robustness, while avoiding redundant tests.

#### Readability

The code is easy to understand.

#### Simplicity

The code is not over-engineered, sufficient effort is made to minimize the cyclomatic complexity of the software.  

#### Functional

Insofar as is possible the code intuitively and expeditiously executes the designated task.

#### Clean

The code is free from glaring typos (*e.g. misspelled comments*), thinkos, or formatting issues (*e.g. incorrect indentation*).

#### Appropriately Commented

Ambiguous or unclear code segments are commented. The comments are written in complete sentences.
