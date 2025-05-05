# M31 Autonomous 🚀

<div align="center">

![M31 Logo](assets/icon.png)

[![VS Code Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/m31lab.m31-autonomous?color=blue&label=VS%20Code%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=m31lab.m31-autonomous)
[![VS Code Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/m31lab.m31-autonomous?color=blue&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=m31lab.m31-autonomous)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Docs](https://img.shields.io/badge/docs-online-brightgreen.svg)](https://m31lab.github.io/)
[![Discord](https://img.shields.io/discord/1234567890?color=7289DA&label=discord&logo=discord&logoColor=white)](https://discord.gg/m31)
[![CI](https://github.com/m31lab/Autonomous/actions/workflows/ci.yml/badge.svg)](https://github.com/m31lab/Autonomous/actions/workflows/ci.yml)

**An intelligent AI coding assistant with agent capabilities that lives right in your IDE**

[Installation](#-installation) • 
[Features](#-features) • 
[Documentation](https://m31lab.github.io/) • 
[Contributing](.github/CONTRIBUTING.md) • 
[Discord](https://discord.gg/m31)

</div>

## 🌟 Overview

M31 Autonomous is an advanced AI coding assistant for VS Code that analyzes your codebase, creates and modifies code, runs commands, and controls browsers - all with your explicit permission. It combines the power of Large Language Models (LLMs) with a carefully designed agentic workflow to help you solve complex programming tasks while maintaining full control.

<div align="center">
<img src="assets/demo.gif" alt="M31 Autonomous Demo" width="80%">
</div>

## ✨ Features

- **🔍 Context-Aware Code Understanding**: Analyzes your entire codebase to provide contextually relevant assistance and recommendations
- **📝 Intelligent File Operations**: Creates, modifies, and refactors files with visual diffs and clear explanations of changes
- **🖥️ Terminal Command Integration**: Runs commands, installs dependencies, starts servers - all with your explicit approval
- **🌐 Browser Automation & Testing**: Tests websites, captures screenshots, and helps debug web applications
- **🔧 Extensible Tool System**: Extends capabilities with Model Context Protocol (MCP) servers for specialized workflows
- **⚙️ Customizable Behavior**: Configure rules to tailor M31's responses, code style, and interactions to your preferences
- **🔄 Comprehensive Task History**: Tracks and revisits previous tasks with full session history and code changes
- **📝 AI Git Integration**: Generates conventional, high-quality commit messages for your Git changes with one click
- **🔐 Privacy-First Design**: Works with multiple AI providers and keeps your code secure with granular access controls

## 🚀 Installation

### VS Code Marketplace

1. Install the extension from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=m31lab.m31-autonomous)
2. Configure your preferred API provider in the extension settings
3. Start your first task by writing a request in the chat box

### Manual Installation(Will Be Open Source Soon)

```bash
git clone https://github.com/m31lab/Autonomous.git
cd Autonomous
npm run install:all
npm run package
code --install-extension m31-autonomous-*.vsix
```

## 🔌 Supported AI Providers

M31 Autonomous works with multiple AI providers, giving you flexibility in choosing the backend that best fits your needs:

| Provider | Models | Benefits |
|----------|--------|----------|
| **Claude (Anthropic)** | Claude 3 Opus, Sonnet, Haiku | Highest quality, best reasoning |
| **OpenAI** | GPT-4o, GPT-4, GPT-3.5 | Widely available, versatile |
| **OpenRouter** | Various models | Access to multiple providers |
| **AWS Bedrock** | Claude, Titan, Llama | Enterprise-grade security |
| **LM Studio** | Any compatible model | Local execution, no data sharing |

## 💡 Quick Start Guide

### Starting Your First Task

1. Open the M31 Autonomous sidebar in VS Code
2. Type a natural language request, such as:
   - "Create a React component for a user profile"
   - "Fix the error in this function" 
   - "Set up a basic Express server with MongoDB"

### Using Context Providers

Enhance your requests with specific context using the @ syntax:

- `@file:path/to/file.js` - Reference a specific file
- `@folder:src/components` - Reference a directory
- `@url:https://example.com` - Reference a web page
- `@git:commit` - Reference Git information

### Command Palette Integration

Access M31 Autonomous features through the VS Code command palette (Ctrl+Shift+P / Cmd+Shift+P):

- **M31-Autonomous: Open in New Tab** - Opens the assistant in a dedicated tab
- **M31-Autonomous: Add to M31-Autonomous** - Adds selected code to the chat
- **M31-Autonomous: Generate Git Commit Message** - Creates a commit message for staged changes

## 🛠️ Advanced Features

### AI Git Commit Integration

Streamline your Git workflow with intelligent commit message generation:

- Click the "AI Commit" button in the status bar or use Alt+C shortcut
- M31 analyzes your staged changes and suggests a conventional commit message
- One-click options to commit, edit, or commit and push

### Browser Automation

M31 can interact with web browsers to help test and debug web applications:

```
Can you open my React app at http://localhost:3000 and test the login form?
```

M31 will launch a browser, navigate to your app, interact with the UI, and report results.

### Terminal Command Execution

Run terminal commands with confidence:

```
Can you set up a new Next.js project with TypeScript and Tailwind CSS?
```

M31 will suggest and execute the necessary commands (with your approval) to complete the task.

### Personalization with Rules

Create a `.m31rules` file in your project root to customize M31's behavior:

```
Always use TypeScript strict mode.
Prefer functional components over class components in React.
Follow the project's existing code style and patterns.
```

## 🔒 Privacy & Security

M31 Autonomous prioritizes your security and privacy:

- **Explicit Permission**: Every action requires your approval
- **Access Control**: Use `.m31ignore` to specify directories/files M31 shouldn't access
- **Secure API Keys**: All API keys are stored securely using VS Code's secrets storage
- **Local Execution**: Support for local models through LM Studio

## 🤝 Contributing

Contributions to M31 Autonomous are welcome! Please see our [Contributing Guide](.github/CONTRIBUTING.md) for details on:

- Setting up the development environment
- Code style and guidelines
- Issue reporting and feature requests
- Pull request process

## 📊 Performance & Compatibility

| OS | Compatibility | Notes |
|----|---------------|-------|
| Windows | ✅ Full | Tested on Windows 10 & 11 |
| macOS | ✅ Full | Tested on Intel & Apple Silicon |
| Linux | ✅ Full | Tested on Ubuntu, Debian, Fedora |

Minimum Requirements:
- VS Code 1.84.0+
- Node.js 18.x+
- 4GB RAM (8GB+ recommended)

## 📚 Resources

- [GitHub Repository](https://github.com/m31lab/Autonomous)
- [Documentation](https://m31lab.github.io/)
<!-- - [Discord Community](https://discord.gg/m31) -->
<!-- - [Twitter](https://twitter.com/m31lab) -->
- [Issue Tracker](https://github.com/m31lab/Autonomous/issues)
- [Changelog](CHANGELOG.md)

## 📄 License

M31 Autonomous is released under the [MIT License](LICENSE).

## 🙏 Acknowledgements

M31 Autonomous builds upon the work of many open-source projects and research in AI, natural language processing, and developer tools. We're grateful to the community for their contributions.

Special thanks to:
- The VS Code team for their excellent extension API
- The Anthropic and OpenAI teams for their groundbreaking LLMs
- All our early users for valuable feedback and suggestions
- Cline (@cline) for his invaluable guidance and support
- And everyone who has contributed to the open-source ecosystem
---

<div align="center">
Made with ❤️ by <a href="https://m31lab.github.io/">M31 Labs</a>
</div>
