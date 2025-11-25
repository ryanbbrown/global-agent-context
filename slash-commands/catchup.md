---
description: Catch up on recent changes
---

Understand what active (uncommitted) work has been done in the current branch.

## Git commands to use

1. `git status --short` - See overview of changed/staged/untracked files
2. `git diff --diff-filter=M` - View diffs for modified files only
3. `git diff --diff-filter=D --name-only` - List deleted files (just names)
4. For new/untracked files shown in status, read them directly
5. (Optional) To see contents of a crucial deleted file: `git show HEAD:path/to/file`