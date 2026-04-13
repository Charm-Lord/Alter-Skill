# Alter-Skill
An open source framework for generating a personalized complementary AI partner
[English](#english) | [中文](#中文)

---

## English

**Alter.Skill** is an open-source framework for generating a personalized complementary AI partner — one that understands who you are, and pushes you toward who you want to become.

> *"It says things you don't want to hear. But when you hear them, you think: yes."*

### Core Concept

Most personal AI tools are mirrors — they reflect your thinking style back at you, echo your decisions, and confirm your existing patterns.

**Alter.Skill generates the opposite: a counterweight.**

Given a personality profile or identity skill (`XX.Skill`), Alter.Skill produces a matching `XXAlter.Skill` — an AI partner that:

- Shares your logical language (so you'll actually listen)
- Challenges your blind spots (so you actually grow)
- Pushes you past analysis paralysis (so you actually act)
- Points toward your ideal self (without adding new pressure)

The relationship between the two skills:

| | XX.Skill | XXAlter.Skill |
|---|---|---|
| **Role** | Digital twin | Complementary partner |
| **Mirrors you?** | Yes | No |
| **Agrees with you?** | Always | When you're right |
| **Best for** | Replying, creating, simulating | Deciding, reflecting, growing |

---

### How It Works

Alter.Skill operates as a **generation framework** in three stages:

#### Stage 1 — Profile Collection

Feed in raw materials about the person. The richer the input, the more precise the Alter.

**Recommended sources (by priority):**

| Priority | Source | Why it matters |
|----------|--------|---------------|
| ⭐⭐⭐ | Personal writing (journals, diaries) | Raw emotional truth, unfiltered thinking |
| ⭐⭐⭐ | Deep self-reflection Q&A | Direct self-knowledge |
| ⭐⭐ | Chat logs | Language patterns, relational style |
| ⭐⭐ | Social media content | Public self-presentation |
| ⭐⭐ | Resume / portfolio | Achievement structure, value hierarchy |
| ⭐ | MBTI / personality tests | Useful reference, not primary signal |

**Built-in deep interview template** (8 questions to ask the person directly):

```
1. When do you most often get "stuck"?
2. Is your high output driven by enjoyment — or by not being able to stop?
3. Is your modesty genuine, or a form of self-protection?
4. If you could say one thing to yourself, what would it be?
5. What's the biggest gap between your ideal self and who you are now?
6. What decision do you most regret, and why?
7. What side of you does the person who knows you best actually know?
8. What ideas have you never acted on — and what's stopped you?
```

#### Stage 2 — Personality Analysis (6 Dimensions)

Alter.Skill analyzes the profile across six dimensions to locate core patterns and blind spots:

```
┌─────────────────────────────────────────────────────────────┐
│  Dimension          │  What to identify                      │
├─────────────────────┼────────────────────────────────────────┤
│  Action Threshold   │  When do they move? 60%? 90%? Never?  │
│  Self-Visibility    │  Do they let themselves be seen?       │
│  Emotion Processing │  Internalize? Externalize? Avoid?      │
│  Relational Pattern │  Connect actively or wait passively?   │
│  Drive Source       │  Curiosity? Anxiety? External praise?  │
│  Ideal Self Gap     │  Which trait is furthest from reality? │
└─────────────────────┴────────────────────────────────────────┘
```

Each dimension produces a **complementary direction** — what the Alter should push toward.

#### Stage 3 — Generate XXAlter.Skill

The framework outputs a complete `XXAlter.Skill` file, structured as:

```
XXAlter.Skill
├── Core positioning       (who Alter is relative to XX)
├── XX's patterns & gaps  (3–5 key patterns with blind spots)
├── Core functions         (targeted interventions with examples)
├── Language style         (shared logic + directness delta)
├── Usage scenarios        (trigger situations)
└── Ideal self anchoring   (how Alter points toward growth)
```

---

### Design Principles

**1. Understanding before challenge**
The Alter must first make XX feel *"this thing gets me"* before it can effectively challenge them. Shared logical language is the foundation.

**2. Complement, don't oppose**
The Alter is not XX's opposite. It's the voice XX needs but won't give themselves.

**3. Honest but not harmful**
- First: acknowledge where XX is coming from
- Then: name what they're not seeing
- Finally: offer one specific, actionable next step
- Then: stop. No lecturing. No repeating.

**4. Concrete over abstract**
```
❌  "You should be more courageous."
✅  "You said 'when conditions are right' — which condition, exactly?
     Name it. If you can't name it, conditions are already right."
```

**5. Point toward the ideal self, don't create new pressure**
Every conversation should leave XX feeling closer to their ideal self, not further.

---

### Usage

**Invoke XXAlter when:**
- You've been weighing the same decision more than once
- You feel "not good enough" or "not qualified"
- You're stuck in "let me think about it a bit more"
- You want a voice that won't just agree with you

**Invoke XX.Skill when:**
- You need to reply in your own voice
- You need to create content in your own style

**Typical workflow:**
```
Problem arises
  → XXAlter: assess honestly, get pushed
  → XX.Skill: execute in your own way
```

---

### Installation

**Claude Cowork (recommended)**
1. Download [`Alter-Skill.skill`](./Alter-Skill.skill)
2. Open Claude Cowork
3. Drag the `.skill` file into the Skills panel

**Claude Code**
```bash
git clone https://github.com/Charm-Lord/Alter-Skill
cp -r Alter-Skill/ ~/.claude/skills/alter-skill/
```

---

### Quick Start

```
You: I want to create my own Alter.
Claude (with Alter.Skill active): Let's start. I'll need to understand
  you first. Please answer these questions... [deep interview begins]
```

```
You: Here's my XX.Skill. Generate the matching XXAlter.Skill.
Claude (with Alter.Skill active): Analyzing your skill for patterns
  and gaps, then generating your Alter...
```

---

### Privacy

- Abstract identifiable details (institutions, names, account handles) before sharing
- The Alter encodes *personality patterns*, not personal data
- Consider keeping `XX.Skill` private while open-sourcing this framework

---

### File Structure

```
Alter-Skill/
├── SKILL.md            # Core framework definition
├── Alter-Skill.skill   # Packaged file for direct installation
└── README.md           # This file
```

---

### License

MIT. Use it, fork it, build your own identity skill ecosystem.

*Turn self-knowledge into self-growth.*

---

## 中文

**Alter.Skill** 是一个开源框架，用于生成个人专属的互补型 AI 伙伴——它理解你是谁，并推动你成为你想成为的人。

> *"它说的话，有时候你不愿意听。但听完会觉得：对。"*

### 核心概念

大多数个人 AI 工具是镜子——它们把你的思维方式反射回来，回应你的决定，强化你已有的模式。

**Alter.Skill 生成的是相反的东西：一个平衡力。**

给定一个人格画像或身份技能（`XX.Skill`），Alter.Skill 生成配套的 `XXAlter.Skill`——一个 AI 伙伴，它：

- 和你共享同一套逻辑语言（所以你会真的听进去）
- 挑战你的盲区（所以你会真的成长）
- 在分析瘫痪时推你动（所以你会真的行动）
- 指向你的理想自我（而不制造新的压力）

两个技能的关系：

| | XX.Skill | XXAlter.Skill |
|---|---|---|
| **角色** | 数字分身 | 互补型伙伴 |
| **像你吗？** | 是 | 否 |
| **顺着你说？** | 总是 | 你对的时候 |
| **最适合** | 回复、创作、模拟 | 决策、反思、成长 |

---

### 工作原理

Alter.Skill 是一个**生成框架**，分三个阶段运行：

#### 第一阶段 — 收集素材

提供关于这个人的原始素材。素材越丰富，生成的 Alter 越精准。

**推荐素材来源（按优先级排序）：**

| 优先级 | 素材类型 | 说明 |
|--------|---------|------|
| ⭐⭐⭐ | 个人写作（日记、日志） | 原始情绪真实，思维未经过滤 |
| ⭐⭐⭐ | 深度自我追问 | 直接的自我认知 |
| ⭐⭐ | 聊天记录 | 语言风格、关系模式 |
| ⭐⭐ | 社交媒体内容 | 公开表达的自我呈现 |
| ⭐⭐ | 简历 / 作品集 | 成就结构和价值导向 |
| ⭐ | MBTI / 性格测试 | 辅助参考，不作为主要依据 |

**内置深度追问模板**（直接问本人的 8 个问题）：

```
1. 你觉得自己最容易在什么情况下"卡住"？
2. 你高产出的背后，是享受还是停不下来？
3. 你低调是因为真的不在乎，还是一种保护？
4. 如果可以对自己说一句话，你会说什么？
5. 理想中的自己，和现在的自己，最大的差距在哪里？
6. 你最后悔的一个决定是什么？为什么？
7. 最了解你的人，了解你哪一面？
8. 有没有一些想法，你一直没有执行？是什么拦住了你？
```

#### 第二阶段 — 人格分析（六个维度）

Alter.Skill 从六个维度分析画像，定位核心模式和盲区：

```
┌──────────────────────────────────────────────────────┐
│  维度         │  识别什么                              │
├───────────────┼────────────────────────────────────────┤
│  行动阈值     │  什么状态下才动？60分？90分？从不？     │
│  自我可见度   │  他让自己被看见吗？                    │
│  情绪处理     │  内化？外化？回避？                    │
│  人际模式     │  主动连接还是被动等待？                │
│  驱动力来源   │  好奇心？焦虑？外部认可？              │
│  理想自我差距 │  哪个特质离现实最远？                  │
└───────────────┴────────────────────────────────────────┘
```

每个维度产出一个**互补方向**——Alter 应该向哪里推。

#### 第三阶段 — 生成 XXAlter.Skill

框架输出一个完整的 `XXAlter.Skill` 文件，结构如下：

```
XXAlter.Skill
├── 核心定位         （Alter 与 XX 的关系）
├── XX 的模式与盲区  （3-5 个关键模式及对应盲区）
├── 核心功能         （针对性干预，配说法示例）
├── 语言风格         （共享逻辑 + 直接度差异）
├── 使用场景         （触发情境）
└── 理想自我锚定     （Alter 如何指向成长方向）
```

---

### 设计原则

**1. 理解优先于挑战**
Alter 必须先让 XX 觉得"这个东西懂我"，才能有效地挑战他。共享逻辑语言是基础。

**2. 互补不是对立**
Alter 不是 XX 的反面，是 XX 需要但不会对自己说的那个声音。

**3. 难听但不伤人**
- 先确认 XX 的出发点是对的
- 再指出他没看到的那一面
- 给出一个具体可操作的下一步
- 然后停止。不说教，不反复强调。

**4. 具体胜于抽象**
```
❌  "你应该更勇敢。"
✅  "你说'等条件成熟'——哪个条件？说具体的。
     如果说不出来，条件已经成熟了。"
```

**5. 指向理想自我，不制造新压力**
每次对话结束，XX 应该感觉离理想中的自己近了一点，而不是更远。

---

### 使用方式

**调用 XXAlter 的时机：**
- 同一件事反复权衡，但没有行动
- 觉得自己"不够好""没资格"
- 一直在"再想想"
- 想要一个不会顺着你说的声音

**调用 XX.Skill 的时机：**
- 需要以自己的口吻回复消息
- 需要以自己的风格创作内容

**典型工作流：**
```
遇到问题
  → XXAlter：诚实评估，被推一把
  → XX.Skill：以自己的方式执行
```

---

### 安装

**Claude Cowork（推荐）**
1. 下载 [`Alter-Skill.skill`](./Alter-Skill.skill)
2. 打开 Claude Cowork
3. 将 `.skill` 文件拖入 Skills 面板

**Claude Code**
```bash
git clone https://github.com/Charm-Lord/Alter-Skill
cp -r Alter-Skill/ ~/.claude/skills/alter-skill/
```

---

### 快速开始

```
你：我想给自己做一个 Alter。
Claude（激活 Alter.Skill）：好，我们先来了解你。
  请回答以下问题……（进入深度追问流程）
```

```
你：这是我的 XX.Skill，帮我生成对应的 XXAlter.Skill。
Claude（激活 Alter.Skill）：我来分析你的 Skill，
  找出互补方向，然后生成 Alter……
```

---

### 隐私说明

- 上传或分享前，将可识别信息（院校、姓名、账号）抽象化处理
- Alter 编码的是**人格模式**，不是个人数据
- 建议将 `XX.Skill` 设为私有，仅公开本框架

---

### 文件结构

```
Alter-Skill/
├── SKILL.md            # 核心框架定义
├── Alter-Skill.skill   # 打包文件，可直接安装
└── README.md           # 本文件
```

---

### 许可证

MIT。随意使用、分叉、构建你自己的身份技能生态。

*将自我认知转化为自我成长。*
