# vscode-copilot-tips

This repository contains tips and best practices for developers using GitHub Copilot in Visual Studio Code. It focuses on how to work effectively with Copilot's Agent, Skill, and MCP features, plus guidance for creating custom tools and finding high-quality resources.

## Agent

An **Agent** is a configured Copilot assistant that can perform tasks, automate workflows, and help you code faster inside VS Code. Agents connect to language models and tools to provide contextual suggestions, run commands, or even manage code review and refactoring.

- What it is: a specialized Copilot persona or workflow that combines AI reasoning with practical actions.
- How it works: Agents use prompts, tool connections, and the VS Code interface to understand your project context and respond with code, explanations, or task automation.
- How to use: enable Agents in VS Code, choose an agent from the Copilot panel, and ask it for coding help, refactoring, documentation, or debugging assistance.
- Custom agents: create your own by defining agent behavior, prompt templates, and integrations in VS Code settings or via the Copilot extension.
- Popular places for agents: GitHub Agents marketplace, Vercel agent collections, Claude agents, and community-shared agent templates for React, TypeScript, and best practices.

## Skill

A **Skill** is a reusable capability that Copilot can use to solve specific problems or automate coding tasks. Skills are narrower than agents and are focused on actions like generating tests, linting code, or translating documentation.

- What it is: a discrete, composable feature that extends Copilot with a specialized function.
- How it works: Skills are invoked by Copilot when a relevant task is detected or when you explicitly request them in VS Code.
- How to use: install or enable Skills through the Copilot extension, then trigger them from commands, the Copilot sidebar, or inline code suggestions.
- Custom skills: build your own by writing templates, rule sets, or automation scripts that target your development workflow in VS Code.
- Popular places for skills: GitHub Skills library, Vercel skill collections, Claude skill repositories, and community sources for React, Node, and frontend engineering workflows.

## MCP (Model Context Protocol)

**MCP** stands for Model Context Protocol. It is a standard for connecting language models with applications and tools, giving Copilot richer context about your files, codebase, and environment.

- What it is: a protocol for sharing structured project context between VS Code and AI models.
- What is an MCP server: a local or remote service that provides contextual data, document indexing, and model-aware search to improve AI responses.
- How it works: VS Code sends project context to the MCP server, which processes files, metadata, and references, then returns context that the model can use when generating suggestions.
- How to use: install or connect to an MCP server extension in VS Code, configure it for your workspace, and let Copilot query it for richer code-aware answers.
- Custom MCP servers: create your own server by implementing the MCP API, feeding it repository data, docs, and project metadata to support custom workflows.
- Popular MCP servers: Perplexity MCP Server and other community servers that enhance code understanding and search for developers.

## Why this repo

This repository is a practical source for developers who want to level up their GitHub Copilot usage in VS Code. It is designed to collect actionable guidance on Agents, Skills, MCP servers, and the best places to find strong examples and community-backed tooling.

### What to Expect

- clear explanations of Copilot concepts
- tips for building custom tools in VS Code
- references to real-world agent and skill resources
- guidance on modern MCP-enabled workflows

Use this repo as your personal guide for building a smarter, more efficient Copilot-powered coding workflow.
