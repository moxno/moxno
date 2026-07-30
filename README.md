# PrivacyScrubber Ecosystem 🛡️

Building **[PrivacyScrubber](https://privacyscrubber.com)** — the zero-trust, 100% client-side PII sanitization engine for AI workflows.

---

### 🛠️ Core Projects

- 🌐 **Web App**: [PrivacyScrubber.com](https://privacyscrubber.com) — 100% browser-native data redaction (zero server logs, Airplane Mode verified).
- 🧩 **Chrome Extension**: [PrivacyScrubber on CWS](https://chromewebstore.google.com/detail/privacyscrubber) — In-page automatic prompt sanitization for ChatGPT, Claude & Gemini.
- 🤖 **MCP Server**: [`@privacyscrubber/mcp-server`](https://github.com/moxno/privacyscrubber-mcp) — Model Context Protocol server for AI IDEs (Cursor, Antigravity, Windsurf).
- 📦 **NPM SDK**: [`privacyscrubber`](https://www.npmjs.com/package/privacyscrubber) — Zero-dependency ESM/CJS de-tokenization module.

---

### ⚡ Tech Stack & Security Model

- **Security Architecture**: Zero-Trust Data Sanitization (ZTDS), Volatile RAM Session Isolation, Local Cryptography (`Argon2id` + `AES-GCM`).
- **Core Stack**: Vanilla JavaScript (ES Modules), Web Workers, WebAssembly (PDF.js / Tesseract.js OCR), Manifest V3.
- **AI Protocols**: W3C WebMCP discovery, stdio JSON-RPC 2.0.

---

### 🌐 Official Links

- 🌐 **Website**: [privacyscrubber.com](https://privacyscrubber.com)
- 🐙 **MCP Server Repo**: [moxno/privacyscrubber-mcp](https://github.com/moxno/privacyscrubber-mcp)
