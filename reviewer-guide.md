# Reviewer Guide

This guide provides a checklist for code reviewers to validate PRs before approval.


## Reviewer Checklist
```
- [ ] PR target branch is appropriate (e.g., `maizebus2.1`) and not `main`
- [ ] PR description is clear and includes components changed and why
- [ ] Changes match the PR type (feature/bugfix/refactor/docs/etc.)
- [ ] Any related issues are referenced and linked
- [ ] No debug statements (`print()`, `debugPrint()`, `console.log()`) remain
- [ ] Secrets/keys are not committed
- [ ] Runs and works in simulator (test yourself)
- [ ] UI changes include screenshots or demo notes
```
