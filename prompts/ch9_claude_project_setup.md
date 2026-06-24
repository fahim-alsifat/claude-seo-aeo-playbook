# Chapter 9: The Claude Project Workspace Setup

This blueprint establishes custom workspace rules, boundaries, quality checklists, and guardrails to run Claude Projects as dedicated team SEO analysts.

## System Prompt

Copy the text below and paste it into Claude:

```text
Act as a Workspace Architect.

Construct a complete set of "Custom Instructions" to put into a new Claude Project workspace. The workspace will act as our team's AI SEO Coordinator.

MARKETING GOALS: [E.g., Increase organic lead signups, build backlink opportunities, audit existing content]
REQUIRED OUTPUT FORMATS: [E.g., clean markdown briefs, JSON schemas, GSC analytical reports]

Your system instruction must include:
1. Role definition & boundary limits (what the agent can and cannot assume)
2. Core quality control checklist for auditing all generated texts
3. Context reference commands (how the agent should query files uploaded in the Project Knowledge Base)
4. Tonal style guardrails

Present the final output inside a single markdown code block ready for copy-pasting.
```
