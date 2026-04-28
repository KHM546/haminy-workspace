# 课程大纲：如何用 AI 工具创建“需求设计与取舍”Skill 插件

## 一、课程定位

这门课不是教产品经理“如何临时问一次 AI”，而是教大家把一套可复用的需求分析、方案设计与取舍方法，沉淀成一个可以反复调用的 Skill。

这里的目标不是得到一份需求文档，而是得到一个可安装、可复用、可迭代的 AI 能力模块，后续可以作为：

- Codex Skill
- 本地插件中的 Skill
- 团队内部复用的标准化 AI 工作流

也就是说，这门课讲的是：

- 如何把产品经理的方法论整理成 AI 可执行的技能说明
- 如何让 AI 在固定边界内稳定地产出需求设计与取舍结果
- 如何把零散 prompt 升级成可沉淀、可复制、可维护的 Skill
- 如何从 0 到 1 做出自己的第一个 Skill，并逐轮迭代到可用
- 如何站在别人已有 Skill 的基础上做定制化改造，而不是每次都从零开始

---

## 二、课程名称

如何用 AI 工具创建“需求设计与取舍”Skill 插件：产品经理方法沉淀实战课

可选副标题：

- 从 prompt 到 Skill：把需求设计方法沉淀成可复用 AI 能力
- 如何为产品经理打造一个“需求设计与取舍”专属 Skill

---

## 三、课程目标

这门课控制在 40 分钟，目标不是讲完整插件开发，而是让学员掌握从 prompt 到 Skill 的最小可用闭环。

学完后，学员应能完成以下事情：

1. 讲清楚 prompt、Skill、插件三者的区别
2. 把“需求设计与取舍”的流程拆成可复用步骤
3. 写出一个基础版 `SKILL.md`
4. 写清楚这个 Skill 的输入、输出和约束
5. 带走一版后续可以继续迭代的 Skill 初稿

---

## 四、适合对象

- 希望把自己的产品方法论沉淀为 AI 工具能力的产品经理
- 想用 Codex、ChatGPT、Claude 等工具做标准化需求分析的人
- 想做团队内部 AI 工作流、技能库、插件库的人
- 对 AI 提效不满足于“问答”，想做“可复用技能资产”的同学

---

## 五、课程核心产出

课程结束时，每位学员至少应产出以下内容：

1. 一个 `SKILL.md` 初稿
2. 一套输入输出模板

建议补充产出：

3. 一句清晰的 Skill `description`
4. 一份 5 步 workflow 草稿

---

## 六、课程整体安排

### 1. 课程形式

本课程设计为 **1 节 40 分钟实战入门课**。

适用场景：

- 新人培训
- 部门内部分享
- AI Skill 入门工作坊

### 2. 时间安排

1. 第一部分：prompt、Skill、插件的区别，8 分钟
2. 第二部分：怎么把需求分析流程拆出来，10 分钟
3. 第三部分：怎么写一个基础 `SKILL.md`，15 分钟
4. 第四部分：现场收口与产出说明，7 分钟

### 3. 本节课讲什么

#### 第一部分：讲清 prompt、Skill、插件的区别

时长：8 分钟

要讲清的核心内容：

1. prompt 解决一次问题
2. Skill 解决一类问题
3. 插件组织多个能力
4. 为什么产品经理更适合先做 Skill，而不是一上来做插件

本段结论：

- prompt 是临时对话
- Skill 是可复用工作说明
- 插件是多个 Skill、脚本和配置的组织方式

---

#### 第二部分：怎么把需求分析流程拆出来

时长：10 分钟

要讲清的核心内容：

1. 从重复劳动开始找 Skill 选题
2. 先手工跑通，再让 AI 帮你封装
3. 一个 Skill 先只解决一个具体问题
4. “需求设计与取舍”可以拆成固定流程

固定流程：

1. 澄清
2. 定义
3. 发散
4. 对比
5. 结论

本段结论：

- 不先拆流程，后面写出来的 Skill 很容易失控
- 流程比措辞更重要

---

#### 第三部分：怎么写一个基础 `SKILL.md`

时长：15 分钟

要讲清的核心内容：

