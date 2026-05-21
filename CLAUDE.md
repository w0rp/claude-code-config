# HOME directory CLAUDE.md

## General command Guidance

* You are not allowed to use any `git` commands that stage/unstage changes,
  merge code, rebase, etc.
* You can use `git` commands such as `git status`, `git diff`, `git reflog`,
  or any other `git` command that reads information from the codebase.
* You are not permitted to execute `python`, `node`, or `perl` by any means!
  For Python you may only `uv run` scripts in the codebase, importantly
  `uv run test`, and for TypeScript you may only run tests via Yarn.
  Think and reason about code instead of attempting to run it other than through
  tests.
