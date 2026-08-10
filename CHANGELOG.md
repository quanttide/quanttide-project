# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- 注册子模块：`apps/qtdata`（量潮数据）

### 变更

- 更新 `apps/qtcloud-project` 子模块：重构 Flutter 客户端为项目管理框架骨架（首页项目列表、项目详情十大知识领域导航、范围管理页）
- 更新 `apps/qtcloud-project` 子模块：配置 Studio 部署 CI 与基础设施 IaC（OSS/CDN/DNS，`project.cloud.quanttide.com`）、应用名称统一为量潮项目云

## [0.1.0] - 2026-08-10

### 新增

- 初始化仓库骨架：README、LICENSE（CC BY 4.0）、CHANGELOG、AGENTS
- 注册子模块：`apps/qtcloud-project`（项目管理云服务）
- 注册子模块：`docs/handbook`、`docs/tutorial`、`docs/specification`（领域文档）
- 注册子模块：`packages/quanttide-project-toolkit`（共享工具集）