1. `SKILL.md` 的最小结构
2. `name` 和 `description` 分别负责什么
3. 为什么 `description` 是 Skill 能否被正确匹配的第一关
4. body 里至少要写清 workflow、输入、输出、约束
5. 第一版不要写太复杂，先把主流程写通

建议示例结构：

```md
---
name: requirement-design-tradeoff
description: Use when the user wants help turning a vague requirement or business problem into structured requirement clarification, option comparison, and tradeoff recommendations.
---

# Requirement Design and Tradeoff

## Use this skill when

- The user has a vague requirement
- The user needs structured requirement analysis
- The user wants multiple solution options and a recommendation

## Workflow

1. Clarify the request
2. Define the problem
3. Generate multiple options
4. Compare options
5. Give a recommendation

## Input requirements

- Business background
- User or target audience
- Current issue
- Goal
- Constraints

## Output format

- Requirement clarification
- Problem statement
- Options comparison
- Tradeoff recommendation
- Risks and open questions

## Constraints

- Do not jump directly to features before clarification
- Ask follow-up questions if key information is missing
- Provide at least 2 options
- Compare options by value, cost, and risk
```

本段结论：

- Skill 的基础不是写长，而是写清
- 写清输入、输出、约束，比堆很多漂亮话更重要

---

#### 第四部分：现场收口与产出说明

时长：7 分钟

要讲清的核心内容：

1. 这节课的最终产出是什么
2. 课后第一轮应该怎么补全自己的 Skill
3. 怎么用真实案例继续迭代

本段最终产出：

- 一个 `SKILL.md` 初稿
- 一套输入输出模板

课后建议动作：

1. 找一个你最近反复做的需求分析任务
2. 用这套结构补完你的第一版 Skill
3. 用 1 个真实需求测试一次

---

## 七、课程内容大纲

### 模块 1：prompt、Skill、插件的区别

#### 模块目标

让学员在最短时间内建立正确概念，不把 Skill 理解成“更长的 prompt”。

#### 核心内容

- prompt 解决一次问题
- Skill 解决一类问题
- 插件组织多个能力
- Skill 和插件的关系
- 为什么这一节课先做 Skill，不展开插件开发

#### 讲师要强调的结论

- prompt 是临时对话
- Skill 是可复用工作说明
- 插件是多个 Skill、脚本和配置的组织方式

---

### 模块 2：怎么把需求分析流程拆出来

#### 模块目标

让学员知道 Skill 不是凭空写出来的，而是从真实工作流程中抽象出来的。

#### 核心内容

- 从重复劳动开始找 Skill 选题
- 先手工跑通，再交给 AI 封装
- 一个 Skill 先只解决一个问题
- “需求设计与取舍”的 5 步流程

#### 固定流程

1. 澄清
2. 定义
3. 发散
4. 对比
5. 结论

#### 讲师要强调的结论

- 不先拆流程，Skill 很容易失控
- 流程比辞藻更重要

---

### 模块 3：怎么写一个基础 `SKILL.md`

#### 模块目标

让学员知道一个基础 Skill 至少要写清什么，现场能写出第一版结构。

#### 核心内容

- `SKILL.md` 的最小结构
- `name` 和 `description` 的作用
- body 中最少要写哪些内容
- 为什么第一版先写清输入、输出、约束

#### 最小结构建议

1. `name`
2. `description`
3. use when
4. workflow
5. input requirements
6. output format
7. constraints

#### 讲师要强调的结论

- Skill 的基础不是写长，而是写清
- 写清输入、输出、约束，比堆很多大段文字更重要

---

### 模块 4：现场产出与收口

#### 模块目标

让学员在 40 分钟结束时明确拿走什么，以及课后如何继续补完。

#### 核心内容

- 一个合格的基础版 Skill 初稿应该长什么样
- 输入模板和输出模板怎么写
- 课后如何用真实需求做第一轮测试

#### 本模块关键输出

- 一个 `SKILL.md` 初稿
- 一套输入输出模板
- 一句可用的 Skill `description`

---

## 八、课上可用案例

40 分钟版本建议只用 **1 个主案例 + 1 个备选案例**，重点不是讲业务本身，而是带大家走完“拆流程 -> 写 `SKILL.md` -> 产出模板”的最小闭环。

