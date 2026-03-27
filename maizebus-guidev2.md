# Commits

We are following a conventional commits way of doing commits to help keep things readable and to make maintenance easier over time.

## Commit Types
- `feat` – new feature

- `fix` – bug fix
  
- `docs` – documentation only
  
- `style` – formatting, whitespace, missing semicolons
  
- `refactor` – code change that neither fixes a bug nor adds a feature

- `perf` – performance improvement
  
- `test` – adding or correcting tests
  
- `chore` – maintenance (build scripts, dependencies, CI)

## Commit Scope
**Flutter side:** `ui`, `widget`, `screen`, `map`, `bus`, `route`, `notif`, `firebase`  
**Backend side:** `backend`, `api`, `endpoint`, `service`, `db`  
**Shared:** `auth`


## Commit Format
Format to follow:
```
<type>(<scope>): <subject>

<body>

<footer>
```

Commit Example:
```
feat(ui): Add "NEW" button to map screen

Added a non-functional button that says "NEW" to the map screen. This is a place to temporarily put our MaizeBus2 launch video.
```
This commit is good because it explains **what** added or changed, and more importantly explains **why** the change was done.



# Pull Requests


## PR Template
```
## Description
(1-2 sentences: what changed and why — e.g., "Added Firebase push notifications for real-time bus arrivals")

## Type of Change
- [ ] New feature (`feat`)
- [ ] Bug fix (`fix`)
- [ ] Refactor / code improvement
- [ ] Dependency / build update
- [ ] Documentation
- [ ] Other (explain)

## Related Issues
Closes #XX

## Changes Made
- Flutter:
  - ...
- Backend (TypeScript):
  - ...
- Firebase / Shared:
  - ...

## Testing Done
**Flutter:**
- [ ] Tested on:
  - [ ] iOS Simulator
  - [ ] Android Emulator
  - [ ] Physical device

**Backend:**
- [ ] TypeScript compilation & linting passed
- [ ] Unit / integration tests passed
- [ ] Tested API endpoints

**Integration:**
- [ ] Flutter app successfully calls updated backend endpoints
- [ ] End-to-end flow tested (e.g., bus arrival → notification)

## Screenshots / Demo (if UI or notification change)
<!-- Drag & drop images or screen recordings here -->

## Checklist
- [ ] Commit messages follow Conventional Commits
- [ ] PR title follows `[type](scope): short description`
- [ ] PR target branch is not `main` and is our current working update branch (e.g. `maizebus2.1`)
- [ ] No `print()` / `debugPrint()` / `console.log()` left in production code
- [ ] Code follows project style (Dart + ESLint/Prettier for TS)
- [ ] Secrets / keys not committed
```
