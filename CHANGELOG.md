# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- 注册子模块：`apps/qtdata`（量潮数据）
- 注册子模块：`examples/default`（项目管理实验室，quanttide-laboratory-of-project-management）
- 注册子模块：`data/context`（项目管理语境，quanttide-context-of-project-management）
- 注册子模块：`data/journal`（项目管理日志，quanttide-journal-of-project-management）
- 注册子模块：`data/profile`（项目管理档案，quanttide-profile-of-project-management）
- 注册子模块：`data/intention`（项目管理意图，quanttide-intention-of-project-management）
- 注册子模块：`data/roadmap`（项目管理路线图，quanttide-roadmap-of-project-management）
- 注册子模块：`data/insight`（项目管理洞察，quanttide-insight-of-project-management）
- 注册子模块：`data/brochure`（项目管理宣传册，quanttide-brochure-of-project-management）
- 注册子模块：`data/report`（项目管理报告，quanttide-report-of-project-management）
- 注册子模块：`data/library`（项目管理参考，quanttide-library-of-project-management）
- 注册子模块：`data/history`（项目管理历史，quanttide-history-of-project-management）
- 注册子模块：`data/archive`（项目管理归档，quanttide-archive-of-project-management）
- 注册子模块：`docs/bylaw`（项目管理章程，quanttide-bylaw-of-project-management）
- 注册子模块：`docs/essay`（项目管理札记，quanttide-essay-of-project-management）
- 注册子模块：`docs/gallery`（项目管理案例集，quanttide-gallery-of-project-management）

### 变更

- 更新 `apps/qtcloud-project` 子模块：重构 Flutter 客户端为项目管理框架骨架（首页项目列表、项目详情十大知识领域导航、范围管理页）
- 更新 `apps/qtcloud-project` 子模块：配置 Studio 部署 CI 与基础设施 IaC（OSS/CDN/DNS，`project.cloud.quanttide.com`）、应用名称统一为量潮项目云
- 更新 `apps/qtcloud-project` 子模块：发布 `studio/v0.1.0-alpha.2`，HTTPS 证书签发绑定（Let's Encrypt）

## [0.1.0] - 2026-08-10

### 新增

- 初始化仓库骨架：README、LICENSE（CC BY 4.0）、CHANGELOG、AGENTS
- 注册子模块：`apps/qtcloud-project`（项目管理云服务）
- 注册子模块：`docs/handbook`、`docs/tutorial`、`docs/specification`（领域文档）
- 注册子模块：`packages/quanttide-project-toolkit`（共享工具集）
