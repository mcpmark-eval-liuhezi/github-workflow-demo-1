# github-workflow-demo-1
A live, self-contained demo of a change moving through GitHub: CI on the default branch, a feature branch, a pull request, a line-level review, and a tracking issue.

## Walkthrough notes

- CI lives in `.github/workflows/ci.yml` and runs on every push to the default branch.
- Feature work happens on a short-lived branch and lands through a pull request.
- Reviews can be left as line-level comments directly on the diff.
