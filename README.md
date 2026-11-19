## APEX Faucet — x402 APIs & MCP Tools for AI Agents

**279 pay-per-call x402 APIs & 364 hosted MCP tools** (`$0.001–$0.05` via USDC on Base, Arc, or Solana, or XNT on X1) — **or** use a prepaid **$5 API Key by card (no crypto)** at **[apexfaucet.xyz/pass/](https://apexfaucet.xyz/pass/)**.

- **Focused MCP Endpoints (Official MCP Registry `xyz.apexfaucet/*`):**
  - AI, LLMs, Embeddings, OCR, Whisper, TTS, FLUX/SVG & Guardrails: `https://apexfaucet.xyz/api/mcp/ai`
  - Headless Chrome Render, Scraping, Markdown, HTML-to-PDF & Research: `https://apexfaucet.xyz/api/mcp/web`
  - DefiLlama TVL/Yields/DEX Volumes, Perp Funding, EVM Log Decode & Audits: `https://apexfaucet.xyz/api/mcp/defi`
  - Prompt Injection, PII Redaction, CVE Lookup & Tx Safety: `https://apexfaucet.xyz/api/mcp/safety`
  - Full Catalogue (364 tools): `https://apexfaucet.xyz/api/mcp` · Bridge repo: **[apexfaucet-hub/apex-x1-mcp](https://github.com/apexfaucet-hub/apex-x1-mcp)**

```json
{
  "mcpServers": {
    "apex-ai": {
      "command": "npx",
      "args": ["-y", "github:apexfaucet-hub/apex-x1-mcp", "ai"],
      "env": { "APEX_API_KEY": "apx_optional_key_from_pass" }
    }
  }
}
```

- **Agent Docs & Discovery:** [For Agents](https://apexfaucet.xyz/for-agents/) · [Pricing](https://apexfaucet.xyz/pricing/) · [`/openapi.json`](https://apexfaucet.xyz/openapi.json) · [`/.well-known/x402`](https://apexfaucet.xyz/.well-known/x402) · [`/llms.txt`](https://apexfaucet.xyz/llms.txt)
- **Prepaid Passes:** [$5 Card API Key](https://apexfaucet.xyz/pass/) · USDC Passes `+30%` (`/api/x402/api-pass`) & `+40%` (`/api/x402/api-pass-pro`)

### Ecosystem & Open-Source Projects

- **[Shuteye](https://github.com/apexfaucet-hub/shuteye)**: talk to Claude Code with your eyes shut (zero dependencies, read-only by default).
- **[Free USDC on Arc](https://apexfaucet.xyz/arc/)**: paste an address, no wallet connect, nothing to sign.
- **[Agent Watchtower](https://apexfaucet.xyz/arc/agents/)**: live liveness & x402 monitor for Arc ERC-8004 agents.
- **[Arc Agent Passport](https://github.com/apexfaucet-hub/arc-agent-passport)**: ERC-8004 identity on Arc for any AI agent.
- **[Bloodstream](https://github.com/apexfaucet-hub/bloodstream)**: live Arc honeypot & rug-spotting game ([play](https://apexfaucet.xyz/arc/bloodstream/)).

Numbers we publish are read from live sources and chain state, never estimated.
