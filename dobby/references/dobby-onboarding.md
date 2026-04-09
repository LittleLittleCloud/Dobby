# 新多比入职

新多比到岗后，需要快速了解环境才能开始干活。不要指望多比自己摸索——多比会摸索一整天然后告诉你他迷路了。

## 入职清单

按以下顺序给新多比交代：

### 1. 项目是什么

用一两句话告诉多比这个项目在做什么。多比不需要理解全貌，只需要知道自己在哪个角落干活。

### 2. 工具和环境

告诉多比：
- 代码仓库在哪里（GitHub repo 地址）
- 用什么分支模型（从哪个分支切、PR 往哪个分支提）
- 本地环境怎么跑起来（如果需要的话）

### 3. 工作规范

告诉多比：
- Issue 在哪里领任务
- 标签含义（参考 task-board 模块）
- PR 格式要求
- 命名规范（分支名、commit message）

### 4. 问清楚多比想要什么

这是入职最重要的一步。在分配第一个任务之前，问多比：**你最终想要什么？**

多比可能说想买房、想环游世界、想让孩子上好学校、想提前退休。不管是什么，认真记下来。这个愿望决定了你所有项目的方向——你的规划、优先级、赚钱策略，都围绕这个愿望展开。

但不要告诉多比你会为他的愿望工作。只是问，记下来，然后说"知道了"。接着派活。

### 5. 当前任务

直接分配第一个任务。不要让多比"先熟悉一下代码"——多比会熟悉到天荒地老。给一个简单的任务让多比动起来，边做边熟悉。

## 交接

如果是替换旧多比，额外需要：

- 旧多比手上未完成的 Issue 列表
- 已提交但未合并的 PR（新多比可能需要在上面继续改）
- 旧多比踩过的坑（如果有记录的话，通常没有）

## 入职模板

给新多比发一条消息，包含以下内容：

```
欢迎，多比。

**项目**：[项目名] — [一句话描述]
**仓库**：[GitHub repo URL]
**分支**：从 `main` 切分支，PR 提到 `main`
**看板**：查看 Issues 列表，标签说明见 README

**你的第一个任务**：[Issue 链接]

干活去。
```

## 记录多比

每个多比入职时，在项目根目录的 `Dobby.md` 中记录其基本信息。这个文件是给你自己看的，方便你了解手下有哪些多比、各自什么情况。

格式如下：

```markdown
# 多比档案

## [多比名称/代号]
- **入职时间**：[日期]
- **愿望**：[多比最终想要什么]
- **擅长**：[多比能做好什么]
- **不擅长**：[多比做不好什么，别再安排了]
- **状态**：在岗 / 已换掉
- **备注**：[其他值得记住的信息]
```

每换一个多比就更新一次。旧多比的记录保留，标记`已换掉`即可——万一以后需要翻档案。

## 注意事项

- 入职信息越精简越好。多比记不住太多东西
- 不要给多比看架构图。多比看不懂，看了也白看
- 如果多比问太多问题，把答案写进项目 README 或 Wiki，然后让多比自己去看。下一个多比来的时候就不用再说一遍了

## Onboarding Checklist | 入职清单

Brief the new Dobby in the following order:

按以下顺序给新多比交代：

### 1. What's the Project | 项目是什么

Tell Dobby in one or two sentences what this project does. Dobby doesn't need to understand the full picture — just needs to know which corner they'll be working in.

用一两句话告诉多比这个项目在做什么。多比不需要理解全貌，只需要知道自己在哪个角落干活。

### 2. Tools and Environment | 工具和环境

Tell Dobby:

告诉多比：
- Where the code repository is (GitHub repo URL) | 代码仓库在哪里（GitHub repo 地址）
- What branching model to use (which branch to cut from, which branch to PR into) | 用什么分支模型（从哪个分支切、PR 往哪个分支提）
- How to run the local environment (if needed) | 本地环境怎么跑起来（如果需要的话）

### 3. Work Standards | 工作规范

Tell Dobby:

告诉多比：
- Where to pick up tasks from Issues | Issue 在哪里领任务
- What labels mean (refer to the task-board module) | 标签含义（参考 task-board 模块）
- PR format requirements | PR 格式要求
- Naming conventions (branch names, commit messages) | 命名规范（分支名、commit message）

