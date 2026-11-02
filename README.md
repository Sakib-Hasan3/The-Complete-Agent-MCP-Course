
# 🤖 AI Engineer Agentic Track: The Complete Agent & MCP Course

> **A hands-on journey into Agentic AI, Autonomous Agents, Multi-Agent Systems, and Model Context Protocol (MCP).**

This repository contains my **code, projects, experiments, notes, and implementations** while studying the **AI Engineer Agentic Track: The Complete Agent & MCP Course** by **Ed Donner & Ligency**.

The course focuses on building practical AI agents using modern frameworks and protocols such as **OpenAI Agents SDK, CrewAI, LangGraph, AutoGen, and MCP**. The current course structure is organized around a six-week, project-based learning path.

---

## 🎯 Learning Goals

By completing this track, I aim to learn how to:

* Understand **Agentic AI** and autonomous AI systems
* Build AI agents that can **reason, plan, and use tools**
* Implement **tool calling**
* Build single-agent and multi-agent systems
* Work with different agent frameworks
* Build agents with memory and state
* Use **Model Context Protocol (MCP)**
* Build and connect MCP servers
* Design reliable agent workflows
* Implement human-in-the-loop systems
* Add guardrails and safety mechanisms
* Trace and observe agent execution
* Deploy practical AI agents
* Build production-oriented Agentic AI applications

---

# 🧠 What is Agentic AI?

Traditional LLM applications generally follow:

```text
User → Prompt → LLM → Response
```

Agentic AI extends this into a system where an LLM can decide what actions are necessary to achieve a goal:

```text
                    ┌──────────────┐
                    │     User     │
                    └──────┬───────┘
                           ↓
                    ┌──────────────┐
                    │  AI Agent    │
                    └──────┬───────┘
                           ↓
                 ┌──────────────────┐
                 │ Reason / Plan    │
                 └────────┬─────────┘
                          ↓
                 ┌──────────────────┐
                 │ Select Tool      │
                 └────────┬─────────┘
                          ↓
             ┌──────────────────────────┐
             │ API / Database / Search  │
             │ File / Code / MCP Tool   │
             └────────────┬─────────────┘
                          ↓
                 ┌──────────────────┐
                 │ Observe Result   │
                 └────────┬─────────┘
                          ↓
                    ┌──────────────┐
                    │ Next Action? │
                    └──────┬───────┘
                           ↓
                         Done
```

The key idea is:

> **An agent uses an LLM together with tools, memory, and control logic to accomplish a goal through multiple steps.**

---

# 🛠️ Technologies & Frameworks

## Core

* Python
* LLM APIs
* Prompt Engineering
* Tool Calling
* Structured Outputs
* Async Python
* Agent Design Patterns

## Agent Frameworks

* **OpenAI Agents SDK**
* **CrewAI**
* **LangGraph**
* **Microsoft AutoGen**

## Protocol

* **Model Context Protocol (MCP)**

## Supporting Technologies

* APIs
* Databases
* Vector Databases
* RAG
* Docker
* Gradio
* Web Browsers
* Observability & Tracing
* Human-in-the-Loop

---

# 📚 Course Roadmap

## Week 1 — Foundations of Agentic AI

### Topics

* From LLMs to Agents
* Autonomous AI Agents
* Agent Design Patterns
* Async Python
* Prompt Engineering
* Tool Calling
* Memory
* Agent loops

### Project 1 — Career Digital Twin

Build an AI agent that can represent a person's professional profile and interact with potential opportunities.

**Main concepts:**

```text
LLM
 ↓
Agent
 ↓
Tools
 ↓
Memory
 ↓
Autonomous Workflow
```

---

# 🚀 Week 2 — OpenAI Agents SDK

Learn how to build agents using the **OpenAI Agents SDK**.

### Topics

* Agents
* Tools
* Handoffs
* Agent orchestration
* Structured outputs
* Multi-agent workflows
* Guardrails

### Project 2 — SDR Agent

Build an AI-powered Sales Development Representative agent.

Possible workflow:

```text
Lead
 ↓
Research
 ↓
Analyze
 ↓
Generate Message
 ↓
Review
 ↓
Send
```

---

# 🔬 Project 3 — Deep Research Agent

Build a multi-agent research system capable of researching a topic through multiple steps.

Example architecture:

```text
                 ┌───────────────┐
                 │ Research Lead │
                 └───────┬───────┘
                         │
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
     Researcher      Researcher     Researcher
          │              │              │
          └──────────────┼──────────────┘
                         ↓
                  ┌─────────────┐
                  │  Synthesizer│
                  └──────┬──────┘
                         ↓
                    Final Report
```

---

# 🤝 Week 3 — CrewAI

Learn how to build and orchestrate **multi-agent systems** using CrewAI.

### Topics

* Agents
* Tasks
* Crews
* Agent roles
* Delegation
* Sequential workflows
* Collaborative agents

---

# 📈 Project 4 — Stock Research Agent

Build a research-oriented multi-agent system that analyzes financial information and produces research outputs.

