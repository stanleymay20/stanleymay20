# Canonical Repository Registry

This registry is the public portfolio source of truth for project-family identity. It is intentionally conservative: a repository becomes **canonical** only when the controlled project state supports that conclusion. A generated or prettier name is not enough.

| Project family | Canonical / current target | Status | Notes |
|---|---|---|---|
| AgentShield | `demo-repo` | **FLAGSHIP / canonical identity pending** | Controlled implementation spans dedicated branches. Rename/default-branch integration deferred until v14 evidence is frozen. |
| HumanOS | `humanos-life-interface` | **Strategic private flagship / VERIFIED** | Keep distinct from AgentShield; HumanOS is the human-facing orchestration product, AgentShield is the security boundary. Read-only CI passes locked install, lint, 67 tests and production build; the permanent dependency audit passes production-moderate and full-tree-high thresholds. |
| AICIS | `aicis-divine-core-6d24171b` | **CANONICAL** | Preserve `AICIS-control` until component-vs-duplicate role is verified. |
| Quantivis | `quantisights-pro-c6abd242` | **CANONICAL** | Generated suffix is naming debt, not a reason to move prematurely. |
| ScrollLibrary | `scroll-wisdom-weave-d69aa349` | **CANONICAL** | Other `scroll-wisdom-weave*` repos require content/history comparison before deprecation. |
| ScrollIntel | `scrollintel-ai-system` | **CANONICAL / RESOLVED** | `scroll-intel` is explicitly retained as a superseded legacy prototype and points to the maintained successor, which contains the broader multi-agent platform, frontend/backend layers, deployment tooling, monitoring and tests. |
| Apply Wingman | `apply-wingman` | **CANONICAL / RESOLVED** | `JobAutoPilot` is retained only as historical lineage. Its current tree is empty and its reachable pre-empty history contains cleanup artifacts rather than recoverable application source; the maintained ATS/application system lives in `apply-wingman`. |
| AutoMarketer | `app-automarketer-891ef675` | **CANONICAL / RESOLVED** | `app-automarketer` explicitly declares itself superseded and points to the maintained Universal AI Growth OS implementation. The canonical current tree is protected against committed environment files and uses a safe `.env.example`. |
| ScrollJustice | `scroll-justice-prophecy-ai-40` | **CANONICAL CANDIDATE** | Compare public predecessor and related justice repos before consolidation. |
| Adelaide finance | `adelaide-ledger-ai` | **CANONICAL CANDIDATE** | `AdelaideAccounts` empty; `AdelaideAI` near-empty. Verify history before deprecation. |
| AI Studio | `stanley-ai-studio` | **CANONICAL / RESOLVED** | `AI_Studio` contains only the legacy placeholder and now redirects to `stanley-ai-studio`, which contains the application source and deployment/project assets. |
| ScrollCloud | split role | **COMPONENT FAMILY** | `-ScrollCloud-Core` and `scrollcloud-front` appear role-separated, but backend/core is near-empty and naming needs repair. |
| News summarization | unresolved | **VERIFY-CONSOLIDATION** | The later `text-summarization-news-aggregation` has a cleaner modular `src/` layout, while `news-summarizer` contains additional notebook/Flask/image-workflow material and repository clutter. Preserve both until unique functionality is compared. |
| Billionaires analysis | `billionaires-net-worth-analysis` | **CANONICAL / RESOLVED** | `Billionaires_Analysis_Project` is already marked as a superseded legacy shell and points to the canonical repository, which contains the R Markdown source, R code, rendered output and assessment. |

## Canonicalization rules

A repository is promoted to canonical only after checking, as applicable:

- latest meaningful commit/history;
- unique source files and migrations;
- database schema/migration lineage;
- CI/workflow evidence;
- releases and tags;
- deployment configuration;
- issues and pull-request history;
- documentation/evidence packs;
- controlled SHA or publication state;
- external links/domains depending on the repository name.

## Superseded-repository policy

When a predecessor is confirmed superseded:

1. preserve it long enough to capture unique history/evidence;
2. add a clear README notice pointing to the canonical repository;
3. avoid accepting new feature work there;
4. archive rather than delete by default;
5. retain it permanently when it carries controlled experiment/publication provenance that should remain independently inspectable.

## Naming target

Canonical product names should eventually converge on simple lowercase kebab-case identities such as:

- `agentshield`
- `aicis`
- `quantivis`
- `scrolllibrary`
- `scrollintel`
- `apply-wingman`

Renaming is a **later** step. Do not rename a canonical repository until CI, package imports, deployment URLs, documentation links, submodules, badges, webhooks and external references have been checked.
