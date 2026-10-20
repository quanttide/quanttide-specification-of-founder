# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 移除

- `work/syntax.md`：work 语法尚未成为标准，降级迁出至语境层的 `work/specification/`；本仓暂无可收录规格

### 新增

- `work/index.md`：工作结构规格——owner 与 reviewer 两个角色、五站一轮、凭证与账本；规则 R1、R2、R5、R6、R7，自 `agent/index.md` 拆出
- `agent/index.md`：智能体协作规格——一句话情境、自然语言描述与形式化规则三段；自手册迁入
- 初始化规格仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`

### 变更

- `agent/index.md`：改为「双智能体协作」模型，只对两个独立主体的过界物与连接结构建模，不再使用具体角色名；规则收敛为 R3、R4
- `index.md`、`myst.yml`、`README.md`：目录增加「工作」一节
