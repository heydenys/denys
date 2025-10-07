# Commit ccd2b20a7a91c55223a8588196722db72524caef — "Got rid of the errors that showed in VS Code"

## Summary

This pull request contains small documentation and formatting fixes to `README.md` to resolve VS Code/markdown-lint warnings (MD041, MD026, MD022).

## What changed

------------

- Converted the first line into a top-level heading (H1) so the file starts with a top-level heading (MD041).
- Removed trailing punctuation from the heading to satisfy the no-trailing-punctuation rule (MD026).
- Added a blank line after the heading so headings are surrounded by blank lines (MD022).
- Fixed minor whitespace and wording in two lines.

## Files changed

------------

- `README.md`: heading level changed from `###` to `#`, removed trailing punctuation, added blank line, small text/whitespace tweaks.

## Why

------------

These are non-functional, stylistic changes intended to make the Markdown adhere to common linter rules and improve readability in editors like VS Code.

## Notes

------------

- No code changes. Safe to merge.
- If you'd like, I can also run a markdown linter across the repository and fix any additional issues.
