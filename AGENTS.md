# AGENTS（quanttide-project）

面向在仓库内工作的编码 agent 的指令。**动手前先读「关键文件」一节**。

## 仓库是什么

量潮项目管理编排仓库：`apps/qtcloud-project`（项目管理云服务，子模块）、`docs/*`（领域文档，子模块）、`packages/quanttide-project-toolkit`（共享工具集，子模块，独立仓库 `quanttide/quanttide-project-toolkit`）。

## 关键文件（按优先级阅读）

| 文件 | 作用 | 何时必读 |
|------|------|----------|
| `README.md` | 仓库结构、领域边界 | 每次工作前 |
| `CONTRIBUTING.md` | 提交规范、子模块纪律、文档同步要求 | 每次提交前 |
| `CHANGELOG.md` | 版本变更记录 | 发布版本时 |

## 提交纪律

- 子模块（`apps/qtcloud-project`、`docs/*`、`packages/quanttide-project-toolkit`）内容先提交到各自仓库，主仓库只记录指针
- Conventional Commits，中文描述；文档与代码同批提交
- 提交前核对：文档是否同步、子模块指针是否已更新
