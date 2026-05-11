# Wang Shanbo

> **Doing is the best way of thinking.**
>
> 36-year-old **Engineering Lead + Hardware Sourcing** at a Chinese B2B SaaS serving **500+ paying merchants** with **¥3B GMV** flowing through the platform.
>
> 5 months · 3 AI products shipped on the side · 1 killed · burning **$2,000/month** in top-tier LLMs.

🇬🇧 English (you're here) · 🇨🇳 [中文 README →](./README-zh.md)

---

## TL;DR

I'm 36, in Hangzhou. **Engineering Lead + Hardware Sourcing** at **Tai Man Man Tech (台满满科技)** — joined 2 years ago; **hardware sourcing was handed to me within my first 2 months** because of execution speed (most founders don't delegate this in 2 years; mine did in 2 months). Real day job: a production B2B SaaS for billiard halls — **500+ paying venues**, **¥3B platform GMV**, **10-person R&D**.

The unusual combination:

- **AI-native at production scale** — burn ~**$2,000 / 600M+ tokens per month** on Claude Opus and other frontier models
- **Cross-platform full-stack** — Web · Mobile · Desktop · Embedded shipped to paying customers in 5+ industries over 11 years
- **China hardware supply chain insider** — direct OEM-owner relationships for 6 hardware categories (lighting controllers, locker systems, serial-port-charging order pads, smart TVs, all-in-one POS terminals)
- **Indie builder** — shipped [NormCode](https://github.com/wangshanbo/NormCode) (AI IDE, v1 sunset), [Sentinel](https://github.com/wangshanbo/sentinel-specs) (web app, v2 in progress), [Guard](https://github.com/wangshanbo/guard) (Rust policy layer) on the side

## Day Job — what I actually do all week

| Dimension | Numbers |
|---|---|
| **Company** | Tai Man Man Tech (台满满科技), Hangzhou — joined 2 yrs ago |
| **Role** | Engineering Lead + Hardware Sourcing — sourcing handed to me within month 2 due to execution speed |
| **Customers in production** | **500+ billiard halls** across China |
| **Platform GMV** | **~¥3,000,000,000** (3B RMB) flowing through the system |
| **R&D team** | **10 engineers**, including 1 director-of-engineering hire |
| **Last 5 months — features shipped by the team** | **50+** production features (low bug rate per feature), **most of them written by AI under my orchestration** |
| **Last 5 months — backend modules I shipped via AI** | 3 Java modules end-to-end with AI: **lighting control · ESC/POS receipt printing · order scheduler**. Why I went hands-on (with AI): backend was shipping too slow — I built the SOPs first to **un-block the whole team**, then wrote the modules as proof-of-concept of those SOPs. |
| **Production AI workflow I authored & maintain** | A full set of Cursor rules + skills inside our codebase's `.cursor/` (project-level SOPs, role guardrails, loadable skills). The philosophy underneath: **author the SOPs with the strongest model (Opus / GPT-5), run code generation with the weakest model that still works (Haiku / 3.5)**. If the AI ships wrong code, default blame is on **my SOP**, never on the model. Goal: **let an average front-end or Java engineer, with this SOP set, produce code that conforms to our project's conventions on first attempt**. This is what actually drives the team's 50+ AI-shipped features — the practical proof behind the [Build-to-Think manifesto](https://github.com/wangshanbo/ai-native-sop/blob/main/00-manifesto-build-to-think.md). |
| **Front-end surfaces I continuously maintain** | **5+ apps in active iteration**: cashier desktop · merchant admin web · order-pad app · WeChat mini-program · in-house tooling |
| **Hardware OEM relationships I personally manage** | **6 categories · 6 factory owners on direct WeChat / phone** |
| **Third-party hardware/software vendors I integrated with** | **6** in the last 5 months |
| **Competitor hardware compatibility (the hidden moat)** | I personally reverse-engineer competitor hardware protocols (serial / wire / vendor SDK) so our software accepts the legacy gear competitors' customers already own — directly converted dozens of incumbent venues |
| **Trade shows attended** | On the floor in person, collecting requirements from billiard hall owners → feeding back into roadmap |

The non-obvious part — **as engineering lead in the AI era, my job is no longer to type code**. It's to author the SOPs that let AI type code correctly, and spend the freed bandwidth on the things only humans can do: vendor diligence, supply chain, hardware reverse engineering, customer floor at trade shows, and shipping side projects that compound long-term reputation.

## What I shipped on the side (last 5 months · evenings & weekends)

| Product | Stack | Status | What it is |
|---|---|---|---|
| 🛡️ **[NormCode](https://github.com/wangshanbo/NormCode)** | TypeScript · VS Code fork · GLM | **v1 · sunset** | Long-running AI IDE — 10 versions of agent harness, 13+ core services (BudgetGovernor / HumanGate / EpisodicMemory / FailureTaxonomy / RollingPlanner …). I shipped it. Then I killed the form-factor. Lessons live in Sentinel. |
| 🚀 **[Sentinel](https://github.com/wangshanbo/sentinel-specs)** | TypeScript · Web App · Node · Sandbox | **v2 · in progress · public specs** | "AI co-founder" web product: anyone, by chatting, ships a real, deployable, evolvable, operable full-stack app. Direct competitor to Bolt / Lovable / v0 / Replit Agent — built around **continuous evolution after launch**, not 5-minute demos. |
| 🦀 **[Guard](https://github.com/wangshanbo/guard)** | Rust · MCP Server | **shipped** | Policy layer for AI development: MCP gives AI hands, Skills gives AI experience, **Guard makes sure AI doesn't do the wrong thing**. One-line install into any project's `.cursor/mcp.json`. |
| ✍️ **[ai-native-sop](https://github.com/wangshanbo/ai-native-sop)** | Markdown | 1/10 published | Chinese blog series open-sourcing the methodology behind the $2K/month AI spend. Manifesto chapter live: [《Build to Think》](https://github.com/wangshanbo/ai-native-sop/blob/main/00-manifesto-build-to-think.md). |

## My stack

| Domain | Tech |
|---|---|
| Front-end / Cross-platform | Vue 3 · React · Next.js · **Flutter** · Quasar · WeChat MP · Electron |
| Back-end | TypeScript · Node · Java (legacy maintenance) · Rust (Guard) |
| AI | Cursor · Claude Code · Anthropic API · OpenAI · 智谱 GLM · Self-built [NormCode](https://github.com/wangshanbo/NormCode) |
| **IoT × Hardware** | **Serial port · MQTT · Lighting control · ESC/POS · Android Kiosk** · **direct relationships with Chinese OEM owners for: lighting controllers, locker systems, serial-port-charging order pads, smart TVs, all-in-one terminals** |
| Methodology | AI-native dev · Spec-driven dev · Long-running agent harness · Strangler pattern for legacy |

## What makes my profile rare

```
AI-native engineer at $2K/mo production scale
  ✕ Cross-platform full-stack shipped to paying B2B
    ✕ China IoT hardware supply chain insider (6 OEM owners on direct line)
      = a combination found in <50 people globally.
```

- **AI-native at production scale**: $2K/month sustained spend on frontier models, with NormCode + Sentinel + Guard as proof
- **Cross-platform full-stack**: Web · Mobile · Desktop · Embedded — one person can ship a complete product surface
- **Hardware × AI**: Direct OEM-owner relationships in China for 6 hardware categories. **I can prototype an AI hardware device in 2 weeks, not 6 months**
- **B2B SaaS for 11 years**: Education · e-contracts · internet cafes · billiard halls · retail POS — all delivered to production paying customers
- **Real say, not just title**: Engineering lead by org chart; **the founder handed hardware sourcing over within my first 2 months** at the company — the org chart catches up later, but the trust signal was set in 8 weeks

## Now

- 🚀 Shipping **Sentinel v2** to the first 100 real users (public specs at [`sentinel-specs`](https://github.com/wangshanbo/sentinel-specs))
- 🦀 Open-sourcing **Guard** to Cursor / Claude Code communities
- ✍️ Writing [《月烧 $2,000 AI 反常识 SOP》](https://github.com/wangshanbo/ai-native-sop) — 10-chapter Chinese series
- 🔌 Prototyping **AI × hardware** experiments using my OEM supply chain
- 🤝 Open to: **fractional CTO**, **AI workflow consulting**, **AI × hardware co-founding**, **remote IC roles** at AI-native teams

## Beliefs

> ## **"AI for everyone — not just for those who can afford the strongest model."**
>
> A 70-point model + strong SOPs producing 80-point code beats an 80-point model + weak prompts producing 85-point code at 10× the cost. The first scales to every developer on the planet. The second only scales to the 5% who can afford it.
>
> Even as frontier models keep getting stronger and the "tooling layer" keeps getting thinner, **the strongest model will never be cheap enough for everyone**. So my entire methodology — the SOPs, the side projects, the writing — is built for the **95%** who need to ship production-grade code without burning a salary on tokens every month. **I'm building for the 95%.**

> **"Prompt engineering is dead"** is a lie sold by people who can't ship.
> Real AI leverage comes from **context engineering** — feeding the model your codebase rules, business invariants, and review SOPs every single turn.

> **Doing is the best way of thinking.** I shipped NormCode v0~v9 in 3 months and killed it in month 4. That kill — built on actual production code, not on a PPT — is worth more than 6 months of strategic discussion.

> **Strong model authors the SOP. Weak model runs the code.** Most teams burn frontier-model tokens on every line of generated code. I burn them once on the SOPs (Opus / GPT-5), and let the weakest model that still works (Haiku / 3.5) do the per-line generation. **Costs drop ~10×. Output stays production-grade. The team scales without a single new senior hire.**

> **If the AI ships wrong code, the SOP is wrong — never the model.** This single mental shift is what separates "AI as toy" from "AI as production teammate". Treat AI like a new hire: if the new hire keeps making the same mistake, you don't fire the new hire — you fix the onboarding doc.

> **As engineering lead in the AI era, your job is no longer to type code.** It's to **author the SOPs that let AI type code correctly** (mine live in our codebase's `.cursor/`), and spend the freed bandwidth on the things only humans can do: vendor diligence, supply chain, hardware reverse engineering, customer floor at trade shows, and shipping side projects that compound long-term reputation.

## Reach out

- 📧 [627257359@qq.com](mailto:627257359@qq.com)
- 🐙 [github.com/wangshanbo](https://github.com/wangshanbo)
- 💬 即刻 / X / WeChat — links coming soon

---

<sub>This profile is itself an open experiment in **AI-native personal branding**. The whole repo is generated, refined, and maintained with the same workflow described above. PRs welcome — especially typo fixes, English polishing, or "I tried this and got X" testimonials.</sub>
