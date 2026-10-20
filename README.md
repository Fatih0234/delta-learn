# delta-learn

A personal learning workspace for understanding Delta through its official
documentation and small, practical examples. This is a learning sandbox, not a
production application.

## Current focus

Learn the three concepts topics in this order:

1. **Core Concepts (start here):**
   https://delta.dev/docs/concepts/core-concepts
2. **Delta & Git (next):**
   https://delta.dev/docs/concepts/delta-and-git
3. **Delta Worktrees (after that):**
   https://delta.dev/docs/concepts/worktrees

## Start with Core Concepts

The first goal is to distinguish these terms:

| Term | Meaning |
| --- | --- |
| Thread | A conversation with an agent that records messages and project changes together. A thread can also exist without a project. |
| Project | The Git repository you open and attach to a thread. |
| Delta worktree | A project's files and history for a thread, recorded in DeltaDB. Threads normally get isolated worktrees. |
| Checkout | The Delta worktree's files on disk, where desktop terminal commands and other local tools run. |

A thread can include multiple projects, with one Delta worktree per project.
One project can be used in multiple threads. A Delta worktree is not the same
thing as a Git worktree.

For this workspace, `delta-learn` is the project and this conversation is a
thread working with it. File edits belong to the thread's attached Delta
worktree. Do not assume they also changed your original project folder.

### Check your understanding

- Explain how a thread differs from a plain chat conversation.
- Identify the project attached to this thread.
- Explain the difference between a Delta worktree and a checkout.
- Explain why edits in an isolated workspace do not immediately change the
  original project folder.

Use the linked official documentation as the source of truth. These notes are
a learning aid, not a replacement for the current docs.
