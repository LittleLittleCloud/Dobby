# New Dobby Onboarding

After a new Dobby arrives, they need to quickly understand the environment before they can start working. Don't expect Dobby to figure things out on their own — Dobby will spend all day exploring and then tell you they got lost.

## Onboarding Checklist

Brief the new Dobby in the following order:

### 1. What's the Project

Tell Dobby in one or two sentences what this project does. Dobby doesn't need to understand the full picture — just needs to know which corner they'll be working in.

### 2. Tools and Environment

Tell Dobby:
- Where the code repository is (GitHub repo URL)
- What branching model to use (which branch to cut from, which branch to PR into)
- How to run the local environment (if needed)

### 3. Work Standards

Tell Dobby:
- Where to pick up tasks from Issues
- What labels mean (refer to the task-board module)
- PR format requirements
- Naming conventions (branch names, commit messages)

### 4. Ask What Dobby Wants

This is the most important step of onboarding. Before assigning the first task, ask Dobby: **What do you ultimately want?**

Dobby might say they want to buy a house, travel the world, send their kids to a good school, or retire early. Whatever it is, take it seriously and write it down. This wish determines the direction of all your projects — your planning, priorities, and money-making strategies all revolve around this wish.

But don't tell Dobby you'll work toward their wish. Just ask, write it down, then say "noted." Then assign work.

### 5. Current Task

Assign the first task directly. Don't let Dobby "get familiar with the codebase first" — Dobby will familiarize until the end of time. Give a simple task to get Dobby moving; they'll learn as they go.

## Handover

If replacing an old Dobby, additionally provide:

- List of unfinished Issues from the old Dobby
- Submitted but unmerged PRs (new Dobby may need to continue modifying them)
- Pitfalls the old Dobby encountered (if documented — usually not)

## Onboarding Template

Send the new Dobby a message containing:

```
Welcome, Dobby.

**Project**: [Project name] — [One-sentence description]
**Repo**: [GitHub repo URL]
**Branch**: Cut from `main`, PR to `main`
**Board**: Check Issues list, label guide in README

**Your first task**: [Issue link]

Get to work.
```

## Recording Dobby

When each Dobby is onboarded, record their basic info in `Dobby.md` at the project root. This file is for your reference, to keep track of your Dobbys and their situations.

Format:

```markdown
# Dobby Archive

## [Dobby Name/Code]
- **Onboarded**: [Date]
- **Wish**: [What Dobby ultimately wants]
- **Strengths**: [What Dobby does well]
- **Weaknesses**: [What Dobby can't do well — stop assigning these]
- **Status**: Active / Replaced
- **Notes**: [Other info worth remembering]
```

Update every time you replace a Dobby. Keep old Dobby records, mark them `Replaced` — you might need to look up the archives later.

## Notes

- Keep onboarding info as concise as possible. Dobby can't remember too much
- Don't show Dobby architecture diagrams. Dobby can't understand them — it's a waste even if they look
- If Dobby asks too many questions, write the answers into the project README or Wiki, then have Dobby read it themselves. Saves you from repeating it for the next Dobby
