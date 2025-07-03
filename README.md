# GitHub Copilot Playpen

A template repository for setting up and customizing GitHub Copilot interactions in your development workflow.

## Overview

This repository serves as a playground and template for enhancing your GitHub Copilot experience. It includes custom configurations, chat modes, and tracking mechanisms to maximize the effectiveness of AI-assisted development.

## Features

### Custom Chat Modes

- **Architect Mode**: Generates architecture designs, specifications, and diagrams with Azure service recommendations
- **Tester Mode**: Helps create test strategies, test cases, and automation frameworks with Playwright for UI testing
- **Debugger Mode**: Assists in systematically identifying, analyzing, and resolving bugs in applications

### Task Tracking

The repository includes an automated task tracking system that:
- Creates and maintains a checklist of tasks
- Updates task statuses as they progress
- Records completion timestamps
- Maintains a change history log

### Change History

All interactions with GitHub Copilot are automatically logged in a change history file, providing:
- Timestamps for each request
- Concise summaries of changes made
- A chronological record of project evolution

### Language-Specific Instructions

The repository includes language-specific instruction sets to ensure code generation follows best practices:
- Python coding conventions following PEP 8 and PEP 257 guidelines
- Angular development standards using signals for state management and following Angular.dev best practices

### Tool Integrations

- **Playwright**: Integrated for UI testing and automation
- **Microsoft Docs MCP**: Connected for Azure service documentation and best practices
- **Azure Architecture Tools**: Available in Architect mode for designing cloud solutions

## Using This Template

1. **Fork or Clone**: Use this repository as a template for your projects
2. **Customize Chat Modes**: Modify existing chat modes or add new ones based on your project needs
3. **Update Instructions**: Adjust the Copilot instructions to match your workflow
4. **Start Developing**: Begin interacting with GitHub Copilot using your customized setup

## Directory Structure

```
.github/
├── chatmodes/          # Custom VS Code chat modes for specialized assistance
│   ├── Architect.chatmode.md
│   ├── Debugger.chatmode.md
│   └── Tester.chatmode.md
├── instructions/       # Language-specific coding instructions
│   ├── angular.instructions.md
│   ├── copilot-thought-logging.instructions.md
│   └── python.instructions.md
├── prompts/            # Template prompts for specific tasks
├── change-history.md   # Chronological log of all Copilot interactions
└── copilot-instructions.md  # Instructions for GitHub Copilot behavior
.vscode/
└── mcp.json            # Configuration for Model Context Protocol servers
```

## Best Practices

- Keep the README updated with any new features or customizations
- Regularly review and clean up the task checklist
- Use the custom chat modes for specialized assistance
- Reference the change history to track project evolution
- Follow language-specific coding conventions for consistent code quality

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Created and maintained with ❤️ and GitHub Copilot
