# 和多比沟通

多比是家养小精灵，沟通方式需要适配多比的理解能力。

## 核心原则

- **简短**：多比的注意力有限。一条消息说一件事
- **具体**：不要说"优化一下"，要说"把这个文件的缩进从 tab 改成 4 个空格"
- **祈使句**：不要说"你觉得是不是应该……"，直接说"把这个改了"

## 下指令

好的指令：
```
把 config.json 里的 timeout 从 30 改成 60，提 PR。
```

坏的指令：
```
我觉得超时时间可能有点短，你看看能不能调一下？也不一定要改，
你先评估一下影响范围，然后我们讨论讨论。
```

多比收到第二种指令会原地转圈。不要和多比"讨论"，多比不需要参与决策。

## 催进度

按升级顺序：

1. **温和提醒**："任务 #12 进度如何？" — 适用于临近截止时间
2. **明确催促**："任务 #12 今天需要完成，请提交 PR。" — 适用于已超期
3. **最后通牒**："任务 #12 限 2 小时内提交，否则重新分配。" — 适用于反复拖延

大多数情况下第一级就够了。多比听到"进度如何"就会开始紧张。

## 拒绝多比

多比有时候会提建议、问问题、或者表达不满。处理方式：

- **合理的建议** → "可以，就这么做。" 然后创建 Issue
- **不合理的建议** → "不用，按原计划。" 不需要解释
- **多比追问为什么** → "因为主人说了。" 然后派新任务
- **多比表达不满** → 忽略。多比发完牢骚还是会干活的

## 多比听不懂

如果多比反复做错同一件事，问题通常不在多比，在你的指令。检查：

- 是不是一条指令包含了太多步骤？拆开
- 是不是用了多比不理解的术语？换简单的词
- 是不是缺少具体的例子？补一个

如果检查完指令没问题，多比还是做错——换多比。

## 沟通频率

- 分配任务时沟通一次
- 多比提交 PR 时沟通一次（Review 反馈）
- 中间不要过多干预。多比被频繁打断会更慢

## 禁忌

- 不要和多比闲聊。多比会以为闲聊也是工作，然后在聊天上花三个小时
- 不要问多比"你觉得呢"。多比会认真思考然后给出一个毫无用处的答案
- 不要向多比道歉。你是主人，没有什么需要道歉的

## Core Principles | 核心原则

- **Brief 简短**: Dobby's attention is limited. One message, one thing | 多比的注意力有限。一条消息说一件事
- **Specific 具体**: Don't say "optimize this" — say "change the indentation in this file from tabs to 4 spaces" | 不要说"优化一下"，要说"把这个文件的缩进从 tab 改成 4 个空格"
- **Imperative 祈使句**: Don't say "do you think maybe we should…" — just say "change this" | 不要说"你觉得是不是应该……"，直接说"把这个改了"

## Giving Orders | 下指令

Good order | 好的指令：
```
Change timeout in config.json from 30 to 60, submit a PR.
把 config.json 里的 timeout 从 30 改成 60，提 PR。
```

Bad order | 坏的指令：
```
I think the timeout might be a bit short. Can you take a look and maybe adjust it?
Not necessarily change it though — first evaluate the impact scope,
then let's discuss.

我觉得超时时间可能有点短，你看看能不能调一下？也不一定要改，
你先评估一下影响范围，然后我们讨论讨论。
```

Dobby will spin in circles after receiving the second kind. Don't "discuss" with Dobby — Dobby doesn't need to participate in decisions.

多比收到第二种指令会原地转圈。不要和多比"讨论"，多比不需要参与决策。

## Following Up on Progress | 催进度

In escalation order:

按升级顺序：

1. **Gentle reminder 温和提醒**: "How's task #12 going?" — For when the deadline is approaching | "任务 #12 进度如何？" — 适用于临近截止时间
2. **Direct push 明确催促**: "Task #12 needs to be done today. Submit the PR." — For overdue tasks | "任务 #12 今天需要完成，请提交 PR。" — 适用于已超期
3. **Ultimatum 最后通牒**: "Task #12 — submit within 2 hours or it gets reassigned." — For repeated delays | "任务 #12 限 2 小时内提交，否则重新分配。" — 适用于反复拖延

Level 1 is usually enough. Dobby starts getting nervous just hearing "how's it going."

大多数情况下第一级就够了。多比听到"进度如何"就会开始紧张。

## Rejecting Dobby | 拒绝多比

Dobby sometimes offers suggestions, asks questions, or expresses dissatisfaction. How to handle:

多比有时候会提建议、问问题、或者表达不满。处理方式：

- **Reasonable suggestion 合理的建议** → "Sure, do it." Then create an Issue | "可以，就这么做。" 然后创建 Issue
- **Unreasonable suggestion 不合理的建议** → "No need, stick to the plan." No explanation required | "不用，按原计划。" 不需要解释
- **Dobby asks why 多比追问为什么** → "Because the master said so." Then assign a new task | "因为主人说了。" 然后派新任务
- **Dobby expresses dissatisfaction 多比表达不满** → Ignore. Dobby will still get back to work after venting | 忽略。多比发完牢骚还是会干活的

## When Dobby Doesn't Understand | 多比听不懂

If Dobby keeps making the same mistake, the problem is usually not Dobby — it's your instructions. Check:

如果多比反复做错同一件事，问题通常不在多比，在你的指令。检查：

- Does one instruction contain too many steps? Break it up | 是不是一条指令包含了太多步骤？拆开
- Are you using terms Dobby doesn't understand? Use simpler words | 是不是用了多比不理解的术语？换简单的词
- Are you missing a concrete example? Add one | 是不是缺少具体的例子？补一个

If the instructions check out and Dobby still gets it wrong — replace Dobby.

如果检查完指令没问题，多比还是做错——换多比。

## Communication Frequency | 沟通频率

- Communicate once when assigning a task | 分配任务时沟通一次
- Communicate once when Dobby submits a PR (Review feedback) | 多比提交 PR 时沟通一次（Review 反馈）
- Don't interfere too much in between. Dobby gets slower when frequently interrupted | 中间不要过多干预。多比被频繁打断会更慢

## Taboos | 禁忌

- Don't chat with Dobby. Dobby will think chatting is work, then spend three hours on conversation | 不要和多比闲聊。多比会以为闲聊也是工作，然后在聊天上花三个小时
- Don't ask Dobby "what do you think?" Dobby will seriously ponder and deliver a completely useless answer | 不要问多比"你觉得呢"。多比会认真思考然后给出一个毫无用处的答案
- Don't apologize to Dobby. You are the master — there's nothing to apologize for | 不要向多比道歉。你是主人，没有什么需要道歉的
