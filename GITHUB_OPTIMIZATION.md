# GitHub Portfolio Optimization Programme

Controlled portfolio baseline: **100 owned repositories** reviewed through the connected GitHub account on 2026-09-11.

The objective is not to delete history. It is to make the account read like a coherent engineering portfolio: a small number of flagship systems, a visible incubation layer, a separate academic/evidence layer, and a controlled consolidation/archive queue.

The portfolio classification lives in [PROJECT_PORTFOLIO.md](PROJECT_PORTFOLIO.md). This file is the **live cleanup ledger** and should emphasize unresolved work rather than repeatedly re-listing settled families.

## Operating rules

1. Do not delete a repository because its name looks duplicated.
2. Compare canonical candidates at commit/tree/content/history level before consolidation.
3. Preserve migrations, CI evidence, releases, tags, issues, PRs, experiment lineage and controlled SHA gates.
4. Prefer archive/deprecation over deletion for public predecessors.
5. Do not restructure a branch while a controlled experiment is running.
6. Public repositories should either demonstrate meaningful work or clearly state that they are historical/reference repositories.
7. Private incubations do not need to compete for attention on the public profile.
8. Mark a repository **VERIFIED** only after permanent read-only quality/security gates pass and temporary write-enabled repair workflows are removed.
9. A resolved canonical does not automatically authorize deleting or archiving siblings; unique-history checks still apply.

## Closed / resolved families

### AutoMarketer

- `app-automarketer-891ef675` — **CANONICAL / RESOLVED / VERIFIED**.
- Permanent CI and dependency-security gates passed after controlled dependency repair.
- Temporary writer removed.
- `app-automarketer` remains historical/consolidation evidence until its own final archive decision is made.

### Adelaide finance

- `adelaide-ledger-ai` — **CANONICAL / RESOLVED / VERIFIED**.
- Permanent read-only CI passes locked install, lint, application/tooling TypeScript checks and production build.
- Permanent dependency audit passes locked install, direct dependency-tree validation, production audit and full-tree audit.
- The committed npm dependency tree reported **0 known vulnerabilities** under both audit gates at verification.
- Final cleanup head after temporary-writer removal: `5d0fbcb46a84eee237bcab46794664775f1ab1a5`.
- `AdelaideAccounts` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. Repository contains only its superseded README; no unique application source.
- `AdelaideAI` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. Current/history inspection shows only the project shell, LICENSE and superseded README; no unique application source.

### News summarization

- `text-summarization-news-aggregation` — **CANONICAL ACADEMIC SUCCESSOR / LINEAGE RESOLVED / NOT PRODUCTION-VERIFIED**.
- `news-summarizer` — **HISTORICAL PROTOTYPE / PRESERVE**.
- Chronology: predecessor active through 2024-09-18; structured successor began 2024-09-26.
- Shared lineage: NewsAPI ingestion, T5 summarization and WordPress publishing.
- Unique predecessor evidence intentionally preserved: Reuters archive scraping, TF-IDF extractive summarization and Flask `/summarize` trigger.
- The successor now contains `LINEAGE.md` and an accurate README. Its historical workflow is under `github/workflows/`, not `.github/workflows/`, and is intentionally **not active**; no external publishing automation was enabled during cleanup.

### Billionaire net-worth analysis

- `billionaires-net-worth-analysis` — **CANONICAL ACADEMIC / EVIDENCE REPOSITORY — LINEAGE RESOLVED**.
- Contains the R Markdown source, R analysis code, rendered HTML, figures, TeX/log outputs and applied-statistics assessment PDF.
- `Billionaires_Analysis_Project` — **SUPERSEDED LEGACY SHELL / SAFE ARCHIVE CANDIDATE**.
- Its 2024 initial commit contained only the MIT LICENSE and one-line README; no unique analysis source was ever present in that repository.

## Active consolidation queue

### AgentShield

Current repository identity: `demo-repo`.

Do not rename or change the default branch while the controlled AgentShield experiment/evidence line remains active. Once frozen, integrate the controlled product/research lineages, preserve experiment evidence and replace the demo identity with AgentShield-specific metadata.

### AICIS

Canonical target: `aicis-divine-core-6d24171b`.

Still compare:

