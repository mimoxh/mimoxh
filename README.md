# Hi, I'm mimoxh 👋

**AI Agent 工具 · Windows 桌面应用 · 开发效率**

我围绕 AI Agent 的日常使用开发工具：集中管理 Skills 与 MCP 配置、查看 AI 订阅用量，以及为 Agent 接入自建搜索服务。

Building practical tools for AI agents and everyday desktop workflows.

## 开源项目

### [Skills Manager](https://github.com/mimoxh/skills_manager)

集中管理多个 AI 客户端的 Agent Skills 与 MCP server 配置，减少重复安装和手动配置。

- 扫描本地 Skills，对比不同 Agent 的安装情况，并按需同步。
- 导入本地技能文件夹或 ZIP，从技能仓库浏览和安装 Skills。
- 管理 MCP server，支持 Agent 标签、自定义目录和主题切换。

`Tauri 2` · `Rust` · `React` · `TypeScript` · `Tailwind CSS`

### [AI Usage Monitor](https://github.com/mimoxh/ai_usage_monitor)

Windows 桌面 AI 订阅用量监控工具，把多个订阅的用量、余额与重置时间放在一起查看。

- 支持千问、OpenCode Go、MiniMax、MiMo 和 DeepSeek 余额。
- 支持多订阅管理、额度重置倒计时和自动刷新。
- 提供完整与简略视图，以及支持鼠标穿透的桌面悬浮窗。

`Flutter` · `Dart` · `Windows`

### [DSH SearXNG Search](https://github.com/mimoxh/dsh-searxng-search)

为 DSH（DeepSeek Harness）接入 SearXNG 的第三方搜索插件，适合自建或内网搜索服务。

- 让内置 `web_search` 使用 SearXNG JSON API。
- 保留原有搜索工具参数、结果卡片与引用格式。
- 零运行时依赖，无构建步骤，支持离线自测。

`JavaScript` · `Node.js` · `SearXNG`

## 关注的方向

- **Agent 工作流**：Skills、MCP 配置管理与搜索服务接入。
- **桌面体验**：多应用配置管理、用量可视化与轻量悬浮工具。
- **本地工具**：围绕日常使用中的具体问题，减少重复操作。

## English

I build tools for AI agent workflows and Windows desktops. My projects include **Skills Manager** for managing agent skills and MCP configurations, **AI Usage Monitor** for tracking AI subscriptions and balances, and **DSH SearXNG Search** for connecting DSH to a self-hosted search service.

欢迎通过对应项目的 Issues 反馈问题、提出建议或交流使用体验。
