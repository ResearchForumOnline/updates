# Public Release Checklist

Use this checklist before pushing public updates to GitHub.

## Content

- The newest update is at the top.
- Product names and links are correct.
- Visitor-facing language is clear and not written like an internal note.
- Security claims are cautious and evidence-aware.
- Research claims avoid unsupported approvals or certification language.
- No unrelated private projects are included.

## Sensitive Data

- No keys, passwords, cookies, tokens, or private credentials.
- No server-only config values or internal private paths.
- No customer data, payment data, raw DNA files, or private chat logs.
- No private ZMath / Shield implementation code.
- No private ZeroThink prompt libraries.

## GitHub Hygiene

- README explains the repo purpose.
- Changelog is newest first.
- Security boundary is present.
- Large generated archives are not committed unless intentionally public.
- Screenshots do not reveal account data or private URLs.
- Install commands do not require private secrets.

## Website-Agent Checks

- Public agents answer a direct product question.
- Public agents do not repeat the same intro for unrelated prompts.
- Voice endpoint returns an audio response where enabled.
- Fallback copy is short and only appears when the model lane is unavailable.

## Final Scan

Run a local text scan for obvious sensitive patterns and unrelated private project names before publishing.
