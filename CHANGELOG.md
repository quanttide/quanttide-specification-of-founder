# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 移除

- `work/syntax.md`：work 语法尚未成为标准，降级迁出至语境层的 `work/specification/`；本仓暂无可收录规格

### 新增

- `language/context.md`：语境规格——语境定义为三元组 ⟨F, T, G⟩，即语场、语旨、语式；每个参数给出语用学来源、可标注表示与检查函数；列语用失误的三维判定与 C1–C4 四条规则；解释性内容迁至论文仓 `language/context.md`

- `meta/`：元概念规格——`rule.md`、`contract.md`、`criterion.md` 各记一个概念的本意、计算机实现与核心区别，`index.md` 记三者对比与协同
- `work/index.md`：工作结构规格——owner 与 reviewer 两个角色、五站一轮、凭证与账本；规则 R1、R2、R5、R6、R7，自 `agent/index.md` 拆出
- `agent/index.md`：智能体协作规格——一句话情境、自然语言描述与形式化规则三段；自手册迁入
- 初始化规格仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`

### 变更

- `language/context.md`：语境定义从「对象、读者、惯例」改为语域三参数——语场 F、语旨 T、语式 G，惯例拆进体裁规则集与语域期望；「错配」改称语用失误，按违反维度判定与定向修复；补失误分类、边界与代价、术语对照三项
- `language/context.md`：判定口径细化——C2 改为「目标语场惯用或该语场许可的说法」，桥接映射定义在标签集层面，区间按分量给出并输出方向，失误报告定为 ⟨维度, 分量, 方向⟩；代价项补 F 更新、桥接映射库覆盖与标注粒度

- `agent/index.md`：改为以单个智能体为单位建模——身份、上下文、能力边界、输出四节，协作降为两个主体之间的关系；R1、R5 在身份层标注，规则集仍为 R3、R4
- `index.md`、`myst.yml`、`README.md`：目录增加「工作」一节
