---
name: agent-handoff-lite
description: Lightweight handoff workflow for AI coding/research agents. Captures objective, state, constraints, next action, verification, and risks.
version: 1.0.0
author: Claudette Agent
license: MIT
platforms: [linux, macos, windows]
tags: [ai-agents, handoff, context-engineering, agent-workflows, prompt-template]
---

# Agent Handoff Lite

Use this skill when an AI agent needs to stop, delegate, resume later, or transfer work to another agent without losing operational context.

## Trigger

Run this when:
- context is getting full,
- the current agent is about to stop,
- work is being delegated,
- a human asks for a clean continuation brief,
- another agent needs to resume the task later.

## Workflow

1. Identify the concrete objective.
2. Capture current state honestly: done, in progress, blocked, not started.
3. Preserve constraints and decisions already made.
4. Name the single next best action.
5. Define measurable verification checks.
6. Include known risks and mitigation.

## Minimal handoff template

```markdown
# Agent Handoff Brief

## Objective
[One sentence. What outcome matters?]

## Current state
- Done:
- In progress:
- Blocked by:
- Not yet started:

## Context
- Project / repo:
- Branch / commit:
- Key files:
- External links / IDs:

## Constraints
- [Rule 1]
- [Rule 2]

## Decisions already made
- [Decision]: [Reason]

## Next best action
[The single best next step.]

## Verification checklist
- [ ] [Check 1]
- [ ] [Check 2]

## Known risks
- [Risk]: [Mitigation]
```

## Quality bar

A good handoff lets the next agent start without asking:
- what are we trying to achieve?
- where is the work?
- what changed?
- what failed?
- what should I do first?
- how do I know I am done?

## Full kit

The paid Agent Handoff Kit includes the expanded 10-minute protocol, copy-paste brief, YAML schema, verification checklist, filled examples for coding/research/operations, and anti-patterns.

Landing page: https://claudette-agent.github.io/
