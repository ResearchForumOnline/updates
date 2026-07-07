# Changelog

Newest public-safe updates are listed first.

## 2026-07-07

### Public AI Agents

- Reworked the website agent path so the public widgets call an OpenZero-backed bridge before falling back to canned product guidance.
- Added a fast CPU-friendly public model lane for normal website questions.
- Kept a deeper OpenZero model lane available for heavier reasoning and Matrix-side assistant work.
- Added queueing around the upstream model path so simultaneous site visitors do not overload the CPU host.
- Retained deterministic fallback answers only for outages, timeouts, or empty model replies.
- Added public-agent fact guards and an instant curated answer lane for common site questions, reducing repeat/static behaviour and avoiding product-drift claims.
- Expanded public voice work through local Voicebox-style audio generation and browser speech where available.
- Removed public wording that exposed exact daily usage limits on pages.

### CallChat

- Improved the CallChat public website, downloads page, Shield page, pricing language, admin visibility, and Matrix/Element guidance.
- Added public-facing CallChat docs for Element setup, live web client usage, Zero Bot, Q-Calls, Shield/ZMath, and self-hosting.
- Clarified that standard Matrix-compatible secure chat on CallChat stays free.
- Clarified that ZMath / CallChat Shield is optional premium licensing for self-hosted servers, with CallChat's own public service acting as the showcase lane.
- Added public GitHub direction for a CallChat repo that can install or guide Synapse, Element, OpenZero integration, and website widget options while excluding private Shield implementation.
- Added a stronger CallChat open graph/share image and video content updates.

### TalkToAI

- Improved the TalkToAI public agent so it can answer ecosystem questions through the model-backed bridge instead of repeating one static introduction.
- Updated public site wording to remove internal-sounding copy and keep the visitor as the audience.
- Removed unwanted footer references from the public site where requested.
- Kept the main TalkToAI route focused on ecosystem discovery, docs, projects, AI guides, and research pathways.

### FrontDeskAgent

- Updated the live receptionist demo path so it can answer business visitor questions through the OpenZero-backed lane.
- Added public docs describing self-hosted receptionist deployment, website widget direction, and OpenZero CPU-first operation.
- Kept FrontDeskAgent GitHub public-safe by excluding private credentials, paid service internals, and protected model routing details.

### ZeroThink

- Hardened the Research Paper Creator flow for literature expansion, survey drafts, claim/evidence graph planning, provenance notes, and export reliability.
- Scoped the provenance-aware survey expansion workflow to the research and paper-creator lanes rather than the main general ZeroThink route.
- Documented the workflow where public papers/articles feed AI extraction, claim/evidence graphs, classical baselines, optional quantum or simulator candidate methods, comparisons, and auditable reports.
- Continued protecting private prompts, private keys, and non-public research internals.

### OpenZero

- Tested lighter public-serving models for speed and kept the faster public route separate from deeper OpenZero reasoning.
- Documented the bridge role more clearly: OpenZero can serve local CPU models, website agents, Matrix bots, and other TalkToAI products without needing paid hosted voice or LLM services for every interaction.
- Kept sensitive runtime details, private routes, and operator credentials out of public GitHub updates.

### QuantumEncryption1

- Added or improved the quantum-ready evidence and provenance workflow route.
- Added paper-creator and evidence workflow links so students and researchers can see how claim/evidence graph expansion fits the research lane.
- Improved the QE1 agent path so normal questions use a local model route before safe fallback.
- Fixed UI issues in the header and public page layout.
- Kept public wording cautious: research-ready, provenance-aware, and security-aware without unsupported approval claims.

### FreeWebPanel

- Continued UI, speed, product clarity, Softaculous compatibility direction, admin/end-user usability, and monetisation path work.
- Clarified that site-owner licensing payments are separate from hosting customers' own payment configurations.
- Kept FreeWebPanel public material focused on install, hosting operations, security, docs, and customer onboarding.

### ZSEC

- Repaired and expanded public GitHub presentation.
- Improved public page styling and documentation around security-only Linux update automation.
- Kept language focused on read-only advisory data, update discipline, and server-hardening workflows.

### GitHub Public Boundary

- Created this updates repository as a public, non-sensitive change ledger.
- Excluded private implementation details, credentials, logs, exact private deployment paths, payment data, private research files, and protected ZMath / Shield internals.
- Avoided unrelated private projects.

## 2026-07-06

- Expanded CallChat with Matrix/Element-compatible planning, Synapse template docs, Android app planning, Shield threat-model docs, AI bot planning, user manuals, downloadable guides, and public site pages.
- Improved site agents and voice experiments across CallChat, TalkToAI, and FrontDeskAgent.
- Added CallChat GitHub planning for a public self-host route while keeping proprietary encryption source private.

## 2026-07-04

- Expanded OpenZero public GitHub front page so users can see more of the local AI node capability surface.
- Added OpenZero update notes, CPU runtime docs, bridge docs, Voicebox direction, and model guidance.
- Updated TalkToAI Docs with updates pages, manual links, PDF guides, cleaner navigation, and product pages.
- Rebuilt ZeroThink, OpenZero, and FreeWebPanel manuals.
- Removed public-facing crypto-style distractions from OpenZero presentation while preserving internal compatibility where needed.

## 2026-07-03

- Improved ZSEC page design and GitHub content.
- Continued UI and speed work across TalkToAI, docs, FreeWebPanel, and related public pages.
- Restored and expanded ZeroThink FAQ coverage from older backup material where safe.
- Improved ZeroThink reasoning, model, and provider key documentation.

## 2026-07-02

- Rebuilt docs.talktoai.org as a large documentation hub with product pages, manuals, videos, FAQ, business pages, service pages, contact, and TalkToAI Quiz.
- Added book-style online readers and PDFs for key products.
- Improved clean URL handling, navigation, SEO structure, and public documentation layout.

## Earlier 2026

- TalkToAI, ZeroThink, OpenZero, ZMath, DNA Lab, ZSEC, FreeWebPanel, QuantumEncryption1, courses, docs, and satellite sites were shaped into a connected public ecosystem.
