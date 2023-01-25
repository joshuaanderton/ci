# Continuous Integration for Laravel apps (via GitHub)
The following is a guide to setting up basic (but life-saving) CI implementation that consists of the following steps:

- Code Linting
- Style & Dependency checks
- Build
  - Triggered by:
    - Merges to `staging` branch - after approved PR is squash-and-merged in
    - Merges to `master`
  - Deploy
    - Triggered by:
    - Build passes for merge to `master`
