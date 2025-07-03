# GitHub Copilot Instructions

## Overview

These instructions define how GitHub Copilot should assist with this project. This file lays out requirements for general copilot interaction and maintenance of the project repository.

## General Rules

1. **Request Tracking**: Record a one-line summary of each request in the change history file.
2. **README Updates**: Keep the README.md file updated with any new features, tools, or significant changes.



## Change History Tracking

Each request made to GitHub Copilot should be recorded in the `.github/change-history.md` file with:

1. The current timestamp in ISO format (YYYY-MM-DD)
2. A concise one-line summary of the request

Example format:
```markdown
- 2025-07-02: Created initial project structure for the web application
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

- If you need clarity before proceeding with a request, ask questions to ensure understanding.

