# 教员 Skill

一个面向 Codex/Agent 的中文方法论技能。它融合两个《毛选》蒸馏项目，并加入可验证、可纠错的现代决策框架，用于分析现实困境、战略选择、资源分配、组织协作和实践复盘。

## 主要能力

- 从事实和约束出发识别当前主要矛盾
- 区分主要矛盾、矛盾的主要方面和转化条件
- 用低成本行动验证判断，再决定是否集中投入
- 分析长期积累、阶段变化、根据地和退出条件
- 处理团队利益、群众反馈、合作边界与组织复盘
- 按需检索毛选原文，区分原文、方法概括和现代应用

## 安装

将仓库复制到 Codex 的 skills 目录：

```powershell
git clone https://github.com/abdaziz902019287273-sketch/jiaoyuan-skill.git "$env:USERPROFILE\.codex\skills\jiaoyuan"
```

如果目标目录已存在，请先自行备份或选择其他目录，不要直接覆盖。

## 使用

```text
请用 $jiaoyuan 分析我的处境，指出当前主要矛盾、判断依据和下一步可检验的行动。
```

也可以直接说“教员怎么看”“用毛选分析”，或要求用调查研究、群众路线、持久战略等方法处理具体问题。

## 设计原则

本技能保留相关方法的启发力，同时避免冒充历史人物、用气势代替证据，或把历史类比当成现实证明。重要判断应说明依据、不确定性、可观察结果和调整条件。

技能不依赖外部 API 或全文知识库。精确引用原文时，需要实际查证可靠文本。

## 文件结构

```text
jiaoyuan-skill/
├── SKILL.md
├── agents/openai.yaml
├── references/
│   ├── examples.md
│   ├── investigation.md
│   ├── organization.md
│   ├── sources.md
│   └── strategy.md
└── LICENSE
```

## 来源与许可

主要参考：

- [leezythu/maoxuan-skill](https://github.com/leezythu/maoxuan-skill)
- [chinapathbreaker/mao-skill](https://github.com/chinapathbreaker/mao-skill)

更具体的融合记录见 [references/sources.md](references/sources.md)。本仓库依据随附的 [MIT License](LICENSE) 发布。
