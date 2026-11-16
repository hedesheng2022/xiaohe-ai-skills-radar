# 采集与排序

条目以实际 SKILL.md 为单位，目录不是把一个技能集合仓库包装成一个技能。采集器读取源文件名称、描述及可核对的文件信息，通过配置的准入条件后进入目录；下载成功不代表可安装或运行成功。

仓库 Stars、历史 Stars 增长与仓库活跃度是热度信号，只说明公开关注程度。同仓库的各技能共享仓库指标，不能据此推断每个技能的安装量、质量或任务表现。历史不足时增长保持为空。

导出顺序直接复用网站的 `skillsDirectoryData`，不在数据仓库另算一套排名。未抓取源文件的历史资料保留为历史资料，不因为有旧安装量而宣称已核验。

本次准入配置快照（以站点采集器解释为准）：

```json
{
  "schemaVersion": 1,
  "targetCount": 3000,
  "maximumCount": 6000,
  "dailyNewLimit": 450,
  "maxDocumentsPerRun": 650,
  "maxRepositoriesPerRun": 12,
  "maxApiRequests": 50,
  "githubPages": 1,
  "requestTimeoutMs": 18000,
  "maxDocumentBytes": 262144,
  "historyDays": 90,
  "reviewAfterUnseenDays": 60,
  "minimumRepositoryStars": 5,
  "internalAutomationPathSegments": [
    ".automations",
    ".vc"
  ],
  "seedRepositories": [
    "openai/skills",
    "anthropics/skills",
    "vercel-labs/skills",
    "vercel-labs/agent-skills",
    "microsoft/skills",
    "mattpocock/skills"
  ],
  "searchQueries": [
    "topic:agent-skills archived:false fork:false stars:>=5",
    "\"agent skills\" in:description archived:false fork:false stars:>=20"
  ],
  "excludedPathSegments": [
    "node_modules",
    "vendor",
    "fixtures",
    "__fixtures__",
    "testdata",
    "examples",
    "tests",
    "__tests__",
    ".git",
    ".automations",
    ".vc"
  ],
  "excludedRepositories": [],
  "policy": {
    "targetIsCapacityNotQuota": true,
    "requireActualSkillDocument": true,
    "repositoryStarsAreNotSkillInstalls": true,
    "preserveExistingUrls": true,
    "monthlyReviewNeverDeletesAutomatically": true,
    "machineAdmissionIsNotEditorialReview": true,
    "identicalDocumentShaHasOnePublicPrimary": true,
    "retainDuplicateSourceEvidence": true,
    "internalRepositoryAutomationsRequireResearch": true,
    "formalCollectionRequiresReleaseGate": true
  }
}
```

报告分别记录已采集、更新、拒绝及发布状态。无独立价值或来源不足的候选可以不收录；目录规模目标不等于内容配额。既有公开 URL 的退出与承接由网站发布策略处理，数据仓库本身不删除网站页面或改变索引策略。
