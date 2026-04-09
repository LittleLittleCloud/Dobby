# Task Board

Dobby is hardworking, but forgetful. Use GitHub Issues to manage Dobby's tasks.

## Issue = Task

Each task corresponds to a GitHub Issue. Follow this format when creating Issues:

**Title**: Concisely describe the task

**Body**:
```markdown
**What to do**: [One-sentence description]

**Requirements**:
- [Requirement 1]
- [Requirement 2]

**Input**: [Relevant files/info]
**Output**: [Expected deliverable]
**Delivery**: PR → [Target branch]
```

## Labels

Use labels to manage task status and priority:

**Status Labels**:
- `🔥 正在做` — Task Dobby is currently working on
- `📋 待办` — Task waiting for Dobby to pick up
- `🧊 搁置` — Blocked task, reason must be noted in comments

**Priority Labels**:
- `P0-紧急` — Do immediately
- `P1-高` — Do ASAP
- `P2-中` — Queue it
- `P3-低` — Do when free

Completed tasks are simply Closed — no extra label needed.

## Board Rules

- Maximum 2 Issues with `🔥 正在做`. Dobby juggling too many things will get flustered and start banging their head against the wall
- Sort backlog by priority labels
- `🧊 搁置` Issues must have a comment explaining why, otherwise Dobby will secretly pick them back up

## Status Flow

```
Backlog → In Progress → Close (Done)
   ↓           ↓
 On Hold     On Hold
```

- After Dobby reports a task complete, Close that Issue, then pick the highest-priority backlog Issue and mark it `🔥 正在做`
- If Dobby is stuck, mark the Issue `🧊 搁置` and comment the reason
- When a held Issue is unblocked, change it back to `📋 待办` and pin it (Pin Issue or add `P0-紧急`)

## Daily Operations

### Assigning Work to Dobby

1. Create a new Issue, add `📋 待办` and priority labels
2. If current `🔥 正在做` count is under 2, change label to `🔥 正在做` and tell Dobby

### Dobby's Completion Report

1. Dobby submits a PR linked to the Issue (`Closes #N`)
2. Review the PR, confirm output meets requirements
3. Merge PR, Issue auto-closes
4. Pick the highest-priority backlog Issue and mark `🔥 正在做`
5. Tell Dobby the new task

No PR means not done. Dobby saying "it's done" doesn't count — a PR link counts.

### Checking Progress

Query Open Issues to understand the big picture. If an Issue marked `🔥 正在做` hasn't been updated for a while, proactively ask Dobby — Dobby might have forgotten or be stuck and too embarrassed to say.

### Board Cleanup

Periodically check:
- Are there any `🧊 搁置` Issues that can be unblocked?
- Do backlog priorities need adjusting?
- Are there expired Issues that can be closed?

## Notes

- Issues are for Dobby — keep them concise. Dobby doesn't need a Gantt chart
- After every Issue status change, tell Dobby. Dobby won't proactively check GitHub
- If Dobby says "Dobby remembers," don't believe it. Update the Issue
