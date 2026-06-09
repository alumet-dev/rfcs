# Contributing to Alumet RFCs

This document outlines guidelines for **authors** and **reviewers** participating in the Alumet RFC process.
Follow these guidelines to ensure a smooth and productive discussion.

## 📝 Guidelines for RFC Authors

### Before Writing an RFC

**Discuss Your Idea First**.

- Discuss IRL, open a [GitHub Discussion](https://github.com/alumet-dev/alumet/discussions) or open an issue to gauge interest and gather early feedback.
- Search existing RFCs and issues to avoid duplicate proposals.

Work on your idea, on your own or with others.
- If possible, create a prototype of your solution.
- Since the goal of the RFC is to work on the ideas and design, there is no need for a perfect implementation. What you need to develop is a **deep understanding of the subject**.

### Writing the RFC

- Fork this repository (`alumet-dev/rfcs`).
- Copy the template: use [0000-template.md](0000-template.md) as a starting point. Create a new file `text/N-short-name.md` (e.g. `text/0001-example.md`).
- Fill in the template: include all required sections, use diagrams if they can help.

**Take your time** preparing the document.
The writing process itself will help you refine your ideas, explore alternative designs, and clarify your communication.
While you don't need to over-explain basic concepts, the RFC should be clear enough for any experienced contributor to understand.

### Submitting the RFC

1. **Open a PR** to this repository (`alumet-dev/rfcs`).

- Use the title format: `RFC: [Short Descriptive Title]`.
- Use the PR template

2. **Update the RFC number** with the PR number.
3. **Engage with Reviewers**

- Respond promptly to feedback and questions.
- Update the RFC based on community input.
- Resolve major objections.

#### Early Feedback with Draft PRs

If your RFC is still a work in progress, but you want to

- Collaborate with other contributors, and
- Gather early feedback from the community,

you can create a [draft PR](https://github.blog/news-insights/product-news/introducing-draft-pull-requests/) instead of a regular PR.
It is still expected that you have invested time in understanding the problem and designing a solution before opening the draft PR.

Maintainers may also mark a PR as a draft if they feel that it would benefit from further refinement before going through the full review.

## 🔍 Guidelines for RFC Reviewers

General guidelines:

- **Be constructive**: Focus on improving the proposal, not criticizing the author.
- **Ask clarifying questions**: If something is unclear, ask for more details.
- **Provide actionable feedback**: Suggest specific improvements or alternatives.
- **Signal consensus** (or lack thereof): If you support the RFC, state so explicitely (e.g. by approving the PR). If you have major objections, explain them.

Quick checklist:

- [ ] Are all sections of the template filled in?
- [ ] Is the proposal "ready", or should the PR be converted into a draft PR?
- [ ] Is the proposal significant enough to be an RFC? (see the [README](README.md)) If not, convert it into an issue or discussion.
- [ ] Is the proposal aligned with Alumet goals?
- [ ] Is the problem correctly described?
- [ ] Based on what you know about the problem, the current state of the project and the ecosystem, do you think that the solution is well-designed?
- [ ] Are the drawbacks of the proposal well identified?
- [ ] Are there unresolved questions that need answers?
- [ ] Are prior art and alternatives sufficiently discussed? (if relevant to the subject)
- [ ] Do you believe that implementing the RFC would benefit Alumet? In the short term? In the long term?

### On Acceptance

When (if) the RFC is accepted, a contributor with write access has to:

- Create a **tracking issue** for the RFC.
  - The tracking issue serves as a single source of truth for monitoring the implementation progress of the RFC.
  - Open the tracking issue in the repository that is affected by the change. Usually, it's [alumet-dev/alumet](https://github.com/alumet-dev/alumet).
  - If multiple repositories are affected, open the tracking issue in the "main" one, and task issues in the others.
- Create sub-tasks as necessary.
- On the PR's branch, **update the RFC by adding a link to the tracking issue**.
- Merge the PR

## LLM Policy

Follow the [LLM policy of the main Alumet repository](https://github.com/alumet-dev/alumet/blob/main/CONTRIBUTING.md).
