# Data & AI for Development — Portfolio Evidence

This page curates projects that demonstrate how I apply data science, AI and software engineering to questions with economic, environmental or institutional relevance.

The emphasis is on **evidence, reproducibility and decision support**. SDG references below identify relevant problem domains; they do not imply United Nations endorsement or independently measured SDG impact.

## 1. EU Innovation, AI & Energy Analytics

**Repository:** https://github.com/stanleymay20/forecasting-system  
**Policy brief:** https://github.com/stanleymay20/forecasting-system/blob/main/policy_briefs/AI_INNOVATION_ENERGY_TRANSITION_EU_2026.md

**Problem:** How can AI adoption, innovation investment, renewable-energy transition and economic capacity be compared across countries without hiding differences in source coverage and reporting periods?

**Evidence in the repository:**

- Eurostat, OECD and World Bank data sources;
- 10-country comparative design;
- Python/Pandas multi-source integration;
- missingness and coverage analysis;
- unique-key and expected-member validation;
- reusable quality-control functions;
- automated tests and CI;
- explicit evidence boundaries before final numerical publication;
- a September 2026 policy brief translating current official statistics into cautious, decision-oriented recommendations.

**Relevant domains:** digital transformation · innovation policy · energy transition · economic development

**SDG mapping:** 7 · 8 · 9 · 13

## 2. AI Sustainability Dashboard

**Repository:** https://github.com/stanleymay20/ai_sustainability_dashboard  
**Live application:** https://aisustainabilitydashboard.streamlit.app/

**Problem:** How can environmental information from independent APIs be transformed into understandable indicators while preserving limitations in availability, geography and forecast quality?

**Evidence in the repository:**

- live environmental API integration;
- PM2.5 time-series preparation;
- Holt-Winters / Exponential Smoothing forecasting;
- exploratory K-Means geospatial clustering;
- carbon-intensity and mobility-related data integrations;
- defensive API handling and explicit limitations.

**Relevant domains:** environmental monitoring · sustainable cities · clean energy · climate analytics

**SDG mapping:** 3 · 7 · 11 · 13

## 3. AICIS — Resilience & Risk Decision Support

**Repository:** https://github.com/stanleymay20/aicis-divine-core-6d24171b

**Problem:** How can heterogeneous socioeconomic, climate, infrastructure and governance signals be transformed into traceable analysis and human-reviewed response options?

**Evidence in the repository:**

- realtime data architecture;
- canonicalization and relevance-scoring workflows;
- structured risk variables;
- intervention and governance review concepts;
- evidence/provenance hardening;
- PostgreSQL/Supabase data architecture;
- Row-Level Security and server-side privileged workflows;
- explicit distinction between implemented engineering and unvalidated operational effectiveness.

**Relevant domains:** resilience · governance · institutional decision support · climate/infrastructure risk

**SDG mapping:** 9 · 11 · 13 · 16

## 4. Quantivis — Decision Intelligence

**Repository:** https://github.com/stanleymay20/quantisights-pro-c6abd242  
**Website:** https://www.quantivis.io

**Problem:** How can messy operational data be validated, profiled and transformed into analytical outputs without hiding poor data quality behind confident recommendations?

**Evidence in the repository:**

- PostgreSQL/SQL data workflows;
- schema and metric inference;
- ingestion validation and diagnostics;
- dataset quality scoring;
- forecasting and reporting workflows;
- multi-tenant application architecture;
- CI, audit and release controls.

**Transferable development applications:** SME/programme analytics · financial-inclusion monitoring · regional economic indicators · programme data quality

These are potential applications of the platform architecture, not claims of current institutional deployment.

**SDG mapping:** 8 · 9 · 10

## Portfolio principle

Across these projects I try to maintain the same analytical discipline:

```text
Source data
   ↓
Coverage and quality checks
   ↓
Transformation and modelling
   ↓
Uncertainty / evidence boundaries
   ↓
Human-readable analytical output
   ↓
Decision support — not automatic authority
```

## What I am strengthening next

- extend policy analysis beyond the European comparison with development-economy evidence;
- larger authoritative datasets for environmental/geospatial work;
- model validation and backtesting;
- evidence provenance and responsible AI governance;
- development-oriented economic and programme analytics.

**Stanley Osei-Wusu**
