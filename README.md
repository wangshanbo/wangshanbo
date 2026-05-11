# Wang Shanbo · 王善波

> **Doing is the best way of thinking.**
>
> 36-year-old **Engineering Lead + Hardware Sourcing** at a Chinese B2B SaaS serving **500+ paying merchants** with **¥3B GMV** flowing through the platform.
>
> 5 months · 3 AI products shipped on the side · 1 killed · burning **$2,000/month** in top-tier LLMs.

🇬🇧 [English](#english) · 🇨🇳 [中文](#中文)

---

<a id="english"></a>

## TL;DR

I'm 36, in Hangzhou. **Engineering Lead + Hardware Sourcing** at **Tai Man Man Tech (台满满科技)** — alongside the founder for **5+ years**. Real day job: a production B2B SaaS for billiard halls, **500+ paying venues**, **¥3B platform GMV**, **10-person R&D**.

The unusual combination:

- **AI-native at production scale** — burn ~**$2,000 / 600M+ tokens per month** on Claude Opus and other frontier models
- **Cross-platform full-stack** — Web · Mobile · Desktop · Embedded shipped to paying customers in 5+ industries over 11 years
- **China hardware supply chain insider** — direct OEM-owner relationships for 6 hardware categories (lighting controllers, locker systems, serial-port-charging order pads, smart TVs, all-in-one POS terminals)
- **Indie builder** — shipped [NormCode](https://github.com/wangshanbo/NormCode) (AI IDE, v1 sunset), [Sentinel](https://github.com/wangshanbo/sentinel-specs) (web, v2 in progress), [Guard](https://github.com/wangshanbo/guard) (Rust policy layer) on the side

## Day Job — what I actually do all week

| Dimension | Numbers |
|---|---|
| **Company** | Tai Man Man Tech (台满满科技), Hangzhou — 5+ yrs alongside the founder |
| **Role** | Engineering Lead + Hardware Sourcing |
| **Customers in production** | **500+ billiard halls** across China |
| **Platform GMV** | **~¥3,000,000,000** (3B RMB) flowing through the system |
| **R&D team** | **10 engineers**, including 1 director-of-engineering hire |
| **Last 5 months — features shipped by the team** | **50+** production features (low bug rate per feature) |
| **Last 5 months — modules I personally owned hands-on** | 3 critical: **lighting control · ESC/POS receipt printing · order scheduler** |
| **Hardware OEM relationships I personally manage** | **6 categories · 6 factory owners on direct WeChat / phone** |
| **Third-party hardware/software vendors I integrated with** | **6** in the last 5 months |
| **Trade shows attended** | On the floor in person, collecting requirements from billiard hall owners → feeding back into roadmap |

The non-obvious part — **as engineering lead, I dropped my hands-on coding from 80% → 20% of my week**. The 60% I freed up went into supply chain / vendor diligence / trade show requirements / and the open-source side projects below. **In the AI era this is what an engineering lead's leverage actually looks like.**

## What I shipped on the side (last 5 months · evenings & weekends)

| Product | Stack | Status | What it is |
|---|---|---|---|
| 🛡️ **[NormCode](https://github.com/wangshanbo/NormCode)** | TypeScript · VS Code fork · GLM | **v1 · sunset** | Long-running AI IDE — 10 versions of agent harness, 13+ core services (BudgetGovernor / HumanGate / EpisodicMemory / FailureTaxonomy / RollingPlanner …). I shipped it. Then I killed the form-factor. Lessons live in Sentinel. |
| 🚀 **[Sentinel](https://github.com/wangshanbo/sentinel-specs)** | TypeScript · Web App · Node · Sandbox | **v2 · in progress · public specs** | "AI co-founder" web product: anyone, by chatting, ships a real, deployable, evolvable, operable full-stack app. Direct competitor to Bolt / Lovable / v0 / Replit Agent — built around **continuous evolution after launch**, not 5-minute demos. |
| 🦀 **[Guard](https://github.com/wangshanbo/guard)** | Rust · MCP Server | **shipped** | Policy layer for AI development: MCP gives AI hands, Skills gives AI experience, **Guard makes sure AI doesn't do the wrong thing**. One-line install into any project's `.cursor/mcp.json`. |
| ✍️ **[ai-native-sop](https://github.com/wangshanbo/ai-native-sop)** | Markdown | 1/10 published | Chinese blog series open-sourcing the methodology behind $2K/month AI spend. Manifesto chapter live: [《Build to Think》](https://github.com/wangshanbo/ai-native-sop/blob/main/00-manifesto-build-to-think.md). |

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
- **Real say, not just title**: Engineering lead by org chart, but 5+ years of trust with the founder means real influence on product / tech / hardware roadmap

## Now

- 🚀 Shipping **Sentinel v2** to the first 100 real users (public specs at [`sentinel-specs`](https://github.com/wangshanbo/sentinel-specs))
- 🦀 Open-sourcing **Guard** to Cursor / Claude Code communities
- ✍️ Writing [《月烧 $2,000 AI 反常识 SOP》](https://github.com/wangshanbo/ai-native-sop) — 10-chapter Chinese series
- 🔌 Prototyping **AI × hardware** experiments using my OEM supply chain
- 🤝 Open to: **fractional CTO**, **AI workflow consulting**, **AI × hardware co-founding**, **remote IC roles** at AI-native teams

## Beliefs

> **"Prompt engineering is dead"** is a lie sold by people who can't ship.
> Real AI leverage comes from **context engineering** — feeding the model your codebase rules, business invariants, and review SOPs every single turn.

> **Doing is the best way of thinking.** I shipped NormCode v0~v9 in 3 months and killed it in month 4. That kill — built on actual production code, not on a PPT — is worth more than 6 months of strategic discussion.

> **As engineering lead in the AI era, your hands-on coding ratio drops to 20%.** The other 80% goes to: vendor diligence, supply chain, customer floor at trade shows, and shipping side projects that compound your reputation.

## Reach out

- 📧 [627257359@qq.com](mailto:627257359@qq.com)
- 🐙 [github.com/wangshanbo](https://github.com/wangshanbo)
- 💬 即刻 / X / WeChat — links coming soon

---

<a id="中文"></a>

## 中文版

我是王善波，36 岁，杭州。

### TL;DR

- 🏢 **台满满科技 · 研发主管 + 硬件采购负责人**，跟随创始人 **5+ 年**
- 📊 真实业务规模：**服务 500+ 球房 / 平台总流水 ¥30 亿 / 10 人研发部**
- 🧠 **AI 应用层重度实践者**：业余时间月烧 **\$2,000 / 6 亿 tokens** 在 Claude Opus 等顶级模型上
- 🚀 **过去 5 个月业余 ship 了 3 个 AI 产品 + 砍了 1 个**：NormCode (v1·已 sunset) / Sentinel (v2·进行中) / Guard (Rust 策略层)
- 🛠️ **跨端全栈** 11 年：Vue / React / Flutter / TypeScript / Java（存量）/ Rust
- 🔌 **国内硬件供应链直通**：灯控 / 存杆柜 / 点单机（串口充电）/ 电视 / 一体机 **6 类硬件 / 6 家 OEM 工厂老板直达**

### Day Job — 我每天到底在干什么

| 维度 | 数字 |
|---|---|
| **公司** | 台满满科技 · 杭州 · 跟随创始人 5+ 年 |
| **职位** | 研发主管 + 硬件采购负责人 |
| **生产付费客户** | **500+ 球房** |
| **平台总 GMV** | **~¥30 亿** |
| **研发团队** | **10 人**（含 1 位浙大硕招进来的研发总监）|
| **过去 5 个月团队 ship 的功能** | **50+ 个生产功能**，bug 率较低 |
| **过去 5 个月我亲自下场写的模块** | 3 个关键模块：**灯控 · ESC/POS 小票 · 订单定时任务** |
| **我亲自管的 OEM 工厂老板** | **6 类硬件 / 6 家工厂老板直接微信电话** |
| **5 个月对接的三方软硬件公司** | **6 家** |
| **展会** | **亲自上展会前线**面对面收球房老板需求，反向推动 roadmap |

非常反常识的一点 —— **作为研发主管，我把"亲自写代码"的占比从 80% 砍到 20%**。多出来的 60% 时间去管供应链、对接三方、上展会、业余 build 上面那些开源。**这才是 AI 时代研发主管的真实杠杆姿势**。

### 业余 ship 的 4 个公开作品

| 产品 | 状态 | 是什么 |
|---|---|---|
| 🛡️ **[NormCode](https://github.com/wangshanbo/NormCode)** | v1 · 已 sunset | 长程 AI IDE，10 个版本完整迭代，13+ 核心服务全部上线后我亲手砍掉了 vscode fork 这个形态 |
| 🚀 **[Sentinel](https://github.com/wangshanbo/sentinel-specs)** | v2 · 进行中 · 公开 specs | "AI 合伙人"web 产品：让普通人通过对话做出**真实可上线、可演化、可运营**的全栈应用。直接对标 Bolt / Lovable / v0 / Replit Agent |
| 🦀 **[Guard](https://github.com/wangshanbo/guard)** | 已开源 | Rust 写的 AI 开发策略约束层。**MCP 让 AI 有手脚，Skills 让 AI 有经验，Guard 让 AI 不做错事** |
| ✍️ **[ai-native-sop](https://github.com/wangshanbo/ai-native-sop)** | 1/10 篇已发布 | 把私人 AI 工作流方法论开源化的中文连载。manifesto 在这里：[《做就是最好的想》](https://github.com/wangshanbo/ai-native-sop/blob/main/00-manifesto-build-to-think.md) |

### 我的稀缺性

```
AI Native 工程师（月烧 $2K 持续生产级使用）
  ✕ 跨端全栈（已 ship 5+ 行业付费客户）
    ✕ 国内 OEM 直达 insider（6 家工厂老板手机号）
      = 全球范围内不超过 50 个人的画像
```

- **AI Native 生产级**：月烧 \$2K 持续支出在前沿模型上，3 个 ship 出来的产品作为证据
- **跨端全栈**：Web / Mobile / 桌面 / Embedded 一人交付完整产品形态
- **硬件 × AI**：6 类硬件 / 6 家 OEM 老板直达。**AI 硬件原型 2 周可出**，不是 6 个月
- **B2B SaaS 11 年**：教育 / 电子合同 / 网吧 / 球房 / 零售 POS，全部 ship 到生产付费客户
- **不是头衔，是话语权**：组织结构上是研发主管，但跟创始人 5+ 年信任意味着对产品 / 技术 / 硬件 roadmap 有实质影响力

### 现在在做什么

- 🚀 Sentinel v2 ship 到第一批 100 个真实用户（公开 specs：[`sentinel-specs`](https://github.com/wangshanbo/sentinel-specs)）
- 🦀 Guard 开源到 Cursor / Claude Code 社区
- ✍️ 写 [《月烧 \$2,000 AI 反常识 SOP》](https://github.com/wangshanbo/ai-native-sop) 中文连载（共 10 篇）
- 🔌 用 OEM 供应链 prototype 几个 AI × 硬件实验
- 🤝 接 **fractional CTO** / **AI 工作流咨询** / **AI × 硬件创业合伙** / **海外 AI Native 团队远程 IC**

### 我相信

> **"Prompt engineering 已死"** 是不会 ship 的人卖的鸡汤。
> AI 真正的杠杆来自**上下文工程** —— 每一轮对话都把代码规约、业务不变量、review SOP 喂给模型。

> **做就是最好的想。** NormCode v0~v9 我 ship 了 3 个月，第 4 个月砍了。那次"砍"是基于真实生产代码做的判断，不是 PPT —— 它的价值大于 6 个月的战略讨论。

> **AI 时代的研发主管，亲自写代码占比应该降到 20%**。多出来的 80% 应该投入到：供应商尽调、供应链、展会前线、业余 ship 能复利你声誉的项目。

### 找我

- 📧 627257359@qq.com
- 🐙 [github.com/wangshanbo](https://github.com/wangshanbo)
- 💬 即刻 / X / 微信 — 链接持续更新中

---

<sub>This profile is itself an open experiment in **AI-native personal branding**. The whole repo is generated, refined, and maintained with the same workflow described above. PRs welcome — especially typo fixes, English polishing, or "I tried this and got X" testimonials.</sub>
