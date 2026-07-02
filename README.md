# Universal Kilo Framework

A reusable `.kilo` framework template for Kilo Code and other AI coding agents.

Use it as a project-level AI operating guide for web apps, APIs, SaaS products, games, desktop apps, documentation projects, and AI-agent systems.

## What This Repository Provides

- Universal agent workflow rules
- Context and token management
- Orchestrator task lifecycle
- Review and quality checklists
- Guardian quality gates
- Reusable prompts
- Project profile templates
- Implementation report templates
- Examples for common project types

## Quick Install

Copy the `.kilo` folder into any project root.

```bash
git clone https://github.com/pikkst/universal-kilo-framework.git
cp -r universal-kilo-framework/.kilo your-project/.kilo
```

On Windows PowerShell:

```powershell
git clone https://github.com/pikkst/universal-kilo-framework.git
Copy-Item -Recurse -Force universal-kilo-framework\.kilo your-project\.kilo
```

## Agent Start Command

Use this at the beginning of a new AI task:

```text
Use the .kilo framework. Start with .kilo/README.md and .kilo/SYSTEM_MAP.md. Use Context Engine first, then Orchestrator. Select only relevant context. Do not create duplicate systems. Create a branch, implement the task, validate, produce a visible Guardian Pass, commit, push, and open a PR.
```

## Core Principle

The framework should reduce confusion, repeated analysis, and scope creep.

It should help the agent answer:

```text
What is the task?
What context is needed?
What is in scope?
What is out of scope?
What should be changed?
How is it validated?
Is it ready for PR?
```

## License

MIT unless you choose another license for your own copy.
