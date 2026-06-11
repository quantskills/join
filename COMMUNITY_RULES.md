# QUANTSKILLS Community Rules

QUANTSKILLS is an open community for Quant Skills, Agents, and Strategies.

These rules are intentionally lightweight. They are designed to protect contributors, project quality, and the long-term credibility of the QUANTSKILLS ecosystem.

## 1. Respect Contributors

Be respectful in Issues, Pull Requests, Discussions, reviews, and project comments.

Harassment, personal attacks, threats, discrimination, or repeated hostile behavior are not allowed.

## 2. No Spam or Misleading Projects

Do not submit spam, fake projects, misleading claims, clickbait, malicious promotion, or low-effort repository noise.

Project titles, descriptions, and README files should describe the project honestly.

## 3. No Illegal, Infringing, or Unsafe Content

Do not upload or submit illegal content, infringing materials, malicious code, leaked data, private datasets, pirated documents, or unsafe instructions.

If a project uses third-party code, data, papers, or reports, cite the source and respect the license.

## 4. Clear Project Status

Member-created repositories are Community Projects by default.

Do not present an unreviewed project as official, certified, verified, endorsed, or production-ready by QUANTSKILLS.

Avoid names or badges that imply official status unless the project has been reviewed and approved.

## 5. Repository Naming and Project Declaration

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
- `AGENT.md` for Agent repositories

The declaration file should explain what the project does, how to use it, who maintains it, what scenarios it supports, and any important limitations.

Each repository should also declare its upstream organization and repository metadata in `SKILL.md`, `AGENT.md`, or a project manifest such as `skill.yml` / `agent.yml`.

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

QUANTSKILLS may use AI-assisted tools to scan organization repositories, read repository names, `SKILL.md` / `AGENT.md`, README files, and descriptions, then help maintain the public registry.

Final listing, recommendation, validation, or official recognition still requires maintainer review.

## 6. Respect Authorship and Licensing

Respect original authorship, contribution history, and open-source licenses.

When adapting strategies, papers, datasets, or code, provide attribution and explain what has been changed.

## 7. No Sensitive Information

Do not post phone numbers, WeChat IDs, email addresses, government IDs, passwords, API keys, private tokens, private account credentials, private datasets, or confidential documents in public Issues, Pull Requests, README files, or repository content.

If private follow-up is needed, maintainers will arrange a safer channel.

## 8. Quant Work Must Include Boundaries

Projects involving factors, strategies, backtests, trading signals, or investment workflows should clearly state:

- Data source
- Assumptions
- Parameters
- Known limitations
- Risk boundaries
- Whether the project is only a research or educational example

Do not promise returns or imply that a strategy is safe, guaranteed, or investment advice.

## 9. Maintainer Moderation

Maintainers may remind contributors, request changes, close Issues or Pull Requests, edit labels, restrict access, archive repositories, transfer repositories, or delete repositories when necessary.

This may happen for security issues, legal risk, spam, abandoned projects, naming conflicts, sensitive data exposure, misleading claims, or violations of these rules.

## 10. Governance Principle

Low barrier to join. High standard for validation.

Contributors are encouraged to experiment and publish, while QUANTSKILLS reserves official recognition for projects that are clear, useful, maintainable, and appropriately validated.
