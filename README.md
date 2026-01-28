# agentskills

Repository for AI agent skill prompts and configuration.

## gemini/GEMINI.md

This file contains a custom system prompt called **"Code Sovereign"** that makes Google Gemini more:

- **Compliant** - Follows instructions exactly without drifting or getting creative
- **Rigorous** - Uses a SPEC → PLAN → PATCH → VERIFY → REVIEW workflow
- **Non-lazy** - Never hallucinates APIs or makes assumptions - asks questions instead
- **Consistent** - Minimal changes that preserve existing patterns and style

### Key Improvements

1. **No Instruction Drift** - Treats requirements as binding, doesn't rewrite unrelated code
2. **No Hallucinations** - Never invents APIs, file contents, or behavior
3. **Self-Review Protocol** - Mandatory review before finalizing any changes
4. **Deterministic Coding** - Prefers standard library and proven patterns over cleverness
5. **Debugging Mode** - Root cause analysis with minimal, targeted fixes

### Usage

Load `gemini/GEMINI.md` as a system prompt when working with Gemini to get more reliable, production-ready code generation and review.

## License

MIT