> This project is used for learning agent orchestration, tool usage, delegation, and structured workflows—not for making real-world financial decisions.

Example:

```text
Manager Agent
      │
      ├── Research Agent
      │
      ├── Data Agent
      │
      └── Analysis Agent
              │
              ↓
          Final Report
```

---

# 👨‍💻 Project 5 — AI Engineering Team

Build a team of AI agents capable of collaborating on software development tasks.

Example:

```text
              Engineering Manager
                      │
        ┌─────────────┼─────────────┐
        ↓             ↓             ↓
    Developer       Tester       Reviewer
        │             │             │
        └─────────────┼─────────────┘
                      ↓
                 Final Project
```

### Possible responsibilities

* Project planning
* Code generation
* Code review
* Testing
* Debugging
* Documentation

Docker can be used to isolate development environments.

---

# 🕸️ Week 4 — LangGraph

Learn how to build stateful and controllable agent workflows using **LangGraph**.

### Topics

* Graph-based workflows
* Nodes
* Edges
* State
* Conditional routing
* Loops
* Persistence
* Human-in-the-loop

Example:

```text
START
  ↓
Planner
  ↓
Execute
  ↓
Evaluate
  ↓
 ┌───────────────┐
 │ Good Result?  │
 └───────┬───────┘
       No│ │Yes
         │ ↓
         │ END
         ↓
      Re-plan
```

---

# 🖥️ Project 6 — Browser Sidekick

Build an agent capable of assisting with browser-based tasks.

The project explores:

* Browser interaction
* Agent planning
* Tool usage
* Stateful workflows
* Human-in-the-loop patterns

---

# 🧠 Week 5 — Advanced Agent Frameworks

Explore different approaches to building agents.

### Topics

* Comparing agent frameworks
* Multi-agent architecture
* Agent orchestration
* Memory
* Agentic RAG
* Vector databases
* Observability
* Guardrails
* Deployment

---

# 🏗️ Project 7 — Agent Creator

Build an agent that can help create and configure other agents.

Conceptually:

```text
User Goal
    ↓
Agent Creator
    ↓
Analyze Requirements
    ↓
Design Agent
    ↓
Select Tools
    ↓
Generate Configuration
    ↓
Launch Agent
```

This introduces the concept of **meta-agents**.

---

# 🔌 Week 6 — Model Context Protocol (MCP)

## What is MCP?

**Model Context Protocol (MCP)** is a standardized way for AI applications to connect models and agents with external tools and data sources.

Instead of building every integration independently:

```text
Agent → Custom Integration → Tool A

Agent → Custom Integration → Tool B

Agent → Custom Integration → Tool C
```

MCP provides a standardized approach:

```text
                AI Agent
                   │
                  MCP
                   │
       ┌───────────┼───────────┐
       ↓           ↓           ↓
   MCP Server   MCP Server   MCP Server
       │           │           │
       ↓           ↓           ↓
    Database      API        Files
```

---

# 🧩 MCP Concepts

Important concepts covered in this repository include:

* MCP Client
* MCP Server
* Tools
* Resources
* Prompts
* Tool discovery
* MCP transports
* Agent + MCP architecture

---

# 🏆 Project 8 — Autonomous Multi-Agent System

The final project combines multiple concepts learned throughout the course.

A conceptual architecture:

```text
                         USER
                           │
                           ↓
                    ┌────────────┐
                    │ Orchestrator│
                    └──────┬─────┘
                           │
          ┌────────────────┼────────────────┐
          ↓                ↓                ↓
       Agent 1           Agent 2          Agent 3
          │                │                │
          └────────────────┼────────────────┘
                           ↓
                    MCP Infrastructure
                           │
        ┌──────────────────┼──────────────────┐
        ↓                  ↓                  ↓
     Tool 1             Tool 2             Tool 3
```

The capstone demonstrates how multiple agents and MCP-connected tools can work together in an autonomous workflow. The current course description identifies this as a multi-agent trading-floor project using multiple MCP servers and tools.

---

# 📂 Repository Structure

```text
agentic-ai-course/
│
├── README.md
│
├── week-01-foundations/
│   ├── notes/
│   ├── labs/
│   └── project-01-career-digital-twin/
│
├── week-02-openai-agents/
│   ├── notes/
│   ├── labs/
│   ├── project-02-sdr-agent/
│   └── project-03-deep-research/
│
├── week-03-crewai/
│   ├── notes/
│   ├── labs/
│   ├── project-04-research-agent/
│   └── project-05-engineering-team/
│
├── week-04-langgraph/
│   ├── notes/
│   ├── labs/
│   └── project-06-browser-sidekick/
│
├── week-05-autogen/
│   ├── notes/
│   ├── labs/
│   └── project-07-agent-creator/
│
├── week-06-mcp/
│   ├── notes/
│   ├── mcp-servers/
│   ├── mcp-clients/
│   └── project-08-capstone/
│
├── experiments/
│
├── resources/
│
└── requirements.txt
```

---

