# TalkToAI Public Updates

Public-safe update history for the TalkToAI ecosystem.

This repository tracks user-facing progress across TalkToAI, ZeroThink, OpenZero, CallChat, FrontDeskAgent, FreeWebPanel, ZSEC, QuantumEncryption1, docs, manuals, public agents, and research workflows.

It is intentionally written for users, reviewers, developers, operators, partners, and supporters. It is not a server operations log and it does not publish private implementation material.

## Latest Highlights

- Public website agents were moved away from static fallback copy toward OpenZero-backed answers.
- A fast public model lane was added for website chat so CallChat, TalkToAI, FrontDeskAgent, and QuantumEncryption1 can answer normal visitor questions without feeling frozen.
- OpenZero keeps a deeper model lane for heavier reasoning while lighter public prompts use a smaller CPU-friendly route.
- Voicebox and browser speech work was expanded so site visitors can speak with AI guides and hear replies where enabled.
- CallChat was expanded as a Matrix-compatible sovereign messenger with Element compatibility, Zero Bot, Shield documentation, licensing pages, and self-hosting docs.
- CallChat public docs now separate standard free Matrix chat from optional ZMath / Shield licensing.
- ZeroThink Research Paper Creator gained a safer literature and evidence workflow lane for survey expansion, claim/evidence graphs, provenance, and auditable paper drafting.
- QuantumEncryption1 gained a quantum-ready evidence and provenance workflow page, paper-creator route, agent improvements, and UI fixes.
- FrontDeskAgent gained a model-backed live receptionist demo path instead of a repeated fixed response.
- FreeWebPanel, ZSEC, docs, manuals, PDFs, and GitHub readmes were improved for clearer product discovery.

## Public Links

- TalkToAI: https://talktoai.org/
- TalkToAI Docs: https://docs.talktoai.org/
- ZeroThink: https://zerothink.talktoai.org/
- OpenZero: https://openzero.talktoai.org/
- OpenZero GitHub: https://github.com/ResearchForumOnline/OpenZero
- CallChat: https://callchat.org/
- CallChat GitHub: https://github.com/ResearchForumOnline/CallChat
- FrontDeskAgent: https://frontdeskagent.online/
- FrontDeskAgent GitHub: https://github.com/ResearchForumOnline/FrontDeskAgent
- FreeWebPanel: https://freewebpanel.com/
- ZSEC GitHub: https://github.com/ResearchForumOnline/ZSEC
- QuantumEncryption1: https://quantumencryption1.com/
- Research GitHub: https://github.com/ResearchForumOnline/research

## Repository Map

- `CHANGELOG.md` - newest public-safe updates first.
- `SECURITY-BOUNDARY.md` - what must not be published here.
- `docs/public-agent-routing.md` - public explanation of the OpenZero-backed website agents.
- `docs/release-checklist.md` - repeatable GitHub release hygiene checklist.
- `docs/public-links.md` - ecosystem link index.
- `systems/` - system-by-system public update notes.

## Public Release Boundary

This repository does not include API keys, OAuth secrets, SSH keys, cookies, passwords, database credentials, server logs, private deployment paths, Matrix signing keys, private ZMath / Shield implementation code, customer data, payment data, raw DNA data, or protected research internals.

Public documents describe behaviour, user benefits, safe architecture boundaries, and where to learn more.
