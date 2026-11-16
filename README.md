# 小贺 AI Skills Radar

以独立 Skill 源文件为单位的资料目录与仓库热度快照，和[小贺 AI Skills 目录](https://ai.xiao-he.top/skills.html)使用同一份数据与顺序。当前共 **309** 条资料，其中 **0** 条已抓到实际 SKILL.md；另外 **309** 条历史资料保留原来源，尚未定位并抓取源文件。

- [浏览中文 Skills 目录](https://ai.xiao-he.top/skills.html)
- [下载 JSON](data/skills-directory.json) · [下载 CSV](data/skills-directory.csv)
- [查看采集报告](data/latest-run.json) · [数据字段](docs/data-fields.md) · [采集与排序规则](docs/scoring-method.md)

数据快照：`2026-07-28`。网站发布成功后，发布流水线再同步本仓库；单独的采集成功记录不代表网站已发布。

> 自动采集不等于安装实测、安全审计或官方推荐。Stars、增长与热度均为仓库级快照，不是单个 Skill 的安装量。同一仓库中的不同 Skill 会共享这些仓库指标。

## 当前目录前 20 项

| 顺序 | Skill | 所属仓库 | 仓库 Stars | 仓库热度 | 详情 |
| ---: | --- | --- | ---: | ---: | --- |
| 1 | [find-skills](https://skills.sh/vercel-labs/skills/find-skills) | vercel-labs/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/find-skills.html) |
| 2 | [frontend-design](https://skills.sh/anthropics/skills/frontend-design) | anthropics/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/frontend-design.html) |
| 3 | [grill-me](https://skills.sh/mattpocock/skills/grill-me) | mattpocock/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/grill-me.html) |
| 4 | [agent-browser](https://skills.sh/vercel-labs/agent-browser/agent-browser) | vercel-labs/agent-browser | — | — | [中文资料](https://ai.xiao-he.top/skills/agent-browser-vercel-labs.html) |
| 5 | [vercel-react-best-practices](https://skills.sh/vercel-labs/agent-skills/vercel-react-best-practices) | vercel-labs/agent-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/vercel-react-best-practices.html) |
| 6 | [grill-with-docs](https://skills.sh/mattpocock/skills/grill-with-docs) | mattpocock/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/grill-with-docs.html) |
| 7 | [improve-codebase-architecture](https://skills.sh/mattpocock/skills/improve-codebase-architecture) | mattpocock/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/improve-codebase-architecture.html) |
| 8 | [tdd](https://skills.sh/mattpocock/skills/tdd) | mattpocock/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/tdd.html) |
| 9 | [web-design-guidelines](https://skills.sh/vercel-labs/agent-skills/web-design-guidelines) | vercel-labs/agent-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/web-design-guidelines.html) |
| 10 | [setup-matt-pocock-skills](https://skills.sh/mattpocock/skills/setup-matt-pocock-skills) | mattpocock/skills | — | — | [中文资料](https://ai.xiao-he.top/skills/setup-matt-pocock-skills.html) |
| 11 | [microsoft-foundry](https://skills.sh/microsoft/azure-skills/microsoft-foundry) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/microsoft-foundry.html) |
| 12 | [azure-ai](https://skills.sh/microsoft/azure-skills/azure-ai) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-ai.html) |
| 13 | [azure-diagnostics](https://skills.sh/microsoft/azure-skills/azure-diagnostics) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-diagnostics.html) |
| 14 | [azure-deploy](https://skills.sh/microsoft/azure-skills/azure-deploy) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-deploy.html) |
| 15 | [azure-prepare](https://skills.sh/microsoft/azure-skills/azure-prepare) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-prepare.html) |
| 16 | [azure-validate](https://skills.sh/microsoft/azure-skills/azure-validate) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-validate.html) |
| 17 | [azure-storage](https://skills.sh/microsoft/azure-skills/azure-storage) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-storage.html) |
| 18 | [entra-app-registration](https://skills.sh/microsoft/azure-skills/entra-app-registration) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/entra-app-registration.html) |
| 19 | [appinsights-instrumentation](https://skills.sh/microsoft/azure-skills/appinsights-instrumentation) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/appinsights-instrumentation.html) |
| 20 | [azure-resource-lookup](https://skills.sh/microsoft/azure-skills/azure-resource-lookup) | microsoft/azure-skills | — | — | [中文资料](https://ai.xiao-he.top/skills/azure-resource-lookup.html) |

## 身份与资料来源

已定位条目的身份为 `repository + SKILL.md 文件路径`，同仓库多个技能分别记录。历史资料未定位文件时，`skill_key` 和 `skill_path` 为空，`record_key` 使用明确的 `legacy:` 前缀，不根据名称猜路径。

用途摘要优先保留网站已整理的具体项目说明，再使用已抓源文件中的描述。原文不是中文时保留原文，不将仓库简介写成某个技能的能力。每条资料保留独立来源、源文件 SHA256、可用时的提交版本及采集时间；人工核对日期和运行测试状态分别记录。

本仓库不分发第三方完整 SKILL.md、脚本或依赖，仅保留来源元数据与用途摘要。使用具体技能时，应从对应上游取得完整目录，并核对其许可证与客户端支持。

## 历史安装量

`historical_installs` 仅保留原 Skills.sh 快照的累计安装量，必须同时看 `historical_installs_snapshot_at`、指标名称和来源 URL。它不被当作今天的安装量，也不替代当前仓库 Stars。

## 更正资料

欢迎通过 Issue 提供源文件迁移、错误用途、许可证或错误匹配的公开证据。请给出具体仓库、文件路径和观察日期。本站为独立中文资料站，与被收录项目没有默认官方隶属关系。
