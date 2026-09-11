# GitHub Portfolio Optimization Programme

Controlled portfolio baseline: **100 owned repositories** reviewed through the connected GitHub account on 2026-09-11.

The objective is not to delete history. It is to make the account read like a coherent engineering portfolio: a small number of flagship systems, a visible incubation layer, a separate academic/evidence layer, and a controlled consolidation/archive queue.

## Operating rules

1. Do not delete a repository because its name looks duplicated.
2. Compare canonical candidates at commit/tree/content level before consolidation.
3. Preserve migrations, CI evidence, releases, tags, issues, PRs, experiment lineage and controlled SHA gates.
4. Prefer archive/deprecation over deletion for public predecessors.
5. Do not restructure a branch while a controlled experiment is running.
6. Public repositories should either demonstrate meaningful work or clearly state that they are historical/reference repositories.
7. Private incubations do not need to compete for attention on the public profile.

## Portfolio tiers

### Tier A — flagship / canonical

These should dominate the public profile and eventually receive consistent READMEs, security/release metadata and repository governance.

- `demo-repo` — **AgentShield** — AI agent security and runtime governance. Repository rename/integration deferred until the current controlled v14 experiment is frozen.
- `aicis-divine-core-6d24171b` — **AICIS** — current controlled canonical target.
- `quantisights-pro-c6abd242` — **Quantivis** — current canonical target.
- `scroll-wisdom-weave-d69aa349` — **ScrollLibrary** — current controlled canonical target.
- `scrollintel-ai-system` — **ScrollIntel** — canonical candidate pending duplicate/history verification.
- `apply-wingman` — **Apply Wingman** — canonical career-automation product.
- `AI-ENGINEERING-From-Foundations-to-Production-Systems` — flagship technical publication/project.
- `forecasting-system` — flagship data/forecasting evidence.
- `ai_sustainability_dashboard` — flagship applied data/AI evidence.

### Tier B — strategic incubation / components

These are worth keeping active, but should not crowd the profile landing page before they reach stronger product/release maturity.

- `humanos-life-interface` — HumanOS, private flagship incubation.
- `agyai-your-personal-intelligence`
- `control-ai-grid`
- `intelligence-nexus-29`
- `signal-ai-suite`
- `scroll-nexus`
- `stanley-ai-studio`
- `studio-foundation`
- `pure-prompt-app-gen`
- `AutoDevAgent-GPTX`
- `DevStream-AI`
- `scroll-engine-x`
- `ai-payment-app`
- `adelaide-ledger-ai`
- `scroll-justice-prophecy-ai-40`
- `healthos-your-wellness-navigator`
- `educhat-ai`
- `jimp-global-trade-vision`
- `inventory-ignite-ai`
- `churchos-backend`
- `churchos-frontend`
- `scrollcloud-front`
- `scroll-scribe-automaton`
- `scrollcomfort-ai`
- `to-voice`
- `insight-reader`
- `daily-chapter-guide`
- `daily-chapter-reflections`
- `Bible-ARVR-App`

## Consolidation clusters

### AgentShield

Current repository: `demo-repo`.

Do not rename or change the default branch while `agentshield-assessment-v14-high-recall` is still executing. Once frozen, create a canonical integration lineage that preserves research branches and the green platform branch. Then replace the demo identity with AgentShield-specific repository metadata and a professional default README.

### AICIS

Canonical target: `aicis-divine-core-6d24171b`.

Compare before any archive decision:

- `aicis-divine-core`
- `aicis-divine-core-b1d2f00f`
- `AICIS-control` — verify whether this is a genuine control-plane component rather than a duplicate.

### Quantivis

Canonical target: `quantisights-pro-c6abd242`.

Compare:

- `quantisights-pro`
- `quantisights-pro-e4e7e290`
- `quantisights-pro-ff2bbabf`

Generated-ID names should eventually disappear from the public product identity, but only after the strongest lineage is confirmed.

### ScrollLibrary

Canonical target: `scroll-wisdom-weave-d69aa349`.

Compare:

- `scroll-wisdom-weave`
- `scroll-wisdom-weave-370c9253`
- `scroll-wisdom-weave-94f4588f`
- `scroll-wisdom-weave-ffcd64d1`

### ScrollIntel

Canonical candidate: `scrollintel-ai-system`.

Compare:

- `scroll-intel`
- `ScrollIntel` — currently empty in repository metadata.
- `scrollintel.` — currently empty and has undesirable trailing punctuation.

### Apply Wingman

Canonical: `apply-wingman`.

Compare `JobAutoPilot` and preserve any unique ATS-routing/application logic before deprecating it.

### AutoMarketer

