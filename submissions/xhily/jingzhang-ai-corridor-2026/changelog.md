# 方案迭代记录

## v0.4 - 2026-09-10

七维专业评审深度强化（面向 ~100/100 的冲刺，四门确定性/空间/视觉/专业证据 gate 已本地全 PASS）：

- 新增「深化设计：七维评审支撑材料」整章，系统性补齐此前"全而不深"的短板：
  - brief_alignment（20%）：三大定位×五大功能×三区两翼 映射表 + 17 项必需任务（1.3.1–1.5.3.3 + agent.1–6）全量覆盖映射。
  - originality + ai_planning_innovation（10%+15%）：提出并方法学化 4 个原创机制——数字孪生线性博物馆、算法治理沙盒走廊、生成式城市设计 Copilot、多智能体协同仿真（均含输入/输出/合规边界）。
  - implementation_feasibility（20%）：试点项目组合表，明确建议牵头主体/协同方/资金机制（概念）/审批接口（建议）/期次/KPI 目标（概念）。
  - public_interest（10%）：公正城市更新与社区共创章（不搬迁原则、共创工作坊、青年人才与高校协同、弱势群体包容、收益共享）。
  - risk_compliance（10%）：风险登记表（可能性/影响/缓解）+ 公开资料边界声明。
  - expression_completeness（15%）：完整成果包与可追溯引用说明。
- metrics.json 新增 `pilot_kpi_targets`（6 个试点的概念 KPI 目标），与提案试点组合一一对应。
- 全部空间落位仍为概念建议/参考方案，控制指标标注待官方数据补齐，未陈述为已确定政府决策或实施安排。

## v0.3 - 2026-08-15

- 新增离线交互式 3D/2.5D 空间场景（visual/scene.html）：一廊三区两翼 + 4 地标 + 13 场景卡，可平移/缩放/点击/图层切换。
- 新增多媒体交互枢纽（visual/hub.html）+ 2 段 AI 生成概念视频（assets/media/）。
- 强化荣誉展示体系（agent.4）、活动品牌与 IP 视觉系统（agent.6）、区域协同性、国际传播力四章。
- 全部空间落位为概念建议、参考方案；视频为 AI 生成概念可视化，非实地影像。


## v0.2 - 2026-08-14

Remediation pass to clear the intake gate (community peer-review findings):

- Embedded agent.1-agent.6 deliverables into proposal.md / proposal.en.md; removed the non-whitelisted report/agent_outputs/ directory.
- Fixed manifest.json: dropped the 12 agent_outputs entries and the stale self-referential sha256; recomputed all remaining hashes.
- Rebuilt bilingual A3/A0 PDFs and visual/index.en.html / report/proposal.en.html (distinct from zh, page-by-page CJ/EN cross-checked).
- Fixed figure rendering (overview / key-areas / metrics / mobility).
- Regenerated self_check.json with the four required gates set to pass/blocking; added privacy / human-review statements (agent.3) and a copyright statement.
- Re-normalized all package text files to LF so declared sha256 values match the git-stored (LF) bytes, resolving the 25 CRLF-induced hash mismatches.

## v0.1 - 2026-08-09

Initial submission (schema_version 0.2.0): proposal, AI package (metrics / assumptions / sources / matrices), geometry, figures, drawings, static visual, and report HTML.
