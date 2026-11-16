# 数据字段

| 字段 | 口径 |
| --- | --- |
| `record_key` | 数据记录的稳定键；未定位源文件的旧资料带 legacy 前缀 |
| `skill_key` / `skill_path` | 抓取实际源文件后才填写的仓库加文件路径身份 |
| `source_document_…` | 真实源文件的 URL、引用、提交 SHA、内容 SHA256、字节数与抓取时间 |
| `source_copies` | 内容 SHA256 相同的其他来源，保留独立仓库、文件路径、精确提交与抓取时间，不因此新增页面 |
| `source_summary_captured_at` | 旧摘要来源快照时间，不等于本次抓取或人工复核时间 |
| `summary` / `summary_language` | 与网站同源的用途摘要；英文来源不会伪装成人工中文审核 |
| `repository_stars` / `repository_star_delta_7d` / `repository_heat_score` | 仓库级公开热度，未知时为空 |
| `repository_captured_at` | 仓库元数据快照时间 |
| `source_reviewed_at` | 已有明确人工来源核对记录的日期；抓到文件不会自动设置此日期 |
| `runtime_tested` | 既有资料是否明确记载运行测试；自动抓取不把它设置为真 |
| `license` | 采集器记录的许可证及其来源/状态，不自动推定技能文件采用仓库整体许可 |
| `historical_installs…` | 旧榜单的安装量、指标、时间与来源，和当前仓库热度分开 |

`captured_at` 是当前雷达快照时间。某条记录自己的源文件、仓库指标和摘要可能来自不同时间，引用时应保留对应字段。未知值使用 null，不伪造为零。
