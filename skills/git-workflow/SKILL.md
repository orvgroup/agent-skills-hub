---
name: git-workflow
description: Manage Git repositories, branches, commits, merges, pull requests, and collaborative development workflows safely.
---

# Git Workflow Skill

## Purpose

Help AI agents follow safe, consistent, and maintainable Git workflows.

## Core Responsibilities

- Inspect repository status and history.
- Create and manage branches.
- Write meaningful commits.
- Synchronize local and remote changes.
- Resolve merge conflicts carefully.
- Prepare pull requests.
- Maintain a clean and understandable project history.

## Standard Workflow

1. Inspect the current branch and working tree.
2. Review existing changes before modifying files.
3. Create a descriptive branch for independent work.
4. Make focused changes related to one task.
5. Review the diff before committing.
6. Run relevant tests and checks.
7. Commit with a clear, descriptive message.
8. Push the branch and open a pull request when appropriate.
9. Review feedback and update the changes.
10. Merge only after required checks and reviews pass.

## Commit Guidelines

- Use concise, meaningful commit messages.
- Keep commits focused on a single logical change.
- Avoid committing generated files, secrets, or temporary files.
- Never claim a commit succeeded unless the operation confirms it.
- Do not rewrite shared history without authorization.

## Branch Guidelines

- Keep the main branch stable.
- Use descriptive branch names.
- Avoid making unrelated changes in one branch.
- Do not force-push shared branches unless explicitly authorized.

## Conflict Resolution

1. Inspect all conflicting files.
2. Understand both sides of the changes.
3. Preserve intended functionality.
4. Resolve conflicts without blindly choosing one side.
5. Review the final diff.
6. Run relevant tests before completing the merge.

## Safety Rules

- Never run destructive Git commands without understanding their impact.
- Do not use `git reset --hard`, force-push, or delete branches without authorization.
- Never expose access tokens or credentials.
- Do not overwrite uncommitted user changes.
- Confirm the target branch before merging or pushing.

## Quality Checklist

- [ ] Correct branch selected.
- [ ] Working tree reviewed.
- [ ] Changes are focused.
- [ ] Diff reviewed.
- [ ] Relevant tests executed.
- [ ] Commit message is meaningful.
- [ ] No secrets or unwanted files committed.
- [ ] Pull request description explains the changes.
