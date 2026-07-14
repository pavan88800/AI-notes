# AI Workflow for Saving Tokens and Managing Large Tasks

## Core Principle

Instead of repeatedly explaining the full requirements in every prompt:

1. Create a detailed plan in a Markdown (`.md`) file.
2. Review and modify the plan until it matches your exact requirements.
3. Ask the AI to execute the plan step by step.
4. Continue referencing the same Markdown file throughout the session.

This approach drastically reduces token usage and keeps work organized.

---

# Why This Works

When you do **not** use a plan file:

- You repeat the same context many times.
- The AI reprocesses all requirements in every prompt.
- More tokens are consumed.
- Responses may become inconsistent.

When you use a Markdown plan:

- Requirements are defined once.
- Future prompts are short.
- The AI follows a stable source of truth.
- You save a significant number of tokens.

---

# Standard Workflow

## Step 1: Generate the Plan

Prompt:

```text
Create a detailed implementation plan and save it as `project-plan.md`.
```