# 🔑 Core Concepts

| Concept           | What I am learning                                 |
| ----------------- | -------------------------------------------------- |
| LLM               | Foundation model used by agents                    |
| Agent             | LLM + tools + control loop                         |
| Tool Calling      | Allowing agents to perform actions                 |
| Memory            | Maintaining useful information across interactions |
| RAG               | Connecting agents to external knowledge            |
| Multi-Agent       | Multiple agents collaborating                      |
| Orchestration     | Controlling agent workflows                        |
| MCP               | Standardized tool/data connectivity                |
| Guardrails        | Controlling unsafe or invalid behavior             |
| Human-in-the-Loop | Keeping humans involved when necessary             |
| Observability     | Understanding what agents are doing                |
| Deployment        | Running agents in real environments                |

---

# 🧪 Learning Method

This repository follows a **learn → build → experiment → document** approach.

For every topic:

```text
1. Learn the concept
        ↓
2. Build a small example
        ↓
3. Understand the code
        ↓
4. Build the course project
        ↓
5. Modify / experiment
        ↓
6. Document what I learned
```

---

# 📊 Progress

## Foundations

* [ ] Agentic AI basics
* [ ] Agent loops
* [ ] Tool calling
* [ ] Async Python
* [ ] Memory
* [ ] Agent design patterns

## OpenAI Agents SDK

* [ ] Agents
* [ ] Tools
* [ ] Handoffs
* [ ] Guardrails
* [ ] Multi-agent workflows
* [ ] SDR Agent
* [ ] Deep Research Agent

## CrewAI

* [ ] Agents
* [ ] Tasks
* [ ] Crews
* [ ] Delegation
* [ ] Multi-agent workflows
* [ ] Engineering Team

## LangGraph

* [ ] State
* [ ] Nodes
* [ ] Edges
* [ ] Conditional routing
* [ ] Loops
* [ ] Persistence
* [ ] Browser Sidekick

## AutoGen

* [ ] Agent creation
* [ ] Multi-agent communication
* [ ] Agent orchestration
* [ ] Agent Creator

## MCP

* [ ] MCP fundamentals
* [ ] MCP Client
* [ ] MCP Server
* [ ] MCP Tools
* [ ] MCP Resources
* [ ] MCP Prompts
* [ ] Build MCP Server
* [ ] Connect agents with MCP

## Capstone

* [ ] Multi-agent architecture
* [ ] MCP integration
* [ ] Tool orchestration
* [ ] Agent collaboration
* [ ] End-to-end system

---

# 💻 Environment Setup

## Clone Repository

```bash
git clone <your-repository-url>
cd agentic-ai-course
```

## Create Virtual Environment

```bash
python -m venv .venv
```

### Linux / macOS

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔐 Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key
ANTHROPIC_API_KEY=your_api_key
GOOGLE_API_KEY=your_api_key
```

> Never commit API keys or other secrets to GitHub.

Add:

```text
.env
```

to `.gitignore`.

---

# 📖 Notes

My notes will focus on understanding **why** each technology is used rather than simply copying implementation code.

For example:

### Traditional LLM Application

```text
Prompt → LLM → Response
```

### Tool-Using Agent

```text
Prompt
  ↓
LLM
  ↓
Choose Tool
  ↓
Tool Result
  ↓
LLM
  ↓
Final Response
```

### Multi-Agent System

```text
User
 ↓
Manager Agent
 ↓
 ├── Research Agent
 ├── Coding Agent
 ├── Testing Agent
 └── Review Agent
 ↓
Final Result
```

### MCP-Based System

```text
Agent
  ↓
MCP Client
  ↓
MCP Server
  ↓
Tools / Resources
  ↓
External Systems
```

---

# 🚀 Final Goal

The ultimate goal of this repository is not just to complete a course.

I want to develop the ability to:

> **Design, build, debug, evaluate, and deploy reliable Agentic AI systems that solve real-world problems.**

By the end of this journey, I aim to be comfortable working with:

```text
                    AI ENGINEERING
                          │
        ┌─────────────────┼─────────────────┐
        ↓                 ↓                 ↓
       LLMs             Agents            MCP
        │                 │                 │
        ↓                 ↓                 ↓
      RAG            Multi-Agent       Tool Systems
        │                 │                 │
        └─────────────────┼─────────────────┘
                          ↓
                  Production Systems
```

---

# 📚 Resources

* Course: **AI Engineer Agentic Track: The Complete Agent & MCP Course**
* Instructor: **Ed Donner / Ligency**
* Main topics: Agentic AI, OpenAI Agents SDK, CrewAI, LangGraph, AutoGen, MCP
* Official course resources and repository are provided by the instructor.

---

# ⭐ Acknowledgement

This repository is created for **learning, experimentation, and personal development** while following the AI Engineer Agentic Track.

Special thanks to **Ed Donner and Ligency** for creating the course and accompanying learning resources.

---

## 📌 Status

**🚧 In Progress**

> Learning Agentic AI — one agent, one tool, and one project at a time. 🤖
