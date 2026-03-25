## Description

Added checks for unwanted characters in stop names. Some stop names had multiple spaces and characters like "%" which were not intentional and have been removed


## Type of Change
- [ ] New feature (`feat`)
- [x] Bug fix (`fix`)
- [ ] Refactor / code improvement
- [ ] Dependency / build update
- [ ] Documentation
- [ ] Other (explain)


## Changes Made
- Flutter:
  - constants.dart
  - bus_stop.dart
  - map_screen.dart
  - search_sheet_main.dart

## Testing Done
**Flutter:**
- [ ] Tested on:
  - [x] iOS Simulator
  - [ ] Android Emulator
  - [ ] Physical device


## Checklist
- [x] Commit messages follow Conventional Commits
- [x] PR title follows `[type](scope): short description`
- [x] No `print()` / `console.log()` left in production code
- [x] Code follows project style (Dart + ESLint/Prettier for TS)
- [x] Secrets / keys not committed
