# OpenZero Updates

OpenZero is the local-first AI node and CPU-friendly brain lane behind several TalkToAI systems.

## Public Role

- Runs local model workflows where possible.
- Provides OpenAI-compatible API-style routes for connected products.
- Supports website agents, Matrix bots, research workflows, and self-hosted deployments.
- Works as the preferred local brain for CallChat, FrontDeskAgent, and ZeroThink integrations.

## Latest Work

- Added a smaller public model lane for fast website answers.
- Kept a deeper model lane for heavier reasoning.
- Tested multiple model sizes for CPU practicality.
- Added queueing/concurrency protection around public model access.
- Improved documentation around the bridge between OpenZero, ZeroThink, CallChat, and FrontDeskAgent.
- Kept private runtime settings, endpoints, keys, and protected internals out of public docs.

## Public Messaging

OpenZero should be described as practical local AI infrastructure: a self-hosted node that can serve useful models, agents, voice tools, and product integrations without forcing every feature through a paid external provider.
