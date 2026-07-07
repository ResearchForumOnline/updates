# Public Agent Routing Notes

The public site agents are designed to answer visitors without exposing private infrastructure.

## Current Public Behaviour

- CallChat, TalkToAI, FrontDeskAgent, and QuantumEncryption1 can call a site agent route.
- The site route asks a protected OpenZero-backed bridge first.
- A smaller CPU-friendly public model lane handles normal website questions quickly.
- A deeper OpenZero lane remains available for heavier internal or Matrix-side reasoning.
- If the model path is unavailable, the site returns a short deterministic product guide instead of failing silently.
- Browser speech and local Voicebox-style audio can be used where enabled.

## Why This Matters

This removes the old problem where a visitor asked different questions and received the same fixed line repeatedly. The expected experience is now:

1. visitor asks a normal product question
2. site agent sends a bounded prompt to the bridge
3. OpenZero-backed model answers from site-specific context
4. voice output can speak the answer where supported
5. fallback text is used only when the model path is down, empty, or timed out

## Abuse And Safety Controls

The public sites should keep abuse controls in place without publishing exact private thresholds. Good controls include:

- same-origin checks
- request body limits
- short prompts for public widgets
- model timeout handling
- queueing or concurrency guards
- no secret logging
- no private account data in public prompts

## Public-Safe Model Notes

The public lane is allowed to mention that OpenZero can run CPU-friendly models and that larger models are reserved for deeper work. Public docs should not publish private endpoint URLs, private keys, or exact server-only routing secrets.
