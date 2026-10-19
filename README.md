# Shadowrocket configuration

This repository is **private** and stores the original Shadowrocket configuration.

## Source configuration
- `erix20261016_chatgpt_US01.conf` — original iCloud configuration, preserved without modification.
- ChatGPT policy group `ChatGPT-US` currently selects the subscription node `🇨🇳 台湾 02`. The group name is legacy; it does **not** indicate that a US node must be used.
- Existing subscriptions/nodes remain managed within Shadowrocket.

## Remote-updates plan
A private GitHub raw URL is not anonymously accessible to Shadowrocket. To use native URL subscription updates:
1. Create a **separate public repository** for a sanitized configuration or public rule lists, excluding tokens, subscription addresses, and secrets.
2. Use `https://raw.githubusercontent.com/OWNER/REPO/main/FILE.conf` for the public configuration.
3. In Shadowrocket, use **Config → + → Download** and activate the downloaded config.
4. Set routing mode to Config and enable config updates in Shadowrocket's settings.
5. Edit files in the public repository from ChatGPT/Codex; updates apply when Shadowrocket refreshes.

**Security:** Do not make this backup repository public without examining every file and commit history for sensitive material.

**Operational:** Keep an iCloud copy of the last working configuration to recover from malformed updates.
