# 🛠️ Engineering Skills & AI Ops

A centralized library of **System Prompts**, **Technical Workflows**, and **Engineering Standards** used to automate software development lifecycles and orchestrate AI agents.

## 🎯 Purpose
This repository acts as a **Meta-Framework** for modern engineering. It stores the logic used to transform high-level requirements and architecture plans (RFCs) into executable code, structured backlogs, and standardized documentation.

---

## 🏗️ Repository Structure

```text
.
├── commands/           # Workflow automation commands for PR reviews and work tracking
├── mcp/                # Model Context Protocol server configurations and sync utilities
│   ├── refresh-mcps    # Script to refresh MCP server connections
│   ├── servers.template.json  # Template configuration for MCP servers
│   └── sync/           # Synchronization utilities
│       └── validate-symlinks  # Script to validate MCP symlinks
├── rules/              # Engineering standards and workflow rules
├── skills/             # AI agent skills and specialized workflows
│   ├── adr-skill/      # Architecture Decision Record management skill
│   ├── backlog-to-project/  # Skill for converting backlogs to project items
│   ├── software-engineer/   # General software engineering workflows
│   ├── story-reviewer/      # User story review automation
│   └── user-story-writer/   # User story generation skill
├── src/                # Source code and language-specific agent configurations
│   └── main/java/      # Java-specific agent definitions
└── LICENSE             # Repository license
