# CHANGELOG — legal-research-skill（PAEG 工具生态 14.4 法律检索）

## v0.1.1 (2026-08-28) — 基线结构修复（第一波审计 FIX-1/FIX-2）

**更新路径**：legal-research/SKILL.md

- FIX-1：恢复「第二阶段：系统性检索」标题（八阶段工作流恢复连续）
- FIX-2：「指导性案例第237号」层级修正（## → #### 附示例）
- 基线审计：5/5 保留项 PASS（六类用户分层/AskUserQuestion 主动问询/八阶段/法源覆盖/输出规范）

## v0.1.0 (2026-08-28) — 顶尖化补齐 + 发布

**更新路径**：src/{legal_validator, case_retriever, legal_reasoning}.py + use_database_by_api/db_adapter.py + mcp_server.py + web/

- 校验机制（效力/时效/引用）、案例关键词检索、法律推理方法（演绎/归纳/类比/溯因）
- 数据库接入（威科/北大法宝/裁判文书网，用户可配置）
- MCP 9 工具 + 独立网页（6 工具面板）
- SKILL.md 能力升级章节
- 测试 32 全绿
