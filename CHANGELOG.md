# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 移除

- `work/syntax.md`：work 语法尚未成为标准，降级迁出至语境层的 `work/specification/`；本仓暂无可收录规格

### 新增

- `language/context.md`：语境规格——定义语场、语旨、语式与体裁、语域等基本概念，给出语用失误的三维关系与 C1–C4 四条规则；判定细则注明由标注体系另定

- `meta/`：元概念规格——`rule.md`、`contract.md`、`criterion.md` 各记一个概念的本意、计算机实现与核心区别，`index.md` 记三者对比与协同
- `work/index.md`：工作结构规格——owner 与 reviewer 两个角色、五站一轮、凭证与账本；规则 R1、R2、R5、R6、R7，自 `agent/index.md` 拆出
- `agent/index.md`：智能体协作规格——一句话情境、自然语言描述与形式化规则三段；自手册迁入
- 初始化规格仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`

### 变更

- `language/context.md`：语境从「对象、读者、惯例」改为语场、语旨、语式三项，惯例拆进体裁规约与语域期望；「错配」改称语用失误
- `language/context.md`：只留基本概念与形式化关系，删除标注向量、桥接映射、失误报告格式等过早的实现细节

- `agent/index.md`：改为以单个智能体为单位建模——身份、上下文、能力边界、输出四节，协作降为两个主体之间的关系；R1、R5 在身份层标注，规则集仍为 R3、R4
- `index.md`、`myst.yml`、`README.md`：目录增加「工作」一节
