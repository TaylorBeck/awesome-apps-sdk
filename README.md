# 🌟 Awesome Apps SDK

> A curated list of **community projects, tools, tutorials, and examples** built with or around the new [OpenAI Apps SDK](https://developers.openai.com/apps-sdk), enabling developers to create rich, interactive apps that run *inside ChatGPT*.

---

## 🧰 What is the Apps SDK?

The **Apps SDK** is an open-source toolkit by OpenAI for building custom apps that integrate directly into ChatGPT. It lets you define rich user interfaces, connect external tools or APIs, and combine them with the [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) — all without leaving the chat interface.

* 🧑‍💻 Build **interactive apps** inside ChatGPT
* 🔌 Combine with MCP servers for deeper integrations
* 🧪 Works with Python, TypeScript, and more
* 📦 Fully open source and extensible

---

## 📦 Official Examples

| Repo                                                                                  | Description                                                                       |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [openai/openai-apps-sdk-examples](https://github.com/openai/openai-apps-sdk-examples) | Official starter projects showing UI components, MCP integration, and sample apps |
| [openai/openai-agents-python](https://github.com/openai/openai-agents-python)         | Multi-agent orchestration framework that pairs well with Apps SDK                 |
| [openai/openai-agents-js](https://github.com/openai/openai-agents-js)                 | JavaScript/TypeScript agent SDK for apps                                          |
| [openai/openai-realtime-agents](https://github.com/openai/openai-realtime-agents)     | Real-time agent demo showcasing live interactions                                 |

---

## 🚀 Community Apps & Experiments

| Repo                                                                | Description                                                  |
| ------------------------------------------------------------------- | ------------------------------------------------------------ |
| [LibreChat](https://github.com/danny-avila/LibreChat)               | Open-source ChatGPT UI exploring native Apps SDK integration |
| [fastmcp](https://github.com/fastmcp/fastmcp)                       | Lightweight MCP server framework planning Apps SDK support   |
| [PipedreamHQ/mcp](https://github.com/PipedreamHQ/mcp)               | Dynamic MCP servers — can be combined with Apps SDK UIs      |
| [kaeawc/android-mcp-sdk](https://github.com/kaeawc/android-mcp-sdk) | Android SDK for hosting MCP servers — useful for mobile apps |

---

## 🔩 MCP SDKs & Building Blocks

Since Apps SDK builds on top of **MCP**, many existing tools can be reused:

| Repo                                                                                          | Language                                              | Description |
| --------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ----------- |
| [modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) | TypeScript SDK for MCP servers and clients            |             |
| [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)         | Python SDK for building MCP integrations              |             |
| [codeboyzhou/mcp-java-sdk-examples](https://github.com/codeboyzhou/mcp-java-sdk-examples)     | Java MCP server samples, including Spring integration |             |

---

## 📚 Guides, Articles & Tutorials

* [How to Create a ChatGPT App with the Apps SDK](https://developers.openai.com/apps-sdk) – official guide
* [Cursor: Building ChatGPT Apps with the Apps SDK](https://cursor.sh/blog) – walkthrough & workflow tips
* [Wired: ChatGPT Is Getting Apps](https://www.wired.com) – launch coverage & ecosystem context

---

## 🤝 Contributing

Want to add your project? Fork this repo and submit a PR with:

```markdown
- [repo-name](https://github.com/username/repo-name) – Short description (tech stack, what it does, why it’s cool)
```

Please include:

* 🧑‍💻 Tech stack
* 📦 How it uses the Apps SDK
* 📸 (Optional) Demo GIF or screenshot
