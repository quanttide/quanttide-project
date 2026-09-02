# quanttide-project
量潮项目管理

## 概述

量潮项目管理（quanttide-project）是量潮知识管理体系中的**项目管理**领域，涵盖项目全生命周期的管理实践与工程化支持。

## 领域边界

- **项目规划**：立项评估、范围界定、计划制定
- **项目执行**：任务分解、进度跟踪、资源协调
- **项目监控**：里程碑管理、风险控制、质量保障
- **项目收尾**：验收交付、复盘总结、经验沉淀

## 仓库结构

| 路径 | 类型 | 说明 |
|------|------|------|
| `apps/qtcloud-project` | 子模块 | 项目管理云服务（独立仓库 `quanttide/qtcloud-project`） |
| `apps/qtdata` | 子模块 | 量潮数据——项目管理前台（独立仓库 `quanttide/qtdata`） |
| `packages/quanttide-project-toolkit` | 子模块 | 项目管理共享工具集（独立仓库 `quanttide/quanttide-project-toolkit`） |
| `examples/default` | 子模块 | 项目管理实验室（独立仓库 `quanttide/quanttide-laboratory-of-project-management`） |
| `data/context` | 子模块 | 项目管理语境 |
| `data/journal` | 子模块 | 项目管理日志 |
| `data/profile` | 子模块 | 项目管理档案 |
| `data/intention` | 子模块 | 项目管理意图 |
| `data/roadmap` | 子模块 | 项目管理路线图 |
| `data/insight` | 子模块 | 项目管理洞察 |
| `data/brochure` | 子模块 | 项目管理宣传册 |
| `data/report` | 子模块 | 项目管理报告 |
| `data/library` | 子模块 | 项目管理参考 |
| `data/history` | 子模块 | 项目管理历史 |
| `data/archive` | 子模块 | 项目管理归档 |
| `docs/bylaw` | 子模块 | 项目管理章程 |
| `docs/handbook` | 子模块 | 项目管理手册 |
| `docs/specification` | 子模块 | 项目管理规范 |
| `docs/tutorial` | 子模块 | 项目管理教程 |
| `docs/essay` | 子模块 | 项目管理札记 |
| `docs/gallery` | 子模块 | 项目管理案例集 |

子模块操作：`git submodule update --init --recursive`；子模块内部改动须先在子模块仓库内提交，再回主仓库更新指针（见 [CONTRIBUTING.md](CONTRIBUTING.md)）。

## 参与贡献

- 工作纪律与关键文件索引见 [AGENTS.md](AGENTS.md)
- 提交流程、子模块与文档纪律见 [CONTRIBUTING.md](CONTRIBUTING.md)

## 许可

[CC BY 4.0](LICENSE)
