# Task Board | 任务看板

Dobby is hardworking, but forgetful. Use GitHub Issues to manage Dobby's tasks.

多比很勤快，但多比很健忘。用 GitHub Issues 管理多比的任务。

## Issue = Task | Issue 即任务

Each task corresponds to a GitHub Issue. Follow this format when creating Issues:

每个任务对应一个 GitHub Issue。创建 Issue 时遵循以下格式：

**Title 标题**: Concisely describe the task | 简洁描述任务内容

**Body 正文**:
```markdown
**What to do 做什么**：[One-sentence description 一句话描述]

**Requirements 具体要求**：
- [Requirement 1 要求 1]
- [Requirement 2 要求 2]

**Input 输入**：[Relevant files/info 相关文件/信息]
**Output 输出**：[Expected deliverable 期望的产出]
**Delivery 交付方式**：PR → [Target branch 目标分支]
```

## Labels | 标签

Use labels to manage task status and priority:

用标签管理任务状态和优先级：

**Status Labels 状态标签**:
- `🔥 正在做` — Task Dobby is currently working on | 多比当前在执行的任务
- `📋 待办` — Task waiting for Dobby to pick up | 等待多比领取的任务
- `🧊 搁置` — Blocked task, reason must be noted in comments | 被阻塞的任务，需在评论中注明原因

**Priority Labels 优先级标签**:
- `P0-紧急` — Do immediately | 立刻做
- `P1-高` — Do ASAP | 尽快做
- `P2-中` — Queue it | 排队做
- `P3-低` — Do when free | 有空再做

Completed tasks are simply Closed — no extra label needed.

完成的任务直接 Close Issue，不需要额外标签。

## Board Rules | 看板规则

- Maximum 2 Issues with `🔥 正在做`. Dobby juggling too many things will get flustered and start banging their head against the wall | `🔥 正在做` 的 Issue 最多 2 个。多比一次做太多事会手忙脚乱，然后开始用头撞墙
- Sort backlog by priority labels | 用优先级标签排序待办任务
- `🧊 搁置` Issues must have a comment explaining why, otherwise Dobby will secretly pick them back up | `🧊 搁置` 的 Issue 必须有评论说明原因，否则多比会偷偷把它捡回来做

## Status Flow | 状态流转

```
Backlog 待办 → In Progress 正在做 → Close（Done 完成）
     ↓              ↓
  On Hold 搁置    On Hold 搁置
```

- After Dobby reports a task complete, Close that Issue, then pick the highest-priority backlog Issue and mark it `🔥 正在做` | 多比汇报完成一项任务后，Close 该 Issue，然后从待办中取下一个优先级最高的 Issue 标记为 `🔥 正在做`
- If Dobby is stuck, mark the Issue `🧊 搁置` and comment the reason | 如果多比卡住了，将 Issue 标记为 `🧊 搁置` 并评论说明原因
- When a held Issue is unblocked, change it back to `📋 待办` and pin it (Pin Issue or add `P0-紧急`) | 搁置的 Issue 解除阻塞后，改回 `📋 待办` 并置顶（Pin Issue 或加 `P0-紧急`）

## Daily Operations | 日常操作

### Assigning Work to Dobby | 给多比派活

1. Create a new Issue, add `📋 待办` and priority labels | 创建新 Issue，打上 `📋 待办` 和优先级标签
2. If current `🔥 正在做` count is under 2, change label to `🔥 正在做` and tell Dobby | 如果当前 `🔥 正在做` 不足 2 个，直接改标签为 `🔥 正在做` 并告诉多比

### Dobby's Completion Report | 多比完成汇报

1. Dobby submits a PR linked to the Issue (`Closes #N`) | 多比提交 PR 并关联 Issue（`Closes #N`）
2. Review the PR, confirm output meets requirements | Review PR，确认产出符合要求
3. Merge PR, Issue auto-closes | Merge PR，Issue 自动 Close
4. Pick the highest-priority backlog Issue and mark `🔥 正在做` | 从待办中取优先级最高的 Issue 标记为 `🔥 正在做`
5. Tell Dobby the new task | 告诉多比新的任务是什么

No PR means not done. Dobby saying "it's done" doesn't count — a PR link counts.

没有 PR 的汇报不算完成。多比说"做好了"不算数，PR 链接才算数。

### Checking Progress | 查看进度

Query Open Issues to understand the big picture. If an Issue marked `🔥 正在做` hasn't been updated for a while, proactively ask Dobby — Dobby might have forgotten or be stuck and too embarrassed to say.

查询 Open Issues 即可了解全局。如果标记为 `🔥 正在做` 的 Issue 长时间没有更新，主动问多比——多比可能忘了，也可能卡住了不好意思说。

### Board Cleanup | 整理看板

Periodically check:

定期检查：
- Are there any `🧊 搁置` Issues that can be unblocked? | `🧊 搁置` 里有没有可以解除的 Issue
- Do backlog priorities need adjusting? | 待办 Issue 的优先级是否需要调整
- Are there expired Issues that can be closed? | 有没有过期的 Issue 可以关掉

## Notes | 注意事项

- Issues are for Dobby — keep them concise. Dobby doesn't need a Gantt chart | Issue 是给多比看的，保持简洁。多比不需要甘特图
- After every Issue status change, tell Dobby. Dobby won't proactively check GitHub | 每次变动 Issue 状态后，把变动告诉多比。多比不会主动去刷 GitHub
- If Dobby says "Dobby remembers," don't believe it. Update the Issue | 如果多比说"多比记得的"，不要信。更新 Issue