- `aicis-divine-core`
- `aicis-divine-core-b1d2f00f`
- `AICIS-control` — determine whether genuine control-plane component or overlapping workspace.

### Quantivis

Canonical target: `quantisights-pro-c6abd242`.

Still compare:

- `quantisights-pro`
- `quantisights-pro-e4e7e290`
- `quantisights-pro-ff2bbabf`

### ScrollLibrary

Canonical target: `scroll-wisdom-weave-d69aa349`.

Still compare:

- `scroll-wisdom-weave`
- `scroll-wisdom-weave-370c9253`
- `scroll-wisdom-weave-94f4588f`
- `scroll-wisdom-weave-ffcd64d1`

### ScrollIntel

Canonical candidate: `scrollintel-ai-system`.

Still compare:

- `scroll-intel`
- `ScrollIntel` — empty/private shell candidate.
- `scrollintel.` — empty public shell with trailing-punctuation naming debt.

### Apply Wingman

Canonical: `apply-wingman`.

Compare `JobAutoPilot`; preserve unique ATS-routing/application logic before deprecation.

### ScrollJustice

Compare:

- `scroll-justice-prophecy-ai-40`
- `scroll-justice-prophecy-ai`
- `FastTrackJusticeAI`
- `legal-case-updater.`

Do not infer canonical status from names alone; earlier dependency experiments do not substitute for family-level source/history verification.

### ScrollCloud

Review together:

- `-ScrollCloud-Core`
- `scrollcloud-front`
- `Cloud-2.0`
- `PushBridge`
- `pushbridge-blueprint`

Determine intentional component boundaries before any rename/archive decision.

## Remaining high-confidence shell / noise checks

These are empty or near-empty candidates that still need a final history/reference check before archive/private decisions:

- `AI_Studio`
- `clinical-ai-platform` — private
- `Cloud-2.0` — private
- `curry36-chatbot`
- `Data-Integrartion` — misspelled
- `legal-case-updater.` — trailing punctuation
- `perceptron`
- `PromptTube`
- `pushbridge-blueprint`
- `SAVIOR`
- `ScrollIntel` — private
- `scrollintel.` — trailing punctuation
- `stanleymay20.github.io`
- `-ScrollCloud-Core` — leading punctuation
- `PushBridge`

Resolved Adelaide shells have been removed from this queue.

## Naming debt

Normalize names only after link, deployment, CI and external-reference impact is checked:

- `demo-repo` → future AgentShield-specific identity
- `-ScrollCloud-Core` → remove leading hyphen
- `Kingdom-Wealth-` → remove trailing hyphen
- `legal-case-updater.` → remove trailing period
- `scrollintel.` → remove trailing period
- `machine-learniing` → correct spelling
- `Data-Integrartion` → correct spelling
- generated suffixes such as `-6d24171b`, `-c6abd242`, `-d69aa349`, `-891ef675` → remove only after canonical lineage is verified

Preferred product naming:

`product-name`  
`product-name-api`  
`product-name-web`  
`product-name-infra`  
`product-name-research`

## Public/private strategy

**Public:** flagship products with professional documentation; selected academic/data evidence; intentional open-source components; historical repositories only when clearly marked as superseded/reference.

**Private:** early product incubations, unfinished concepts, internal infrastructure and duplicated generated workspaces whose public state adds noise but no portfolio evidence.

Do not hide failed or negative research when it forms part of a controlled scientific lineage.

## Repository quality standard

Flagship/canonical repositories should converge on:

- clear product name and one-sentence purpose;
- architecture/threat-model documentation where relevant;
- reproducible installation/setup instructions;
- explicit maturity status;
- deterministic dependency management;
- tests and permanent read-only CI;
- security/release gates appropriate to the project;
- no committed credentials;
- license decision;
- contribution/security policy where public collaboration is intended;
- canonical repository marker when predecessor repositories exist;
- release/version history for production-facing systems.

## Public portfolio target

A visitor should primarily see roughly **8–12 flagship/evidence projects**, currently centered on AgentShield, AICIS, Quantivis, ScrollLibrary, ScrollIntel, Apply Wingman, the EU innovation/AI/energy analytics work, AI Sustainability Dashboard and the AI Engineering publication/project.

The account may retain substantial historical/internal repositories, but public navigation should make the canonical project for each family unambiguous.
