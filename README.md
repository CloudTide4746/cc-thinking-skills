
# Claude Code Thinking Skills

> **Claude Code 中用于批判性思维的 39 个心智模型与思维框架**

这是一个为 [Claude Code](https://claude.ai/claude-code) 设计的、全面的思维技能集合，用于增强 AI 辅助下的问题解决、决策制定和战略分析能力。这些技能基于系统思维、认知科学和战略分析领域中成熟可靠的框架与心智模型。

[![Claude Code Skills](https://img.shields.io/badge/Claude_Code-Skills-7C3AED?style=flat\&logo=data\:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMiA3TDEyIDEyTDIyIDdMMTIgMloiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMiIvPgo8cGF0aCBkPSJNMiAxN0wxMiAyMkwyMiAxNyIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIi8+CjxwYXRoIGQ9Ik0yIDEyTDEyIDE3TDIyIDEyIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiLz4KPC9zdmc+)](https://github.com/tjboudreaux/cc-thinking-skills)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills Count](https://img.shields.io/badge/Skills-39-blue)](https://github.com/tjboudreaux/cc-thinking-skills)

## 特性

* **39 个思维框架** —— 用于提升决策质量的完整心智模型集合
* **经过验证** —— 基于认知科学与系统思维中的成熟框架
* **Claude Code 原生适配** —— 专为 Claude Code 的技能系统设计
* **高质量脚本工具** —— 可用于校验和增强技能质量
* **零配置** —— 安装后直接通过技能名调用即可

## 快速开始

### 通过插件市场安装（推荐）

可以直接在 Claude Code 中通过插件系统安装：

```bash
# 添加市场源
/plugin marketplace add tjboudreaux/cc-thinking-skills

# 安装插件
/plugin install thinking-skills@thinking-skills-marketplace
```

### 另一种方式：手动安装

直接克隆仓库并复制技能文件：

```bash
# 克隆仓库
git clone https://github.com/tjboudreaux/cc-thinking-skills.git

# 复制技能到全局 Claude Code 配置目录
cp -r cc-thinking-skills/skills/* ~/.claude/skills/

# 或复制到某个特定项目中
cp -r cc-thinking-skills/skills/* /path/to/your/project/.claude/skills/
```

### 开发模式：作为本地插件加载

用于测试或开发时：

```bash
claude --plugin-dir ./cc-thinking-skills
```

### 使用方式

安装完成后，可以在 Claude Code 中通过技能名直接调用任意技能：

```text
> Use first-principles thinking to analyze this architecture decision
> Apply the pre-mortem framework to this project plan
> Help me use Bayesian reasoning to evaluate this hypothesis
> Use the theory of constraints to find our bottleneck
```

## 可用技能

### 决策与分析

| 技能                             | 描述                    | 最适用场景       |
| ------------------------------ | --------------------- | ----------- |
| `thinking-first-principles`    | 将问题拆解为最基本的事实          | 创新、挑战既有假设   |
| `thinking-second-order`        | 思考直接后果之外的后续影响         | 战略决策、政策变化   |
| `thinking-inversion`           | 通过识别失败路径来解决问题         | 风险识别、规划     |
| `thinking-pre-mortem`          | 先假设失败，再倒推原因           | 项目启动、风险评估   |
| `thinking-kepner-tregoe`       | 一种系统化、理性的复杂分析流程       | 高风险决策、根因分析  |
| `thinking-reversibility`       | 按决策是否可逆进行分类（Type 1/2） | 承诺强度判断、风险评估 |
| `thinking-regret-minimization` | 从未来自我的视角检验决策          | 职业选择、重大人生决策 |
| `thinking-opportunity-cost`    | 通过放弃了什么来评估选择          | 资源分配、优先级排序  |

### 认知与行为

| 技能                             | 描述              | 最适用场景       |
| ------------------------------ | --------------- | ----------- |
| `thinking-bayesian`            | 根据新证据动态更新信念     | 概率估计、不确定性判断 |
| `thinking-debiasing`           | 识别并对抗认知偏差       | 重大决策、高风险判断  |
| `thinking-dual-process`        | 判断何时依赖直觉，何时依赖分析 | 速度与准确性的权衡   |
| `thinking-bounded-rationality` | 在约束条件下做“足够好”的决策 | 时间压力、满意解选择  |
| `thinking-socratic`            | 系统化提问框架         | 需求分析、调试、辅导  |
| `thinking-probabilistic`       | 校准后的概率性思维       | 预测、不确定性量化   |
| `thinking-steel-manning`       | 用最强版本来论证对立观点    | 辩论、决策校验     |

### 系统与战略

| 技能                               | 描述                | 最适用场景       |
| -------------------------------- | ----------------- | ----------- |
| `thinking-systems`               | 从相互关联的整体中分析问题     | 复杂调试、架构分析   |
| `thinking-feedback-loops`        | 识别强化回路与平衡回路       | 增长设计、组织动态   |
| `thinking-archetypes`            | 识别反复出现的系统模式       | 组织问题、重复性问题  |
| `thinking-ooda`                  | 面向动态环境的快速决策框架     | 事故响应、竞争场景   |
| `thinking-leverage-points`       | 找到“小改动带来大影响”的杠杆点  | 系统优化、干预设计   |
| `thinking-theory-of-constraints` | 识别并管理系统瓶颈         | 性能优化、吞吐提升   |
| `thinking-cynefin`               | 按因果关系将问题划分为不同复杂度域 | 方法选择、匹配处理方式 |

### 问题解决与创新

| 技能                              | 描述                | 最适用场景          |
| ------------------------------- | ----------------- | -------------- |
| `thinking-occams-razor`         | 优先采用更简单的解释        | 调试、架构决策        |
| `thinking-map-territory`        | 认识到模型与现实之间的差异     | 预期偏差、抽象理解      |
| `thinking-circle-of-competence` | 明确自己能力边界          | 委派、学习决策        |
| `thinking-triz`                 | 解决技术矛盾            | 工程设计、创新        |
| `thinking-five-whys-plus`       | 带有偏差防护的增强版“五个为什么” | 调试、事故复盘        |
| `thinking-scientific-method`    | 基于假设驱动的调查方法       | 调试、A/B 测试、实验设计 |
| `thinking-thought-experiment`   | 通过结构化想象进行探索       | 架构、边界情况、哲学思考   |

### 估算与风险

| 技能                          | 描述             | 最适用场景        |
| --------------------------- | -------------- | ------------ |
| `thinking-fermi-estimation` | 数量级估算方法        | 快速规模判断、可行性评估 |
| `thinking-margin-of-safety` | 为不确定性预留缓冲空间    | 风险管理、系统设计    |
| `thinking-lindy-effect`     | 越 오래存在的事物越可能持续 | 技术选型、耐久性判断   |
| `thinking-via-negativa`     | 通过移除而不是增加来改进   | 简化、提升鲁棒性     |
| `thinking-red-team`         | 以对抗视角攻击自己的方案   | 安全审查、方案验证    |

### 产品与创新

| 技能                         | 描述               | 最适用场景       |
| -------------------------- | ---------------- | ----------- |
| `thinking-jobs-to-be-done` | 理解用户“雇佣”产品来完成的任务 | 产品开发、功能设计   |
| `thinking-effectuation`    | 从已有资源出发，而非从目标出发  | 创业、创新、不确定环境 |

### 元技能

| 技能                           | 描述                       | 最适用场景      |
| ---------------------------- | ------------------------ | ---------- |
| `thinking-model-router`      | **从这里开始** —— 按问题域路由到合适模型 | 所有思维技能的入口  |
| `thinking-model-selection`   | 为问题选择最合适的模型              | 新问题、方法选择   |
| `thinking-model-combination` | 组合多个模型，得到更丰富的分析          | 复杂问题、高风险决策 |

## 质量保证工具

这个集合还包含用于维护和提升技能质量的脚本工具：

### 校验技能

根据质量标准检查所有技能：

```bash
node scripts/validate-skills.js
```

输出报告包括：

* 必需部分是否齐全
* 质量指标（示例、表格、清单等）
* 每个技能的总体评分
* 需要改进的技能列表

### 生成增强建议

为某个技能生成具体的改进建议：

```bash
# 单个技能
node scripts/enhance-skill.js thinking-first-principles

# 所有技能的汇总建议
node scripts/enhance-skill.js
```

### 生成 AI 改进提示词

为 Claude 生成用于增强技能的提示词：

```bash
node scripts/generate-improvement-prompt.js thinking-bayesian
```

这会生成一份详细提示词，你可以将其交给 Claude Code，系统性地改进任意技能。

## 详细技能说明

### 第一性原理思维

剥离假设，找到最底层的真实约束与基本事实，再从这些基础出发重建解决方案。该方法由 Elon Musk 推广，其思想源头可以追溯到亚里士多德哲学。

**适用场景：**

* 传统方法已经失效
* 你被告知某件事“不可能”
* 你需要的是创新，而不是渐进式优化

### 贝叶斯推理

根据新证据系统性地更新自己的判断。它提供了一套关于概率与不确定性的思考框架。

**适用场景：**

* 估计概率或可能性
* 解读测试结果或指标数据
* 在信息不完整的条件下做决策

### 系统思维

将问题视为由多个相互作用部分构成的整体，关注反馈回路和涌现行为。这对于调试复杂分布式系统尤为重要。

**适用场景：**

* 调试问题跨越多个组件
* 修复一个地方却在别处引发问题
* 行为呈现出涌现性或难以直观看懂

### 约束理论

任何系统中都只有一个真正限制吞吐量的约束点。优化其他地方通常都是浪费。这一理论基于 Eliyahu Goldratt 的研究。

**适用场景：**

* 性能优化
* 流程改进
* 资源分配
* 识别瓶颈

### Cynefin 框架

根据因果关系的可识别程度，将问题划分为：清晰（Clear）、繁杂（Complicated）、复杂（Complex）和混乱（Chaotic）四类。不同类别的问题需要不同的应对方式。

**适用场景：**

* 选择方法论
* 理解为什么某种方法失效
* 危机管理

### 待完成工作（Jobs to Be Done）

用户购买的不是产品本身，而是产品所完成的“任务”。真正理解这个任务，才能打开创新空间。

**适用场景：**

* 产品开发
* 功能优先级排序
* 理解用户行为

### 红队思维

在对手替你发现漏洞之前，先主动攻击自己的方案。最好的防御，是先知道自己的弱点在哪里。

**适用场景：**

* 安全审查
* 上线前准备
* 方案压力测试

## 贡献

欢迎贡献！请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解详细指南。

### 添加新技能

1. 在 `skills/` 目录下新建一个名为 `thinking-{name}` 的目录
2. 添加一个带有 YAML frontmatter 的 `SKILL.md` 文件：

```yaml
---
name: thinking-your-skill-name
description: 简短描述，不超过 200 个字符（Claude Code 用它来匹配技能）
---
```

3. 编写完整文档，内容应包括：

   * 概述与核心原则
   * 何时使用的判断流程
   * 分步过程说明
   * 至少 2 个实际案例
   * 可复用模板
   * 验证清单
   * 关键问题

4. 校验你的技能：

```bash
node scripts/validate-skills.js
```

## 关键词

`claude-code` `claude` `anthropic` `ai` `skills` `mental-models` `critical-thinking` `decision-making` `problem-solving` `systems-thinking` `first-principles` `bayesian-reasoning` `cognitive-bias` `strategic-thinking` `frameworks` `triz` `ooda` `pre-mortem` `socratic-method` `theory-of-constraints` `cynefin` `jobs-to-be-done` `red-team` `fermi-estimation`

## 相关资源

* [Claude Code Documentation](https://docs.anthropic.com/claude-code)
* [Charlie Munger's Mental Models](https://fs.blog/mental-models/)
* [Thinking in Systems - Donella Meadows](https://www.chelseagreen.com/product/thinking-in-systems/)
* [Thinking, Fast and Slow - Daniel Kahneman](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374533555)
* [The Goal - Eliyahu Goldratt](https://www.amazon.com/Goal-Process-Ongoing-Improvement/dp/0884271951)

## 许可证

MIT License —— 详见 [LICENSE](LICENSE)

## 作者

由 [TJ Boudreaux](https://github.com/tjboudreaux) 创建

---

**觉得有用的话，欢迎点个 Star，并分享给其他也能从这些思维框架中受益的人。**

