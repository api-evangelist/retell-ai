# Retell AI (retell-ai)

Retell AI provides voice AI infrastructure for building conversational agents with low-latency turn detection, interruption handling, tool calling, knowledge bases, and conversation flows. The Retell SDK exposes a published OpenAPI spec covering agents, calls, voices, knowledge bases, conversation flows, batches, and chat agents.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/retell-ai/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Voice, Agents, Realtime, Conversational

## APIs
1. **Retell AI Platform API** — REST API at `https://api.retellai.com` for agents, conversation flows, calls, voices, knowledge bases, retell LLM, batches, chat agents. OpenAPI spec at [`openapi/retell-ai-openapi.yml`](openapi/retell-ai-openapi.yml).

## Common Properties
- [Website](https://www.retellai.com/)
- [Documentation](https://docs.retellai.com/)
- [OpenAPI](openapi/retell-ai-openapi.yml)
- [Plans](plans/retell-ai-plans-pricing.yml) — reconciled
- [RateLimits](rate-limits/retell-ai-rate-limits.yml) — partial (concurrency documented; HTTP RPS not public)
- [FinOps](finops/retell-ai-finops.yml) — reconciled

## Pricing Snapshot
- Pay-as-you-go with $10 free credits and 20 free concurrent calls
- Voice agents: $0.07–$0.31/min bundled (Retell infra ~$0.055/min + pass-through TTS, LLM, telephony)
- Chat agents: $0.002+/msg
- Additional concurrency: $8/concurrency/month
- First 10 knowledge bases free; first 100 minutes of AI QA free
- Enterprise: custom

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
