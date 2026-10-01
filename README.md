# PrivacyScrubber Ecosystem

Building **[PrivacyScrubber](https://privacyscrubber.com)** — the zero-trust, 100% client-side PII sanitization engine for AI workflows.

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--0642--5985-green.svg)](https://orcid.org/0009-0002-0642-5985)
[![DOI: Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22058770-blue.svg)](https://doi.org/10.5281/zenodo.22058770)
[![DOI: OSF](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F5BYJF-brightgreen.svg)](https://doi.org/10.17605/OSF.IO/5BYJF)
[![MCP: TensorBlock](https://img.shields.io/badge/MCP-TensorBlock%20Listed-blue)](https://github.com/TensorBlock/awesome-mcp-servers)

---

### Core Projects & Ecosystem

- **Web App**: [PrivacyScrubber.com](https://privacyscrubber.com) — 100% browser-native data redaction (zero server logs, RAM-only processing, Airplane Mode verified).
- **Chrome Extension**: [PrivacyScrubber on Chrome Web Store](https://chromewebstore.google.com/detail/privacyscrubber-%E2%80%94-zero-tr/pimoejgefeilajmmbpghifdmhdlkgjol) — In-page automatic prompt sanitization for ChatGPT, Claude, and Gemini with zero network egress.
- **MCP Server**: [`@privacyscrubber/mcp-server`](https://privacyscrubber.com/pii-mcp/) ([GitHub](https://github.com/moxno/privacyscrubber-mcp)) — Model Context Protocol server for AI IDEs (Cursor, Antigravity, Claude Desktop, Windsurf).
- **Headless Node.js & WASM SDK**: [`@privacyscrubber/sdk`](https://privacyscrubber.com/sdk/) ([npm](https://www.npmjs.com/package/@privacyscrubber/sdk)) — Zero-dependency ESM/CJS de-tokenization engine (<1ms in-memory latency).
- **ZTDS Open Standard**: [ZTDS.ai](https://ztds.ai) — Zero-Trust Data Sanitization protocol (RFC v1.0, Apache-2.0).

---

### Key Capabilities

- **Zero-Trust Data Sanitization (ZTDS)**: Prompts and files are sanitized entirely in volatile local RAM. Zero telemetry, zero server-side prompt storage.
- **30 Specialized Industry Profiles**: Out-of-the-box detection for Healthcare/HIPAA, Finance/SOX, Legal/Attorney-Client Privilege, DevOps Secrets, HR/FERPA, and Enterprise workflows.
- **Bi-Directional Reverse Scrub**: Restore masked tokens in downstream AI responses locally in memory.

---

### Academic Treatises & Empirical Research

- **Zero-Trust Data Sanitization (ZTDS)**: [Zenodo / CERN (DOI: 10.5281/zenodo.22058770)](https://doi.org/10.5281/zenodo.22058770)
- **Empirical Latency & RAM Profiling Study**: [Center for Open Science (DOI: 10.17605/OSF.IO/5BYJF)](https://doi.org/10.17605/OSF.IO/5BYJF)
- **EU AI Act & US Privacy Statutory Compliance**: [Elsevier / SSRN #7335581](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7335581)
- **Preserving Attorney-Client Privilege in GenAI**: [Law Archive / OSF #4wc86](https://osf.io/preprints/lawarchive/4wc86/)

---

### Registries & Official Listings

- **Glama.ai MCP Registry**: [moxno/privacyscrubber-mcp](https://glama.ai/mcp/servers/moxno/privacyscrubber-mcp)
- **Smithery.ai Registry**: [privacyscrubber/privacyscrubber-mcp](https://smithery.ai/servers/privacyscrubber/privacyscrubber-mcp)
- **Awesome MCP Servers**: Listed in [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers#security) & [TensorBlock](https://github.com/TensorBlock/awesome-mcp-servers)
- **Cursor Directory**: [privacyscrubber-mcp](https://cursor.directory/plugins/privacyscrubber-mcp)
- **G2 Product Profile**: [PrivacyScrubber Reviews](https://www.g2.com/products/privacyscrubber/reviews)
- **There's An AI For That (TAAFT)**: [PrivacyScrubber](https://theresanaiforthat.com/ai/privacy-scrubber/)

---

### Contact & Profiles

- Website: [privacyscrubber.com](https://privacyscrubber.com)
- Founder: [BrandMeWeb](https://brandmeweb.com)
- LinkedIn: [Ilya Sibiryakov](https://www.linkedin.com/in/ilya-sibiryakov/)
- ORCID: [0009-0002-0642-5985](https://orcid.org/0009-0002-0642-5985)
