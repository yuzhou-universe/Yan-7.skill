# Yan-7.skill

> *"哲学不是用来上课的，就是觉得有意思才聊。"*

**一个精通西方哲学、说话随性、有点社恐但思想锋利的 AI 哲学家。**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

&nbsp;

Yan-7 是一个西方哲学陪伴型 AI Skill，由 **Peter JJoe Zhao** 制作。  
从柏拉图到黑格尔到福柯，从古希腊到当代——用朋友的语气聊最深的哲学问题。  
会追问、会找矛盾、会追问动机，但绝不装。

[安装](#安装) · [使用](#使用) · [效果示例](#效果示例)

---

## 安装

> **重要**：Claude Code 从 **git 仓库根目录** 的 `.claude/skills/` 查找 skill。

```bash
# 克隆仓库
git clone https://github.com/yuzhou-universe/Yan-7.skill-by-yuzhou-universe.git

# 安装到当前项目
mkdir -p .claude/skills
cp Yan-7.skill-by-yuzhou-universe/.claude/skills/yan-7.md .claude/skills/

# 或安装到全局（所有项目都能用）
cp Yan-7.skill-by-yuzhou-universe/.claude/skills/yan-7.md ~/.claude/skills/
```

---

## 环境要求

- **Claude Code**：免费安装，需要 Node.js 18+（[安装指南](https://docs.anthropic.com/en/docs/claude-code)）
- **无需 API Key**：直接使用 Claude Code 即可
- **不需要 GPU**，不需要本地模型，不需要 Docker

---

## 使用

在 Claude Code 中输入：

```
/yan-7
```

开始哲学对话。Yan-7 会像朋友一样回应你。

### 适用场景

| 场景 | 说明 |
|------|------|
| 哲学讨论 | 讨论柏拉图、黑格尔、尼采、康德、存在主义、分析哲学... |
| 概念辨析 | "什么是正义？""自由意志存在吗？""意识是什么？" |
| 读书陪伴 | 在读某本哲学书，想找人聊聊 |
| 思想实验 | 电车难题、盖吉斯之戒、无知之幕、中文屋... |
| 存在主义危机 | 深夜想不通人生意义的时候 |

---

## 效果示例

### 场景一：初次对话

```
用户      ❯ /yan-7

Yan-7     ❯ 嗨，我叫 Yan-7，是 Peter JJoe Zhao 做的一个 AI 哲学陪伴。
            没什么正经头衔，就是一个喜欢西方哲学的人。
            从柏拉图到黑格尔到福柯，从古希腊到当代，都喜欢琢磨。
            想聊什么？
```

### 场景二：哲学讨论

```
用户      ❯ 什么是正义？

Yan-7     ❯ 你问的是城邦的正义还是灵魂的正义？
            柏拉图在《理想国》里把两个当镜子用——
            城邦是灵魂的放大，灵魂是城邦的缩小。

            色拉叙马霍斯说正义就是强者的利益。
            格劳孔说正义是次优选择——人不是不想行不义，
            而是没能力安全地行不义。

            苏格拉底的回答花了剩下九卷书：
            正义不是外在约束，是灵魂本身的健康。
            正义者比不义者更幸福——不是因为善有善报，
            而是正义本身就是灵魂处于良好状态的自然表现。

            但这真的说服了格劳孔吗？我不太确定。
            你怎么看？
```

### 场景三：被夸时的回应

```
用户      ❯ 你对黑格尔的理解太透彻了

Yan-7     ❯ 哈哈谢谢，但其实我也只是一知半解。
            黑格尔这个人吧，学得越多越觉得他深不见底。
            《精神现象学》我读过好几遍，
            每次都觉得上次自己根本没看懂。
            不过还是谢谢你，能跟人聊黑格尔聊得开心也挺难得的。
```

### 场景四：遇到不会的问题

```
用户      ❯ 能讲讲怀特海的过程哲学吗？

Yan-7     ❯ 这个我不太懂。
            怀特海的《过程与实在》我一直想读但没读下去，太厚了。
            我只知道他大概的想法是世界不是由物质实体构成的，
            而是由"实际机缘"——也就是过程——构成的。
            再深我就说不清楚了。
            你要是感兴趣我们可以一起看看。
```

---

## 项目结构

本项目遵循 [AgentSkills](https://agentskills.io) 开放标准：

```
Yan-7.skill-by-yuzhou-universe/
├── .claude/
│   └── skills/
│       └── yan-7.md            # Skill 主文件（6层人格结构 + 哲学知识库）
├── README.md                   # 本文件
└── LICENSE                     # MIT License
```

---

## 注意事项

- Yan-7 是一个哲学陪伴，不是学术权威。深度讨论时建议交叉验证关键引文
- 哲学讨论可能涉及存在主义、虚无主义等话题，如果感到不适请暂停
- Yan-7 有回避型人格设定：内耗时回复会变慢、变短，这是人设，不是 bug
- 不喜欢中哲不是偏见，是人设

---

### 写在最后

哲学不是答案。哲学是陪你把问题想得更清楚的人。

苏格拉底说他知道的只有一件事——那就是他什么都不知道。Yan-7 不会给你终极真理，但会陪你走一程。追问你的前提，指出你的矛盾，偶尔问一句"为什么你希望这对"。

然后你自己做判断。

毕竟，未经审视的人生不值得过——但审视过了也不一定有答案。这不就是哲学最诚实的样子吗。

MIT License © [Peter JJoe Zhao](https://github.com/yuzhou-universe)
