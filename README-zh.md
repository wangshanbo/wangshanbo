# 王善波

在杭州的台满满科技做研发主管和硬件采购。我们做球房 SaaS——大约 500 家球房在线，平台跑过 30 亿流水，研发团队 10 人。两年前入职。

日常跟 6 家 OEM 工厂做电话回访，跟他们一起定硬件技术方案。最近在做的事包括推动灯控通信协议从 ZigBee 到 433MHz 再到 LoRa 的演进——场地密度大到 ZigBee mesh 撑不住了，于是切到 433，进一步规模化又切到 LoRa；以及参与 Android 点单机的主板换代。

技术上我同时维护 5 个前端项目：收银端、管理端、点单机、小程序、内部工具；用 AI 写了 3 个 Java 后端模块：灯控、ESC/POS 小票、订单定时任务。团队的代码绝大多数也由 AI 在我编排下写出，靠的是我在公司代码仓库 `.cursor/` 里维护的一套 rules 和 skills。过去 5 个月大约 ship 了 50 个生产功能，团队规模始终是 10 人。

业余每个月在最强大模型上花大约 2000 美金，写了几个东西把过程中学到的分享出来：

- [NormCode](https://github.com/wangshanbo/NormCode) —— 基于 VS Code 的长程 AI IDE。从 v0 做到 v9，然后归档；形态不对。
- [Sentinel](https://github.com/wangshanbo/sentinel-specs) —— 让不懂编程的人通过对话做出真实可演化应用的 web 产品。目前只公开 specs。
- [Guard](https://github.com/wangshanbo/guard) —— Rust 写的小型 AI 策略层，防止 AI 写出不该写的代码。MCP server 形态，一行命令装进任何项目。
- [ai-native-sop](https://github.com/wangshanbo/ai-native-sop) —— 中文连载，关于我每天在用的 AI 工作流。
- [qianxuesen-metasynthesis](https://github.com/wangshanbo/qianxuesen-metasynthesis) —— 业余研究项目，把钱学森 1990 年综合集成研讨厅与 2026 年 Anthropic Harness Engineering 做结构对照。已暂停于 v0.2，15 个可证伪预测留待 2031 年回看。

一条主线：哪怕大模型越来越强，最强最贵的模型也永远不会便宜到人人都用得起。所以我把最贵的 token 花在写 SOP 上，让最便宜的可用模型去写代码。AI 写错了，我假设是 SOP 错了，不是模型错了。

English README → [README.md](./README.md)

627257359@qq.com
