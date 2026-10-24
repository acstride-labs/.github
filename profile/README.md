# AC-Stride

## Competitive programming, inside VS Code

AC-Stride brings Codeforces statements, solutions and local tests into one workspace. Import a round or a single problem, write in your preferred language, and check your work without leaving your editor.

- C++, Python, Java and Kotlin, with separate templates and local toolchain settings.
- Automatic statement and sample downloads, custom tests, output differences and execution controls.
- Submission history, verdicts and standings; optional confirmed submission through CF Tool.
- Optional AI statement translation through your own model provider, with configurable prompts, target languages and a local LRU request cache.

Codeforces tools ship with the extension. Install the compiler or runtime for your solution language separately. Login and automatic submission are experimental and may be blocked by Codeforces site verification; public downloads and local practice do not require login.

[Website](https://acstride.com/en) · [Get the extension](https://github.com/acstride-labs/acstride-vscode-extension/releases) · [Documentation](https://github.com/acstride-labs/acstride-vscode-extension#readme)

---

### 题面、代码、测试 都在 VS Code

为算法竞赛与日常练习打造的工具集。从导入 Codeforces 比赛和题目，到编写解答、运行测试、查看提交结果，让做题流程留在熟悉的编辑器里。

[官网](https://acstride.com/zh-CN) · [下载插件](https://github.com/acstride-labs/acstride-vscode-extension/releases) · [使用文档](https://github.com/acstride-labs/acstride-vscode-extension#readme)

## 在一个工作区里解题

- **比赛与练习**：导入整场 Codeforces 比赛、单道题目，或创建本地练习；自动下载题面和样例。
- **多编程语言**：支持 C++、Python、Java 和 Kotlin，提供独立的代码模板、环境检测与本地运行配置。
- **测试与反馈**：运行样例和自定义用例，查看标准输出、错误信息与输出差异，支持超时控制和取消运行。
- **比赛动态**：查看提交记录、判题结果与排名；提供复制代码并前往官网提交，以及需要登录和二次确认的一键提交。
- **可选 AI 辅助**：连接自己的模型服务，按需或自动翻译题面，配置目标语言、Prompt 与本地 LRU 请求缓存。
- **多语言界面**：支持简体中文、English、Русский 和日本語。

Codeforces 工具随插件打包，无需另行安装 CF Tool。运行解答需要准备对应语言的编译器或运行环境。登录与自动提交属于实验功能，可能受 Codeforces 网页验证限制；未登录也可以下载公开题目和进行本地练习。

## 项目

| 项目 | 用途 |
| --- | --- |
| [VS Code Extension](https://github.com/acstride-labs/acstride-vscode-extension) | 做题工作区：题面、代码、测试与比赛信息 |
| [CF Tool](https://github.com/acstride-labs/acstride-cf-tool) | Codeforces API 客户端与命令行工具，承载与 Codeforces 交互的能力 |
| [Website](https://github.com/acstride-labs/acstride-web) | 产品介绍、下载入口与使用指南 |

发现问题或有改进建议，欢迎在对应项目的 Issues 中反馈。复现步骤、系统与插件版本、去除敏感信息后的日志，都能帮助我们定位问题。
