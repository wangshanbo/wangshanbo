# Wang Shanbo

Engineering lead and hardware sourcing at Tai Man Man Tech in Hangzhou. We make a B2B SaaS for billiard halls — around 500 venues in production, roughly ¥3B in platform GMV, a 10-person engineering team. I joined two years ago.

Day to day I run operational calls with our six OEM partners and co-author hardware architecture decisions with them. Recent work includes moving our lighting control radio from ZigBee to 433MHz to LoRa as venue density grew past what a ZigBee mesh could carry, and helping plan a motherboard generation upgrade for our Android order pads.

On the engineering side I maintain five front-end surfaces — cashier desktop, merchant admin web, order pad, WeChat mini-program, internal tooling — and wrote three Java backend modules with AI: lighting control, ESC/POS receipts, and an order scheduler. Most of the team's day-to-day code is also written by AI, driven by a set of project-level Cursor rules and skills I authored and maintain in our repo's `.cursor/`. About 50 production features over the last five months, team size unchanged.

Outside of work I spend around $2,000 a month on frontier LLMs and made a few things to share what I picked up:

- [NormCode](https://github.com/wangshanbo/NormCode) — a long-running AI IDE on top of VS Code. Shipped v0 through v9, then archived; the form factor wasn't right.
- [Sentinel](https://github.com/wangshanbo/sentinel-specs) — a web product that helps non-coders ship and keep evolving real apps by chatting. Public specs only for now.
- [Guard](https://github.com/wangshanbo/guard) — a small Rust policy layer that keeps AI codegen from doing the wrong thing. Installs as an MCP server.
- [ai-native-sop](https://github.com/wangshanbo/ai-native-sop) — a Chinese essay series on the AI workflow I use day to day.
- [qianxuesen-metasynthesis](https://github.com/wangshanbo/qianxuesen-metasynthesis) — a side research project mapping Qian Xuesen's 1990 metasynthesis hall to Anthropic's 2026 harness engineering. Paused at v0.2; 15 falsifiable predictions to revisit in 2031.

The through-line in all of this: I don't think the strongest model will ever be cheap enough for everyone. So I spend my best tokens authoring the SOPs, and let the cheapest working model write the code. When the AI ships wrong code I assume my SOP is wrong, not the model.

中文 README → [README-zh.md](./README-zh.md)

627257359@qq.com
