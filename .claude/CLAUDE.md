# Project notes for Claude

## Commits and pull requests

- **Author:** commit as the repo owner, not as Claude. Before the first commit in a
  session, run:

  ```bash
  git config user.name "WardinaSafein"
  git config user.email "wardinasafein55@gmail.com"
  ```

- **No attribution trailers:** do not add `Co-Authored-By:` or `Claude-Session:` lines
  to commit messages.
- **Titles** (commits and PRs): short and professional.
  - Under ~50 characters, imperative mood, sentence case ("Simplify 404 page").
  - No all-caps words; put detail in the body or PR description.
  - Say what changed, not how.
