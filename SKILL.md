---
name: a-tool-that-generates-language-specific
description: A tool that generates language-specific .gitignore files. Given a language, framework, or tool name, it pro...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: A tool that generates language-specific .gitignore files. Given a language, framework, or tool name, it produces a comprehensive .gitignore with annotated sections explaining each pattern.

# Context
Should support at least 20 common languages/frameworks. Can combine multiple targets (e.g., 'node,macos,vscode').

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: pragmatic-builder description: A builder that generates Agent Skills with a practical focus — one script, inline smoke tests, and usage examples embedded in the SKILL.md. version: 0.1.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.