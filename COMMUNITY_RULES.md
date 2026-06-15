# QUANTSKILLS 社区规则 / Community Rules

> 默认优先显示中文版。English version follows the Chinese version.

中文版是本文件的默认阅读版本。英文版用于国际贡献者参考。

## 中文版（默认）

QUANTSKILLS 是一个面向 Quant Skills 和 Agents 的开放社区。

这些规则刻意保持轻量。它们的目标是保护贡献者、项目质量，以及 QUANTSKILLS 生态的长期可信度。

### 1. 尊重贡献者

请在 Issues、Pull Requests、Discussions、代码评审和项目评论中保持尊重。

社区不允许骚扰、人身攻击、威胁、歧视，或反复出现的敌意行为。

### 2. 禁止垃圾内容或误导性项目

不要提交垃圾内容、虚假项目、误导性声明、标题党、恶意推广，或低质量仓库噪音。

项目标题、描述和 README 文件应当真实说明项目内容。

### 3. 禁止非法、侵权或不安全内容

不要上传或提交非法内容、侵权材料、恶意代码、泄露数据、私有数据集、盗版文档，或不安全的操作说明。

如果项目使用第三方代码、数据、论文或报告，请注明来源并遵守相关许可证。

### 4. 明确项目状态

成员创建的仓库默认属于 Community Projects。

未经审核的项目不得宣称自己是 QUANTSKILLS 官方、认证、验证、背书或生产可用项目。

除非项目已经过审核并获得批准，否则应避免使用暗示官方身份的名称或徽章。

### 5. 仓库命名与项目声明

QUANTSKILLS 组织下的仓库应使用以下小写前缀之一：

- `skill-`：用于可复用能力，例如因子、策略模板、数据处理、报告复现、验证工具、研究组件、提示词、示例或工具
- `agent-`：用于 AI Agents 或自动化工作流，例如研究复现 Agent、策略审计 Agent、数据处理 Agent、评审 Agent 或多步骤任务系统

示例：

- `skill-five-day-momentum`
- `skill-report-replication`
- `skill-factor-validation`
- `agent-research-replication`
- `agent-strategy-auditor`

仓库名称应使用小写字母，并使用连字符，而不是空格或下划线。

每个仓库根目录应包含一个声明文件：

- Skill 仓库使用 `SKILL.md`
- Agent 仓库使用 `AGENTS.md`

声明文件应说明项目做什么、如何使用、由谁维护、支持哪些场景，以及有哪些重要限制。

每个仓库还应在 `SKILL.md`、`AGENTS.md`，或 `skill.yml` / `agent.yml` 等项目清单中声明上游组织和仓库元数据。

示例：

```yaml
metadata:
  organization: QuantSkills
  organization_url: https://github.com/quantskills
  repository: skill-quant-factor-directional-alpha
  repository_url: https://github.com/quantskills/skill-quant-factor-directional-alpha
  project_type: skill
  collection: directional-alpha
```

这有助于 AI Agents、注册表工具、维护者和下游用户在项目被复制、fork、下载或索引后，识别项目的上游来源。

QUANTSKILLS 可以使用 AI 辅助工具扫描组织仓库，读取仓库名称、`SKILL.md` / `AGENTS.md`、README 文件和描述，并协助维护公开注册表。

最终的收录、推荐、验证或官方认可仍需维护者审核。

### 6. 尊重作者署名与许可证

请尊重原作者署名、贡献历史和开源许可证。

在改编策略、论文、数据集或代码时，请提供归因，并说明改动内容。

### 7. 禁止敏感信息

不要在公开 Issues、Pull Requests、README 文件或仓库内容中发布电话号码、微信号、电子邮箱、政府证件号码、密码、API key、私有 token、私人账号凭据、私有数据集或机密文档。

如果确实需要私下跟进，维护者会安排更安全的沟通渠道。

### 8. 量化项目必须说明边界

涉及因子、策略、回测、交易信号或投资工作流的项目，应清楚说明：

- 数据来源
- 假设条件
- 参数
- 已知限制
- 风险边界
- 项目是否仅为研究或教育示例

不得承诺收益，也不得暗示某个策略是安全、保证盈利或构成投资建议。

### 9. 维护者治理

维护者可以在必要时提醒贡献者、要求修改、关闭 Issues 或 Pull Requests、编辑标签、限制访问、归档仓库、转移仓库或删除仓库。

这些情况可能包括安全问题、法律风险、垃圾内容、无人维护项目、命名冲突、敏感数据暴露、误导性声明，或违反本规则。

