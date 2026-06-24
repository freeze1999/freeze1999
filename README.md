### Self-taught AI systems builder

I build production AI without a formal CS background. Most of my work circles one problem: making LLM agents persistent, autonomous, and cheap to run.

**Selected work**

[the-synthetic-mind](https://github.com/freeze1999/the-synthetic-mind) is a persistent AI agent that keeps its memory and identity even when you swap the model underneath it. Tiered memory, nightly consolidation, and a substrate-swap experiment that shows the identity holds.

[reverie](https://github.com/freeze1999/reverie) is a reasoning-first idle engine for persistent agents. When the agent has nothing to do, its behaviour emerges from reasoning about its own idle state, gated by a cheap, model-free safety layer. Packaged with tests and CI.

[claude-mac-bridge](https://github.com/freeze1999/claude-mac-bridge) and [codex-mac-bridge](https://github.com/freeze1999/codex-mac-bridge) are MCP servers that let an agent delegate coding tasks to Claude Code or Codex on a remote Mac over SSH and Tailscale, with persistent sessions.

[somnus](https://github.com/freeze1999/somnus) and [agent-curfew](https://github.com/freeze1999/agent-curfew) handle the boring but expensive part: deciding when an agent should wind down, and blocking off-hours traffic at zero token cost.

I also built a live e-commerce site with a custom inventory and quotation pipeline for a lighting company. The code is private since it's a real business, but it's running in production.

