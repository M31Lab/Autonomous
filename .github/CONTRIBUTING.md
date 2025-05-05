# Contributing to M31 Autonomous

Thank you for your interest in contributing to M31 Autonomous! This document provides guidelines and instructions for contributing to the project.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Environment](#development-environment)
- [Making Contributions](#making-contributions)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Code Contributions](#code-contributions)
- [Pull Request Process](#pull-request-process)
- [Style Guides](#style-guides)
  - [Git Commit Messages](#git-commit-messages)
  - [TypeScript Style Guide](#typescript-style-guide)
  - [Documentation](#documentation)
- [Community](#community)

## Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct.

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Set up the development environment
4. Create a new branch for your work
5. Make your changes
6. Test your changes
7. Push to your fork and submit a pull request

## Development Environment

To set up your development environment:

1. Install [Node.js](https://nodejs.org/) (version 18.x or later)
2. Install [VS Code](https://code.visualstudio.com/)
3. Clone the repository: `git clone https://github.com/m31lab/Autonomous.git`
4. Install dependencies:
   ```
   cd Autonomous
   npm run install:all
   ```
5. Build the extension:
   ```
   npm run compile
   ```
6. To run the extension in development mode:
   - Press F5 in VS Code to launch a new window with the extension loaded
   - Make changes to the code
   - Reload the window to see changes (Ctrl+R or Cmd+R)

## Making Contributions

### Reporting Bugs

1. Use the Bug Report template when creating an issue
2. Include detailed steps to reproduce
3. Include your environment (OS, VS Code version, etc.)
4. If applicable, include screenshots or error logs

### Suggesting Features

1. Use the Feature Request template when creating an issue
2. Clearly explain the problem the feature would solve
3. Be specific about the solution you'd like
4. Consider alternatives and why they might not be sufficient

### Code Contributions

1. Check existing issues and pull requests before starting work
2. Comment on an issue to express interest before starting work
3. Follow the style guides
4. Write tests for your code
5. Update documentation as necessary

## Pull Request Process

1. Create a new branch for your changes
2. Make your changes, following the style guides
3. Add or update tests as necessary
4. Update documentation as necessary
5. Run tests locally to ensure they pass
6. Push your changes to your fork
7. Create a pull request using the provided template
8. Respond to review comments
9. Once approved, your pull request will be merged

## Style Guides

### Git Commit Messages

- Use the conventional commit format:
  ```
  type(scope): short description

  Longer description if necessary
  ```
- Types include: feat, fix, docs, style, refactor, perf, test, build, ci, chore
- Keep the first line under 72 characters
- Use the present tense ("add feature" not "added feature")
- Use the imperative mood ("move cursor to..." not "moves cursor to...")

### TypeScript Style Guide

- Follow the ESLint and Prettier configuration in the project
- Use TypeScript strict mode
- Avoid any types unless absolutely necessary
- Write clean, self-documenting code with descriptive variable names
- Add JSDoc comments for public APIs

### Documentation

- Use clear, concise language
- Update documentation when making code changes
- Follow Markdown best practices
- Validate links

## Community

- Join our [Discord](https://discord.gg/m31) to chat with other contributors
- Follow us on [Twitter](https://twitter.com/m31lab) for announcements
- Check our [documentation](https://m31lab.github.io/) for detailed guides

Thank you for contributing to M31 Autonomous! 