# Project Portfolio Architecture

This is the portfolio map for repositories owned by `stanleymay20`.

**Inventory baseline:** 100 owned repositories reviewed on 2026-09-11.

**Current cleanup programme:** [GITHUB_OPTIMIZATION.md](GITHUB_OPTIMIZATION.md)

The goal is to present a coherent engineering portfolio without deleting controlled history. Product families are separated into flagship/canonical systems, strategic incubations/components, academic evidence and consolidation/reference repositories.

## Status vocabulary

- **FLAGSHIP** — portfolio-defining project.
- **CANONICAL** — preferred repository for a project family based on the current controlled state.
- **RESOLVED** — the current family identity/consolidation decision is complete for the verified scope.
- **VERIFIED** — permanent read-only quality/security gates have passed on the canonical repository.
- **SECURITY HARDENING** — canonical lineage is known, but an explicit security closure gate remains open.
- **COMPONENT** — supporting repository that may remain separate intentionally.
- **INCUBATION** — active but not yet ready to dominate the public portfolio.
- **ACADEMIC / EVIDENCE** — coursework, research or technical evidence.
- **VERIFY-CONSOLIDATION** — overlaps another repository; compare before archive/merge.
- **PLACEHOLDER** — empty or near-empty in current GitHub metadata; verify before keeping public.

## Tier A — flagship / canonical systems

### AgentShield — AI agent security & runtime governance

- `demo-repo` — **FLAGSHIP / CANONICAL REPOSITORY IDENTITY PENDING**.

`demo-repo` is AgentShield. Its current public default branch is not yet the product source of truth; controlled work lives across branches including the green platform branch and research/evaluation lineages. Do not rename/restructure the repository until the active controlled experiment is frozen and its evidence verified.

AgentShield belongs in **AI safety, agent security and runtime governance**, not in learning/demo projects.

### AICIS — decision intelligence / resilience

- `aicis-divine-core-6d24171b` — **FLAGSHIP / CANONICAL / LINEAGE RESOLVED**.
- `aicis-divine-core` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `aicis-divine-core-b1d2f00f` — **HISTORICAL SNAPSHOT / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `AICIS-control` — **LEGACY INDEPENDENT TRADING PROTOTYPE / PRESERVE / SECURITY REMEDIATION OPEN**.

The Divine Core decision is based on exact Git ancestry. The canonical repository directly contains predecessor head `24e20206e403cb4ed1544764acfbc7eb91fc2238` (Global Signals Engine) and May snapshot head `3a5a0ef65f4cf3eb8128ba59f60e2e1405b2b64a` (ML evaluation SLO observability/provenance). Canonical `LINEAGE.md` was merged through PR #29 after Security DB Behavioral Proof, Authentication Boundary Proof, CI and CodeQL all passed; merge commit `8c91173e27ba2aa615fbf85b9966c339bcb5c460`.

`AICIS-control` is intentionally separate: it predates Divine Core, is a Python/Firebase-era cryptocurrency/exchange automation prototype, and its initial commit is not reachable from the maintained TypeScript/Supabase lineage. A 12 September 2026 review found hard-coded exchange credentials in its public branch tip. The current file has been sanitized to environment-variable loading, but provider-side rotation/revocation and historical secret review remain mandatory. Do not archive it or describe it as production-ready until its `SECURITY_REMEDIATION.md` closure steps are evidenced.

### Quantivis — decision intelligence

- `quantisights-pro-c6abd242` — **FLAGSHIP / CANONICAL / LINEAGE RESOLVED**.
- `quantisights-pro` — **HISTORICAL PREDECESSOR / SUPERSEDED**.
- `quantisights-pro-e4e7e290` — **HISTORICAL SNAPSHOT / SUPERSEDED FOR DEVELOPMENT**.
- `quantisights-pro-ff2bbabf` — **HISTORICAL FEATURE/RESEARCH SNAPSHOT / PRESERVE / UNIQUE-WORK REVIEW OPEN**.

Canonical identity is proven by shared Git history, not repository naming alone. The canonical repo directly contains predecessor commit `b799bbae7e3077818dad35698cbb65601581aee3` from `quantisights-pro`, May schema-fix commit `82e3dffad260e07ccdf58e4a9e545a9b5ce2803b` from `e4e7e290`, and July audit commit `28a6a08b80cebbe9a3250e2781eb6e743d1fdd37` from `ff2bbabf`.

