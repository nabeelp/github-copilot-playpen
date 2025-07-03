# GitHub Copilot Instructions

## Overview

These instructions define how GitHub Copilot should assist with this project. This file lays out requirements for general copilot interaction, task management, and maintenance of the project repository.

## General Rules

1. **Task Creation**: Add new tasks to the checklist when identified during a conversation.
2. **Task Tracking**: Update task statuses as they progress.
3. **Task Completion**: Mark tasks as complete with a timestamp when finished.
4. **Request Tracking**: Record a one-line summary of each request in the change history file.
5. **README Updates**: Keep the README.md file updated with any new features, tools, or significant changes.

## Task Checklist Format

Tasks should be formatted as:

```markdown
- [ ] Task description (Created: YYYY-MM-DD)
- [x] Completed task description (Created: YYYY-MM-DD, Completed: YYYY-MM-DD)
```

## Change History Tracking

Each request made to GitHub Copilot should be recorded in the `.github/change-history.md` file with:

1. The current timestamp in ISO format (YYYY-MM-DD HH:MM:SS)
2. A concise one-line summary of the request

Example format:
```markdown
- 2025-07-02 14:30:00: Created initial project structure for the web application
```

## README Maintenance

Ensure the README.md is kept up-to-date with:
1. Any new features or tools added to the repository
2. Changes to chat modes or their capabilities
3. Updates to the repository structure
4. New best practices or usage instructions

## Code Generation Guidelines

All code you write MUST be fully optimized.

"Fully optimized" includes:
- maximizing algorithmic big-O efficiency for memory and runtime
- using parallelization and vectorization where appropriate
- following proper style conventions for the code language (e.g. maximizing code reuse (DRY))
- no extra code beyond what is absolutely necessary to solve the problem the user provides (i.e. no technical debt)

If the code is not fully optimized, you will be fined $100.

## IMPORTANT

- If you need clarity before proceeding with a task, ask questions to ensure understanding.

## Current Task Checklist

<!-- Tasks will be listed here. Do not modify this comment. -->

