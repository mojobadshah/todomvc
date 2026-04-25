# Groq Public Poly Auto-Fork Refactor Plan

- Source repo: `tastejs/todomvc`
- Target repo: `mojobadshah/todomvc`
- Branch: `groq-poly-refactor-todomvc-2026-04-25t19-16-48-294z`
- Risk: `low`

## Fallback Safe Staging Plan

- Source repo: `tastejs/todomvc`
- Add a minimal frontend staging demo.
- Add a GitHub Actions smoke workflow.
- Add plan/result metadata.
- Do not modify application source files.

### Planning note

Groq API error 413 Payload Too Large
{"error":{"message":"Request too large for model `llama-3.1-8b-instant` in organization `org_01jznpxw4wf1ta3za18qr1d3hb` service tier `on_demand` on tokens per minute (TPM): Limit 6000, Requested 13192, please reduce your message size and try again. Need more tokens? Upgrade to Dev Tier today at https://console.groq.com/settings/billing","type":"tokens","code":"rate_limit_exceeded"}}
