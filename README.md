# PrivacyScrubber Ecosystem 🛡️

Building **[PrivacyScrubber](https://privacyscrubber.com)** — the zero-trust, 100% client-side PII sanitization engine for AI workflows.

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--0642--5985-green.svg)](https://orcid.org/0009-0002-0642-5985)
[![DOI: Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22058770-blue.svg)](https://doi.org/10.5281/zenodo.22058770)
[![DOI: OSF](https://img.shields.io/badge/DOI-10.17605%2FOSF.IO%2F5BYJF-brightgreen.svg)](https://doi.org/10.17605/OSF.IO/5BYJF)

---

### 🛠️ Core Projects

- 🌐 **Web App**: [PrivacyScrubber.com](https://privacyscrubber.com) — 100% browser-native data redaction (zero server logs, Airplane Mode verified).
- 🧩 **Chrome Extension**: [PrivacyScrubber on Chrome Web Store](https://chromewebstore.google.com/detail/privacyscrubber-%E2%80%94-zero-tr/pimoejgefeilajmmbpghifdmhdlkgjol) — In-page automatic prompt sanitization for ChatGPT, Claude & Gemini.
- 🤖 **MCP Server**: [`@privacyscrubber/mcp-server`](https://github.com/moxno/privacyscrubber-mcp) — Model Context Protocol server for AI IDEs (Cursor, Antigravity, Windsurf).
- 📦 **NPM SDK**: [`privacyscrubber`](https://www.npmjs.com/package/privacyscrubber) — Zero-dependency ESM/CJS de-tokenization module (<1ms latency).

---

### 🔬 Academic Research & Treatises

- **Zero-Trust Data Sanitization (ZTDS)**: [Zenodo Paper (DOI: 10.5281/zenodo.22058770)](https://doi.org/10.5281/zenodo.22058770)
- **Empirical Latency & RAM Profiling Study**: [Center for Open Science (DOI: 10.17605/OSF.IO/5BYJF)](https://doi.org/10.17605/OSF.IO/5BYJF)
- **EU AI Act & US Privacy Statutory Compliance**: [Elsevier / SSRN #7335581](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7335581)
- **Preserving Attorney-Client Privilege in GenAI**: [Law Archive / OSF #4wc86](https://osf.io/preprints/lawarchive/4wc86/)

---

### ⚡ Tech Stack & Security Model

- **Security Architecture**: Zero-Trust Data Sanitization (ZTDS), Volatile RAM Session Isolation, Local Cryptography (`Argon2id` + `AES-GCM` / `XChaCha20-Poly1305`).
- **Core Stack**: Vanilla JavaScript (ES Modules), Web Workers, WebAssembly (PDF.js / Tesseract.js OCR), Manifest V3.
- **AI Protocols**: Model Context Protocol (stdio JSON-RPC 2.0).

---

### 🌐 Official Links & Verification

- 🌐 **Website**: [privacyscrubber.com](https://privacyscrubber.com)
- 🐙 **MCP Server**: [moxno/privacyscrubber-mcp](https://github.com/moxno/privacyscrubber-mcp)
- 💼 **LinkedIn**: [Ilya Sibiryakov](https://www.linkedin.com/in/ilya-sibiryakov/)
- 🪪 **ORCID**: [0009-0002-0642-5985](https://orcid.org/0009-0002-0642-5985)
