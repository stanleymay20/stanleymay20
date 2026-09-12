# GitHub Portfolio Optimization Programme

Controlled portfolio baseline: **100 owned repositories** reviewed through the connected GitHub account on 2026-09-11.

The objective is not to delete history. It is to make the account read like a coherent engineering portfolio: a small number of flagship systems, a visible incubation layer, a separate academic/evidence layer, and a controlled consolidation/archive queue.

The portfolio classification lives in [PROJECT_PORTFOLIO.md](PROJECT_PORTFOLIO.md). This file is the **live cleanup ledger** and emphasizes unresolved work rather than repeatedly re-listing settled families.

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
- `AdelaideAccounts` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. No unique application source.
- `AdelaideAI` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. Only project-shell history, LICENSE and superseded README; no unique application source.

### News summarization

- `text-summarization-news-aggregation` — **CANONICAL ACADEMIC SUCCESSOR / LINEAGE RESOLVED / NOT PRODUCTION-VERIFIED**.
- `news-summarizer` — **HISTORICAL PROTOTYPE / PRESERVE**.
- Chronology: predecessor active through 2024-09-18; structured successor began 2024-09-26.
- Shared lineage: NewsAPI ingestion, T5 summarization and WordPress publishing.
- Unique predecessor evidence intentionally preserved: Reuters archive scraping, TF-IDF extractive summarization and Flask `/summarize` trigger.
- The successor contains `LINEAGE.md` and an accurate README. Its historical workflow is under `github/workflows/`, not `.github/workflows/`, and remains intentionally inactive.

### Billionaire net-worth analysis

- `billionaires-net-worth-analysis` — **CANONICAL ACADEMIC / EVIDENCE REPOSITORY — LINEAGE RESOLVED**.
- Contains the R Markdown source, R analysis code, rendered HTML, figures, TeX/log outputs and applied-statistics assessment PDF.
- `Billionaires_Analysis_Project` — **SUPERSEDED LEGACY SHELL / SAFE ARCHIVE CANDIDATE**.
- Its 2024 initial commit contained only the MIT LICENSE and one-line README; no unique analysis source was ever present there.

### ScrollIntel

- `scrollintel-ai-system` — **CANONICAL / LINEAGE RESOLVED / SECURITY HARDENING — NOT VERIFIED**.
- `scroll-intel` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- The canonical repository contains the predecessor's exact substantive initial commit `06400f440697a4d63cf758e33197fc805be26145`, so the original backend/spec foundation is preserved in canonical Git history.
- `ScrollIntel` and `scrollintel.` are confirmed **empty Git repositories** with no commit history; both are safe archive candidates.
- **Security closure remains open:** `SECURITY_CREDENTIAL_REMEDIATION.md` states that historical credential exposure must be assessed, affected credentials rotated/revoked where necessary, history searched, secret scanning rerun and closure evidence recorded before ScrollIntel may be treated as security-closed or production-certified.

### Apply Wingman

- `apply-wingman` — **CANONICAL / LINEAGE RESOLVED**.
- `JobAutoPilot` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- The current predecessor tree contains only its historical README.
- The 2025 commit `afb0abdf510a4ae372acb4902c88a192c08acbd7`, despite being titled “Final full project restore with all working code,” only removed `.gitignore`, LICENSE and `bfg.jar`; the prior safe-restore commit only added those cleanup artifacts.
- No recoverable ATS/application source remains in reachable `JobAutoPilot` history, so the active React/Supabase/Playwright implementation is unambiguously `apply-wingman`.

### ScrollLibrary

- `scroll-wisdom-weave-d69aa349` — **CANONICAL / LINEAGE RESOLVED**.
- `scroll-wisdom-weave`, `scroll-wisdom-weave-370c9253`, `scroll-wisdom-weave-94f4588f`, and `scroll-wisdom-weave-ffcd64d1` — **HISTORICAL SNAPSHOTS / SUPERSEDED / SAFE ARCHIVE CANDIDATES**.
- Exact Git reachability proves the canonical repository already contains the siblings' latest substantive product lineages: `24a637557197fd296a103b986b88e5930d3b830c`, `635c04a56544dbe6e73ec45c3111caf4cb3df154`, `7e75e379b07736458c2151c48dcbe09ca16b36d3`, and `4faad571aad65fa2f38765014c46c9dbcd0f7e8c`, plus security commit `a21c6cfc65cf296d2f7cce4d020ab645cc155462`.
- All four sibling READMEs now point development to the canonical repository; no sibling has been archived or deleted.
- Canonical lineage documentation is in protected PR #22 (`docs/scrolllibrary-lineage-resolution`, head `1e72709b965c0ed2723574e32ddd9db095438948`). Its required checks must pass before merge.
- **LINEAGE RESOLVED does not mean VERIFIED.** ScrollLibrary quality/security/release status continues to depend on its permanent controlled gates.

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

### Quantivis — unique-work preservation review

Canonical identity is resolved: `quantisights-pro-c6abd242` is the maintained repository and contains `LINEAGE.md`.

Resolved predecessor evidence:

- `quantisights-pro` — historical predecessor. Canonical directly contains substantive March commit `b799bbae7e3077818dad35698cbb65601581aee3`.
- `quantisights-pro-e4e7e290` — historical snapshot. Canonical directly contains substantive May commit `82e3dffad260e07ccdf58e4a9e545a9b5ce2803b`.
- `quantisights-pro-ff2bbabf` — partially integrated historical feature/research snapshot. Canonical directly contains July audit commit `28a6a08b80cebbe9a3250e2781eb6e743d1fdd37`.

Remaining Quantivis task is a focused review of later `ff2bbabf` branch-only work before any archive decision, especially:

- `7a4948edf2f6c5d80a0f6f72580064377493efef` — homepage live-trust metrics work; not reachable from canonical history.
- `74366d7b3eccee8633701e0ed658d76e0a17cfae` — Phase 2 structured-ingestion persistence design/migration proposal; not reachable from canonical history and explicitly **not applied** to production.

Do not blindly re-apply the historical migration proposal to the current canonical backend. Reassess it against the present schema first.

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

## Security-hardening queue

### ScrollIntel credential closure

This is no longer a canonical-identification problem. The remaining work is security closure on `scrollintel-ai-system`:

1. inventory historical credential classes without exposing values;
2. identify which credentials were real versus placeholders;
3. rotate/revoke affected real credentials at their providers;
4. verify deployments use current secret stores rather than tracked files;
5. scan repository history for other secret-bearing material;
6. consider history rewriting only after rotation/revocation;
7. re-run secret scanning and permanent quality/security gates;
8. record non-secret closure evidence.

Do not mark ScrollIntel VERIFIED until this programme is closed.

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
- `stanleymay20.github.io`
- `-ScrollCloud-Core` — leading punctuation
- `PushBridge`

Resolved Adelaide and ScrollIntel shells have been removed from this queue.

## Naming debt

Normalize names only after link, deployment, CI and external-reference impact is checked:

- `demo-repo` → future AgentShield-specific identity
- `-ScrollCloud-Core` → remove leading hyphen
- `Kingdom-Wealth-` → remove trailing hyphen
- `legal-case-updater.` → remove trailing period
- `scrollintel.` → trailing-period repository is now a safe archive candidate rather than a rename target
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

ScrollIntel may remain visible as a significant engineering project, but its portfolio presentation must clearly state that security hardening remains open until credential-remediation closure is proven.