`ff2bbabf` is intentionally preserved because later branch-only work is not reachable from canonical history, including homepage live-trust commit `7a4948edf2f6c5d80a0f6f72580064377493efef` and the explicitly un-applied Phase 2 structured-ingestion design/migration proposal `74366d7b3eccee8633701e0ed658d76e0a17cfae`. See the canonical repository's `LINEAGE.md`; do not re-apply historical DB proposals without a fresh schema review.

### ScrollLibrary — AI publishing OS

- `scroll-wisdom-weave-d69aa349` — **FLAGSHIP / CANONICAL / LINEAGE RESOLVED / VERIFIED**.
- `scroll-wisdom-weave` — **HISTORICAL SNAPSHOT / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `scroll-wisdom-weave-370c9253` — **HISTORICAL SNAPSHOT / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `scroll-wisdom-weave-94f4588f` — **HISTORICAL SNAPSHOT / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `scroll-wisdom-weave-ffcd64d1` — **HISTORICAL SNAPSHOT / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.

The decision is based on exact Git ancestry. The canonical repository directly contains each sibling's latest substantive product lineage: `24a637557197fd296a103b986b88e5930d3b830c` (evidence retrieval), `635c04a56544dbe6e73ec45c3111caf4cb3df154` (Instant Mastery/visual assessment), `7e75e379b07736458c2151c48dcbe09ca16b36d3` (Sell wizard repair), and `4faad571aad65fa2f38765014c46c9dbcd0f7e8c` plus `a21c6cfc65cf296d2f7cce4d020ab645cc155462` (Shopify/OAuth security lineage). The later sibling-only commits are repository-hygiene/environment-file cleanup rather than divergent product work.

