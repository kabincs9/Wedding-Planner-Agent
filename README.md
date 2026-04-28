# 💒 Advanced Wedding Planner Agent | Module 2

**Multi-Agent AI Wedding Planner** 🍾✨  
*A sophisticated multi-agent system that plans your dream wedding with custom state management and Model Context Protocol (MCP).*

An intelligent multi-agent application that coordinates multiple specialized agents to create complete, personalized wedding plans — from venue selection and budgeting to vendor coordination and timeline creation.

## ✨ Project Overview

This project takes agent development to the next level by building a **Multi-Agent System** powered by LangChain. It uses custom state, shared context, and connects to external tools via the **Model Context Protocol (MCP)**.

The system acts as a full wedding planning team — with different agents handling specific aspects while collaborating through a shared custom state.

## 🛠️ Tech Stack

- **LangChain** (Python)
- Advanced `create_agent` with **Custom State**
- **Multi-Agent System** architecture
- **Model Context Protocol (MCP)** & MCP Server
- **Middleware** for dynamic agent behavior
- Shared context and state management
- **Tavily** search + external tool integration
- **uv** — Lightning-fast Python package manager
- Jupyter Lab & Jupyter Notebooks

## 🎯 Key Features

- Multi-agent collaboration for complex planning
- Custom state management across agents
- Integration with MCP servers for external tools
- Dynamic agent behavior using middleware
- Persistent context and memory across conversations
- Coordinated workflow for venue, budget, vendors, and timeline
- Beautiful streaming responses with rich formatting

## 🚀 Key Learnings from Module 2

- Building **Multi-Agent Systems** with LangChain
- Implementing **Custom State** for complex workflows
- Working with **Model Context Protocol (MCP)** and MCP servers
- Using middleware to enhance and control agent behavior
- Managing shared context between multiple agents
- Creating production-ready agent architectures

## 📸 Demo

The system takes high-level requirements (budget, location, theme, guest count) and returns a comprehensive wedding plan coordinated by multiple specialized agents.

**Example:**  
User says: *"Plan a budget-friendly wedding in Pokhara for 80 guests with a Himalayan theme."*

→ The multi-agent system delivers a full plan including venue suggestions, vendor recommendations, timeline, and budget breakdown.

## 📂 Project Structure

```bash
wedding-planner-agent/
├── notebooks/              # Experimentation & development
├── src/
│   ├── agents/             # Individual specialized agents
│   ├── state.py            # Custom state definition
│   ├── mcp_server/         # MCP server implementation
│   ├── middleware.py       # Custom middleware
│   └── workflow.py         # Multi-agent orchestration
├── pyproject.toml          # uv configuration
├── requirements.txt
└── README.md
🏅 Certificate
Student: Kabin Baniya
School: LangChain Academy
Course: Foundation: Introduction to LangChain - Python
Certificate ID: eht4iamrjm

Quick Start
Bashgit clone https://github.com/kabincs9/wedding-planner-agent.git
cd wedding-planner-agent

# Using uv (recommended)
uv sync
uv run jupyter lab
