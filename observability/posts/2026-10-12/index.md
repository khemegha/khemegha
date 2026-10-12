# Green dashboards, broken agents

*October 12, 2026 · ASA AI Agent Observability*

![ASA AI Agent Observability — calls, latency, tokens, errors and Guard decisions per model](obs_2026-10-12_1.jpg)

Latency and uptime can look healthy while AI agents fail silently: in this window, 8.8% of model calls errored and our Guard blocked 8 prompts.

ASA AI Agent Observability tracks every call, token, error and Guard decision, per agent and per model, in one live view.

Your team sees errors, token spend and blocked attacks before your users do.

## What this dashboard shows

- **Usage at a glance:** 7.1 million requests and 1,480 unique users over the period, with a satisfaction score of 80%.
- **Every agent, every model:** 29,813 invocations through the gateway of our 20 agents, across 10 active models, with token consumption tracked in (682,960) and out (172,514).
- **Performance where it matters:** a median latency of 4.6 s and time to first token next to the averages, so a single slow model can't hide behind a global number.
- **Errors per model, not just globally:** an 8.8% error rate on the latest window, broken down by model so the team knows exactly which one to fix.
- **Security in the same view:** ASA-AI-Guard decisions (8 prompts blocked, 1 flagged) sit beside performance metrics, so a spike in blocked prompts is spotted as fast as a spike in latency.

## Why it matters

Classic monitoring was built for APIs that either answer or fail. AI agents can answer, look healthy, and still be wrong, slow on one model, expensive, or under attack. The industry is converging on the same conclusion: agents need their own observability, with traces, token accounting and continuous evaluation, not just uptime checks. That is what we built SENTINEL's AI observability layer for, whether your models run in the cloud or on your own infrastructure.

**Want a live demo on your own agents?** Write to us at **contact@asa-ai.fr**.

#AIObservability #LLMOps #OpenTelemetry #AIAgents #AISecurity #GenAI #ASAAI

**Sources:** [Monitor LLM agents in production with Grafana Cloud Agent Observability (DEV Community)](https://dev.to/mr_manushukla/monitor-llm-agents-in-production-with-grafana-cloud-agent-observability-2026-3al9)

<!-- source-captures: Screenshot 2026-10-07 093259.png -->
