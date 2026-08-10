# 贡献指南（quanttide-project）

## 仓库结构须知

本仓库是项目管理领域的**编排仓库**：大部分内容在子模块中。

- **子模块**（`apps/qtcloud-project`、`docs/*`、`packages/quanttide-project-toolkit`）：各自独立仓库，在主仓库**只提交指针更新**

## 提交规范

遵循 Conventional Commits，描述用中文，参照历史：

```
feat: 新增项目立项流程文档
docs: 更新项目监控章节
chore: update qtcloud-project submodule
```

- 类型：`feat` / `fix` / `refactor` / `docs` / `test` / `chore`
- 一次提交一个逻辑变更；文档与代码同批提交

## 子模块纪律

1. 先进入子模块仓库提交并推送，再回主仓库 `git add <子模块路径>` 更新指针
2. 不把子模块内容改作他用；主仓库 diff 中子模块条目只应是指针变化
3. `git submodule update --init --recursive` 初始化后开始工作

## 文档同步

| 变更 | 需同步 |
|------|--------|
| 新增/修改领域文档 | `README.md` 仓库结构表、`docs/` 对应子模块 |
| 子模块指针更新 | 主仓库 `CHANGELOG.md` |

## 验证

- 文档项目：`jupyter-book build index.md --site`（docs 子模块内）
- 推送前确认本地无未提交的文档/代码遗漏

## 不做的事

- 不在主仓库直接修改子模块内容（先提交到子模块仓库）
- 不擅自移除 `apps/`、`docs/`、`packages/` 等预留目录
