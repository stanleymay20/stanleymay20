# Canonical Repository Registry

This registry is the public portfolio source of truth for project-family identity. It is intentionally conservative: a repository becomes **canonical** only when the controlled project state supports that conclusion. A generated or prettier name is not enough.

| Project family | Canonical / current target | Status | Notes |
|---|---|---|---|
| AgentShield | `demo-repo` | **FLAGSHIP / canonical identity pending** | Controlled implementation spans dedicated branches. Rename/default-branch integration deferred until v14 evidence is frozen. |
| HumanOS | `humanos-life-interface` | **Strategic private flagship** | Keep distinct from AgentShield; HumanOS is the human-facing orchestration product, AgentShield is the security boundary. |
| AICIS | `aicis-divine-core-6d24171b` | **CANONICAL** | Preserve `AICIS-control` until component-vs-duplicate role is verified. |
| Quantivis | `quantisights-pro-c6abd242` | **CANONICAL** | Generated suffix is naming debt, not a reason to move prematurely. |
| ScrollLibrary | `scroll-wisdom-weave-d69aa349` | **CANONICAL** | Other `scroll-wisdom-weave*` repos require content/history comparison before deprecation. |
| ScrollIntel | `scrollintel-ai-system` | **CANONICAL CANDIDATE** | Verify against `scroll-intel`; two other names are currently empty. |
| Apply Wingman | `apply-wingman` | **CANONICAL** | Compare `JobAutoPilot` for unique ATS/application logic before deprecation. |
| AutoMarketer | `app-automarketer-891ef675` | **CANONICAL CANDIDATE** | Compare with `app-automarketer`. |
| ScrollJustice | `scroll-justice-prophecy-ai-40` | **CANONICAL CANDIDATE** | Compare public predecessor and related justice repos before consolidation. |
| Adelaide finance | `adelaide-ledger-ai` | **CANONICAL CANDIDATE** | `AdelaideAccounts` empty; `AdelaideAI` near-empty. Verify history before deprecation. |
| AI Studio | `stanley-ai-studio` | **CANONICAL CANDIDATE** | `AI_Studio` currently empty. |
| ScrollCloud | split role | **COMPONENT FAMILY** | `-ScrollCloud-Core` and `scrollcloud-front` appear role-separated, but backend/core is near-empty and naming needs repair. |
| News summarization | unresolved | **VERIFY-CONSOLIDATION** | Compare `news-summarizer` and `text-summarization-news-aggregation`. |
| Billionaires analysis | unresolved | **ACADEMIC DUPLICATE CHECK** | Compare `billionaires-net-worth-analysis` and `Billionaires_Analysis_Project`. |

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