Compare:

- `app-automarketer`
- `app-automarketer-891ef675`

### ScrollJustice

Compare:

- `scroll-justice-prophecy-ai`
- `scroll-justice-prophecy-ai-40`
- `FastTrackJusticeAI`
- `legal-case-updater.`

### Adelaide finance

Canonical candidate: `adelaide-ledger-ai`.

`AdelaideAccounts` is currently empty and `AdelaideAI` is near-empty; verify whether either contains unique history before deprecation.

### News / summarization

Compare `news-summarizer` with `text-summarization-news-aggregation`.

### Academic duplicate

Compare `billionaires-net-worth-analysis` with `Billionaires_Analysis_Project`.

## High-confidence cleanup queue

The following repositories are empty or near-empty according to current GitHub repository metadata and should be verified first because they create portfolio noise with little visible value:

- `AdelaideAccounts` — size 0
- `AI_Studio` — size 0
- `clinical-ai-platform` — size 0, private
- `Cloud-2.0` — size 0, private
- `curry36-chatbot` — size 0
- `Data-Integrartion` — size 0 and misspelled
- `legal-case-updater.` — size 0 and trailing punctuation
- `perceptron` — size 0
- `PromptTube` — size 0
- `pushbridge-blueprint` — size 0
- `SAVIOR` — size 0
- `ScrollIntel` — size 0, private
- `scrollintel.` — size 0 and trailing punctuation
- `stanleymay20.github.io` — size 0
- `-ScrollCloud-Core` — size 1 and leading punctuation
- `AdelaideAI` — size 1
- `PushBridge` — size 1

These are **archive/deprecation candidates, not automatic deletion candidates**.

## Naming debt

The following names weaken the professional presentation and should be normalized only after link/CI/deployment impact is checked:

- `demo-repo` → future AgentShield-specific name
- `-ScrollCloud-Core` → remove leading hyphen
- `Kingdom-Wealth-` → remove trailing hyphen
- `legal-case-updater.` → remove trailing period
- `scrollintel.` → remove trailing period
- `machine-learniing` → correct spelling
- `Data-Integrartion` → correct spelling
- generated suffixes such as `-6d24171b`, `-c6abd242`, `-d69aa349`, `-891ef675` → remove only after canonical lineage is verified

Preferred naming convention for product repositories:

`product-name`  
`product-name-api`  
`product-name-web`  
`product-name-infra`  
`product-name-research`

## Public/private strategy

**Public:** flagship products with professional documentation; selected academic/data evidence; intentional open-source components; historical repositories only when clearly marked as superseded/reference.

**Private:** early product incubations, unfinished concepts, internal infrastructure, duplicated generated workspaces and repositories whose public state adds noise but no portfolio evidence.

Do not make a repository private merely to hide a failed experiment. Negative research evidence should remain preserved when it is part of a controlled scientific lineage.

## Repository quality standard for Tier A

Every Tier A repository should converge on:

- clear product name and one-sentence purpose;
- architecture/threat-model documentation where relevant;
- installation or reproducibility instructions;
- explicit current status: research, beta, production candidate, etc.;
- tests and CI status;
- security/release gates appropriate to the project;
- license decision;
- contribution/security policy when public collaboration is intended;
- no secrets or committed runtime credentials;
- deterministic dependency management;
- release/version history for production-facing systems;
- canonical repository marker when predecessor repositories exist.

## GitHub profile presentation

The profile README should show no more than a small number of strong projects. Current public emphasis:

1. AgentShield
2. AICIS
3. Quantivis
4. ScrollLibrary
5. ScrollIntel
6. Apply Wingman
7. EU Innovation / AI / Energy Analytics
8. AI Sustainability Dashboard
9. AI Engineering publication/project

HumanOS remains strategically important but is currently private, so it should be described as incubation rather than presented as a public repository link.

## Controlled cleanup sequence

1. Fix the profile presentation and portfolio map.
2. Complete AgentShield v14 and freeze the evidence.
3. Verify canonical candidates within each duplicate family.
4. Add canonical/superseded READMEs before archiving predecessors.
5. Normalize public repository names only after dependency/link checks.
6. Harden Tier A CI, security, release and documentation standards.
7. Move empty/obsolete public placeholders out of the public portfolio through archive/private decisions after verification.
8. Build the currently empty `stanleymay20.github.io` only if it adds value beyond the GitHub profile; otherwise archive it rather than leaving an empty public shell.

## Success target

The account may retain 100 repositories internally, but a visitor should experience roughly **8–12 public flagship/evidence projects**, a small number of clearly labelled incubations/components, and no ambiguity about which repository is canonical for a product family.
