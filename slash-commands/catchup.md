---
description: Catch up on recent changes
argument-hint: [target-branch]
---

Understand changes in the current branch.

- If `$1` is provided: Compare all changes (committed + uncommitted) against that branch
- If `$1` is empty: Show only uncommitted work

## If target branch provided ($1 is not empty)
1. `git diff $1 --stat` - Overview of all changes vs target branch
2. `git diff $1 --diff-filter=M` - View diffs for modified files
3. `git diff $1 --diff-filter=D --name-only` - List deleted files
4. `git diff $1 --diff-filter=A --name-only` - List added files, then read them directly

## If no target branch (uncommitted changes only)
1. `git status --short` - Overview of changed/staged/untracked files
2. `git diff --diff-filter=M` - View diffs for modified files only
3. `git diff --diff-filter=D --name-only` - List deleted files
4. For new/untracked files shown in status, read them directly
5. (Optional) To see contents of a crucial deleted file: `git show HEAD:path/to/file`