### 10. 治理原则

低门槛加入，高标准验证。

我们鼓励贡献者实验和发布项目，同时 QUANTSKILLS 会把官方认可保留给清晰、有用、可维护，并经过适当验证的项目。

---

## English Version

QUANTSKILLS is an open community for Quant Skills and Agents.

These rules are intentionally lightweight. They are designed to protect contributors, project quality, and the long-term credibility of the QUANTSKILLS ecosystem.

### 1. Respect Contributors

Be respectful in Issues, Pull Requests, Discussions, reviews, and project comments.

Harassment, personal attacks, threats, discrimination, or repeated hostile behavior are not allowed.

### 2. No Spam or Misleading Projects

Do not submit spam, fake projects, misleading claims, clickbait, malicious promotion, or low-effort repository noise.

Project titles, descriptions, and README files should describe the project honestly.

### 3. No Illegal, Infringing, or Unsafe Content

Do not upload or submit illegal content, infringing materials, malicious code, leaked data, private datasets, pirated documents, or unsafe instructions.

If a project uses third-party code, data, papers, or reports, cite the source and respect the license.

### 4. Clear Project Status

Member-created repositories are Community Projects by default.

Do not present an unreviewed project as official, certified, verified, endorsed, or production-ready by QUANTSKILLS.

Avoid names or badges that imply official status unless the project has been reviewed and approved.

### 5. Repository Naming and Project Declaration

Repositories under the QUANTSKILLS organization should use one of the following lowercase prefixes:

- `skill-` for reusable capabilities, such as factors, strategy templates, data processing, report replication, validation utilities, research components, prompts, examples, or tools
- `agent-` for AI Agents or automated workflows, such as research replication agents, strategy audit agents, data processing agents, review agents, or multi-step task systems

Examples:

- `skill-five-day-momentum`
- `skill-report-replication`
- `skill-factor-validation`
- `agent-research-replication`
- `agent-strategy-auditor`

Repository names should be lowercase and use hyphens instead of spaces or underscores.

Each repository should include a declaration file at the repository root:

- `SKILL.md` for Skill repositories
- `AGENTS.md` for Agent repositories

The declaration file should explain what the project does, how to use it, who maintains it, what scenarios it supports, and any important limitations.

Each repository should also declare its upstream organization and repository metadata in `SKILL.md`, `AGENTS.md`, or a project manifest such as `skill.yml` / `agent.yml`.

Example:

```yaml
metadata:
  organization: QuantSkills
  organization_url: https://github.com/quantskills
  repository: skill-quant-factor-directional-alpha
  repository_url: https://github.com/quantskills/skill-quant-factor-directional-alpha
  project_type: skill
  collection: directional-alpha
```

This helps AI Agents, registry tools, maintainers, and downstream users identify the upstream source of a project after it is copied, forked, downloaded, or indexed.

QUANTSKILLS may use AI-assisted tools to scan organization repositories, read repository names, `SKILL.md` / `AGENTS.md`, README files, and descriptions, then help maintain the public registry.

Final listing, recommendation, validation, or official recognition still requires maintainer review.

### 6. Respect Authorship and Licensing

Respect original authorship, contribution history, and open-source licenses.

When adapting strategies, papers, datasets, or code, provide attribution and explain what has been changed.

### 7. No Sensitive Information

Do not post phone numbers, WeChat IDs, email addresses, government IDs, passwords, API keys, private tokens, private account credentials, private datasets, or confidential documents in public Issues, Pull Requests, README files, or repository content.

If private follow-up is needed, maintainers will arrange a safer channel.

### 8. Quant Work Must Include Boundaries

Projects involving factors, strategies, backtests, trading signals, or investment workflows should clearly state:

- Data source
- Assumptions
- Parameters
- Known limitations
- Risk boundaries
- Whether the project is only a research or educational example

Do not promise returns or imply that a strategy is safe, guaranteed, or investment advice.

### 9. Maintainer Moderation

Maintainers may remind contributors, request changes, close Issues or Pull Requests, edit labels, restrict access, archive repositories, transfer repositories, or delete repositories when necessary.

This may happen for security issues, legal risk, spam, abandoned projects, naming conflicts, sensitive data exposure, misleading claims, or violations of these rules.

### 10. Governance Principle

Low barrier to join. High standard for validation.

Contributors are encouraged to experiment and publish, while QUANTSKILLS reserves official recognition for projects that are clear, useful, maintainable, and appropriately validated.
