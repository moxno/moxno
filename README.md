# Ilya Sibiryakov — Zero-Trust Data Sanitization (ZTDS™) & AI Privacy Architecture

[![IETF Draft](https://img.shields.io/badge/IETF_Draft-draft--sibiryakov--ztds--protocol--02-purple.svg)](https://datatracker.ietf.org/doc/draft-sibiryakov-ztds-protocol/)
[![ZTDS Standard](https://img.shields.io/badge/ZTDS_Standard-RFC_v1.0-059669.svg)](https://ztds.ai/standard/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--0642--5985-green.svg)](https://orcid.org/0009-0002-0642-5985)
[![DOI: Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22058770-blue.svg)](https://doi.org/10.5281/zenodo.22058770)
[![DOI: OSF](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F5BYJF-brightgreen.svg)](https://doi.org/10.17605/OSF.IO/5BYJF)
[![SSRN](https://img.shields.io/badge/SSRN-7335581-darkred.svg)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7335581)
[![NPM MCP](https://img.shields.io/npm/v/@privacyscrubber/mcp-server?label=%40privacyscrubber%2Fmcp-server&color=3b82f6)](https://www.npmjs.com/package/@privacyscrubber/mcp-server)
[![NPM SDK](https://img.shields.io/npm/v/@privacyscrubber/sdk?label=%40privacyscrubber%2Fsdk&color=10b981)](https://www.npmjs.com/package/@privacyscrubber/sdk)

---

### Institutional & Architectural Positioning

- **[ZTDS.ai](https://ztds.ai)** (*Chief Architect & Lead Author*): Vendor-neutral open standard and specification authority for **Zero-Trust Data Sanitization (ZTDS™ RFC v1.0)** and IETF Internet-Draft [`draft-sibiryakov-ztds-protocol`](https://datatracker.ietf.org/doc/draft-sibiryakov-ztds-protocol/).
- **[PrivacyScrubber](https://privacyscrubber.com)** (*Lead Systems Architect*): Pioneer certified commercial implementation of the ZTDS standard — 100% client-side, zero-egress PII & secrets sanitization in volatile RAM across Web, Chrome Extension, MCP Server, and Headless Node.js/WASM SDK.
- **[BrandMeWeb](https://brandmeweb.com)** (*Founder & Chief Architect*): Digital systems engineering agency and commercial R&D studio operating PrivacyScrubber and financing ZTDS protocol research.

---

### Flagship Open-Source & Developer Repositories

| Repository | Role | Package / URL |
| :--- | :--- | :--- |
| [**`moxno/privacyscrubber-mcp`**](https://github.com/moxno/privacyscrubber-mcp) | Production MCP Server & Agentic Guard (30 Industry Profiles, HIPAA, PCI-DSS 4.0, SOC 2, DevOps Secrets) | [`@privacyscrubber/mcp-server`](https://www.npmjs.com/package/@privacyscrubber/mcp-server) · [`privacyscrubber-mcp` (PyPI)](https://pypi.org/project/privacyscrubber-mcp/) |
| [**`moxno/ztds.ai`**](https://github.com/moxno/ztds.ai) | ZTDS™ Open Specification (RFC v1.0), Conformance Registry, Cryptographic Certificates & CLI Auditor | [ztds.ai](https://ztds.ai) · [`ztds` (npm)](https://www.npmjs.com/package/ztds) |
| [**`moxno/ztds-mcp`**](https://github.com/moxno/ztds-mcp) | Open-Source Reference ZTDS RFC v1.0 MCP Server (Apache-2.0) for Cursor, Claude Code & Windsurf | [`ztds-mcp` (npm)](https://www.npmjs.com/package/ztds-mcp) |

---

### Developer Quickstart (Zero Network & Cloud Leakage)

```bash
# 1. Production MCP Server & Agentic Guard (Cursor, Claude Desktop, Claude Code, Windsurf)
npx -y @privacyscrubber/mcp-server

# 2. Headless Node.js / TypeScript / RAG Pipeline SDK (<0.4ms in-memory latency, 0 dependencies)
npm install @privacyscrubber/sdk

# 3. Git Pre-Commit Leak Shield (blocks API keys & PII before commit)
npx ps-git-guard install

# 4. Open-Standard ZTDS RFC v1.0 Reference MCP & Codebase Invariant Auditor
npx ztds-mcp init
npx ztds-mcp audit ./src
```

---

### Core Product Planes

- **Web Workspace**: [privacyscrubber.com](https://privacyscrubber.com) — 100% browser-native data redaction in volatile RAM (0 bytes server egress, Airplane Mode verified).
- **Chrome Extension**: [Chrome Web Store](https://chromewebstore.google.com/detail/privacyscrubber-%E2%80%94-zero-tr/pimoejgefeilajmmbpghifdmhdlkgjol) — In-DOM prompt firewall across ChatGPT, Claude, Gemini, Copilot, Perplexity, and DeepSeek.
- **MCP Server & Agentic Guard**: [privacyscrubber.com/pii-mcp/](https://privacyscrubber.com/pii-mcp/) — Local stdio JSON-RPC sanitization and pre-execution guardrails for AI coding agents.
- **Headless Developer SDK**: [privacyscrubber.com/sdk/](https://privacyscrubber.com/sdk/) — Bijective in-memory tokenization and streaming SSE detokenization for OpenAI, Anthropic, LangChain, and vector RAG lakes.

---

### IETF Internet-Draft & Academic Treatises

- **IETF Internet-Draft**: [Zero-Trust Data Sanitization (ZTDS) Protocol (`draft-sibiryakov-ztds-protocol-02`)](https://datatracker.ietf.org/doc/draft-sibiryakov-ztds-protocol/)
- **Zero-Trust Data Sanitization (ZTDS) Specification**: [Zenodo / CERN (DOI: 10.5281/zenodo.22058770)](https://doi.org/10.5281/zenodo.22058770)
- **Empirical Latency & RAM Profiling Study**: [Center for Open Science (DOI: 10.17605/OSF.IO/5BYJF)](https://doi.org/10.17605/OSF.IO/5BYJF)
- **EU AI Act & US Privacy Statutory Compliance**: [Elsevier / SSRN #7335581](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7335581)
- **Preserving Attorney-Client Privilege in GenAI**: [Law Archive / OSF #4wc86](https://osf.io/preprints/lawarchive/4wc86/)

---

### Official Registries & Verification

- **ZTDS Conformance Registry**: [ztds.ai/registry/](https://ztds.ai/registry/)
- **Glama.ai MCP Registry**: [moxno/privacyscrubber-mcp](https://glama.ai/mcp/servers/moxno/privacyscrubber-mcp) · [moxno/ztds-mcp](https://glama.ai/mcp/servers/moxno/ztds-mcp)
- **Smithery.ai Registry**: [privacyscrubber/privacyscrubber-mcp](https://smithery.ai/servers/privacyscrubber/privacyscrubber-mcp) · [ilsimox/ztds-mcp](https://smithery.ai/servers/ilsimox/ztds-mcp)
- **Awesome MCP Servers**: Listed in [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) & [TensorBlock/awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers)
- **G2 Product Profile**: [PrivacyScrubber Reviews](https://www.g2.com/products/privacyscrubber/reviews)

---

### Contact & Links

- **PrivacyScrubber**: [https://privacyscrubber.com](https://privacyscrubber.com)
- **ZTDS Consortium**: [https://ztds.ai](https://ztds.ai)
- **BrandMeWeb**: [https://brandmeweb.com](https://brandmeweb.com)
- **LinkedIn**: [https://www.linkedin.com/in/ilya-sibiryakov/](https://www.linkedin.com/in/ilya-sibiryakov/)
- **ORCID**: [https://orcid.org/0009-0002-0642-5985](https://orcid.org/0009-0002-0642-5985)
