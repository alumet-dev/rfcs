# Alumet RFCs

This repository hosts the **Request for Comments (RFC)** process for the [Alumet project](https://github.com/alumet-dev).
RFCs are the primary mechanism for proposing, discussing, and refining **substantial changes** to Alumet.

## What is an RFC?

An **RFC (Request for Comments)** is a structured document that:

- **Describes a problem** or opportunity in the Alumet ecosystem.
- **Proposes a solution** with clear motivation, design, and alternatives.
- **Invites feedback** from the community and maintainers before implementation.

## When to Use the RFC Process

RFCs are intentionally heavier-weight than regular PRs (Pull Requests) because they are designed to **facilitate in-depth discussion** before any implementation begins.
While PRs focus on code changes, RFCs ensure that **substantial or impactful proposals** are thoroughly vetted, debated, and refined by the community and maintainers.
This process ensures alignment with Alumet's long-term goals.

Submit an RFC for changes that:

- Significantly touch the **core engine**: API breaking changes, pipeline redesign, crate reorganisation, …
- Significantly impact **user experience**: major CLI changes, revamp of the deployment process, redesign of the documentation, …
- Transform the **development workflow**: breaking changes, new tools, organisation changes, …
- Require **discussion and consensus** among the main contributors

Skip the RFC process for:

- Bug fixes or minor optimizations.
- Small or straightforward improvements (e.g. documentation updates, tweaks to existing plugins, creation of new plugins that fit the roadmap).
- Experimental or proof-of-concept work (open an issue or draft PR in another repository instead).
- Questions and rough ideas (open a discussion in another repository instead)

Please read the [Contribution Guide](CONTRIBUTING.md) for more information.

## RFC Life Cycle

Here is the story of a typical RFC, from a post-it note to a merged PR.

### Preparation Phase

1. Author works on a specific topic.
1. Author prepares an explanation of their solution.

### Draft Phase (optional)

1. Author opens a draft PR with the RFC (using the template – see [CONTRIBUTING.md](CONTRIBUTING.md)).
1. Early feedback from the community.
1. Iterate on design and address questions.

### Discussion Phase

1. A PR is opened (using the template – see [CONTRIBUTING.md](CONTRIBUTING.md)). Alternatively, if a draft PR has been opened, it is marked as "Ready for Review".
1. The PR is reviewed. Of course, experienced contributors have more technical knowledge to review the RFC. However, we encourage Alumet users to participate by adding comments (regular comments, not review comments).
1. Author responds to comments and updates the RFC. `goto step 2;`

### Acceptance

Approval is based on **clear benefit** to the project and **lack of major objections**.

Once no major concerns remain, Alumet contributors can approve the PR.
When everything is clear, a maintainer merges the PR.

Implementation begins, tracked via linked issues in the appropriate repository.

### Rejection / Withdrawal

If unresolved concerns or misalignment persist, the author can close the PR, or maintainers can close the PR.
Authors can revise and resubmit later. Spam is not allowed.
