<div align="center">

  # agentskills

  **AI Agent Skill Prompts & Configuration**

  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![GitHub stars](https://img.shields.io/github/stars/aaronaalmendarez/agentskills?style=social)](https://github.com/aaronaalmendarez/agentskills/stargazers)
  [![GitHub forks](https://img.shields.io/github/forks/aaronaalmendarez/agentskills?style=social)](https://github.com/aaronaalmendarez/agentskills/network/members)

</div>

---

## Overview

A curated collection of system prompts and configurations designed to enhance AI agent behavior. These prompts are engineered to reduce common failure modes like instruction drift, hallucination, and inconsistent output quality.

## What's Inside

### gemini/GEMINI.md — Code Sovereign

A rigorously-designed system prompt that transforms AI coding assistance through:

- **Spec-Lock Protocol** — Explicit requirement restatement before any work begins
- **Plan-First Workflow** — Ordered, testable steps with clear checkpoints
- **Self-Review Mandate** — Internal verification before finalization
- **Minimal Patch Discipline** — Smallest possible changes that accomplish the goal
- **Context Hygiene** — Session summaries for long-running conversations

#### What It Fixes

| Problem | Solution |
|---------|----------|
| Instruction drift | Binding requirements, no creativity creep |
| Hallucinated APIs | Ask or state assumptions explicitly |
| Over-refactoring | Preserve existing patterns and style |
| Inconsistent output | Deterministic coding standards |
| Scope collapse | Step-by-step execution with checkpoints |

#### Output Format

Every coding response follows a strict structure:

```
A) SPEC LOCK
B) PLAN
C) PATCH
D) VERIFY
E) SELF-REVIEW
F) NEXT (if needed)
```

---

## Installation

```bash
git clone https://github.com/aaronaalmendarez/agentskills.git
cd agentskills
```

## Usage

Load `gemini/GEMINI.md` as a system prompt when working with compatible AI models.

## Contributing

Feel free to submit issues and pull requests.

## License

MIT © 2026 [aaronaalmendarez](https://github.com/aaronaalmendarez)