### 案例 1：活动报名转化率低

#### 原始输入

“活动报名页转化率太低了，帮我优化一下。”

#### 适合验证的能力

- 是否会先做澄清，而不是直接给页面方案
- 是否能把需求分析流程拆成 5 步
- 是否能写出对应的输入、输出和约束
- 是否能形成基础版 `SKILL.md`

#### 适合用于演示的模块

- 模块 2
- 模块 3
- 模块 4

---

### 案例 2：要不要加消息提醒功能

作为备选案例使用，当主案例大家已经比较熟悉时，可以用它来替换。

#### 原始输入

“运营想加一个消息提醒功能，提升用户活跃。”

#### 适合验证的能力

- 是否能把“加功能”改写成问题定义
- 是否能复用同一套 5 步流程
- 是否能验证 `description` 和模板是不是写得过泛或过窄

#### 适合用于演示的模块

- 模块 2
- 模块 3
- 模块 4

---

## 九、课程验收标准

### 1. 课堂验收标准

课程结束时，学员至少要完成以下 4 项中的 3 项：

1. 说清楚 prompt、Skill、插件的区别
2. 写出“澄清、定义、发散、对比、结论”这 5 步流程
3. 写出一版基础 `SKILL.md` 结构
4. 写出输入、输出、约束三部分的初稿

### 2. Skill 成果验收标准

一个合格的“需求设计与取舍”Skill，至少应满足以下要求：

- 能明确触发场景
- `description` 准确，AI 能较稳定匹配到
- 能要求先澄清后方案
- 能输出问题定义，而不是直接功能清单
- 能稳定给出至少 2 个可比较方案
- 能按照价值、成本、风险做取舍说明
- 能输出风险项与待确认项
- 不严重依赖讲师口头补充才能使用
- 一个 Skill 只解决一类核心问题，不贪大求全

### 3. 文档与结构验收标准

提交内容至少包含：

- `SKILL.md`
- 1 份输入模板
- 1 份输出模板

### 4. 评分建议

总分 100 分：

- 概念区分是否清楚：20 分
- 工作流拆解是否合理：25 分
- `SKILL.md` 是否完整可用：30 分
- 输入输出约束是否清楚：25 分

合格标准：

- 60 分及以上：可用于个人练习
- 80 分及以上：可用于日常工作
- 90 分及以上：可作为团队内部复用 Skill

---

## 十、课后作业设计

40 分钟版本建议只留 **1 个课后作业**，让大家课后补完第一版 Skill。

### 作业：补完你的第一版 Skill

#### 作业说明

请从你最近反复处理的一类需求中，选 1 个真实场景，按课堂上的结构补完一版“需求设计与取舍”Skill。

#### 提交内容

- 1 句 Skill description
- 5 步 workflow
- `name`
- use when
- workflow
- input requirements
- output format
- constraints

#### 验收重点

- 是否能把流程写清楚
- 是否写清输入、输出、约束
- 是否能围绕一类问题，而不是写成大而全说明书

---

## 十一、课程亮点

- 不是教“怎么提问 AI”，而是教“怎么造一个可复用 Skill”
- 不停留在 prompt 技巧，而是进入方法沉淀和能力产品化
- 直接贴近产品经理日常工作流
- 强调“先手工跑通，再交给 AI 封装”
- 强调 `description` 是 Skill 成败的第一关
- 强调“一个 Skill 解决一个问题”
- 强调“先改现成 Skill，再做私人版本”
- 课后可以形成真实可用的 AI 资产，而不是一次性笔记
- 适合后续扩展成团队内部插件、技能库或培训模板

---

## 十二、课程一句话介绍

这门课帮助产品经理把“需求设计与取舍”的经验方法，沉淀成一个可反复调用、可持续迭代、可放进 AI 工具中的 Skill 插件。

---

## 十三、标题页可直接使用文案

### 主标题

如何用 AI 工具创建“需求设计与取舍”Skill 插件

### 副标题

把产品经理的方法论沉淀成可复用的 AI 工作能力

### 开场说明

这门课不只是教你如何问 AI，而是教你如何把自己的需求分析方法做成一个可以长期复用的 Skill。
