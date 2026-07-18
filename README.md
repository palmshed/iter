# Harper

An AI assistant written in Rust.

Harper is an autonomous coding agent designed for software development workflows. It combines language models, tool execution, sandboxed environments, and developer-focused interfaces into a unified system.

## Platform

Harper is primarily built for Linux.

The project is developed using a Debian-based toolchain and relies on Bubblewrap for secure sandbox isolation. While development can be performed from macOS or Windows using containerized environments, Linux remains the primary execution and validation platform.

## Components

### harper-core

Core runtime services and assistant logic.

### harper-agent

Agent workflows, conversation handling, tool routing, and deterministic actions.

### harper-ui

A terminal user interface for interacting with Harper.

### harper-mcp-server

Model Context Protocol integration.

### harper-sandbox

Isolated execution environments for tools and commands.

### harper-firmware

Hardware abstraction support for embedded and edge platforms.

## Capabilities

* Autonomous coding workflows
* Codebase investigation
* File and repository operations
* Shell command execution
* Git and GitHub integration
* Code review workflows
* Tool orchestration
* Persistent sessions and memory
* Terminal interface
* VS Code integration
* MCP support
* Sandboxed execution

## Model Support

* OpenAI
* Gemini
* SambaNova
* Ollama

## Architecture

Harper provides the runtime, interfaces, and execution environment.

Iter provides the agent.

Together they form a Rust-based platform for AI-assisted software development.

---

## Origin

> Carrier: https://github.com/harpertoken/harper
