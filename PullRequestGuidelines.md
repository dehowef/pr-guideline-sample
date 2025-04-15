

# Guidelines for Submitting a Pull Request to SampleProject

Thank you for your interest in contributing to SampleProject. We aim to make contributing simple and transparent, while maintaining a clean commit history to support future revisions and modular development.

We use GitHub to manage and track feature requests, bugs, and issues. Please check the [Issues](https://github.com/dehowef/pr-guideline-sample/issues) and [Pull Requests](https://github.com/dehowef/pr-guideline-sample/pulls) tabs to see what is in progress and under review.

## General Pull Request Guidelines
We aim to have a streamlined, readable commit log so that contributors can look back and readily pinpoint where changes occurred.

All submitted Pull Requests (PRs) should adhere to the following guidelines:
- PRs should be made from a forked repository
  - Create a branch from `main` in your forked repo
  - Do your work on this branch and make your pull request against `main`
- PRs should consist of a single commit.
	- The first line of the commit message should be a short description (max 50 characters).
	- Commit message bodies should not exceed 72 characters per line.
- PRs should be complete. Examples include:
  - Implementing a single feature
  - Refactoring code in a meaningful way
  - Resolving a bug
  - Updating documentation
- PRs should be focused:
  - PRs should ideally address one GitHub Issue.
  - Bug fixes that address multiple related bugs are acceptable.
  - Avoid combining multiple unrelated features in a single PR.

Before submission, verify that the code compiles without errors and that all regression tests pass.

## Feature Additions and Refactors

- Create a GitHub Issue proposing a new feature or refactor and tag it in your commit message.
- In the commit body, briefly describe the implementation and changes made.
- Add or update regression tests as needed in the `/regress` folder.

## Bug Fixes

- Tag the GitHub Issue(s) your PR addresses in your commit message.
- In the commit body, briefly explain how the PR resolves the bug(s) and what changes were made.
- Add or update regression tests as needed in the `/regress` folder.

## Documentation

Revisions to documentation should be substantive—such as adding new content, proofreading and editing sections, or improving clarity. To keep the commit log clean and organized, please avoid submitting one-line documentation changes as Pull Requests.

In the commit body, briefly explain the improvements you made.

Please refer to the [documentation style guide](https://github.com/dehowef/pr-guideline-sample/tree/main) in our wiki for detailed contribution guidelines.

Before submitting, build the documentation and verify that it compiles without errors.

## Pull Request Review Process

Once a PR is submitted, it will undergo community review.

Discussion and review will take place in the Conversation tab of each Pull Request. We encourage community participation and constructive feedback. Committers and trusted project members may ask you to clarify your PR or make changes. Please respond promptly.

Each PR requires approval from two committers. Once a PR is approved, a committer or senior community member will merge it into the main branch, and it will be included in a future release.

