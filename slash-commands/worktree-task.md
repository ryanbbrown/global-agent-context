---
description: Start work on assigned ticket in this worktree
---

You are working in a git worktree on branch: $ARGUMENTS

1. Run `tk ready` to see available tickets, or `tk show <id>` if you know your ticket
2. Run necessary setup (npm install, etc.) if node_modules is missing
3. Run `tk start <id>` on your assigned ticket
4. Do the work
5. Commit with a clear message referencing the ticket ID
6. Run `tk close <id>`
7. Do NOT push or merge