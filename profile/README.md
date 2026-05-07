## Hi there 👋

**Project Tharsis** is a collection of personal experiments — built to re-explore the world through a new lens: **90% artificial intelligence** plus **10% pure human intuition**.

Each project starts with a question: *Can AI make this better?* The answer lives in code.

---

### 🎁 [Argus](https://github.com/Project-Tharsis/argus) — Gift Recommendation Engine
> *Can an AI Agent find the perfect gift?*

An open-source MCP Server that turns vague intentions ("buy something for my girlfriend") into structured shopping queries, then generates recommendations with reasoning. All prompt engineering lives in external `skills/*.md` files — Python handles engineering, not LLM opinions. **v0.1.0 released.**

`Python` · `FastMCP` · `skill-based architecture`

---

### 🏃 [ElCap](https://github.com/Project-Tharsis/elcap) — Personal Health Coach
> *Can AI read your body better than you can?*

A native macOS/iOS app that ingests HealthKit data, computes advanced training metrics (TRIMP, ACWR, ATL/CTL), and provides AI-powered coaching via Moonshot AI. Supabase backend with Edge Functions. The training algorithms are the real product — the AI just asks the right questions.

`Swift` · `SwiftUI` · `HealthKit` · `Supabase` · `Moonshot AI`

---

### 🌬️ [Boreas](https://github.com/Project-Tharsis/boreas) — Personal VPN
> *Can setting up a VPN take 30 seconds?*

A Python CLI that turns any Linux VPS into a WireGuard VPN with one command. Client management, QR codes for mobile onboarding, multi-region support. No YAML sprawl, no forgotten iptables rules. Built because VPN setup should be boring.

`Python` · `WireGuard` · `CLI`

---

### 🏛️ [Clio](https://github.com/Project-Tharsis/clio) — Social Media Monitor
> *Can AI surface what matters before the market does?*

A cross-platform intelligence system tracking AI + economy discussions across US (Reddit, HN, X/Twitter) and China (小红书, 微博, 知乎). Cron-driven collection → structured daily briefings. Named after the muse of history — because narratives shape markets.

`Python` · `cron` · `multi-platform`

---

### 🛡️ [Faro](https://github.com/Project-Tharsis/faro) — Security Pipeline
> *Can AI police itself?*

A security scanner for Hermes Agent skills and plugins. 19 checks across dangerous calls, credential leaks, config access, and network activity. Staging → Audit → Approve pipeline. Nothing becomes active without a scan. Named after lighthouses — because someone has to watch the rocks.

`Python` · `CLI` · `pre-llm-call hook`

---

### Philosophy

These aren't SaaS products. They're tools built by one person, for one person, then opened up. Each one answers a concrete need — gift anxiety, training optimization, VPN drudgery, information overload, supply chain trust.

The common thread: **AI isn't the product. It's the interface.** Argus doesn't search — it tells you what to search. ElCap doesn't train — it tells you how to interpret your training. Clio doesn't think — it tells you what to think about.

---

Built with taste. Maintained with obsession. [All MIT licensed.](https://github.com/Project-Tharsis)
