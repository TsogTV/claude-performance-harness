# ⚡ Performance Harness for Claude by TsogCreatives Lab (Free Tier Optimization)
Ultra-lean Claude Desktop harness &amp; system instructions (CLAUDE.md). Eliminates token bloat, enforces surgical search/replace edits, and stops rate-limit lockouts on free/pro tiers.

===

Stop getting locked out by Claude Desktop rate limits. This ultra-lean configuration strips out background MCP schema bloat, enforces surgical search/replace code output, and halts speculative hallucinations.

## 🎯 Features
* **Zero Conversational Filler:** Saves 50+ tokens per turn.
* **Search/Replace Block Format:** Eliminates full-file rewrites (70-90% token reduction).
* **Grounding Over Guessing:** Claude stops immediately if a file or parameter is missing.
* **Payload-Based Intercepts:** Triggers safety checkpoints before hitting context caps.

## 🛠️ Installation

1. Copy `CLAUDE.md` to your root configuration directory (`~/.claude/CLAUDE.md` or `%APPDATA%\Claude\CLAUDE.md`).
2. Update your `claude_desktop_config.json` using `claude_desktop_config.template.json`.
3. Rename inactive MCP servers with `_DISABLED` (e.g., `"_local_n8n_DISABLED"`) to free up context tokens.

---
⚡ *Maintained by TsogCreatives Lab (Solo Dev & Creative Studio)*
