# Contributing

Welcome to CloudTTY!

- [Contributing](#contributing)
- [Before you get started](#before-you-get-started)
  - [Code of Conduct](#code-of-conduct)
  - [Community Expectations](#community-expectations)
- [Getting started](#getting-started)
- [Your First Contribution](#your-first-contribution)
  - [Find something to work on](#find-something-to-work-on)
    - [Find a good first topic](#find-a-good-first-topic)
      - [Work on an issue](#work-on-an-issue)
    - [File an Issue](#file-an-issue)
- [Contributor Workflow](#contributor-workflow)
  - [Creating Pull Requests](#creating-pull-requests)
  - [Code Review](#code-review)

# Before you get started

## Code of Conduct

Please make sure to read and observe our [Code of Conduct](/CODE_OF_CONDUCT.md).

## Community Expectations

CloudTTY is a community project driven by its community which strives to promote a healthy, friendly and productive environment.

# Getting started

- Fork the repository on GitHub
- Make your changes in your forked repository
- Submit a Pull Request (PR)

# Your First Contribution

We will help you contribute in different areas such as filing issues, developing features, fixing critical bugs and
getting your work reviewed and merged.

## Find something to work on

We are always in need of help, whether it's fixing documentation, reporting bugs, or writing code.
Look for places where best coding practices aren't followed, code refactoring is needed, or tests are missing.
Here's how you can get started.

### Find a good first topic

There are [multiple repositories](https://github.com/cloudtty/) within the CloudTTY organization.
Each repository has beginner-friendly issues marked as "good first issues".
For example, [cloudtty/cloudtty](https://github.com/cloudtty/cloudtty) has
[help wanted](https://github.com/cloudtty/cloudtty/issues?q=state%3Aclosed%20is%3Aissue%20label%3A%22help%20wanted%22) and
[good first issue](https://github.com/cloudtty/cloudtty/issues?q=is%3Aopen%20is%3Aissue%20label%3A%22good%20first%20issue%22)
labels for issues that should not require deep knowledge of the system.
We can help new contributors who wish to work on such issues.

Another good way to contribute is to find documentation improvements, such as fixing missing or broken links.
Please see [Contributing](#contributing) below for the workflow.

#### Work on an issue

When you are willing to take on an issue, simply reply to the issue and a maintainer will assign it to you.

### File an Issue

While we encourage everyone to contribute code, we also appreciate when someone reports an issue.
Issues should be filed under the appropriate CloudTTY sub-repository.

Please follow the provided submission guidelines when opening an issue.

# Contributor Workflow

Please never hesitate to ask questions or submit a pull request.

This is a rough outline of what a contributor's workflow looks like:

- Create a topic branch from where you want to base the contribution (usually master)
- Make commits of logical units
- Push changes in your topic branch to your personal fork of the repository
- Submit a pull request to [cloudtty/cloudtty](https://github.com/cloudtty/cloudtty)

## Creating Pull Requests

Pull requests are often called simply "PRs".
CloudTTY generally follows the standard [GitHub pull request](https://help.github.com/articles/about-pull-requests/) process.
To submit a proposed change, please develop the code/fix and add new test cases.

## Code Review

To make it easier for your PR to receive reviews, consider that reviewers will need you to:

* Follow [good coding guidelines](https://github.com/golang/go/wiki/CodeReviewComments)
* Write [good commit messages](https://chris.beams.io/posts/git-commit/)
* Break large changes into a logical series of smaller patches which individually make easily understandable changes, and in aggregate solve a broader issue
