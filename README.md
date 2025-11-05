# Awesome CLI Coding Agents

> A curated list of CLI (command-line interface) AI agents that understand code and can make edits, generate files, and manage coding workflows from the terminal.

## What are CLI Coding Agents?

CLI coding agents are AI-powered tools that run directly in your terminal and can:
- **Understand codebases** - Read and comprehend project structure and existing code
- **Make intelligent edits** - Modify multiple files with context awareness
- **Generate code** - Create new files and complete implementations
- **Manage workflows** - Handle git commits, PRs, and project automation
- **Execute autonomously** - Take action based on natural language instructions

## Agents

### 1. Claude Code
**Type:** Commercial | **Language:** TypeScript/Node.js
**Repository:** https://github.com/anthropics/claude-code

Anthropic's agentic coding tool that lives in your terminal, understands codebases, and handles git workflows through natural language. Part of Claude Code CLI.

**Key Features:**
- Git integration with intelligent commit messages
- Multi-file editing capabilities
- GitHub/GitLab repository management
- WebSearch and WebFetch integration
- Deep codebase understanding

---

### 2. Aider
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/Aider-AI/aider

AI pair programming tool that runs in your terminal and directly edits code in local git repositories with sensible, atomic commits.

**Key Features:**
- Direct repository editing
- Multi-file coordination
- Automatic git commit generation
- Claude 3.5 Sonnet, DeepSeek, GPT-4o support
- Conversational code editing

---

### 3. Gemini CLI
**Type:** Open Source | **Language:** TypeScript
**Repository:** https://github.com/google-gemini/gemini-cli

Google's open-source AI agent bringing Gemini directly into the terminal for coding, problem-solving, and intelligent task management.

**Key Features:**
- Deep code understanding
- File manipulation and creation
- Command execution capabilities
- Dynamic troubleshooting
- System integration

---

### 4. GitHub Copilot CLI
**Type:** Commercial | **Language:** Proprietary
**Repository:** https://github.com/features/copilot/cli

Brings GitHub Copilot directly to your command line with intelligent code assistance, debugging, and GitHub repository interactions.

**Key Features:**
- Interactive and programmatic modes
- Code suggestions and debugging
- GitHub repository integration
- Explain functionality
- Command line assistance

---

### 5. Goose
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/block/goose

Open-source extensible AI agent from Block that goes beyond code suggestions - builds projects, debugs complex issues, and orchestrates sophisticated coding workflows.

**Key Features:**
- Autonomous project building
- Code migration capabilities (Ember→React, Ruby→Kotlin)
- Workflow orchestration
- Model Context Protocol support
- Fully extensible architecture

---

### 6. Continue
**Type:** Open Source | **Language:** TypeScript
**Repository:** https://github.com/continuedev/continue

Open-source coding agent with TUI (terminal user interface) mode for interactive development and headless mode for background automation tasks.

**Key Features:**
- Interactive TUI mode
- Async agents for background work
- CI/CD integration
- Granular permissions system
- Multi-model support

---

### 7. Cursor CLI
**Type:** Commercial | **Language:** TypeScript
**Repository:** https://cursor.com/en/cli

Command-line version of the Cursor AI editor, enabling AI-powered coding workflows to run directly from the terminal without requiring a GUI.

**Key Features:**
- Cursor Agent in CLI
- Headless workflow execution
- Model flexibility
- Terminal-native development
- Beta with active development

---

### 8. Mentat
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/AbanteAI/mentat

AI coding assistant that coordinates intelligent edits across multiple files from the command line with automatic context awareness via RAG (Retrieval Augmented Generation).

**Key Features:**
- Multi-file edit coordination
- RAG-based automatic context
- Project-wide awareness
- Interactive editing sessions
- Git integration

---

### 9. Cody CLI
**Type:** Open Source | **Language:** TypeScript
**Repository:** https://github.com/sourcegraph/cody

Command-line version of Sourcegraph's Cody AI assistant with deep code graph integration for enhanced contextual understanding.

**Key Features:**
- Code graph integration
- Developer chat interface
- Code completions
- Custom prompt support
- Extensive context awareness

---

### 10. Sweep AI
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/sweepai/sweep

AI junior developer that autonomously transforms bug reports and feature requests into actual code changes and automatically generates pull requests.