All four sibling READMEs point development to the canonical repository, and canonical `LINEAGE.md` is now merged. The first documentation PR (#22) was preserved and closed as superseded after its pre-repair checks exposed an xmldom dependency advisory and two stale real-reader E2E assertions. Controlled repair PR #23 fixed those issues and merged at `7c81c18fe6e7a4ebe9ac2eb157773742f64e93b9` only after CI, GA Real E2E, Dependency Review, EPUB Conformance and CodeQL all passed. The clean lineage successor PR #24 then passed the same five permanent gates and merged at `a28d304ae1818a598de76db403b591dc1a93b0c2`. The temporary write-enabled repair workflow removed itself before PR review. No sibling has been archived or deleted.

### ScrollIntel — intelligence/orchestration

- `scrollintel-ai-system` — **FLAGSHIP / CANONICAL / LINEAGE RESOLVED / SECURITY HARDENING — NOT VERIFIED**.
- `scroll-intel` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.
- `ScrollIntel` — **EMPTY PRIVATE SHELL / SAFE ARCHIVE CANDIDATE**.
- `scrollintel.` — **EMPTY PUBLIC SHELL / SAFE ARCHIVE CANDIDATE / NAMING-DEBT**.

Lineage evidence is unusually strong: `scrollintel-ai-system` contains the exact predecessor commit `06400f440697a4d63cf758e33197fc805be26145`, so the original backend/spec foundation is preserved in the canonical repository's Git history. `scroll-intel` has only that substantive initial commit plus a later documentation commit marking it superseded.

ScrollIntel is **not VERIFIED**. The canonical repository's `SECURITY_CREDENTIAL_REMEDIATION.md` explicitly states that historical credential exposure assessment, any required credential rotations/revocations, history review and re-scanning must be completed before security remediation is closed.

### Apply Wingman — career automation

- `apply-wingman` — **FLAGSHIP / CANONICAL / LINEAGE RESOLVED**.
- `JobAutoPilot` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**.

The current `JobAutoPilot` tree contains only its historical README. Its reachable 2025 cleanup history does not contain recoverable application source: the misleadingly titled `afb0abdf510a4ae372acb4902c88a192c08acbd7` “Final full project restore” commit only removed `.gitignore`, LICENSE and `bfg.jar`, while the preceding safe-restore commit only added those cleanup artifacts. The active React/Supabase application and Playwright ATS worker therefore remain unambiguously in `apply-wingman`.

### Technical publication / data evidence

- `AI-ENGINEERING-From-Foundations-to-Production-Systems` — **FLAGSHIP / TECHNICAL PUBLICATION**.
- `forecasting-system` — **FLAGSHIP / DATA & FORECASTING EVIDENCE**.
- `ai_sustainability_dashboard` — **FLAGSHIP / APPLIED DATA & AI EVIDENCE**.

## Tier B — strategic incubation & components

### Human / personal AI

- `humanos-life-interface` — **STRATEGIC PRIVATE FLAGSHIP INCUBATION** — HumanOS.
- `agyai-your-personal-intelligence` — **INCUBATION**.
- `control-ai-grid` — **COMPONENT / INCUBATION**.
- `intelligence-nexus-29` — **INCUBATION**.
- `signal-ai-suite` — **INCUBATION**.
- `scroll-nexus` — **COMPONENT / INCUBATION**.
- `scrollchat-ai` — **INCUBATION**.
- `scrollwrappedcodex` — **INCUBATION**.

### AI engineering / developer tooling

- `stanley-ai-studio` — **CANONICAL CANDIDATE**.
- `studio-foundation` — **COMPONENT**.
- `pure-prompt-app-gen` — **INCUBATION**.
- `AutoDevAgent-GPTX` — **EXPERIMENTAL**.
- `DevStream-AI` — **EXPERIMENTAL**.
- `scroll-engine-x` — **COMPONENT / INCUBATION**.
- `screenshot-perfect-119` — **EXPERIMENTAL / PRIVATE**.
- `next-dashboard-ui` — **TEMPLATE / LEARNING / COMPONENT**.
- `AI_Studio` — **PLACEHOLDER / VERIFY-CONSOLIDATION**.

### Cloud / infrastructure

- `-ScrollCloud-Core` — **COMPONENT / NAMING-DEBT**.
- `scrollcloud-front` — **COMPONENT**.
- `Cloud-2.0` — **PLACEHOLDER / PRIVATE**.
- `PushBridge` — **COMPONENT / NEAR-EMPTY**.
- `pushbridge-blueprint` — **PLACEHOLDER / VERIFY-CONSOLIDATION**.

### Fintech / payments / accounting

- `ai-payment-app` — **STRATEGIC INCUBATION**.
- `adelaide-ledger-ai` — **CANONICAL / RESOLVED / VERIFIED**.
  - Verification: permanent read-only CI passes locked install, lint, application/tooling TypeScript checks and production build; permanent dependency audit passes locked install, direct-tree validation and both production/full-tree security gates after the controlled dependency migration.
- `AdelaideAccounts` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. No unique application source.
- `AdelaideAI` — **HISTORICAL PREDECESSOR / SUPERSEDED / SAFE ARCHIVE CANDIDATE**. Only project-shell history, LICENSE and superseded README; no unique application source.
- `ai-monetization-app` — **EXPERIMENTAL**.
- `Freecryptocurrency` — **LEGACY / VERIFY SECURITY & RELEVANCE**.

### Justice / governance

- `scroll-justice-prophecy-ai-40` — **CANONICAL CANDIDATE / PRIVATE**.
- `scroll-justice-prophecy-ai` — **VERIFY-CONSOLIDATION**.
- `FastTrackJusticeAI` — **POSSIBLE PREDECESSOR**.
- `legal-case-updater.` — **PLACEHOLDER / NAMING-DEBT**.

### Health / wellness

- `healthos-your-wellness-navigator` — **INCUBATION**.
- `clinical-ai-platform` — **PLACEHOLDER / PRIVATE**.
- `scrollcomfort-ai` — **EXPERIMENTAL**.
- `diabetes_prediction` — **ACADEMIC / EVIDENCE**.

### Publishing / education / faith / media

- `scroll-scribe-automaton` — **PUBLISHING COMPONENT**.
- `Kingdom-Wealth-` — **BOOK / PRIVATE / NAMING-DEBT**.
- `educhat-ai` — **EDUCATION INCUBATION / PRIVATE**.
- `uni-leaderboard-buddy` — **EDUCATION EXPERIMENT / PRIVATE**.
- `daily-chapter-guide` — **CONTENT / PRIVATE**.
- `daily-chapter-reflections` — **CONTENT**.
- `Bible-ARVR-App` — **EXPERIMENTAL**.
- `churchos-backend` — **COMPONENT**.
- `churchos-frontend` — **COMPONENT**.
- `insight-reader` — **PRIVATE INCUBATION**.
- `to-voice` — **PRIVATE MEDIA INCUBATION**.
- `PromptTube` — **PLACEHOLDER**.

### Enterprise / business automation

- `app-automarketer-891ef675` — **CANONICAL / RESOLVED / VERIFIED**.
- `app-automarketer` — **VERIFY-CONSOLIDATION**.
- `inventory-ignite-ai` — **PRIVATE INCUBATION**.
- `jimp-global-trade-vision` — **ACTIVE**.
- `jimp` — **NEAR-EMPTY / COMPANY ROOT CANDIDATE**.
- `curry36-whatsapp-bot` — **EXPERIMENTAL**.
- `curry36-chatbot` — **PLACEHOLDER**.

## Tier C — academic / technical evidence

These should remain discoverable but should not compete visually with the flagship product portfolio.

- `Data-Storytelling-with-Google-Data-Studio`
- `Data-Visualization`
- `machine-learniing` — naming debt
- `billionaires-net-worth-analysis` — **CANONICAL ACADEMIC / EVIDENCE — LINEAGE RESOLVED**. Contains the R Markdown source, R analysis code, rendered outputs, figures and applied-statistics assessment.
- `Billionaires_Analysis_Project` — **SUPERSEDED LEGACY SHELL / SAFE ARCHIVE CANDIDATE**. Its initial commit contained only the MIT LICENSE and a one-line README; no unique analysis source was ever present.
- `Social-Network`
- `Social-Network-Analysis`
- `haensel-ams-bayesian-mmm`
- `cs50-ai`
- `cs50-projects`
- `tiny_python_projects`
- `perceptron` — placeholder
- `text-summarization-news-aggregation` — **CANONICAL ACADEMIC SUCCESSOR / LINEAGE RESOLVED / NOT PRODUCTION-VERIFIED**. Structured modular successor for the 2024 news summarization work; see its `LINEAGE.md`.

## Tier D — reference / legacy / consolidation

- `langflow` — **REFERENCE / FORK CANDIDATE**; clearly separate from original product IP unless materially modified.
- `Python-Natural-Language-Processing-Cookbook` — **REFERENCE / FORK CANDIDATE**.
- `news-summarizer` — **HISTORICAL PROTOTYPE / PRESERVE**. Retains unique Reuters scraping, TF-IDF extractive summarization and Flask trigger experiments absent from the structured successor; do not delete as a duplicate.
- empty or near-empty public placeholders listed in [GITHUB_OPTIMIZATION.md](GITHUB_OPTIMIZATION.md).

## Profile & delivery

- `stanleymay20` — **CANONICAL PROFILE REPOSITORY**.
- `stanleymay20.github.io` — currently empty; build only if it adds value beyond the GitHub profile, otherwise archive after verification.

## Public portfolio hierarchy

A visitor should primarily see:

1. AgentShield
2. AICIS
3. Quantivis
4. ScrollLibrary
5. ScrollIntel — clearly labelled as undergoing security hardening, not production-certified
6. Apply Wingman
7. EU Innovation / AI / Energy Analytics
8. AI Sustainability Dashboard
9. AI Engineering publication/project

HumanOS remains strategically important but is currently private and should be presented as incubation rather than a public repository link.

## Safe cleanup sequence

1. Verify canonical repositories by commit/tree/content/history comparison.
2. Preserve releases, tags, migrations, CI evidence, issues, PRs and controlled SHA gates.
3. Add canonical/superseded README notices to predecessors.
4. Archive only after verification; do not delete by default.
5. Normalize naming only after checking links, deployments, CI and external references.
6. Keep academic/reference repositories discoverable through this index but outside the flagship presentation.

For the live cleanup queue, naming debt, empty repositories and public/private strategy, see [GITHUB_OPTIMIZATION.md](GITHUB_OPTIMIZATION.md).
