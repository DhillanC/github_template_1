# GitHub Agile Planning Template

Reusable starter repository for practicing GitHub Issues, pull requests, and lightweight agile planning.

Use this template when you want a clean repository with ready-made issue and PR templates for a small project, lab, or learning exercise.

## What's Included

- User story issue template
- Feature request issue template
- Bug report issue template
- Technical task issue template
- Pull request template
- Contribution guide
- Suggested workflow for moving work from issue to pull request
- MIT license

## Recommended Workflow

1. Create an issue using the template that best matches the work.
2. Add labels so the backlog is easy to scan.
3. Create a branch from the issue.
4. Make the change in small commits.
5. Open a pull request and link it to the issue.
6. Review the pull request before merging.
7. Close the issue when the acceptance criteria are met.

## Issue Types

Use **User Story** when the work describes value from a user's perspective.

Use **Feature Request** when the work is a new capability that still needs shaping.

Use **Bug Report** when something is broken or behaving unexpectedly.

Use **Technical Task** for maintenance, setup, documentation, refactoring, or other work that does not directly describe user-facing value.

## Branch Naming

Recommended branch names:

- `feature/short-description`
- `bugfix/short-description`
- `task/short-description`
- `docs/short-description`

Example:

```text
feature/add-weather-report
```

## Pull Request Expectations

Before opening a pull request:

- Keep the change focused on one issue or one logical unit of work.
- Update documentation when behavior or usage changes.
- Add or update tests when the project has test coverage.
- Confirm the acceptance criteria are satisfied.

## Project Board Tips

For a simple project board, start with these columns:

- Backlog
- Ready
- In Progress
- In Review
- Done

Move issues across the board as work progresses. Keep pull requests linked to their issues so GitHub can track status automatically.

## License

This template is available under the MIT License. See [LICENSE](LICENSE).