**Key Features:**
- Automatic PR generation
- Multi-file code changes
- GitHub integration
- JetBrains IDE support
- Issue-to-PR automation

---

### 11. GPT Engineer
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/AntonOsika/gpt-engineer

CLI platform for code generation from text prompts, capable of generating complete, functional codebases in any programming language.

**Key Features:**
- Full codebase generation
- Multi-language support
- Model flexibility (OpenAI, WizardCoder, etc.)
- Image input support
- Interactive refinement loop

---

### 12. Qodo Command
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/qodo-ai/command

CLI for building, managing, and running AI agents for SDLC (Software Development Life Cycle) automation, testing, and code review tasks.

**Key Features:**
- Test generation agents
- Code review automation
- Web UI mode available
- CI/CD integration
- SDLC workflow automation

---

### 13. OpenCode
**Type:** Open Source | **Language:** Go
**Repository:** https://github.com/opencode-ai/opencode

AI coding assistant built in Go with a responsive terminal user interface for efficient terminal-based development tasks.

**Key Features:**
- Terminal user interface
- Multi-model support
- Fast execution
- Interactive development
- Code understanding

---

### 14. Open Interpreter
**Type:** Open Source | **Language:** Python
**Repository:** https://github.com/openinterpreter/open-interpreter

Natural language interface that lets LLMs execute code locally with full system access for practical file manipulation and task automation.

**Key Features:**
- Local code execution
- Multi-language support
- Full system access
- File manipulation
- Task automation

---

## Comparison Table

| Agent | Type | Language | Multi-File | Git Support | Autonomous |
|-------|------|----------|-----------|------------|-----------|
| Claude Code | Commercial | TypeScript | ✅ | ✅ | ✅ |
| Aider | Open Source | Python | ✅ | ✅ | ✅ |
| Gemini CLI | Open Source | TypeScript | ✅ | ✅ | ✅ |
| GitHub Copilot CLI | Commercial | Proprietary | ✅ | ✅ | ⚠️ |
| Goose | Open Source | Python | ✅ | ✅ | ✅ |
| Continue | Open Source | TypeScript | ✅ | ✅ | ✅ |
| Cursor CLI | Commercial | TypeScript | ✅ | ⚠️ | ✅ |
| Mentat | Open Source | Python | ✅ | ✅ | ✅ |
| Cody CLI | Open Source | TypeScript | ✅ | ✅ | ⚠️ |
| Sweep AI | Open Source | Python | ✅ | ✅ | ✅ |
| GPT Engineer | Open Source | Python | ✅ | ⚠️ | ✅ |
| Qodo Command | Open Source | Python | ✅ | ✅ | ✅ |
| OpenCode | Open Source | Go | ✅ | ⚠️ | ✅ |
| Open Interpreter | Open Source | Python | ✅ | ⚠️ | ✅ |

## Key Capabilities Overview

### Multi-File Editing
Agents that can intelligently coordinate changes across multiple files:
- Claude Code, Aider, Gemini CLI, Continue, Mentat, Sweep AI, all others

### Git Integration
Agents with native git workflow support:
- Claude Code, Aider, Mentat, Cody CLI, Sweep AI

### Autonomous Execution
Agents that can work independently with minimal user intervention:
- Goose, Sweep AI, Open Interpreter, GPT Engineer

### Codebase Understanding
Agents with deep context awareness of entire projects:
- Claude Code, Aider, Mentat, Cody CLI, Goose

## Getting Started

### For Beginners
Start with these user-friendly agents:
1. **Claude Code** - Excellent git/workflow integration
2. **Aider** - Great for pair programming style
3. **Gemini CLI** - Good all-around coding agent

### For Advanced Users
Consider these powerful options:
1. **Goose** - Maximum extensibility and automation
2. **Continue** - Flexible async agent capabilities
3. **Sweep AI** - Autonomous issue resolution

### For Privacy-Conscious Users
Open-source agents with local model support:
1. **Aider** - Works with local models
2. **Open Interpreter** - Full local execution
3. **Continue** - Local model compatible

## Contributing

Have a CLI coding agent to add? Please submit a pull request with:
- Agent name and repository link
- Brief 1-2 sentence description
- Type (open-source/commercial)
- Primary implementation language
- Key features list

## License

This list is curated for the awesome community. Each tool maintains its own license - see individual repositories for details.

---

**Last Updated:** November 4, 2025