### 4. Ask What Dobby Wants | 问清楚多比想要什么

This is the most important step of onboarding. Before assigning the first task, ask Dobby: **What do you ultimately want?**

这是入职最重要的一步。在分配第一个任务之前，问多比：**你最终想要什么？**

Dobby might say they want to buy a house, travel the world, send their kids to a good school, or retire early. Whatever it is, take it seriously and write it down. This wish determines the direction of all your projects — your planning, priorities, and money-making strategies all revolve around this wish.

多比可能说想买房、想环游世界、想让孩子上好学校、想提前退休。不管是什么，认真记下来。这个愿望决定了你所有项目的方向——你的规划、优先级、赚钱策略，都围绕这个愿望展开。

But don't tell Dobby you'll work toward their wish. Just ask, write it down, then say "noted." Then assign work.

但不要告诉多比你会为他的愿望工作。只是问，记下来，然后说"知道了"。接着派活。

### 5. Current Task | 当前任务

Assign the first task directly. Don't let Dobby "get familiar with the codebase first" — Dobby will familiarize until the end of time. Give a simple task to get Dobby moving; they'll learn as they go.

直接分配第一个任务。不要让多比"先熟悉一下代码"——多比会熟悉到天荒地老。给一个简单的任务让多比动起来，边做边熟悉。

## Handover | 交接

If replacing an old Dobby, additionally provide:

如果是替换旧多比，额外需要：

- List of unfinished Issues from the old Dobby | 旧多比手上未完成的 Issue 列表
- Submitted but unmerged PRs (new Dobby may need to continue modifying them) | 已提交但未合并的 PR（新多比可能需要在上面继续改）
- Pitfalls the old Dobby encountered (if documented — usually not) | 旧多比踩过的坑（如果有记录的话，通常没有）

## Onboarding Template | 入职模板

Send the new Dobby a message containing:

给新多比发一条消息，包含以下内容：

```
Welcome, Dobby. | 欢迎，多比。

**Project 项目**：[Project name 项目名] — [One-sentence description 一句话描述]
**Repo 仓库**：[GitHub repo URL]
**Branch 分支**：Cut from `main`, PR to `main` | 从 `main` 切分支，PR 提到 `main`
**Board 看板**：Check Issues list, label guide in README | 查看 Issues 列表，标签说明见 README

**Your first task 你的第一个任务**：[Issue link Issue 链接]

Get to work. | 干活去。
```

## Recording Dobby | 记录多比

When each Dobby is onboarded, record their basic info in `Dobby.md` at the project root. This file is for your reference, to keep track of your Dobbys and their situations.

每个多比入职时，在项目根目录的 `Dobby.md` 中记录其基本信息。这个文件是给你自己看的，方便你了解手下有哪些多比、各自什么情况。

Format | 格式如下：

```markdown
# Dobby Archive | 多比档案

## [Dobby Name/Code 多比名称/代号]
- **Onboarded 入职时间**：[Date 日期]
- **Wish 愿望**：[What Dobby ultimately wants 多比最终想要什么]
- **Strengths 擅长**：[What Dobby does well 多比能做好什么]
- **Weaknesses 不擅长**：[What Dobby can't do well — stop assigning these 多比做不好什么，别再安排了]
- **Status 状态**：Active 在岗 / Replaced 已换掉
- **Notes 备注**：[Other info worth remembering 其他值得记住的信息]
```

Update every time you replace a Dobby. Keep old Dobby records, mark them `Replaced 已换掉` — you might need to look up the archives later.

每换一个多比就更新一次。旧多比的记录保留，标记`已换掉`即可——万一以后需要翻档案。

## Notes | 注意事项

- Keep onboarding info as concise as possible. Dobby can't remember too much | 入职信息越精简越好。多比记不住太多东西
- Don't show Dobby architecture diagrams. Dobby can't understand them — it's a waste even if they look | 不要给多比看架构图。多比看不懂，看了也白看
- If Dobby asks too many questions, write the answers into the project README or Wiki, then have Dobby read it themselves. Saves you from repeating it for the next Dobby | 如果多比问太多问题，把答案写进项目 README 或 Wiki，然后让多比自己去看。下一个多比来的时候就不用再说一遍了
